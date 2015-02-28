#Ubuntu 日积月累

>添加环境变量
>查看版本命令
>查看CPU信息：
>查看板卡信息：
>查看内存信息：
>查看USB设备：
>查看键盘和鼠标：
>查看各设备的中断请求(IRQ)：
>查看net端口




######添加环境变量
```shell
export PATH=$PATH:/usr/local/php/bin
```

######查看版本命令
```shell
sudo lsb_release -a
```
######查看CPU信息：
```shell
cat /proc/cpuinfo 
```
######查看板卡信息：
```shell
cat /proc/pci 
```
######查看内存信息：
```shell
cat /proc/meminfo 
```
######查看USB设备：
```shell
cat /proc/bus/usb/devices 
```
######查看键盘和鼠标：
```shell
cat /proc/bus/input/devices 
```
######查看各设备的中断请求(IRQ)：
```shell
cat /proc/interrupts
```
######查看net端口
```
netstat -tunlp |grep 9000
```
