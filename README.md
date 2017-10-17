# DBCourseScript
电子科技大学网络工程数据库课程实验环境配置脚本

# 使用说明
- 该脚本根据实验指导书的实验一的相关配置步骤，自动执行相关配置，减轻同学们配置的压力
- 该脚本仅支持Centos 5/6/7
- 在配置脚本之后，请跟随实验指导书第一章3.2开始使用图形界面安装Oracle Database

# 使用要求
- 需要在root用户下运行该脚本
- 需要将Oracle database 11g的安装包与该脚本放置在同一文件夹中，并且保持下载的原名称，即**linux.x64_11R2_database_1of2.zip** 和 **linux.x64_11R2_database_2of2.zip**
- 需要保持网络畅通

# 使用方法
在root用户下，在终端中切换到脚本所在文件夹，给该脚本添加执行权限，执行脚本
例如，假设脚本位于/home/abc
  ```bash
  cd /home/abc
  chmod +x install.sh
  ./install.sh
  ```

**如果有关于脚本的任何问题或者发现bug，请联系我，非常感谢**
  
 
  
