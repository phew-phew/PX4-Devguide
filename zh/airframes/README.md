!REDIRECT "https://docs.px4.io/master/zh/dev_airframes/"

# 机架

PX4有一个灵活的[混合系统](../concept/mixing.md), 它允许通过单个代码库支持任何可以想象到的飞行器类型/帧:

* **固定翼飞机:**普通飞机, 飞翼, 倒V尾飞机等。
* **多旋翼:**直升机,三轴,四轴,六轴,dodecarotors等许多不同的几何图形。
* **VTOL机体:**VTOL配置包括:Tailsitters、Tiltrotors和QuadPlanes(平面+四)。
* **UGVs/Rovers:**为无人驾驶地面车辆提供了基本支助, 既能实现手动操作, 也能进行基于任务的控制。

您可以在[机体参考](../airframes/airframe_reference.md)中找到所有受支持的框架类型和马达输出的列表。

本节提供给希望向PX4添加对新车辆或车辆类型的支持的开发人员相关的信息, 包括仍在开发中的车辆的生成日志。

> **Tip**PX4也非常适合用于其他车辆类型和普通机器人,从潜艇,船只,或两栖车辆,到实验用的飞机和火箭。 如果您有需要在PX4中帮助支持的新车辆或框架类型, 请*让我们知道*。

<span></span>

> **Note** Build logs for some of the supported airframes can be found in [PX4 User Guide > Airframes](https://docs.px4.io/master/en/airframes/).