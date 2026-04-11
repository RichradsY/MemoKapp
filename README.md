# MemoK

Privacy-first background recording for iPhone, built for real-world interruptions.

[App Store](https://apps.apple.com/us/app/id6757718388) · [User Guide](./USER_GUIDE.md) · [Privacy Policy](./PRIVACY_POLICY.md)  · [中文](#中文)

## English

MemoK is an iPhone background recorder for meetings, lectures, interviews, and voice notes.

The app was shaped gradually through real user feedback. Many of the latest improvements focus on the places where recording apps usually fail in everyday use: interruptions, long-session management, quick switching to Camera, and keeping recordings organized afterward.

### Why MemoK

- Built for long sessions you can trust, not just quick memos
- Designed around real iPhone context switching instead of ideal conditions
- Local-first by default: no account required, no ads, no IAP

### Highlights

#### Recording reliability

- Background continuous recording
- Scheduled recording windows and all-day mode
- Smart segmented recording from `1` to `180` minutes
- Save-first, auto-resume oriented interruption recovery
- Better coexistence with dictation and other short audio-session takeovers
- More resilient recording during quick photo / video switching

#### Review and organization

- Waveform playback for faster review
- Quick Notes attached to recordings, exported as Markdown
- Batch export and batch delete
- Custom export filenames with variable templates
- Star protection for important files
- Automatic cleanup for excess files

#### Product details

- Audio quality options: Low / Medium / High
- Dark / Light / System theme
- Daily stats and lightweight diagnostics export
- Multi-language support

### Privacy

- Recordings stay on-device by default
- MemoK does not upload recordings to external servers by default
- Please follow local laws and obtain consent before recording

### Boundaries

- MemoK does **not** record phone calls
- MemoK does **not** capture third-party app audio streams

### Build From Source

Requirements:

- iOS `16.0` or later
- Xcode with iOS development support
- A physical iPhone for realistic background-audio testing

Steps:

1. Open [RollingRecorderApp.xcodeproj](./RollingRecorderApp/RollingRecorderApp.xcodeproj).
2. Select your signing team and bundle identifier if needed.
3. Build and run on an iPhone.
4. Grant microphone permission on first launch.



## 中文

MemoK 是一款面向 iPhone 的后台录音应用，适合会议、课堂、访谈和日常语音记录。

它不是按“理想录音场景”设计的，而是围绕真实使用过程不断打磨出来的。很多近期优化都来自用户反馈，重点放在这些最容易出问题的地方：录音被打断、长录音难管理、录音时临时切出去拍照 / 录像，以及录完之后如何更快整理。

### 主要特点

#### 录音稳定性

- 后台持续录音
- 定时录音与全天录音
- `1-180` 分钟自动分段
- 被打断后的优先保存与自动恢复
- 更注重与 dictation 等短暂音频接管场景共存
- 切去拍照、录像等常见操作时尽量保持录音连续

#### 回看与整理

- 波形播放，便于快速定位
- 录音附加快速笔记，导出为 Markdown
- 批量导出 / 批量删除
- 支持变量模板的自定义导出文件名
- 星标保护重要文件
- 自动清理多余文件

#### 其他细节

- 低 / 中 / 高三档音质
- 深色 / 浅色 / 跟随系统主题
- 每日统计与轻量诊断导出
- 多语言支持

### 隐私与边界

- 录音默认仅保存在本地设备
- 默认不会上传到外部服务器
- 不支持电话通话录音
- 不录制第三方 App 音频流

录音前请遵守当地法律并取得相关同意。

### 本地运行

环境要求：

- iOS `16.0` 或更高版本
- 已安装 Xcode
- 建议使用真机测试后台录音与中断恢复

步骤：

1. 打开 [RollingRecorderApp.xcodeproj](./RollingRecorderApp/RollingRecorderApp.xcodeproj)
2. 如有需要，配置签名团队与 Bundle Identifier
3. 在 iPhone 上编译运行
4. 首次启动时授予麦克风权限


