# Apriori Association Rules
This repository implements the Apriori algorithm to mine association rules from transaction data. The code is flexible and can be used with any dataset containing transactional data.

## Problem Description
The task involves analyzing transaction data to uncover associations between different items. Transactions are represented by sets of items, with each item appearing in a separate row under the same transaction ID. The goal is to identify frequent item sets and generate strong association rules based on user-defined parameters.

## Key Requirements:
### Input:
A dataset in Excel, CSV, or text file format.
Minimum support count.
Minimum confidence (percentage value).

### Output:
The frequent itemsets.
Strong association rules with their confidence.

### Features:
User-friendly interface that allows the user to select the percentage of the data to be analyzed.
The algorithm used is Apriori.
