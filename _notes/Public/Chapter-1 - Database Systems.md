---
title: Chapter - 1
feed: show
date: 05-10-2024
---
	2024-10-06 *15:59*

📒1.1.1 Record Storage
- A common way to make a database persistent is to store its records in files. The
simplest and most straightforward approach is for a database system to store records
in text files
Unfortunately, the approach is too inefficient to be useful, for two
reasons.
The first reason is that large text files take too long to update.

The second reason is that large text files take too long to read. Consider searching
the STUDENT file for the students in the class of 2019. The only way is to scan the file
sequentially. Sequential scanning can be very inefficient. You probably know several
in-memory data structures, such as trees and hash tables, which enable fast searching.

 ❓**How do indexes work?**

Multi User access -
Catastrophes - Transaction Management

- Set up Apache Derby on Eclipse using just 4 jars - derby.jar, derbyclient.jar, derbynet.jar, derbytools.jar
- Could communicate both with the embedded db and the local server db. 

➡️ Next : Setup Simple DB and do the exercises


