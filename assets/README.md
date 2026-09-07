# 演示素材目录

本目录存放各项目的演示截图与动图。

## 命名规范

```text
assets/
├── 01-dual-arm/
│   ├── architecture.png          # 系统架构图（.md 中已有 Mermaid，可选）
│   ├── can-timing.png            # CAN 时序 / 抓包对比
│   └── pick-place-demo.gif       # 取放书实机演示
├── 02-go2w/
│   ├── supervisor-state.png      # supervisor 状态机
│   └── fault-injection.png       # 故障注入结果
├── 03-logistics/
│   ├── robot-photo.jpg           # 整车照片
│   ├── trajectory.png            # 五次插值轨迹曲线
│   └── demo.gif                  # 搬运作业演示
├── 04-ai-glasses/
│   ├── pipeline-switch.png       # 管道切换流程
│   └── ble-provisioning.png      # BLE 配网交互
└── 05-hplayer/
    ├── cpu-before-after.png      # CPU 占用对比
    └── playback.jpg              # 播放效果
```

## 建议

- **格式**：截图用 PNG，动图用 GIF 或短 MP4（GitHub 对 MP4 支持更好）。
- **体积**：单文件建议 < 5 MB；超过 10 MB 用 [Git LFS](https://git-lfs.github.com/)。
- **脱敏**：分享前检查画面中是否含内网 IP、串口输出、设备序列号、内部界面。
- **动图时长**：3–8 秒、突出一个动作，比长录屏更有效。

## 未提供素材时的替代方案

各项目文档中的架构图与流程图均使用 **Mermaid** 编写，GitHub 会原生渲染，
无需图片即可展示系统设计。素材缺失不影响文档可读性。

<!-- 素材占位：请将截图/动图放入对应子目录，并在项目文档中取消图片引用注释 -->
