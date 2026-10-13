# AgroDesign Simple GanttChart

ブラウザだけで動くガントチャート作成ツールです。インストールもアカウント登録も不要で、HTML ファイル 1 個で動きます。

*English follows below.*

## 使い方

- **ブラウザで開く**: <https://agrodesign-studios.github.io/simple-ganttchart/>
- **オフラインで使う**: [Releases](https://github.com/AgroDesign-Studios/simple-ganttchart/releases/latest) から `AgroDesign-Simple-GanttChart-v<バージョン>.html` をダウンロードし、ダブルクリックして開きます。インターネット接続は要りません。HTML ファイル 1 つだけで完全に動作します。データは、ブラウザ上（ローカル PC のみ）に保存され、サーバには保存されません。

対応ブラウザは Chrome / Edge / Firefox / Safari（デスクトップ）です。画面下部の「ヘルプ」に操作方法があり、「English」で表示言語を切り替えられます。

## できること

- タスクの開始日・終了日、依存関係（先行タスク）、グループ、進捗をもつガントチャートの作成
- 日・週・月の表示切り替え、日本の祝日の表示
- PDF・画像（PNG）への出力
- JSON での書き出し・読み込み（バックアップ、別の PC への移行）
- 「HTML 書き出し」: チャートを埋め込んだ HTML ファイルを作り、そのまま相手に渡せます

## データの保存場所

入力した内容は、**お使いのブラウザの中（localStorage）にだけ**保存されます。サーバーには送信されません。

- 別の PC や別のブラウザには引き継がれません。移行や共有には「JSON 書き出し」を使ってください。
- ブラウザの閲覧データを消去すると、チャートも消えます。大事なチャートは JSON で書き出して保管してください。
- 「全消去」は元に戻せません。

## ライセンス

[Apache License 2.0](LICENSE) です。再配布・改変ができます。
同梱している OSS（React、i18next、jsPDF など）の名前・版・ライセンス全文は、画面下部の「ライセンス情報」に載っています。

Copyright 2026 AgroDesign Studios

---

# AgroDesign Simple GanttChart (English)

A Gantt chart tool that runs entirely in your browser. Nothing to install, no account: it is a single HTML file.

## How to use

- **Open in the browser**: <https://agrodesign-studios.github.io/simple-ganttchart/>
- **Use offline**: download `AgroDesign-Simple-GanttChart-v<version>.html` from [Releases](https://github.com/AgroDesign-Studios/simple-ganttchart/releases/latest) and double-click it. No internet connection is needed. The single HTML file is all it needs to run. Your data is saved in the browser (on your own PC only), never on a server.

Supported browsers: Chrome, Edge, Firefox and Safari on desktop. "Help" at the bottom of the page explains the controls, and "English" / "日本語" switches the language.

## Features

- Gantt charts with start and end dates, dependencies (predecessors), groups and progress
- Day, week and month views; Japanese public holidays
- Export to PDF and PNG
- JSON export and import (backup, moving to another PC)
- "Export HTML": makes an HTML file with your chart embedded, ready to hand to someone else

## Where your data lives

Everything you enter is saved **only inside your browser (localStorage)**. Nothing is sent to a server.

- Data does not follow you to another PC or browser. Use "Export JSON" to move or share a chart.
- Clearing your browser's site data deletes your charts. Keep a JSON export of anything important.
- "Clear all" cannot be undone.

## License

[Apache License 2.0](LICENSE). You may redistribute and modify it.
The name, version and full licence text of each bundled open-source package (React, i18next, jsPDF and others) is listed under "License" at the bottom of the page.

Copyright 2026 AgroDesign Studios
