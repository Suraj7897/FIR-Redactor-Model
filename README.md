# **FIR Redactor by Suraj Mukherjee** 🚔  
*Ensuring Data Privacy in Law Enforcement*  

## 📌 **Overview**  
Welcome to the **FIR Redactor**, a powerful and intuitive tool developed for the Karnataka Police Department. The purpose of this tool is to enhance the privacy and security of sensitive information within **First Information Reports (FIRs)**. By leveraging cutting-edge AI, PDF processing libraries, and language models, this tool helps redact personal identifiers from FIR documents written in both **English** and **Kannada**.  
<br>
![Seamless Redaction Process](https://github.com/raju-2003/KSP-DATATHON-24/assets/107802002/092cadc2-dc8b-45ea-992e-da55dc2302e7)

## 🔥 **Key Features**  
✅ **Dual Language Support**: Works with both **English** and **Kannada** FIRs. <br>
✅ **AI-Powered Entity Extraction**: Accurately extracts sensitive information using **OpenAI**. <br>
✅ **Automated Redaction**: Seamlessly redacts identified personal data from **PDFs**. <br>
✅ **User-Friendly Interface**: Easy-to-use UI with tabs for **Home**, **Login**, and **Redaction**. <br>
✅ **Security-First**: Adheres to strict privacy and security protocols. <br>

## 🛠 **Technologies Used**  
- **Language Models:** OpenAI GPT <br>
- **PDF Processing:** PyMuPDF, PyPDF2 <br>
- **Web Interface:** Streamlit <br>
- **Database:** MongoDB <br>
- **Security:** JWT Authentication <br>

## 🚀 **Getting Started**  
### **1. Prerequisites**  
- Python 3.7 or higher <br>
- MongoDB <br>
- **OpenAI** API Key <br>
- Streamlit <br>
- PyPDF2, PyMuPDF <br>

### **2. Installation**  
``bash
git clone https://github.com/Suraj7897/KSP-DATATHON-24.git  
cd KSP-DATATHON-24  
pip install -r requirements.txt  
<br>
3. Set Up Environment Variables
Create a .streamlit/secrets.toml file and add your OpenAI API Key and MongoDB connection string. Example:

toml
Copy
Edit
[secrets]  
openai = "your_openai_api_key"  
connection_string = "your_mongodb_connection_string"  
<br>
4. Running the Application
Run the application with:

bash
Copy
Edit
streamlit run app.py  
<br>
📸 Screenshots / Demo
![Criminal Investigation Department](https://github.com/user-attachments/assets/1e6d6c35-75e8-48fb-b074-ee673bb2726d)
![484ac387b9dac68e30c446673015c562bb4549b5](https://github.com/user-attachments/assets/e64d46d1-3877-4757-b1b4-68387bb5328f)
![429d9c1790f00d5ea7de67650ae8f4c111a82616](https://github.com/user-attachments/assets/ffc97801-1337-4769-87e4-50186d50a0dd)
![59ffc1ebea2898d68ed4bacf0115ffb5643e14e9](https://github.com/user-attachments/assets/d7875374-5a70-4306-bdf5-8a124715d534)
![5c5da72eec6ef0f13337ff286f76e2691c57716e](https://github.com/user-attachments/assets/83e43243-f323-4ee0-a94c-035f6c446fbd)



<br>

📝 How It Works
Upload FIR Documents: Upload PDF FIRs for processing. <br>
AI-Suggested Redactions: The AI will suggest personal identifiers to redact. <br>
Manual Redaction: Users can manually redact sensitive information. <br>
Download Redacted Document: After review, download the redacted FIR PDF. <br>
🔐 Security & Privacy
The FIR Redactor ensures sensitive data is handled securely. All documents are processed with strict privacy standards, ensuring no unauthorized access. The tool helps meet privacy regulations while maintaining public trust. <br>

🚀 Usage
Login
Use the following login credentials:

Username: admin <br>
Password: admin <br>
Redaction Process
Upload FIR Document <br>
AI Redaction Suggestions <br>
Manual Redaction Option <br>
Download Redacted PDF <br>
💡 Application Structure
app.py: The main application file with Streamlit UI and logic. <br>
requirements.txt: Contains the necessary libraries and dependencies. <br>
generate_token(user_id): Generates JWT tokens for authentication. <br>
validate_token(token): Validates the authentication token. <br>
save_token(user_id, token, expiry): Saves the authentication token to MongoDB. <br>
extract_entities(text): Extracts sensitive data from the text using OpenAI. <br>
👨‍💻 Developed By
Suraj Mukherjee
Embedded & Software Developer | IoT Enthusiast | Passionate About Data Privacy and Security <br>

This tool is designed to assist the Karnataka Police Department in safeguarding personal information within FIRs, facilitating compliance with privacy regulations, and enhancing public trust. <br>

🌐 Links
GitHub Repo: Suraj Mukherjee - KSP-DATATHON-24 <br>
LinkedIn Profile: Suraj Mukherjee <br>
Contact: mukherjeesuraj7897@gmail.com <br>
