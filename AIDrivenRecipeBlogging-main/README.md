# 🍲 Flavor Fusion: AI-Driven Recipe Generator

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-ff4b4b)
![Gemini AI](https://img.shields.io/badge/AI-Google%20Gemini-4285F4)

**Flavor Fusion** is an interactive web application that leverages the power of Google's Gemini AI to generate creative and delicious recipe blog posts. Whether you're a food enthusiast looking for inspiration or a developer enjoying a quick coding joke, Flavor Fusion serves up content with a side of fun!

## 🌐 Live Demo

🔗 Demo Video: https://drive.google.com/file/d/1yXiaPI3NcRrDJxg5Y-NFgKvLUIxFRx40/view?usp=sharing

## ✨ Features

-   **AI-Powered Recipes**: Generates detailed recipe blog posts including titles, ingredients, instructions, and engaging introductions using Google Gemini Flash.
-   **Customizable Output**:
    -   **Topic**: Input any dish name or ingredient (e.g., "Vegan Chocolate Cake", "Spicy Ramen").
    -   **Word Count**: Adjust the length of the blog post from 100 to 2000 words.
-   **Entertainment**: Enjoy a random programming joke while your recipe is being "cooked" by the AI.
-   **Downloadable Content**: Save your generated recipes directly as Markdown (`.md`) files.
-   **Modern UI**: A clean, responsive interface built with Streamlit, featuring custom styling.

## 🛠️ Tech Stack

-   **Frontend**: [Streamlit](https://streamlit.io/)
-   **AI Model**: [Google Gemini](https://ai.google.dev/) (gemini-flash-latest)
-   **Language**: Python

## 🚀 Installation & Setup


    ```

1.  **Install Dependencies**

    Make sure you have Python installed. Then run:

    ```bash
    pip install -r requirements.txt
    ```

2.  **API Configuration**

    The application requires a Google Gemini API key.
    
    > **Note**: The current version has an API key embedded for demonstration. For security in production or public forks, it is recommended to use environment variables or Streamlit secrets.

    To set up your own API key:
    -   Get a key from [Google AI Studio](https://makersuite.google.com/app/apikey).
    -   Create a `.streamlit/secrets.toml` file (or set an environment variable) and update the code in `app.py` to use `st.secrets["GOOGLE_API_KEY"]`.

## 💡 Usage

1.  **Run the App**

    ```bash
    streamlit run app.py
    ```

2.  **Generate a Recipe**
    -   Enter a recipe topic in the sidebar.
    -   Select your desired word count.
    -   Click **Generate Recipe**.
    -   Wait for the magic (and enjoy a joke)!
    -   Download the result if you like it.

## 📂 Project Structure

-   `app.py`: Main application logic and UI.
-   `requirements.txt`: Python dependencies.
-   `README.md`: Project documentation.

---


Made by Pothuraju GowriShankar



