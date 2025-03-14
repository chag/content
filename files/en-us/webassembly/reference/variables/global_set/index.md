---
title: Global set
slug: WebAssembly/Reference/Variables/Global_set
page-type: webassembly-instruction
sidebar: webassemblysidebar
---

The **`global.set`** instruction sets the values of a global variable.

{{EmbedInteractiveExample("pages/wat/global_set.html", "tabbed-taller")}}

## Syntax

```wasm
;; load the number 2 onto the stack
i32.const 2

;; store the number 2 in the variable $val
global.set $val
```

| Instruction  | Binary opcode |
| ------------ | ------------- |
| `global.set` | `0x24`        |
