---
layout: lesson
title: Using spreadsheet programs for scientific data
root: .
---

Data Carpentry Authors:**Christie Bahlai**, **Aleksandra Pawlik**<br>
Contributors: **Jennifer Bryan**, **Alexander Duryee**, **Jeffrey Hollister**, **Daisie Huang**, **Owen Jones**, **Katja Seltmann**, **Clare Sloggett**, **Harriet Dashnow** and **Ben Marwick**

Good data organization is the foundation of your research project. Most researchers
have data or do data entry in spreadsheets. Spreadsheet programs are very useful graphical interfaces for designing data tables and handling very basic data quality control functions. 

**Much of your time as a manager or researcher will be spent in this 'data wrangling' stage.**

It could be manipulating data to get it **in** a database, or **modifying** output from a database to do something. Examples: Data summaries for a project or institutional report, database migration, preparing for analysis in another software, share a temporary list of taxon names for a student working in a collection, or a data list for sharing and visualizing content in your collection. 

Regarding data migration: Likely you should NOT be using spreadsheets except to visualize data. Delimited text files are used for moving data. Your data workflow for cleaning data will be different based on your data transformation issues, but there are a few, first steps:

	1. Understand the data you are merging. Carefully define the fields from the export database and map to the import database.
	2. Make a list of the data transformations/data cleaning you need to do. This document is very useful, as most data cleaning efforts happen **more than once**.
	3. Data cleaning is iterative. Not between datasets, but on the same dataset. This is the reason we suggest repeatable methods for data cleaning.
	4. Once you understand the data transformations, than you can discover the best way to make those happen.
	* If you have a lot to do and its very challenging, it might be time to ask for help. If you know what you need to do very specifically, it becomes clearer and easier (cheaper) when you do reach out for help.

---

### Spreadsheet outline

In this lesson, we’re going to talk about:

- Good data entry practices - formatting data tables in spreadsheets
- How to avoid common formatting mistakes
- Dates as data - beware!
- Basic quality control and data manipulation in spreadsheets
- Exporting data from spreadsheets
- Simple function
- Taming the iDigBio Portal

---

### Why aren't we teaching data analysis in spreadsheets

- Data analysis in spreadsheets usually requires a lot of manual work. If you want to change a parameter or run an analyses with a new dataset, you usually have to redo everything by hand. (We do know that you can create macros, but see the next point.)
- It is also difficult to track or reproduce statistical or plotting analyses 
done in spreadsheet programs when you want to go back to your work or someone asks 
for details of your analysis.
- We envision spreadsheets as a way to view and rearrange data for use in other applications or databases to store the data.

### Spreadsheet programs

- LibreOffice - used in these lessons because it's a free, open source
spreadsheet program
- Microsoft Excel
- Gnumeric
- OpenOffice.org

Commands may differ a bit between programs, but general ideas
for thinking about spreadsheets is the same. **Group yourselves**

---

Spreadsheets encompass a lot of the things we need
to be able to do as researchers. We can use them for:

- Data entry
- Organizing data
- Subsetting and sorting data
- Statistics
- Plotting

---

In this lesson, we’re going to talk about:

1. [Formatting data tables in spreadsheets](01-format-data.html)
2. [Formatting problems](02-common-mistakes.html)
3. [Dates as data.](03-dates-as-data.html)
4. Basic quality control and data manipulation in spreadsheets.
5. [Exporting data from spreadsheets.](05-exporting-data.html)
6. [Data export formats caveats](06-data-formats-caveats.html)
8. [Functions](07-functions.html)
9. [Regular Expressions](08-regular-expressions.html)
10. [iDigbio Portal Exercise](09-iDigBio-portal.html)

Next: [Formatting data tables in spreadsheets.](01-format-data.html)
