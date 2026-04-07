# Summer Reading Group 2026: Applied Empirics × AI for Research

**Organizer:** [Philip Zhang](https://rphilipzhang.github.io/rphilipzhang/)  
**Schedule (tentative):** Tuesdays, 9:30 am - 11:30 am  
**Duration:** 10 weeks  
**Participants:** PhD students, post-doctoral fellows, research assistants  
**Lunch:** Group lunch after each session (covered by Philip)
**Sign-up Sheet:** [Sign up here](https://github.com/rphilipzhang/Reading-Group-2026).
**[Zoom Link](https://cuhk.zoom.us/j/91010132061?pwd=NnAJPWU6ckdFpeEPb28TZEaGGEjfVY.1), Zoom ID: 910 1013 2061, Passcode: 073575**

---

## Overview

This reading group has two parallel tracks, each occupying one hour per session:

| Time | Track | Focus |
|------|-------|-------|
| 9:30 - 10:30 | **Applied Empirics** | Core causal inference and econometric methods applied in business/economics research |
| 10:30 - 11:30 | **AI for Research** | Practical AI techniques that power modern research workflows |

### Prerequisites & Assumptions

- **Applied Empirics:** Participants are expected to have a solid foundation in econometrics and causal inference (e.g., OLS, potential outcomes, basic DID, IV, RDD concepts). The reading group focuses on **applying** these methods *correctly* in empirical research settings, navigating practical challenges such as assumption validation, robustness checks, and replication, rather than re-teaching the underlying theory.
- **AI for Research:** Participants are assumed to be familiar with the basics of AI and LLMs (e.g., what a large language model is, how to use ChatGPT-style interfaces for simple tasks). The reading group focuses on **modern agentic AI**, multi-agent workflows, autonomous research systems, AI coding agents, and integration of AI into end-to-end research pipelines, which goes well beyond basic LLM usage. We will build AI systems together to empower our research.

### Track Descriptions

**Applied Empirics** follows the structure of [Goldsmith-Pinkham's Applied Methods course](https://github.com/paulgp/applied-methods-phd) and [Sant'Anna's DID resources](https://psantanna.com/did-resources/), covering canonical identification strategies (DID, IV, RDD) and modern ML-based causal inference methods, with emphasis on assumptions, simulations, and hands-on replication.

**[AI for Research](https://velikov-mihail.github.io/ai-econ-wiki/)** draws on recent developments in agentic AI systems, AI coding assistants, and autonomous research pipelines, aiming to equip participants with practical skills to integrate modern AI tools into their own research workflows.

---

## Format

### Track 1: Applied Empirics (1 hour)

Each presenter should present the following:

1. **Method introduction** (~15 min): Explain the core identification strategy (e.g., IV, DID), key assumptions, and intuition.
2. **Simulation exercise** (~20 min) Run simulations (constructed with AI assistance is encouraged) to demonstrate why certain assumptions are critical and which violations are more or less consequential.
3. **Paper replication** (~25 min): **Each speaker should select an empirical paper of his/her own choice** that uses this identification strategy; discuss how the key assumptions apply (or fail) in that setting; demonstrate a stepwise replication of the main results (use the paper's open-source data if available; otherwise simulate data based on the paper's setting, using AI).

### Track 2: AI for Research (1 hour)

Each presenter should present the following:

1. **Technical background** (~20 min): Provide the necessary theoretical and technical context for the week's technique (e.g., how multi-agent systems work, how RAG differs from wiki-based knowledge management).
2. **Implementation demo** (~15 min): Present the your own implementation of the method(s) and discuss how to cross necessary technical barriers, with the help of AI.
3. **Applications & reflections** (~25 min): Demonstrate applications, discuss limitations, and share thoughts on how to use and iterate this method in your own research.

In either case, if you have difficulty selecting what to present in the reading group, please directly contact Philip.

### Logistics

- **One day before** each session, speakers must upload slides, code, and documentation to the reading group GitHub repo.
- Presenters are encouraged to use agentic AI tools (Claude Code, Codex, Cursor, etc.) to prepare simulations, replications, and demos to the best extent possible.


---

## Presentation Schedule

Please [sign up](https://docs.google.com/spreadsheets/d/1av1Zpzm4U140xW02cjVyymvDjQ8gSTv050DII3wAeE4/edit?usp=sharing) for **one empirics session** and **one AI session** (or more if needed). Each Topic 1 speaker should **select an empirical paper of his/her own choice** for the replication exercise.

| Week |Date (Tentative)| Empirics Presenter | AI Presenter |
|------|----|--------------------|--------------|
| 1 |05.18| ||
| 2 |05.25| ||
| 3 |06.02| ||
| 4 |06.07| ||
| 5 |06.16| ||
| 6 |06.23| ||
| 7 |06.30| ||
| 8 |07.07| |
| 9 |07.14| |
| 10|07.21| |

---

## Weekly Schedule

### Applied Empirics

| Week | Topic |Key References|
|------|-------|--------------|
| 1 | Propensity Scores, Matching & Reweighting |[Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/03_propensity_scores.pdf)|
| 2 | Classic DID (2×2) |[Slides 1](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/13_dind.pdf), [Slides 2](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/13a_dind_foundations.pdf), [Slides 3](https://psantanna.com/DiD/02_two_by_two.pdf), [Slides 4](https://psantanna.com/DiD/03_Clustering.pdf), [Slides 5](https://psantanna.com/DiD/04_Functional_form.pdf), [Slides 6](https://psantanna.com/DiD/05_Covariates.pdf)|
| 3 | Modern DID: Staggered Adoption & TWFE Problems |[Slides 1](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/13b_dind_staggered.pdf), [Slides 2](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/13c_dind_extensions.pdf), [Slides 3](https://psantanna.com/DiD/09_Twfe.pdf), [Slides 4](https://psantanna.com/DiD/11_Staggered_problems.pdf), [Slides 5](https://psantanna.com/DiD/12_CS.pdf), [Slides 6](https://psantanna.com/DiD/13_On_off.pdf)|
| 4 | Event Studies, Synthetic Control & Synthetic DID |[Slides 1](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/14_synthetic_dind.pdf), [Slides 2](https://psantanna.com/DiD/08_ES.pdf), [Slides 3](https://psantanna.com/DiD/10_Pretest.pdf)|
| 5 | IV: Core Theory |[Slides 1](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/15_iv_partI.pdf), [Slides 2](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/16_iv_partII.pdf)|
| 6 | IV Extensions: Bartik, Shift-Share & Examiner Designs |[Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/17_iv_partIII.pdf), [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/18_bartik_sim_iv.pdf), [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/19_judge_iv.pdf)|
| 7 | RDD: Sharp, Fuzzy & Extensions |[Slides 1](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/20_regression_discontinuity_1.pdf), [Slides 2](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/21_regression_discontinuity_2.pdf), [Slides 3](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/22_regression_discontinuity_3.pdf)|
| 8 | Double/Debiased Machine Learning |[Slides 1](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/23_machine_learning_1.pdf), [Slides 2](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/24_machine_learning_2.pdf), [Slides 3](https://psantanna.com/DiD/06_DML.pdf), [Slides 4](https://github.com/rphilipzhang/AI-PhD-S25/blob/main/Slides/AI-PhD-S2025-11-DML.pdf)|
| 9 | ML × Causal Inference |[Slides 1](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/25_machine_learning_3.pdf), [Slides 2](https://github.com/rphilipzhang/AI-PhD-S25/blob/main/Slides/AI-PhD-S2025-12-HTE.pdf)|
| 10 | Partial Identification & Sensitivity Analysis |[Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/26_partial_identification.pdf)|

### AI for Research

| Week | Topic |Key References|
|------|-------|--------------|
| 1 | AI Coding Agents & Multi-Agent Workflows for Research |[Substack](https://paulgp.substack.com/p/getting-started-with-claude-code), [GitHub](https://github.com/pedrohcgs/claude-code-my-workflow)|
| 2 | AI-Powered Statistical Analysis: StatsClaw & Code Generation |[GitHub](https://github.com/statsclaw)|
| 3 | AI-Driven Replication Studies |[GitHub](https://github.com/andybhall/vbm-replication-extension), [arXiv](https://arxiv.org/abs/2602.16733)|
| 4 | Autonomous Research Systems |[GitHub 1](https://github.com/karpathy/autoresearch), [GitHub 2](https://github.com/sakanaai/ai-scientist-v2)|
| 5 | Knowledge Management with LLMs: Wiki vs. RAG |[Gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f), [Project APE](https://ape.socialcatalystlab.org/)|
| 6 | AI for Data Collection & Unstructured Data |[GitHub 1](https://github.com/velikov-mihail/AI-Powered-Scholarship), [Project APE](https://ape.socialcatalystlab.org/), [GitHub](https://github.com/andybhall/vbm-replication-extension)|
| 7 | LLM Social Simulations for Economic & Social Research |[GitHub 1](https://github.com/camel-ai/oasis), [GitHub 2](https://github.com/tsinghua-fib-lab/AgentSociety)|
| 8 | AI for Academic Writing & Peer Review |[Project APE](https://ape.socialcatalystlab.org/), [GitHub 1](https://github.com/andybhall/vbm-replication-extension), [GitHub 2](https://github.com/sakanaai/ai-scientist-v2)|
| 9 | AI for Theoretical Model Building & Mathematical Proof |[Vibe Research](https://vincent.codes.finance/posts/vibe-research-paper/), [GitHub](https://github.com/fintech-research/ai-lab-investment/)|
| 10 | Building Your AI-Augmented Research Workflow |[Wiki](https://velikov-mihail.github.io/ai-econ-wiki/), [Substack](https://paulgp.substack.com/p/research-in-the-time-of-ai), [GitHub](https://github.com/pedrohcgs/claude-code-my-workflow)|

---

### Week 1

| Track | Topic | Presenter |
|-------|-------|-----------|
| Empirics | **Propensity Scores, Matching & Reweighting**: IPW, doubly robust estimation, overlap diagnostics | _TBD_ |
| AI | **AI Coding Agents & Multi-Agent Workflows for Research**: Claude Code, Cursor, orchestrator patterns, quality gates, adversarial critic-fixer, CLAUDE.md/MEMORY.md | _TBD_ |


**Empirics References:**


- Goldsmith-Pinkham, P. Propensity Scores. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/03_propensity_scores.pdf)


- Imbens, G. W. & Xu, Y. (2024). LaLonde (1986) after Nearly Four Decades: Lessons Learned. [NBER Working Paper](https://www.nber.org/papers/w32029)
- Rosenbaum, P. R. & Rubin, D. B. (1983). The Central Role of the Propensity Score in Observational Studies for Causal Effects. *Biometrika*, 70(1), 41--55. [DOI](https://doi.org/10.1093/biomet/70.1.41)
- Heckman, J. J., Ichimura, H. & Todd, P. E. (1998). Matching as an Econometric Evaluation Estimator. *Review of Economic Studies*, 65(2), 261--294. [DOI](https://doi.org/10.1111/1467-937X.00044)
- Hirano, K., Imbens, G. W. & Ridder, G. (2003). Efficient Estimation of Average Treatment Effects Using the Estimated Propensity Score. *Econometrica*, 71(4), 1161--1189. [DOI](https://doi.org/10.1111/1468-0262.00442)
- Dehejia, R. H. & Wahba, S. (2002). Propensity Score-Matching Methods for Nonexperimental Causal Studies. *Review of Economics and Statistics*, 84(1), 151--161. [DOI](https://doi.org/10.1162/003465302317331982)
- Smith, J. A. & Todd, P. E. (2005). Does Matching Overcome LaLonde's Critique of Nonexperimental Estimators? *Journal of Econometrics*, 125(1-2), 305--353. [DOI](https://doi.org/10.1016/j.jeconom.2004.04.011)
- Goldsmith-Pinkham, P., Hull, P. & Kolesar, M. (2022). Contamination Bias in Linear Regressions. [NBER Working Paper](https://www.nber.org/papers/w30108)

**AI References:**

- Goldsmith-Pinkham, P. Getting Started with Claude Code: A Researcher's Setup Guide. [Substack](https://paulgp.substack.com/p/getting-started-with-claude-code)
- Goldsmith-Pinkham, P. Claude Code for Applied Economists (7-episode video series, Markus Academy). [Substack](https://markusacademy.substack.com/p/claude-code-for-applied-economists) · [Princeton](https://bcf.princeton.edu/events/paul-goldsmith-pinkham-mini-series-on-claude-code-for-applied-economists/)
- Sant'Anna, P. My Claude Code Setup (workflow guide for academics). [Website](https://psantanna.com/claude-code-my-workflow/workflow-guide.html)
- Sant'Anna, P. claude-code-my-workflow: multi-agent template with orchestrator, adversarial critic-fixer, quality gates. [GitHub](https://github.com/pedrohcgs/claude-code-my-workflow)
- Anthropic. Claude Code Official Documentation. [Docs](https://docs.anthropic.com/en/docs/claude-code) · [GitHub](https://github.com/anthropics/claude-code)
- Cursor. Official Documentation. [Website](https://cursor.com/) · [Docs](https://cursordocs.com/en)
- OpenAI. Agents SDK (March 2025): production-grade multi-agent toolkit with explicit handoffs. [GitHub](https://github.com/openai/openai-agents-python)
- CrewAI. Role-based multi-agent framework. [Website](https://www.crewai.com/) · [GitHub](https://github.com/crewAIInc/crewAI)
- LangGraph (LangChain). Graph-first agent orchestration with state machines. [Docs](https://langchain-ai.github.io/langgraph/)
- Langfuse (2025). Comparing Open-Source AI Agent Frameworks (CrewAI, LangGraph, AutoGen). [Blog](https://langfuse.com/blog/2025-03-19-ai-agent-comparison)
- *Harness Engineering:*
  - Böckeler, B. (2026). Harness Engineering for Coding Agents. *Martin Fowler's Blog*. [Article](https://martinfowler.com/articles/harness-engineering.html)
  - Young, J. (Anthropic, 2025). Effective Harnesses for Long-Running Agents. *Anthropic Engineering Blog*. [Article](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents)
  - HumanLayer (2026). Skill Issue: Harness Engineering for Coding Agents. [Blog](https://www.humanlayer.dev/blog/skill-issue-harness-engineering-for-coding-agents)
  - Anthropic. How Claude Remembers Your Project (CLAUDE.md, memory, rules hierarchy). [Docs](https://code.claude.com/docs/en/memory)
  - Anthropic. Best Practices for Claude Code (CLAUDE.md sizing, sub-agents, workflow patterns). [Docs](https://code.claude.com/docs/en/best-practices)
  - AGENTS.md Specification: an emerging open standard for agent instruction files. [Website](https://agents.md/)
  - DeployHQ. CLAUDE.md, AGENTS.md, and Every AI Config File Explained. [Blog](https://www.deployhq.com/blog/ai-coding-config-files-guide)

---

### Week 2

| Track | Topic | Presenter |
|-------|-------|-----------|
| Empirics | **Classic DID (2×2)**: Parallel trends, inference with clustering, covariate adjustment, functional form sensitivity | _TBD_ |
| AI | **AI-Powered Statistical Analysis: StatsClaw & Code Generation**: Natural language to production-ready statistical code, comparison of tools | _TBD_ |




**Empirics References:**

- Goldsmith-Pinkham, P. Difference-in-Differences. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/13_dind.pdf) · DiD Foundations. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/13a_dind_foundations.pdf)

- Sant'Anna, P. Classical 2×2 DiD Setup. [Slides](https://psantanna.com/DiD/02_two_by_two.pdf) · Clustering. [Slides](https://psantanna.com/DiD/03_Clustering.pdf) · Parallel Trends and Functional Form. [Slides](https://psantanna.com/DiD/04_Functional_form.pdf) · Covariates. [Slides](https://psantanna.com/DiD/05_Covariates.pdf)

- Bertrand, M., Duflo, E. & Mullainathan, S. (2004). How Much Should We Trust Difference-In-Differences Estimates? *Quarterly Journal of Economics*, 119(1), 249--275. [DOI](https://doi.org/10.1162/003355304772839588)
- Card, D. & Krueger, A. B. (1994). Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania. *American Economic Review*, 84(4), 772--793. [JSTOR](https://www.jstor.org/stable/2118030)
- Roth, J. & Sant'Anna, P. (2023). When Is Parallel Trends Sensitive to Functional Form? *Econometrica*, 91(2), 737--747. [DOI](https://doi.org/10.3982/ECTA19402)
- Roth, J. (2022). Pretest with Caution: Event-Study Estimates after Testing for Parallel Trends. *American Economic Review: Insights*, 4(3), 305--322. [DOI](https://doi.org/10.1257/aeri.20210236)
- Sant'Anna, P. & Zhao, J. (2020). Doubly Robust Difference-in-Differences Estimators. *Journal of Econometrics*, 219(1), 101--122. [DOI](https://doi.org/10.1016/j.jeconom.2020.06.003)
- Freyaldenhoven, S., Hansen, C. & Shapiro, J. M. (2019). Pre-event Trends in the Panel Event-Study Design. *American Economic Review*, 109(9), 3307--3338. [DOI](https://doi.org/10.1257/aer.20180609)
- Sant'Anna, P. DID Checklist (visual practitioner guide). [Website](https://psantanna.com/did-resources/)

**AI References:**

- StatsClaw. AI-powered statistical code generation (R, Python, C++, Julia, Stata). [Website](https://statsclaw.ai/)
- Novy-Marx, R. & Velikov, M. (2025). AI-Powered (Finance) Scholarship. *Journal of Economic Literature*, 64(1), 5-37. [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5060022) · [NBER](https://www.nber.org/papers/w33363) · [Code](https://github.com/velikov-mihail/AI-Powered-Scholarship)
- Velikov, M. AI in Business & Economic Research Wiki (129 sources, 10 categories). [Website](https://velikov-mihail.github.io/ai-econ-wiki/)

---

### Week 3

| Track | Topic | Presenter |
|-------|-------|-----------|
| Empirics | **Modern DID: Staggered Adoption & TWFE Problems**: Bacon decomposition, negative weights, Callaway & Sant'Anna (2021), Sun & Abraham (2021), de Chaisemartin & D'Haultfoeuille (2020) | _TBD_ |
| AI | **AI-Driven Replication Studies**: End-to-end replication with AI, verification workflows, credibility and reproducibility at scale | _TBD_ |




**Empirics References:**

- Goldsmith-Pinkham, P. DiD Staggered. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/13b_dind_staggered.pdf) · DiD Extensions. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/13c_dind_extensions.pdf)
- Sant'Anna, P. TWFE with Multiple Periods. [Slides](https://psantanna.com/DiD/09_Twfe.pdf) · Staggered Treatment Adoption Problems. [Slides](https://psantanna.com/DiD/11_Staggered_problems.pdf) · Reliable Estimators with Staggered Adoption. [Slides](https://psantanna.com/DiD/12_CS.pdf) · Treatments Turning On-and-Off. [Slides](https://psantanna.com/DiD/13_On_off.pdf)

- Callaway, B. & Sant'Anna, P. (2021). Difference-in-Differences with Multiple Time Periods. *Journal of Econometrics*, 225(2), 200--230. [DOI](https://doi.org/10.1016/j.jeconom.2020.12.001)
- Roth, J., Sant'Anna, P., Bilinski, A. & Poe, J. (2023). What's Trending in Difference-in-Differences? A Synthesis of the Recent Econometrics Literature. *Journal of Econometrics*, 235(2), 2218--2244. [DOI](https://doi.org/10.1016/j.jeconom.2023.03.008)
- Baker, A., Callaway, B., Cunningham, S., Goodman-Bacon, A. & Sant'Anna, P. (2025). Difference-in-Differences Designs: A Practitioner's Guide. [Working Paper](https://arxiv.org/abs/2502.00818)
- Goodman-Bacon, A. (2021). Difference-in-Differences with Variation in Treatment Timing. *Journal of Econometrics*, 225(2), 254--277. [DOI](https://doi.org/10.1016/j.jeconom.2021.03.014)
- de Chaisemartin, C. & D'Haultfoeuille, X. (2020). Two-Way Fixed Effects Estimators with Heterogeneous Treatment Effects. *American Economic Review*, 110(9), 2964--2996. [DOI](https://doi.org/10.1257/aer.20181169)
- Sun, L. & Abraham, S. (2021). Estimating Dynamic Treatment Effects in Event Studies with Heterogeneous Treatment Effects. *Journal of Econometrics*, 225(2), 175--199. [DOI](https://doi.org/10.1016/j.jeconom.2020.09.006)
- Baker, A. C., Larcker, D. F. & Wang, C. C. Y. (2022). How Much Should We Trust Staggered Difference-In-Differences Estimates? *Journal of Financial Economics*, 144(2), 370--395. [DOI](https://doi.org/10.1016/j.jfineco.2022.01.004)
- **Software:** `did`/`csdid` — [R](https://bcallaway11.github.io/did/) · [Stata](https://friosavila.github.io/playingwithstata/main_csdid.html); `DRDID`/`drdid` — [R](https://pedrohcgs.github.io/DRDID/)

**AI References:**

- Hall, A. B. VBM Replication Extension: Claude Code replicated all 12 coefficients from Thompson et al. (2020), then extended through 2024. [GitHub](https://github.com/andybhall/vbm-replication-extension)
- Xu, Y. & Yang, L. (2026). Scaling Reproducibility: An AI-Assisted Workflow for Large-Scale Replication and Reanalysis. [arXiv](https://arxiv.org/abs/2602.16733)
- Straus, G. & Hall, A. B. How Accurately Did Claude Code Replicate and Extend a Published Political Science Paper? (independent audit). [PDF](https://www.andrewbenjaminhall.com/Straus_Hall_Claude_Audit.pdf)
- Thompson, D. M. et al. (2020). Universal Vote-by-Mail Has No Impact on Partisan Turnout or Vote Share. *PNAS*, 117(25), 14052--14056. [DOI](https://doi.org/10.1073/pnas.2007249117)
- Brodeur, A., Mikola, D. & Cook, N. (2024). Mass Reproducibility and Replicability: A New Hope. *IZA Discussion Paper* No. 16912. [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4790780)

---

### Week 4

| Track | Topic | Presenter |
|-------|-------|-----------|
| Empirics | **Event Studies, Synthetic Control & Synthetic DID**: Dynamic treatment effects, pre-trend testing, SC estimation, SDID | _TBD_ |
| AI | **Autonomous Research Systems**: Project APE, Karpathy's autoresearch, AI Scientist, LLM-as-judge, quality assessment at scale | _TBD_ |



**Empirics References:**

- Goldsmith-Pinkham, P. Synthetic DiD. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/14_synthetic_dind.pdf)
- Sant'Anna, P. Event Studies. [Slides](https://psantanna.com/DiD/08_ES.pdf) · Pre-tests. [Slides](https://psantanna.com/DiD/10_Pretest.pdf)


- Abadie, A. (2021). Using Synthetic Controls: Feasibility, Data Requirements, and Methodological Aspects. *Journal of Economic Literature*, 59(2), 391--425. [DOI](https://doi.org/10.1257/jel.20191450)
- Abadie, A., Diamond, A. & Hainmueller, J. (2010). Synthetic Control Methods for Comparative Case Studies: Estimating the Effect of California's Tobacco Control Program. *Journal of the American Statistical Association*, 105(490), 493--505. [DOI](https://doi.org/10.1198/jasa.2009.ap08746)
- Arkhangelsky, D., Athey, S., Hirshberg, D. A., Imbens, G. W. & Wager, S. (2021). Synthetic Difference in Differences. *American Economic Review*, 111(12), 4088--4118. [DOI](https://doi.org/10.1257/aer.20190159)
- Rambachan, A. & Roth, J. (2023). A More Credible Approach to Parallel Trends. *Review of Economic Studies*, 90(5), 2555--2591. [DOI](https://doi.org/10.1093/restud/rdad018)
- Roth, J. & Sant'Anna, P. (2023). Efficient Estimation for Staggered Rollout Designs. *Journal of Political Economy: Microeconomics*, 1(4), 669--709. [DOI](https://doi.org/10.1086/726581)
- Goldsmith-Pinkham, P. & Lyu, X. (2025). Causal Inference in Financial Event Studies. [Working Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5033637)

**AI References:**

- Project APE (Autonomous Policy Evaluation). AI-generated economics research at scale, TrueSkill tournament. Social Catalyst Lab, U. Zurich. [Website](https://ape.socialcatalystlab.org/) · [Papers](https://github.com/SocialCatalystLab/ape-papers)
- Karpathy, A. autoresearch: autonomous ML experimentation loop (modify → train → evaluate → iterate). [GitHub](https://github.com/karpathy/autoresearch)
- Lu, C. et al. (Sakana AI, 2024). The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery. [Website](https://sakana.ai/ai-scientist/) · [GitHub](https://github.com/SakanaAI/AI-Scientist)
- Sakana AI (2025). The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search. [arXiv](https://arxiv.org/abs/2504.08066)
- Nature (2026). Towards End-to-End Automation of AI Research. [Article](https://www.nature.com/articles/s41586-026-10265-5)

---

### Week 5

| Track | Topic | Presenter |
|-------|-------|-----------|
| Empirics | **IV: Core Theory**: Exclusion restriction, relevance, monotonicity, LATE, 2SLS, weak instruments | _TBD_ |
| AI | **Knowledge Management with LLMs: Wiki vs. RAG**: Karpathy's LLM wiki pattern, persistent knowledge bases, applications to literature reviews | _TBD_ |




**Empirics References:**

- Goldsmith-Pinkham, P. IV Part I. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/15_iv_partI.pdf) · IV Part II. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/16_iv_partII.pdf)
- Angrist, J. D., Imbens, G. W. & Rubin, D. B. (1996). Identification of Causal Effects Using Instrumental Variables. *Journal of the American Statistical Association*, 91(434), 444--455. [DOI](https://doi.org/10.1080/01621459.1996.10476902)
- Andrews, I., Stock, J. H. & Sun, L. (2019). Weak Instruments in Instrumental Variables Regression: Theory and Practice. *Annual Review of Economics*, 11, 727--753. [DOI](https://doi.org/10.1146/annurev-economics-080218-025643)
- Imbens, G. W. & Angrist, J. D. (1994). Identification and Estimation of Local Average Treatment Effects. *Econometrica*, 62(2), 467--475. [DOI](https://doi.org/10.2307/2951620)
- Heckman, J. J. (1997). Instrumental Variables: A Study of Implicit Behavioral Assumptions Used in Making Program Evaluations. *Journal of Human Resources*, 32(3), 441--462. [DOI](https://doi.org/10.2307/146178)
- Heckman, J. J. & Vytlacil, E. (1999). Local Instrumental Variables and Latent Variable Models for Identifying and Bounding Treatment Effects. *PNAS*, 96(8), 4730--4734. [DOI](https://doi.org/10.1073/pnas.96.8.4730)
- Mian, A. & Sufi, A. (2014). What Explains the 2007--2009 Drop in Employment? *Econometrica*, 82(6), 2197--2223. [DOI](https://doi.org/10.3982/ECTA10451)

**AI References:**

- Karpathy, A. LLM Wiki: LLM-maintained persistent knowledge bases (structured Markdown wikis from raw sources). [Gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)
- Lewis, P. et al. (2020). Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks. *NeurIPS 2020*. [arXiv](https://arxiv.org/abs/2005.11401)
- Velikov, M. AI in Business & Economic Research Wiki (129 sources, structured knowledge base). [Website](https://velikov-mihail.github.io/ai-econ-wiki/)
- Novy-Marx, R. & Velikov, M. (2025). AI-Powered (Finance) Scholarship. *Journal of Economic Literature*, 64(1), 5-37. [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5060022) · [NBER](https://www.nber.org/papers/w33363) · [Code](https://github.com/velikov-mihail/AI-Powered-Scholarship)
---

### Week 6

| Track | Topic | Presenter |
|-------|-------|-----------|
| Empirics | **IV Extensions: Bartik, Shift-Share & Examiner Designs**: Simulated instruments, judge IV, practical diagnostics | _TBD_ |
| AI | **AI for Data Collection & Unstructured Data**: Web scraping, NLP pipelines, text-as-data, embeddings for research | _TBD_ |



**Empirics References:**

- Goldsmith-Pinkham, P. IV Part III. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/17_iv_partIII.pdf) · Bartik / Shift-Share IV. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/18_bartik_sim_iv.pdf) · Judge IV. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/19_judge_iv.pdf)
- Borusyak, K., Hull, P. & Jaravel, X. (2025). A Practical Guide to Shift-Share Instruments. *Journal of Economic Perspectives*. [Working Paper](https://arxiv.org/abs/2412.08826)
- Goldsmith-Pinkham, P., Hull, P. & Kolesar, M. (2025). Leniency Designs: An Operator's Manual. [Working Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5051253)
- Goldsmith-Pinkham, P., Sorkin, I. & Swift, H. (2020). Bartik Instruments: What, When, Why and How. *American Economic Review*, 110(8), 2586--2624. [DOI](https://doi.org/10.1257/aer.20181047)
- Adao, R., Kolesar, M. & Morales, E. (2019). Shift-Share Designs: Theory and Inference. *Quarterly Journal of Economics*, 134(4), 1949--2010. [DOI](https://doi.org/10.1093/qje/qjz025)
- Borusyak, K. & Hull, P. (2023). Non-Random Exposure to Exogenous Shocks. *Econometrica*, 91(6), 2155--2185. [DOI](https://doi.org/10.3982/ECTA19978)
- Frandsen, B. R., Lefgren, L. J. & Leslie, E. C. (2023). Judging Judge Fixed Effects. *American Economic Review*, 113(1), 253--277. [DOI](https://doi.org/10.1257/aer.20201860)
- Arnold, D., Dobbie, W. & Yang, C. S. (2018). Racial Bias in Bail Decisions. *Quarterly Journal of Economics*, 133(4), 1885--1932. [DOI](https://doi.org/10.1093/qje/qjy012)

**AI References:**

- Gentzkow, M., Kelly, B. & Taddy, M. (2019). Text as Data. *Journal of Economic Literature*, 57(3), 535--574. [DOI](https://doi.org/10.1257/jel.20181020) · [PDF](https://web.stanford.edu/~gentzkow/research/text-as-data.pdf)
- Kelly, B. et al. (2021). Measuring Technological Innovation over the Long Run. *American Economic Review: Insights*, 3(3), 303--320. [DOI](https://doi.org/10.1257/aeri.20190499)
- Goldsmith-Pinkham, P., Hirtle, B. & Lucca, D. (2016). Parsing the Content of Bank Supervision. *FRBNY Staff Report*. [PDF](https://www.newyorkfed.org/medialibrary/media/research/staff_reports/sr770.pdf)
- CEPR VoxEU. Leveraging Large Language Models for Large-Scale Information Retrieval in Economics. [Article](https://cepr.org/voxeu/columns/leveraging-large-language-models-large-scale-information-retrieval-economics)
- Debelak, R. et al. (2025). From Embeddings to Explainability: A Tutorial on LLM-Based Text Analysis for Behavioral Scientists. *Advances in Methods and Practices in Psychological Science*. [DOI](https://doi.org/10.1177/25152459251351285)

---

### Week 7

| Track | Topic | Presenter |
|-------|-------|-----------|
| Empirics | **RDD: Sharp, Fuzzy & Extensions**: Identification, bandwidth selection, manipulation testing, RD checklist | _TBD_ |
| AI | **LLM Social Simulations for Economic & Social Research**: Homo Silicus, generative agents, agent-based social simulation, validation challenges | _TBD_ |




**Empirics References:**

- Goldsmith-Pinkham, P. Regression Discontinuity Part 1. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/20_regression_discontinuity_1.pdf) · Part 2. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/21_regression_discontinuity_2.pdf) · Part 3. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/22_regression_discontinuity_3.pdf)
- Cattaneo, M. D., Idrobo, N. & Titiunik, R. (2020). *A Practical Introduction to Regression Discontinuity Designs: Foundations*. Cambridge Elements. [Website](https://rdpackages.github.io/references/Cattaneo-Idrobo-Titiunik_2020_CUP.pdf)
- Cattaneo, M. D., Idrobo, N. & Titiunik, R. (2024). *A Practical Introduction to Regression Discontinuity Designs: Extensions*. Cambridge Elements. [Website](https://rdpackages.github.io/references/Cattaneo-Idrobo-Titiunik_2024_CUP.pdf)
- Hahn, J., Todd, P. & Van der Klaauw, W. (2001). Identification and Estimation of Treatment Effects with a Regression-Discontinuity Design. *Econometrica*, 69(1), 201--209. [DOI](https://doi.org/10.1111/1468-0262.00183)
- Calonico, S., Cattaneo, M. D. & Titiunik, R. (2014). Robust Nonparametric Confidence Intervals for Regression-Discontinuity Designs. *Econometrica*, 82(6), 2295--2326. [DOI](https://doi.org/10.3982/ECTA11757)
- McCrary, J. (2008). Manipulation of the Running Variable in the Regression Discontinuity Design: A Density Test. *Journal of Econometrics*, 142(2), 698--714. [DOI](https://doi.org/10.1016/j.jeconom.2007.05.005)
- Gelman, A. & Imbens, G. (2019). Why High-Order Polynomials Should Not Be Used in Regression Discontinuity Designs. *Journal of Business & Economic Statistics*, 37(3), 447--456. [DOI](https://doi.org/10.1080/07350015.2017.1366909)
- Gerard, F., Rokkanen, M. & Rothe, C. (2020). Bounds on Treatment Effects in Regression Discontinuity Designs with a Manipulated Running Variable. *Quantitative Economics*, 11(3), 839--870. [DOI](https://doi.org/10.3982/QE1370)
- **Software:** `rdrobust`, `rddensity`, `rdlocrand` — [RD Packages](https://rdpackages.github.io/)

**AI References:**

- Manning, B. S. & Horton, J. J. (2025). General Social Agents. [arXiv](https://arxiv.org/abs/2508.17407)
- Anthis, J. R., Liu, R., Richardson, S. M., Kozlowski, A. C., Koch, B., Evans, J., Brynjolfsson, E. & Bernstein, M. (2025). LLM Social Simulations Are a Promising Research Method. *ICML 2025*. [arXiv](https://arxiv.org/abs/2504.02234)
- Brynjolfsson, E., Enriquez, J. R., Kazinnik, S. & Nguyen, D. T. (2026). Augmenting Survey Data with Generative AI: An Application to Economic Research. [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6343598)
- Horton, J. J., Filippas, A. & Manning, B. S. (2023). Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus? [arXiv](https://arxiv.org/abs/2301.07543)
- Park, J. S., O'Brien, J. C., Cai, C. J., Morris, M. R., Liang, P. & Bernstein, M. S. (2023). Generative Agents: Interactive Simulacra of Human Behavior. *UIST 2023*. [arXiv](https://arxiv.org/abs/2304.03442)
- Argyle, L. P., Busby, E. C., Fulda, N., Gubler, J. R., Rytting, C. & Wingate, D. (2023). Out of One, Many: Using Language Models to Simulate Human Samples. *Political Analysis*. [DOI](https://doi.org/10.1017/pan.2023.2)
- Mei, Q., Xie, Y., Yuan, W. & Jackson, M. O. (2024). A Turing Test of Whether AI Chatbots Are Behaviorally Similar to Humans. *PNAS*, 121(10). [DOI](https://doi.org/10.1073/pnas.2313925121)
- Manning, B. S., Zhu, K. & Horton, J. J. (2024). Automated Social Science: Language Models as Scientist and Subjects. [arXiv](https://arxiv.org/abs/2404.11794)
- Aher, G. V., Arriaga, R. I. & Kalai, A. T. (2023). Using Large Language Models to Simulate Multiple Humans and Replicate Human Subject Studies. *ICML 2023*. [arXiv](https://arxiv.org/abs/2208.10264)
- Yang, Z. et al. (2024). OASIS: Open Agent Social Interaction Simulations with One Million Agents. [arXiv](https://arxiv.org/abs/2411.11581) · [GitHub](https://github.com/camel-ai/oasis)
- Piao, J. et al. (2025). AgentSociety: Large-Scale Simulation of LLM-Driven Generative Agents Advances Understanding of Human Behaviors and Society. [arXiv](https://arxiv.org/abs/2502.08691) · [GitHub](https://github.com/tsinghua-fib-lab/AgentSociety)
- Vezhnevets, A. S. et al. (Google DeepMind, 2023). Generative Agent-Based Modeling with Actions Grounded in Physical, Social, or Digital Space using Concordia. [arXiv](https://arxiv.org/abs/2312.03664) · [GitHub](https://github.com/google-deepmind/concordia)
- Bail, C. A. (2024). Can Generative AI Improve Social Science? *PNAS*. [DOI](https://doi.org/10.1073/pnas.2314021121)

---

### Week 8

| Track | Topic | Presenter |
|-------|-------|-----------|
| Empirics | **Double/Debiased Machine Learning**: Neyman orthogonality, cross-fitting, partially linear models, DML for ATE/CATE, IV and panel settings | _TBD_ |
| AI | **AI for Academic Writing & Peer Review**: Drafting, proofreading agents, LLM-assisted review, ethics and disclosure | _TBD_ |



**Empirics References:**

- Goldsmith-Pinkham, P. Machine Learning Part 1. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/23_machine_learning_1.pdf) · Part 2. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/24_machine_learning_2.pdf)
- Sant'Anna, P. Leveraging Advances in Machine Learning. [Slides](https://psantanna.com/DiD/06_DML.pdf)
- Chernozhukov, V., Chetverikov, D., Demirer, M., Duflo, E., Hansen, C., Newey, W. & Robins, J. (2018). Double/Debiased Machine Learning for Treatment and Structural Parameters. *Econometrics Journal*, 21(1), C1--C68. [DOI](https://doi.org/10.1111/ectj.12097)
- Chernozhukov, V., Hansen, C., Kallus, N., Spindler, M. & Syrgkanis, V. (2024). *Applied Causal Inference Powered by ML and AI*. [Free online](https://causalml-book.org/)
- Chernozhukov, V., Goldman, M., Semenova, V. & Taddy, M. (2021). Orthogonal Machine Learning for Demand Estimation: High-Dimensional Causal Inference in Dynamic Panels. [arXiv](https://arxiv.org/abs/1712.09988)
- Belloni, A., Chernozhukov, V. & Hansen, C. (2014). Inference on Treatment Effects after Selection among High-Dimensional Controls. *Review of Economic Studies*, 81(2), 608--650. [DOI](https://doi.org/10.1093/restud/rdt044)
- Farrell, M. H., Liang, T. & Misra, S. (2021). Deep Neural Networks for Estimation and Inference. *Econometrica*, 89(1), 181--213. [DOI](https://doi.org/10.3982/ECTA16901)
- **Software:** `DoubleML` — [Python/R](https://docs.doubleml.org/); `EconML` — [Python](https://econml.azurewebsites.net/)

**AI References:**

- Liang, W. et al. (2024). Can Large Language Models Provide Useful Feedback on Research Papers? A Large-Scale Empirical Analysis. *NEJM AI*. [DOI](https://doi.org/10.1056/AIoa2400196)
- Nature (2026). A Large-Scale Randomized Study of LLM Feedback in Peer Review. *Nature Machine Intelligence*. [Article](https://www.nature.com/articles/s42256-026-01188-x)
- Stanford HAI. How Much Research Is Being Written by Large Language Models? [Article](https://hai.stanford.edu/news/how-much-research-being-written-large-language-models)
- Nature Portfolio. AI Policy for Authors (LLM disclosure requirements). [Policy](https://www.nature.com/nature-portfolio/editorial-policies/ai)
- Large Language Models for Automated Scholarly Paper Review: A Survey (2025). [arXiv](https://arxiv.org/abs/2501.10326)

---

### Week 9

| Track | Topic | Presenter |
|-------|-------|-----------|
| Empirics | **ML × Causal Inference**: Causal forests, heterogeneous treatment effects (CATE), prediction vs. inference, policy learning | _TBD_ |
| AI | **AI for Theoretical Model Building & Mathematical Proof**: LLM-assisted formalization, theorem proving, model derivation, economic theory with AI | _TBD_ |

**Lecture Slides:**


**Empirics References:**

Goldsmith-Pinkham, P. Machine Learning Part 3. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/25_machine_learning_3.pdf)
- Athey, S. & Imbens, G. W. (2019). Machine Learning Methods That Economists Should Know About. *Annual Review of Economics*, 11, 685--725. [DOI](https://doi.org/10.1146/annurev-economics-080217-053433)
- Wager, S. & Athey, S. (2018). Estimation and Inference of Heterogeneous Treatment Effects Using Random Forests. *Journal of the American Statistical Association*, 113(523), 1228--1242. [DOI](https://doi.org/10.1080/01621459.2017.1319839)
- Athey, S. & Imbens, G. W. (2016). Recursive Partitioning for Heterogeneous Causal Effects. *PNAS*, 113(27), 7353--7360. [DOI](https://doi.org/10.1073/pnas.1510489113)
- Chernozhukov, V. et al. (2020). Generic Machine Learning Inference on Heterogeneous Treatment Effects in Randomized Experiments. [arXiv](https://arxiv.org/abs/1712.04802)
- Davis, J. & Heller, S. B. (2017). Using Causal Forests to Predict Treatment Heterogeneity: An Application to Summer Jobs. *American Economic Review: P&P*, 107(5), 546--550. [DOI](https://doi.org/10.1257/aer.p20171000)
- Fuster, A., Goldsmith-Pinkham, P., Ramadorai, T. & Walther, A. (2022). Predictably Unequal? The Effects of Machine Learning on Credit Markets. *Journal of Finance*, 77(1), 5--47. [DOI](https://doi.org/10.1111/jofi.13090)
- **Software:** `grf` (generalized random forests) — [R](https://grf-labs.github.io/grf/); `EconML` — [Python](https://econml.azurewebsites.net/)

**AI References:**

- Korinek, A. (2023). Language Models and Cognitive Automation for Economic Research. *NBER Working Paper* No. 30957. [NBER](https://www.nber.org/papers/w30957) — Systematic guide for economists on using LLMs for mathematical derivations, solving models, checking proofs, and deriving comparative statics; includes worked examples.
- Korinek, A. (2023). Generative AI for Economic Research: Use Cases and Implications for Economists. *Journal of Economic Literature*. [AEA](https://www.aeaweb.org/articles?id=10.1257/jel.20231736) — Published version covering LLM capabilities for game-theoretic models, mechanism design, and an honest assessment of failure modes in longer proofs.
- Manning, A. & Mendelson, J. (2025). Can AI Build Economic Models? A Comparative Study. [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5183832)
- Mannix, C. & Zhong, S. (2024). Can LLMs Solve Economic Models? A Systematic Evaluation — benchmarks on Nash equilibria, contract theory, principal-agent problems, optimal mechanism design. [arXiv](https://arxiv.org/abs/2407.00779)
- Duetting, P., Feng, Z., Narasimhan, H., Parkes, D. C. & Ravindranath, S. S. (2024). Mechanism Design for Large Language Models. [arXiv](https://arxiv.org/abs/2310.10826)
- Wolfram, S. (2023). ChatGPT Gets Its "Wolfram Superpowers" — LLM + computer algebra system workflow for solving FOCs, deriving comparative statics, verifying equilibrium conditions. [Blog](https://writings.stephenwolfram.com/2023/03/chatgpt-gets-its-wolfram-superpowers/)
- *Background on AI for mathematical reasoning (optional):*
  - Romera-Paredes, B. et al. (Google DeepMind, 2024). Mathematical Discoveries from Program Search with Large Language Models. *Nature*, 625, 468--475. [DOI](https://doi.org/10.1038/s41586-023-06924-6)
  - Yang, K. et al. (2024). LeanDojo: Theorem Proving with Retrieval-Augmented Language Models. *NeurIPS 2023*. [arXiv](https://arxiv.org/abs/2306.15626) · [GitHub](https://github.com/lean-dojo/LeanDojo)


---

### Week 10

| Track | Topic | Presenter |
|-------|-------|-----------|
| Empirics | **Partial Identification & Sensitivity Analysis**: Bounds under weaker assumptions, sensitivity of causal estimates, Rambachan & Roth (2023) | _TBD_ |
| AI | **Building Your AI-Augmented Research Workflow**: Integrating tools into a personal research pipeline, lessons learned, group discussion on adoption | _TBD_ |


**Empirics References:**

- Goldsmith-Pinkham, P. Partial Identification. [Slides](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/26_partial_identification.pdf)
- Molinari, F. (2020). Microeconometrics with Partial Identification. *Handbook of Econometrics*, Vol. 7A, 355--486. [DOI](https://doi.org/10.1016/bs.hoe.2020.05.002)
- Manski, C. F. (1990). Nonparametric Bounds on Treatment Effects. *American Economic Review: P&P*, 80(2), 319--323. [JSTOR](https://www.jstor.org/stable/2006592)
- Lee, D. S. (2009). Training, Wages, and Sample Selection: Estimating Sharp Bounds on Treatment Effects. *Review of Economic Studies*, 76(3), 1071--1102. [DOI](https://doi.org/10.1111/j.1467-937X.2009.00536.x)
- Imbens, G. W. & Manski, C. F. (2004). Confidence Intervals for Partially Identified Parameters. *Econometrica*, 72(6), 1845--1857. [DOI](https://doi.org/10.1111/j.1468-0262.2004.00555.x)
- Tamer, E. (2010). Partial Identification in Econometrics. *Annual Review of Economics*, 2, 167--195. [DOI](https://doi.org/10.1146/annurev.economics.050708.143401)
- Rambachan, A. & Roth, J. (2023). A More Credible Approach to Parallel Trends. *Review of Economic Studies*, 90(5), 2555--2591. [DOI](https://doi.org/10.1093/restud/rdad018)

**AI References:**

- Goldsmith-Pinkham, P. (2026). Research in the Time of AI. [Substack](https://paulgp.substack.com/p/research-in-the-time-of-ai)
- Xu, Y. & Yang, L. (2026). Scaling Reproducibility: An AI-Assisted Workflow for Large-Scale Replication and Reanalysis. [arXiv](https://arxiv.org/abs/2602.16733)
- Patterns / Cell Press (2025). Recalibrating Academic Expertise in the Age of Generative AI. [Article](https://www.cell.com/patterns/fulltext/S2666-3899(25)00321-6)
- Sant'Anna, P. claude-code-my-workflow (domain-agnostic academic workflow template). [GitHub](https://github.com/pedrohcgs/claude-code-my-workflow)
- Nature (2026). How to Build an AI Scientist: First Peer-Reviewed Paper Spills the Secrets. [Article](https://www.nature.com/articles/d41586-026-00899-w)



---

## General References

- Angrist, J. D. & Pischke, J.-S. (2009). *Mostly Harmless Econometrics*. Princeton University Press.
- Cunningham, S. (2021). *Causal Inference: The Mixtape*. Yale University Press. [Free online](https://mixtape.scunning.com/)
- Imbens, G. W. & Rubin, D. B. (2015). *Causal Inference for Statistics, Social, and Biomedical Sciences*. Cambridge University Press.
- Hansen, B. (2022). *Econometrics*. Princeton University Press. [Free online](https://www.ssc.wisc.edu/~bhansen/econometrics/)
- Chernozhukov, V. et al. (2024). *Applied Causal Inference Powered by ML and AI*. [Free online](https://causalml-book.org/)
- Aronow, P. M. & Miller, B. T. (2019). *Foundations of Agnostic Statistics*. Cambridge University Press.
- Healy, K. (2018). *Data Visualization: A Practical Introduction*. Princeton University Press. [Free online](https://socviz.co/)

- Goldsmith-Pinkham, P. Applied Empirical Methods (full course with slides and code). [GitHub](https://github.com/paulgp/applied-methods-phd)
- Sant'Anna, P. DID Resources (14-lecture course, checklist, software). [Website](https://psantanna.com/did-resources/)
- Velikov, M. AI in Business & Economic Research Wiki. [Website](https://velikov-mihail.github.io/ai-econ-wiki/)

---

*Last updated: 2026-04-07*
