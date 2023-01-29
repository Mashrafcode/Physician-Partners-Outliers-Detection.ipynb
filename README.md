# Physician Partners : Outliers-Detection

## Problem Stataement : 
In this exercise, we are providing you with an example of financial data (all numbers are fictional).

You need to create an algorithm that can find outliers in this data by one column / several columns. E.g. some members have extremely high costs in the current month and your solution should be able to detect such records. Think about features and how you would explain them to business people.

### Data Description
The dataset sfr_test.csv contains fictional financial information about customers of the company.

Below is the description of the selected columns from this dataset:

* member_unique_id - member's ID
* gender - member's gender
* dob - member's date of birth
* eligible_year - year
* eligible_month - month
* affiliation_type - doctor's type
* pbp_group - health plan group
* plan_name - health plan name
* npi - doctor's ID
* line_of_business - health plan type
* esrd - True if patient is on dialysis
* hospice - True if patient is in hospice
The remaining columns contain various financial indicators. All values in these financial columns contain a $ sign.

