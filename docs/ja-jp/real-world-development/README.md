---
title: "実践的な開発"
slug: ja-jp/real-world-development
authors:
  - geektrainer
lastUpdated: 2026-09-16
---

現実的なシナリオ、完成したアプリケーション、共有バックログを使って、ソフトウェア開発ライフサイクル全体で GitHub Copilot を活用します。変更の計画、コードの作成、動作のテスト、pull request のレビュー、エージェントによる作業管理を繰り返し行います。

## シナリオ

開発者をテーマにしたボードゲームのクラウドファンディングを提供する架空の会社、Tailspin Toys の新しい開発者として作業します。チームのバックログは GitHub Issue として登録されており、すぐに取り組めます。フィルターやページネーションなどの機能作業に加え、アクセシビリティやコーディング標準などの品質改善も含まれています。

## 環境を選ぶ

GitHub Copilot は、どこで作業していても利用できます。開発方法に合った環境を選択してください。各ワークショップは個別のセットアップから始まり、共通の Tailspin Toys シナリオを使用します。

### [GitHub Copilot CLI][cli]

ターミナルでエージェント型アシスタントを使用します。Plan モードと Autopilot モード、手順、スキル、カスタム エージェント、Playwright MCP、Agent Merge、便利なスラッシュ コマンドを活用します。

### [GitHub Copilot app][app]

複数のエージェント セッションを並行して実行し、セッション モードを切り替え、Canvas で共同作業し、デスクトップ アプリで GitHub Issue と pull request を管理します。

### [GitHub Copilot cloud agent][cloud]

GitHub Issue を非同期エージェントに割り当て、作業を案内して進捗を監視し、エージェントが作成する pull request をレビューします。

### [Visual Studio Code][vscode]

Visual Studio Code と GitHub Codespaces で GitHub Copilot を使用します。エディターを離れずに、Copilot Chat のエージェント モード、MCP サーバー、カスタム エージェントを活用します。

[cli]: cli/
[app]: app/
[cloud]: cloud/
[vscode]: vscode/
