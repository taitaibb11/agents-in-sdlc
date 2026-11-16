---
title: "Exercício 0: Pré-requisitos"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

Antes de começar os exercícios do cloud agent do Copilot, prepare o que você vai precisar. Crie uma cópia do repositório Tailspin Toys e inicie um [codespace][codespaces]. Você usará esse ambiente para editar arquivos de instruções e revisar o trabalho do cloud agent.

## Configure o repositório do workshop

Use o [modelo][template-repository] para criar uma cópia do repositório em que você vai trabalhar. O novo repositório inclui todos os arquivos necessários para os exercícios e será usado durante o workshop.

1. Em uma nova janela do navegador, acesse o [modelo do Tailspin Toys][tailspin-template].
2. Na página do repositório de treinamento, selecione **Use this template** e, em seguida, **Create a new repository** para criar uma cópia do repositório.

    ![Botão Use this template](../../../_images/ex0-use-template.png)

3. Se estiver participando do workshop em um evento organizado pelo GitHub ou pela Microsoft, siga as orientações do mentor. Caso contrário, crie o repositório em uma organização que tenha acesso ao GitHub Copilot.

    ![Formulário para especificar as configurações do repositório de modelo](../../../_images/ex0-repository-settings.png)

4. Anote o caminho do repositório criado (**organization-or-user-name/repository-name**) para consultar depois.

## Crie um codespace

Agora você vai fazer o workshop em um codespace.

[GitHub Codespaces][codespaces] é um ambiente de desenvolvimento na nuvem que permite escrever, executar e depurar código no navegador. Ele oferece um IDE completo com suporte a várias linguagens de programação, extensões e ferramentas.

1. Acesse o repositório que você acabou de criar.
2. Selecione o botão verde **Code**.

    ![Selecione o botão Code](../../../_images/ex0-code-button.png)

3. Selecione a guia **Codespaces** e, em seguida, o botão **+** para criar um codespace.

    ![Criar um novo codespace](../../../_images/ex0-create-codespace.png)

A criação do codespace pode levar alguns minutos, mas ainda é muito mais rápida do que instalar todos os serviços manualmente. Enquanto aguarda, explore outros recursos do GitHub Copilot, que você conhecerá nas próximas etapas.

> [!CAUTION]
> Você usará este codespace nos próximos exercícios. Por enquanto, mantenha-o aberto em uma guia do navegador.

> [!NOTE]
> Este workshop foi configurado para ser executado no Codespaces ou em um [dev container][dev-containers] local. Ambos os ambientes oferecem os pré-requisitos necessários para que as atividades funcionem sem problemas. Para executar localmente, abra o repositório clonado no VS Code e selecione **Reopen in Container** quando solicitado. O VS Code criará o mesmo dev container usado pelo Codespaces.

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## Resumo

Você criou uma cópia do repositório do workshop e iniciou a criação de um codespace. É nesse ambiente que você trabalhará com o cloud agent do Copilot.

## Próxima etapa

Adicione instruções personalizadas para o cloud agent seguir. Continue para o [Exercício 1 - Instruções personalizadas][next-lesson].

## Recursos

- [Visão geral do GitHub Codespaces][codespaces]
- [Criar um repositório a partir de um modelo][template-repository]
- [Início rápido do Codespaces][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[next-lesson]: ../1-custom-instructions/
