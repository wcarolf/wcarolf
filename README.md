<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:003B00,100:00FF41&height=120&section=header" alt="" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=44&duration=3000&pause=1000&color=00FF41&background=000000&center=true&vCenter=true&repeat=false&width=800&height=80&lines=ANA+CAROLINY_" alt="Ana Caroliny" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=2500&pause=1000&color=00E5FF&background=000000&center=true&vCenter=true&repeat=false&width=800&height=40&lines=%5B+AI+ENGINEERING+%5D_" alt="AI Engineering" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1200&color=00FF41&background=000000&center=true&vCenter=true&width=800&height=40&lines=%5B+SYSTEM+ONLINE+%5D;Wake+up%2C+Ana...;LLM+%2F%2F+Tool+Calling+%2F%2F+Guardrails" alt="typing" />

<br/>

![Python](https://img.shields.io/badge/PYTHON-000000?style=for-the-badge&logo=python&logoColor=00FF41)
![OpenAI SDK](https://img.shields.io/badge/OPENAI_SDK-000000?style=for-the-badge&logo=openai&logoColor=00FF41)
![OpenRouter](https://img.shields.io/badge/OPENROUTER-000000?style=for-the-badge&logoColor=00FF41)
![Google Colab](https://img.shields.io/badge/COLAB-000000?style=for-the-badge&logo=googlecolab&logoColor=00FF41)
![Linux](https://img.shields.io/badge/LINUX-000000?style=for-the-badge&logo=linux&logoColor=00FF41)
![VS Code](https://img.shields.io/badge/VS_CODE-000000?style=for-the-badge&logo=visualstudiocode&logoColor=00FF41)
![Git](https://img.shields.io/badge/GIT-000000?style=for-the-badge&logo=git&logoColor=00FF41)


</div>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=2000&pause=1000&color=00FF41&background=000000&center=false&vCenter=true&repeat=false&width=800&height=44&lines=%3E+whoami_" alt="whoami" />

```bash
$ whoami
ana_caroliny

$ cat profile.txt
role        : Engenharia de IA
education   : Tecnologia em Redes de Computadores
looking_for : AI Engineer 
location    : São Paulo, SP
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=2000&pause=1000&color=00FF41&background=000000&center=false&vCenter=true&repeat=false&width=800&height=44&lines=%3E+cat+stack.json_" alt="stack" />

| Área | Tecnologias |
|---|---|
| **Linguagem** | Python (POO, estruturas de dados, tratamento de erros, JSON) |
| **IA** | Loop ReAct, function calling, guardrails, engenharia de contexto, OpenAI SDK, OpenRouter |
| **Web e dados** | requests, BeautifulSoup, integração de APIs REST |
| **Ferramentas** | Git, GitHub, VS Code, Google Colab, Linux |

**Em estudo:** avaliação de agentes · RAG · Docker · SQL · conceitos de nuvem

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=2000&pause=1000&color=00FF41&background=000000&center=false&vCenter=true&repeat=false&width=800&height=44&lines=%3E+.%2Ffeatured_project_" alt="projeto" />

### 🤖 [Autonomous Web Maze Agent](https://github.com/wcarolf/autonomous-web-maze-agent)

Agente autônomo que navega por páginas web e resolve um labirinto online, decidindo a cada passo qual link acessar. Construído sem frameworks de agentes, sobre o SDK da OpenAI conectado ao OpenRouter. Baseado no desafio do laboratório de agentes de Ed Donner.

```text
[TAREFA] ──▶ [LLM RACIOCINA]
                  │
        ┌─────────┴─────────┐
        ▼                   ▼
 (precisa de página)   (achou a saída)
        │                   │
        ▼                   ▼
 [tool call: url]      [resposta final]
        │
        ▼
 [read_web_page()]
  ├─ guardrail de domínio
  ├─ requests + BeautifulSoup
  └─ try/except -> erro vira feedback
        │
        ▼
 [resultado volta ao LLM] ──▶ (próximo passo, máx. 25)
```

| Conceito | Como foi aplicado |
|---|---|
| **Loop ReAct** | Alterna raciocínio do modelo e observação do ambiente até a condição de parada |
| **Function calling** | Schema JSON descreve a ferramenta de leitura web e o modelo decide quando usá-la |
| **Guardrails** | Validação de URL para restringir o agente ao domínio do labirinto |
| **Tolerância a falhas** | Erros voltam ao modelo como feedback para ele corrigir a rota |
| **Controle de execução** | Limite de passos contra loops infinitos e gasto excessivo de API |

[![Repositório](https://img.shields.io/badge/VER_REPOSIT%C3%93RIO-000000?style=for-the-badge&logo=github&logoColor=00FF41)](https://github.com/wcarolf/autonomous-web-maze-agent)
[![Open In Colab](https://img.shields.io/badge/ABRIR_NO_COLAB-000000?style=for-the-badge&logo=googlecolab&logoColor=00E5FF)](https://colab.research.google.com/drive/1oo4GJg_RPw-NOrLufhBOiuy3SixUi1Eh?usp=sharing)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=2000&pause=1000&color=00FF41&background=000000&center=false&vCenter=true&repeat=false&width=800&height=44&lines=%3E+cat+roadmap.md_" alt="roadmap" />

- [x] Agente ReAct com function calling e guardrails
- [ ] Avaliação: múltiplas execuções com taxa de sucesso, passos e custo
- [ ] Agente de pesquisa com busca na web e saída estruturada
- [ ] RAG: agente que responde com base em documentos
- [ ] Containerização com Docker

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=2000&pause=1000&color=00FF41&background=000000&center=false&vCenter=true&repeat=false&width=800&height=44&lines=%3E+.%2Fcontact_" alt="contato" />

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-000000?style=for-the-badge&logo=linkedin&logoColor=00FF41)](https://www.linkedin.com/in/anacarolinyfmachado)
[![GitHub](https://img.shields.io/badge/GITHUB-000000?style=for-the-badge&logo=github&logoColor=00FF41)](https://github.com/wcarolf)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF41,50:003B00,100:000000&height=100&section=footer" alt="footer" />

</div>
