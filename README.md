# Semantic Book Recommender

This is a **Semantic Book Recommendation System** that uses **LangChain**, **HuggingFace embeddings**, and **ChromaDB** to provide book recommendations based on user queries. The system allows filtering by category and emotional tone and is integrated with a **Gradio** dashboard for an interactive UI.

## Features
- **Semantic Search**: Uses embeddings to find books similar to a user's query.
- **Emotion-Based Filtering**: Sort recommendations based on emotions like joy, anger, sadness, etc.
- **Category Selection**: Filter books by specific genres/categories.
- **Interactive UI**: Powered by **Gradio**.

---

## Installation

### **1. Clone the Repository**
```sh
  git clone https://github.com/your-username/semantic-book-recommender.git
  cd semantic-book-recommender
```

### **2. Create and Activate Virtual Environment**
```sh
# For Windows
python -m venv venv
venv\Scripts\activate

# For Mac/Linux
python3 -m venv venv
source venv/bin/activate
```

### **3. Install Dependencies**
```sh
pip install -r requirements.txt
```

### **4. Set Up Environment Variables**
Create a `.env` file in the project root and add:
```
OPENAI_API_KEY=your_openai_api_key_here
```
Make sure you replace `your_openai_api_key_here` with your actual API key.

---

## Running the Application
```sh
python app.py
```
This will launch the **Gradio dashboard** in your browser.

---

## Project Structure
```
📂 semantic-book-recommender
├── 📄 app.py                 # Main application script
├── 📄 books_with_emotions.csv # Dataset with book details & emotions
├── 📄 tagged_description.txt  # Preprocessed book descriptions
├── 📄 requirements.txt       # Python dependencies
├── 📄 .env                   # Environment variables (ignored in Git)
└── 📄 README.md              # Project documentation
```

---

## Deployment (Optional)
To deploy your app using **Gradio Share**:
```sh
python app.py --share
```

To deploy on **Hugging Face Spaces** or **Streamlit Cloud**, additional configurations may be needed.

---

## How to Push to GitHub
```sh
# Initialize Git (if not already initialized)
git init
git add .
git commit -m "Initial commit"

git branch -M main
git remote add origin https://github.com/your-username/semantic-book-recommender.git
git push -u origin main
```

Replace `your-username` with your GitHub username.

---

## Contributing
Feel free to fork this repository, create a new branch, and submit a pull request with improvements!

---

## License
This project is open-source and available under the **MIT License**.

---

## Contact
For any issues or feature requests, please open an **Issue** on GitHub.

