# Sword

+ WordPress

  WordPress用户名检测、登录密码暴破。直接点击`Crack`不会自动获取网站用户名并进行暴破，而是从`UserName`获取用户名，如果为空就会获取用户再暴破。Thead不建议修改。

  ![](./images/wp.bmp)

+ Liferay

  CVE-2020-7961的漏洞利用，包括漏洞检测（执行一个命令）、命令执行、GetWebShell、上传自定义WebShell、MSF ReverseShell。
  
  ![](images/Liferay.png)
  
+ phpMyAdmin

  phpMyAdmin暴破，可检测版本。

  ![](./images/phpMyAdmin.png)

+ Drupal
  
  CVE-2018-7600漏洞利用，包括命令执行、GetWebshell。
  
  ![](./images/Drupal.png)
  
+ Tomcat
  
  tomcat密码暴破，注意：tomcat高于7版本默认会有防暴破机制，在5分钟之内同一账户登陆失败5次以上，但是返回包里面没有异常。

  ![](./images/tomcat.png)

+ IIS6
  
  CVE-2017-7269，iis6 webdav远程代码执行漏洞扫描、ReverseShell、shellcode执行。

  ![](./images/iis6_webdav.bmp)