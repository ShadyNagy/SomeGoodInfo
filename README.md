# SomeGoodInfo


### Change Git User
```powershell
git config --global user.name "Full Name"
git config --global user.email "email@address.com"
```

### Angular Build With virtual Path
```powershell
ng build --prod --base-href /ServerVirtualPath/ --deploy-url /ServerVirtualPath/
```


### Github Secrets Show
```powershell
echo ${{secrets.MY_SECRET}} | sed 's/./& /g'
```

### IIS express create config
```powershell
C:\Program Files\IIS Express>"C:\Program Files\IIS Express\appcmd.exe" add s
/name:SealingService /bindings:"http/*:61800:localhost" /physicalPath:"C:\Us
sehch\Documents\Paragon\ParagonCore\servers\SealingService\SealingService"
```

Path
```powershell
C:\Users\Administrator\Documents\IISExpress\config\applicationhost.config
```

Task create for iis express
```powershell
powershell
start-process 'C:\Program Files\IIS Express\iisexpress.exe' /site:mywebsite -windowstyle Hidden -Verb RunAs
```
https://www.serverwatch.com/guides/multiple-remote-desktop-connections-on-windows-server-2016-and-windows-server-2012-page-2/

If you know assembler, you can find the functions listed below and patch their response checking

For Win7:
In WinScard.dll WinStationIsSessionRemoteable function from WINSTA
In SCartSvr.dll CheckTokenMembership function from ADVAPI32

For Win Server 2012:
In WinScard.dll WinStationGetCurrentSessionCapabilities function from WINSTA
In SCartSvr.dll CheckTokenMembership function from ADVAPI32

For Win10, Win Server 2019:
In WinScard.dll WinStationGetCurrentSessionCapabilities function from WINSTA

Don't forget:
1) restart scardsvr if needed
2) pathch both Winscard libraries from System32 and SysWoW64
3) Windows File Protection
4) different Windows subversions (e.g. Win10) can use different libraries versions, check it before copy patched libraries from other computer


### VPN
https://www.cyberciti.biz/faq/centos-8-set-up-wireguard-vpn-server/
```bash
$ sudo dkms autoinstall
```
