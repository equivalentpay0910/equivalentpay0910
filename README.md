<p align="center">
  <img src="banner.png" alt="Pixel art banner: Esha's character waving next to a little farmhouse, with the text Hi, I'm Esha" width="100%">
</p>

<p align="center">
  Data Science @ San José State University · Minors in Statistics + CS · SF Bay Area<br>
  <b>Seeking Summer 2027 SWE + ML internships</b>
</p>

<p align="center">
  <a href="https://equivalentpay0910.github.io"><img src="https://img.shields.io/badge/Portfolio-equivalentpay0910.github.io-6E9F59?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/esha-h/"><img src="https://img.shields.io/badge/LinkedIn-esha--h-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:esha.hooda@sjsu.edu"><img src="https://img.shields.io/badge/Email-esha.hooda@sjsu.edu-C23B2E?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

I build AI and software people can actually trust: agents, RAG systems, and the data pipelines underneath. Previously a **Deep Learning Intern at Hewlett Packard Enterprise × National University of Singapore**, now building AI agents and doing ML research at SJSU. Feel free to look around my repos and reach out!

---

## 🔗 About Me

- 🎓 **B.S. Data Science** at SJSU, graduating **Dec 2027**, with a concentration in Public Health
- 💼 **Previously:** Deep Learning Intern @ HPE × NUS (Singapore), where I trained a posture-detection model to **93% accuracy** and shipped models into Azure deployment pipelines
- 🛠️ **Currently building:** **Daybeam**, an AI planning agent, and **LegalBee**, a RAG legal copilot I lead at SJSU's Responsible Computing Club
- 🔬 **Researching:** diffusion models (SR3) for fluorescence microscopy super-resolution, plus causal-inference models on 70K+ student records to evaluate SJSU's Learning Assistant Program
- 🌱 **Learning right now:** diffusion models, agent evaluation, and search-based planning (ReAct, beam search)
- ⚡ **Fun facts:** I've been to six continents and I run on matcha 🍵

---

## 🛠️ Tools & Languages

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white)

**ML & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow%2FKeras-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6E9F59?style=flat-square)
![LLM Agents](https://img.shields.io/badge/LLM%20Agents%20%2B%20Tool--calling-6E9F59?style=flat-square)
![Claude API](https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white)

**Software, Data & Cloud**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

---

## 💻 Featured Projects

### 🌅 Daybeam · *in progress, repo coming soon*
An AI planning agent that turns "plan my Saturday in San José: farmers market before noon, lunch under $20, home by 6" into a full day plan.

- Tool calls to an **A\* route planner** over San José roads, a places lookup, and a **code-based checker** that verifies every constraint (time windows, budget, travel time, opening hours)
- Compares **one-shot, ReAct, and beam-search** planning on **hundreds of multi-constraint tasks** for success rate, cost, and speed: does extra search buy more correct plans, and is it worth the cost?
- **Tech:** Python · LLM tool-calling · ReAct · beam search · A\* · Streamlit

### 🐝 LegalBee · *in progress, repo coming soon*
A jurisdiction-aware **RAG copilot** that answers legal questions from government, court, and legal-aid sources, with citations and explicit confidence signals.

- First vertical: **California tenant law**, with retrieval accuracy and hallucination rate built in as evaluation metrics from day one
- I lead the project at SJSU's Responsible Computing Club: roadmap, weekly sprints, and hands-on building
- **Tech:** Python · RAG (embeddings + vector search) · LLM prompting · NLP classification

### 🤖 [AI Job Application Tracker Agent](https://github.com/equivalentpay0910/job-tracker-agent)
A full-stack agent that decides on its own which tools to call when given a job posting.

- **5-tool architecture:** parse the posting, fetch the resume, score fit, log the result
- Persisted conversation memory, plus a scoring prompt written specifically to avoid inflating fit scores
- **Tech:** Python · Flask · SQLite · Anthropic Claude API (tool-calling) · RAG · JavaScript

### 🛡️ Trust & Safety Risk Pipeline · *repo coming soon*
A multimodal risk-detection pipeline that combines **3 signal types** (tabular fraud, NLP content, image risk) into **1 unified risk score**.

- **Tech:** Python · SQL · PySpark · XGBoost · Hugging Face Transformers · PyTorch · Docker

### 📈 Stock Volatility Prediction Pipeline · *repo coming soon*
A distributed **PySpark pipeline on GCP** processing **600,000+ daily trades** across **500+ stocks**.

- Random forest feature importance identified prior-day intraday range as the dominant volatility predictor (0.837)
- Served as lead engineer and PM: feature roadmap, weekly report-outs, and dashboards
- **Tech:** Python · PySpark · SQL · ETL · GCP · Pandas

<details>
<summary><b>More projects</b></summary>

- **Fake News Detection Using LSTM & BERT:** compared 4 models on 20,000 articles and traced near-perfect scores to a source-style confound inflating every model; recommended cross-source validation
- **[LeetCode / NeetCode practice](https://github.com/equivalentpay0910/leetcode-practice):** daily data structures + algorithms practice in Python, organized by pattern (two pointers, sliding window, graphs, DP and more) so weak spots are easy to see
- **[Pixel farm portfolio](https://github.com/equivalentpay0910/equivalentpay0910.github.io):** my personal site at [equivalentpay0910.github.io](https://equivalentpay0910.github.io), built in plain HTML, CSS, and JavaScript with Claude as my coding partner, including original pixel art drawn in code

</details>

---

## 🔬 Research

- **Diffusion Models for Microscopy Super-Resolution** (Advisor: Dr. Tahir Bachar Issa, SJSU): applying SR3 to video-rate fluorescence microscopy, replacing a GAN-based baseline
- **Learning Assistant Program Evaluation** (Advisor: Dr. Cassandra Paul, SJSU Research Foundation): logistic regression, OLS with course fixed effects, HLM, and propensity score matching on 70K+ student records; currently testing for an instructor effect

---

## 🏅 Certifications

Machine Learning & AI (IIT Bombay / IIT Madras) · Code in Place (Stanford) · IRB Research Training · CRLA Levels 1 & 2 · Fundamental AI Algorithms & Applications (SJSU, expected May 2027)

---

## 📫 Connect With Me

I'd love to hear what you're building. Let's connect and talk about how I can contribute!

🌐 [Portfolio](https://equivalentpay0910.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/esha-h/) · ✉️ [esha.hooda@sjsu.edu](mailto:esha.hooda@sjsu.edu)
