# Manual OS: Public Edition  
**Rev: 20250619**  
_A lightweight method for controlling ChatGPT behavior using a pasted rule block._

---

## What This Is

This repository contains the public version of the **Manual OS**: a paste-at-start ruleset designed to give ChatGPT users more consistent behavior without relying on memory saves or external tools.

The Manual OS attempts to enable:

- Reliable multi-step workflows across a single chat
- Text freezing and lossless retrieval
- Token usage monitoring and re-anchoring
- Clear separation between proposals and approvals
- Optional extensions for dialogue co-writing and scoring

All of this is done in-chat—ideal for mobile workflows or users seeking more consistency from ChatGPT without building a plugin or app.

---

## Why This Exists

The author was building complex projects with ChatGPT and began running into consistent issues:

- Previously written text would reappear with small but critical losses: missing words, altered phrasing, or dropped lines.
- Attempts to preserve logic and formatting using memory were inconsistent and unreliable.
- **One specific rule—the ability to freeze and later retrieve exact user-written text—was explicitly not allowed to be stored in ChatGPT’s memory system.** This created a hard limit on workflows that required high-fidelity reuse of earlier language.

To solve this, the author began pasting a ruleset manually at the beginning of each session. This paste-block governed how ChatGPT behaved, processed proposals, froze text for later reference, and warned about approaching token limits. The author refers to this system as the **Manual OS**—a workaround method for regaining control over structure, output, and consistency without external tools.

This system enables projects of high complexity to survive ChatGPT’s default flattening and helps enforce boundaries in a flexible, in-chat way.

---

## How to Use It

1. Copy the `SESSION RULESET` file from this repo.
2. Paste it into the start of any ChatGPT session.
3. Begin work as usual—ChatGPT will follow the ruleset exactly.

---

## Token Cost

The full public ruleset (as of Rev 20250618) costs **~1,650 tokens**, well under 10% of the total context limit in GPT-4 and GPT-4o. This leaves room for most tasks while still enforcing structured behavior.

**Users may reduce token cost** by removing rules they don’t need:
- The validation marker rule (RULE_00) can be removed entirely.
- Optional rules (e.g., dual scoring, dialogue feedback) can be omitted.
- Examples can be trimmed to reduce size further.

---

## Licensing

**Author:** Tim Shaw  
**License:** [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) — Attribution required, no commercial use.

---

## Contributing

This repository is intentionally minimal. If interest grows, the author may expand it to include:
- Community variants of the Manual OS
- Plugins or wrappers
- Templates for structured workflows

For now, the core concept is simple: paste a ruleset, gain a little more control.
