# ai-engineer-roadmap

Phase 1 — Days 1–7: LLM Intuition & First API Calls
Days 1–3: Understand how LLMs actually work
Your goal here is mental models, not math. You don't need to implement backprop — you need to understand why LLMs behave the way they do.

YouTube: 3Blue1Brown — But what is a GPT? — the single best visual explanation of transformers (45 min, worth every minute)
YouTube: Andrej Karpathy — Intro to Large Language Models — a practitioner's mental model (1 hr)
YouTube: Jay Alammar — The Illustrated Transformer (visual walkthrough of his blog)
Article: Jay Alammar's blog — The Illustrated GPT-2 — read slowly, revisit diagrams
Article: Simon Willison — What I learned from GPT — a practitioner's framing

Days 4–5: Calling models from code
You're a Java engineer, so Python will feel slightly foreign. Lean into it — all LLM tooling is Python-first.

YouTube: Tech With Tim — OpenAI API Python Tutorial
YouTube: Fireship — Anthropic Claude API in 100 seconds (search "Anthropic Claude API tutorial fireship")
Docs to read: OpenAI API Best Practices + Anthropic Prompting Guide
Article: Chip Huyen — Building LLM Applications for Production — essential reading for a backend engineer crossing over

Days 6–7: Build your first LLM-powered endpoint
Tie your Java/backend instincts to AI. Build a simple REST API that accepts a question, sends it to an LLM, and returns a structured response.

YouTube: Patrick Loeber — FastAPI + OpenAI Tutorial
Use Python + FastAPI (this is the standard in the AI space — worth learning now)


Phase 2 — Days 8–16: RAG, Tool Calling & Structured Outputs
Days 8–10: RAG pipelines
Most AI engineering roles involve RAG. This is your biggest leverage point.

YouTube: Sam Witteveen — RAG from scratch
YouTube: LlamaIndex — Official RAG tutorial playlist on their YouTube channel
YouTube: Tech With Tim — LangChain RAG Tutorial
Article: Pinecone — What is RAG? (long-form guide)
Article: LangChain RAG conceptual guide
Free e-book: Mastering RAG — Galileo AI — read chapters 1–4

Days 11–13: Tool calling & simple agents
This is where your systems engineering instincts kick in — think of tool calling as dependency injection for AI.

YouTube: Andrej Karpathy — State of GPT — covers agents and tool use conceptually
YouTube: James Briggs — LangGraph Agents Tutorial
Docs: Anthropic Tool Use Docs — read fully, it's concise and excellent
Docs: OpenAI Function Calling
Article: Lilian Weng — LLM Powered Autonomous Agents — the definitive deep-dive

Days 14–16: Structured outputs + prompt engineering depth

YouTube: Prompt Engineering Guide — YouTube channel — pick 3–4 videos
YouTube: DeepLearning.AI — ChatGPT Prompt Engineering for Developers (free, ~2 hrs)
Article: OpenAI Structured Outputs Guide
Docs: Pydantic — spend half a day here, it'll pay off for the rest of your career in AI


Phase 3 — Days 17–24: Evals, Deployment & Cost Control
Days 17–19: Evaluation
This is the gap between junior and senior AI engineers. Most people skip it. Don't.

YouTube: Hamel Husain — LLM Evaluation Masterclass (search "Hamel LLM evals")
YouTube: DeepLearning.AI — Building and Evaluating Advanced RAG (free)
Article: Shreya Shankar — Who validates the validators? — practical take
Free e-book: Mastering LLM-as-a-judge — Galileo
Tool to explore: LangSmith + Braintrust

Days 20–22: Deploying to production
As a Java backend engineer, this is your comfort zone — apply your instincts here.

YouTube: Patrick Loeber — Deploy ML models with FastAPI
Article: OpenTelemetry for LLM observability — skim the concepts section
Article: Google Cloud Retry Strategy — treat LLM APIs like any unreliable external service (you already know this pattern)

Days 23–24: Cost & latency

Article: Anthropic — Reducing costs guide
YouTube: Search "LLM prompt caching tutorial" — several good 20-min explainers
Article: vLLM overview — skim to understand throughput/batching concepts even if you won't use it immediately


Phase 4 — Days 25–30: Portfolio Project + Job Prep
Build one capstone project. The best AI engineer portfolio project for your background is a production-grade RAG API: a service that ingests documents, embeds them, stores in a vector DB, exposes a query endpoint with streaming responses, structured outputs, evals, and basic cost logging. It proves everything an employer cares about.
Interview prep resources:

YouTube: Exponent — AI Engineer Mock Interview (search "AI engineer interview questions 2024")
Article: Eugene Yan — Patterns for Building LLM Applications — read this before any interview
Article: Chip Huyen — AI Engineering roles — understand how companies think about the role
