## 🎓 ThesisLink

**Automate your professor outreach, personalize your thesis journey.**

---

## 📌 What is ThesisLink?

**ThesisLink** is an open-source, personal CRM and automation tool built for ambitious students who want to streamline how they find and reach out to academic supervisors for thesis-based MSc or PhD programs.

As a First-Class Computer Science graduate deeply focused on AI and automation, I (Nsikak Ebong) built ThesisLink to solve my own pain point: writing, sending, tracking, and personalizing countless supervisor emails, SOPs, and attachments — all while making each outreach professional and impactful.

---

## ✅ Key Features

- **📚 Supervisor CRM**  
  Add, edit, and manage a clean database of target professors, with fields for names, emails, universities, research interests, custom notes, and status tracking.

- **📝 Dynamic Email & SOP Templates**  
  Use smart merge fields like `[ProfName]`, `[University]`, `[ResearchTopic]` to personalize each email and SOP automatically — no more endless copy-paste.

- **📎 Document Uploader**  
  Upload, organize, and attach your CV, SOP, transcripts, and any supporting files securely.

- **📬 Automated Sending & Follow-Ups**  
  Connect with Gmail API, SMTP, or SendGrid to send personalized emails in smart batches. Schedule polite follow-ups if no reply after X days.

- **📊 Dashboard & Logs**  
  Visualize your outreach pipeline: professors contacted, replies received, pending actions — all in a clean, modern, mobile-friendly interface.

- **✨ Beautiful & Minimalist UI**  
  Built with React.js and TailwindCSS for a calm, productivity-focused experience that works seamlessly on desktop or mobile.

---

## ⚙️ Tech Stack

- **Frontend:** React.js + TailwindCSS  
- **Backend:** Python FastAPI or Django REST 
- **Database:** SQLite or PostgreSQL  
- **Email Integration:** Gmail API (OAuth2), SendGrid, or secure SMTP  
- **Scheduler:** Celery or custom cron jobs for follow-ups  
- **Hosting:** Deploy locally or on cloud (e.g., AWS, Vercel, or your own VPS)

---

## 🚀 Getting Started

1️⃣ **Clone the repo**

```bash
git clone https://github.com/Nsiikak/ThesisLink.git
cd ThesisLink
````

2️⃣ **Install dependencies**

```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
python -m venv env
source env/bin/activate
pip install -r requirements.txt
```

3️⃣ **Set up environment variables**

* Create a `.env` file in both `frontend/` and `backend/` with:

  * Gmail API keys or SMTP credentials
  * Backend base URL for Axios requests
  * Frontend URL for CORS

4️⃣ **Run the app**

```bash
# Backend
cd backend
uvicorn main:app --reload

# Frontend
cd ../frontend
npm run dev
```

---

## 📂 Project Structure

```
ThesisLink/
 ├── frontend/      # React + TailwindCSS
 ├── backend/       # FastAPI 
 ├── .env           # Environment configs
 ├── README.md
 ├── LICENSE
```

---

## 🎨 Design Principles

* Clean, minimalist, academic-friendly color palette (soft blues, whites, light greys)
* Responsive and accessible
* Easy forms, clear input validation, drag-and-drop document uploads
* Preview screens for final emails before sending
* Notifications and status indicators for sending, errors, and replies

---

## 🔒 Security

* OAuth2 for Gmail API to send emails safely
* No storing of passwords in plain text
* PDF attachments handled securely and deleted if needed
* Minimal permissions — only sends what you approve

---

## 📜 License

This project is licensed under the MIT License — free for anyone to use, fork, adapt, and improve.
See [`LICENSE`](./LICENSE).

---

## 🤝 Contributing

Pull requests, improvements, and ideas are welcome!
Feel free to fork the repo, open an issue, or submit a pull request.

---

## 🧩 Roadmap

✅ MVP: CRM, email template merge, file uploads, sending
✅ Logs & follow-ups
✅ Responsive design
🔜 OAuth login for multi-user support
🔜 AI-powered paper summary snippet (auto-inserts relevant lines from professor’s latest work)
🔜 Automatic status syncing from Gmail replies

---

## 📬 Contact

**Nsikak Ebong**
📧 [nsikakebong98@gmail.com](mailto:nsikakebong98@gmail.com)
🌐 [nsikakebong.com](https://nsikakebong.com)
🔗 [LinkedIn](https://www.linkedin.com/in/nsikak-abasi-ebong-78a0b1264)

---

**Let’s make finding the perfect supervisor faster, smarter, and stress-free.**
Happy automating! 🚀



