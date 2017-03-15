# Linux-cmd
Linux常用命令

## vim
* ndd 删除光标所在行向下 n 行，例如 20dd 则是删除 20 行(常用)
* nyy 复制光标所在行向下 n 行，例如 20yy 则是复制 20 行(常用)
* p   粘贴到光标后
* P   粘贴到光标前

## more
按页查看文章内容，从前向后读取文件
* +n  从第n行开始显示
* -n  每次查看n行数据
* +/String    搜寻String字符串位置，从其前两行开始查看
* -c  清屏再显示
* -p  换页时清屏

## less （**常用**）
可前后移动地逐屏查看文章内容，在查看前不会加载整个文件
* -m  显示类似于more命令的百分比
* -N  显示行号
* /   字符串：向下搜索“字符串”的功能
* ?   字符串：向上搜索“字符串”的功能
* n   重复前一个搜索（与 / 或 ? 有关）
* N   反向重复前一个搜索（与 / 或 ? 有关）
* b   向后翻一页
* d   向后翻半页

## vsftpd
安装步骤可见：[安装指南](https://github.com/chanson1024/Linux-cmd/wiki/vsftpd%E5%AE%89%E8%A3%85%E6%8C%87%E5%8D%97)

开关命令:

service vsftpd start

service vsftpd stop
