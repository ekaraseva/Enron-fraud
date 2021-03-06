# Enron fraud prediction
This project is part of Udacity's Intro to Machine Learning course.

## Overview
In this project, we play detective, and use machine learning skills to building an algorithm to identify Enron Employees who may have committed fraud based on the public Enron financial and email dataset.

This project teachs you the end-to-end process of investigating data through a machine learning lens.

### Dataset
In 2000, Enron was one of the largest companies in the United States. By 2002, it had collapsed into bankruptcy due to widespread corporate fraud. In the resulting Federal investigation, there was a significant amount of typically confidential information entered into public record, including tens of thousands of emails and detailed financial data for top executives.

In this project, you will play detective, and put your new skills to use by building a person of interest identifier based on financial and email data made public as a result of the Enron scandal. To assist you in your detective work, we've combined this data with a hand-generated list of persons of interest in the fraud case, which means individuals who were indicted, reached a settlement, or plea deal with the government, or testified in exchange for prosecution immunity.

- final_project_dataset.pkl - the dataset for the project.
- emails_by_address : this directory contains many text files, each of which contains all the messages to or from a particular email address.

The features in the data fall into three major types, namely financial features, email features and POI labels.

- financial features: ['salary', 'deferral_payments', 'total_payments', 'loan_advances', 'bonus', 'restricted_stock_deferred', 'deferred_income', 'total_stock_value', 'expenses', 'exercised_stock_options', 'other', 'long_term_incentive', 'restricted_stock', 'director_fees'] (all units are in US dollars)
- email features: ['to_messages', 'email_address', 'from_poi_to_this_person', 'from_messages', 'from_this_person_to_poi', 'shared_receipt_with_poi'] (units are generally number of emails messages; notable exception is ‘email_address’, which is a text string)
- POI label: [‘poi’] (boolean, represented as integer)

## Getting started
Clone or download the repository.
Download and unzip Enron data (423mb) from the link https://www.cs.cmu.edu/~./enron/enron_mail_20150507.tar.gz to the same directory.

### Prerequisites
- Python (2.7)
- Pandas
- Numpy
- TBD....

## Key findings
TBD...
