# git 下载
Git 是一个版本控制系统，也可以理解为一个工具，跟 Java 类似，使用之前必须先进行下载安装， Mac 笔记本上其实系统自带了 Git ，不过这里统一提供各平台的安装方式，这部分就不过多介绍，相信大家可以搞定。
- Mac：https://sourceforge.net/projects/git-osx-installer/
- Windows：https://git-for-windows.github.io/
- Linux：apt-get install git


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
