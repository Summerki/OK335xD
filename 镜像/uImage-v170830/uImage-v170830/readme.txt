2017-08-30：增加4G模块支持

更新内核操作如下：
将uImage 拷贝到ARM板卡系统中，在uImage当前目录下执行如下操作：
dd if=uImage of=/dev/mmcblk0 seek=2048 && sync && sync



