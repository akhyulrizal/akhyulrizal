<div align="center">
  
  <!-- Animated Cat SVG -->
  <svg width="120" height="120" xmlns="http://www.w3.org/2000/svg">
    <style>
      @keyframes blink { 0%, 50%, 100% { height: 10px; } 25%, 75% { height: 0; } }
      @keyframes tail { 0%, 100% { transform: rotate(-5deg); } 50% { transform: rotate(5deg); } }
      .eye-lid { animation: blink 3s infinite; }
      .tail { transform-origin: 20% 50%; animation: tail 2s infinite alternate; }
    </style>
    
    <!-- Cat body -->
    <circle cx="60" cy="70" r="30" fill="#6D4C41"/>
    <circle cx="45" cy="60" r="10" fill="#6D4C41"/>
    <circle cx="75" cy="60" r="10" fill="#6D4C41"/>
    
    <!-- Eyes -->
    <circle cx="50" cy="55" r="3" fill="white"/>
    <circle cx="70" cy="55" r="3" fill="white"/>
    <rect class="eye-lid" x="47" y="54" width="6" height="2" fill="#6D4C41" rx="1"/>
    <rect class="eye-lid" x="67" y="54" width="6" height="2" fill="#6D4C41" rx="1"/>
    
    <!-- Tail -->
    <path class="tail" d="M20 70 Q30 50, 40 65 Q50 80, 30 80 Z" fill="#5D4037"/>
    
    <!-- Ears -->
    <path d="M40 40 L50 30 L60 40 Z" fill="#5D4037"/>
    <path d="M70 40 L80 30 L90 40 Z" fill="#5D4037"/>
    
    <!-- Nose and mouth -->
    <circle cx="60" cy="65" r="2" fill="#FFCDD2"/>
    <path d="M60 67 Q65 70, 60 73" stroke="#FFCDD2" fill="transparent"/>
  </svg>

  <!-- RGB Digital Clock -->
  <div style="
    font-family: 'Courier New', monospace;
    font-size: 24px;
    font-weight: bold;
    background: #111;
    color: #0f0;
    padding: 10px 20px;
    border-radius: 5px;
    display: inline-block;
    margin: 15px;
    text-shadow: 0 0 5px #0f0;
    box-shadow: 0 0 10px rgba(0,255,0,0.5);
  ">
    <span id="live-clock">Loading time...</span>
  </div>
</div>

<script>
  function updateClock() {
    const now = new Date();
    const timeStr = now.toLocaleTimeString('en-US', {hour: '2-digit', minute:'2-digit', second:'2-digit'});
    document.getElementById('live-clock').textContent = timeStr;
  }
  setInterval(updateClock, 1000);
  updateClock();
</script>

---

## 👋 Hello World! 

I'm **Akhyul Rizal**, a passionate university student diving deep into the fascinating world of Data Science, Artificial Intelligence, and Machine Learning. I thrive on transforming raw data into meaningful insights and building intelligent systems that solve real-world problems.

_"In data we trust, but we must verify"_ 📊

---

## 🔭 Currently Learning

- Deep Learning architectures (CNNs, RNNs, Transformers)
- Natural Language Processing techniques
- Big Data technologies (Spark, Hadoop)
- Cloud ML platforms (AWS SageMaker, Google AI Platform)
- MLOps and model deployment

---

## 💻 Tech Stack

### 🐍 Programming
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### 📊 Data Science & ML
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

### 📈 Visualization
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

### 🛠️ Tools
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## 🚀 Highlighted Projects

### 1. [Predictive Maintenance System](https://github.com/akhyulrizal/predictive-maintenance)
> Machine learning model that predicts equipment failures using sensor data  
> - 🔧 Techniques: Time-series analysis, Random Forests, Feature Engineering  
> - 📈 Results: 92% prediction accuracy, reduced downtime by 40%  
> - 🛠️ Tools: Python, Scikit-learn, XGBoost, Dash

### 2. [Sentiment Analysis for Product Reviews](https://github.com/akhyulrizal/sentiment-analysis)
> NLP system that classifies customer sentiment from e-commerce reviews  
> - 🗣️ Techniques: BERT embeddings, LSTM networks, Attention mechanisms  
> - 📊 Results: 89% classification accuracy, deployed as API endpoint  
> - 🧰 Tools: TensorFlow, HuggingFace Transformers, Flask

### 3. [COVID-19 Data Visualization Dashboard](https://github.com/akhyulrizal/covid-dashboard)
> Interactive dashboard tracking pandemic metrics across countries  
> - 🌍 Features: Geospatial visualization, Time-series forecasting  
> - 📱 Output: Real-time web dashboard with interactive controls  
> - 🛠️ Tools: Plotly Dash, Pandas, Heroku

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/akhyulrizal)  
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/akhyulrizal)  
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akhyulrizal)  
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akhyul.rizal@university.edu)

---

## 💬 Favorite Quote

> "Without data, you're just another person with an opinion."  
> — **W. Edwards Deming**

---

⭐ From [Akhyul Rizal](https://github.com/akhyulrizal) with ❤️