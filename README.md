# 天迪-3567D-ELSYK-M8188SEHackintosh-OC 0.88

适合工控主板 七代 hd620 无法关闭csm 无法设置dvmt


天迪3567D。ELSYK M8188SE

CPU。I5-7300U
内存 板载8G
网卡 英特尔 8265AC、
声卡 ALC662
有线网卡 8111


12 monterey。4k 正常显示。蓝牙 无线网卡 有线网卡 接力。账户正常


存在问题 alc662无法驱动。无HDMI音频


刷新bios后 需在OC启动界面按空格 进入GRUB。 原版Bios输入setup_var_3 0x7D3 0x2. 或刷我上传的版本 setup_var_3 0x7D4 0x2 否则启动mac会重启



内附efi  oc0.88.    bios以及刷新工具和教程

升级13后 需要更新英特尔网卡到2.20  联网慢 不建议

新版bios支持nvme硬盘  NGFF即为默认原版BIOS--输入setup_var_3 0x7D3 0x2。NVME 为新版支持NVME硬盘BIOS 建议更新。setup_var_3 0x7D4 0x2
