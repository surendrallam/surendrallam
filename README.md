# Surendra Allam

Senior AI engineer in Bengaluru. I build AI agents and LLM features into products that already have users, then measure them: accuracy, cost per answer, latency.

### Featured: [ask-your-data-agent](https://github.com/surendrallam/ask-your-data-agent)

A Claude agent that answers business questions with read-only SQL, applies governed metric definitions, asks when a name is ambiguous, and shows the query behind every number. Benchmarked on 50 questions, three runs each, graded by re-running the SQL:

| Model | Accuracy (150 runs) | $ per 1,000 questions |
|---|---|---|
| Claude Haiku 5.5 | 96.7% | $0.67 |
| Claude Sonnet 5.5 | 100% | $8.34 |
| Claude Opus 5.5 | 100% | $19.70 |

### More benchmarked projects

| Project | What it shows |
|---|---|
| [grounded-rag-assistant](https://github.com/surendrallam/grounded-rag-assistant) | A support assistant that answers only from your documents and cites every answer. 64-question benchmark across Claude models: Haiku with Sonnet re-asking failed checks passed 192 of 192 at $0.74 per 1,000 questions. |
| [refund-triage-agent](https://github.com/surendrallam/refund-triage-agent) | An agent for refund emails: Claude reads and writes, code decides eligibility, amounts and limits. 30 scenarios x 3 runs per model, audited three times: Haiku 90 of 90 at $0.60 per 1,000 tickets, Sonnet 90 of 90, Opus 89 of 90, and 0 rule violations. |

### What I build

- AI features and tool-calling agents in existing products
- Knowledge assistants with citations, and ask-your-data over SQL or graph databases
- LLM cost and latency: prompt caching, model routing, evaluations
- Voice agents in English, Hindi and Hinglish

### Track record

- 10+ years in AI engineering; IEEE-published deep-learning research
- A plain-English data assistant live in three production products (Amazon Bedrock, Neo4j)
- Repeat-query LLM cost cut by about 90% on a production assistant
- Feature delivery from weeks to days after moving a team to AI-first development with Claude Code
