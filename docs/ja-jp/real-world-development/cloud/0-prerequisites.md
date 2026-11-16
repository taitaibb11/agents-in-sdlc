---
title: "演習 0: 前提条件"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

Copilot cloud agent の演習を始める前に、必要なものを準備します。Tailspin Toys リポジトリのコピーを作成し、[codespace][codespaces] を開始します。この環境で手順ファイルを編集し、cloud agent が作成した内容をレビューします。

## ワークショップ用リポジトリの設定

[テンプレート][template-repository]を使って、作業するリポジトリのコピーを作成します。新しいリポジトリには演習に必要なファイルがすべて含まれており、ワークショップを通して使用します。

1. 新しいブラウザー ウィンドウで [Tailspin Toys テンプレート][tailspin-template]を開きます。
2. ハンズオン用リポジトリのページで **Use this template** を選択し、次に **Create a new repository** を選択してリポジトリのコピーを作成します。

    ![Use this template ボタン](../../../_images/ex0-use-template.png)

3. GitHub または Microsoft が主催するイベントでワークショップに参加している場合は、メンターの案内に従います。それ以外の場合は、GitHub Copilot を利用できる組織にリポジトリを作成します。

    ![テンプレート リポジトリの設定を入力するフォーム](../../../_images/ex0-repository-settings.png)

4. 後で参照できるように、作成したリポジトリのパス (**organization-or-user-name/repository-name**) を記録します。

## codespace の作成

codespace でワークショップを進めます。

[GitHub Codespaces][codespaces] は、ブラウザーでコードの作成、実行、デバッグができるクラウド開発環境です。複数のプログラミング言語、拡張機能、ツールをサポートするフル機能の IDE を利用できます。

1. 先ほど作成したリポジトリを開きます。
2. 緑色の **Code** ボタンを選択します。

    ![Code ボタンを選択](../../../_images/ex0-code-button.png)

3. **Codespaces** タブを選択し、**+** ボタンを選択して新しい codespace を作成します。

    ![新しい codespace の作成](../../../_images/ex0-create-codespace.png)

codespace の作成には数分かかることがありますが、すべてのサービスを手動でインストールするよりもはるかに短時間で済みます。待っている間に GitHub Copilot の他の機能を確認できます。次のステップから順に学びます。

> [!CAUTION]
> 以降の演習でもこの codespace を使用します。今はブラウザーのタブで開いたままにしてください。

> [!NOTE]
> このワークショップは Codespaces またはローカルの [dev container][dev-containers] で実行できるように構成されています。どちらの環境にも、手順をスムーズに進めるために必要な前提条件が用意されています。ローカルで実行するには、クローンしたリポジトリを VS Code で開き、メッセージが表示されたら **Reopen in Container** を選択します。VS Code が Codespaces と同じ dev container を構築します。

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## まとめ

ハンズオン用リポジトリのコピーを作成し、codespace の作成を開始しました。この環境で Copilot cloud agent と作業します。

## 次のステップ

cloud agent が従うカスタム手順を追加します。[演習 1 - カスタム手順][next-lesson]に進みます。

## リソース

- [GitHub Codespaces の概要][codespaces]
- [テンプレートからリポジトリを作成する][template-repository]
- [Codespaces クイックスタート][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[next-lesson]: ../1-custom-instructions/
