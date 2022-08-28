
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

The approach for building the accounting entry is below:   <br />

1) Import two tables from excel file. One for Loan data, the other for HFI & HFS data.     <br/>
2) Clean up the data by stripping spaces of each column title.   <br />
3) Build an aggregation formula for each column of the dataset that has numerical values   <br />
    •	Use for loop instead of sum() on each column in order to make the code more efficient
3) Perform some additions and subtractions to validate the ending balance of the loan.   <br />
4) Merge HFI&HFS table into Loan data table, only merging those which the loan ID matched  <br />
5) Create table by using pd.DataFrame() for each journal entry.    <br />
6) Combined all table into one big table for purpose of booking entry in Quickbook  <br />


### Marketing

The approach for building the marketing analytics is below:   <br />

1) Import one tables from loan data excel      <br/>
2) Create a numerical aggregation that groups the data by the year and then averages the results.   <br />
3) Review the DataFrame   <br />
3) Create a visual aggregation explore the Average outstanding principal by different segment   <br /
    * Loan Segment, FICO, Region, Market Channel etc <br />
 
 ![This is graph image](Loan_Segment.png)
 
 ![This is graph image](Region.png)
 
