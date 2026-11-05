<div align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1E3F,100:1E90FF&height=170&section=header&text=Abdulaziz%20Yusupaliev&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=AI%20%2F%20ML%20Engineer%20%C2%B7%20Tashkent&descSize=16&descAlignY=58&animation=fadeIn"
    width="100%"
    alt="Abdulaziz Yusupaliev, AI/ML Engineer"
  />
</div>

<div align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=1E90FF&center=true&vCenter=true&width=600&lines=Speech+recognition+for+Karakalpak;RAG+and+multi-agent+LLM+apps;Fine-tuning+with+LoRA+and+QLoRA;AIMO+medalist+%F0%9F%8F%85"
    alt="Speech recognition, RAG and multi-agent LLM apps, fine-tuning with LoRA and QLoRA, AIMO medalist"
  />
</div>

<div align="center">
  <a href="https://github.com/vvadr"><img src="https://img.shields.io/github/followers/vvadr?style=social" alt="GitHub followers" /></a>
  <img src="https://komarev.com/ghpvc/?username=vvadr&color=1E90FF&style=flat-square&label=Profile+Views" alt="Profile views" />
</div>

## 👋 About

I train ML models and build the apps around them: speech recognition for Karakalpak, document Q&A with LLM agents, and fine-tuned small open models. I write the React/Next.js frontends myself.

- 🎙️ Karakalpak speech-to-text: **18.6% WER** on news speech
- 📄 LLM apps that cite their sources and say so when the answer isn't there
- 🏅 National and international **AIMO medalist**
- 📍 Tashkent, Uzbekistan · 📫 [abdulazizyusupaliev009@gmail.com](mailto:abdulazizyusupaliev009@gmail.com)

## 🧠 AI / ML Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,pytorch,sklearn,fastapi,docker,postgres,git,github&perline=8" alt="Python, PyTorch, scikit-learn, FastAPI, Docker, PostgreSQL, Git, GitHub" />
</div>

<br />

| Area | Tools |
| --- | --- |
| **Speech & deep learning** | PyTorch, Hugging Face Transformers, PEFT (LoRA / QLoRA), KenLM |
| **LLM apps** | LangGraph, Qdrant, Gemini, RAGAS, Langfuse |
| **Classical ML** | scikit-learn, pandas, NumPy, Matplotlib, Seaborn |
| **Serving** | FastAPI, Docker, PostgreSQL, Gradio |

## 🚀 Featured Projects

### 🎙️ [Karakalpak Speech-to-Text](https://github.com/vvadr/karakalpak-stt-model)

Speech recognition for Karakalpak, a low-resource Turkic language. Fine-tuned `wav2vec2-xls-r-300m` with LoRA on a ~97-hour dataset (22k recordings), plus a 4-gram KenLM for beam-search decoding.

| Test set | Greedy WER | Beam + KenLM WER |
| --- | --- | --- |
| News speech (1,950 clips) | 38.4% | **18.6%** |
| Literary (523 clips) | 22.3% | **18.3%** |

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LoRA](https://img.shields.io/badge/PEFT-LoRA-1E90FF?style=flat-square)
![KenLM](https://img.shields.io/badge/KenLM-4--gram-555555?style=flat-square)

### 🤖 [Multi-Agent AI Analyst](https://github.com/vvadr/Multi-Agent-AI-Analyst)

Upload documents and ask questions. A supervisor agent sends each question to retrieval, web research or analytics agents and returns an answer with citations. **[Live demo](https://multi-agent-ai-analyst-psi.vercel.app/)**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C1C1C?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### 📄 [LoanSource AI](https://github.com/vvadr/LoanSource-AI)

Q&A over public loan-term PDFs. Qwen2.5-1.5B-Instruct fine-tuned with QLoRA on a free Colab T4, TF-IDF page retrieval, answers link to source pages, and it declines financial or legal advice.

![Qwen](https://img.shields.io/badge/Qwen2.5-1.5B-615CED?style=flat-square)
![QLoRA](https://img.shields.io/badge/QLoRA-fine--tuning-1E90FF?style=flat-square)
![Colab](https://img.shields.io/badge/Colab-T4-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square)

<details>
  <summary><strong>Smaller ML projects</strong></summary>

<br />

| Project | What it does | Stack |
| --- | --- | --- |
| [**yelp-restaurant-rating-prep**](https://github.com/vvadr/yelp-restaurant-rating-prep) | Turns the Yelp Open Dataset into a clean 22-column Philadelphia restaurant dataset for star-rating prediction | Python, pandas, Parquet |
| [**Flower_ML_model**](https://github.com/vvadr/Flower_ML_model) | Iris species classifier with a random forest | scikit-learn, pandas |
| [**Sport-team-odds**](https://github.com/vvadr/Sport-team-odds) | Exploratory data analysis notebook | pandas, Matplotlib |

</details>

## 🌐 Frontend

I build the interfaces for my ML projects too.

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind" alt="TypeScript, React, Next.js, Tailwind CSS" />
</div>

<details>
  <summary><strong>Web projects</strong></summary>

<br />

| Project | What it does | Stack |
| --- | --- | --- |
| [**udevs-app**](https://github.com/vvadr/udevs-app) | Twitter-style social app | React, TypeScript |
| [**udevs-app-backend**](https://github.com/vvadr/udevs-app-strapi-backend) | Backend for udevs-app | Strapi, TypeScript |
| [**weather-app**](https://github.com/vvadr/weather-app-react) | Weather app using a public API | React |

</details>

## 📊 GitHub Stats

<div align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=vvadr&theme=tokyonight&show_icons=true&hide_border=true&title_color=1E90FF&icon_color=1E90FF"
    height="165"
    alt="GitHub stats"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=vvadr&theme=tokyonight&hide_border=true&layout=compact&langs_count=6&title_color=1E90FF"
    height="165"
    alt="Most-used languages"
  />
</div>

<div align="center">
  <img
    src="https://streak-stats.demolab.com/?user=vvadr&theme=tokyonight&hide_border=true&ring=1E90FF&fire=1E90FF&currStreakLabel=1E90FF"
    alt="GitHub contribution streak"
  />
</div>

## 📫 Connect

<div align="center">
  <a href="mailto:abdulazizyusupaliev009@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://www.linkedin.com/in/abdulaziz-yusupaliev-521166377/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://t.me/d_vaderrr"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://instagram.com/d_vaderrr"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="https://abdulazizyusupaliev.vercel.app"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
</div>

<div align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:1E90FF,100:0B1E3F&height=90&section=footer"
    width="100%"
    alt=""
  />
</div>
