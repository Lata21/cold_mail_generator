# 📧 Cold Mail Generator

**Cold Mail Generator** is an AI-powered tool built using **Groq**, **LangChain**, and **Streamlit**.  
It enables service-based companies to generate personalized cold emails by analyzing job listings directly from a company’s career page.

Users simply provide the **URL of a career page**, and the app:
- Extracts job descriptions using web scraping and LLMs.
- Analyzes skills and requirements.
- Matches the most relevant portfolio links from a **vector database (ChromaDB)**.
- Generates a **customized cold email** suitable for outreach.

---
### Workflow:
1. User enters a company’s **career page URL**.
2. The app extracts job listings using **LangChain’s WebBaseLoader**.
3. Each job’s skill requirements are matched with **portfolio data stored in ChromaDB**.
4. A custom cold email is generated using **Groq LLM** models.
5. The result is displayed in the Streamlit frontend.

---

## ⚙️ Set-up Instructions

### 1. Clone the repository
```bash
git clone https://github.com/Lata21/cold_mail_generator.git
cd cold_mail_generator
