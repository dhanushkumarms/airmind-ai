# ✈ Airmind  
*AI-Powered Airline Query Intelligence System*

---

<p align="center">
  <img src="assets/airmind_logo.png" alt="Airmind Logo" width="800"/>
</p>

---

![Airmind](https://img.shields.io/badge/Airmind-Active-harlequin?style=for-the-badge&logo=vercel&logoColor=white)  
---

![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi&logoColor=white)  
![React](https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=white)  
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white)  
![HuggingFace](https://img.shields.io/badge/Transformers-NLP-orange?style=for-the-badge&logo=huggingface&logoColor=yellow)  
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=yellow)  

---

## 📖 Description  

**Airmind** is an AI-based airline customer support assistant that automatically classifies user queries such as *flight status, cancellations, baggage issues,* and more. It uses **Natural Language Processing (NLP)** to predict the correct category and learns from user feedback to continually improve accuracy.

---

## ❗ Problem Solved  

Traditional customer service in airlines faces:  
- ❌ High response time due to manual sorting  
- ❌ Repetitive questions to support staff  
- ❌ Poor accuracy in routing user requests  
- ❌ No learning from past user interactions  

**✅ Airmind solves this with:**  
✔ AI-based message classification  
✔ Feedback-integrated continuous learning  
✔ Real-time stats & accuracy logs  
✔ Frontend chat + backend intelligence  

---

## ⚙️ Tech Stack  

**Frontend**  
- ![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)  
- ![Axios](https://img.shields.io/badge/Axios-API-blueviolet?style=for-the-badge)  
- ![Tailwind](https://img.shields.io/badge/Custom_UI-Dark/Light_Theme-teal?style=for-the-badge)  

**Backend**  
- ![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi)  
- ![Python](https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge)  
- ![SQLite](https://img.shields.io/badge/SQLite-Database-blue?style=for-the-badge)  
- ![Transformers](https://img.shields.io/badge/HuggingFace-NLP-orange?style=for-the-badge&logo=huggingface)  

**Model Training (Colab Notebook)**  
- RoBERTa / DistilBERT  
- Tokenization & Fine-Tuning  
- Exportable to `backend/airline_intent_classifier/`  

---

## ✨ Features  

- 🤖 **AI-Powered Classification** – Understands user queries using NLP  
- 📊 **Real-Time Stats Dashboard** – Accuracy, total predictions, errors  
- 🔁 **Feedback Loop** – Learns from user corrections  
- 🌙 **Dark & Light Mode UI**  
- 🗄 **Logs & History Module** for admins  
- 🚀 **Deployable on Cloud (Render/Azure/Vercel)**  

---

## ⚙️ Installation & Setup  

### ✅ 1. Clone the Repository  
```bash
git clone https://github.com/your-username/airmind.git
cd airmind
```

### ✅ 2. Backend Setup  
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```
Backend runs at:  
```cpp
http://127.0.0.1:8000
```

### ✅ 3. Frontend Setup  
```bash
cd ../frontend
npm install
npm start
```
Frontend runs at:  
```arduino
http://localhost:3000
```

---

### 🧠 Model Training (Google Colab)  
Open `notebooks/Airmind_Training.ipynb` in Google Colab  
Upload dataset (`airline_intents_data.csv`)  
Fine-tune RoBERTa model  
Export trained model into `backend/airline_intent_classifier/`  

---

### 📸 Screenshots  
### How to Make This Project a GitHub Repository  

1. **Initialize Git in the Project Directory**  
    Open a terminal in the project root and run:  
    ```bash
    git init
    ```

2. **Add All Files to Git**  
    Stage all files for the initial commit:  
    ```bash
    git add .
    ```

3. **Commit the Changes**  
    Create the first commit:  
    ```bash
    git commit -m "Initial commit"
    ```

4. **Create a New Repository on GitHub**  
    - Go to [GitHub](https://github.com) and log in.  
    - Click the "+" icon in the top-right corner and select "New repository".  
    - Fill in the repository name (e.g., `airmind`) and other details.  
    - Click "Create repository".  

5. **Link the Local Repository to GitHub**  
    Copy the repository URL from GitHub and run:  
    ```bash
    git remote add origin <repository-url>
    ```

6. **Push the Code to GitHub**  
    Push the local repository to GitHub:  
    ```bash
    git branch -M main
    git push -u origin main
    ```

Your project is now live on GitHub!

---

### 🚀 Future Enhancements  
🌍 Multilingual Query Support  
🔐 Admin Authentication & Role-Based Access  
🧾 PDF/Email Report Auto-Generation  
☁ Cloud Deployment (AWS / Azure / Render)  
🤝 Live Chat Integration with Human Agent  

---

### 👨‍💻 Contributors  
Dhanushkumar M

---

### 📜 License  
This project is licensed under the MIT License.
