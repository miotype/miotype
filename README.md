<p align="center">
  <img src="assets/icon.png" width="96" height="96" alt="MioType icon">
</p>

<h1 align="center">MioType</h1>

<p align="center">
  <b>Speak, don't type.</b> Voice typing and instant translation for the Mac.<br>
  Press <kbd>Fn</kbd>, talk, press <kbd>Fn</kbd> again — the words land at your cursor, in any app.
</p>

<p align="center">
  <a href="https://miotype.com/download"><b>Download for macOS</b></a> ·
  <a href="https://miotype.com">Website</a> ·
  <a href="https://miotype.com/pricing">Pricing</a>
</p>

<p align="center"><sub><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.pt.md">Português</a> · <a href="README.ru.md">Русский</a></sub></p>

---

Your cursor can be in a terminal, VS Code, Cursor, a Claude Code or Codex prompt, a Slack thread or a commit message. MioType doesn't care. It types into whatever has focus.

## Shortcuts

| Keys | What happens |
|---|---|
| <kbd>Fn</kbd> | Press to start talking, press again to type it out. <kbd>Esc</kbd> cancels |
| <kbd>Fn</kbd> + <kbd>Space</kbd> | Ask anything. Select text first to ask about it, or say "make this shorter" to rewrite it in place |
| <kbd>Fn</kbd> + <kbd>Left Shift</kbd> | Speak Chinese, get English, and back |
| <kbd>Fn</kbd> + <kbd>Control</kbd> | Translate the selection. A single English word opens a dictionary card |
| <kbd>Fn</kbd> + <kbd>R</kbd> | Polish the selection in place |
| <kbd>Fn</kbd> + <kbd>S</kbd> | Look up a word or phrase |

Every shortcut can be rebound in Settings.

## Why developers like it

- **It types where your cursor is.** No separate window and no copy-paste step. Dictate a long prompt to your coding agent, a PR description or an issue reply right where it goes.
- **Mixed Chinese and English stays mixed.** Say "把这个 function 改成 async" and you get exactly that. English terms are not translated into Chinese.
- **It learns your vocabulary.** Fix a misheard word right after dictating (`kubectl`, `useEffect`, your teammate's name) and MioType adds it to your dictionary, so it comes out right next time. You can also import a dictionary.
- **Offline is one switch away.** Pick the local Whisper model in Settings and speech never leaves your Mac. It works with no network and no account.
- **Bring your own key.** Point recognition and polishing at your own API provider instead of MioType Cloud.

## Free and paid

| | |
|---|---|
| **Local** | Free forever. Offline Whisper dictation, plus translation and polishing with your own API key. History, dictionary and settings stay on your Mac |
| **Free cloud** | Sign in to get 3,000 cloud words every week |
| **MioType Cloud** | 100,000 cloud words a month for cloud recognition, AI polishing and translation, with no API key needed. US$9.99/month, US$59.99/year or US$149 once |

Details are on the [pricing page](https://miotype.com/pricing). Purchases can be refunded within 14 days, no questions asked.

## Privacy

- Local Whisper runs entirely on your Mac.
- In cloud mode, each request's audio or text goes through our server to Alibaba Cloud Model Studio and the result comes straight back. Our server does not store audio or text. It records only the word count, request type and time, to track your allowance.
- With your own API key, requests go from your Mac directly to the provider you chose.
- We don't train models on your content, and we run no ads or trackers.
- Full policy: [miotype.com/privacy](https://miotype.com/privacy)

## Requirements

- A Mac with Apple silicon (M1 or later)
- Microphone and Accessibility permissions. MioType asks for them during setup

## Feedback

Found a bug or want a feature? [Open an issue](https://github.com/miotype/miotype/issues/new/choose). For anything private, write to [hi@miotype.com](mailto:hi@miotype.com).

Release notes for each version are published under [Releases](https://github.com/miotype/miotype/releases). Click **Watch → Custom → Releases** to get notified.

---

MioType is closed source. This repository holds the public issue tracker and release notes.
