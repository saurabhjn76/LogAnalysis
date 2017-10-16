# LogAnalysis
Project 3 of Udacity FSND

Here are the questions the reporting tool should answer. The example answers given aren't the right ones, though!

#### What are the most popular three articles of all time? Which articles have been accessed the most? Present this information as a sorted list with the most popular article at the top.

Example:

"Princess Shellfish Marries Prince Handsome" — 1201 views
"Baltimore Ravens Defeat Rhode Island Shoggoths" — 915 views
"Political Scandal Ends In Political Scandal" — 553 views


####  Who are the most popular article authors of all time? That is, when you sum up all of the articles each author has written, which authors get the most page views? Present this as a sorted list with the most popular author at the top.

Example:

Ursula La Multa — 2304 views
Rudolf von Treppenwitz — 1985 views
Markoff Chaney — 1723 views
Anonymous Contributor — 1023 views


#### On which days did more than 1% of requests lead to errors? The log table includes a column status that indicates the HTTP status code that the news site sent to the user's browser.


#### To run  the news database to its original form, first  drop each of the tables, then import the data from the newsdata.sql file.

In psql:

```
drop table log;
drop table articles;
drop table authors;
```
Then in the shell, to import the data:

```psql -d news -f newsdata.sql```

Run the script:

``` python main.py```

The output is shown in  `out.txt`.

