
|||
| -------------- |-------------- |
|sv50/sv32||
|ram|lp4x 4g*2|
|emmc|32g|

||
| -------------- |
|compatible = "rockchip,rk3588-nvr-demo-v10\0rockchip,rk3588"|
|model = "Seewo SV50"|
|board = "AV.RK3588.71"|


/ # cat /etc/os-release
NAME=Buildroot
VERSION=linux-5.10-gen-rkr3.1-71-g7a86348704
ID=buildroot
VERSION_ID=2021.11
PRETTY_NAME="Buildroot 2021.11"
BUILD_INFO="slave@lubo-server Wed Nov 15 23:22:04 CST 2023 - /home/slave/ci/workspace/lubo/kdl_rk3588_sdk_test/buildroot/configs/rockchip_rk3588_defconfig"

/ # cat /proc/version
Linux version 5.10.66-ab28 (slave@lubo-server) V3.23.8111523.1065642_26adabcb657d_VBoard (aarch64-none-linux-gnu-gcc (GNU Toolchain for the A-profile Architecture 10.3-2021.07 (arm-10.29)) 10.3.1 20210621, GNU ld (GNU Toolchain for the A-profile Architecture 10.3-2021.07 (arm-10.29)) 2.36.1.20210621) #2 SMP Wed Nov 15 23:18:32 CST 2023

/ # cat /etc/redhat-release
cat: /etc/redhat-release: No such file or directory

/ # lsb_release -a 
sh: lsb_release: command not found

/ # uname -a
Linux SV32 5.10.66-ab28 #2 SMP Wed Nov 15 23:18:32 CST 2023 aarch64 GNU/Linux









|||1#board|2#board|
| -------------- | -------------- | ------ | ------ |
|wb921au(mt7921au)| wifi&bt|✔|X|
|rtl8762cmf|bt|X|✔|
|rtl8111h|10/100/1000M|✔|✔|
|lt6911c|HDMI1.4/DP++MIPI DSI/CSI/LVDS|✔|✔|
|lt8911exb|MIPI? DSI/CSI to eDP|✔|✔|
|vl817|USB 3.1 Gen1 Hub|✔|✔|
|3peak t480|rs485|✔|✔|
|ip804a|PoE PSE IC|✔|✔|
|bl5372|RTC|✔|✔|
|sgm330a-yqs||✔|✔|
|acm8625p||✔|✔|
|XM25QH40BJIG||✔|✔|
|gd32fces||✔|✔|
|PI6C557-05BLE||✔|✔|


