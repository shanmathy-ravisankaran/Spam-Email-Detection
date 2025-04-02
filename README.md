# Spam Email Classification System

A production-grade machine learning system designed to robustly classify emails as "Spam" or "Ham" (legitimate). This project features a modular pipeline architecture for training and inference, integrated with a modern Streamlit user interface for easy interaction.

## 🚀 Key Features

- **Advanced ML Pipeline**: Modular design separating data ingestion, transformation, and model training.
- **Multiple Model Support**: evaluation of various algorithms including SVM, Logistic Regression, Decision Trees, and Random Forest.
- **Interactive Web UI**: Built with Streamlit for real-time single-email analysis and batch processing.
- **MBOX Support**: Native capability to process and classify entire `mbox` email archives.
- **Detailed Analytics**: Comprehensive logging and performance metrics (Precision, Recall, F1-Score).

## 🛠️ Tech Stack

- **Language**: Python 3.10+
- **Frontend**: Streamlit
- **ML Framework**: Scikit-learn
- **Data Processing**: Pandas, NumPy, BeautifulSoup4
- **Project Management**: `uv` (recommended) or `pip`

## 📂 Project Structure

```
├── app.py                  # Main Streamlit Web Application
├── requirements.txt        # Project dependencies
├── main.py                 # (Optional) Alternative entry point
├── src/
│   ├── components/         # Core processing modules (Ingestion, Transformation)
│   ├── pipeline/           # Orchestration pipelines (Training, Prediction)
│   ├── config/             # Configuration and parameters
│   └── utils/              # Helper functions, logging, and state management
├── data/                   # Dataset storage (inputs)
├── outputs/                # Training artifacts (models, vectorizers)
└── logs/                   # System runtime logs
```

