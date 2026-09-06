<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:0D1117,50:1B1F27,100:0D1117&text=Daksha%20Mehta&fontColor=E7E2D6&fontSize=40&fontAlignY=34&animation=fadeIn&desc=Agentic%20AI%20%2F%20MLOps&descAlignY=58&descSize=16&descColor=C99A5B" alt="Daksha Mehta" />
  <br />
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=17&pause=1500&color=8A9BA8&center=true&vCenter=true&width=520&height=32&lines=Agentic+AI+systems%2C+end+to+end.;Multi-agent+orchestration.;FastAPI+backends.+MLOps+that+ships." alt="Typing SVG" /></a>
</p>

## About

<img align="left" width="190" src="assets/ice-bear.png" alt="Ice Bear resting his chin on his paws, content and unbothered" />

B.Tech Information Technology at **ABV-IIITM Gwalior**, class of 2028. I build **agentic AI systems** — the kind where several specialized agents have to agree on an answer — and the **MLOps** around them, because a model that never leaves a notebook hasn't done anything yet.

Most of what I work on sits at the seam between the two: an agent that calls five external services and still has to return something trustworthy, a classifier that has to notice when the data underneath it has quietly shifted. The interesting problems are rarely the model. They're the schema, the retry, the drift test that fires at 3am.

Outside the code, I'm **Vice Chair of the IEEE Student Branch** at ABV-IIITM Gwalior, where I run logistics for hackathons that pull 1,000+ participants and mentor juniors through their first GenAI projects.

---

## Selected Work

### [AAFA — AI Agent Financial Analyst](https://github.com/Daksha1611/AI-Agent-Financial-Analyst)

A multi-agent financial analysis platform built on **CrewAI**, orchestrating separate quantitative and qualitative agents that pull live market data through yfinance and Firecrawl.

The backend is async **FastAPI** integrating five external services — yfinance, Firecrawl, OpenRouter, Azure Blob Storage, Azure PostgreSQL — with reports persisted through SQLAlchemy ORM. Three **Pydantic**-validated tool schemas keep agent output honest, and **LiteLLM** lets the whole thing migrate across OpenAI, Groq, and OpenRouter without touching a line of agent logic.

![Python](https://img.shields.io/badge/Python-14161B?style=flat-square&logo=python&logoColor=C7C0AE)
![CrewAI](https://img.shields.io/badge/CrewAI-14161B?style=flat-square&logoColor=C7C0AE)
![LiteLLM](https://img.shields.io/badge/LiteLLM-14161B?style=flat-square&logoColor=C7C0AE)
![FastAPI](https://img.shields.io/badge/FastAPI-14161B?style=flat-square&logo=fastapi&logoColor=C7C0AE)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-14161B?style=flat-square&logo=sqlalchemy&logoColor=C7C0AE)
![Azure](https://img.shields.io/badge/Azure-14161B?style=flat-square&logo=microsoftazure&logoColor=C7C0AE)

### [Network Security — Phishing Detection MLOps](https://github.com/Daksha1611/NetworkSecurity)

An end-to-end MLOps pipeline on the UCI Phishing dataset — **11,000+ samples, 30 features** — where five candidate algorithms are evaluated before the best one is promoted to deployment.

The part I care about is what happens after training. Validation and preprocessing run **KNN imputation** for missing values and **KS-tests** to catch statistical drift between the training distribution and whatever inference actually sees. **GitHub Actions** containerizes the app, pushes to **AWS ECR** for EC2 deployment, and logs every experiment to **MLflow** through DagsHub.

![Python](https://img.shields.io/badge/Python-14161B?style=flat-square&logo=python&logoColor=C7C0AE)
![FastAPI](https://img.shields.io/badge/FastAPI-14161B?style=flat-square&logo=fastapi&logoColor=C7C0AE)
![MLflow](https://img.shields.io/badge/MLflow-14161B?style=flat-square&logo=mlflow&logoColor=C7C0AE)
![Docker](https://img.shields.io/badge/Docker-14161B?style=flat-square&logo=docker&logoColor=C7C0AE)
![AWS](https://img.shields.io/badge/AWS_ECR_+_EC2-14161B?style=flat-square&logo=amazonwebservices&logoColor=C7C0AE)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-14161B?style=flat-square&logo=githubactions&logoColor=C7C0AE)

### [InterVue — AI-Powered Interview Coach](https://github.com/Daksha1611/InterVue)

A full-stack interview platform on MVC architecture, exposing **14 REST endpoints** over MongoDB.

Resume scoring is deliberately hybrid: a rule-based pass across five dimensions handles what is objectively checkable, and **GPT-4o-mini** via OpenRouter handles the contextual judgement a rulebook can't encode. Voice interaction runs entirely on the browser-native **Web Speech API** — SpeechSynthesis and SpeechRecognition — so the whole feature costs nothing per user.

![Node.js](https://img.shields.io/badge/Node.js-14161B?style=flat-square&logo=nodedotjs&logoColor=C7C0AE)
![Express](https://img.shields.io/badge/Express-14161B?style=flat-square&logo=express&logoColor=C7C0AE)
![MongoDB](https://img.shields.io/badge/MongoDB-14161B?style=flat-square&logo=mongodb&logoColor=C7C0AE)
![OpenRouter](https://img.shields.io/badge/OpenRouter-14161B?style=flat-square&logoColor=C7C0AE)
![Web Speech API](https://img.shields.io/badge/Web_Speech_API-14161B?style=flat-square&logoColor=C7C0AE)

<details>
<summary><strong>Also on the shelf</strong> — hackathon builds and earlier work</summary>
<br />

- [**Interlock**](https://github.com/Daksha1611/Interlock) — payment-recovery agent designed for safety first. Built for the Razorpay AI Buildathon.
- [**papersynth**](https://github.com/Daksha1611/papersynth) — synthesizes implementation specs from multiple research papers, with citations intact.
- [**pharos**](https://github.com/Daksha1611/pharos) — disaster resource orchestration, turning multilingual distress signals into something dispatchable.
- [**In-Depth EDA**](https://github.com/Daksha1611/In-Depth-Exploratory-Data-Analysis-EDA-) — kept around because it's where the statistics habits started.

</details>

---

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-14161B?style=for-the-badge&logo=python&logoColor=C7C0AE)
![C++](https://img.shields.io/badge/C++-14161B?style=for-the-badge&logo=cplusplus&logoColor=C7C0AE)
![JavaScript](https://img.shields.io/badge/JavaScript-14161B?style=for-the-badge&logo=javascript&logoColor=C7C0AE)
![SQL](https://img.shields.io/badge/SQL-14161B?style=for-the-badge&logo=postgresql&logoColor=C7C0AE)
![Java](https://img.shields.io/badge/Java-14161B?style=for-the-badge&logo=openjdk&logoColor=C7C0AE)
![Verilog](https://img.shields.io/badge/Verilog-14161B?style=for-the-badge&logoColor=C7C0AE)

**AI / ML**

![Generative AI](https://img.shields.io/badge/Generative_AI-1E1812?style=for-the-badge&logo=openai&logoColor=C99A5B)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-1E1812?style=for-the-badge&logoColor=C99A5B)
![CrewAI](https://img.shields.io/badge/CrewAI-1E1812?style=for-the-badge&logoColor=C99A5B)
![LiteLLM](https://img.shields.io/badge/LiteLLM-1E1812?style=for-the-badge&logoColor=C99A5B)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1E1812?style=for-the-badge&logo=scikitlearn&logoColor=C99A5B)
![TensorFlow](https://img.shields.io/badge/TensorFlow-1E1812?style=for-the-badge&logo=tensorflow&logoColor=C99A5B)
![Keras](https://img.shields.io/badge/Keras-1E1812?style=for-the-badge&logo=keras&logoColor=C99A5B)
![MLflow](https://img.shields.io/badge/MLflow-1E1812?style=for-the-badge&logo=mlflow&logoColor=C99A5B)

**Backend / APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-14161B?style=for-the-badge&logo=fastapi&logoColor=C7C0AE)
![Pydantic](https://img.shields.io/badge/Pydantic-14161B?style=for-the-badge&logo=pydantic&logoColor=C7C0AE)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-14161B?style=for-the-badge&logo=sqlalchemy&logoColor=C7C0AE)
![Node.js](https://img.shields.io/badge/Node.js-14161B?style=for-the-badge&logo=nodedotjs&logoColor=C7C0AE)
![Express](https://img.shields.io/badge/Express-14161B?style=for-the-badge&logo=express&logoColor=C7C0AE)

**Cloud / DevOps**

![AWS](https://img.shields.io/badge/AWS-14161B?style=for-the-badge&logo=amazonwebservices&logoColor=C7C0AE)
![Azure](https://img.shields.io/badge/Azure-14161B?style=for-the-badge&logo=microsoftazure&logoColor=C7C0AE)
![Docker](https://img.shields.io/badge/Docker-14161B?style=for-the-badge&logo=docker&logoColor=C7C0AE)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-14161B?style=for-the-badge&logo=githubactions&logoColor=C7C0AE)
![Linux](https://img.shields.io/badge/Linux-14161B?style=for-the-badge&logo=linux&logoColor=C7C0AE)
![Git](https://img.shields.io/badge/Git-14161B?style=for-the-badge&logo=git&logoColor=C7C0AE)

**Data / Frontend**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14161B?style=for-the-badge&logo=postgresql&logoColor=C7C0AE)
![MongoDB](https://img.shields.io/badge/MongoDB-14161B?style=for-the-badge&logo=mongodb&logoColor=C7C0AE)
![pandas](https://img.shields.io/badge/pandas-14161B?style=for-the-badge&logo=pandas&logoColor=C7C0AE)
![NumPy](https://img.shields.io/badge/NumPy-14161B?style=for-the-badge&logo=numpy&logoColor=C7C0AE)
![Streamlit](https://img.shields.io/badge/Streamlit-14161B?style=for-the-badge&logo=streamlit&logoColor=C7C0AE)
![React](https://img.shields.io/badge/React-14161B?style=for-the-badge&logo=react&logoColor=C7C0AE)

---

## Beyond The Code

- **AWS Certified AI Practitioner** (AIF-C01), plus a Complete Data Science & ML Bootcamp.
- **Vice Chair, IEEE Student Branch, ABV-IIITM Gwalior** — led sponsorship, logistics, and operations for Hacksagon 2026 and Hackagon, supporting 1,000+ participants, and coordinated the IEEE IATMSI international conference.
- **Technical mentorship** — running sessions on Generative AI and ML fundamentals, walking students through designing and shipping their first AI projects.

---

## GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Daksha1611&hide_border=true&background=00000000&stroke=8A9BA8&ring=C99A5B&fire=C99A5B&currStreakLabel=C99A5B&sideLabels=8A9BA8&dates=8A9BA8&currStreakNum=E7E2D6&sideNums=E7E2D6&titleColor=E7E2D6" alt="GitHub streak" width="430" />
  &nbsp;
  <img src="https://github-readme-stats-one-bice.vercel.app/api/top-langs/?username=Daksha1611&layout=compact&langs_count=8&hide_border=true&bg_color=00000000&title_color=E7E2D6&text_color=8A9BA8" alt="Top languages" width="340" />
</p>

---

<p align="center">
  <a href="https://www.linkedin.com/in/daksha1611">
    <img src="https://img.shields.io/badge/linkedin-14161B?style=for-the-badge&logo=linkedin&logoColor=C7C0AE" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:mehtadaksha1611@gmail.com">
    <img src="https://img.shields.io/badge/email-14161B?style=for-the-badge&logo=gmail&logoColor=C7C0AE" alt="Email" />
  </a>
  &nbsp;
  <a href="https://github.com/Daksha1611">
    <img src="https://img.shields.io/badge/github-14161B?style=for-the-badge&logo=github&logoColor=C7C0AE" alt="GitHub" />
  </a>
</p>

<p align="center">
  <i>Still building. Still shipping. Still learning what breaks in production.</i>
</p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=90&color=0:0D1117,50:1B1F27,100:0D1117&section=footer" alt="" />
</p>
