# ImageCollection
參考這篇https://tophat.top/posts/51a82223.html
把相對應的配置檔設置為github即可
```
{
  "picgo": {
    "path": ""  //默认值为 "" ，表示使用下面的“picBed”信息。 外部配置文件应该是包含以下所有“picBed”信息的JSON文件。
  },
  "picBed": {
    "current": "smms",  // 当前图片托管，默认值为“smms”
    "weibo": {          // weibo image hosting
      "chooseCookie": true, //  true | false
      "username": "",
      "password": "",
      "quality": "",  // "thumbnail" | "mw690" | "large"
      "cookie": ""
    },
    "qiniu": {    // qiniu image hosting
      "accessKey": "", // AK
      "secretKey": "", // SK
      "bucket": "", // 存储空间名称
      "url": "",    // 外链域名
      "area": "z0",   // "z0" -> 华东, "z1" -> 华北, "z2" -> 华南, "na0" -> 北美, "as0" -> 东南亚
      "options": "",  // 需要使用的七牛云中定义的样式名
      "path": ""  // 定义图片前的路径，如：images/、images/2019
    },
    "upyun": {     // upyun image hosting
      "bucket": "",
      "operator": "",
      "password": "",
      "options": "",
      "path": "",
      "url": ""
    },
    "tcyun": {    // tcyun image hosting
      "secretId": "",
      "secretKey": "",
      "bucket": "",
      "appId": "",
      "area": "",
      "path": "",
      "customUrl": "",
      "version": "v5" // "v5" | "v4"
    },
    "github": {    // github image hosting
      "repo": "",
      "token": "",
      "path": "",
      "customUrl": "",
      "branch": "",
      "username": ""
    },
    "aliyun": {    // aliyun image hosting
      "accessKeyId": "",
      "accessKeySecret": "",
      "bucket": "",
      "area": "",
      "path": "",
      "customUrl": ""
    }
  },
  "picgoPlugins": {}
}
