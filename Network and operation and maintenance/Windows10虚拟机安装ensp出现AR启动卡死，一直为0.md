# Windows10虚拟机安装ensp出现AR启动卡死，一直为0（解决方案）



##  1.环境准备与确认

1. 首先 ，确认你的虚拟机是否是windows10，例如我的虚拟机操作系统如下：

![img](https://i-blog.csdnimg.cn/direct/46e7f76b519d46caab2699cd3cc1f3fd.png)![点击并拖拽以移动](data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==)

   2.然后，确认你的环境是否正确，重点查看VirtualBox是否是"VirtualBox-5.2.44-139111-Win"版本

## 2.上述环境配置正确，但启动AR进度一直为0，且虚拟机卡死的解决方案

在进行上述正确的环境配置下，AR启动进度为0，且虚拟机卡死，解决方案如下图所示：

点击设置

![img](https://i-blog.csdnimg.cn/direct/72002b3973254281b074d6e89a0395ab.png)![点击并拖拽以移动](data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==)

选择处理器

![img](https://i-blog.csdnimg.cn/direct/0406090925b64654b51ce5edcf37f134.png)![点击并拖拽以移动](data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==)

会看到右边出现如下图所示的虚拟化引擎，勾选前两个选项，确定，然后再次启动虚拟机运行ensp，AR就不会进度一直为0，卡死了

![img](https://i-blog.csdnimg.cn/direct/373927b671b14badb7713424abc4b984.png)![点击并拖拽以移动](data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==)

如果上述正确配置后，报错不支持虚拟化计数器，那请先进入Windows安全中心关闭内核隔离，重启，基本就没有问题了，如果还有问题，欢迎留言![img](https://i-blog.csdnimg.cn/direct/a0fb9bd583b64c49bdbc8f984ac21ea5.png)![点击并拖拽以移动](data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==)
