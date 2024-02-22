# Flu Shot Learning: Predict H1N1 and Seasonal Flu Vaccines

![Flu Vaccine](https://drivendata-public-assets.s3.amazonaws.com/flu-vaccine.jpg)

## Problem Description

Your goal is to predict how likely individuals are to receive their H1N1 and seasonal flu vaccines. Specifically, you'll be predicting two probabilities: one for h1n1_vaccine and one for seasonal_vaccine.

Each row in the dataset represents one person who responded to the National 2009 H1N1 Flu Survey.

### Labels
- **h1n1_vaccine**: Whether respondent received H1N1 flu vaccine. (0 = No, 1 = Yes)
- **seasonal_vaccine**: Whether respondent received seasonal flu vaccine. (0 = No, 1 = Yes)

### Features
- **h1n1_concern**: Level of concern about the H1N1 flu.
- **h1n1_knowledge**: Level of knowledge about H1N1 flu.
- **behavioral_antiviral_meds**: Has taken antiviral medications.
- **behavioral_avoidance**: Has avoided close contact with others with flu-like symptoms.
- **behavioral_face_mask**: Has bought a face mask.
- **behavioral_wash_hands**: Has frequently washed hands or used hand sanitizer.
- (And so on...)

## Performance Metric
- The performance metric is the ROC AUC score for each target variable.

## Submission Format
- The submission format includes probabilities for both h1n1_vaccine and seasonal_vaccine.

## Dataset
- The dataset contains 36 columns, with the first column being a unique identifier and the remaining 35 columns representing features.

## Example
- A sample submission file and dataset are provided for reference.

## Usage
- Clone the repository and run the provided scripts to train and evaluate your models.

## Dependencies
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## License
- This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

