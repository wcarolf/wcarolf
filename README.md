<div align="center">

<!-- Título principal animado em verde Matrix -->
<a href="https://github.com/wcarolf">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=34&duration=2000&pause=5000&color=00FF41&center=true&vCenter=true&width=700&lines=Ana+Caroliny" alt="Ana Caroliny" />
</a>

<!-- Subtítulo dinâmico com as tuas áreas de foco -->
<a href="https://github.com/wcarolf">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=700&lines=AI+Engineering+%26+Data+Engineering+Enthusiast;Computer+Networks+Student+%40+Anhanguera;Building+Autonomous+AI+Agents+in+Python" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00FF41)](https://www.linkedin.com/in/anacarolinyfmachado/)
[![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=00FF41)](https://github.com/wcarolf)
[![Location](https://img.shields.io/badge/São_Paulo,_Brazil-0D1117?style=for-the-badge&logo=google-maps&logoColor=00FF41)](#)
[![Views](https://komarev.com/ghpvc/?username=wcarolf&label=Profile+Views&color=008F11&style=for-the-badge)](https://github.com/wcarolf)
[![License](https://img.shields.io/badge/License-MIT-008F11?style=for-the-badge)](#contact)

<br/>

**[ 🇧🇷 Mudar para Português (Change to Portuguese) ](#pt-br)**

<br/>

### 📑 Table of Contents
[About Me](#about-me) &nbsp;•&nbsp; [Tech Stack](#tech-stack) &nbsp;•&nbsp; [Architecture](#architecture) &nbsp;•&nbsp; [Project](#project) &nbsp;•&nbsp; [Tips & Insights](#tips)

</div>

<br/>

<a name="about-me"></a>
### 🧑‍💻 About Me

- 🎓 Pursuing a degree in **Computer Networks (Redes de Computadores)** at Faculdade Anhanguera.
- 🚀 Transitioning into Tech, focusing on **AI Engineering** and **Data Engineering**.
- 🧠 Driven by continuous learning, curiosity.
- 💼 **7+ years of experience** in sales — combining analytical problem-solving and communication with technical execution.

---

<a name="tech-stack"></a>
### 🛠️ Tech Stack & Tools

**Languages & Data:** &nbsp; ![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=00FF41) ![JSON](https://img.shields.io/badge/JSON-0D1117?style=flat-square&logo=json&logoColor=00FF41) ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup4-0D1117?style=flat-square&logo=python&logoColor=00FF41)  
**AI Engineering:** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![OpenAI SDK](https://img.shields.io/badge/OpenAI_SDK-0D1117?style=flat-square&logo=openai&logoColor=00FF41) ![OpenRouter](https://img.shields.io/badge/OpenRouter_API-0D1117?style=flat-square&logo=ai&logoColor=00FF41)  
**Environments:** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![Linux](https://img.shields.io/badge/Linux-0D1117?style=flat-square&logo=linux&logoColor=00FF41) ![VS Code](https://img.shields.io/badge/VS_Code-0D1117?style=flat-square&logo=visual-studio-code&logoColor=00FF41) ![Google Colab](https://img.shields.io/badge/Colab-0D1117?style=flat-square&logo=googlecolab&logoColor=00FF41)

---

<a name="architecture"></a>
### 🧠 Architecture Flow: ReAct AI Agents
*How I structure data flows in my autonomous agent implementations.*

```mermaid
graph TD;
    A[Raw Web HTML] -->|BeautifulSoup| B(Data Parsing & Cleaning);
    B --> C{Agent Harness / ReAct Loop};
    C -->|JSON Schema Prompt| D[LLM Reasoning API];
    D -->|Function Call| E[Action Execution];
    E -->|Success/Error Feedback| C;
    C -->|Final Answer| F[Automated Output];
    
    classDef matrix fill:#0D1117,stroke:#00FF41,stroke-width:1px,color:#00FF41;
    class A,B,C,D,E,F matrix;
