# 📚 AI-Powered Learning Dashboard

An interactive web application built with **Python Streamlit** that helps students learn effectively by summarizing study material, generating quizzes, and creating flashcards from uploaded PDFs.

## 🚀 Features
- **Text Extraction**: Automatically extracts text from uploaded PDF documents.
- **Summarization**: Provides concise summaries of the material using AI.
- **Quiz Questions**: Generates simple quiz questions based on key terms from the material.
- **Flashcards**: Creates flashcards to help students memorize important terms.

## 🛠️ Technologies Used
- **Streamlit**: For building an interactive user interface.
- **Hugging Face Transformers**: For summarization using state-of-the-art NLP models.
- **pdfplumber**: For extracting text from PDF files.
- **scikit-learn**: For key term extraction and quiz question generation.

## 💻 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/ai-learning-dashboard.git
   cd ai-learning-dashboard
   ```

2. **Install dependencies**:
   ```bash
   pip install streamlit transformers pdfplumber scikit-learn
   ```

3. **Run the application**:
   ```bash
   streamlit run learning_dashboard.py
   ```

4. **Open the app**:
   The app will open automatically in your default browser. If not, navigate to the URL displayed in the terminal (e.g., `http://localhost:8501`).

## 📂 Project Structure
```plaintext
.
├── learning_dashboard.py  # Main Streamlit app code
├── README.md              # Project documentation
└── requirements.txt       # Dependencies (optional)
```

## 🎯 How to Use
1. Upload your study material in **PDF format**.
2. View the **extracted text** to confirm its content.
3. Check out the **AI-generated summary** of the material.
4. Explore the **quiz questions** created for self-assessment.
5. Use the **flashcards** for quick revision of key terms.

## 🔧 Customization
You can modify or extend the app:
- Replace the summarization model with a custom model.
- Add definitions to flashcards using a dictionary API or custom logic.
- Improve quiz generation with advanced NLP techniques.

## 📦 Example Output
When you upload a PDF, you will see:
- A brief **summary** of the content.
- Five quiz questions like:
  ```
  1. What does the term 'data' mean?
  2. What does the term 'model' mean?
  ```
- Flashcards for important terms:
  ```
  **Data**: Definition of 'data' here.
  **Model**: Definition of 'model' here.
  ```

## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request or report issues.

## 📝 License
This project is licensed under the [MIT License](LICENSE).

## 🌟 Acknowledgments
- Hugging Face for the amazing NLP models.
- Streamlit for simplifying web application development.
- OpenAI for inspiring innovation in AI projects.

