# llm-pet

四组可在 Codex 中使用的动画桌宠：GPT 白龙、Claude 橙花、DeepSeek 蓝色大肥鱼、Gemini 星猫。共 7 个版本，每个版本都包含 Codex 所需的 `pet.json` 和 `spritesheet.webp`，动作涵盖待机、移动、招手、跳跃、失败、等待、工作和审查等 9 种状态。

> 形象原创作者：B 站 UP 主 **[ZipZipPipe](https://space.bilibili.com/4168597)**。DeepSeek 形象还基于 **上善** 的鲸鱼角色设定。使用和再分享前请阅读 [署名与使用条件](NOTICE.md)：**标注作者、仅限非商业用途**；DeepSeek 素材另遵循 **CC BY-NC-SA 4.0**。这些是同人桌宠，与各模型公司没有官方关联。

## 预览与选择

| 桌宠 | 标准版 | Q 版 |
| --- | --- | --- |
| GPT 白龙 | — | [预览](previews/gpt-white-dragon.gif) · `gpt-white-dragon` |
| Claude 橙花 | [预览](previews/claude-scholar-mature.gif) · `claude-scholar-mature` | [预览](previews/claude-scholar-chibi.gif) · `claude-scholar-chibi` |
| DeepSeek 蓝色大肥鱼 | [预览](previews/deepseek-whale-mature.gif) · `deepseek-whale-mature` | [预览](previews/deepseek-whale-chibi.gif) · `deepseek-whale-chibi` |
| Gemini 星猫 | [预览](previews/gemini-starcat-mature.gif) · `gemini-starcat-mature` | [预览](previews/gemini-starcat-chibi.gif) · `gemini-starcat-chibi` |

<p align="center">
  <img src="previews/gpt-white-dragon.gif" alt="GPT 白龙待机动画" width="140">
  <img src="previews/claude-scholar-chibi.gif" alt="Claude 橙花 Q 版待机动画" width="140">
  <img src="previews/deepseek-whale-chibi.gif" alt="DeepSeek 蓝色大肥鱼 Q 版待机动画" width="140">
  <img src="previews/gemini-starcat-chibi.gif" alt="Gemini 星猫 Q 版待机动画" width="140">
</p>

预览 GIF 只展示待机动作；安装包中的图集包含全部 9 种状态。

## 手动安装

1. 在本页点 **Code → Download ZIP**，解压；或克隆此仓库。
2. 从 `pets/` 中挑选一个或多个版本，把各版本文件夹完整复制到 Codex 的 `pets` 目录。默认位置如下：
   - macOS / Linux：`~/.codex/pets/`
   - Windows：`%USERPROFILE%\.codex\pets\`
   - 如果设置了 `CODEX_HOME`，则使用该目录下的 `pets/`。
3. 例如选择 `deepseek-whale-chibi`，安装后应是：

   ```text
   <Codex 配置目录>/pets/deepseek-whale-chibi/
     pet.json
     spritesheet.webp
   ```

4. 在 Codex 的桌宠选择界面选择对应名称。如果没有立即出现，重新打开 Codex 后再查看。

只复制所选版本的两个文件即可；`previews/` 无需安装。替换旧版本时，先保留自己的自定义文件备份。

## 让 Agent 帮你安装

复制下面的提示词，发送给能访问本机文件的 Codex Agent；把其中的版本 ID 改成上表中想要的版本。Agent 会先检查文件，再安装所选版本。

```text
请从 https://github.com/savanna0425/llm-pet 安装 Codex 桌宠 deepseek-whale-chibi。
只读取该仓库 pets/deepseek-whale-chibi/ 下的 pet.json 和 spritesheet.webp；先确认 JSON 的 id 与目录名一致，spritesheetPath 为 spritesheet.webp，图集为 1536×1872 像素。
把这两个文件复制到 ${CODEX_HOME:-$HOME/.codex}/pets/deepseek-whale-chibi/；如果已有同名桌宠，先备份旧文件再替换。
安装后核对目标目录内两个文件都存在，并告诉我如何在 Codex 中选择它。不执行仓库中的脚本，不索取或输出凭据。
```

Windows 用户可把目标路径改为 `%CODEX_HOME%\pets\deepseek-whale-chibi\`；若未设置 `CODEX_HOME`，使用 `%USERPROFILE%\.codex\pets\deepseek-whale-chibi\`。

## 文件范围

`pets/<版本 ID>/` 只包含安装文件；`previews/` 只包含待机 GIF。仓库不包含原始设定图、制作工程、个人配置或安装脚本。

## 署名与使用条件

请阅读 [NOTICE.md](NOTICE.md)。这些美术素材具有非商业和署名要求；公开提供文件不代表放弃原作者权利，也不构成各模型公司的官方授权。
