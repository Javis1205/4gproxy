The tool is not requeid for using allproxy.

## clientUtilities
You can use clientUtilities to do IP reset for Huawei E3372/E8372/E3276, the valid command formt is

```
clientUtilities -deviceMode e3372 -params $IP
or
clientUtilities -deviceMode e8372 -params $IP#user#password
```

if you want to do reboot:

```
clientUtilities -deviceMode e8372 -params $IP#user#password -command reboot
or
clientUtilities -deviceMode e3372 -params $IP -command reboot
```

## setDHCP.exe (For windows only)
A tool which can change the DHCP of huaweiE3372
## proxyTester (For windows only)
A tool which supports http and socks5 proxy verification

## wpa_cli
Android wifi debug tool