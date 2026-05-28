# DeepGuard AI — Automated Media Credibility & Digital Forensics Platform

DeepGuard AI is a multi-modal media credibility and digital forensics ecosystem built for the **Beyond Tomorrow Summit Hackathon 2026**. 

The platform allows users, platforms, and media organizations to drop any media file (images, videos) or remote URLs to perform an instant, multi-layered integrity audit. It simplifies complex forensic data matrices into intuitive credibility scores and detailed verification logs, helping combat synthetic media (deepfakes) and digital misinformation.

---

## 🔥 Key Features
* **Multi-Modal Analytics Engine:** Designed to evaluate visual pixel inconsistencies, textual context, and file metadata simultaneously.
* **Cryptographic Integrity Verification:** Real-time generation of secure **SHA-256 hashes** to trace hidden edits, structural tampering, or metadata modifications.
* **Asynchronous Pipeline Visualizer:** A smooth, step-by-step progress tracking loop that shows live processing stages (`Metadata Analysis` ➔ `Cryptographic Verification` ➔ `Model Inference`).
* **Analytical Dashboard:** Clear metrics showcasing Total Scans, System Credibility Indexes, and interactive time-series distribution charts using Recharts.

---

## 🛠️ Technology Stack
* **Frontend Framework:** React 18 (Functional Components, Context API)
* **Build Tool:** Vite (High-speed bundler)
* **Styling Engine:** Tailwind CSS (Modern dark-mode theme)
* **Data Visualization:** Recharts (Interactive analytics graphs)
* **Icon Library:** Lucide React

---

## 📂 Project Structure

```text
deepguard-ai/
├── src/
│   ├── components/
│   │   ├── Dashboard.jsx         # Global threat analytics and Recharts graphs
│   │   ├── MediaScanner.jsx      # Drag-and-drop file uploader and live progress tracking
│   │   └── AnalysisResults.jsx   # Detailed diagnostic report views
│   ├── context/
│   │   └── AppContext.jsx        # Global state and pipeline simulation database
│   ├── App.jsx                   # High-fidelity dashboard application shell layout
│   ├── index.css                 # Global styles and Tailwind utilities
│   └── main.jsx                  # Application root entry point
├── package.json
└── README.md
