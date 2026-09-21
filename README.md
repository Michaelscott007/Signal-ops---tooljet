# SignalOps

**Product Intelligence Command Center**

SignalOps is a compact product exercise exploring how product teams can turn noisy product evidence into traceable decisions without handing roadmap judgment over to AI.

It is inspired by ToolJet's Technical APM role and by the broader problem of operating AI-assisted enterprise software responsibly.

## The product question

How can a product team turn noisy evidence into faster decisions without allowing AI to obscure the source or own the roadmap decision?

SignalOps combines:

- recent public issues from the `ToolJet/ToolJet` GitHub repository;
- clearly labeled synthetic enterprise feedback.

A PM can search and filter signals, inspect original evidence, review structured interpretation, override it, and record a final decision.

## Product principle

> AI can structure evidence. It should not silently make the final product decision.

The PM should always be able to see the source, change the interpretation, override a recommendation and explain the final decision.

## Demo capabilities

- Live read-only fetch of public ToolJet GitHub issues
- Pull requests filtered from GitHub's issues endpoint
- Unified signal inbox
- Human review workbench
- Transparent prioritization inputs
- Browser-only persistence for demo decisions
- Loading / empty / failure states
- Explicit provenance for every signal

## Data policy

- GitHub issues are public data from `ToolJet/ToolJet`.
- All customer feedback in the prototype is synthetic.
- No real ToolJet customer information is represented.
- No credentials or private APIs are used.

## Run locally

Open `index.html` directly, or:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files

- `index.html` — application shell
- `style.css` — UI system
- `app.js` — GitHub ingestion, normalization, scoring, filtering and review state
- `PRODUCT_BRIEF.md` — product rationale and validation plan
- `DEMO_SCRIPT.md` — 90-second walkthrough

## Intentional limitation

This is a portable browser prototype rather than a native ToolJet implementation. A production version would move persistence, permissions, workflow execution and AI evaluation into governed backend services or ToolJet-native components.

## Why this exercise

The goal is not to demonstrate dashboard construction. It is to demonstrate product judgment across ambiguous evidence, APIs, data modeling, prioritization, AI boundaries, enterprise UX and human review.

---

Built by Jainil Trivedi as an independent product exercise. ToolJet is not affiliated with or responsible for this demo.
