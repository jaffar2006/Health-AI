🩺 Medical AI Assistant
A lightweight Gradio-powered web app that uses IBM's Granite 3.2 2B Instruct model to provide informational medical guidance based on user input. This tool offers two key features: Disease Prediction and Personalized Treatment Plans, with a strong emphasis on ethical use and disclaimers.

⚠️ Disclaimer: This application is for informational purposes only. It does not provide medical advice, diagnosis, or treatment. Always consult a licensed healthcare professional.

🚀 Features
🔍 Disease Prediction
Input symptoms (e.g., "fever, cough, fatigue")

Get possible medical conditions and general medication suggestions

Includes a disclaimer to reinforce responsible use

🧑‍⚕️ Treatment Plan Generator
Input condition, age, gender, and medical history

Receive a personalized treatment plan with home remedies and general medication guidelines

Reinforces the importance of professional medical consultation

🧠 Model & Runtime
Model: ibm-granite/granite-3.2-2b-instruct

Frameworks: Transformers, Gradio

Device Management: Automatically selects GPU (float16) or CPU (float32) based on availability

Prompt Engineering: Structured prompts with disclaimers and context-aware generation

🛠️ Installation
bash
git clone https://github.com/your-username/medical-ai-assistant.git
cd medical-ai-assistant
pip install -r requirements.txt
python app.py
You can also launch the app with share=True to get a public Gradio link.

📦 Dependencies
transformers

torch

gradio

Install via:

bash
pip install transformers torch gradio
📸 Screenshots
Disease Prediction	Treatment Plan
✅ Ethical Use
This project is designed with responsibility and transparency in mind:

All outputs include disclaimers

No diagnosis or treatment is provided

Encourages users to consult professionals
