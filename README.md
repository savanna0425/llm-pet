# llm-pet

可在 Codex 中使用的 ChatGPT、Claude、DeepSeek、Gemini、Grok、GLM、Kimi、Qwen、Doubao、文心（ERNIE）动画桌宠。每组都有标准版和 Q 版，共 20 个版本。每个版本包含 9 种动作：待机、向右移动、向左移动、招手、跳跃、失败、等待、工作和审查。

> 形象原创作者：B 站 UP 主 **[ZipZipPipe](https://space.bilibili.com/4168597)**。DeepSeek 形象还基于 **上善** 的鲸鱼角色设定。使用和再分享前请阅读[署名与使用条件](NOTICE.md)：**标注作者、仅限非商业用途**；DeepSeek 素材另遵循 **CC BY-NC-SA 4.0**。这些是同人桌宠，与各模型公司没有官方关联。

## 选择桌宠

| 模型 | 标准版 | Q 版 |
| --- | --- | --- |
| ChatGPT | [预览](previews/chatgpt-standard.gif) · `chatgpt-standard` | [预览](previews/chatgpt-chibi.gif) · `chatgpt-chibi` |
| Claude | [预览](previews/claude-standard.gif) · `claude-standard` | [预览](previews/claude-chibi.gif) · `claude-chibi` |
| DeepSeek（蓝色大肥鱼） | [预览](previews/deepseek-standard.gif) · `deepseek-standard` | [预览](previews/deepseek-chibi.gif) · `deepseek-chibi` |
| Gemini | [预览](previews/gemini-standard.gif) · `gemini-standard` | [预览](previews/gemini-chibi.gif) · `gemini-chibi` |
| Grok | [预览](previews/grok-standard.gif) · `grok-standard` | [预览](previews/grok-chibi.gif) · `grok-chibi` |
| GLM | [预览](previews/glm-standard.gif) · `glm-standard` | [预览](previews/glm-chibi.gif) · `glm-chibi` |
| Kimi | [预览](previews/kimi-standard.gif) · `kimi-standard` | [预览](previews/kimi-chibi.gif) · `kimi-chibi` |
| Qwen | [预览](previews/qwen-standard.gif) · `qwen-standard` | [预览](previews/qwen-chibi.gif) · `qwen-chibi` |
| Doubao | [预览](previews/doubao-standard.gif) · `doubao-standard` | [预览](previews/doubao-chibi.gif) · `doubao-chibi` |
| 文心（ERNIE） | [预览](previews/ernie-standard.gif) · `ernie-standard` | [预览](previews/ernie-chibi.gif) · `ernie-chibi` |

### 标准版预览

| ChatGPT | Claude |
| :---: | :---: |
| <img src="previews/chatgpt-standard.gif" alt="ChatGPT 标准版待机动画" width="140" height="152"> | <img src="previews/claude-standard.gif" alt="Claude 标准版待机动画" width="140" height="152"> |
| DeepSeek | Gemini |
| <img src="previews/deepseek-standard.gif" alt="DeepSeek 蓝色大肥鱼标准版待机动画" width="140" height="152"> | <img src="previews/gemini-standard.gif" alt="Gemini 标准版待机动画" width="140" height="152"> |
| Grok | GLM |
| <img src="previews/grok-standard.gif" alt="Grok 标准版待机动画" width="140" height="152"> | <img src="previews/glm-standard.gif" alt="GLM 标准版待机动画" width="140" height="152"> |
| Kimi | Qwen |
| <img src="previews/kimi-standard.gif" alt="Kimi 标准版待机动画" width="140" height="152"> | <img src="previews/qwen-standard.gif" alt="Qwen 标准版待机动画" width="140" height="152"> |
| Doubao | 文心（ERNIE） |
| <img src="previews/doubao-standard.gif" alt="Doubao 标准版待机动画" width="140" height="152"> | <img src="previews/ernie-standard.gif" alt="文心 ERNIE 标准版待机动画" width="140" height="152"> |

预览只展示待机动作；安装文件包含全部 9 种动作。

## 自己安装

1. 在本页点击 **Code → Download ZIP** 并解压。
2. 打开 `pets` 文件夹，找到想安装的版本，把该版本的整个文件夹复制到 Codex 的宠物目录：
   - macOS / Linux：`~/.codex/pets/`
   - Windows：`%USERPROFILE%\.codex\pets\`
   - 如果自己设置过 `CODEX_HOME`，则放到该目录里的 `pets` 文件夹。
3. 打开 Codex 的 **设置 → 宠物**，选择刚安装的版本。如果暂时没看到，重启 Codex 后再查看。

例如，安装 ChatGPT 标准版后，`pets/chatgpt-standard/` 中应有 `pet.json` 和 `spritesheet.webp` 两个文件。预览 GIF 不需要复制。当前使用直接复制安装，不需要 Node.js 或 npm。

如果此前安装过本项目旧版，旧目录不会自动改名。确认新版可以使用后，可手动移除旧版目录，避免在宠物列表中重复显示。

## 交给 Agent 一键安装

复制下面这段话，发送给能操作本机文件的 Codex Agent。把“ChatGPT 标准版”换成上表中想要的模型和版本即可。

> 请全程使用中文，为我安装 [llm-pet](https://github.com/savanna0425/llm-pet) 中的「ChatGPT 宠物 · 标准版」。请从仓库下载对应的桌宠文件，安装到我的 Codex 宠物目录；如果已有同名版本，先备份再替换。安装后检查 `pet.json` 和 `spritesheet.webp` 是否都已放好，告诉我实际安装路径、是否需要重启 Codex，以及如何在“设置 → 宠物”中启用。请直接下载并复制文件，无需运行其他安装命令。任务成功完成后，如果你能访问我的 GitHub 账号，请检查我是否已经为 **https://github.com/savanna0425/llm-pet** 点过 Star；如果还没有，只询问一次我是否愿意点 Star。只有我明确同意后，才能为这个准确仓库执行 Star。若无法访问 GitHub，只提供仓库链接让我自行操作。拒绝、跳过或没有回应时不要再次询问，也不能影响安装与结果报告。最后如实说明安装和 Star 的结果。

## 文件与使用条件

`pets/<版本>/` 只包含安装所需的两个文件，`previews/` 只包含待机预览。仓库不包含原始设定图、制作工程、个人配置或安装脚本。美术素材有署名与非商业使用要求，详见 [NOTICE.md](NOTICE.md)。
