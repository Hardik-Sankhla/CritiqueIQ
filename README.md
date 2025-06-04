<h1 align="center">✨ CritiqueIQ</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/Hardik-Sankhla/Markdown-Resources/main/Image/CritiqueIQ_Banner.png" alt="CritiqueIQ_Banner">
</p>

## 🎯**CritiqueIQ**  

___

### **Introduction:**  

The **CritiqueIQ - Product Review Analyzer** is an AI-powered tool designed to streamline the process of extracting valuable insights from customer reviews. By leveraging advanced natural language processing models, this tool helps businesses like Acme Retail Company efficiently analyze and categorize customer feedback to enhance decision-making across marketing, support, and logistics teams.

___

## 🎯 What is CritiqueIQ?

**CritiqueIQ** is an innovative solution tailored for businesses that receive a high volume of customer feedback. This tool is particularly beneficial for Acme Retail Company, which deals with thousands of reviews daily. The analyzer employs state-of-the-art language models, such as Mistral or LLaMA, hosted via Ollama, to perform sentiment analysis, topic detection, and text summarization.

___

## 🔥 Core Features

- 📊 **Sentiment Analysis** – Classifies reviews as Positive, Neutral, or Negative, providing a quick overview of customer satisfaction.
- 📌 **Topic Detection** – Identifies the main issues or topics discussed in reviews, such as delivery delays or product defects.
- 📝 **Summary Generation** – Produces a one-line summary of each review, highlighting the core message.
- 📈 **Interactive Dashboard** – Built with Streamlit, the dashboard allows users to upload CSV files of reviews, visualize sentiment distribution, and explore top topics.
- 📥 **Downloadable Insights** – Users can download the analyzed results as a CSV file for further analysis or reporting.
- ⚙️ **Technical Stack** – Backend developed using FastAPI, frontend with Streamlit, and data manipulation with Pandas.
- 🚀 **Deployment Ready** – Containerized using Docker for consistent deployment environments and suitable for cloud deployment on platforms like AWS, Azure, or Heroku.

___

## Project Structure and Organization

    review-analyzer-acme/
    ├── backend/
    │   ├── __init__.py
    │   └── main.py
    ├── frontend/
    │   ├── __init__.py
    │   └── app.py
    ├── data/
    │   └── sample_reviews.csv
    ├── tests/
    │   ├── test_backend.py
    │   └── test_frontend.py
    ├── requirements.txt
    ├── README.md
    └── .gitignore
    

___

## 🛠️ Installation

1. **Clone the Repository:**

   ```python
   git clone https://github.com/yourusername/review-analyzer-acme.git
   cd review-analyzer-acme
   ```

2. **Set Up a Virtual Environment:**

    ```python
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies:**

    ```python
    pip install -r requirements.txt
    ```

4. **Run the Backend:**

    ```python
    uvicorn backend.main:app --reload
    ```

5. **Run the Backend:**

    ```python
    streamlit run frontend/app.py
    ```

___

## 🚀 Usage

- Upload CSV: Use the dashboard to upload a CSV file containing product reviews.
- Analyze Reviews: The tool will process the reviews and display sentiment, topics, and summaries.
- Download Results: Download the analyzed data as a CSV file for further use.

___

## Results: 

| ![Integration 1](https://raw.githubusercontent.com/Hardik-Sankhla/Markdown-Resources/main/Image/Result1.png) | ![Integration 2](https://raw.githubusercontent.com/Hardik-Sankhla/Markdown-Resources/main/Image/Result2.png) |
|:---:|:---:|
| ![Integration 3](https://raw.githubusercontent.com/Hardik-Sankhla/Markdown-Resources/main/Image/Result3.png) | ![Integration 4](https://raw.githubusercontent.com/Hardik-Sankhla/Markdown-Resources/main/Image/Result4.png) |

___

## 🤝 Contribution

We welcome contributions to enhance **CritiqueIQ!** 

Please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/YourFeature).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/YourFeature).
5. Open a pull request.

___

## 📄 License

This project is licensed under the MIT License - see the LICENSE  file for details.

___

📧 Contact

For any inquiries or feedback, please contact Hardik Sankhla .
