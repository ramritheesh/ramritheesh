<!-- HEADER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=Ram%20Ritheesh&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Robotics%20and%20AI%20%7C%20Building%20ML%20systems%20that%20ship&descAlignY=58&descSize=18" alt="header" />

<!-- TYPING ANIMATION -->
<div align="center">
  <a href="https://github.com/ramritheesh">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=36BCF7&center=true&vCenter=true&width=760&height=50&lines=Robotics+and+AI+Student+%40+BIT+%7C+CGPA+8.63;Fraud+detection+that+explains+itself+(SHAP);RAG+pipelines+and+LLM+apps+with+Gemini;From+raw+data+to+FastAPI+to+React+dashboards;Open+to+AI%2FML+internships+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</div>

<br>

<!-- CONTACT BADGES -->
<p align="center">
  <a href="https://www.linkedin.com/in/k-v-ram-ritheesh"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ram123ritheesh@gmail.com"><img src="https://img.shields.io/badge/Gmail-Email%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Status-Open%20to%20Internships-2ea44f?style=for-the-badge" alt="Open to work">
  <img src="https://hits.sh/github.com/ramritheesh.svg?style=for-the-badge&label=Profile%20Views&color=7c3aed" alt="Profile views">
</p>

---

## 👨💻 About Me

<table>
<tr>
<td width="55%" valign="top">

```python
class RamRitheesh:
    def __init__(self):
        self.role      = "AI/ML Engineer (in the making)"
        self.studying  = "B.Tech, Robotics and AI @ BIT"
        self.cgpa      = 8.63
        self.location  = "Bengaluru, India"
        self.loves     = ["ML pipelines", "LLM apps",
                          "Explainable AI", "Clean APIs"]
        self.looking_for = "AI/ML internship"

    def mission(self):
        return "Turn messy data into models people can trust."
```

</td>
<td width="45%" valign="top">

🔭 **Building:** LLM, RAG and fraud-detection systems

🧪 **Obsessed with:** model evaluation and explainability

⚙️ **Strength:** end-to-end, from SQL and models to APIs and UI

🎯 **Goal:** ship production-ready AI at a product team

</td>
</tr>
</table>

---

## 🧰 Tech Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cpp,js,ts,sklearn,pandas,numpy,fastapi,react,vite,nodejs,express,postgres,mongodb,powerbi,docker,git,github,vercel,postman,linux&perline=7" alt="skills" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat-square" />
  <img src="https://img.shields.io/badge/SHAP-FF6F00?style=flat-square" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-0ea5e9?style=flat-square" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/imbalanced--learn-6f42c1?style=flat-square" />
</p>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" align="center">
  <a href="https://github.com/ramritheesh/razorguard">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ramritheesh&repo=razorguard&theme=tokyonight&hide_border=true" />
  </a>
</td>
<td width="50%" align="center">
  <a href="https://github.com/ramritheesh/career-os-ai-career-assistant">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ramritheesh&repo=career-os-ai-career-assistant&theme=tokyonight&hide_border=true" />
  </a>
</td>
</tr>
<tr>
<td width="50%" align="center">
  <a href="https://github.com/ramritheesh/ScamShield-AI">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ramritheesh&repo=ScamShield-AI&theme=tokyonight&hide_border=true" />
  </a>
</td>
<td width="50%" align="center">
  <a href="https://github.com/ramritheesh/ai-insurance-classifier">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ramritheesh&repo=ai-insurance-classifier&theme=tokyonight&hide_border=true" />
  </a>
</td>
</tr>
</table>

### 🛡️ RazorGuard: fraud detection that explains itself

> Rule-based fraud limits miss behavioral patterns. RazorGuard scores each transaction against the customer's own history.

| 🎯 ROC-AUC | ⚖️ Threshold | 🔁 Recall | ⚡ Latency |
|:---:|:---:|:---:|:---:|
| **0.9055** | **0.18** (cost-sensitive) | **61.9%** | **< 200 ms** |

```mermaid
flowchart LR
    A["Transaction"] --> B["Feature engineering<br/>amount ratio, merchant velocity"]
    B --> C["XGBoost classifier"]
    C --> D["SHAP explanation"]
    C --> E{"Risk score 0-100"}
    E -->|low| F["ALLOW"]
    E -->|medium| G["REVIEW"]
    E -->|high| H["BLOCK"]
    D --> I["React dashboard"]
    E --> I
```

<details>
<summary><b>🔍 More project highlights (click to expand)</b></summary>
<br>

**🧭 Career.OS: AI career assistant**
Ranks jobs with a hybrid score: **40% keyword + 60% semantic similarity** (Hugging Face embeddings, cosine similarity). A RAG pipeline powered by Gemini gives personalized career chat, and the "Explain My Match" feature shows skill gaps and strengths. JWT auth with per-user data isolation.
`React` `Node.js` `Express` `MongoDB Atlas` `Gemini API` `RAG`

**🚨 ScamShield AI: digital safety agent**
Paste a suspicious SMS, email or screenshot and get a **0-100 risk score**, a classification and clear next steps. Async FastAPI backend with structured Gemini prompts and multimodal screenshot analysis. API keys stay server-side.
`FastAPI` `Gemini API` `React` `Render` `Vercel`

**📄 InsurAI Classifier: claims triage**
Hybrid NLP and generative AI pipeline that classifies unstructured insurance claim documents and extracts policy entities and triage tags.
`TypeScript` `React` `NLP` `Gemini API`

</details>

---

## 💼 Experience

<details open>
<summary><b>Project Intern · KodNest Technologies</b> &nbsp;|&nbsp; Feb 2026 to May 2026</summary>
<br>

- ⚙️ Built **FastAPI** microservice components with **Pydantic** contracts between services
- 🧹 Automated ingestion validation that filtered malformed inputs with **95% precision**
- 🧪 Wrote **Pytest** unit and regression suites that caught **25+** integration bugs before staging
- 📊 Built Power BI and Excel reports for team leads; documented runbooks and test logs on Git/GitHub

</details>

<details>
<summary><b>🎓 Education and certifications</b></summary>
<br>

- **B.Tech, Robotics and Artificial Intelligence**, Bangalore Institute of Technology (2022 to 2026), **CGPA 8.63/10**
- AI/ML Specialization, **Infosys**
- Introduction to Machine Learning, **NPTEL**
- Full-Stack Web Development, **Internshala**
- AI Foundation Course, **Jio Institute**

</details>

---

## 📊 GitHub Analytics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=ramritheesh&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramritheesh&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ramritheesh&theme=tokyo-night&hide_border=true&area=true" width="100%" />
</p>

---

## 🤝 Let's Connect

<div align="center">

**Hiring for AI/ML, or building something with LLMs? Let's talk.**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/k-v-ram-ritheesh)
[![Email](https://img.shields.io/badge/-ram123ritheesh@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ram123ritheesh@gmail.com)

*"Models are easy to build. Models people can trust are the real work."*

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" alt="footer" />
