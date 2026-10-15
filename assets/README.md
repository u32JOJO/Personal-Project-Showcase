# 演示素材目录

本目录存放各项目的演示截图、动图及公开仿真视频。

## 命名规范

```text
assets/
├── 01-logistics/
│   ├── robot-photo.jpg           # 整车照片
│   ├── trajectory.png            # 五次插值轨迹曲线
│   ├── architecture.png          # 四层架构（可选，.md 中已有 Mermaid）
│   └── demo.gif                  # 搬运作业演示
├── 02-ai-glasses/
│   ├── pipeline-switch.png       # 管道切换流程
│   └── ble-provisioning.png      # BLE 配网交互
├── 03-hplayer/
│   ├── cpu-before-after.png      # CPU 占用对比
│   └── playback.jpg              # 播放效果
└── 04-go2w/
    ├── cover.png                 # 正式轨迹的单台近景
    ├── go2w-showcase.mp4          # 48.5 秒精简展示
    ├── go2w-100x10.mp4            # 95 秒完整百台 10 轮演示
    ├── go2w-single.mp4            # 9.5 秒正式首轮单台近景
    └── results-summary.json       # 可公开的汇总评估数据
```

## 建议

- **格式**：截图用 PNG / JPG，视频采用 H.264 MP4。
- **播放入口**：README 使用视频附件链接内嵌播放器，并保留仓库 MP4 备用入口。仅提交 MP4 文件不会自动在 README 中生成播放器。
- **体积**：GitHub 免费账户的视频附件上限为 10 MB，与 Git 仓库单文件限制不同；本目录三段 Go2W 视频均低于此附件限制。超过 10 MB 并不自动要求 Git LFS。
- **脱敏**：分享前检查画面中是否含串口输出、内网 IP、设备序列号、内部界面。
- **动图时长**：3–8 秒、突出一个动作，比长录屏更有效。

平台限制见 [GitHub 官方附件说明](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/attaching-files)。
Go2W 视频使用实际仿真轨迹离线回放，完整视频保留全部轮次；精简片中的自然跌落探索明确标注为未验证成功恢复。

## 未提供素材时的替代方案

各项目文档中的架构图与流程图均使用 **Mermaid** 编写，GitHub 会原生渲染，
无需图片即可展示系统设计。素材缺失不影响文档可读性。

<!-- 素材占位：请将截图/动图放入对应子目录，并在项目文档中取消图片引用注释 -->
