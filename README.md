# 👋 Greetings, Programs!

## 👾 I'm Tripp. I figure things out.

I'm a systems researcher — trained by the empirical, and wired to understand how things function at the lowest level. I read systems, find the gold nuggets in the constraints most miss, and reconfigure the conventional into something faster, smaller, and sometimes into something fundamentally novel.

My background spans IT support, project risk management for Shell, ExxonMobil, and Cameron Subsea, data center construction planning for Google and Microsoft, training and consulting for Oracle's P6 and Project Risk Analysis, digital communications, logistics, and now — computer and neural architecture research.

My fundamental strengths:

1. Bridging the gap between complex systems and the people who depend on them.
2. Optimizing how people and machines work together for common objectives.
3. Simplifying the unnecessarily complex into load-bearing essentials.

### True Story

In 1999, I was a Pre-Sales Engineer for a company specializing in fax broadcasting. In early 2001, our company decided to inflict its new email broadcasting service upon the world. In its infancy, it took our pre-sales teams hours to manually set up tests for these jobs — let alone deployment. We had to comb through text and HTML files to replace untrackable URLs with trackable URLs. Our teams had virtually no familiarity with HTML or the underlying mechanics of email message formatting. We were already swamped before this new service was dropped in our laps. It was crushing us.

I had no classical programming training. In point of fact, the last time I wrote anything in code was in the 5th grade on a [Tandy TRS-80 Color Computer with 4,096 bytes of RAM](https://en.wikipedia.org/wiki/TRS-80_Color_Computer) with a [cassette recorder](./assets/images/FMNzTXcX0AA0JM2.jpg_large) for saving and recalling programs.

But I understood the problem. And I knew it didn't have to be this hard.

Extremely motivated, I spent a weekend learning just enough Perl and regular expressions to write a small hosted app that let us upload our text and HTML docs, replace the embedded URLs with trackable URLs, and download the new files. It worked! It wasn't pretty — but it reduced hours of testing into minutes. The following Monday morning, I shared it with the pre-sales reps in our company. My inbox overflowed with emails of gratitude for giving the teams their days back.

I was hooked. I love solutions.

## Current Projects

My research is unified by a single thesis: ternary computation — arithmetic in the set {-1, 0, +1} — is not a compression trick or an optimization shortcut, but a fundamentally different computational paradigm with properties that conventional floating-point cannot access. These projects share a common engine of ternary primitives, Hamming arithmetic, and frozen deterministic execution.

- **MetaScorer** — Zero-config anomaly detection for embedded systems. Self-calibrates on 1,500 samples, commits a static threshold, and alerts when a signal deviates from learned dynamics. Fits in 9 kilobytes. Runs on industrial microcontrollers. No cloud, no training data, no configuration file.
- **The Reflex** — Ternary neural inference on a $6 microcontroller at ~50 µA. Computes signed dot products entirely through peripheral routing hardware — pulse counters and parallel I/O repurposed as ternary multipliers. Hand-written RISC-V assembly, 6,320 bytes. Includes a ternary Closed-form Continuous-time (CfC) neural network in 3,615 bytes.
- **SS|TT** — Zero-parameter ternary image classifier. 97.27% accuracy on MNIST with no learned parameters, no floating-point, and no gradient descent. Integer operations and table lookups only. All core data structures designed for L-Cache residency.
- **lcvdb** — Vector database designed for exact recall using ternary-encoded embeddings and Hamming distance. No approximate nearest neighbors. No probabilistic shortcuts.
- **L-Cache Kernels** — A 12-opcode AVX2/NEON instruction set expressing the same ternary arithmetic that runs on peripheral hardware and RISC-V assembly. 4,600x faster than silicon, bit-identical results. Fungible computation — substrate changes, math doesn't.

## Original Inspiration

- **[TriX](https://github.com/anjaustin/trix)** — 2-bit conditional ternary neural architecture with learned computational sparsity and emergent routing. Networks are trained, frozen, verified, and deployed — ML as engineering, not guesswork.
- **[Fungible Computation](https://github.com/anjaustin/fungible-computation)** — Demonstrating equivalence between neural and classical computation through exact digital emulation. The same ternary arithmetic runs on peripheral hardware, RISC-V assembly, and AVX2 L-Cache kernels — bit-identical across all three.
- **[FLYNNCONCEIVABLE](https://github.com/anjaustin/flynnconceivable)** — Verified neural implementation of the 6502 CPU.
- **[Hollywood Squares OS](https://github.com/anjaustin/hollywood-squares-os)** — Distributed micro-kernel for addressable processor networks with message-passing as the fundamental syscall interface.

## Methodical Madness

I document what doesn't work with the same care as what does. Failed experiments, falsified hypotheses, and benchmarked weaknesses are essential scaffolding. Every claim in my technical documentation traces to a specific test, audit, or benchmark. My company's anomaly detection system ships with twelve documented limitations and their supporting evidence. Decisions are gated on experimental outcomes, not projections.

In a field where overclaimed results are the norm, I treat intellectual honesty as infrastructure.

## Let's Connect

I'm open to collaboration, consulting engagements, and partnerships — particularly with people building systems that are inspectable, deterministic, and marvelously unconventional.

If you're working on something thoughtful or fringe, I'm listening.

- [LinkedIn](https://www.linkedin.com/in/anjaustin)

---
I have no idea what I am doing, but I know I am doing it really well.
