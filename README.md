
# ⚽ Football Match Predictor (React + TensorFlow.js)

This is a web app that uses a trained DNN model (converted with TensorFlow.js) to predict the outcome of football matches based on historical features.

---

## 🚀 Features
- Accepts Home and Away team input
- Normalizes match data using a precomputed scaler
- Loads a trained model in-browser with TensorFlow.js
- Predicts match outcome (Home Win, Draw, Away Win)
- Clean UI with Tailwind CSS

---

## 📁 Folder Structure

```
football-predictor-app/
├── public/
│   └── model/                # Contains model.json and weight shard
│   └── assets/               # Contains scaler.json and label_encoder.json
├── src/
│   ├── App.jsx               # Main app logic
│   ├── assets/matches.csv    # Optional match dataset
│   └── index.css             # Tailwind CSS
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

---

## 🛠️ Local Development

### 1. Install dependencies
```bash
npm install
```

### 2. Start the dev server
```bash
npm run dev
```

---

## 🌍 Deployment on Vercel

### Option 1: With GitHub

1. Push this project to GitHub
2. Go to [https://vercel.com](https://vercel.com) and click “Add Project”
3. Import your GitHub repo
4. Set **Framework Preset** to **Vite**
5. Click **Deploy**

### Option 2: Using Vercel CLI

```bash
npm install -g vercel
vercel login
vercel deploy --prod
```

---

## ✅ Notes

- Replace `scaler.json`, `label_encoder.json`, and the model files with your actual content.
- Use `App.jsx` to plug in real-time values for prediction or extend the UI for batch processing.

---
