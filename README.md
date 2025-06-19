# Manual OS: Public Edition  
**Rev: 20250619**  
_A lightweight method for controlling ChatGPT behavior using a pasted rule block._

---

## What This Is

This repository contains the public version of the **Manual OS**: a paste-at-start ruleset designed to give ChatGPT users more consistent behavior without relying on memory saves or external tools.

The Manual OS attempts to enable:

- Reliable multi-step workflows across a single chat
- Enhanced problem surfacing by ChatGPT
- More useful feedback on produced content
- Text freezing and lossless retrieval
- Token usage monitoring and re-anchoring
- Clear separation between proposals and approvals

All of this is done in-chat—ideal for mobile workflows or users seeking more consistency from ChatGPT without building a plugin or app.

---

## Why This Exists

The author was building complex projects with ChatGPT and began running into consistent issues:

- Previously written text would reappear with small but critical losses: missing words, altered phrasing, or dropped lines.
- Attempts to preserve logic and formatting using memory were inconsistent and unreliable.
- **One specific rule—the ability to freeze and later retrieve exact user-written text—was explicitly not allowed to be stored in ChatGPT’s memory system.** This created a hard limit on workflows that required high-fidelity reuse of earlier language.

To solve this, the author began pasting a ruleset manually at the beginning of each session. This paste-block governed how ChatGPT behaved, processed proposals, froze text for later reference, and warned about approaching token limits. The author refers to this system as the **Manual OS**—a workaround method for regaining control over structure, output, and consistency without external tools.

This system appears to help enable projects of higher complexity to survive ChatGPT’s default flattening and helps enforce boundaries in a flexible, in-chat way.

---

## How to Use It

1. Copy the `SESSION RULESET` file from this repo. I save the text on my notes app and copy and paste into the ChatGPT app from there.
2. Paste it into the start of any ChatGPT session.
3. Begin work as usual—ChatGPT will follow the ruleset exactly.

---

## Token Cost

The full public ruleset (as of Rev 20250618) costs ~700 tokens. My personal rule set that is more tailored to my needs takes up about twice that.

---

## Licensing

**Author:** Tim Shaw  
**License:** [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) — Attribution required, no commercial use.

This version of the Manual OS was developed independently through my own testing and collaboration with ChatGPT. To my knowledge, no identical system has been publicly released under open license, but similar approaches may exist. If you know of any, feel free to link them.
