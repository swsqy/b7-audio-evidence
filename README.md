# B7 audio evidence

[在线听检](https://swsqy.github.io/b7-audio-evidence/) · [实验报告与复现条件](https://gist.github.com/swsqy/24c7a22b4e146c24d4b3274b79bd64b8)

20 条原始 WAV、10 份 codec NPY：seeds 16、25、29、52、54 × CustomVoice/Vivian 和 Base embedding。每组包含 streamed/offline 对照，标注、说明及异常片段试听。

纯静态 HTML / CSS / JavaScript，无 Python、构建依赖、外部 CDN 或 ChatGPT Sites 依赖。GitHub Pages 从 main 分支根目录发布。音频和 codec 保存在 assets/，SHA-256 见 checksums.json。音频是原始实验产物，不做转码或归一化。

Gist 中的 05_AUDIO.html 是内嵌全部音频和 codec 的独立离线副本；下载单个 HTML 后即可使用，不必下载 ZIP。Gist 自身只展示源码，在线播放使用上方 GitHub Pages 链接。

页面保留已有听检标签，用于证据复核，不能视作新的盲听。完整条件、证据限制和后续研究建议见报告。
