# Fuzzy Genetic Classifier(CI_P3)

## Genetic Fuzzy System for SMS Spam Detection

### Description

This project implements a genetic fuzzy system for SMS spam detection. The system uses a genetic algorithm to evolve fuzzy rules that determine whether an SMS message is legitimate (ham) or spam. It applies feature selection and reduction techniques on the SMS dataset and evolves fuzzy rules based on linguistic variables and fuzzy sets. The fitness of each chromosome is evaluated using the accuracy of spam detection on the test data. The system aims to find optimal fuzzy rules for SMS spam detection.

### Requirements

- Python (>=3.6)
- Numpy
- Pandas
- Matplotlib
- Scikit-learn

### How to Use

1. Clone this repository:

```
git clone https://github.com/alimamanpoosh/Fuzzy-Genetic-Classifier.git
cd your_project
```

2. Install the required dependencies:

```
pip install numpy pandas matplotlib scikit-learn
```

3. Run the project:

```
python main.py
```

### File Descriptions

- `main.py`: Contains the main script to run the genetic fuzzy system.
- `SMSSpamCollection`: Dataset containing SMS messages labeled as spam or legitimate.
- `spam_detection.png`: Image used in the README to illustrate the spam detection process.
- `LICENSE`: Project license file.

### Contributions

Contributions to this project are welcome! Feel free to create issues or submit pull requests.

