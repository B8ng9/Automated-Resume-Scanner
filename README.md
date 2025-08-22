⚡ Smart ATS – AI-Powered Resume Evaluator

📝 An intelligent Application Tracking System (ATS) simulator that helps you optimize your resume for job applications using Google’s Generative AI (Gemini-Pro).






✨ Features

✅ Upload your resume in PDF format
✅ Paste a job description for evaluation
✅ Get a Match Score (%) against ATS standards
✅ Highlighted list of Missing Keywords
✅ Smart Profile Summary & Suggestions

📸 Demo Preview
<p align="center"> <img src="https://user-images.githubusercontent.com/placeholder/demo.gif" alt="Smart ATS Demo" width="600"/> </p>
🛠️ Tech Stack

Streamlit
 – UI & deployment

Google Generative AI (Gemini-Pro)
 – Resume analysis & scoring

PyPDF2
 – Extracting text from resumes

dotenv
 – Secure API key handling

📂 Project Structure
.
├── app.py              # Main Streamlit app
├── requirements.txt    # Dependencies
├── .env                # API Key configuration (ignored in Git)

⚙️ Installation & Setup
1. Clone this repository
git clone https://github.com/your-username/smart-ats.git
cd smart-ats

2. Create & activate a virtual environment
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

3. Install dependencies
pip install -r requirements.txt

4. Configure API Key

Create a .env file in the project root:

GOOGLE_API_KEY=your_google_api_key_here


👉 Get your API key from Google MakerSuite
.

5. Run the app
streamlit run app.py

🎯 Usage Flow

Paste your Job Description (JD).

Upload your Resume (PDF only).

Hit Submit.

Get:

📊 ATS Match %

📌 Missing Keywords

📝 Profile Summary & Tips

🚀 Roadmap

 Compare multiple resumes at once

 Export results as PDF / CSV reports

 Interactive charts & graphs for ATS scoring

 Support for DOCX resumes

🤝 Contributing

Contributions are welcome!

Fork the project 🍴

Create a new branch 🌱

Commit your changes 💡

Open a PR 🚀

📜 License

This project is licensed under the MIT License
.

🔥 With Smart ATS, land your dream job faster by making your resume ATS-friendly!

