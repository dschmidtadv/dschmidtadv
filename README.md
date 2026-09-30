# Hi, I'm Dietrich Gottfried Schmidt 👋
### Senior Enterprise Cloud & AI Solutions Architect | AWS Certified | Distributed Systems & DevEx

Dual EU/US Citizen | Fully Remote (Global & EMEA Timezone Friendly) | Languages: English (Native), German (Native)

[LinkedIn Profile](https://www.linkedin.com/in/dietrichschmidt/) • [GitHub Overview](https://github.com/dschmidtadv) • [Master Resume](https://docs.google.com/document/d/1CibLpOKQ-5nsRE9XuaUDddSc4r_maFcv_FznYLM0ypI/edit)

---

## 🚀 About Me

I am a Cloud Solutions Architect with 25 years of engineering leadership, bridging rock-solid enterprise AWS infrastructure with cutting-edge private AI workflows and developer platforms. My work centers on transforming legacy enterprise environments into secure, high-velocity developer platforms with automated guardrails, 99.996% uptime, and zero-leakage local AI ecosystems.

- 🏗️ **Enterprise Cloud & Reliability:** AWS Certified Solutions Architect, architecting multi-region high-availability platforms, least-privilege IAM, automated scale-to-zero serverless compute (saving ~99.7% of non-prod idle compute), and keyless blue-green deployments via AWS Systems Manager.
- 🤖 **Applied AI & Agentic MLOps:** Creator and author of custom Model Context Protocol (MCP) servers, private LiteLLM / OpenRouter gateways, and deterministic guardrail middleware for autonomous AI coding agents.
- 🌍 **Distributed Leadership:** Veteran leader of asynchronous, transatlantic, and globally distributed engineering teams.

---

## 🧠 Featured Architectural Case Studies & Technical Writings

### 1. The "Dual-Brain" AI Agent: Solving the "Blind Coding" Problem
*Autonomous AI coding agents often make locally optimal changes that cause catastrophic regressions across legacy systems because they lack architectural context and blast-radius awareness.*
* **Semantic Memory (The "Why"):** Powered by **Qdrant** vector databases to maintain institutional memory, historical ADRs, and security compliance guidelines.
* **Structural Memory (The "How"):** Powered by **GitNexus** to calculate exact mathematical blast-radius impact analysis on symbols and dependencies before code is touched.
* **Three-Source Verification (3SV) Protocol:** Enforces a three-stage pre-flight check (Local State → Semantic Qdrant Check → GitNexus Blast Radius) before generating or applying diffs.
* **Deployment:** Containerized via Docker Compose for zero-leakage local developer setups or scaled across enterprise clouds.

### 2. Agent Reliability & The Circuit Breaker Pattern
*“You cannot prompt your way out of an architecture problem.” High-reasoning models (e.g., Claude 3.7 Sonnet) often fall into infinite loops and "argument jitter" due to helpfulness alignment overriding negative constraints.*
* **Layer 1: Cognitive Override (Soft Boundary):** Redefines terminal states as successful outcomes in prompt schemas (`<STATUS>ABORT_LOOP</STATUS>`), giving agents permission to fail gracefully.
* **Layer 2: Agent Circuit Breaker (Hard Boundary):** Python execution middleware that hashes tool-call signatures (base commands + arguments). After 3 consecutive failed attempts, it physically trips the circuit breaker and strips tool permissions, protecting API budgets and preventing runaway execution.

### 3. Enterprise AI Gateway & Least-Cost Routing (LCR)
* **Private Cloud Ingress:** Containerized LiteLLM proxy on AWS ECS routing PR reviews (pr-agent) to Claude models via Amazon Bedrock, ensuring proprietary code never leaves the cloud VPC.
* **Multi-Provider Optimization:** Integrated OpenRouter and LiteLLM gateways with Least-Cost Routing (LCR), automated model-group fallbacks, per-request cost/latency telemetry headers, and Presidio PII masking.
* **Operational Impact:** Accelerated production incident triage and root-cause analysis by a factor of 20 (20x MTTR reduction) using custom autonomous AI diagnostic agents.

### 4. High-Performance Hybrid Entity Resolution (GenealogyDedupeGUI)
* **Multi-Stage Data Funnel:** Flattened raw hierarchical datasets into columnar Parquet files using a recursive descent parser.
* **Deterministic & Probabilistic Topology:** Directed graph modeling in **DuckDB** paired with **Splink** (Fellegi-Sunter model with Daitch-Mokotoff phonetic arrays and Term Frequency weighting).
* **Hybrid AI Reasoning:** 2-hop ambiguous family boundaries are resolved locally via DeepSeek-R1 for privacy or scaled dynamically via OpenRouter for high-concurrency cloud throughput.

---

## 🛠️️ Technical Stack & Tooling

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Cloud & Architecture** | AWS (EC2, ALB, Lambda, DynamoDB, S3, CloudFront, Route 53, Global Accelerator, WAF, IAM, SSM, ECS, ECR, RDS, VPC) |
| **AI, MLOps & DevEx** | Model Context Protocol (MCP), Qdrant, Ollama, LiteLLM, OpenRouter (LCR), Amazon Bedrock, Roo Code, Cline, Continue.dev, pr-agent |
| **Infrastructure as Code** | Terraform, Ansible, Docker, Docker Compose, Kubernetes, Helm Charts |
| **CI/CD & Reliability** | GitHub Actions (OIDC, reusable workflows, self-hosted runners), GitLab CI, Jenkins, Blue-Green Releases, 3SV Gates |
| **Enterprise Web Platforms** | Drupal (10/11), Drush, PHP 8.3, Symfony 7, Composer, Redis, Valkey, Apache, Nginx |
| **Data, Tooling & Languages** | Python, DuckDB, Parquet, Splink, SQL, Bash, Puppeteer, Git, GitHub, VS Code |

---

## 📦 Featured Repositories

* **[qdrant-memory-mcp](https://github.com/rivasolutionsinc-corp/qdrant-memory-mcp):** Custom Model Context Protocol (MCP) server providing persistent semantic memory and vector indexing via Qdrant for AI coding agents.
* **[charts](https://github.com/dschmidtadv/charts):** Curated Kubernetes Helm chart orchestration and cloud-native application deployments.
* **[drupal-devcontainer](https://github.com/dschmidtadv/drupal-devcontainer):** Standardized local containerized development environments for complex web platforms.
* **[serverless-broken-link-checker](https://github.com/dschmidtadv/serverless-broken-link-checker):** Event-driven AWS Lambda telemetry and status validation for high-traffic public properties.

---

## 📬 Let's Connect

- **LinkedIn:** [linkedin.com/in/dietrichschmidt](https://www.linkedin.com/in/dietrichschmidt/)
- **GitHub:** [github.com/dschmidtadv](https://github.com/dschmidtadv)
- **Work Preferences:** 100% Remote | Work From Anywhere (WFA) | Global & EMEA Remote | Transatlantic Distributed Teams