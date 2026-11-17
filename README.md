# X-MACRO-LAB-POCKET0

X-MACRO-LAB-POCKET0 是一个基于思澈（SiFli）SF32LB52 的小智 AI 语音交互终端资料仓库。当前收录插件版 V1.3 的硬件设计文件、软件固件包，以及实物展示素材。

软件开源地址：https://github.com/78/xiaozhi-sf32

## 效果展示

![X-MACRO-LAB-POCKET0 实物展示](<01_resource/demo picture/1280X1280.JPEG>)

展示图中标注的外壳正面尺寸约为 **68.53 mm × 48.15 mm**：

![X-MACRO-LAB-POCKET0 尺寸](<01_resource/demo picture/size.jpg>)

[观看「思澈小智AI展示」视频](<01_resource/demo picture/思澈小智AI展示.mp4>)

## 硬件资料

| 资料 | 文件 | 说明 |
| --- | --- | --- |
| 原理图 | [插件版原理图.pdf](<01_resource/hardware/PCB/插件版原理图.pdf>) | 插件版电路原理图 |
| PCB 结构 | [DXF_小智AI插件版V1.3_AutoCAD2007.dxf](<01_resource/hardware/PCB/DXF_小智AI插件版V1.3_AutoCAD2007.dxf>) | AutoCAD 2007 格式的结构文件 |
| 顶壳 | [3D_插件版V1.3外壳设计V1_顶壳.stl](<01_resource/hardware/3D Model/3D_插件版V1.3外壳设计V1_顶壳.stl>) | V1.3 外壳 3D 打印模型 |
| 底壳 | [3D_插件版V1.3外壳设计V1_底壳.stl](<01_resource/hardware/3D Model/3D_插件版V1.3外壳设计V1_底壳.stl>) | V1.3 外壳 3D 打印模型 |
| 面板 | [Panel_插件版v1.3面板设计v1_2025-08-15.epanm](<01_resource/hardware/3D Model/Panel_插件版v1.3面板设计v1_2025-08-15.epanm>) | V1.3 面板设计文件 |
| 按键帽 | [按键帽.STL](<01_resource/hardware/3D Model/按键帽.STL>) | 按键帽 3D 打印模型 |
| 焊接清单 | [pcb_smt.png](<01_resource/demo picture/pcb_smt.png>) | 器件参数、位号及焊接备注 |

焊接清单中列出的主要器件包括：LC-OPEN-SF32LB52-MOD-N16R8 主控、GMI6050P-36db 麦克风、LM4871N 音频功放、CR123A 3.7 V 电池盒、屏幕排针接口及按键等。

PCB 与实物预览：

| 项目 | 预览 |
| --- | --- |
| PCB 顶层 | ![PCB 顶层](<01_resource/demo picture/pcb_top.png>) |
| PCB 底层 | ![PCB 底层](<01_resource/demo picture/pcb_bottom.png>) |
| 实物正面 | ![PCB 实物正面](<01_resource/demo picture/pcb_demo_top.jpg>) |
| 实物背面 | ![PCB 实物背面](<01_resource/demo picture/pcb_demo_bottom.jpg>) |

## 软件资料

[sf32lb52-xty-ai-tht.zip](<01_resource/software/sf32lb52-xty-ai-tht.zip>) 包含固件镜像与烧录工具：

- `bootloader.bin`
- `ER_IROM1.bin`
- `ER_IROM2.bin`
- `ER_IROM3.bin`
- `ftab.bin`
- `sftool.exe`

具体烧录流程请参考上方软件开源仓库。

## 目录结构

```text
01_resource/
├── demo picture/                 # 实物图、PCB 预览、焊接清单和演示视频
├── hardware/
│   ├── 3D Model/                 # 外壳、面板及按键帽模型
│   └── PCB/                      # 原理图与结构文件
└── software/                     # 固件包及烧录工具
```
