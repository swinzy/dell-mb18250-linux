# Linux on Dell Pro Max 18 Plus (MB18250)

> [!NOTE]
> **Dell MB18250 is an officially supported Linux laptop (via Dell OEM Ubuntu 24.04 LTS).**<br>This repository is for users who do not want to use OEM Ubuntu.
>
> If you do not care what distro you use and just want everything to work out-of-the-box, use an official Dell Ubuntu installation, and everything will "just work".

> [!CAUTION]
> **USE THIS REPOSITORY AT YOUR OWN RISK!** <br>
> Any guide, especially code, in thie repository may be subject to a specific environment, or it may even cause unexpected concequences. I am not affiliated with Dell or any vendor of its hardware.<br>
> Make sure you know what you are doing and proceed with care.

> [!TIP]
> If you have any questions, feel free to use the "Discussion" feature to reach out! Have fun!

## My Specs:
- CPU: Intel Core Ultra 7 265HX
- RAM: 1x128GB 6400MT/s CAMM2 Dual Channel, non-ECC
- GPU: NVIDIA RTX PRO 5000 Blackwell 24GB
- WWAN: 5G Qualcomm Snapdragon DX72 with e-SIM
- Display: QHD+ LCD 2560x1600, non-touch + IR camera
- Palmrest: Finger print reader + smart card + NFC + Control Vault 3+
- Factory-installed OS: Ubuntu 24.04 LTS OEM
- OS: Fedora 43 (as-of March 2026)

<details>

<summary>Full specs (for nerds)</summary>

```csv
Component,Part Number,Description,Quantity
"817-BBXG : ""Not selected in this configur ation"" Label","W21JJ","INFO,GNRC,OEM,TRACKING,PN","1"
"817-BBBN : NO RAID","00009","Information,Generic,Part      Number","1"
"817-BBBB : Custom Configuration","W21JJ","INFO,GNRC,OEM,TRACKING,PN","1"
"658-BFWT : Ubuntu Dell Pro Max Laptops","H781T","INFO,GO-TO-AHCI","1"
"","G156K","INFO,NSRS,SET AHCI,OPTI","1"
"","XP1N9","INSTR,UBUNTU CLIENT OS","1"
"","WT4RH","INFO,RYLTY,UBT,LIC,DELLPROMAX","1"
"650-BBBG : No Intel Connectivity Performa nce Suite","73K1G","INFO,ICPS,OPT-OUT","1"
"650-AAAM : No Anti-Virus Software","T5D0W","INFO,NO ANTI-VIRUS SW","1"
"631-BCJY : Intel vPro Enterprise Technolo gy Enabled","VY54T","INFO,MGMT,INTEL,VPRO","1"
"","H738F","LBL,STNG,MGMT,AMT/VPRO,1","1"
"","00HG8","SRV,SWME19P0,KINGDA","1"
"","H9WWN","INFO,RYLTY,ME,VPRO,KINGDA","1"
"631-BBZB : No Factory Install Language So ftware","YK34V","INFO,PLACEHOLDER,PIECE-PART","1"
"630-AAPK : No Productivity Software","864KE","Information,PLACEHOLDER       PIECE-PART","1"
"620-AALW : OS-Windows Media Not Included","864KE","Information,PLACEHOLDER       PIECE-PART","1"
"605-BBPV : Ubuntu 24.04 LTS (Long Term Su pport)","7RXM1","INFO,ESP-ADDR,100","1"
"","X0601","INFO,BYPS,UPTN","1"
"","0616F","INFO,BOOT,GPT,OVERRIDE","1"
"","DP1FF","INFO,SECUREBOOT,ENABLE","1"
"","01YT5","INFO,HEVC,PRESENT","1"
"","DXJP5","INFO,LINUX,SET MODE TPM2.0","1"
"","XP9T9","INFO,BOOT,CNTNR,GPT","1"
"","57154","Service Charge,Software,      Windows 98,Fully Integrated   System Test","1"
"","YX48R","SRV,SW,OS,UBUNTU24.04,FI","1"
"","YJH1C","INFO,LNX,DISABLE,LGCY,OPROM","1"
"","9472R","Information,Software,Linux-   Partition","1"
"583-BMQF : English US backlit Copilot key  keyboard with numeric keypad","R9T05","INFO,KYBD,BLIT,XLOB","1"
"","P30CW","KYBD,99,US,ENG,M24IXU-BS","1"
"556-BGGS : WWAN 5G Qualcomm Snapdragon X7 2 with E-Esim","C6YHV","INFO,COMMS,MMB,WWAN,MSFT","1"
"","43PRR","SRV,XHTML,MBLBB,DW5934E","1"
"","PDKVN","SRV,E-LBL,DW5934E,SAB,CITC","1"
"","J98PM","LBL,REG,MBLBB,DW5934E,E2K","1"
"","PTNW2","MDM,WRLES,DW5934E,5G","1"
"","02PY8","INFO,WWAN,ESIM,ORDER","1"
"","WCW8D","LBL,REG,WWAN,IMEI","1"
"","187R6","SRV,DRVR,DW5934E,KDK ARLHX 18","1"
"","19TP4","INSTR,ESIM,EMBEDDED,WWAN","1"
"","7YPNW","INFO,RYLTY,ERICSSON,5G WWAN,PC","1"
"555-BMWM : Intel BE200 WLAN Driver with B luetooth","XMDVP","SRV,DRVR,WRLES,M2,BE200,KDK18","1"
"","D6J6N","SRV,DRVR,WRLES,BT,BE200,KDK18","1"
"","VNFG5","SRV,HTML,WRLES,INTEL,BE200","1"
"555-BMSL : Intel Wi-Fi 7 BE200 Wireless C ard","22V2Y","LBL,REG,WRLES,BE200,WW","1"
"","DT7J9","CRD,WRLES,M.2,INTEL,BE200,WW","1"
"492-BFFX : 280W AC adapter, USB Type C","F9FR7","ADPT,AC,280W,LTON,TYPEC,LIANO","1"
"490-BKYQ : NVIDIA RTX PRO 5000 Blackwell 24GB GDDR7","NWP3T","CBL,FPC FXBM-X126F043A,MB1X250","1"
"","YRV12","SRV,SW,DRVR,NV,WIN32UX","1"
"","HVTGX","ASSY,HTSNK,DGFF2,MB18250","1"
"","9VN2G","ASSY,FAN,UMA/DIS,MB18250","1"
"","P83G7","CRD,GRPHC,NV,WN22-X11,DGFF2","1"
"","H63J6","SRV,SW,DRVR,NV,WN22-X11","1"
"","H75JR","CBL,FPC,FXBM-X126F043B,MB1X250","1"
"451-BDMS : 6 cell, 96Whr, ExpressCharge(T M) Capable, Long Life Cycle ba ttery, 3-year warranty","X7JKK","INSTR,LCL,LONGLIFE,BATTRY","1"
"","KX3ND","INFO,LCL,LONGLIFE BATTERY, NEW","1"
"","6DCG2","BTRY,PRI,96WHR,6C,LITH,COSMX","1"
"450-ALFS : E5 Power Cord 1M for Australia /New Zealand","DMDFW","CORD,PWR,2.5A,1M,C5,E5,PP,AUS","1"
"409-BCZB : Intel(R) Rapid Storage Technol ogy Driver","9D219","SRV,DRVR,APP,INTL,IRST,MB1X250","1"
"401-AAGM : No Additional Hard Drive","W21JJ","INFO,GNRC,OEM,TRACKING,PN","1"
"400-BTMB : 512GB Performance SSD Gen4, SE D Ready,TLC","55D30","SSDR,512G,OP2,G44,80S2,XG10D","1"
"","2HMFM","INFO,C DRIVE,PCIESSD","1"
"391-BKCR : 18"" QHD+ LCD 2560x1600 with 50 0 nits, DCI-P3 100%, Non-Touch , WLAN+WWAN, IR camera, Microp hone","5D83R","BRKT,FOR WWAN ANT,MB18250","1"
"","4XYFH","INFO,MDIAG,SABRE,WBT CHECK","1"
"","5GKR3","ASSY,LCD,H,Q,IR,WWAN,MB18","1"
"","HCC9J","INFO,SWSI,LCD,18.0,NON-TCH","1"
"","WG17P","SRV,SW,WALLPAPER,N,QHD+LOGO","1"
"","25W60","INFO,IR CMRA,FOR WBT CHECK","1"
"389-FGBC : Intel Core Ultra 7 Processor L abel","25PYN","LBL,INTEL,CU7,14,ULTRA,SMALL","1"
"389-DVNR : Not EPEAT Registered","W21JJ","INFO,GNRC,OEM,TRACKING,PN","1"
"389-BCGW : No UPC/EAN Label","2CVKK","INFO,NO,UPC/EAN,LBL","1"
"387-BBDO : Not ENERGY STAR Qualified","864KE","Information,PLACEHOLDER       PIECE-PART","1"
"379-BGKP : Intel(R) Core(TM) Ultra 7 proc essor 265HX, 55W vPro","W21JJ","INFO,GNRC,OEM,TRACKING,PN","1"
"370-BDFD : 128GB: 1x128GB 6400MTs CAMM2 D ual Channel, non-ECC","7N1WY","ASSY,CON,DIMM/D-CAMM,MB1X250","1"
"","PX69W","CRD,MEM,128GB,DC,6400,CAMM2","1"
"","30H47","PLT,THRM2,CAMM,SINK,MB1X25","1"
"","DP2MY","BRKT,FOR,D-CAMM,WO/R,B,MB1X250","1"
"","6KG8F","PLT,THRM1,CAMM,MB1X25","1"
"","1FK7X","INFO,CAMM MEMORY,M-DIAG","1"
"346-BMKG : Palmrest with Finger Print Rea der + Smart Card + NFC + Contr ol Vault 3+","185D2","INFO,SC,CONTACT","1"
"","RGRRR","LBL,NBK,NON-FIPS FPR,MB1X250","1"
"","4WM5C","LBL,REG,NFC STKR,52X36,TRSP","1"
"","CGDM9","INFO,RYLTY,NFC,CHIP","1"
"","0XDTD","INFO,RFID,PALMREST","1"
"","1XWFN","INFO,RYLTY,CV,KLC,PLTFRM","1"
"","F5PK5","ASSY,PLMRST,FP/SC/NFC,MB18","1"
"","P67K7","LBL,REG,NBK,RFID,WW,MB1X250","1"
"","YR93R","SRV,DRVR,USH,MB1X250","1"
"","DHTHW","CBL,FOR USH BRD,MB18250","1"
"","J7D02","INFO,RYLTY,BRCM,CV3,FP+SC/FS","1"
"","WCRND","INFO,MDIAGS,USH FW FLASH","1"
"","H1M32","INFO,APP, NFC","1"
"","R161G","INFO,RYLTY,DCPSC,HIDGBL,XLOB","1"
"340-DXMC : Dell Pro Max Laptop Packaging","G47TK","SHP MTL,BG,18,435X406,RC,LDPE","1"
"","6DC41","SHP MTL,PAD,KYBD,KGKA,18","1"
"","HJ0DK","SHP MTL,PPR SEAL,MAINST,16-17","1"
"","GYRFG","SHP MTL,DOC,BAND,240X40","1"
"","KR8M7","LBL,REG,COO,CKS,280W,MB18250","1"
"","Y31DH","KIT,SHP MTL,OVPK,ENH,KGKA,18","1"
"","2J81W","INFO,MIN-CONFIG,NB,BIZ,DAO","1"
"","Y364G","INFO,DIRSHP,CMPL,KUNSHAN","1"
"","864KE","Information,PLACEHOLDER       PIECE-PART","1"
"340-DXCS : Quick Setup Guide for Dell Pro  Max 18 Plus","97C0J","PLCMT,MB18250,DELL PRO MAX,WW","1"
"340-CKSZ : No AutoPilot","W21JJ","INFO,GNRC,OEM,TRACKING,PN","1"
"340-AFGK : Australia and New Zealand Warr anty Tech Sheet","J8NF0","TSH,WSI,ENG,AUS","1"
"340-ACBS : Document for MUI (English, Khe mer, Bahasa Indonesia, Arabic,  Spanish)","4N89R","GDE,PROD,MUI,SERI,APCC","1"
"329-BLKQ : Intel(R) Core(TM) Ultra 7 265H X","X4N2V","CBL,BATTERY,MB1X250","1"
"","6T462","LBL,REG,AIO,170X11,BLANK","1"
"","Y6GJC","BRKT,EDP,MB18250","1"
"","JDMYG","ASSY,BRKT,WLAN,MB18250","1"
"","VR9FG","PWA,PLN,MS3,U7,V,DS,MB18250","1"
"","G0MCT","ASSY,FRM,INNER FRM,MB18250","1"
"","6HY70","ASSY,BASE,MB18250","1"
"321-BMDT : Dell Pro Max 18 Plus Bottom Do or","9GYTV","ASSY,DOOR,MB18250","1"
"319-BBLZ : 8MP IR with USB Synapctics Cam era, HDR with UPD ready, TNR5","YK34V","INFO,PLACEHOLDER,PIECE-PART","1"
"210-BRXJ : Dell Pro Max 18 Plus (MB18250)  XCTO Base","1VC62","SRV,OS,W11,MEP,INTEL,ARL","1"
"","991D1","SRV,SW,ISS5P6,KINGDA","1"
"","H82C5","INFO,HASH,ENABLE,VERIFY,RGD","1"
"","K5NGT","SRV,DRVR,INTL,PMT,MB1X250","1"
"","PHJFR","INFO,RYLTY,INSYDE,AGS,BIOS,NBK","1"
"","9JTWW","SRV,DRVR,AUDIOTRINITYTB16,WD15","1"
"","H1R74","INFO,INTEL,SW,ISS3P0,XLOB","1"
"","TVCJ7","SRV,DRVR,LAN,TRINITY,TB16","1"
"","1HCYJ","SRV,APP,INTEL,TBT,MB1X250","1"
"","WXM2C","SRV,BIOS RECOVERY 2","1"
"","9MV2C","SRV,SW,AUD,MB1X250","1"
"","XPRGW","INFO,UEFI-CL3","1"
"","MV1F1","SRV,DRVR,INTEL,LAN,MB1X250","1"
"","5TCXK","INFO,CODEC,CPU,CHECK","1"
"","GWK5X","INFO,MYDELL,DEP QR CODE,PKG","1"
"","NX0Y6","SRV,DRVR,INTL,NPU,MB1X250","1"
"","8MWHP","SRV,DRVR,LINUX,MB1X250","1"
"","D3GG1","INFO,SWSI,NB,STD,PM,MB18250","1"
"","56YDJ","INFO,MYDELL,DEP QR CODE,SYS","1"
"","J8PH2","INFO,CHAIN,CUSTODY","1"
"","01YT5","INFO,HEVC,PRESENT","1"
"","WX4P1","SRV,SW,FISH,WBI OPTIMIZATION","1"
"","N6RX7","SRV,SCPC,CHECK","1"
"","KNYCD","INFO,WIN,ADCNTDSTBY,DCMOD","1"
"","33MP4","INFO,SVC TAG,EMEA LOGISTIC","1"
"","W07TN","INSTR,REG,E-LBL,BIOS,MB1X250","1"
"","GK9XK","SRV,DRVR,INTL,HID,MB1X250","1"
"","XVP8C","SRV,DRVR,TBT,MB1X250","1"
"","57154","Service Charge,Software,      Windows 98,Fully Integrated   System Test","1"
"","5JCXP","SRV,DRVR,CHIPSET,MB1X250","1"
"","4P9FX","INFO,HASH,BIOS","1"
"","HMGJW","SRV,WIN10/11,ALS,ON","1"
"","FKGV4","SRV,DRVR,INTL,IPF,MB1X250","1"
"","15W8J","SRV,SW,INTL,UMA,MB1X250","1"
"","T3C54","SRV,SW,SERIAL IO,MB1X250","1"
"","2RGHR","SRV,DRVR,DTT,MB1X250","1"
"","G6MPX","INFO,SW,MS,SCPC,CHECK,UEFI","1"
"","HP6JJ","INFO,WIN,ADCNTDSTBY,ACMODE","1"
"","C5R7K","SRV,SW,MEM-CARD,MB1X250","1"
"","GHVV5","INFO,SW,MS,SCPC,CHECK,TXT","1"
"","K10MK","SRV,DRVR,BARLOW RIDGE,MB1X250","1"
"","6GHHV","SRV,DRVR,INTL PPM,W11,MB1X250","1"
```

</details>

## What's Working
*\*on Fedora 43 Workstation*
| Component                                 | Working                     | Note                                                             |
|-------------------------------------------|-----------------------------|------------------------------------------------------------------|
| Boot with vanilla kernel                  | :white_check_mark:          |                                                                  |
| Secure Boot with vanilla kernel           | :white_check_mark:          |                                                                  |
| Display (max resolution and refresh rate) | :white_check_mark:          |                                                                  |
| NVIDIA GPU                                | :white_check_mark::warning: | Driver installs, performance untested                            |
| Wi-Fi                                     | :white_check_mark:          |                                                                  |
| WWAN (5G)                                 | :white_check_mark::warning: | Additional steps required. See [/wwan/README.md](wwan/README.md) |
| Bluetooth                                 | :white_check_mark:          |                                                                  |
| Keyboard                                  | :white_check_mark:          |                                                                  |
| Touchpad                                  | :white_check_mark:          |                                                                  |
| Audio                                     | :white_check_mark:          |                                                                  |
| Microphone                                | :white_check_mark:          |                                                                  |
| Modern Standby / Suspend (S0ix / s2idle)  | :white_check_mark:          |                                                                  |
| Camera                                    | :white_check_mark:          |                                                                  |
| IR camera                                 | Not tested                  |                                                                  |
| Fingerprint                               | :warning:                   | Only works in OEM Ubuntu. Port to Fedora WIP                     |
| Battery report and charging               | :white_check_mark:          |                                                                  |
| Thunderbolt + DP alt mode                 | :white_check_mark:          |                                                                  |
| SD card reader                            | Not tested                  |                                                                  |
| Smart card reader                         | :white_check_mark:          |                                                                  |
| NFC                                       | Not tested                  |                                                                  |
| Ambient light sensor                      | :warning:                   | Only works in OEM Ubuntu. Port to Fedora WIP                     |
| 3.5mm                                     | Not tested                  |                                                                  |
| HDMI                                      | Not tested                  |                                                                  |
| RJ45                                      | Not tested                  |                                                                  |
