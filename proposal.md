# Capstone Proposal

## Domain Background

Stroke is an ailment affecting the normal blood supply to the brain. According to the [World Health Organisation](https://www.who.int/bulletin/volumes/94/9/16-181636/en/) stroke is the second leading cause of death globally, accounting for 10.2% of deaths in 2016. 

Based on numbers of deaths alone, incidence appears to increase dramatically with age. A recent publication of the [International Journal of Scientific & Engineering Research](https://www.ijser.org/researchpaper/Stroke-Prediction-Models-A-Systematic-Review.pdf) outlines some existing models for cardiovascular risk assessment, which are used to predict strokes. There may be scope to improve on these using Machine Learning techniques.

I was personally drawn to this problem by a hunger to understand the affliction more deeply. Several people close to me have either passed away from a stroke, or are now living with a disability brought on as a result.

## Problem Statement

Train & deploy a Machine Learning model that can effectively & efficiently predict stroke incidence. Test results will be used to fine-tune the model if needed.

## Datasets and Inputs

My Capstone Proposal is driven by the Stroke Prediction Dataset available on [Kaggle](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).

The dataset is available as a single CSV file. This dataset was chosen as it contains features related to both a person's lifestyle (e.g. `ever_married`, `smoking_status`, `Residence_type`) and medical condition (e.g. `hypertension`, `heart_disease`, `avg_glucose_level`), along with the all-important `stroke` label.

Disregarding `id` and the label, we are left with ten features that should provide us with concrete insights in to what causes the ailment.

It is worth noting that approximately 95% of people in the dataset did not have a stroke. It will therefore be critcal that we either rebalance our dataset, or choose a scoring algorithm such as recall that punishes false negatives.

## Solution Statement

Split the dataset into a training & testing set, and train an ML model to predict the likelihood of a patient having a stroke, based on features given in the dataset. Deploy and test the model against the test dataset, and further tune the model if necessary.

Next, compare the effectiveness of our new model against the specified benchmark (outlined below). Follow this with a discussion on the merits of different approaches.

## Benchmark Model

Include some basic linear classifier

See notebook

some simple or historical model or result to compare the defined solution to;

A benchmark model is provided that relates to the domain, problem statement, and intended solution. Ideally, the student's benchmark model provides context for existing methods or known information in the domain and problem given, which can then be objectively compared to the student's solution. The benchmark model is clearly defined and measurable.

## Evaluation Metrics

functional representations for how the solution can be measured;

Student proposes at least one evaluation metric that can be used to quantify the performance of both the benchmark model and the solution model presented. The evaluation metric(s) proposed are appropriate given the context of the data, the problem statement, and the intended solution.

## Project Design

how the solution will be developed and results obtained.

Student summarizes a theoretical workflow for approaching a solution given the problem. Discussion is made as to what strategies may be employed, what analysis of the data might be required, or which algorithms will be considered. The workflow and discussion provided align with the qualities of the project. Small visualizations, pseudocode, or diagrams are encouraged but not required.

## Presentation

Proposal follows a well-organized structure and would be readily understood by its intended audience. Each section is written in a clear, concise and specific manner. Few grammatical and spelling mistakes are present. All resources used and referenced are properly cited.

## delete before submitting

Think about a technical field or domain that you are passionate about, such as robotics, virtual reality, finance, natural language processing, or even artificial intelligence (the possibilities are endless!). Then, choose an existing problem within that domain that you are interested in which you could solve by applying machine learning algorithms and techniques. Be sure that you have collected all of the resources needed (such as datasets, inputs, and research) to complete this project, and make the appropriate citations wherever necessary in your proposal.

In addition, you may find a technical domain (along with the problem and dataset) as competitions on platforms such as Kaggle, or Devpost. This can be helpful for discovering a particular problem you may be interested in solving as an alternative to the suggested problem areas above. In many cases, some of the requirements for the capstone proposal are already defined for you when choosing from these platforms.
Evaluation

Your project will be reviewed by a Udacity reviewer against the Capstone Project Proposal rubric. Be sure to review this rubric thoroughly and self-evaluate your project before submission. All criteria found in the rubric must be meeting specifications for you to pass.
Submission Files

At a minimum, your submission will be required to have the following files listed below. If your submission method of choice is uploading an archive (*.zip), please take into consideration the total file size. You will need to include

    A project proposal, in PDF format only, with the name proposal.pdf, addressing each of the seven key points of a proposal. The recommended page length for a proposal is approximately two to three pages.
    Any additional supporting material such as datasets, images, or input files that are necessary for your project and proposal. If these files are too large and you are uploading your submission, instead provide appropriate means of acquiring the necessary files in an included README.md file.
