# Lenovo-3070-Ubuntu20.04
Process to configure my computer

## update kenel to 5.14.0 by apt-get-install
    sudo apt-get upgrade linux-headers-5.14.0-1020-oem
    sudo apt-get upgrade linux-image-5.14.0-1020-oem
   
## wget x201 wifi driver
    wget -c https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/snapshot/linux-firmware-main.tar.gz
    tar -zxvf linux-firmware-main.tar.gz
    cp iwlwifi-*.ucode /lib/firmware
    https://www.cnblogs.com/Boxiang-Zhang/p/15706482.html
    
## nvidia 5.10 
    https://blog.csdn.net/weixin_55749979/article/details/122694538
  
  
## 输入法
    https://blog.csdn.net/qq_33973712/article/details/120234707

## miniconda 
    ./Miniconda3-4.6.14-Linux-x86_64.sh
## terminator
    sudo apt-get install terminator
## mirrors
    http://mirrors.sustech.edu.cn/

## ros
    http://mirrors.sustech.edu.cn/help/ros.html#introduction

## realsense
    https://github.com/IntelRealSense/realsense-ros

## ubuntu 2 windows FTP
    https://blog.csdn.net/qq_42688495/article/details/123254289
