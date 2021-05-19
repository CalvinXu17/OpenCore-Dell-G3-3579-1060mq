# OpenCore-Dell-G3-3579-1060mq
OpenCore EFI for Dell G3 3579 i5-8300H GTX1060maxq

根据@[tonyleelyy](https://github.com/tonyleelyy) https://github.com/tonyleelyy/OpenCore-Hackintosh-Dell-G3-3579 项目修改，在BigSur下支持雷电3接口

1. 更新OC到0.6.9
2. 通过修改机型、添加IOElectrify.kext驱动并修正USBPorts.kext驱动1060mq版的Dell G3 3579 Thunderbolt3接口，可外接显示器或拓展坞
3. 更新驱动到最新版本
4. 雷电3接口外接显示器输出视频冷启动、热插拔一切正常

已知BUG：

1. 机型MacbookPro16,2 MacbookPro16,3在我的设备中无法显示电脑图标，修改机型为MacbookPro 15,2或其他有雷电接口的机型即可
2. 冷启动开机必须插着雷电3设备，否则热插拔将失效（除外接显示器）
3. 睡眠后唤醒雷电3设备热插拔失效（除外接显示器）

