# Software
manage software


# sourcetree 下载
https://www.sourcetreeapp.com/

# SourceTree windows版本免注册免登陆使用方法：
**在目录C:\Users\{youruser}\AppData\Local\Atlassian\SourceTree 下创建文件accounts.json ，注意：{youruser}需要替换为登录系统用户名。**
```
[
  {
    "$id": "1",
    "$type": "SourceTree.Api.Host.Identity.Model.IdentityAccount, SourceTree.Api.Host.Identity",
    "Authenticate": true,
    "HostInstance": {
      "$id": "2",
      "$type": "SourceTree.Host.Atlassianaccount.AtlassianAccountInstance, SourceTree.Host.AtlassianAccount",
      "Host": {
        "$id": "3",
        "$type": "SourceTree.Host.Atlassianaccount.AtlassianAccountHost, SourceTree.Host.AtlassianAccount",
        "Id": "atlassian account"
      },
      "BaseUrl": "https://id.atlassian.com/"
    },
    "Credentials": {
      "$id": "4",
      "$type": "SourceTree.Model.BasicAuthCredentials, SourceTree.Api.Account",
      "Username": "username@email.com"
    },
    "IsDefault": false
  }
]
```
