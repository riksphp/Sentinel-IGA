Sentinel IGA 🛡️

The Agentic Governance-as-Code Orchestrator
Sentinel IGA is a multi-agent system built from the ground up to solve the "Identity Crisis" in AI-augmented development. It transforms the passive code review process into a proactive Governance-as-Code (GaC) decision engine, specifically designed to detect entitlement creep and Segregation of Duties (SoD) violations in real-time.

🚀 The Core Innovation

Unlike standard CI/CD tools, Sentinel IGA does not just scan for syntax. It utilizes a Manual Cognitive Loop to reason about the identity implications of code changes.

Repository Brain: A stateful knowledge base that provides long-term memory of architectural patterns.

Multi-Agent Coordination: A custom-built state machine that orchestrates 9 specialized agents (Security, Identity, Performance, etc.) without external frameworks.

MCP-Driven Governance: Leverages the Model Context Protocol to fetch live organizational IGA policies to verify compliance.

🏗️ Architecture

Sentinel IGA is built on a Modular Agentic Architecture consisting of four primary layers:

Perception Layer: Uses AST-aware chunking to parse repository context.

Memory Layer: A custom RAG implementation using a Vector DB for "Long-term Architectural Memory."

Reasoning Layer: A manual state-transition engine that coordinates specialized agents through a shared context object.

Action Layer: A tool-calling interface that uses MCP to browse files and query external governance APIs.

🛠️ Key Features

SoD Detection: Automatically identifies "Toxic Combinations" of permissions introduced in code.

Context Isolation: Logical multi-tenancy ensures zero data leakage between repository contexts.

Adversarial Defense: Hardened against Indirect Prompt Injection via code comments.

Unified Scorecard: Generates a binary PASS/FAIL verdict with a detailed risk-reasoning report.

📋 Roadmap (MVP1 - 30 Days)

[x] Phase 1: AST Chunker & Repository Indexing (Day 1-5)

[ ] Phase 2: MCP Server & Tool-Calling Logic (Day 6-10)

[ ] Phase 3: Manual State Machine & Supervisor Node (Day 11-15)

[ ] Phase 4: Red Teaming & ArXiv Paper Finalization (Day 16-20)

💻 Tech Stack

Language: TypeScript / Python

Database: ChromaDB (Vector Store)

Protocol: Model Context Protocol (MCP)

LLM Internals: Transformer-based reasoning with custom Chain-of-Thought (CoT) prompting.

📄 Capstone Documentation

The technical research behind this project is detailed in our ArXiv-style whitepaper: <TBD>. It covers the novelty of manual agentic orchestration in the Identity Governance domain.

🤝 Contributing

Sentinel IGA is a capstone project built for the Agentic AI Course. For inquiries regarding enterprise IGA integration (Saviynt, etc.), please reach out via the Issues tab.
