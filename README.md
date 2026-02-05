# Agentic-AI-Quickstart-From-LLM-to-Working-Agents
## 0. What is this repo?
This repository is a **quickstart knowledge base** for Agentic AI. The goal is to help you:
- Understand the core ideas (planning, memory, tool-use, safety, evaluation, cost/latency)
- Choose the right frameworks/tools (without getting lost in the ecosystem)
- Build a minimal working agent (MVP), then gradually make it more reliable and ready to produce

## Suggested learning path
**Beginner (1–2 hours)**
1) Learn the basic concepts  
2) Pick one orchestration framework/SDK and run a single-agent demo  
3) Add one tool (search/retrieval/DB)  
4) Add one safety layer (guardrails)  
5) Add eval (observability)

# Part I — Frameworks ✅
Below is a curated list of frameworks/platforms that are useful for getting started quickly.
## 1. Agentic AI Basics (Concepts)
**Agentic AI Basics: Basic knowledge about Agentic AI**  
- Purpose: a structured intro to what “agentic AI” means and how to think about planning, tools, and memory  
- Link: https://learn.deeplearning.ai/courses/agentic-ai/information

  ---

## 2. LangGraph (Controllable orchestration)
**LangGraph: Graph-style orchestration for controllable multi-step agents**  
- Keywords: state machines, graph workflows, controllability, reliability, testing  
- Best for: building multi-step agents you can **control, debug, and maintain**  
- Link: https://github.com/langchain-ai/langgraph

---

## 3. CrewAI (Role-based multi-agent)
**CrewAI: Role-based multi-agent collaboration; quick to prototype “teams” of agents**  
- Keywords: roles, delegation, parallelization, “agent teams”  
- Best for: fast demos of multi-agent collaboration (planner / coder / reviewer / researcher)  
- Link: https://github.com/crewAIInc/crewAI

---

## 4. PydanticAI (Structured & validated outputs)
**PydanticAI: Enforces structured, validated outputs for safer tool calls and cleaner pipelines**  
- Keywords: typed outputs, schema validation, safer tool execution, auditability  
- Best for: engineering-focused pipelines where you want **strict JSON / structured outputs**  
- Link: https://github.com/pydantic/pydantic-ai

---

## 5. MCP (Model Context Protocol)
**MCP: A standard interface to connect agents to tools/data via reusable servers**  
- Keywords: tool/data interoperability, reusable connectors, less glue code  
- Best for: teams that want “connect once, reuse everywhere” across frameworks  
- Link: https://github.com/modelcontextprotocol

---

## 6. NeMo Guardrails (Safety & compliance)
**NeMo Guardrails: Policy-based input/output controls for LLM agents**  
- Keywords: safety, compliance, prompt-injection/jailbreak mitigation, governance  
- Best for: production or sensitive environments where risk control matters  
- Link: https://github.com/NVIDIA-NeMo/Guardrails

---

## 7. Dify (Low-code platform)
**Dify: A low-code platform with visual workflows and built-in debugging**  
- Keywords: fast prototyping, visual pipelines, quick deployment, debugging UI  
- Best for: shipping a demo quickly, then iterating toward a full implementation  
- Link: https://github.com/langgenius/dify

---

## 8. OpenAI Agents SDK (Production-oriented primitives)
**OpenAI Agents SDK: Lightweight primitives for agents & multi-agent workflows with tracing/observability**  
- Keywords: production-minded building blocks, tracing, debugging, rapid development  
- Best for: quickly building and debugging agentic apps with built-in observability  
- Link: https://openai.github.io/openai-agents-python/?utm_source=chatgpt.com

## Framework Comparison (at a glance)

![Agentic AI framework comparison matrix](https://github.com/Ellawjjjj/Agentic-AI-Quickstart-From-LLM-to-Working-Agents/blob/main/framework-comparison.png)

---
# Part II — Paper link

## Paper Lists 

| Paper List / Repo Name | Link |
|---|---|
| Awesome Agentic Reasoning | [GitHub](https://github.com/weitianxin/Awesome-Agentic-Reasoning) |
| AI Agent Papers | [GitHub](https://github.com/masamasa59/ai-agent-papers) |
| Awesome Agent Papers | [GitHub](https://github.com/luo-junyu/Awesome-Agent-Papers) |


