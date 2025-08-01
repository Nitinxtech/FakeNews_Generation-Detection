# 📰 Fake News Generator & Detector 🔍  
An interactive AI-powered system that demonstrates how news can be both generated and detected using modern NLP models. Built with GPT-2 and BERT using Gradio for an engaging interface.

---

## 🎯 Objective  
The goal of this project is to showcase the **power and risk of AI in media** by simulating how fake news is created and detected. This educational tool allows users to:
- Generate fake news articles using a **GPT-2 model**
- Detect whether a given news snippet is **real or fake** using a **Tiny BERT classifier**

---

## 🚀 Features  
✅ **News Generation** using GPT-2 based on custom prompts  
✅ **Fake News Detection** using `bert-tiny-finetuned-fake-news-detection`  
✅ **Gradio Interface** with intuitive tabs and clean layout  
✅ **Color-coded Feedback** (🟩 Real / 🟥 Fake) with emoji cues  
✅ **Rule-Based Filtering** for common misleading claims  
✅ Personalized UI with custom titles and messages

---

## 🧠 Models Used  
| Component              | Model Name (HuggingFace)                                      |
|------------------------|---------------------------------------------------------------|
| Fake News Generator    | [`gpt2`](https://huggingface.co/gpt2)                         |
| News Detector (Tiny)   | [`mrm8488/bert-tiny-finetuned-fake-news-detection`](https://huggingface.co/mrm8488/bert-tiny-finetuned-fake-news-detection) |

---

## 🖥️ Gradio Interface  
- **Two Tabs:**
  - `Generate Fake News` – input prompt and get AI-generated news
  - `Detect News Authenticity` – paste news text and get fake/real classification  
- **UI Includes:**
  - Loading spinners
  - Emoji-based results
  - Name branding (e.g., “Built by Nitin Pandey”)

---

## 📁 Project Structure  
```bash
├── app.ipynb                # Jupyter Notebook with code and UI
├── README.md                # Project documentation
├── requirements.txt         # Python dependencies
└── assets/                  # (Optional) Screenshots or media

⚙️ Installation & Run Locally
bash
Copy
Edit
# Clone the repository
git clone https://github.com/<your-username>/fake-news-detector.git
cd fake-news-detector

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.ipynb
📝 Or run directly in Google Colab for demo purposes.

🔍 Future Improvements
Use bert-base or roberta-base for higher accuracy

Integrate live fact-checking APIs (e.g., Google Fact Check Tools)

Add news source validation (URL, domain trust)

Generate multiple news versions with temperature control

📚 Use Cases
NLP demos for classrooms and workshops

Raising awareness about AI-generated misinformation

Quick fake/real checker for social media or blog content

Hackathon or portfolio-ready demo project

🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.

📄 License
This project is open source under the MIT License.

🙋‍♂️ Author
Nitin Pandey – LinkedIn • GitHub

🌟 Show your support
If you liked this project, please ⭐ the repo and share it!


