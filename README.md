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
