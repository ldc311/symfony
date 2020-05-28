**symfony:**
	PHP的开发框架
为什么看？
	*Drupal*使用


#《洪大师带你解读Symfony 2框架》
（老师很牛，洪涛现任携车网 CTO，喜好技术研究和分享，曾受邀参加多个技术大会。从2009年开始接触Symfony并使用至今，曾在慕课网制作了《洪大师带你解读Symfony2框架》系列视频课程。）
https://www.imooc.com/learn/244

#《Symfony 5 的迷人发展》
https://www.bilibili.com/video/BV18E411g7gd?p=1
英文字幕
https://symfonycasts.com/screencast/symfony/setup

#《用symfony和vue搭建后台管理系统》
https://study.163.com/course/courseLearn.htm?courseId=1209488845

**symfony安装**
#symfony安装，install Symfony CLI
https://symfony.com/download
#Visual C++ Redistributable for Visual Studio 2015依赖
https://www.microsoft.com/zh-CN/download/details.aspx?id=48145
#下载PHP安装包,解压到symfony的安装目录
https://windows.php.net/download

#安装composer（安装的时候要选择php.exe的位置）
https://www.jianshu.com/p/ab553e38912d
配置阿里云镜像
composer config -g repo.packagist composer https://mirrors.aliyun.com/composer/
php.ini修改 extension=php_openssl.dll

**创建项目**
 composer create-project symfony/website-skeleton my_project_name
直接用
**启动服务**
进入项目目录，运行
symfony serve
浏览器可以访问http://127.0.0.1:8000/

**路由**
composer require annotations（安装出错， Could not find package annotations. ）