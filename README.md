### Hi, I'm Shubham

I lead engineering at [Nova Benefits](https://www.novabenefits.com), a health-benefits platform for Indian employers, from Bengaluru. IIT Delhi.

Most of my work is putting LLM systems into production and making them trustworthy: an AI assistant that answers employees' insurance questions, AI code review that runs on every pull request, and the data pipelines and evals behind them. I care about the boring parts that make AI safe to ship: verification, evals, idempotent pipelines, and clear failure states.

**Things I've built in the open**

| Project | What it is | Stack |
|---|---|---|
| [reviewhound](https://github.com/shubhamattri/reviewhound) | Pull-request reviewer where the model proposes findings and code verifies every claim before it is posted. Measured precision and recall on an offline eval. | Python, tree-sitter, SQLite/Postgres queue, Docker sandbox |
| [artha-engine](https://github.com/shubhamattri/artha-engine) | Household finance engine: parses Indian bank and card statements, reconciles them, and runs an AI advisor that is never allowed to invent a number. | Python, FastAPI, Postgres, LLM tool calling, evals |
| [home-intelligence-platform](https://github.com/shubhamattri/home-intelligence-platform) | Scores homes on commute, schools, hospitals, price and risk. Microservices behind an MCP gateway. | Python, FastAPI, MCP, Docker, Helm |
| [local-dictation](https://github.com/shubhamattri/local-dictation) | Private, offline speech-to-text on your own machine behind a hardened loopback API. | Python, faster-whisper |
| [mbquery](https://github.com/shubhamattri/mbquery) | Metabase from the terminal: SQL, plain-English questions, schema browsing and an MCP server, with personal-data masking. | Python, Typer, httpx, MCP |

**Find me:** [LinkedIn](https://www.linkedin.com/in/shubham-attri)
