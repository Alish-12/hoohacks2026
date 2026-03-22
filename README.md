# SnapshotChef 📸🍳

> Snap your fridge. Get a recipe. Waste less food.

SnapshotChef is an AI-powered web app built at HooHacks 2026 that analyzes your fridge photo and suggests personalized recipes based on what you actually have — complete with dietary filters and real food photos.

---

## ✨ Features

- 📷 **Fridge photo upload** — drag & drop or click to browse
- 🧠 **AI ingredient detection** — OpenAI's vision model identifies what's in your fridge
- 🥗 **Dietary filters** — vegan, vegetarian, gluten-free, dairy-free, nut-free, halal, kosher
- 🍳 **Smart recipe matching** — recipes ranked by ingredient overlap with what you have
- 🖼️ **Food photography** — beautiful recipe photos powered by the Unsplash API
- ➕ **Add extra ingredients** — type in anything extra you have on hand
- ❌ **Remove ingredients** — remove anything the AI got wrong

---

## 🚀 How It Works

1. **Upload a fridge photo** — take a clear photo of the inside of your fridge
2. **AI analyzes it** — OpenAI's vision model identifies your ingredients
3. **Set your preferences** — choose dietary restrictions and add any extra ingredients
4. **Get matches** — see recipes ranked by how well they match what you have

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python, Flask |
| AI | OpenAI API (GPT-4o-mini vision) |
| Images | Unsplash API |
| Data | Pandas + recipes.csv |
| Frontend | HTML, CSS, JavaScript, Jinja2 |

---

## ⚙️ Setup

**1. Clone the repo**
```bash
git clone https://github.com/Alish-12/hoohacks2026.git
cd hoohacks2026/my-website
```

**2. Create a virtual environment**
```bash
python3 -m venv venv
source venv/bin/activate
```

**3. Install dependencies**
```bash
pip3 install -r requirements.txt
```

**4. Create a `.env` file in `my-website/`**
```
OPENAI_API_KEY=your_openai_key_here
UNSPLASH_ACCESS_KEY=your_unsplash_key_here
```

**5. Run the app**
```bash
python3 app.py
```

**6. Open your browser**
```
http://127.0.0.1:1025
```

---

## 📁 Project Structure
```
my-website/
├── app.py                  # Flask backend & routes
├── fridge_ai.py            # OpenAI vision analysis
├── recipes.csv             # Recipe dataset
├── requirements.txt
├── templates/
│   ├── base.html
│   ├── home.html           # Upload page
│   ├── selectFilters.html  # Dietary preferences
│   └── results.html        # Recipe results
├── src/
│   ├── css/
│   ├── js/
│   └── img/
└── uploads/                # Uploaded fridge photos
```

---

## 👩‍💻 Team

Built with ❤️ at **HooHacks 2026** — University of Virginia

| Name | Email |
|---|---|
| Alicia Yoo | vnm3nw@virginia.edu |
| Tracy Do | ctm4nu@virginia.edu |
| Anna Wilcomes | eaz9pn@virginia.edu |

---
