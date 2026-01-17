# Auto Apply on Google Jobs – n8n Automation

This workflow automates job discovery, shortlisting, and AI-driven job applications using Google Jobs and LLMs.

---

## 🔍 Problem It Solves
Manually searching jobs, tracking applications, and writing customized resumes and cover letters is repetitive and time-consuming.

This automation converts the entire process into a guided, AI-assisted workflow.

---

## ⚙️ How It Works

1. User submits a form with:
   - Job title
   - Job location (country-wise)

2. **SerpAPI** searches Google Jobs and fetches openings.

3. Results are stored in **Google Sheets**.

4. For each job:
   - A **Telegram message** is sent asking whether to apply or ignore.

5. If user chooses to apply:
   - Sheet is updated
   - LLM generates:
     - Customized resume
     - Personalized cover letter

6. Generated document links and job platform URLs are stored in Sheets.

---

## 🧠 AI Capabilities
- Job-specific resume customization
- Context-aware cover letter generation
- Decision-based branching

---

## 🛠 Integrations Used
- n8n Forms
- SerpAPI (Google Jobs)
- Telegram Bot
- Google Sheets
- OpenAI / LLM
- HTTP APIs

---

## 📸 Screenshots
See `screenshots/` for workflow and output previews.

---

## ✅ Use Cases
- Job seekers
- Career automation tools
- AI-powered recruitment platforms
