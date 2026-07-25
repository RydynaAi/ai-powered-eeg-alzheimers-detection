# ai-powered-eeg-alzheimers-detection
AI-powered EEG analysis for early Alzheimer's disease detection and prediction
## 🗂️ Project Structure
 
<pre>
EEG-pro Alzheimer's/
├── models/                  # Trained EEGNet model + weights
├── notebooks/
│   ├── 1_data_preprocessing.ipynb
│   └── 2_training_pipeline1.ipynb
├── data/
│   └── new_subjects/        # Raw EEG files for inference (not included, see below)
├── frontend/                # React + TypeScript + Vite dashboard
├── server_fixed.py          # Flask inference API
├── requirements.txt
└── start.sh
</pre>
 
---
 
## 🛠️ Tech Stack
 
<table>
<tr><th>Layer</th><th>Technology</th></tr>
<tr><td>Signal Processing</td><td>MNE-Python, NumPy, SciPy</td></tr>
<tr><td>Model</td><td>TensorFlow / Keras (EEGNet)</td></tr>
<tr><td>Backend API</td><td>Flask, Flask-CORS</td></tr>
<tr><td>Frontend</td><td>React 18, TypeScript, Vite, Tailwind CSS, Chart.js, Three.js</td></tr>
<tr><td>Notebooks</td><td>Jupyter, scikit-learn, seaborn, matplotlib</td></tr>
</table>
---
 
## ⚡ Getting Started
 
### Prerequisites
- Python 3.11
- Node.js 18+
### 1. Clone the repository
<pre>
git clone https://github.com/&lt;your-username&gt;/&lt;your-repo&gt;.git
cd "EEG-pro Alzheimer's"
</pre>
 
### 2. Set up the backend
<pre>
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python server_fixed.py
</pre>
 
### 3. Set up the frontend
<pre>
cd frontend
npm install
npm run dev
</pre>
 
### 4. Run the notebooks (optional)
<pre>
./start.sh
</pre>
 
---
 
## 📊 Dataset
 
<p>
Training data comes from the
<a href="https://openneuro.org/datasets/ds004504">OpenNeuro ds004504</a> dataset of resting-state EEG recordings.
Raw <code>.set</code> EEG files used for inference testing are <b>not included in this repository</b> due to size —
they are available <a href="#">here</a> (add your Google Drive / Kaggle link).
</p>
---
 
## 📈 Model Performance
 
<table>
<tr><th>Metric</th><th>Score</th></tr>
<tr><td>Accuracy</td><td>0.809</td></tr>
<tr><td>AUC</td><td>0.983</td></tr>
</table>
---
 
## 👥 Team
 
<p>Graduation project — Artificial Intelligence</p>
<table>
<tr><th>Name</th></tr>
<tr>
  <td>Rudyna Al-Qarni</td>
</tr>
<tr>
  <td>Najla Alamri</td>
</tr>
<tr>
  <td>Areej Al-Harthi</td>
</tr>
<tr>
  <td>Gina Al-Harthi</td>
</tr>
<tr>
  <td>Lamees Al-Jahmi</td>
</tr>
</table>
---
 
<div align="center">
Made with 🧠 and ☕
</div>
