The approach for building the accounting entry is below:   <br />

1) Import two tables from excel file. One for Loan data, the other for HFI & HFS data.     <br/>
2) Clean up the data by stripping spaces of each column title.   <br />
3) Build an aggregation formula for each column of the dataset that has numerical values   <br />
    •	Use for loop instead of sum() on each column in order to make the code more efficient
3) Perform some additions and subtractions to validate the ending balance of the loan.   <br />
4) Merge HFI&HFS table into Loan data table, only merging those which the loan ID matched  <br />
5) Create table by using pd.DataFrame() for each journal entry.    <br />
6) Combined all table into one big table for purpose of booking entry in Quickbook  <br />
