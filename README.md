# azure-learnings

### Create User
```
az ad user create --display-name developer  --password P@ssw0rd6 --user-principal-name developer@<tenant-name>.onmicrosoft.com

```

### Role Assignment
```
 az role assignment create --assignee "developer@<tanant>.onmicrosoft.com" --role contributor --scope "subscriptions/9527ff71-b027-4c3a-bece-db7852c5eed1/resourceGroups/rg-learnings"
```