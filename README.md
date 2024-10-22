# Customer Review Sentiment Analysis System

A sentiment analysis system for customer reviews using various machine learning models and Count Vectorization technique. The system provides an interactive interface for analyzing customer sentiments and comparing different classification models.

## Features

- Sentiment analysis using multiple classification models:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Multinomial Naive Bayes
- Interactive GUI using IPython widgets
- Real-time sentiment prediction for new reviews
- Model comparison capabilities
- Visualization of results using ROC curves and bar charts
- Performance metrics including accuracy, precision, recall, and F-measure

## Prerequisites

```
python >= 3.6
pandas
numpy
matplotlib
seaborn
scikit-learn
ipywidgets
IPython
```

## Dataset

The system uses the "Amazon_Unlocked_Mobile.csv" dataset containing:
- Customer reviews
- Rating information
- Preprocessed to include only positive (4,5) and negative (1,2) ratings
- Balanced dataset with 20,000 samples from each category

## Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd sentiment-analysis-system
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn ipywidgets ipython
```

## Usage

The system provides three main functionalities:

1. **Analyze Individual Models**
   - Choose from Logistic Regression, SVM, or Multinomial Naive Bayes
   - View different performance metrics:
     - Accuracy scores
     - ROC curves
     - Precision, Recall, and F-Measure reports

2. **Predict Rating for New Reviews**
   - Input any customer review
   - Get real-time sentiment prediction (Good/Bad)
   - Includes progress visualization

3. **Compare Models**
   - View comparative analysis of all models
   - Display accuracy comparison table
   - Visualize results through bar charts

## System Architecture

### Data Preprocessing
- Handles missing values
- Filters relevant columns (Reviews and Rating)
- Balances dataset
- Implements Count Vectorization for text transformation

### Model Implementation
1. **SVM Classifier**
   - Implements Support Vector Machine classification
   - Includes accuracy metrics and ROC curve visualization

2. **Multinomial Naive Bayes**
   - Implements Multinomial NB classification
   - Provides comprehensive performance metrics

3. **Logistic Regression**
   - Implements Logistic Regression classification
   - Includes detailed classification reports

### GUI Components
- Start button for system initialization
- Dropdown menus for model selection
- Radio buttons for metric selection
- Text input for new reviews
- Progress bars for processing visualization

## Performance Metrics

The system provides multiple evaluation metrics:
- Accuracy scores
- ROC curves
- Precision and recall values
- F-measure scores
- Confusion matrices

## Contributing

Feel free to submit issues and enhancement requests.

## Screenshots
<img width="667" alt="Screenshot 2024-10-22 at 3 49 28 PM" src="https://github.com/user-attachments/assets/1d85ee58-9410-4be9-ad4c-8d72b4fbfc46">
<img width="552" alt="Screenshot 2024-10-22 at 3 49 52 PM" src="https://github.com/user-attachments/assets/291f8cd6-457d-4ae4-86f1-68eecc37901b">
<img width="469" alt="Screenshot 2024-10-22 at 3 50 03 PM" src="https://github.com/user-attachments/assets/9f1b02a4-f96a-4e37-b25b-face8bb33fef">
<img width="570" alt="Screenshot 2024-10-22 at 3 50 14 PM" src="https://github.com/user-attachments/assets/54a0dba2-e948-4d99-9abf-160a2400237d">
<img width="476" alt="Screenshot 2024-10-22 at 3 50 25 PM" src="https://github.com/user-attachments/assets/b6696858-f268-4529-b073-741bc18cd1bd">
<img width="486" alt="Screenshot 2024-10-22 at 3 50 37 PM" src="https://github.com/user-attachments/assets/97bd7cac-cbad-4234-946c-30756f014117">
