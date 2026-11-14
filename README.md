<div align="center">

<!-- Banner estilo Matrix em SVG leve e estável -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:003B00,100:008F11&height=180&section=header&text=Ana%20Caroliny%20Machado&fontSize=40&fontColor=00FF41&animation=fadeIn&fontAlignY=38&desc=AI%20Engineering%20%26%20Data%20Engineering%20Enthusiast&descAlignY=62&descSize=17" width="100%" alt="Ana Caroliny Machado" />

<!-- Texto digitando em verde Matrix -->
<a href="https://github.com/wcarolf">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=680&lines=Computer+Networks+Student+%40+Anhanguera;Building+Autonomous+AI+Agents+in+Python;Data+Pipelines%2C+APIs+%26+LLM+Architectures" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00FF41)](https://www.linkedin.com/in/anacarolinyfmachado/)
[![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=00FF41)](https://github.com/wcarolf)
[![Location](https://img.shields.io/badge/São_Paulo,_Brazil-0D1117?style=for-the-badge&logo=google-maps&logoColor=00FF41)](#)
[![Views](https://komarev.com/ghpvc/?username=wcarolf&label=Profile+Views&color=008F11&style=for-the-badge)](https://github.com/wcarolf)
[![License](https://img.shields.io/badge/License-MIT-008F11?style=for-the-badge)](#contact)

**[ 🇧🇷 Mudar para Português (Change to Portuguese) ](#pt-br)**

---

### 📑 Table of Contents
`>` [About Me](#about-me) &nbsp;|&nbsp; [Tech Stack](#tech-stack) &nbsp;|&nbsp; [Architecture Flow](#architecture) &nbsp;|&nbsp; [Featured Project](#project) &nbsp;|&nbsp; [What I Wish I Knew](#tips) &nbsp;|&nbsp; [Contact & License](#contact)

</div>

<a name="about-me"></a>
### 🧑‍💻 About Me

- 🎓 Pursuing a degree in **Computer Networks (Redes de Computadores)** at Faculdade Anhanguera, building a solid foundation in protocols, architecture, and systems.
- 🚀 Transitioning into **Information Technology** with a sharp focus on **AI Engineering** and **Data Engineering**.
- 🧠 Driven by continuous learning, curiosity.
- 💼 Bringing **7+ years of experience** in sales — combining analytical problem-solving and communication with technical execution.

---

<a name="tech-stack"></a>
### 🛠️ Tech Stack & Tools

#### Languages & Data Manipulation
![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=00FF41)
![JSON](https://img.shields.io/badge/JSON-0D1117?style=for-the-badge&logo=json&logoColor=00FF41)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup4-0D1117?style=for-the-badge&logo=python&logoColor=00FF41)

#### AI Engineering & LLMs
![OpenAI SDK](https://img.shields.io/badge/OpenAI_SDK-0D1117?style=for-the-badge&logo=openai&logoColor=00FF41)
![OpenRouter](https://img.shields.io/badge/OpenRouter_API-0D1117?style=for-the-badge&logo=ai&logoColor=00FF41)
![Google Colab](https://img.shields.io/badge/Google_Colab-0D1117?style=for-the-badge&logo=googlecolab&logoColor=00FF41)

#### Environments & Version Control
![Linux](https://img.shields.io/badge/Linux-0D1117?style=for-the-badge&logo=linux&logoColor=00FF41)
![VS Code](https://img.shields.io/badge/VS_Code-0D1117?style=for-the-badge&logo=visual-studio-code&logoColor=00FF41)

---

<a name="architecture"></a>
### 🧠 Architecture Flow: ReAct AI Agents
> *A high-level view of the data flow in the autonomous agents I study and build.*

```mermaid
graph TD;
    A[Raw Web HTML] -->|BeautifulSoup| B(Data Cleaning & Parsing);
    B --> C{Agent Harness / ReAct Loop};
    C -->|JSON Schema Prompt| D[LLM Reasoning via API];
    D -->|Function Call| E[Action Execution];
    E -->|Success/Error Feedback| C;
    C -->|Final Answer| F[Automated Output];
    
    classDef matrix fill:#0D1117,stroke:#00FF41,stroke-width:2px,color:#00FF41;
    class A,B,C,D,E,F matrix;
