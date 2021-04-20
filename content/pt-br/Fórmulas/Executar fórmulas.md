---
title: Executar fórmulas 
weight: 24
description: >-
  Nesta seção, você vai encontrar como executar fórmulas no
  Ritchie.
---

---

## Como executar?

Você tem **duas maneiras** de executar fórmulas usando o Ritchie:

1. Localmente
2. Usando o Docker

Vale reforçar que **método de execução de fórmulas padrão** é escolhido durante a etapa de inicialização do Ritchie com o comando **`rit init`**. Você pode alterar essa configuração executando o comando abaixo:

```text
rit set formula-runner
```

![](/docs/large-gif-1374x404-.gif)

### 1. Execução local

Para executar uma fórmula localmente, é necessário ter instalada no computador a linguagem de programação que foi usada para desenvolver a fórmula.

Exemplo: uma fórmula desenvolvida em **Java** precisará ter **Java instalado** na máquina para ser executada localmente.  


### 2. Execução via Docker

Todas as fórmulas podem ser executadas sem depender da linguagem usada, desde que o **`DOCKER`** esteja instalado e iniciado.

{{% alert color="info" %}}
Para ver melhor como essa execução funciona na prática, confira a [**seção fórmula hello world** ](/docs-ritchie/pt-br/fórmulas/executar-uma-fórmula-hello-world/) para ver como isso funciona na prática.
{{% /alert %}}

{{% alert color="warning" %}}
 
 **Usuários do Docker no MacOS:** 
Para evitar o **'Error: exit status 1'**, é preciso **desativar** o Cloud Experience, dependendo da sua versão. 

Veja como: 
Acesse no Docker:
 -  Preferences > Command Line>  Enable cloud experience.

 ![](/docs-ritchie/static/ritchiedocker.PNG)

{{% /alert %}}

### 3. Local & Docker Flags

É possível forçar o Ritchie CLI a executar uma fórmula seguindo um método de execução específico, usando flags.

* A flag **`--local`** executará a fórmula localmente \(se o método de execução padrão for o Docker\). 
* A flag **`--docker`** executará a fórmula com Docker \(se o método de execução padrão for local\). 

### 4. Containers com Ritchie

{{% alert color="warning" %}}
Todos os templates de formulas contém um arquivo **DockerFile** que cria um container com **Ritchie CLI** instalado.
{{% /alert %}}


## Próximos passos 

Nesta seção, você viu como rodar uma fórmula no Ritchie. Para continuar aprendendo mais:

👉 Vá para página [**Fórmula Hello World**](/docs-ritchie/pt-br/fórmulas/executar-uma-fórmula-hello-world/) e descubra as diferentes maneiras de executar uma fórmula no Ritchie.

👉 Vá para página [**como criar fórmulas**](/docs-ritchie/pt-br/fórmulas/criar-fórmulas/) para entender o passo a passo para criar sua primeira automação usando o Ritchie.