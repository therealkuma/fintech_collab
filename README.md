
# Project 1: Strategy and Decision Tool:
Company Name: K2M2 Lending: Provide personal loans to individual consumers

## Problem
* Currently the analytics is reviewed manually using excel which is prone to human error
* Reviewing the big data manually is costly and time consuming
* Delay in management actions 
## Solution
* Build an automatic analysis tool for the management to make profitable decisions
* Management has access to timely data to make swift strategic decisions
## Data Type
* Loan data for personal loans focused on debt consolidation, home improvement etc.
* Data Range: YTD 2022

## Approachs

### Accounting

The approach for building the accounting entry is below:

Import two tables from excel file. One for Loan data, the other for HFI & HFS data.
Clean up the data by stripping spaces of each column title.
Build an aggregation formula for each column of the dataset that has numerical values
• Use for loop instead of sum() on each column in order to make the code more efficient
Perform some additions and subtractions to validate the ending balance of the loan.
Merge HFI&HFS table into Loan data table, only merging those which the loan ID matched
Create table by using pd.DataFrame() for each journal entry.
Combined all table into one big table for purpose of booking entry in Quickbook
