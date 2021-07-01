# About AluVM

AluVM \(algorithmic logic unit VM\) is a pure functional RISC virtual machine designed for deterministic portable computing tasks. It was designed & implemented by [Dr Maxim Orlovsky](https://dr.orlovsky.ch) at [Pandora Core AG](https://pandoracore.com) and maintained by [LNP/BP Standards Association](https://lnp-bp.org). 

Unlike many other virtual machines, AluVM is register-based and does not allow random memory access. This makes AluVM perfectly suited for such domains as smart contracts, remote code execution, distributed & edge computing because of AluVM  determinism  combined with unprecedented robustness and possibility of formal code analysis.

{% page-ref page="use-cases-1.md" %}

## Key characteristics

* Exceptionless
* Portability
* Sandboxing
* Security
* Extensibility

Instruction set architecture \(ISA\) supports extensions, which allows creation of runtime environments targeting different use cases.

## Using AluVM

The simplest way to use AluVM is AluREX: a runtime environment, package manager & developer toolchain which allows creation, distribution & execution of Alu binaries.

