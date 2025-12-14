# Cell Phone Price Range Classification using Machine Learning

## Project Overview
This project predicts the price range of mobile phones based on hardware specifications such as RAM, battery power, camera, screen size, and connectivity features.

## Algorithms Used
- K-Nearest Neighbors (KNN)
- Logistic Regression (with StandardScaler)
- Random Forest Classifier

## Key Insights
- RAM shows a very strong correlation with price range.
- Battery power and pixel resolution moderately influence price.
- Binary features (4G, WiFi, Touch Screen) have limited standalone impact.
- Logistic Regression with scaling achieved the best generalization.
- Random Forest showed signs of overfitting.

## Dataset
- Source: Kaggle – Mobile Price Classification
- Target variable: `price_range` (0 = low, 3 = very high)

## Results
| Model | Train Accuracy | Test Accuracy |
|------|---------------|---------------|
| KNN | 94.6% | 95.5% |
| Logistic Regression (Scaled) | 97.5% | 97.5% |
| Random Forest | 100% | 89.2% |

## Conclusion
Logistic Regression with feature scaling performs best and avoids overfitting.

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
