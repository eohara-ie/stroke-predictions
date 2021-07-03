# Capstone Report

## Definition

### Project Overview

OK

Student provides a high-level overview of the project in layman’s terms. Background information such as the problem domain, the project origin, and related data sets or input data is given.

Stroke is an ailment affecting the normal blood supply to the brain. According to the [World Health Organisation](https://www.who.int/bulletin/volumes/94/9/16-181636/en/) stroke is the second leading cause of death globally, accounting for 10.2% of deaths in 2016.

Based on numbers of deaths alone, incidence appears to increase dramatically with age. A recent publication of the [International Journal of Scientific & Engineering Research](https://www.ijser.org/researchpaper/Stroke-Prediction-Models-A-Systematic-Review.pdf) outlines some existing models for cardiovascular risk assessment, which are used to predict strokes. There may be scope to improve on these using Machine Learning techniques.

I was personally drawn to this problem by a hunger to understand the affliction more deeply. Several people close to me have either passed away from a stroke, or are now living with a disability brought on as a result.

My Capstone Proposal is driven by the Stroke Prediction Dataset available on [Kaggle](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).

### Problem Statement

OK

The problem which needs to be solved is clearly defined. A strategy for solving the problem, including discussion of the expected solution, has been made.

Train & deploy a Machine Learning model that can effectively & efficiently predict stroke incidence. Following this, determine what feature(s) may be causally related to strokes.

### Metrics

OK

Metrics used to measure the performance of a model or result are clearly defined. Metrics are justified based on the characteristics of the problem.

A crucial aspect of the final model's performance is its' ability to correctly predict instances of stroke (`stroke` = 1). Due to the imbalanced nature of the label values, accuracy will not be a good measure. Both precision and recall are useful when attempting to quantify the ability of a model to predict a single class. They are handily combined in to a single metric called F1 Score. See [this link](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html) for more information on the algorithm in `scikit-learn`.

## Analysis

### Data Exploration

If a dataset is present, features and calculated statistics relevant to the problem have been reported and discussed, along with a sampling of the data. In lieu of a dataset, a thorough description of the input space or input data has been made. Abnormalities or characteristics of the data or input that need to be addressed have been identified.

Pull figures from notebook.

### Exploratory Visualization

A visualization has been provided that summarizes or extracts a relevant characteristic or feature about the dataset or input data with thorough discussion. Visual cues are clearly defined.

![BMI frequencies](images/bmi_hist.png)

### Algorithms and Techniques

Algorithms and techniques used in the project are thoroughly discussed and properly justified based on the characteristics of the problem.

### Benchmark

Student clearly defines a benchmark result or threshold for comparing performances of solutions obtained.

## Methodology

### Data Preprocessing

All preprocessing steps have been clearly documented. Abnormalities or characteristics of the data or input that needed to be addressed have been corrected. If no data preprocessing is necessary, it has been clearly justified.

### Implementation

The process for which metrics, algorithms, and techniques were implemented with the given datasets or input data has been thoroughly documented. Complications that occurred during the coding process are discussed.

### Refinement

The process of improving upon the algorithms and techniques used is clearly documented. Both the initial and final solutions are reported, along with intermediate solutions, if necessary.

## Results

### Model Evaluation and Validation

The final model’s qualities—such as parameters—are evaluated in detail. Some type of analysis is used to validate the robustness of the model’s solution.

### Justification

The final results are compared to the benchmark result or threshold with some type of statistical analysis. Justification is made as to whether the final model and solution is significant enough to have adequately solved the problem.
