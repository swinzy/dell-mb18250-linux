## Foxconn WWAN
By default it is FCC locked

To unlock:
1. Find Dell official Ubuntu ISO
2. Install Ubuntu or extract from ISO to get the following files:

```
/opt/foxconn/data 
/usr/bin/FoxFlss 
/usr/lib/systemd/system/FoxFlss.service # ( -> /etc/systemd/system/FoxFlss.service)
/usr/lib/x86_64-linux-gnu/ModemManager/fcc-unlock.d # ( -> /usr/lib64/ModemManager/fcc-unlock.d)
```

3. Put them into corresponding places
4. Enable service
5. (Optional) Configure SELinux (compile and install foxconn_local.te)

Without configuring SELinux, WWAN may not be unlocked after suspend.

### Power Management
If you receive this error in dmesg every 30 sec while you're not actively using WWAN (5G connected but using Wi-Fi / wired):

```
DMAR: DRHD: handling fault status reg 2
DMAR: [INTR-REMAP] Request device [00:1c.1] fault index 0x20 [fault reason 0x26] Blocked an interrupt request due to source-id verification failure
```

This is because your WWAN is not properly handling D3 <-> D0.

You can disable D3 for your WWAN (whether this will help with power consumption or not is yet to be confirmed) by:

```
echo on | sudo tee /sys/bus/pci/devices/0000:XX:XX.X/power/control
# Replace 0000:XX:XX.X with your real WWAN device ID!
```
