# FloatChat — Conversational Ocean Data Explorer (Prototype)

FloatChat is a browser-based frontend prototype that demonstrates how ARGO oceanographic data could be explored through a conversational interface.

This project was originally built for hackathon pitching — showing how scientific marine data (temperature / salinity / depth readings from ARGO floats) can be democratized and made accessible through chat-based queries + visual dashboards.

---

## 👀 Why FloatChat?

Oceanographic research data is massive, complex, and locked behind specialized tools.  
FloatChat imagines a future where:

- you don’t need a scientific background to explore ocean data  
- you can just *talk* to the ocean dataset like ChatGPT  
- the system automatically visualizes insights for you  

This prototype shows the UI, UX and visualization concepts for that experience.

---

## 🌟 Key Features (Current Prototype)

| Feature | Description |
|---------|-------------|
| Conversational UI | Chat interface designed for marine data Q&A |
| Dashboard Concepts | mock graphs for float trajectories, depth-time analysis |
| Responsive UI | mobile + tablet + desktop friendly |
| Modern UX | ocean gradient design system & smooth UI transitions |
| Hackathon-ready narrative | clearly shows the problem → vision → UI → value |

> Note: This version is **frontend-only**.  
> ARGO data & responses are simulated.

---

## 🧠 Proposed AI Workflow (for future version)

- ingest ARGO NetCDF / CSV float datasets  
- store float embeddings in vector DB  
- semantic RAG based retrieval from dataset  
- LLM produces narrative insights + chart instructions  
- frontend renders the visualization automatically

This shows future potential direction for research product or SaaS.

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, JavaScript |
| Charts | Chart.js |
| Data Status | mock sample JSON data |
| ML / API | not implemented yet (planned RAG backend) |

---

## 📁 Project Structure

```bash
/index.html            -> landing page
/features.html         -> feature showcase
/aboutpage.html        -> ARGO intro + product story
/chat.html             -> main chat interface screen
/dashboard.html        -> visual analytics section
/dashboard_app.js      -> chart logic + mock ARGO data
/dashboard_style.css   -> dashboard styling
/style.css             -> global styling
```

---

## ▶️ Run Locally

```bash
git clone https://github.com/Akanksha-singh27/Akanksha-Floatchat
```

Then open:

```bash
index.html
```

in your browser.

---

## 🚀 Future Roadmap

- integrate real ARGO APIs
- build backend for RAG retriever
- conversational querying with LLM
- persistent user sessions + saved chats
- export visual reports for researchers

---

## 👩‍💻 Author

**Akanksha Singh**

GitHub → [@Akanksha-singh27](https://github.com/Akanksha-singh27)
