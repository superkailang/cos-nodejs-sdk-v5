# cos-nodejs-sdk-v5
cos-nodejs-sdk-v5 解决服务器上传文件Bug

# Bug
1, base.js 中 getService()  options.Protocol undefined 有两处
2, util.js 中 getFileSize() util.isBrowser  判断出错 
