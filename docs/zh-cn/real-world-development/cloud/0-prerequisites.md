---
title: "练习 0：先决条件"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

开始 Copilot 云代理练习前，请准备所需资源。创建 Tailspin Toys 仓库的副本并启动一个 [codespace][codespaces]。你将在此环境中编辑说明文件并审查云代理的工作。

## 设置研讨会仓库

使用[模板][template-repository]创建要开展练习的仓库副本。新仓库包含练习所需的所有文件，并会在整个研讨会中使用。

1. 在新的浏览器窗口中打开 [Tailspin Toys 模板][tailspin-template]。
2. 在练习仓库页面上，选择 **Use this template**，然后选择 **Create a new repository** 来创建仓库副本。

    ![Use this template 按钮](../../../_images/ex0-use-template.png)

3. 如果你是在 GitHub 或 Microsoft 举办的活动中参加研讨会，请遵循导师的指导。否则，请在可以使用 GitHub Copilot 的组织中创建仓库。

    ![填写模板仓库设置的表单](../../../_images/ex0-repository-settings.png)

4. 记下已创建仓库的路径（**organization-or-user-name/repository-name**），以便稍后查阅。

## 创建 codespace

接下来将在 codespace 中完成练习。

[GitHub Codespaces][codespaces] 是基于云的开发环境，可让你在浏览器中编写、运行和调试代码。它提供功能完整的 IDE，支持多种编程语言、扩展和工具。

1. 打开刚创建的仓库。
2. 选择绿色的 **Code** 按钮。

    ![选择 Code 按钮](../../../_images/ex0-code-button.png)

3. 选择 **Codespaces** 选项卡，然后选择 **+** 按钮创建新的 codespace。

    ![创建新的 codespace](../../../_images/ex0-create-codespace.png)

创建 codespace 可能需要几分钟，但比手动安装所有服务快得多。等待期间，可以了解 GitHub Copilot 的其他功能，后续步骤会逐一介绍。

> [!CAUTION]
> 后续练习还会使用此 codespace。现在请让它保持在浏览器标签页中打开。

> [!NOTE]
> 本研讨会已配置为在 Codespaces 或本地 [dev container][dev-containers] 中运行。这两种环境都提供顺利完成练习所需的先决条件。若要在本地运行，请在 VS Code 中打开克隆的仓库，并在收到提示时选择 **Reopen in Container**。VS Code 会构建与 Codespaces 相同的 dev container。

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## 总结

你已创建研讨会仓库的副本并开始创建 codespace。接下来将在此环境中与 Copilot 云代理协作。

## 下一步

添加云代理需要遵循的自定义说明。继续学习[练习 1 - 自定义说明][next-lesson]。

## 资源

- [GitHub Codespaces 概述][codespaces]
- [从模板创建仓库][template-repository]
- [Codespaces 快速入门][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[next-lesson]: ../1-custom-instructions/
