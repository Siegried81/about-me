# Hi, I'm Siegried

**Data & AI engineer** · Brussels

I spent more than fifteen years in banking, at Beobank and then Deutsche Bank. The part I liked best was the data: making sure a figure was right before someone made a decision on it. In 2023 I moved into data, and this year into AI engineering at BeCode.

Why AI? I'd rather understand it than be replaced by it. And I want to help companies use it well, so their people save time on the boring parts and spend it where it counts (on decisions and so on). That only works if the tool is right, so I test what I build before I trust it. My assistants cite their source or say they don't know.

- BeCode AI & Data Science bootcamp, GenAI track, until December 2026. Before that, commercial engineer from Solvay.
- Looking for a permanent AI Engineer or Data Engineer role in or around Brussels, starting January 2027.

---

## Projects

Every repo has its own tests and CI. The detailed results are in each README, and they move as I keep working on them.

| Project | What it does |
|---|---|
| [**ing-usecase**](https://github.com/Siegried81/ing-usecase) | Client project for ING's Customer AI team. I led a team of three for two weeks. We took the public campaign pages of 14 Belgian banks and turned them into one comparison, with one validated LLM call per page and a schema check on every answer. No performance data exists, so we compare what banks say, never what works better. |
| [**Orange Business**](https://github.com/Siegried81/Orange_Business_use_case) | Client project: an innovation radar that scores opportunity spaces from public market signals (news, research, regulation, tenders). Spaces without real evidence are flagged, not scored. Runs daily with Airflow. |
| [**grounded-rag**](https://github.com/Siegried81/grounded-rag) | Ask the EU AI Act or Apple's 10-K a question. The answer cites the exact passage or refuses. Keyword and vector search combined, and every citation and figure checked after the model answers. Red-team suite, optional Qdrant, Docker and Kubernetes. |
| [**route-or-roam**](https://github.com/Siegried81/route-or-roam) | The same Q&A built twice in LangGraph: once as a fixed workflow, once as an agent with tools, a token budget and human approval. Same questions, same model. The agent scores a bit higher but the gap isn't significant, so I don't claim a winner. |
| [**railpulse-genai**](https://github.com/Siegried81/railpulse-genai) | Ask Belgian train delay data a question in plain English. The model writes the SQL, but it only gets a read-only connection and a list of allowed tables, and every number in the answer has to exist in the database. FastAPI with an API key and rate limit. |
| [**flood-to-policy**](https://github.com/Siegried81/flood-to-policy) | The July 2021 floods against the EU flood map. In Eschweiler, 91% of the residents the water reached lived outside the official flood zone. GeoPandas pipeline, React tool, Power BI report and a policy answer with sources. |
| [**dreamjob-v2**](https://github.com/Siegried81/dreamjob-v2) | My job-search platform. It finds openings and drafts the CV, the letter and the first mail, but nothing goes out before I approve it, and a check blocks any claim my profile can't back up. React and FastAPI. |
| [**railpulse-delays**](https://github.com/Siegried81/railpulse-delays) | Why is an SNCB train late? Brussels looks worse at first (10.1% late against 7.4% elsewhere), but the gap goes away once you control for the hour and the train type. |
| [**immo-eliza-deployment**](https://github.com/Siegried81/immo-eliza-deployment) | Belgian house prices with XGBoost, a separate model for luxury homes, and a price range instead of a single number. My first test set had training rows in it. Once I fixed that the error went up, and that's the figure I report. |

<details>
<summary>More</summary>

- [portfolio-forecasting](https://github.com/Siegried81/portfolio-forecasting): three portfolios and six forecasting models, from a random walk to an LSTM, judged on a period no model saw. FastAPI, MLflow.
- [railpulse-challenge-azure](https://github.com/Siegried81/railpulse-challenge-azure) · [railpulse_power-bi](https://github.com/Siegried81/railpulse_power-bi) · [railpulse_sql_analysis](https://github.com/Siegried81/railpulse_sql_analysis): the Azure ingestion, the Power BI report and the SQL study behind RailPulse.
- [immo-eliza-scraping](https://github.com/Siegried81/immo-eliza-scraping) · [immoeliza_ml](https://github.com/Siegried81/immoeliza_ml): the scraper and the model training behind Immo Eliza.

</details>

---

## Stack

Only what my repos actually use.

**GenAI**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langgraph&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-BM25_%2B_dense_%2B_RRF_%2B_MMR-5B4B8A?style=flat)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=flat)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6467F2?style=flat)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat&logo=anthropic&logoColor=white)

**ML & statistics**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat)
![statsmodels](https://img.shields.io/badge/statsmodels-4051B5?style=flat)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)

**Data engineering & BI**
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_Functions_%2B_SQL-0078D4?style=flat)
![GeoPandas](https://img.shields.io/badge/GeoPandas_%2B_rasterio-139C5A?style=flat)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)

**Ship & test**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face_Spaces-FFD21E?style=flat&logo=huggingface&logoColor=black)

A few honest notes: the Kubernetes manifests are for learning, I don't run a cluster in production. The Azure side of RailPulse is offline since my student credits ran out. I'm currently preparing for the AWS Certified Cloud Practitioner (CLF-C02) and Microsoft Certified: Power Platform Fundamentals (PL-900) certifications.

---

## How I work

- **Check the data before the model.** A wrong key once dropped 87% of my rows and every count still looked fine. Now a test locks the key before I collect anything.
- **Don't trust a prompt to enforce a rule.** If the model mustn't touch a table, it gets a connection that can't.
- **Try the simple version first.** An agent has to beat a plain workflow on real numbers. When it doesn't, I say so.
- **Say what's missing.** If I didn't capture a field at the start, it stays empty. I don't fill it with a guess.

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-siegried--camus-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siegried-camus/)
[![Email](https://img.shields.io/badge/csiegried@yahoo.fr-6001D2?style=flat&logo=yahoo&logoColor=white)](mailto:csiegried@yahoo.fr)
[![Docker Hub](https://img.shields.io/badge/Docker_Hub-siegried-2496ED?style=flat&logo=docker&logoColor=white)](https://hub.docker.com/u/siegried)
