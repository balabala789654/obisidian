# 换源
ubuntu的源位于`/etc/apt/sources.list`中
拷贝[清华镜像源](https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu/)将其复制到`/etc/apt/sources.list`中即可
```
sudo cp /etc/apt/sources.list /etc/apt/sources.list.backup 备份官方源
sudo gedit /etc/apt/sources.list 编辑
```

# cmd
1. `sudo systemctl restart NetworkManager`或者`sudo systemctl status NetworkManager` 查看网络情况以及重启网络服务
2. `lspci` `lsmod` `lsusb` `dmesg` 查看电脑硬件


