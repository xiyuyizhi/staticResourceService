# staticResourceService
##node实现的静态资源服务##
*加入缓存及开启gZip*

*test目录为对node服务中的资源的引用测试*
 1.*使用gulp-rev等相关插件来生成资源的hash文件名及cdn地址的替换*
 2.*使用ftp协议部署资源到node服务目录*
 3.*gulp之后对于内容没有更改（及文件名不变）的文件过滤掉，不上传到node服务目录下*

