---
title: Workspaces
weight: 44
description: >-
  Você encontrará nessa seção informações sobre como usar workspaces no Ritchie.
---

---

## Qual a diferença entre workspace e repositório?

Repositórios e workspaces são usados para interagir com as fórmulas no Ritchie, mas em situações diferentes, veja abaixo:

**`workspace`** Você pode usar os comandos do workspace para desenvolver, editar e testar fórmulas `locais`.

**`repository`** Você pode usar o repositório para fazer o download de fórmulas de `repositórios Git` e usa-las.

*Veja o exemplo de adição de repositório na página [**Executar uma fórmula Hello World**]({{< ref path="Fórmulas/Executar uma fórmula hello world" >}}).*

Os comandos para repos e workspaces são similares, eles permitem que o CLI 'veja' as fórmulas disponíveis. Os workspaces possuem **prioridade mais alta** que os Repos, se você usar, por exemplo, os dois comandos para os mesmos repositórios de fórmulas, os workspaces serão executados.

Veja mais sobre os comandos de workspace e repositórios na [**lista de comandos e flags**]({{< ref path="Referência/Lista de comandos e flags" >}}).

## Como adicionar?

Siga os passos para adicionar:

**Passo 1:** Execute o comando abaixo para adicionar um novo workspace:

```text
rit add workspace
```

**Passo 2:** Informe alguns parâmetros de entrada antes da sua execução:

- 1: Informe o nome do workspace (não use espaços ou caracteres especiais).

- 2: Informe o caminho (path) do workspace na sua máquina local.

![](/shared/rit-add-workspace.gif)

## Como listar?

Execute o comando abaixo para listar os workspaces da máquina:

```text
rit list workspace
```

![](/shared/rit-list-workspace.gif)

## Como apagar?

Para excluir um workspace, execute o comando:

```text
rit delete workspace
```

Depois disso, siga os passos:

**Passo 1:** Selecione o workspace;

**Passo 2:** Confirme que você deseja excluir o workspace.

![](/shared/rit-delete-workspace.gif)

## Próximos passos

Nesta seção, você viu como usar workspaces no Ritchie. Para continuar lendo mais:

👉 Conheça a [**lista de comandos**]({{< ref path="Referência/Lista de comandos e flags" >}}) de fórmulas disponíveis no Ritchie.
