# llm-pet

可在 Codex 中使用的 ChatGPT、Claude、DeepSeek、Gemini 动画桌宠。每组都有成熟版和 Q 版，共 8 个版本。每个版本包含 9 种动作：待机、向右移动、向左移动、招手、跳跃、失败、等待、工作和审查。

> 形象原创作者：B 站 UP 主 **[ZipZipPipe](https://space.bilibili.com/4168597)**。DeepSeek 形象还基于 **上善** 的鲸鱼角色设定。使用和再分享前请阅读[署名与使用条件](NOTICE.md)：**标注作者、仅限非商业用途**；DeepSeek 素材另遵循 **CC BY-NC-SA 4.0**。这些是同人桌宠，与各模型公司没有官方关联。

## 选择桌宠

| 模型 | 成熟版 | Q 版 |
| --- | --- | --- |
| ChatGPT | [预览](previews/chatgpt-mature.gif) · `chatgpt-mature` | [预览](previews/chatgpt-chibi.gif) · `chatgpt-chibi` |
| Claude | [预览](previews/claude-mature.gif) · `claude-mature` | [预览](previews/claude-chibi.gif) · `claude-chibi` |
| DeepSeek | [预览](previews/deepseek-mature.gif) · `deepseek-mature` | [预览](previews/deepseek-chibi.gif) · `deepseek-chibi` |
| Gemini | [预览](previews/gemini-mature.gif) · `gemini-mature` | [预览](previews/gemini-chibi.gif) · `gemini-chibi` |

<p align="center">
  <img src="previews/chatgpt-mature.gif" alt="ChatGPT 成熟版待机动画" width="140">
  <img src="previews/claude-mature.gif" alt="Claude 成熟版待机动画" width="140">
  <img src="previews/deepseek-mature.gif" alt="DeepSeek 成熟版待机动画" width="140">
  <img src="previews/gemini-mature.gif" alt="Gemini 成熟版待机动画" width="140">
</p>

预览只展示待机动作；安装文件包含全部 9 种动作。

## 自己安装

1. 在本页点击 **Code → Download ZIP** 并解压。
2. 打开 `pets` 文件夹，找到想安装的版本，把该版本的整个文件夹复制到 Codex 的宠物目录：
   - macOS / Linux：`~/.codex/pets/`
   - Windows：`%USERPROFILE%\.codex\pets\`
   - 如果自己设置过 `CODEX_HOME`，则放到该目录里的 `pets` 文件夹。
3. 打开 Codex 的 **设置 → 宠物**，选择刚安装的版本。如果暂时没看到，重启 Codex 后再查看。

例如，安装 ChatGPT 成熟版后，`pets/chatgpt-mature/` 中应有 `pet.json` 和 `spritesheet.webp` 两个文件。预览 GIF 不需要复制。当前使用直接复制安装，不需要 Node.js 或 npm。

## 交给 Agent 一键安装

复制下面这段话，发送给能操作本机文件的 Codex Agent。把“ChatGPT 成熟版”换成上表中想要的模型和版本即可。

> 请全程使用中文，为我安装 [llm-pet](https://github.com/savanna0425/llm-pet) 中的「ChatGPT 宠物 · 成熟版」。请从仓库下载对应的桌宠文件，安装到我的 Codex 宠物目录；如果已有同名版本，先备份再替换。安装后检查 `pet.json` 和 `spritesheet.webp` 是否都已放好，告诉我实际安装路径、是否需要重启 Codex，以及如何在“设置 → 宠物”中启用。请直接下载并复制文件，无需运行其他安装命令。任务成功完成后，如果你能访问我的 GitHub 账号，请检查我是否已经为 **https://github.com/savanna0425/llm-pet** 点过 Star；如果还没有，只询问一次我是否愿意点 Star。只有我明确同意后，才能为这个准确仓库执行 Star。若无法访问 GitHub，只提供仓库链接让我自行操作。拒绝、跳过或没有回应时不要再次询问，也不能影响安装与结果报告。最后如实说明安装和 Star 的结果。

## 文件与使用条件

`pets/<版本>/` 只包含安装所需的两个文件，`previews/` 只包含待机预览。仓库不包含原始设定图、制作工程、个人配置或安装脚本。美术素材有署名与非商业使用要求，详见 [NOTICE.md](NOTICE.md)。
