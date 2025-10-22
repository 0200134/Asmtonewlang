
🧬 Asmtonewlang


“Born from Assembly, evolved by R3C.”


🧭 Overview


Asmtonewlang is a R3C-based experimental language project that evolves from the assembly-level outputs of the R3C compiler.

It extends the LLVM-free compiler philosophy — transforming NASM assembly into a new generation high-level language built for autonomy, transparency, and control.




Pipeline:

C++ → Rust → ASM → NewLang

(Where R3C stops, Asmtonewlang begins.)





⚙️ Purpose




Explore reverse transpilation — building a high-level syntax from R3C’s NASM output.


Study how low-level semantics can be reconstructed into structured logic.


Preserve R3C’s zero-dependency / cross-platform build principles.


Extend the LLVM-Zero Ecosystem, keeping the same “self-hosting” design philosophy.





🧩 Core Concepts




Concept
Description




Base
Built on top of R3C’s ASM backend and parser


Input
NASM assembly emitted by R3C


Output
Human-readable, C-like or Rust-like “NewLang” syntax


Goal
Demonstrate post-assembly language evolution


Compatibility
Fully interoperable with R3C transpiler outputs





🧱 Architecture


+-----------------------+
|       C++ Front       |
+----------+------------+
           ↓
+-----------------------+
|       Rust Stage      |
+----------+------------+
           ↓
+-----------------------+
|        ASM Core       |
+----------+------------+
           ↓
+-----------------------+
|     Asmtonewlang      |
|  (Reverse Transpiler) |
+-----------------------+





Parser: NASM syntax tree analyzer (based on R3C’s codegen layer)


Transpiler: Converts assembly patterns into structured code blocks


Emitter: Outputs “NewLang” — a readable experimental high-level language





🧠 Design Philosophy




“Assembly is not the end — it’s the beginning of understanding.”

“Languages die when they forget their roots.”


Asmtonewlang exists to prove that evolution can go in both directions:

from abstraction to metal — and from metal to new abstraction.





🧩 Ecosystem Links




🪶 R3C — Core compiler (C++ → Rust → ASM)


🧱 cpppm — Minimal package manager


🦀 Rust-ltss — Long-term stable Rust layer


⚙️ Asmtonewlang — This project (ASM → NewLang)





🔧 Future Goals




Phase
Description
Status




1
Implement NASM parser (AST reconstruction)
🚧 In progress


2
Define NewLang syntax rules
⏳ Planned


3
Prototype reverse transpiler
⏳ Planned


4
Integrate with R3C toolchain
⏳ Planned


5
Self-hosting test suite
⏳ Planned





📜 License


MIT License — same as R3C.




“Freedom to build, freedom to evolve.”


