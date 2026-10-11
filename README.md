# 👋 About Me

Hi, I'm Akshay, an **AI Product Manager** who builds what he specs. I spent 3+ years on data systems in fintech (credit intelligence at 9fin, bank-statement pipelines and merchant categorization at Catalysk). Now I ship AI products for Indian users end to end: PRD, evaluation, release gate and live deploy.

My rule: **a model ships when an evaluation says it's ready.** I freeze held-out data before writing the first prompt, put the release gate in the PRD, and publish the results, failed runs included.

### 🚀 Recently shipped

| Project | What it does | What I measured |
|---|---|---|
| [**Why Did It Drop?**](https://github.com/AKSHAYKUMARDHAR/Why-Did-It-Drop) · [benchmark](https://akshaykumardhar.github.io/Why-Did-It-Drop/) | An analytics agent that explains why a product metric moved, and says when it can't. Code computes every number and checks tracking first; the model explains | Tested on 70 incidents planted in Google's real GA4 data, frozen before any prompt. Failed its gate (20% wrong causes against 5%), and the model added no decision value over fixed rules |
| [**RBI Circular Radar**](https://github.com/AKSHAYKUMARDHAR/RBI-Circular-Radar) · [live](https://akshaykumardhar.github.io/RBI-Circular-Radar/) | Checks RBI every 10 minutes. For each new notification it says which of 17 entity types it applies to, what to do and by when, quoting RBI's own words and page | 1 missed pair in 51 at 100% precision on a fresh held-out run. Verification cut wrong dates from 11 in 165 to 1 |
| [**Will My Policy Pay?**](https://github.com/AKSHAYKUMARDHAR/Will-My-Policy-Pay) · [live](https://will-my-policy-pay.onrender.com) | Explains health insurance fine print in plain English, citing the policy terms, and simulates a hospital bill line by line | 91.4% correct on 152 held-out facts from real policies by 8 insurers. The simulator matches all 25 hand-worked bills |
| [**Is This a Scam?**](https://github.com/AKSHAYKUMARDHAR/Is-This-A-Scam) · [live](https://is-this-a-scam.onrender.com) | Checks messages for scams in Hindi, Bengali and English. It has three verdicts and says "can't tell" when it can't, without guessing | No scams cleared and no injection flips in two held-out runs. 1 false alarm in 114 genuine messages |
| [**UPI Triage Agent**](https://github.com/AKSHAYKUMARDHAR/UPI-Triage-Agent) | Uses an LLM agent to categorize UPI transactions, with MCP tools, RAG on pgvector, a human review queue and an n8n trigger | 98% precision at 86% automation on unseen data. RAG cut unknown payees posted wrong from 44% to 0% |

Four of these are still held back by their own release gates, and each README shows why. I'd rather publish a failed gate than a flattering number.

### 🎯 Roles I'm looking for

AI Product Manager · Associate PM – AI · Technical Product Manager · AI Product Analyst. My focus is fintech, regtech and consumer finance.

### 🧠 What I bring

- **Product:** PRDs with measurable release gates, success metrics, A/B tests, and trade-offs between recall and precision
- **AI / LLMs:** agents and tool use (MCP), RAG, structured extraction with quote verification, prompt-injection guards, self-consistency
- **Evaluation:** golden and held-out sets, ablations, labelling guides, error analysis
- **Data:** Python, SQL/PostgreSQL, ELT pipelines, FastAPI, AWS

📂 **Portfolio and case studies:** [akshaykumardhar.github.io](https://akshaykumardhar.github.io)

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshaydh) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/@AKSHAYKUMARDH15) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:akshaykumardhar14@gmail.com)

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

# 📊 GitHub Stats:

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=AKSHAYKUMARDHAR&theme=dracula)](https://git.io/streak-stats)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
