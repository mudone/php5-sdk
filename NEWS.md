## CHANGE LOG

### v3.2.1

allow images uploaded auto-orient.

允许图片上传成功后自动旋转。

参考：

1. [[API] multipart/form-data 上传文件之 action 字段详解](http://docs.qiniutek.com/v3/api/io/#upload-action)
2. [[SDK] QBox_RS_UploadFile() 方法中的参数增加了 :rotate 选项](http://docs.qiniutek.com/v3/sdk/php5/#upload-server-side)

### v3.2.0

2012-11-06

allow files uploaded auto callback some APIs (like imageInfo, exif, etc…), and add those APIs callback results as part of the custom data for POST biz-server.

允许上传文件(图片)成功后执行回调指定的 API (比如 imageInfo, exif 接口等)，并将指定API的回调结果一并 POST 发送给客户方的业务服务器。

参考：

1. [[API] 生成上传授权凭证 uploadToken 之 escape 参数详解](http://docs.qiniutek.com/v3/api/io/#escape-expression)
2. [[SDK] QBox_MakeAuthToken() 方法中的参数增加了 :escape 选项](http://docs.qiniutek.com/v3/sdk/php5/#generate-upload-token)