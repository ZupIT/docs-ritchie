---
title: Overview
weight: 66
description: In this section, you will find more about stdin flag. 

---

{{% alert color="danger" %}}
The STDIN flag will be deprecated in early 2021, as substituted by [input flags](/standard-inputs/input-flag/).
{{% /alert %}}

{{% alert color="info" %}}
The **`--stdin`** flag on Ritchie has been developed to inform input parameters directly on the command lines.  
  
In that case, the input parameters need to be informed in a **JSON format**:

**`echo`**`'{"key":"value"}'`**`|`**`RIT (GROUP) VERB NOUN` **`--stdin`**
{{% /alert %}}

You can use this stdin flag rules on:

👉 [**Core Commands**]({{< ref path="Stdin flag/stdinflag Core Commands.md" >}}).

👉 [**Formulas Commands**]({{< ref path="Stdin flag/Stdin flag Formulas commands.md" >}}).

