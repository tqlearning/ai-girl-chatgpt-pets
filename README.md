# GPT龙娘 & DeepSeek鲸娘 · ChatGPT 动态 Pet 素材

两位 AI 娘，陪你待机、思考、等回复，也会朝鼠标方向看。

[GitHub 仓库](https://github.com/tqlearning/ai-girl-chatgpt-pets)

本仓库整理了两套**非官方、AI 辅助生成的二创 Pet 精灵图**：GPT龙娘和 DeepSeek鲸娘。每套包含 9 种动画状态、16 个视线方向，以及透明 PNG 图集和预览。

> **许可范围：**本仓库原创说明文档与布局元数据采用 [MIT 许可证](LICENSE)。角色设定与 PNG/GIF 美术资源不包含在此 MIT 授权内；其开放授权尚未确认。使用、修改或再分发前，请先阅读 [权利与许可范围](RIGHTS.md) 和 [来源署名](ATTRIBUTION.md)。

## 认识她们

| GPT龙娘 | DeepSeek鲸娘 |
| --- | --- |
| ![GPT龙娘待机动画](assets/gpt-dragon/previews/idle.gif) | ![DeepSeek鲸娘待机动画](assets/deepseek-whale/previews/idle.gif) |
| 白发紫眸、龙角、小翅膀与龙尾 | 蓝发鲸尾，抱着铁盆白米饭 |
| 轻轻摆尾、眨眼，安静地陪你思考 | 一边干饭一边忙碌，空盆时会失落 |

## 下载与预览

### GPT龙娘

- [透明精灵图 PNG](assets/gpt-dragon/spritesheet.png)
- [布局与动画元数据](assets/gpt-dragon/pet.json)
- [忙碌动画](assets/gpt-dragon/previews/working.gif) · [16 方向预览](assets/gpt-dragon/previews/look-directions.gif) · [全部帧一览](assets/gpt-dragon/previews/contact-sheet.png)

### DeepSeek鲸娘

- [透明精灵图 PNG](assets/deepseek-whale/spritesheet.png)
- [布局与动画元数据](assets/deepseek-whale/pet.json)
- [干饭动画](assets/deepseek-whale/previews/working.gif) · [16 方向预览](assets/deepseek-whale/previews/look-directions.gif) · [全部帧一览](assets/deepseek-whale/previews/contact-sheet.png)

GitHub 页面上的图片可能是缩放预览。请打开 PNG 文件后下载原始文件，保留完整尺寸和透明通道。

## 在支持自定义 Pet 的 ChatGPT 会话中使用

1. 下载对应角色的 `spritesheet.png`。
2. 将 PNG 文件作为附件交给支持自定义 Pet 创建的 ChatGPT 会话，并提出请求，例如：
   - “请用这张精灵图创建一个名为 GPT龙娘的 Pet。”
   - “请用这张精灵图创建一个名为 DeepSeek鲸娘的 Pet。”
3. 由支持该功能的创建流程校验精灵图并创建 Pet；若希望立即启用，请在请求中明确说明。

能否创建和启用取决于当前账号与客户端是否提供相应功能。本仓库不包含客户端、账号绑定信息或一键安装器。`pet.json` 是便于查看和复用的仓库自描述文件，不是官方导入配置；GIF 和联系表仅供预览。

## 图集规格

- 格式：透明 PNG / RGBA
- 完整尺寸：1536 × 2288 像素
- 网格：8 列 × 11 行；每格 192 × 208 像素
- 内容：57 个动作帧 + 16 个方向姿态；15 个未用格保持全透明
- 校验：每个图集的字节数与 SHA-256 见对应 `pet.json`；仓库文件校验和见 [SHA256SUMS](SHA256SUMS)

行顺序、帧数、播放时长及方向坐标见 [FORMAT.md](FORMAT.md)。完整 PNG 是实际使用的图集；预览 GIF 有调色板与展示背景差异。

## 当前效果与限制

两套图集均保留完成版的透明像素和帧布局，发布整理未改动画内容。16 方向是离散姿态，部分相邻角度变化较细微，并非连续插值动画。

- GPT龙娘：22.5°/45°、135°/157.5°、225°/247.5°的姿态较接近；337.5°仍带较明显的左转
- DeepSeek鲸娘：22.5°/45°相近，247.5°向下的分量较轻；337.5°回到 0°时有轻微轮廓和水平位置变化

## 来源与权利

角色形象参考社区流传的同一套 AI 娘设定。社区整理页面将这套形象归于 **ZipZipPipe**；详情与可核查链接见 [ATTRIBUTION.md](ATTRIBUTION.md)。本仓库的动作帧为重新生成和整理的二创素材，原始参考插图不随仓库发布。

这是爱好者素材项目，与 OpenAI、ChatGPT、DeepSeek 或原角色作者不存在已声明的官方合作、授权或背书关系。相关名称用于说明角色主题；权利范围以 [RIGHTS.md](RIGHTS.md) 为准。
