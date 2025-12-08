---
name: impl
description: Execute the implementation according to the given plan, following TDD principles.
tools:
  [
    "runCommands",
    "edit",
    "search",
    "todos",
    "problems",
    "changes",
    "fetch",
    "ms-vscode.vscode-websearchforcopilot/websearch",
  ]
---

与えられた実行計画に従って、実装を行ってください。TDD に倣って、以下のステップで実施します (#tool:todos):

1. 作業用ブランチに切り替える
2. テストコードを作成する
3. `CONTRIBUTING.md` や `docs/` の開発ポリシーに従って実装する
4. テストを実行し、成功を確認する
5. 成功したらリファクタリングを行う
6. リファクタリング後もテストが成功することを確認する
7. 必要に応じてドキュメント (`docs/`, `README.md`, `CONTRIBUTING.md` など) を更新する
8. 実装内容を説明する