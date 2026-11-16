---
title: "レッスン 12 - GitHub Pages でサイトをデプロイする"
description: "GitHub Copilot app を使って Pages ワークフローを構成し、その pull request をレビューして、公開された Space Quiz を確認します。"
authors:
  - jamesmontemagno
lastUpdated: 2026-10-12
---

GitHub Pages にデプロイして Space Quiz を公開します。Copilot はワークフローを準備し、デプロイを案内できますが、変更をレビューし、サイトが公開されたことを確認するのはユーザーの責任です。

このレッスンでは、次の操作を行います。

- Copilot に GitHub Pages のデプロイ構成を依頼します。
- マージする前にワークフローと pull request をレビューします。
- デプロイを追跡し、公開されたサイトを確認します。

## シナリオ

Space Quiz はすでに GitHub リポジトリにありますが、利用するにはまだ簡単な方法が必要です。単一ファイルのサイトを GitHub Pages で公開すると、サーバーやランタイム依存関係を追加せずに、公開 URL からアクセスできるようになります。

## Copilot にデプロイの準備を依頼する

> [!WARNING]
> pull request を作成すると、コードがコミットおよびプッシュされることがあります。このプロンプトを送る前に、承認設定と対象リポジトリを確認してください。**Approve all** を選択している場合、別の確認プロンプトは表示されないものとして操作してください。

`space-quiz` の Copilot app セッションで、次のプロンプトを送信します。

```plaintext
Prepare a GitHub Pages deployment for this repository. Create a GitHub Actions workflow that builds the website if needed and deploys it to GitHub Pages after changes reach the default branch. Add a README describing the app and how to run it locally if one does not already exist. Create a pull request with these changes and report its link and any required Pages settings or permissions. Do not merge, enable auto-merge, change Pages settings, or deploy. Stop and wait for my review.
```

## ワークフローと pull request をレビューする

1. README は、リポジトリに既存の README がない場合にのみ追加されていることを確認します。
2. ワークフローのビルドとデプロイの手順、トリガー、権限を含め、pull request の変更をレビューします。
3. マージされていない pull request ではなく、既定のブランチからデプロイされることを確認します。
4. 必要な修正を依頼し、更新された差分をレビューします。マージを承認する前に、必須の pull request チェックがすべて成功するまで待ちます。

## マージとデプロイを承認する

> [!WARNING]
> 次のプロンプトは、レビュー済みの pull request のマージ、リポジトリの Pages 設定の変更、サイトの公開をエージェントに許可します。レビューを完了し、リポジトリと pull request を確認した後にのみ送信してください。承認設定によっては、これらの操作に別の確認プロンプトが表示されない場合があります。

`<PR_NUMBER>` をレビューした pull request の番号に置き換えてから、次の別のプロンプトを送信します。

```plaintext
I have reviewed pull request <PR_NUMBER> in this repository and authorize its merge and deployment. Enable GitHub Pages using GitHub Actions, merge that pull request only after required checks pass, and monitor the deployment until it succeeds. Report the final URL of the live website. If you lack permission to enable Pages or merge, tell me exactly what I need to approve or do; do not report success until the site is live.
```

![3 段階の図: space-quiz の pull request がマージされた状態、Build website・Upload artifact・Deploy to Pages の各ステップが成功した GitHub Actions の Deploy website 実行、yourname.github.io/space-quiz/ で公開された Space Quiz。](../../../_images/first-steps-app-pages-deploy.svg)

## デプロイを確認する

1. GitHub Actions のデプロイ実行が成功するまで確認します。
2. 報告された URL を開き、Space Quiz が表示されることを確認します。

エージェントが Pages の有効化や pull request のマージを実行できない場合は、提示された具体的な手順に従います。デプロイが成功し、サイトが表示されるまでタスクを完了扱いにしないでください。

## まとめと次のステップ

Space Quiz が公開され、エージェントの報告に頼るのではなくデプロイを確認できました。続けて[レッスン 13: レビューと次のステップ][next-lesson]に進みます。

[next-lesson]: ../13-review/
