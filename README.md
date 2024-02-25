# [SG2002](https://www.soc.xin/SG2002)

* [sophon](http://www.sophon.cn/): [C906/A53 + C906 + 8051](https://github.com/SoCXin/RISC-V)
* [L6R5](https://github.com/SoCXin/Level): C906@1GHz/A53@1GHz, C906@700MHz, 8051@300MHz

## [简介](https://github.com/SoCXin/SG2002/wiki)

[SG2002](https://milkv.io/zh/chips/sg2002) 是面向边缘智能监控 IP 摄像机、智能猫眼门锁、可视门铃、居家智能等多项产品领域而推出的高性能、低功耗芯片，集成了 H.264 视频压缩编解码器, H.265 视频压缩编码器和 ISP。

芯片更集成了自研 TPU，在 8 位整数运算下，可提供 1.0TOPS 的算力。 特殊设计的TPU 调度引擎能有效地为所有的张量处理器核心提供极高的带宽数据流。此外也为用户提供了强大的深度学习模型编译器和软件 SDK 开发包。主流的深度学习框架，比如Caffe 和 Tensorflow，可以轻松地移植到其平台上。除此之外，还提供了安全启动，安全更新，安全加密等，为用户从开发、量产、产品应用，提供一系列安全解决方案。

芯片内集成一个 8 位元的 MCU 子系统, 可替代一般外挂的 MCU 以达到省 BOM cost 及功耗的目的。

### 关键参数

* 1 x C906@1GHz + 1 x C906@700MHz
* 8051@6KB SRAM
* 1 TOPS@INT8
* Sip DRAM 256M
* QFN88 9mmx9mmx0.9mm


## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)

## [选型建议](https://github.com/SoCXin)

SG2002相较于[SG2000](https://milkv.io/zh/duo-s)，拥有更小的封装和DRAM，更少的IO，但拥有更强的NPU

* 相关竞品：[RV1106](https://github.com/SoCXin/RV1106)、[V851S](https://github.com/SoCXin/V851S)
* 上代产品：[CV1800B](https://github.com/SoCXin/CV1800B)

