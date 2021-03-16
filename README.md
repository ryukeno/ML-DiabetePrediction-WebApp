# ML-DiabetePrediction-WebApp
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Predicting Early Stage Diabetes Risk In Individuals using Machine Learning\n",
    "\n",
    "#### Datasource\n",
    "+ https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset.#\n",
    "+ https://archive.ics.uci.edu/ml/machine-learning-databases/00529/"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Project Outline\n",
    "+ Problem\n",
    "+ Motivation\n",
    "+ Dataset Information\n",
    "+ Feature Processing and Feature Engineering\n",
    "+ Machiine Learning Model Development\n",
    "+ Prediction/Result\n",
    "+ Evaluating the result/metrics\n",
    "+ Conclusion\n",
    "+ References"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Problem Statement\n",
    "+ Diabetes is a very common disease with many risk factors that can lead to getting diabetes.\n",
    "+ Is it possible to predict whether a patient/individual is at a risk of early stage diabetes given the signs and symptoms.\n",
    "+ Since we are using an already labelled dataset to build a predictive model our task will be a supervised machine learning problem\n",
    "+ Therefore we will be using a supervised machine learning classification approach to solve our problem.\n",
    "+ Based on the number of target class we have will will need to build a binary classifier type of ML model.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### About Dataset\n",
    "+ Datasource:\n",
    "    - https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset.#\n",
    "+ Description:\n",
    "    - The dataset was collected using direct questionnaires from the patients of Sylhet Diabetes Hospital in Sylhet, Bangladesh and approved by a doctor.\n",
    "    \n",
    "+ Metadata:\n",
    "    - The dataset is a multivariate dataset in a CSV format.\n",
    "    - It has 520 datapoints and 17 fields or attributes.\n",
    "    \n",
    "+ Attribute Information:\n",
    "    - Age 1.20-65\n",
    "    - Sex 1. Male, 2.Female\n",
    "    - Polyuria 1.Yes, 2.No.\n",
    "    - Polydipsia 1.Yes, 2.No.\n",
    "    - sudden weight loss 1.Yes, 2.No.\n",
    "    - weakness 1.Yes, 2.No.\n",
    "    - Polyphagia 1.Yes, 2.No.\n",
    "    - Genital thrush 1.Yes, 2.No.\n",
    "    - visual blurring 1.Yes, 2.No.\n",
    "    - Itching 1.Yes, 2.No.\n",
    "    - Irritability 1.Yes, 2.No.\n",
    "    - delayed healing 1.Yes, 2.No.\n",
    "    - partial paresis 1.Yes, 2.No.\n",
    "    - muscle sti\u000b",
    "ness 1.Yes, 2.No.\n",
    "    - Alopecia 1.Yes, 2.No.\n",
    "    - Obesity 1.Yes, 2.No.\n",
    "    - Class 1.Positive, 2.Negative."
   ]
  },
