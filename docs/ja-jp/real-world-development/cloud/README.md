---
slug: ja-jp/real-world-development/cloud
title: "GitHub Copilot cloud agent"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

[**GitHub Copilot cloud agent**](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent) を使うと、GitHub Copilot がクラウドで非同期に作業できます。GitHub で作業を割り当てると、cloud agent がバックグラウンドでリポジトリを調べて変更を行い、pull request を作成します。その間、別の作業を続けられます。

この演習では、cloud agent が従うカスタム手順を追加し、GitHub Issue を割り当てて実装を依頼します。カスタム エージェントを確認してそのアプローチを調整し、エージェント ダッシュボードでセッションを監視して指示します。最後に、エージェントが作成した pull request をレビューし、結果を繰り返し改善します。

## 演習

| 演習 | トピック | 説明 |
|----------|-------|-------------|
| [0. 前提条件][ex0] | セットアップ | リポジトリと codespace を作成する |
| [1. カスタム手順][ex1] | コンテキスト | cloud agent が従うカスタム手順を追加する |
| [2. Cloud agent][ex2] | 非同期エージェント | GitHub Copilot cloud agent に Issue を割り当てる |
| [3. カスタム エージェント][ex3] | 専門エージェント | カスタム エージェントを確認して使う |
| [4. エージェントの管理][ex4] | 監視 | エージェント セッションを監視して指示する |
| [5. 反復改善][ex5] | レビュー | pull request をレビューし、Copilot の作業を反復して改善して、次のステップを選ぶ |

## 前提条件

このワークショップに参加する前に、次のものを用意します。

- [ ] 有効な **Copilot Student、Pro、Pro+、Business、Enterprise** プランを持つ GitHub アカウント
- [ ] アカウントまたは組織で GitHub Copilot cloud agent が有効になっていること

> [!TIP]
> 有料プランをお持ちでない場合、認証済みの学生は [GitHub Education][callout-student-plan-education] を通じて GitHub Copilot を無料で利用できます。**Copilot Student** プランには、このワークショップで使用する agent、MCP、コードレビュー、Copilot CLI の機能が含まれているため、すべてのハーネスを完了できます。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> Cloud agent は **Copilot Student、Pro、Pro+、Business、Enterprise** の各プランで利用できます。Copilot Free では利用できません。Copilot Business または Enterprise の場合、管理者が組織で有効にする必要があります。

> [!NOTE]
> このハーネスでは MCP を扱いません。Copilot で MCP サーバーを使う方法については、[CLI ハーネス][cli]または [VS Code ハーネス][vscode]を参照してください。

## はじめる

**[演習 0: 前提条件から始めます →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
[cli]: ../cli/
[vscode]: ../vscode/
