|name1|status|name2|
| -------------- | -------------- | -------------- |
csi2-dcphy0|disabled
csi2-dcphy1|okay
csi2-dphy0|disabled
csi2-dphy1|disabled
csi2-dphy2|disabled
route-dp0|disabled
route-dsi0|okay
route-dsi1|disabled
route-edp0|disabled
route-edp1|disabled
route-hdmi0|okay
route-rgb|disabled
route-dp1|okay
route-hdmi1|okay
dmc|disabled
jpege-ccu|okay
mpp-srv|okay
rkcif-dvp|disabled
rkcif-dvp-sditf|disabled
rkcif-mipi-lvds|disabled
rkcif-mipi-lvds-sditf|disabled
rkcif-mipi-lvds-sditf-vir1|disabled
rkcif-mipi-lvds-sditf-vir2|disabled
rkcif-mipi-lvds-sditf-vir3|disabled
rkcif-mipi-lvds1|okay
rkcif-mipi-lvds1-sditf|disabled
rkcif-mipi-lvds1-sditf-vir1|disabled
rkcif-mipi-lvds1-sditf-vir2|disabled
rkcif-mipi-lvds1-sditf-vir3|disabled
rkcif-mipi-lvds2|disabled
rkcif-mipi-lvds2-sditf|disabled
rkcif-mipi-lvds2-sditf-vir1|disabled
rkcif-mipi-lvds2-sditf-vir2|disabled
rkcif-mipi-lvds2-sditf-vir3|disabled
rkcif-mipi-lvds3|disabled
rkcif-mipi-lvds3-sditf|disabled
rkcif-mipi-lvds3-sditf-vir1|disabled
rkcif-mipi-lvds3-sditf-vir2|disabled
rkcif-mipi-lvds3-sditf-vir3|disabled
rkisp0-vir0|disabled
rkisp0-vir1|disabled
rkisp0-vir2|disabled
rkisp0-vir3|disabled
rkisp1-vir0|disabled
rkisp1-vir1|disabled
rkisp1-vir2|disabled
rkisp1-vir3|disabled
rkispp0-vir0|disabled
rkispp1-vir0|disabled
rkvenc-ccu|okay
rockchip-suspend|okay
usbdrd3_0|okay
usbhost3_0|okay
rgb|disabled
power-controller|okay
# 节点名称和地址列表

## 主要硬件节点
gpu@fb000000 | okay | gpu
usb@fc000000 | okay | usb_host0_xhci
usb@fc800000 | okay | usb_host0_ehci
usb@fc840000 | okay | usb_host0_ohci
usb@fc880000 | okay | usb_host1_ehci
usb@fc8c0000 | okay | usb_host1_ohci
iommu@fc900000 | disabled | mmu600_pcie
iommu@fcb00000 | disabled | mmu600_php
usb@fcd00000 | okay | usb_host2_xhci
pwm@fd8b0000 | disabled | pwm0
pwm@fd8b0010 | okay | pwm1
pwm@fd8b0020 | disabled | pwm2
pwm@fd8b0030 | disabled | pwm3
npu@fdab0000 | okay | rknn_core_0
iommu@fdab9000 | okay | rknn_mmu_0
vepu@fdb50000 | disabled | vpu121
vdpu@fdb50400 | okay
iommu@fdb50800 | okay | vpu121_mmu
rga@fdb60000 | okay
rga@fdb70000 | okay
rga@fdb80000 | okay | rga
jpegd@fdb90000 | okay
jpege-core@fdba0000 | okay | vepu121_0
iommu@fdba0800 | okay | vepu121_0_mmu
jpege-core@fdba4000 | okay | vepu121_1
iommu@fdba4800 | okay | vepu121_1_mmu
jpege-core@fdba8000 | okay | vepu121_2
iommu@fdba8800 | okay | vepu121_2_mmu
jpege-core@fdbac000 | okay | vepu121_3
iommu@fdbac800 | okay | vepu121_3_mmu
iep@fdbb0000 | okay
rkvenc-core@fdbd0000 | okay
rkvenc-core@fdbe0000 | okay
rkvdec-ccu@fdc30000 | okay
rkvdec-core@fdc38000 | okay
rkvdec-core@fdc48000 | okay
av1d@fdc70000 | disabled
rkisp-unite@fdcb0000 | disabled
rkisp@fdcb0000 | disabled
rkisp-unite-mmu@fdcb7f00 | disabled
rkisp@fdcc0000 | disabled
rkispp@fdcd0000 | disabled
rkispp@fdcd8000 | disabled
mipi0-csi2@fdd10000 | disabled
mipi1-csi2@fdd20000 | okay
mipi2-csi2@fdd30000 | disabled
mipi3-csi2@fdd40000 | disabled
vop@fdd90000 | okay | vop
spdif-tx@fddb0000 | disabled | spdif_tx2
i2s@fddc0000 | disabled | i2s4_8ch
spdif-tx@fdde0000 | disabled | spdif_tx3
i2s@fddf0000 | okay | i2s5_8ch
i2s@fddfc000 | disabled | i2s9_8ch
spdif-rx@fde08000 | disabled
dsi@fde20000 | okay | dsi0
dsi@fde30000 | disabled | dsi1
hdcp@fde40000 | disabled
dp@fde50000 | disabled | dp0
hdcp@fde70000 | disabled
hdmi@fde80000 | okay | hdmi0
edp@fdec0000 | disabled | edp0
dfi@fe060000 | disabled
pcie@fe180000 | disable | pcie2x1l1
pcie@fe190000 | okay | pcie2x1l2
ethernet@fe1c0000 | okay | gmac1
sata@fe210000 | disabled | sata0
sata@fe230000 | disabled | sata2
spi@fe2b0000 | disabled | sfc
mmc@fe2c0000 | disabled | sdmmc
mmc@fe2d0000 | disabled | sdio
mmc@fe2e0000 | okay | sdhci
crypto@fe370000 | disabled
rng@fe378000 | okay | rng
i2s@fe470000 | okay | i2s0_8ch
i2s@fe480000 | okay | i2s1_8ch
i2s@fe490000 | disabled | i2s2_2ch

