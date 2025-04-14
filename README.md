# zine-sample

# ✍️ ZINE制作プロジェクト
このリポジトリは、ZINEの原稿執筆と進行管理を行うためのものです。  
執筆・編集に関わるメンバーが、効率よくコラボレーションできるように構成されています。
---

## ✅ このリポジトリでやること
- 原稿アイデアの共有（→ [Issues](../../issues) を使います）
- 原稿の執筆・編集（→ [articles/](./articles) フォルダにMarkdownで書きます）
- 原稿の履歴管理（→ GitHubでバージョン管理）
- 編集状況の見える化（→ Issueのラベルやステータス）
---

## 🗂 ディレクトリ構成
```plaintext
/
├── articles/            # 原稿ファイル（Markdown）
│   ├── 01_intro.md
│   └── 02_theme-x.md
├── images/              # 挿入画像
├── .github/
│   └── ISSUE_TEMPLATE/  # 原稿ネタ投稿用テンプレート
└── README.md            # この説明ファイル



## ✏️ 執筆の流れ（ざっくり）

Issueを作成して、書きたいアイデアを投稿します

タイトル、概要、構成などを記入します
ステータスを「アイデア段階」にしておきます
/articles/ フォルダに原稿をMarkdownで書き始めます
例：01_intro.md など
ファイルの先頭にタイトルと著者を書いておくと便利です
編集・加筆修正がある場合は、直接編集してOK
コミットメッセージに「Close #issue番号」と書くとIssueが自動で閉じられます
必要に応じて、Pull Request を使ってレビューや相談もできます
小さく始めたい方は無理に使わなくてもOKです

## 📄 Markdown原稿の書き方（基本ルール）
1記事 = 1ファイル（.md）
ファイル名の先頭に番号をつけて、記事順を明示すると便利です
例：01_intro.md, 02_theme-x.md
見出し（#）で章構成を書きましょう
画像を入れるときは /images/ に保存し、Markdownで参照します

## 🛠 予定している機能・拡張（任意）
自動でMarkdown→PDFの組版（後日設定予定）
GitHub Projectsを使った進行管理（必要なら）
デザインや印刷のワークフローの記録

🙋‍♀️ 参加のしかた・連絡事項
GitやGitHubに慣れていない方も気軽に参加してください！
わからないことがあれば、Issueにコメントするか、主催者まで連絡してください。

最初に1つIssueを立ててアイデアを投稿してみましょう ✨

📌 備考
このREADMEは随時アップデートしていきます。

ご意見や改善提案も歓迎です！
