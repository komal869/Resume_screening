# 🚀  AI Resume Screening & Candidate Ranking System

#link of app

https://resumescreening-j7qr3265apprmbw4ur9vyfo.streamlit.app/

## 🚀 Overview
This is a **Streamlit-based AI-powered Resume Screening System** that ranks resumes based on their similarity to a given job description. It uses **TF-IDF Vectorization** and **Cosine Similarity** to match resumes and return a ranked list of applicants.


---

## 🛠 Features
✅ Reads text from PDF resumes.
✅ Preprocesses and cleans text for improved matching.
✅ Ranks resumes using **TF-IDF + Cosine Similarity**.
✅ Shows match scores visually with progress bars.
✅ Enables downloading ranked results as a CSV file.


---

## 🖥️ Technologies Used
- **Python 3.x**
- **Streamlit** (for interactive UI)
- **PyPDF2** (for extracting text from PDFs)
- **Scikit-learn** (for text processing and similarity measurement)
- **Pandas** (for data handling)



---

## 📦 Installation  

1️⃣ Clone this repository:  

git clone https://github.com/komal869/Resume_screening.git
cd Resume_screening
2️⃣ Install dependencies:

pip install  requirements.txt
3️⃣ Run the Streamlit app:

streamlit run Resume_score.py
📝 Usage
1️⃣ Enter the Job Description in the provided text area.
2️⃣ Upload multiple PDF resumes.
3️⃣ The system extracts text, processes resumes, and ranks them.
4️⃣ View ranked results with progress bars.
5️⃣ Download ranked results as a CSV file.

🏗️ Code Structure
plaintext

📁 Resume_screening
│-- 📄 Resume_score.py  # Main Streamlit app
│-- 📄 requirements.txt  # Dependencies
│-- 📄 README.md  # Documentation



🔥 Future Improvements
Add OCR support for scanned PDFs using Tesseract.
Improve parsing accuracy using NLP techniques.
Integrate with ATS (Applicant Tracking Systems).
🤝 Contributing
Contributions are welcome! Feel free to fork this repo and submit a PR.

📜 License
This project is MIT Licensed.

💡 Built with ❤️ for better hiring decisions!











