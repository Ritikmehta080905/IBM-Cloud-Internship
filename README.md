# IBM Cloud Internship: AI Research Assistant 🚀

![IBM watsonx](https://img.shields.io/badge/IBM-watsonx-0062FF?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-Powered-4CC417?style=for-the-badge)

## 📌 What This Project Does
An **AI research assistant** that:
- Answers academic questions using IBM Granite-3.3B LLM
- Retrieves papers with Milvus vector DB
- Provides structured summaries (key findings, pros/cons)

## 🧩 Repository Contents
| File | Purpose |
|------|---------|
| [`Research_Agent_AI_*.ipynb`](Research_Agent_AI_Ritik_Mehta.ipynb) | Main Jupyter Notebook |
| [`AI_instruction_prompt.txt`](AI_instruction_prompt_and_problem_statement.txt) | LLM prompts & problem statement |
| [`certificates/`](certificates/) | IBM Cloud certifications |
| [`Project_IBM_Internship.pdf`](Project_IBM_Internship.pdf) | Project documentation |

## 🛠️ Tech Stack
```mermaid
graph TD
    A[User Interface] --> B(Gradio)
    B --> C{IBM Granite-3.3B}
    C --> D[Milvus Vector DB]
    D --> E[Research Papers]
