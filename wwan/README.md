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
