# 🌐 SnapClass — Landing Page

The official landing page for **SnapClass**, an AI-powered classroom attendance system. This site introduces visitors to SnapClass, walks through how the app works for both teachers and students, and links directly to the live application.

## 🔗 Quick Links

| Link | Purpose |
|---|---|
| 🌍 **[Visit Landing Page](https://snap-class-making-attendance-landin.vercel.app/)** | Learn about SnapClass and how to use it |
| 🚀 **[Launch the App](https://snapclass-attendance-mains.streamlit.app/)** | Go straight to the deployed app and start using it |
| 💻 **[Main App Repository](https://github.com/Abhishek-Maurya-D/SnapClass-Making_Attendance_faster_using_AI)** | Source code for the SnapClass application itself |

---

## ✨ What's on This Page

- **Hero section** introducing SnapClass with a direct call-to-action to start using the AI attendance app
- **Features overview** — AI Face Analysis, Sequential Voice ID, and QR-Driven Roster enrollment
- **The Teacher's Journey** — a step-by-step visual walkthrough: secure login → dashboard → course creation → FaceID attendance → Voice ID attendance → attendance records
- **The Student's Journey** — instant enrollment via QR/link → biometric (face + voice) registration → personal attendance dashboard
- **Tech stack showcase** highlighting the tools powering SnapClass (Streamlit, Flask, dlib, Resemblyzer, Librosa, Supabase)
- **Call-to-action footer** linking back to the live app

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Backend | [Flask](https://flask.palletsprojects.com/) |
| Templating | Jinja2 (`templates/index.html`) |
| Styling | Custom CSS (`static/css/style.css`) |
| Interactivity | Vanilla JavaScript (`static/js/script.js`) |
| Deployment | [Vercel](https://vercel.com/) |
| Production Server | Gunicorn |

---

## 📂 Project Structure

```
SnapClass-Making-Attendance-landing_page/
├── app.py                  # Flask app — serves the landing page
├── requirements.txt        # Python dependencies (flask, gunicorn)
├── templates/
│   └── index.html          # Landing page markup
└── static/
    ├── css/
    │   └── style.css       # Page styling
    ├── js/
    │   └── script.js       # Page interactivity
    └── img/
        ├── logo.png
        ├── app_logo.png
        └── demo/            # Screenshots used in the teacher/student journey sections
```

---

## 🚀 Getting Started (Run Locally)

### Prerequisites
- Python 3.8+

### 1. Clone the repository
```bash
git clone https://github.com/Abhishek-Maurya-D/SnapClass-Making-Attendance-landing_page.git
cd SnapClass-Making-Attendance-landing_page
```

### 2. Create a virtual environment
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux / macOS
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the app
```bash
python app.py
```
The site will be available at `http://localhost:5002`.

---

## 🖥️ Live Site

View the deployed landing page here 👉 **[snap-class-making-attendance-landin.vercel.app](https://snap-class-making-attendance-landin.vercel.app/)**

Ready to try SnapClass itself? 👉 **[snapclass-attendance-mains.streamlit.app](https://snapclass-attendance-mains.streamlit.app/)**

---

## 👤 Author

**Abhishek Maurya**
[GitHub](https://github.com/Abhishek-Maurya-D) · [Repository](https://github.com/Abhishek-Maurya-D/SnapClass-Making-Attendance-landing_page)

---

## 📄 License

No license file is currently included in this repository. Add one (e.g., MIT) if you intend for others to reuse this code.
