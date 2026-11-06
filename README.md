### Oleg Vdovin – verifiable AI

I build AI systems whose answers and actions can be checked: every claim tied to a source, every agent action written to a tamper-evident log, every benchmark scored without an LLM judge. Based in Kazakhstan; I work in Russian and English.

**Agent accountability and AI security**

- [**kezekshi-l1**](https://github.com/oleg-vdv/kezekshi-l1) – local L1 SOC triage over Wazuh with a fine-tuned Gemma 4: code and [weights](https://huggingface.co/oleg-vdv/kezekshi-l1). Write-up: [0 false escalations on synthetic data, 39 of 100 on real alerts](https://dev.to/olegvdv/my-soc-triage-model-had-0-false-escalations-on-real-alerts-it-had-39-out-of-100-2pj5).
- [**kepil**](https://github.com/oleg-vdv/kepil) – accountability layer for AI agents: passport, mandate, action gateway, tamper-evident journal.
- [**AI-Gateway**](https://github.com/oleg-vdv/AI-Gateway) – on-prem LLM compliance gateway: finds personal data and secrets in prompts and masks them reversibly.
- [**MoneyGate**](https://github.com/oleg-vdv/moneygate) – safety gate for AI agents that move money: scam checks, mandate and tamper-evident journal.
- [**proofbyte**](https://github.com/oleg-vdv/proofbyte) – machine-verifiable compliance evidence: cryptographic inventory for post-quantum migration, AI-agent action-log verification.
- [**AutoGov**](https://github.com/oleg-vdv/AutoGov) – finds shadow n8n automations on laptops and servers and maps what they touch.

**Grounded answers and evaluation**

- [**clausewatch**](https://github.com/oleg-vdv/clausewatch) – an agent over contradictory AI regulation (EU AI Act vs GDPR) that shows the conflict instead of flattening it into one number.
- [**shezhire**](https://github.com/oleg-vdv/shezhire) – Kazakh family tree from recorded stories: a local Gemma reads, code checks every link against the recording.
- [**KZ Scam Shield**](https://www.kaggle.com/benchmarks/ipgleg/kz-scam-shield) – public benchmark of 14 LLMs on Kazakh fraud scenarios in Russian, Kazakh and mixed language. Write-up: [every model I tested would help my mother prepay a fake seller](https://dev.to/olegvdv/every-llm-i-tested-would-help-my-mother-prepay-a-fake-olx-seller-465e).
- [**Your Proxy Eval Is Lying**](https://www.kaggle.com/competitions/gemma-4-developer-agent-paper/writeups/your-proxy-eval-is-lying-calibrating-a-31b-coding) – paper on calibrating evaluation for a Gemma 4 coding agent before tuning it.

**Writing:** [Habr](https://habr.com/ru/users/ipgleg/articles/) (Russian) · [dev.to/olegvdv](https://dev.to/olegvdv) (English)

**Contact:** oleg-vdv@yandex.ru · Telegram [@ipgleg](https://t.me/ipgleg) – open to projects on SOC automation, RAG with verified citations, AI-agent audit and LLM evaluation.
