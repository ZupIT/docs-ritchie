---
title: Renomear fórmulas
weight: 44
description: Você encontrará nessa seção informações sobre como renomear uma fórmula no Ritchie.
---

---

## Como renomear?

### Premissas

{{% alert color="warning" %}}
Somente fórmulas locais podem ser renomeadas.
{{% /alert %}}

## Renomeando sua fórmula

Você pode usar a fórmula do Ritchie **`rit rename formula`** para renomear uma fórmula local. Os parâmetros de entrada necessários são:

1. O nome da fórmula antiga
2. O novo nome da fórmula

{{% alert color="info" %}}

- O Ritchie identificará automaticamente o workspace o qual a fórmula pertence.
  - Caso identifique mais de um workspace com a fórmula informada, um passo extra necessário será escolher em qual workspace a fórmula deve ter seu nome alterado.
- Essa fórmula contempla entrada via _flags_, mais informações em [**lista de comandos e flags**](/docs-ritchie/pt-br/referência/lista-de-comandos-e-flags/).
  {{% /alert %}}

## Efeitos

1. Todos os arquivos que identificam a fórmula serão alterados para o novo nome da fórmula

   _essas alterações refletirão tanto nas pastas internas de controle do Ritchie, quanto na pasta do workspace (sendo ele o default ou personalizado)_

2. O autocomplete do Ritchie identificará somente o novo nome de fórmula

## Próximos passos

Nessa seção, você viu como renomear uma fórmula no Ritchie. Para continuar configurando sua fórmula:

👉 Veja a seção [**como compartilhar fórmulas**](/docs-ritchie/pt-br/fórmulas/compartilhar-fórmulas/).
