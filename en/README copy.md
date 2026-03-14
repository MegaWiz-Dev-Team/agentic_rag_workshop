# 🤖 Agentic RAG Workshop: From Zero to Hero

> RAG + AI Agent Google ADK & Gemini — 

---

## 📋 

- [](#-)
- [](#-)
- [](#-)
- [](#-)
- [](#-)
- [](#-)
- [](#-)
- [Tech Stack](#-tech-stack)

---

## 🎯 

Workshop 3 **Retrieval-Augmented Generation (RAG)** **AI Agent** end-to-end

```
Day 1: Data Engineering Day 2: Agent Building Day 3: Evaluation
───────────────────── ───────────────────── ─────────────────
Raw → Chunk → Embed → Agent + Tool → RAGAS metrics
VectorDB → Retrieve RAG Agent → LLM-as-Judge
 Multi-Agent → A/B Experiment
 Agentic RAG Capstone ⭐
```

**:**
- 🇹🇭 (PyThaiNLP, multilingual-e5-large)
- 🛡️ Anti-cheat homework ( .)
- 🤖 Gemini 2.5 Pro
- 💡 「」blocks section 
- 🧪 Hints + starter code

---

## 📁 

```
agentic_rag_workshop/
├── README.md
├── LICENSE
├── CHANGELOG.md # 📋 
├── final_grading.ipynb # 🏆 Final (3 × 3 )
├── .agent/
│ └── workflows/
│ └── git-workflow.md # 🔀 Git workflow rule (Issue → PR)
├── day1/
│ ├── day1_data_engineering.ipynb # 📖 (87 cells)
│ ├── day1_homework.ipynb # 📝 (18 cells)
│ └── day1_grading.ipynb # ✅ (11 cells)
├── day2/
│ ├── day2_building_agents.ipynb # 📖 (62 cells)
│ ├── day2_homework.ipynb # 📝 (22 cells)
│ └── day2_grading.ipynb # ✅ (11 cells)
└── day3/
 ├── day3_evaluation.ipynb # 📖 (41 cells)
 ├── day3_homework.ipynb # 📝 (18 cells)
 └── day3_grading.ipynb # ✅ (11 cells)
```

---

## 📚 

### Day 1: Data Engineering Pipeline

| Section | |
| ------- | -------------------------------------------------- |
| 1.1 | Deduplication — Hash |
| 1.2 | Chunking — (Fixed / Recursive / Semantic) |
| 1.3 | Gemini Multimodal — PDF AI |
| 1.4 | Thai Tokenization — |
| 1.5 | Embedding — Vector |
| 1.6 | Hybrid Search — Dense + Sparse search |
| 1.7 | Qdrant — Vector Database |
| 1.8 | Indexing — VectorDB |
| 1.9 | Retrieval — |

** (10 ):** pipeline dedup → chunk → embed → search

---

### Day 2: Building Agents with Google ADK

| Section | |
| ------- | -------------------------------------------------------- |
| 2.1 | Agent — Agent + Instruction |
| 2.2 | Tools — Function Tools + Gemini API params |
| 2.3 | RAG Agent — Agent VectorDB |
| 2.4 | Multi-Agent — Sequential / Parallel / Loop / LLM Routing |
| 2.5 | Session Memory — |
| 2.6 | Agentic RAG — Study Assistant |

** (10 ):** Agent + Custom Tool + RAG Agent + Workflow Agent

---

### Day 3: Evaluation & Optimization

| Section | |
| ------- | --------------------------------------------- |
| 3.1 | RAGAS — RAG (4 metrics) |
| 3.2 | Auto Eval Dataset — Q&A Gemini |
| 3.3 | Agent Testing — Tool Selection + LLM-as-Judge |
| 3.4 | A/B Experiment — configs |
| 3.5 | Prompt Engineering — Before vs After |
| 3.6 | Capstone Project ⭐ — 3 |

** (10 ):** RAG + + + Agent + Test

---

## 🔧 

### 
1. **Gemini API Key** — [Google AI Studio](https://aistudio.google.com/apikey)
2. notebooks Google Colab
3. (PDF) (Day 1)
4. ** Google Form** ( [](#-))
5. 📊 **[Slide ](https://docs.google.com/presentation/d/1298peeshWiNPr2JMUTdu1y2A-nuWpGo0N62i25_lvnc/edit)** — Google Slides 

### 
1. **Google Account** ( Colab)
2. **Gemini API Key** — Colab Secrets `GOOGLE_API_KEY`

---

## 🎓 

### Section

```
1. (Markdown cell)
2. (Code cell — Run )
3. 💡 — 
4. 🧪 — 5-10 
```

### 

| Day | | |
| ----- | :------: | ------------------------------ |
| Day 1 | ~4-5 . | 3 . + 1-2 . |
| Day 2 | ~4-5 . | 3 . + 1-2 . |
| Day 3 | ~3-4 . | 2 . + Capstone 1-2 . |

### Tips

- Run `%%time` cells pip install + model download 
- set Colab Secrets 
- Section `await` run Colab ( local Python)
- **💡 ** blocks — takeaway section

---

## 📤 

### Flow

```
 
────────── ──────────
1. Colab 1. Google Form (1 )
2. Run ✅ 2. Google Sheets (auto)
3. File → Download → .ipynb 3. .ipynb Drive
4. Google Form 4. path grading notebook
5. + 5. Run → append CSV
6. ✅ 6. 
```

### Google Form?

| | |
| ----------------------- | ----------------------------------- |
| ** GitHub** | Download .ipynb → Upload Form |
| **1 link ** | link LINE/Classroom |
| **Auto Spreadsheet** | Google Sheets |
| ** Drive** | , |

### 📝 Google Form — 

 Google Form 1 1 Day :

#### Form: " Day X — Agentic RAG Workshop"

| # | Field | | Required | |
| --- | ------------------------------- | ----------- | :------: | --------------------------------------- |
| 1 | **-** | Short text | ✅ | Validation: ≥ 4 |
| 2 | **** | Short text | ✅ | Validation: regex `^\d{10}$` (10 ) |
| 3 | **** | Short text | ✅ | Validation: regex `^0\d{8,9}$` |
| 4 | **LINE ID** | Short text | ❌ | |
| 5 | **Email** | Short text | ✅ | auto-collect Google Account |
| 6 | ** (.ipynb)** | File upload | ✅ | workshop , Max: 20 MB |
| 7 | ** (.ipynb)** | File upload | ✅ | homework, Max: 10 MB |
| 8 | **** | Paragraph | ❌ | |

#### Google Form

| | |
| ----------------------- | -------------------------------------------------- |
| Collect emails | ✅ Verified |
| Limit to 1 response | ✅ () |
| File upload destination | folder Drive: `Workshop_Submissions/DayX/` |
| Confirmation message | `✅ ! 1 ` |

#### 🔗 Google Form Links

| Day | Link |
| ----- | -------------------------------------------------------------------------------- |
| Day 1 | [ Day 1: Data Engineering](https://forms.gle/R7EXvPvUfZ286CVh8) |
| Day 2 | [ Day 2: Building Agents](https://forms.gle/xTQ5eVNKa4fcQVKb8) |
| Day 3 | [ Day 3: Evaluation & Optimization](https://forms.gle/yLVHh4YVVt3miogm8) |

---

## ✅ 

### 

```
1. Google Sheets (linked Form) → .ipynb Drive
2. Colab ( Google Drive → mount)
3. dayX_grading.ipynb Colab
4. Run "Setup" ( + API Key)
5. Run "" 
6. path .ipynb → Run 
7. append CSV/JSON 
8. path → 
```

### 

| Feature | |
| ------------------- | ----------------------------------------- |
| **AI Grading** | Gemini 2.5 Pro + feedback |
| **Anti-cheat** | . |
| **Duplicate check** | + overwrite |
| **Export** | CSV + JSON |

### ( Day = 10 )

<details>
<summary><strong>Day 1: Data Engineering Pipeline</strong></summary>

| | |
| ------------------ | :---: |
| Duplicates | 2 |
| Chunking | 3 |
| Embedding + Search | 3 |
| | 2 |

</details>

<details>
<summary><strong>Day 2: Building Agents</strong></summary>

| | |
| ------------------- | :---: |
| Agent + Custom Tool | 3 |
| RAG Agent | 3 |
| Workflow Agent | 2 |
| | 2 |

</details>

<details>
<summary><strong>Day 3: Evaluation & Optimization</strong></summary>

| | |
| ---------------------- | :---: |
| RAG Pipeline | 3 |
| (LLM-as-Judge) | 2.5 |
| (Before/After) | 2.5 |
| Agent + Test | 2 |

</details>

### output

- `dayX_scores.csv` — (import Excel/Google Sheets )
- `dayX_scores.json` — feedback 

---

## 🏆 (3 )

 **3 ** 10 × 3 = **90 **

### 🤝 Responsibility () — 10 /Day

| | | |
| ------------------ | :---: | ---------------------------- |
| | 3 | timestamp Google Form |
| | 2 | , , |
| Day | 3 | Day 1 + 2 + 3 |
| Run ✅ | 2 | output validation cell |

### 💪 Determination () — 10 /Day

| | | |
| --------------------- | :---: | ---------------------------- |
| | 3 | code cells output |
| parameter | 3 | ≥ 2 |
| / | 2 | comment |
| | 2 | debugging / error handling |

### 💻 Technical () — 10 /Day

| | | |
| ---------------------- | :---: | ----------------------------- |
| Code | 3 | error/traceback |
| | 3 | (anti-cheat) |
| code | 2 | , comment |
| copy / AI | 2 | AI suspected check |

### 📊 

| | Day 1 | Day 2 | Day 3 | |
| ---------------- | :-----: | :-----: | :-----: | :-----: |
| 🤝 Responsibility | /10 | /10 | /10 | /30 |
| 💪 Determination | /10 | /10 | /10 | /30 |
| 💻 Technical | /10 | /10 | /10 | /30 |
| ** Day** | **/30** | **/30** | **/30** | **/90** |

> `final_grading.ipynb` 3 Day → export CSV 

---

## 🐛 Known Issues & Fixes (Colab)

 run Google Colab:

| Issue | | | Notebook |
| :--------------------: | --------------------------------------------- | ---------------------------------- | -------- |
| [#19](../../issues/19) | Thai font matplotlib □□□ | `fonts-thai-tlwg` + `addfont()` | Day 1 |
| [#21](../../issues/21) | ASCII diagram Thai char width | markdown table | Day 1, 2 |
| [#26](../../issues/26) | `InMemoryRunner` `session_service` param | `runner.session_service` | Day 2, 3 |
| [#17](../../issues/17) | `resp.text.strip()` → NoneType error | None check | Day 2, 3 |
| [#30](../../issues/30) | Similarity matrix text | matplotlib heatmap | Day 1 |

> ⚠️ ****: Notebooks **Google Colab** — run local path dependencies 

## 🛠️ Tech Stack

| | |
| ------------------------------------------------------------------------------ | ------------------------- |
| [Google ADK](https://google.github.io/adk-docs/) | AI Agent |
| [Gemini API](https://ai.google.dev/) | LLM (2.5 Flash / 2.5 Pro) |
| [Qdrant](https://qdrant.tech/) | Vector Database |
| [multilingual-e5-large](https://huggingface.co/intfloat/multilingual-e5-large) | Text Embedding () |
| [RAGAS](https://ragas.io/) | RAG Evaluation Framework |
| [PyThaiNLP](https://pythainlp.github.io/) | Thai NLP Toolkit |
| [Google Colab](https://colab.research.google.com/) | Runtime Environment |

---

## 👤 

** (Paripol Toopiroh)**
Chief Executive Officer — [Mega Wiz](https://megawiz.co)
🎓 1 — (KMITL)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paripol-toopiroh-61273a19b/)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=flat&logo=facebook&logoColor=white)](https://www.facebook.com/paripol.toopiroh)

### 🛠️ Tools 

| Tool | |
| ------------ | -------------------------------------- |
| **IDE** | [Antigravity](https://antigravity.dev) |
| **AI Model** | Claude Opus 4.6 (Thinking) |

---

## 🤝 Contributing

 feedback contribution !

- 💬 **** → [Issue](../../issues) 
- 🐛 ** Bug** → [Issue](../../issues) 
- 🔀 **Pull Request** → Fork → → PR 

> contribution license (CC BY-NC-SA 4.0)

---

## 📄 License

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

 [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/)

- ✅ 
- ✅ 
- ✅ 
- ❌ 

 [LICENSE](LICENSE)

---

> _"The best way to learn AI is to build with AI."_
