---
name: issue_sample
about: Describe this issue template's purpose here.
title: "[issue]"
labels: ''
assignees: mac-nanya

---

name: 原稿アイデア
description: zine用の記事アイデアを記録・共有します
title: "[ネタ] タイトルをここに入力"
labels: ["idea"]
body:
  - type: textarea
    id: summary
    attributes:
      label: アイデアの概要
      description: どんなテーマで書きたいか、ざっくり書いてください
      placeholder: 例）インディーズ出版をしたきっかけと、印刷所選びのポイントを紹介したい。
    validations:
      required: true

  - type: textarea
    id: structure
    attributes:
      label: 想定している構成・アウトライン
      description: 見出し案や書きたい内容を箇条書きなどで整理しましょう（任意）
      placeholder: |
        - はじめに：なぜZINEを作ろうと思ったか
        - 印刷所の比較と決定理由
        - 実際に入稿してみての感想
      value: ""
    validations:
      required: false

  - type: input
    id: author
    attributes:
      label: 執筆者
      description: 執筆を担当する人が決まっていればGitHubのユーザー名などを記入
      placeholder: 例）@yourname
    validations:
      required: false

  - type: dropdown
    id: status
    attributes:
      label: 現在のステータス
      options:
        - アイデア段階
        - 執筆中
        - 編集中
        - 完成済み
      default: 0
    validations:
      required: true
