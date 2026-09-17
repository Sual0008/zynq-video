# Zynq Video

基于两块 Zynq-7020 开发板实现 1280×720@30 fps RGB565 图像的
实时采集、千兆以太网传输、DDR 双帧缓存、图像处理与 HDMI 显示。

## 主要功能

- OV5640 SCCB 配置与 DVP 图像采集
- RGB565 图像数据分包
- UDP/IP 千兆以太网传输
- 帧号、包序号校验与异常检测
- AXI4-Full 写入 DDR 双帧缓存
- AXI-VDMA 读取图像
- RGB565 转 RGB888
- 灰度转换、滤波、图像增强和 Sobel 边缘检测
- HDMI 实时显示
