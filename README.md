# SoulPulse AI 视频生成执行指南

为了在你的 Mac Mini 上生成那段“极致冲击力”的不知火舞视频，请按照以下步骤操作：

## 1. 准备 API Key
由于 Seedance 2.0 免费额度绑定在你的账号上，你需要先获取一个 **API Key**（通常在圣思科技官网的开发者后台）。

## 2. 运行一键生成脚本
我已经为你写好了 Python 脚本 `projects/SoulPulse/seedance_generator.py`。你只需要在终端执行：

```bash
cd /Users/snow/.openclaw/workspace/projects/SoulPulse
# 将下面的 KEY 替换为你的真实 API Key
export SEEDANCE_API_KEY="你的_REAL_KEY"
python3 seedance_generator.py
```

## 3. 预览结果
脚本运行完成后，会自动将渲染好的 `.mp4` 文件下载到 `projects/SoulPulse-Vision/videos/` 目录下。

我已经在 GitHub Pages 上为你搭好了预览站：
🔗 **[https://chenios.github.io/SoulPulse-Vision/](https://chenios.github.io/SoulPulse-Vision/)**

## 4. 视频视觉设定 (已内置于脚本)
- **动作源**：KOF XV 不知火舞 - 超必杀忍蜂 (4K 原片提取)
- **皮肤设定**：赛博中式极致破坏版 (高叉、湿身、半透明材质)
- **渲染引擎**：Seedance 2.0 Pro (Ultra Consistency)
