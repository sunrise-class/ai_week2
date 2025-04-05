# Credit Fraud Detector

**Note:** This project is under ongoing development. Expect changes as I refine the methodology. Your feedback and upvotes are greatly appreciated, as they motivate me to improve the accuracy and efficiency of our fraud detection models.

## Introduction

This project explores the use of various predictive models to detect credit card fraud. The dataset provided contains scaled features, anonymized for privacy. Despite the lack of feature names, we can still perform meaningful analysis and build effective detection models.

## Goals

* **Data Understanding:** Analyze the distribution of the provided dataset.
* **Data Balancing:** Create a balanced sub-dataframe with a 50/50 ratio of "Fraud" and "Non-Fraud" transactions using the NearMiss algorithm.
* **Model Selection:** Evaluate the accuracy of different classifiers and identify the most effective one.
* **Neural Network Comparison:** Develop a Neural Network and compare its performance to the best classifier.
* **Imbalanced Data Awareness:** Discuss common pitfalls and best practices when working with imbalanced datasets.

## Project Structure

(You can add more details about the project structure here, such as file organization, dependencies, etc.)

* `data/`: Contains the credit card fraud dataset.
* `notebooks/`: Jupyter notebooks with data analysis, model development, and evaluation.
* `models/`: Saved model files.
* `src/`: Python scripts for data processing and model building (if applicable).
* `requirements.txt`: List of Python dependencies.

## Dependencies

* Python (>= 3.6)
* Pandas
* NumPy
* Scikit-learn
* TensorFlow/Keras (for Neural Network)
* Matplotlib
* Seaborn

(Add specific versions if necessary, or create a `requirements.txt` file and refer to it here.)

## Setup

1.  **Clone the repository:**

    ```bash
    git clone [repository URL]
    cd credit-fraud-detector
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate  # On Windows
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the notebooks:**

    ```bash
    jupyter notebook notebooks/your_notebook.ipynb
    ```

## Data Preprocessing

* The dataset is loaded and analyzed for class distribution.
* The NearMiss algorithm is applied to create a balanced sub-dataframe.

## Model Development

* Various classifiers are evaluated, including:
    * [List the classifiers you used, e.g., Logistic Regression, Random Forest, etc.]
* A Neural Network is developed using TensorFlow/Keras.
* Model performance is compared based on accuracy and other relevant metrics.# ai_week2
