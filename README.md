# Daniel Bisar

**Senior Software Engineer — .NET, AI-Assisted Engineering & Developer Tooling**

I’m a software engineer with 15+ years of professional experience building and evolving software systems, primarily with C#/.NET. My work combines hands-on implementation, architecture, debugging, technical leadership, and making complex codebases easier to understand and change.

I’m particularly interested in **AI-assisted software engineering**: using coding agents as engineering tools while keeping requirements, architecture, verification, testing, and technical judgment explicit.

## Current focus

- C# / .NET and long-lived software systems
- AI-assisted engineering and coding-agent workflows
- Developer tooling and engineering productivity
- Architecture, codebase analysis, testing, and maintainability
- Python / PyTorch experimentation
- C++ / Linux / native and graphics integration

## Selected projects

### [code-map](https://github.com/danielbisar/code-map)
Experimental C# dependency explorer for codebase reconnaissance. It combines Roslyn syntax analysis with an interactive WebGL graph, with an explicitly heuristic analysis contract, automated regression coverage, and CI.

### [tinylm](https://github.com/danielbisar/tinylm)
Small-language-model experiments in PyTorch focused on correctness and measurement: sparse Mixture-of-Experts routing, tokenization, EOS-aware evaluation, checkpoint reliability, reproducible experiment provenance, and quality/runtime/memory trade-offs.

### [agent-sandbox](https://github.com/danielbisar/agent-sandbox)
Local non-root Docker and Podman environments for Codex, Claude Code, and Pi, with persistent state, version-aware image selection, explicit isolation limits, and regression-tested tooling.

### [Medja](https://github.com/danielbisar/Medja)
Historical employer-supported C# UI framework for embedded-style applications. It separates control behavior from rendering to enable headless interaction testing and includes substantial SkiaSharp/OpenGL/native integration. Published with SprintWORX attribution and permission.

### [OpenGL_inject](https://github.com/danielbisar/OpenGL_inject)
Bounded Linux/GLX rendering-interposition experiment using `LD_PRELOAD`, framebuffer capture, OpenGL state preservation, and a shader-based zoom inset. Kept intentionally small and explicit about its supported scope.

## Open-source contributions

### [LLM Tornado](https://github.com/lofcz/LLMTornado) — [PR #193](https://github.com/lofcz/LLMTornado/pull/193)
Contributed function-tool support and restorable conversation history to the .NET SDK's direct Codex OAuth integration. The change added streamed tool-call aggregation, host-controlled tool execution, automatic continuation with tool outputs, and typed history restoration that preserves function call IDs across process restarts.

## Professional background

- Senior IT Consultant / Technical Lead at msg systems ag
- Hands-on development and technical leadership in business-critical software
- Earlier experience leading a software-development department and an international development team
- Domains include finance, logistics, embedded/IoT, and business software

## Engineering approach

I prefer roles where architecture stays close to implementation. I like working directly with difficult systems: understanding existing behavior, reducing uncertainty, improving testability, debugging across abstraction boundaries, and building tools that make subsequent engineering work easier.

With AI-assisted development, I use agents aggressively for implementation and exploration, but treat generated code as untrusted until it is reviewed, tested, measured, and reconciled with the actual system behavior.

## Links

- [Credly](https://www.credly.com/users/daniel-bisar.15d67fac)
