# SignalOps — Product Brief

## Product question
How can a product team turn noisy evidence into faster decisions without allowing AI to obscure the source or own the roadmap decision?

## User
A PM working across an enterprise application platform with inputs arriving from public issues, customer conversations, support and internal teams.

## Job to be done
When product evidence arrives from different channels, help me understand what it says, compare it with other signals and record a decision without losing provenance.

## Prototype scope
SignalOps combines:
1. recent public issues from the ToolJet GitHub repository; and
2. clearly labeled synthetic enterprise feedback.

The PM can search and filter signals, inspect the original evidence, modify the interpretation and make a final decision.

## Product principles
- **Preserve evidence.** Interpretation should never replace the raw source.
- **Human-controlled prioritization.** AI may summarize or classify. A person owns the consequential roadmap decision.
- **Make uncertainty visible.** Weak or ambiguous signals should trigger discovery rather than false precision.
- **Prefer transparent mechanics.** Priority inputs should be inspectable and challengeable.
- **Do not fabricate customer truth.** Synthetic feedback is visibly synthetic.

## What AI is useful for
- summarizing long reports;
- suggesting product areas;
- proposing severity;
- clustering related signals;
- surfacing missing context;
- identifying uncertainty.

## What AI should not do
- invent prevalence or business value;
- silently alter source evidence;
- infer revenue impact without evidence;
- auto-approve roadmap priority;
- hide uncertainty behind a score.

## Success metrics
- median time from new signal to reviewed decision;
- percentage of decisions with intact source provenance;
- PM override rate on machine suggestions;
- duplicate-signal consolidation rate;
- percentage of prioritized signals later supported by additional evidence.

## Limitations
- Customer examples are synthetic.
- Browser-only persistence is used for the demo.
- GitHub's unauthenticated API can be rate-limited.
- The prototype demonstrates the workflow rather than a production backend.

## Next validation
Compare AI-assisted triage against PM-labeled examples and measure whether the workflow reduces review time without degrading decision quality.