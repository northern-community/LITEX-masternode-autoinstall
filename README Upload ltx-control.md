# LITEX

Shell script to upload your previous ltx-control.sh. Use it on your own risk.




## VPS

```
wget https://raw.githubusercontent.com/Simo190/LITEX-masternode-autoinstall/master/Upload_Ltx-control.sh && bash Upload_Ltx-control.sh
```

## Usage control script:

```
./ltx-control.sh -[argument]

-a start LITEX service
-b stop LITEX service
-c status LITEX service
-d checks the autostart of the LITEX service when the server is starting
-e masternode sync status
-f masternode status
-h help - usage for this script
-k firewall status
-l show ltx.conf
-m show firewall log
-n getinfo
-o getblockcount
-p getpeerinfo
