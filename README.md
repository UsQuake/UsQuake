## 👋 Hi, I'm Ssong

I study how system is *✏️ represented*, *🤝 communicated*, *💯 tested*, *🌊 flowed*, *🧹 erased*, and *✊ evolved*.

### 😆 I'm interested in:

- how to make system learn 🗑️ forgetting.
  + like, [**♻ garbage collection**](https://shipilev.net/jvm/diy-gc/)
  + and [*👉 attention*-based **denoiser**](https://dl.acm.org/doi/10.1145/3660800).
- how to make system learn 🔡 representation and 🦠 evolution itself.
  + like, [🔁 ***self-supervised learning***](https://www.youtube.com/watch?v=AfqWt1rk7TE)
  + and [🌱 ***evolutionary*** learning](https://dl.acm.org/doi/pdf/10.1145/3180155.3180160).
- how to make system (﹙˓ 📶 ˒﹚) communicates.  
  + like, [*🤝 protocols* for different **PLs**](https://protobuf.dev/)
  + and [memory-mapped ***🔌 in and out***](https://dl.acm.org/doi/abs/10.1145/3620665.3640389).
- how to make system 💯 tests one another and 🔧 & 📌 fix with 💾 memorization itself.
  + like, [kleene's *📌 fix-point* theorem](https://ropas.snu.ac.kr/~kwang/520/readings/absint/Cousot-JLC-1992.pdf)
  + and [⚖️ differential **💯 testing**](https://github.com/UsQuake/why_wasm_compiler_fuzzing_hard).
- how to make system 🎲 simulates & 🗣️ interprets internally.
  + like, [***🤖 turing-complete*** world models](https://ai.meta.com/vjepa/).
  + and [***reasoning & understanding***](https://arxiv.org/pdf/2607.05188).


### 🤔 I'm currently focusing on:

I'm researching ***how to 💯 test 🖼️ GUI-apps(like, 🌐 browsers, >_ terminal-emulators and 🕹️ games).***:
 - Implementing 🔴 record & ▶ replay with RenderDoc-like techs.
   + gfxreconstruct
   + ydotool
 - Encoding 🎬 framebuffer with **🌀 abstraction** methods like ⌗ hashing.
   + ssdeep

### 🏅 Selected Contributions

- 🐧 **Reported and debugged a Linux kernel audio regression**
  + Reproduced a hard system freeze on an AMD HawkPoint ThinkPad.
  + Provided `dmesg`, ACPI dumps, hardware traces, and regression-test results.
  + Verified the offending change through a kernel revert; the issue was resolved with a code fix.
  + [Bug 221274](https://bugzilla.kernel.org/show_bug.cgi?id=221274)

- 📚 **Reviewed Korean translations for [`phil-opp/blog_os`](https://github.com/phil-opp/blog_os)**
  + Reviewed the Korean updates in [PR #1500](https://github.com/phil-opp/blog_os/pull/1500).
  + Identified typos and inaccurate systems terminology related to stack pointers, SIMD instruction sets, and `rust-analyzer`.
