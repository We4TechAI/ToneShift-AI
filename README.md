# **📧 ToneShift AI – AI-Powered Email Rewriter**  

![ToneShift AI Banner](assets/banner.png) 

### **🔗 GitHub Repository**  
[We4TechAI/ToneShift-AI](https://github.com/We4TechAI/ToneShift-AI.git)  

---

## **📌 Overview**  
**ToneShift AI** is an AI-powered email rewriting tool that refines your emails based on the selected **tone** and **length preference**. Whether you need a **professional, friendly, concise, apologetic, persuasive, or empathetic** tone, this app ensures your emails are well-structured and impactful.  

🚀 **Key Features:**  
✅ Rewrite emails in **6 different tones**  
✅ Adjust email **length** (shorter, longer, or default)  
✅ **Copy to clipboard** with a single click  
✅ **Modern UI** with an intuitive layout  
✅ **Deployable with Docker**  

---



## **⚙️ Tech Stack**  
- **Python** (Core language)  
- **Streamlit** (UI Framework)  
- **Groq API** (AI-powered text generation)  
- **Docker** (For containerization & deployment)  
- **GitHub Actions** (Optional: for CI/CD)  

---

## **🚀 Getting Started**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/We4TechAI/ToneShift-AI.git
cd ToneShift-AI
```

### **2️⃣ Install Dependencies**  
Ensure you have Python 3.8+ installed, then install the required packages:  
```bash
pip install -r requirements.txt
```

### **3️⃣ Set Up API Keys**  
Create a `.env` file in the project root and add your **Groq API key**:  
```
GROQ=your-groq-api-key-here
```
You can get a Groq API key from [Groq's official website](https://groq.com/).  

### **4️⃣ Run the App Locally**  
```bash
streamlit run app.py
```
The app should now be accessible at **http://localhost:8501** 🎉  

---

## **🐳 Running with Docker**  

### **1️⃣ Build the Docker Image**  
```bash
docker build --tag toneshift_ai:latest .
```

### **2️⃣ Run the Container**  
```bash
docker run -d --name toneshift_ai -p 8501:8501 toneshift_ai:latest
```
Now visit **http://localhost:8501** to use the app inside the Docker container.  

### **3️⃣ Stop & Remove Container (Optional)**  
To stop and remove the running container:  
```bash
docker stop toneshift_ai
docker rm toneshift_ai
```

---

## **🛠️ Folder Structure**  
```bash
ToneShift-AI/
│── app.py                # Main Streamlit application
│── requirements.txt       # Python dependencies
│── Dockerfile             # Docker configuration
│── .env                   # API keys (ignored in Git)
│── README.md              # Project documentation
└── assets/                # (Optional) Images, banners, etc.
```

---



## **💡 Future Enhancements**  
🔹 **Add more tone options** (e.g., sarcastic, motivational)  
🔹 **Integrate with Gmail API** for direct email sending  
🔹 **Support multiple languages** for international users  
🔹 **Implement user authentication** for personalized usage  

---

## **📜 License**  
This project is licensed under the **MIT License** – feel free to modify and distribute.  

---

## **👨‍💻 Contributing**  
We welcome contributions! 🎉  
1. Fork the repository  
2. Create a new feature branch (`git checkout -b feature-name`)  
3. Commit changes (`git commit -m "Added new feature"`)  
4. Push to GitHub (`git push origin feature-name`)  
5. Open a Pull Request  

---


🚀 **Built with ❤️ by We4TechAI** 🚀
