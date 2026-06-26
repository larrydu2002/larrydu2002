Hi, I'm Lei 👋

I build and ship AI-powered systems end-to-end. Solo. From problem framing to production.

Currently shipping a range of solo-built AI systems — two production maths-tutoring platforms, a hand-written agent, an MCP implementation, and a controlled pipeline:

🧠 X1 — Adaptive 1-on-1 tutor across NSW Maths Years 7–12. React 18 · FastAPI · Claude · OpenAI. 85 topics, 273 knowledge points, 8 curriculum streams.

📐 aitutormaths.com — HSC exam-intelligence platform. Live in production. Mock papers across all 4 NSW Maths streams, with AI photo-marking and multi-model QA gates.

🤖 Product-Listing Agent — a tool-use agent built from scratch on the Anthropic API, no framework. Given just a product name, the model decides which tools to call and when it's done — fetch specs, find missing fields, generate them, verify its own work. Hand-written loop, every decision point visible and defensible. github.com/larrydu2002/product-agent

🔌 MCP from scratch — a minimal Model Context Protocol server + client, hand-written over raw JSON-RPC on stdio. No SDK, no framework — standard library only. Built to understand MCP's transport layer by hitting every sharp edge myself: why the client launches the server, why stdout is protocol-only, why a shell pipe can't do two-way RPC. github.com/larrydu2002/mcp-from-scratch

📂 Strata Manager — a controlled multi-stage pipeline turning years of scattered email into structured, evidence-backed legal case files. Deliberately a pipeline, not an agent — high-compliance, auditable context where predictability matters more than autonomy.

How I work: define the measurable benefit before building (X1 cut API calls ~50% by design, before anything else shipped) · engineer for reliability where the model can't be trusted (deterministic grading rules, deterministic graph engine, sandboxed execution) · stay close to real users and prune what isn't earning its place.

Background: 15+ years between business and engineering teams at Oracle, Citrix and IBM — including the first XenMobile deployment in the Chinese banking sector and the first CloudPlatform order in mainland China (Ping An Insurance). Now back to building with my own hands.

Stack I'm shipping with: React · FastAPI · Python · SQL · Claude API (Opus, Sonnet) · OpenAI APIs · prompt & agent design · multi-model QA workflows · hand-written MCP server + client over raw JSON-RPC (stdio, no SDK).

📍 Sydney, NSW  ·  📧 larrydu2002@users.noreply.github.com  ·  🔗 aitutormaths.com
