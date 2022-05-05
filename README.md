基于flask前后端分离的租房网站  
框架：flask  
依赖包：ihome_freeze.txt 
完成功能：用户系统，房屋系统，订单系统，第三方支付  
使用工具：nginx, celery, redis, MySQL, Gunicorn, 第三方图片存储 
部署：使用nginx处理静态文件与页面，使用nginx负载均衡服务器分发动态请求给gunicorn+flaskapp
