
In this project, we looked into the several datasets from the Federal Election Commission(https://www.fec.gov/data/browse-data/?tab=bulk-data) including "All Candidates", "Candidate Master", "Committee Master", "Candidate-Committee Linkage", and "Contribution by Individuals". We only collected data in the period 2007-2008.
A note before you download these datasets from the FEC: 
"Anyone can inspect and copy reports and statements filed by political committees. But the names and addresses of individual contributors may not be sold or used for commercial purposes or to solicit contributions or donations."
From those datasets, we built a relational database using SQL querries and Linux shell commands in AWS EC2 environment. 
We also explored the newly-built relational database and discovered insights regarding political candidates' campaign finance. Then, we visualized these the findings using Python matplotlib library.
Questions that we answered:
1. Based on the candidate’s total receipts,find the top 10 candidates from both Democratic and Republican parties. Display last name, first name, candidate state, total receipts, and total disbursement.
2. Based on total number of candidates, find the top 10 committee names, their committee type, total number of candidates, total number of NULL candidates, committee party affiliation.
3. Based on contribution by Individuals, find top 10 House candidate Name, rank, State, Party, total receipts. Repeat for 10 senate candidates. 
4. Write a view that provides top 10 Republican committees in terms of the total number of individuals for those committees. Do the same for democratic committees. Calculate the total number of transaction receipts by those top 20 committees and sort the final answer based on total receipts.
