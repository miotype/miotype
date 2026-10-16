<p align="center">
  <img src="assets/icon.png" width="96" height="96" alt="MioType のアイコン">
</p>

<h1 align="center">MioType</h1>

<p align="center">
  <b>話せば、打ってくれる。</b>Mac のための音声入力と即時翻訳。<br>
  <kbd>Fn</kbd> を押して話し、もう一度 <kbd>Fn</kbd> を押すと、どのアプリでもカーソル位置に文字が入ります。
</p>

<p align="center">
  <a href="https://miotype.com/download"><b>macOS 版をダウンロード</b></a> ·
  <a href="https://miotype.com">ウェブサイト</a> ·
  <a href="https://miotype.com/pricing">料金</a>
</p>

<p align="center"><sub><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.pt.md">Português</a> · <a href="README.ru.md">Русский</a></sub></p>

<p align="center">
  <a href="https://www.youtube.com/watch?v=lWkNX-c_a8k"><img src="assets/demo.jpg" width="720" alt="MioType の 1 分間デモ動画"></a><br>
  <sub><a href="https://www.youtube.com/watch?v=lWkNX-c_a8k">▶ YouTube で 1 分間のデモを見る</a></sub>
</p>

---

カーソルがターミナル、VS Code、Cursor、Claude Code や Codex のプロンプト、Slack のスレッド、コミットメッセージのどこにあっても構いません。MioType はフォーカスのある場所に入力します。

## ショートカット

| キー | 動作 |
|---|---|
| <kbd>Fn</kbd> | 押して話し始め、もう一度押すと入力されます。<kbd>Esc</kbd> でキャンセル |
| <kbd>Fn</kbd> + <kbd>Space</kbd> | 何でも質問できます。先にテキストを選択するとそれについて質問でき、「もっと短くして」と言えばその場で書き換えます |
| <kbd>Fn</kbd> + <kbd>Left Shift</kbd> | 中国語で話すと英語に、英語で話すと中国語に |
| <kbd>Fn</kbd> + <kbd>Control</kbd> | 選択したテキストを翻訳。英単語ひとつなら辞書カードを表示 |
| <kbd>Fn</kbd> + <kbd>R</kbd> | 選択したテキストをその場で推敲 |
| <kbd>Fn</kbd> + <kbd>S</kbd> | 単語やフレーズを調べる |

ショートカットはすべて設定で変更できます。

## 開発者に好まれる理由

- **カーソルのある場所に入力。** 別ウインドウもコピー＆ペーストも不要です。コーディングエージェントへの長いプロンプト、PR の説明、issue への返信を、その場で口述できます。
- **中国語と英語が混ざっても、そのまま。** 「把这个 function 改成 async」と言えば、その通りに入力されます。英語の用語が中国語に訳されることはありません。
- **あなたの語彙を覚えます。** 口述の直後に誤認識された語（`kubectl`、`useEffect`、同僚の名前など）を直すと、MioType が辞書に追加し、次回から正しく入力されます。辞書のインポートもできます。
- **オフラインはスイッチひとつ。** 設定でローカルの Whisper モデルを選べば、音声は Mac の外に出ません。ネットワークもアカウントも不要です。
- **自分の API キーも使えます。** 認識と推敲を、MioType Cloud の代わりに自分の API プロバイダーに向けられます。

## 無料プランと有料プラン

| | |
|---|---|
| **ローカル** | ずっと無料。Whisper によるオフライン口述、自分の API キーでの翻訳と推敲。履歴・辞書・設定は Mac に保存されます |
| **無料クラウド** | サインインすると毎週 3,000 語のクラウド枠 |
| **MioType Cloud** | 毎月 10 万語のクラウド枠。クラウド認識、AI による推敲と翻訳を API キーなしで。月額 US$9.99、年額 US$59.99、または買い切り US$149 |

詳しくは[料金ページ](https://miotype.com/pricing)をご覧ください。購入から 14 日以内なら理由を問わず全額返金します。

## プライバシー

- ローカルの Whisper はすべて Mac 上で動作します。
- クラウドモードでは、各リクエストの音声やテキストが当社サーバーを経由して Alibaba Cloud Model Studio で処理され、結果はそのまま返されます。当社サーバーは音声もテキストも保存せず、利用枠の計算のために語数・リクエストの種類・時刻だけを記録します。
- 自分の API キーを使う場合、リクエストは Mac から選んだプロバイダーへ直接送られます。
- あなたのコンテンツでモデルを学習させることはなく、広告やトラッカーも使いません。
- プライバシーポリシー全文（英語）：[miotype.com/privacy](https://miotype.com/privacy)

## 動作環境

- Apple シリコン搭載の Mac（M1 以降）
- マイクとアクセシビリティの権限。初回設定時に案内します

## フィードバック

不具合や要望は [issue を作成](https://github.com/miotype/miotype/issues/new/choose)してください。公開したくない内容は [hi@miotype.com](mailto:hi@miotype.com) へ。

各バージョンのリリースノートは [Releases](https://github.com/miotype/miotype/releases) で公開しています。**Watch → Custom → Releases** で新しいバージョンの通知を受け取れます。

---

MioType はオープンソースではありません。このリポジトリは公開の issue トラッカーとリリースノートのためのものです。
