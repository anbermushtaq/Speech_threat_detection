<img width="1919" height="955" alt="image" src="https://github.com/user-attachments/assets/2401ef52-cb10-4796-bb81-e1e5b80fadf8" />




🕵️ Speech Threat Detection Dashboard

A Streamlit-based application for detecting potential threats, hate speech, and extremist content in English and Urdu text or speech.
This system leverages multilingual NLP models (XLM-RoBERTa and Whisper ASR) to transcribe, analyze, and classify speech content into predefined threat categories.

🚀 Features

    🎙️ Audio Upload & Transcription – Automatically transcribes audio (English/Urdu) using Whisper ASR.
    
    🧠 Threat Classification – Detects threat types such as physical threat, cyber threat, hate speech, political extremism, and neutral.
    
    🌐 Multilingual Support – Supports both English and Urdu input.
    
    📊 Analytical Dashboard – Interactive visualization of detected categories and upload trends.
    
    💾 Logging – Automatically saves classification history for analysis and download.

⚙️ Setup Instructions
1️⃣ Train the Model (optional)

If you plan to train your own classifier:

Open the provided Colab notebook.

Connect to a GPU runtime.

Upload your dataset file (with columns: sentence, language, label).

Train your multilingual model (e.g., fine-tuned XLM-RoBERTa).

Save the trained model to your Google Drive.

You can skip this step if you’re using a pretrained or hosted model.

2️⃣ Run the Streamlit App

Upload your trained model folder to Google Drive (or Hugging Face Hub).

Open the Streamlit app (streamlit_app.py) in Colab or VS Code.

Run the app:

    streamlit run streamlit_app.py


The app will open in your browser automatically.
