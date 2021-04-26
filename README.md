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
echo ${{secrets.MY_SECRET}} | sed 's/./& /g'
