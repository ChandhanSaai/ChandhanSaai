# Hi, I'm Chandhan 👋

**Applied AI engineer in San Francisco.** I build LLM systems and the proof that they work: evaluation
harnesses, AI agents, reinforcement-learning environments, and the production backend they run on.
Background in robotics (M.Eng, University of Maryland), so I trust systems that survive real conditions.

🟢 **Open to AI / ML / LLM engineer roles** · authorized to work in the US now (STEM OPT)
🌐 [chandhan.com](https://chandhan.com) · [LinkedIn](https://www.linkedin.com/in/chandhan-saai-katuri) · hello@chandhan.com

---

### 💼 Recent work (Verita AI, Software Engineer)

- Delivered and hardened **reinforcement-learning environments** used in a frontier AI lab's model post-training: containerized tasks, verifiers and reward logic, including a fix for reward hacking.
- Built a production **vision-LLM audit pipeline** that reviews screenshots of contractor work sessions against project rules, with cross-provider model benchmarking and sealed, recomputable payout ledgers.
- Built an **MCP server** (Python, FastMCP) connecting a client's expert-evaluation pipeline to Verita's annotation platform.
- Led **SOC 2 Type II** readiness and built a multi-scanner application-security pipeline with LLM-assisted triage.

That code is private; the projects below are public.

---

### 🔧 Featured projects

| Project | What it is |
|---|---|
| [Visa Grep](https://visagrep.com) (live) | Free search of any U.S. employer's H-1B record: Department of Labor filings, USCIS approvals, salaries, green-card (PERM) filings and E-Verify status, with a source for every number. 3.75M H-1B filings across 228K employers, plus a free JSON API and a hosted MCP server for AI assistants. |
| [Project D3: Multi-Agent LLM Evaluation](https://github.com/ChandhanSaai/Project_D3) | Role-specialized LLM agents (advocates, a judge, and an optional jury) score model outputs through structured adversarial debate; two eval protocols with agreement, κ, and position-bias metrics. |
| [SOP-Guided Claims Agent](https://github.com/ChandhanSaai/sop-claims-agent) | An insurance-claims support agent where code owns the procedure and the model only reads and phrases: a four-phase state machine, schema-validated LLM reads, an output guard, and 326 offline replay tests. |
| [Browser Autopilot](https://github.com/ChandhanSaai/Browser-Autopilot) | A vision-driven browser agent: a LangGraph + Playwright loop that turns plain-English web tasks into actions and auto-generates illustrated step-by-step tutorials. |
| [LLM-Triaged Security Audit](https://github.com/ChandhanSaai/multi-scanner-security-audit-with-llm-triage) | Merges 8 SAST/secret/dependency scanners into one SARIF, then a two-pass LLM dedupes, filters false positives, and runs a semantic authz/IDOR reasoning pass into a ranked report. |
| [Metered API Billing](https://github.com/ChandhanSaai/Metered_API_Billing) | Usage-based billing in Django + React built for correctness under concurrency: idempotent ingestion, tenant isolation, integer-cents tiered invoicing, and HMAC-verified webhooks. |
| [GPT from Scratch](https://github.com/ChandhanSaai/GPT-Transformer-Architecture-with-Production-Training-Pipeline) | A GPT-2-style transformer implemented from scratch in PyTorch: hand-built multi-head attention, weight tying, and a mixed-precision + gradient-accumulation training loop. |

**Robotics:** [SAC agent for a Panda arm in robosuite](https://github.com/ChandhanSaai/-Reinforcement-Learning-Based-Pick-and-Place-Task-for-Panda-Robot) · [ROS 2 TurtleBot perception](https://github.com/ChandhanSaai/ROS_2_TurtleBot_perception_project) · [ROS 2 pallet detection (YOLO)](https://github.com/ChandhanSaai/ROS2-Pallet-detection-and-ground-segmentation) · [Panda arm with MoveIt](https://github.com/ChandhanSaai/Controlling-panda-arm-manipulator-with-MoveIt)

---

### 🛠️ Tech I work with

**LLMs & agents:** LLM evaluation / LLM-as-judge · agents and tool use (LangGraph) · MCP · RAG · computer-use agents (Playwright) · Anthropic Claude · OpenAI
**ML:** PyTorch · Transformers · reinforcement learning · Stable Baselines3 · YOLO · computer vision
**Languages:** Python · TypeScript · SQL · C++
**Production:** Django REST Framework · FastAPI · React · PostgreSQL · Docker · AWS · Terraform
