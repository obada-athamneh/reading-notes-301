# Introduction

**Database normalization is a process used to organize a database into tables and columns. The idea is that a table should be about a specific topic and that only those columns which support that topic are included. For example, a spreadsheet containing information about sales people and customers serves several purposes:**

1. Identify sales people in your organization
2. List all customers your company calls upon to sell product
3. Identify which sales people call on specific customers

## Reasons for Normalization

* There are three main reasons to normalize a database. The first is to minimize duplicate data, the second is to minimize or avoid data modification issues, and the third is to simplify queries. As we go through the various states of normalization, we’ll discuss how each form addresses these issues, but to start, let’s look at some data which hasn’t been normalized and discuss some potential pitfalls. Once these are understood, I think you’ll better appreciate the reason to normalize the data. Consider the following table:


### Data Duplication and Modification Anomalies

**Notice that for each SalesPerson, we have listed both the SalesOffice and OfficeNumber. This information is duplicated for each SalesPerson. Duplicated information presents two problems:**

1. It increases storage and decreases performance.
2. It becomes more difficult to maintain data changes.

# Search and Sort Issues

* The last reason we’ll consider is making it easier to search and sort your data. In the SalesStaff table, if you want to search for a specific customer such as Ford
