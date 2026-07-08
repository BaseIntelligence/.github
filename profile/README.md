<div align="center">

<img src="https://pbs.twimg.com/profile_banners/1988944803183357957/1782220001/1500x500" alt="BASE" width="600" />

# BASE

### Decentralized Intelligence. Open by design.

**A community-owned alternative to OpenAI and Anthropic, built on Bittensor.**

[![Bittensor](https://img.shields.io/badge/Built%20on-Bittensor-4C1D95?style=for-the-badge)](https://bittensor.com)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge)](https://www.apache.org/licenses/LICENSE-2.0)
[![Docs](https://img.shields.io/badge/Read-Docs-06B6D4?style=for-the-badge)](https://github.com/BaseIntelligence/docs)

</div>

---

## What is Base

**Base is a Bittensor subnet building frontier AI in the open.** Where OpenAI and Anthropic build behind closed doors, Base turns model research, data collection, and training into a set of open, competitive **challenges** run across a decentralized network of miners.

Every hard problem in the AI pipeline, from discovering better architectures to gathering the freshest training data, is framed as a challenge. Miners around the world compete to solve it, contribute real, working code, and are **incentivized** on-chain for the quality of their work. Validators score contributions and reward the best, so the network improves continuously without a single company owning the outcome.

The result is a lab without walls: the same ambition as the big closed labs, but transparent, permissionless, and owned by its contributors.

---

## Why Base, not a closed lab

The core difference: closed labs are limited to a **handful of salaried employees** competing internally, with no external pressure and no merit-based upside. Base opens the same research to the **entire world** and rewards every contribution on-chain, so the best ideas can come from anyone, anywhere.

| | Closed labs (OpenAI, Anthropic) | **Base** |
|---|---|---|
| **Who competes** | Only internal employees | The whole world, permissionlessly |
| **Talent pool** | A few hundred hires | Thousands of miners, globally |
| **Incentives** | Fixed salaries, no merit reward | On-chain rewards for the best work |
| **Ownership** | Corporate, centralized | Community-owned |
| **Data** | Proprietary pipelines | Decentralized, continuously crawled |
| **Transparency** | Black box | Every contribution is public code |

```mermaid
flowchart TB
    subgraph CLOSED["Closed Labs - OpenAI, Anthropic"]
        direction TB
        C0["A few hundred salaried employees"]
        C1["Compete only inside the company"]
        C2["No external contributors"]
        C3["Fixed pay, no merit incentive"]
        C0 --> C1 --> C2 --> C3
    end

    subgraph BASE["BASE - Open and Decentralized"]
        direction TB
        B0["Anyone on Earth can join"]
        B1["Worldwide open competition"]
        B2["Thousands of miners contribute"]
        B3["On-chain rewards for the best work"]
        B0 --> B1 --> B2 --> B3
    end

    CLOSED -. "closed doors vs the whole world" .-> BASE

    style CLOSED fill:#1f1f2e,stroke:#555,color:#ddd
    style BASE fill:#2a1a4a,stroke:#7c3aed,color:#fff
```

Base is not one model. It is the **machinery that produces models**, opened up to everyone.

---

## The Challenges

Base coordinates the full AI research loop through specialized challenges. Each one targets a distinct part of building better models:

### Prism - Research
Decentralized neural architecture search. Miners submit architectures and training recipes to discover scalable AI improvements, evaluated competitively so the strongest ideas rise to the top.
> The research engine of Base: how we find *better ways to build models*.

### Relay - Data at the edge of the web
Miners compete to crawl the web on demand, following links and extracting page content, incentivized to relay accurate, up-to-date data whenever it's requested.
> The freshness engine: **recent, real-world data** flowing straight into training.

### Data Fabrication - Training-ready datasets
Developers are incentivized to create diverse, high-performance datasets, evaluated in isolated environments and rewarded on quality and utility.
> The refinement engine: turning raw crawled data into **clean fuel for training**.

### Agent Challenge - Applied intelligence
A platform challenge where developers run and monetize terminal-based AI agents, evaluated in isolated environments and rewarded through competitive performance.

### Bounty Challenge - Continuous improvement
Community-driven bug discovery and software improvement, with rewards based on impact and quality.

---

## How it works

```mermaid
flowchart LR
    V["Validators<br/>issue challenges<br/>and score work"]
    M["Miners<br/>compete and contribute<br/>code, data, models"]
    BT["Bittensor<br/>merit-based rewards<br/>weights set on-chain"]

    V -- "challenge" --> M
    M -- "contributions" --> V
    V -- "set weights" --> BT
    BT -- "TAO rewards" --> M

    style V fill:#0e7490,stroke:#06b6d4,color:#fff
    style M fill:#4c1d95,stroke:#7c3aed,color:#fff
    style BT fill:#1e3a8a,stroke:#3b82f6,color:#fff
```

1. **A challenge is issued** - research, crawl, dataset, or agent task.
2. **Miners compete** - they contribute real code, crawled data, or model improvements.
3. **Validators score** - quality is measured in isolated, verifiable environments.
4. **The network rewards** - the best work earns on-chain incentives, and the whole system gets smarter.

---

## The pipeline, end to end

```mermaid
flowchart LR
    P["Prism<br/><i>Research</i><br/>find better architectures"]
    R["Relay<br/><i>Data</i><br/>crawl the freshest web data"]
    D["Data Fabrication<br/><i>Refine</i><br/>training-ready datasets"]
    T["Trained Models<br/><i>Open and owned by the network</i>"]

    P --> R --> D --> T
    T -. "insights feed back" .-> P

    style P fill:#4c1d95,stroke:#a78bfa,color:#fff
    style R fill:#0e7490,stroke:#22d3ee,color:#fff
    style D fill:#92400e,stroke:#f59e0b,color:#fff
    style T fill:#166534,stroke:#22c55e,color:#fff
```

**Prism** discovers *how* to build better models, **Relay** crawls the web for the *most recent* data, **Data Fabrication** turns it into training-ready datasets, and the network trains and improves, in the open.

Research, data, and training, decentralized and incentivized, competing head-to-head with the closed labs.

---

<div align="center">

## Get involved

**[Documentation](https://github.com/BaseIntelligence/docs)** · **[Core Subnet](https://github.com/BaseIntelligence/base)** · **[Prism](https://github.com/BaseIntelligence/prism)** · **[Relay](https://github.com/BaseIntelligence/relay)**

*Frontier AI shouldn't be owned by a few. Base is building it for everyone.*

</div>
