### Hi, I'm Nikolai

I build small, sharp, zero-dependency tools for the quality and trust layer of LLM applications. One coherent family, covering the whole lifecycle of an AI app: author it, harden it, test it, ship it, watch it.

## The toolchain

| Stage | Tool | What it does |
| --- | --- | --- |
| Author | [redline](https://github.com/rxNxkolai/redline) | Lint prompt and agent-instruction files |
| Harden | [crucible](https://github.com/rxNxkolai/crucible) | Red-team a system prompt for security weaknesses |
| Gate | [warden](https://github.com/rxNxkolai/warden) | Lint agent permissions and tool configs |
| Render | [stencil](https://github.com/rxNxkolai/stencil) | Interpolate untrusted data into prompts safely |
| Test | [litmus](https://github.com/rxNxkolai/litmus) | Unit tests for prompts |
| Mock | [cassette](https://github.com/rxNxkolai/cassette) | Record and replay LLM calls for deterministic tests |
| Measure | [tally](https://github.com/rxNxkolai/tally) | Token, cost, and context-budget analysis |
| Repair | [rivet](https://github.com/rxNxkolai/rivet) | Validate and repair the JSON an LLM emits |
| Redact | [veil](https://github.com/rxNxkolai/veil) | Strip PII and secrets before text leaves your app |
| Verify | [veritas](https://github.com/rxNxkolai/veritas) | Check the claims and citations in an answer |
| Supervise | [quorum](https://github.com/rxNxkolai/quorum) | A council of critic-judges watching an agent loop |

Every tool: zero runtime dependencies, tested, CI-green on Node 18, 20, and 22, MIT licensed, with an interactive HTML report. Run any of them with `npx github:rxNxkolai/<tool>`.
