# svnpack，配置文件说明

================================
svntype can be  http,svn,file
	
	http(https/http) ,svn(svn/svn+ssl) ,file(file:///D:/locole/)
  
================================
svntype=http
===========================================
	需要匹配文件的路径	

	svnurl	: 地址(获取到的版本库的路径)
	classurl: 最新版本编译后的class所在的路径

===========================================
svnurl=https://xxx/svn/xxx/
classurl=D:\\tomcat-8.0.28\\wtpwebapps
=========================
snv username 
password for user name
=========================
uname=xxxx
passwd=xxxxx
=================================
项目名称（需要打包的项目名称）
startvision--需要比对两个版本的开始版本号
endvision-结束版本号
=================================
proName=projectName
startvision=6944
endvision=7064
===============================================
需要获取的svn操作的类型包括，每个操作用“,”号分割。
	1.added 
	2.modified
	3.deleted
	4.replaced
	5.missing

===============================================
opertype=modified,added,
=====================================
项目类型有（J2EE,JAME，MAVEN）暂时支持J2EE

=====================================
protype=MAVEN
===========================
 设置zip包生成的路径目录
(指定zip包的生成路径,如果不填的话在当前项目中打zip包)
 eg:zipPath=d://
===========================
zipPath=d\://