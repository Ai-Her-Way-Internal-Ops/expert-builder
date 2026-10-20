# The Expert Builder
## Hire for what you need to learn.
A guided starter kit from AI Her Way. Build a specialist agent with curated sources, decision rules and an audition that shows whether it can do the work.

A useful specialist should bring knowledge and judgement beyond the brief you give it. This kit helps you define that standard, build a source-backed knowledge base and test it. It adapts the source curation, distillation, evaluation and refresh methods in AI Her Way's operating system into a small first build.

**Start here:** open this folder in an AI workspace with file access and paste the prompt in [START-HERE.md](START-HERE.md). Read the resulting role brief and proposed sources before research begins. Use public or permissioned material. Your existing AI subscription or API usage may incur costs.

## What you leave with
- A bounded role brief: who the specialist serves and the decisions it helps with.
- A source register with dates, supporting passages, coverage and disagreements.
- An expert brief containing principles, exceptions, failure modes and known gaps.
- An agent definition that uses that knowledge and the relevant task skills.
- An audition comparing the specialist with the ordinary assistant on the same fresh tasks.
- A refresh date and a record of what changed.

The instructions are ready to use. Your domain expert is built and evaluated during setup. Installing files alone does not create a tested expert, scheduled research or new permissions.

## First useful build
Choose a narrow job such as “assess an onboarding email against our product documentation”. Start with a handful of strong sources and three realistic assignments. Expand the source base when a question exposes a gap. The target is demonstrated usefulness, not a claimed number of hours of human expertise.

## Run modes
- **Agent-capable workspace:** explicitly ask it to run `.claude/agents/expert-builder.md` and load `skills/build-expert/SKILL.md`. The file layout is provided for compatible workspaces; check which files your runtime loads. A model that can research, write files and call separate reviewers can carry the workflow.
- **Chat-only:** paste START-HERE and supply the requested source extracts. Save outputs yourself. Use a fresh conversation for the audition evaluator. File retrieval, delegation and refresh are manual unless connected and tested.

A skill gives the agent a reusable method. The agent definition supplies scope, routing, context and stopping rules. The runtime supplies execution and tools. This kit is portable instructions and templates, not a hosted service or automatic installer.

Try the [synthetic example](examples/first-audition.md) before adding business data. For a real expert, gather external domain evidence and test fresh cases.

## Continue
Want to connect a first business agent with its skills and a separate checker? Explore [The AI Handover Bootcamp](https://go.aiherway.com.au/bootcamp-2026).
