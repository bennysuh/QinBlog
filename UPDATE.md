# 提供了QQ Github的三方登陆
### 2017-2-26

提供了QQ Github的三方登陆，修改UIKIT幻灯片为阻塞加载，提供更友好显示。

修复bug:
- 文章列表问题： 修复了查询SQL联表查询时group by字段写错的问题

# comment and message finished
### 2017-2-9

完成评论、留言系统，完成新消息提醒模块

cache目录统一: 将cache path变为application/common/cache

修复bug:
- 图片上传后存入的URL路径分隔符使用了系统分隔符，导致win系统的服务器图片URL被转义，现在统一改为URL分隔符“/”
- 文章页面的title显示问题 

# first version
### 2017-1-23

网站基本完成
