  compatible = "rockchip,rk3588-nvr-demo-v10\0rockchip,rk3588"
  model = "Seewo SV50"
  board = "AV.RK3588.71"
  
  nvr
  buildroot
  linux5.1


  dc5525
  usb3*2
  usb2*1
  typec*1
  wifi6
  lan*1
  poe lan*4(3*1gb+1*100m)
  hdmi out*3
  hdmi in*2
  epd*1
  nvme/sata*1
  rs485*1

  
  wb921au(mt7921au)      = wifi&bt
  rtl8111h               = eth
  lt6911c                = hdmi
  lt8911exb              = mipi
  vl817                  = usb3
  3peak t480             = rs485
  ip304a                 = 
  bl5372                 =
  sgm330a-yqs            =
  acm8625p               =
  XM25QH40BJIG           =
  gd32fces               =
  PI6C557-05BLE          =
  
  rtl8762cmf             = bt
