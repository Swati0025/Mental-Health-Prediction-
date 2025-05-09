#  Mental Health Assistant

This project is a **Mental Health Disorder Detection System** that utilizes machine learning (Naive Bayes classifier) and a GUI (Tkinter) to predict possible mental health disorders based on user input. 
It also provides treatment suggestions and visual analytics.

---

## 📌 Features

- Text classification using TF-IDF and Multinomial Naive Bayes
- GUI interface to input symptoms and severity
- Disorder prediction and corresponding treatment suggestions
- Data visualizations (disorder distribution, severity levels, word clouds, etc.)
- Custom text preprocessing and cleaning

---

## 📂 Dataset

The project uses a CSV dataset named `large_mental_health_dataset.csv`, which should contain at least the following columns:
- `label`: The mental health disorder
- `text`: Descriptions of symptoms
- `treatment`: Suggested treatment methods
- *(Optional)* `severity`: Severity levels of the disorders

> ⚠️ Ensure the dataset is placed in the same directory and the filename matches the one in the script.

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/mental-health-assistant.git
   cd mental-health-assistant
