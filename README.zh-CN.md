<p align="center">
  <img src="assets/icon.png" width="96" height="96" alt="MioType 图标">
</p>

<h1 align="center">MioType</h1>

<p align="center">
  <b>说话，不用打字。</b>Mac 上的语音输入和即时翻译。<br>
  按一下 <kbd>Fn</kbd> 开始说，再按一下，文字就出现在光标处，任何 App 都行。
</p>

<p align="center">
  <a href="https://miotype.com/download"><b>下载 macOS 版</b></a> ·
  <a href="https://miotype.com/?lang=zh">官网</a> ·
  <a href="https://miotype.com/pricing?lang=zh">价格</a> ·
  <a href="README.md">English</a>
</p>

---

光标在终端、VS Code、Cursor、Claude Code 或 Codex 的输入框、Slack、还是 commit message 里都行，哪里有焦点就打到哪里。

## 快捷键

| 按键 | 作用 |
|---|---|
| <kbd>Fn</kbd> | 按一下开始说，再按一下打出来。<kbd>Esc</kbd> 取消 |
| <kbd>Fn</kbd> + <kbd>Space</kbd> | 问任何问题。先选中文字可以针对它提问，说「改短一点」就原地替换 |
| <kbd>Fn</kbd> + <kbd>左 Shift</kbd> | 说中文出英文，反过来也行 |
| <kbd>Fn</kbd> + <kbd>Control</kbd> | 翻译选中的文字。选中单个英文单词会弹出词典卡片 |
| <kbd>Fn</kbd> + <kbd>R</kbd> | 原地润色选中的文字 |
| <kbd>Fn</kbd> + <kbd>S</kbd> | 查单词或短语 |

所有快捷键都能在设置里改。

## 为什么程序员用着顺手

- **直接打在光标处。**不弹新窗口，不用复制粘贴。给 coding agent 的长提示、PR 描述、issue 回复，在哪写就在哪说。
- **中英混说不乱翻。**说「把这个 function 改成 async」，打出来就是这句，英文术语不会被翻成中文。
- **会记住你的词。**听写完在输入框里改对一个词（`kubectl`、`useEffect`、同事的名字），MioType 会自动记进词典，下次就对了。也可以导入词典。
- **一键切到离线。**在设置里选本地 Whisper 模型，声音不离开你的 Mac，不联网、不登录也能用。
- **可以用自己的 Key。**识别和润色都能改用你自己的 API 服务商。

## 免费与付费

| | |
|---|---|
| **本地** | 永久免费。离线 Whisper 听写；用自己的 API Key 翻译和润色。历史、词典、设置都留在本机 |
| **免费云端** | 登录后每周 3000 字云端额度 |
| **MioType Cloud** | 每月 10 万字云端额度，云端识别、AI 润色和翻译，不用自己的 Key。月付 US$9.99、年付 US$59.99，或一次性 US$149 |

详见[价格页](https://miotype.com/pricing?lang=zh)。任何购买 14 天内可无理由全额退款。

## 隐私

- 本地 Whisper 完全在你的 Mac 上运行。
- 云端模式下，每次请求的音频或文字经我们的服务器转给阿里云百炼处理，结果直接返回给你。服务器不保存音频和文字，只记录字数、请求类型和时间，用来计算额度。
- 用自己的 Key 时，请求从你的 Mac 直接发给你选的服务商。
- 不用你的内容训练模型，没有广告和第三方追踪。
- 完整政策：[miotype.com/privacy](https://miotype.com/privacy?lang=zh)

## 系统要求

- Apple 芯片的 Mac（M1 及以后）
- 麦克风和辅助功能权限，首次设置时会引导你打开

## 反馈

发现 bug 或想要新功能？[提一个 issue](https://github.com/miotype/miotype/issues/new/choose)。不方便公开的，写信到 [hi@miotype.com](mailto:hi@miotype.com)。

每个版本的更新说明会发在 [Releases](https://github.com/miotype/miotype/releases)。点 **Watch → Custom → Releases** 就能收到新版本通知。

---

MioType 不开源。这个仓库用来公开收集反馈和发布更新说明。
