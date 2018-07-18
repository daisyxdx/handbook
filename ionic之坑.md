1.每次修改ts文件或html文件后页面空白，报错：websocket connection to ws failed：error in connection establishrent:net::ERR_CONNECTION_REFURED



解决：

1.ws的版本从3.3.3改到3.3.2

```
.
.
        "ws": "3.3.2",
.
.

    "ws": {
      "version": "3.3.2",
      "resolved": "https://registry.npmjs.org/ws/-/ws-3.3.2.tgz",
      "integrity": "sha512-t+WGpsNxhMR4v6EClXS8r8km5ZljKJzyGhJf7goJz9k5Ye3+b5Bvno5rjqPuIBn5mnn5GBb7o8IrIWHxX1qOLQ==",
.
.
.
```

2.run `npm install --save` from the console

参考：https://github.com/ionic-team/ionic/issues/13668







2.创建provider报错：VM949 vendor.js:1654 ERROR Error: Uncaught (in promise): Error: StaticInjectorError[HttpClient]

解决：AppModule导入HttpClientModule





3.rxjs没有导出的成员“of”

解决：import {of} from 'rxjs/observable/of';





