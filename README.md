
|     |seewo|
| -------------- |-------------- |
|  |sv50/sv32|
| soc | rk3588 |
| ram | 8g |
| emmc | 32g |
| os | buildroot |
| usb3 | 2 |
| usb2 | 1 |
| usbc | 1 |
| hdmi out | 3 |
| hdmi in | 2 |
| edp | 1 |
| wifi&bt | 1# |
| nvme | 1# |
| sata | 2# |
| 1gb poe | 3 |
| 1gb lan | 1 |
| 100m poe | 1 |

| |
| -------------- |
|compatible = "rockchip,rk3588-nvr-demo-v10\0rockchip,rk3588"|
|model = "Seewo SV50"|
|board = "AV.RK3588.71"|


|||1#board|2#board|
| -------------- | -------------- | -------------- | ------ |
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


