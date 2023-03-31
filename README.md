# Auto.js-VSCodeExt

在vscode中安装`Auto.js-VSCodeExt`插件时发现原作者已经删除了这个插件，之前也没保存过visx格式的离线安装包。好在家里另一台电脑上的vscode安装过这个插件，复制过来后，简单修改下配置文件就能用。

1. 解压并复制到extensions目录
```bash
tar xf hyb1996.auto-js-pro-ext-9.0.9.tar.gz
cp -r hyb1996.auto-js-pro-ext-9.0.9 "C:/Users/$username/.vscode/extensions"
```

2. 修改`extensions.json`


在适当位置添加以下内容：
($username处根据实际情况修改)

```json
{
        "identifier": {
            "id": "hyb1996.auto-js-pro-ext",
            "uuid": "99d5196e-6c19-46b8-8b22-59e58b2d2513"
        },
        "version": "9.0.9",
        "location": {
            "$mid": 1,
            "path": "c:\\Users\\$username\\.vscode\\extensions\\hyb1996.auto-js-pro-ext-9.0.9",
            "scheme": "file"
        },
        "relativeLocation": "hyb1996.auto-js-pro-ext-9.0.9",
        "metadata": {
            "id": "99d5196e-6c19-46b8-8b22-59e58b2d2513",
            "publisherId": "9b91d20a-fe8d-4c8f-aa0f-f9349c85254f",
            "publisherDisplayName": "hyb1996",
            "targetPlatform": "undefined",
            "isApplicationScoped": false,
            "updated": true,
            "isPreReleaseVersion": false,
            "preRelease": false,
            "installedTimestamp": 1670069854571
        }
    }
```
