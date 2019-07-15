## 第三方接入推送数据的加密解密示例

推送的数据格式以JSON的方式传递，第三方接入后，拿到推送数据需要解密 `body` 字段，解析成 `JSON` 数据，推送数据结构如下（具体说明详见推送数据文档）：
```
{
  "event": "call", // 事件名
  "body": "neD0iV1eFLpIy4/F1XHFEomEfx2kV/EPMg+edO9TU/8=" // 加密后的推送数据
}
```

各个语言版本的使用详见各个语言文件夹
