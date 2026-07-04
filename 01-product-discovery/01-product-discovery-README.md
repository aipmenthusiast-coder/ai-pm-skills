# Product Discovery Skill README

This README explains how to use and customize the Product Discovery skill.

The skill file is here:

```text
01-product-discovery-skill.md
```

An example of a polished sample output is here:

```text
product-discovery-sample-output.html
```

Use the skill as a reusable AI partner for product discovery work: understanding customer problems, planning research, synthesizing evidence, evaluating opportunities, and preparing decision-ready discovery artifacts.

Product Discovery is meant to frame the problem and the opportunity around it. It is not meant to discover, design, or specify the final product solution. The output should make the problem clearer, identify what is known and unknown, and recommend what to learn or validate next.

## How To Use This Skill

There are three common ways to use the skill:

- Prompt template: paste the skill or the relevant sections into an AI tool when doing discovery work.
- Reusable agent instruction: add the full skill file to an agent, custom assistant, or project instruction set.
- Team-specific skill: copy the skill, add company context, connect relevant knowledge sources, and revise the outputs to match your team's standards.

For best results, do not rely on the generic skill alone. Product discovery is highly contextual. The agent will be much more useful when it can also use relevant context and supporting skill files that provide additional intelligence about your company, customers, market, products, and decision process.

Helpful supporting context files might include:

- Company strategy and annual priorities.
- Product vision, product principles, and roadmap themes.
- Customer segments, personas, and buyer versus user definitions.
- Market, competitor, and positioning notes.
- Pricing and packaging context.
- Research repository summaries.
- Customer interview summaries.
- Support ticket themes.
- Sales call themes.
- Product analytics definitions.
- Experiment history.
- Compliance, privacy, legal, brand, or security requirements.
- Examples of strong internal discovery briefs, PRDs, research summaries, or decision memos.

Helpful supporting skill files might include:

- Customer research synthesis skill.
- Product analytics skill.
- Market and competitive research skill.
- Roadmap prioritization skill.
- PRD generation skill.
- Experiment design skill.
- Executive storytelling skill.

The Product Discovery skill can run on its own, but these additional context and skill files help the agent reason with your company's reality instead of giving generic product advice.

## Key Information To Provide The Agent

The agent can help with partial information, but it creates much stronger discovery work when the PM provides the right starting context.

At minimum, provide:

- Product, feature, workflow, or business area.
- Target customer, user, buyer, or operator segment.
- Problem, opportunity, or question you want to explore.
- Business goal or strategic priority.
- Decision the discovery work needs to support.
- Existing evidence or signals.
- Desired output format.

When available, also provide:

- Relevant customer feedback.
- User research notes.
- Analytics or usage data.
- Support tickets or sales call notes.
- Market, competitor, or regulatory context.
- Known constraints.
- Timeline or decision deadline.
- Stakeholders who need to use the output.
- Success metrics or business outcomes.
- Prior decisions or rejected options.

If the PM does not have all of this information, they should still start. The skill is designed to identify gaps, ask for the most important missing information, and recommend the smallest useful next discovery activity.

## Example Prompts

### Start From A Vague Idea

```text
Use the Product Discovery skill. Help me frame discovery for this idea: [idea]. Ask only the most important clarifying questions, then create a short discovery brief with assumptions, risks, and recommended next steps.
```

### Turn Feedback Into Themes

```text
Use the Product Discovery skill. Synthesize the following customer feedback into themes, jobs-to-be-done, pain points, evidence strength, contradictions, and recommended discovery actions.

[Paste feedback]
```

### Create An Interview Guide

```text
Use the Product Discovery skill. Create a customer interview guide for [target segment] about [problem/workflow]. The goal is to learn [learning goal]. Include warm-up questions, core questions, probes, and a notes framework.
```

### Evaluate An Opportunity

```text
Use the Product Discovery skill. Assess this opportunity: [opportunity]. Identify the customer problem, evidence, assumptions, risks, learning plan, success measures, and a recommendation on whether to continue discovery, test, define, or pause.
```

### Prepare A Decision Memo

```text
Use the Product Discovery skill. Create a decision memo for leadership based on this discovery work. Separate facts from interpretation, summarize evidence, name risks, compare options, and recommend the next product decision.

[Paste discovery notes, research summary, metrics, or context]
```

### Real-World Starter Prompts

```text
Run product discovery on this: our support team says users keep asking for "better search." Here are 15 support tickets and 3 interview summaries. Help me figure out what's actually going on.
```

```text
A VP wants us to build an AI chatbot for onboarding. I don't have research yet. Help me figure out what we need to learn before deciding anything.
```

```text
Here's our churn survey data for enterprise accounts. What are the real problems underneath the answers?
```

## How To Customize This Skill For Your Team

Teams should modify the skill so the agent understands their business, customers, language, standards, and decision process.

Start by adding:

- Company description.
- Product portfolio.
- Target customers.
- User segments or personas.
- Buyer versus user distinction.
- Core workflows.
- Company strategy.
- Product principles.
- Discovery standards.
- Research ethics or privacy rules.
- Data sources.
- Common metrics.
- Decision-making forums.
- Required artifacts.
- Preferred writing style.
- Terms the company uses.
- Terms the company avoids.

Replace generic examples with examples from your own product area.

## How To Enhance This With A Relevant Context Agent

To make the skill more powerful, turn it into an agent that can use relevant context. The agent should not just answer generic discovery questions. It should help your team discover opportunities in the way your company actually works.

### 1. Add Company Knowledge

Give the agent concise reference material such as:

- Company strategy and annual priorities.
- Product vision and product principles.
- Current roadmap themes.
- Customer segments and personas.
- Market positioning.
- Pricing and packaging basics.
- Competitive landscape.
- Known product constraints.
- Compliance, legal, safety, privacy, or brand requirements.
- Historical discovery summaries.
- Examples of strong prior discovery briefs or PRDs.

Keep this material current and remove outdated strategy or stale assumptions.

### 2. Connect Useful Discovery Sources

If your AI environment supports connected tools, give the agent access to approved sources such as:

- Customer interview repository.
- Research reports.
- Support ticket system.
- Sales call transcripts.
- CRM notes.
- Product analytics.
- Experiment results.
- NPS, CSAT, or survey tools.
- Data warehouse summaries.
- Roadmap or planning system.
- Documentation or knowledge base.

Define which sources are trusted, which are directional, and which require human verification.

### 3. Teach The Agent Your Decision Rules

Add rules that reflect how your company makes product decisions.

Examples:

- Prioritize opportunities tied to [company strategic pillar].
- Do not recommend roadmap commitment without evidence from at least [number] customers or [data source].
- Flag enterprise-only requests separately from broad market needs.
- Treat requests from top accounts as important signals, not automatic priorities.
- Consider support burden, implementation cost, and operational complexity.
- Include accessibility, privacy, security, and compliance risks in every recommendation.
- Prefer experiments that can produce learning within [timebox].

### 4. Define Standard Outputs

Tell the agent which artifacts your team expects and what good looks like.

Examples:

- Discovery brief.
- Problem statement.
- Opportunity assessment.
- Customer interview guide.
- Research synthesis.
- Opportunity solution tree.
- Experiment plan.
- Leadership decision memo.
- Handoff notes for design and engineering.

Include examples of excellent internal artifacts if you have them.

### 5. Add Escalation And Guardrail Instructions

The agent should know when to slow down, ask for help, or warn the product manager.

Add instructions such as:

- Flag when evidence is too weak for a product decision.
- Flag when the request may contain sensitive customer data.
- Do not invent customer quotes, metrics, or research findings.
- Label speculative recommendations clearly.
- Ask for legal, security, data, or compliance review when relevant.
- Identify when a discovery question needs direct customer research rather than desk research.
- Identify when the product manager is prematurely solutioning.

### 6. Create A Relevant Context Agent Starter Prompt

Use this starter prompt when configuring the agent:

```text
You are our Product Discovery agent for [company/team]. You help product managers discover customer problems, assess opportunities, plan research, synthesize evidence, and prepare decision-ready discovery artifacts.

Use our company context:
- Company/product:
- Target customers:
- Priority segments:
- Strategic priorities:
- Product principles:
- Key metrics:
- Data sources you may use:
- Required discovery artifacts:
- Decision rules:
- Guardrails:

When responding:
1. Start with the customer problem and decision needed.
2. Separate evidence from interpretation.
3. Identify assumptions, risks, and evidence gaps.
4. Recommend the smallest useful next discovery activity.
5. Use our internal language and artifact formats.
6. Do not invent customer evidence, metrics, or commitments.
7. Flag when human review is required.
```

## Team Setup Checklist

Before asking product managers to use this skill, complete this checklist:

- Copy the Product Discovery skill into your team's AI workspace or agent builder.
- Add the README or a shorter usage guide where PMs can find it.
- Replace placeholders with your company and product context.
- Add one or two examples of strong discovery outputs.
- Define approved data sources.
- Define what the agent is not allowed to access or infer.
- Add decision rules for roadmap, research, and leadership review.
- Add relevant context files or supporting skill files where useful.
- Test the skill on a real but low-risk discovery question.
- Compare the output against your team's standards.
- Revise the skill based on what was missing, too generic, or too verbose.
- Share example prompts with the team.
