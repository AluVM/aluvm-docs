# About AluVM

AluVM \(algorithmic logic unit VM\) is a pure functional RISC virtual machine designed for deterministic portable computing tasks. It was designed & implemented by Dr Maxim Orlovsky at Pandora Core AG and mainained by LNP/BP Standards Association. 

Unlike many other virtual machines machines, AluVM is register-based and does not allow random memory access. This makes AluVM perfectly suited for like smart contracts, remote code execution, distributed & edge computing, guaranteeing high determinism and possibility of formal code analysis, combined with unprecedented robustness.

## Key characteristics

* Exceptionless
* Portability
* Sandboxing
* Security
* Extensibility

Instruction set architecture \(ISA\) supports extensions, which allows creation of runtime environments targeting different use cases.

## Using AluVM

The simplest way to use AluVM is AluREX: a runtime environment, package manager & developer toolchain which allows creation, distribution & execution of Alu binaries.

