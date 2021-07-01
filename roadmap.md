# Roadmap

## AluVM implementation

The current version of AluVM implementation is 0.3. We are targeting 1.0 release until the end of the year

* [x] Instruction set arthitecture design
* [x] Reference implementation in Rust
* [x] Floating point operation implementation
* [x] Virtual machine and control flow implementation
* [x] Separation of code & data segment
* [x] Library management & packaging
* [x] ISA extensions support
* [x] Core cryptography implementation \(digests, Secp256k1 operations\)
* [ ] LNPBP standards and specification writeup
* [ ] Complete implementation of arithmetic operations for domain-specific floating types: BFloat16 \(machine learning\), IEEE binary256 and 512-tapered float \(near-arbitrary precision float arithmetics\)
* [ ] Complete implementation of complex byte-string operations
* [ ] Implement operations on Curve25519
* [ ] Complete test coverage of the reference VM implementation

## Language-specific bindings & toolchain

**2021 H2**

* [x] Assembly language and assembler \(compiler\) as domain-specific language inside rust code
* [ ] ALURE ISA extension for basic I/O
* [ ] Binary code packaging and execution
* [ ] Complete assembly language specification
* [ ] Standalone command-line assembler

**2022**

* [ ] AluREX library & package distribution website
* [ ] Write WASM bindings for AluVM library
* [ ] Create C bindings for AluVM library
* [ ] LLVM cross-compiler
* [ ] Parsel language specification & compiler

## Applications

**2021**

* [ ] Bitcoin-specific ISA extensions
* [ ] RGB-specific ISA extensions & RGB Core runtime
* [ ] ISA extensions for Lightning network & LNP Core runtime
* [ ] Citadel runtime for smart contract UI

**2022**

* [ ] Genetic algorithms ISA extensions and ReBICA runtime environment
* [ ] SIMD/machine learning ISA extensions
* [ ] ISA extensions for Internet2 networking and Web4 remote code execution

**2023**

* [ ] AluROS operating system for distributed computing

