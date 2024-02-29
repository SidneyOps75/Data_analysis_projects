# Data_analysis_projects
## Introduction
Below you shall have a view of the data analysis  notes and projects. The projects will be contained in different files which will be demonstrated below. Anyone can use this as their roadmap in data analysis.
## Types of Variables
Categorical variables indicate membership in a particular group and have a discrete or specific qualitative value. They are further classified into two types:
   - Nominal - These are variables that consist of two or more discrete categories whose value is assigned based on the identity of the object. Examples are gender, eye color or type of animal.
   - Ordinal - These are variables that consist of two or more categories in which order matters in the value. Examples are student class rank (1st, 2nd, 3rd) or satisfaction survey scales (dissatisfied, neutral, satisfied).

Numerical variables are quantitative values:
  - Continuous - These are variables that are quantitative and can be measured along a continuum or range of values. There are two types of continuous variables: Interval variables can have any value within the range of values, and examples are temperature or time; Ratio variables are special interval variables where a value of zero (0) can mean that there is none of that variable and examples are income or sales volume.
  - Discrete - These types of continuous variables are quantitative but have a specific value from a finite set of values. Examples include the number of sensors activated in a network, or the number of cars in a lot.
## Static and streaming data
There are two types of data that analysts work with: static data and streaming data. Data that is received and stored prior to performing analysis on the data is considered static data. When each event is processed and analyzed as it is received and subsequent results are used or stored, the data is referred to as streaming data.
Consider data from a movie review site. A data analyst wants to categorize each viewer comment by whether it is positive or negative during the week a new movie was previewed. The analyst can treat the data as either static or streaming. If the data is going to be treated as static data, it will be stored in the database for later analysis at the end of the week. If it is going to be treated as streaming data, each entry in the comments will be analyzed as it is observed, in real-time. Often, the results of analysis of streaming data are represented as a continuously updated dashboard, or as input to an automated function.
## Structured file types
### Relational Databases
A relational database is a collection of tables with columns and rows that are connected by pre-defined relationships. These items are organized as a set of tables. Tables are used to hold information about the objects to be represented in the database. Each column in a table holds a certain kind of data, and each field in that column stores the actual value of an attribute.
### Logs 
Log files are a machine-generated historical record of everything and anything that happens within a system, such as transactions, errors, or intrusions. Log files are usually considered structured data, because they are machine-generated and so adhere to a standard format.
### Spreadsheets 
A spreadsheet file is an example of a flat file database. A flat file database stores records in a single file with no hierarchical structure. Spreadsheets are organized similarly to tables in a database, in that the data is organized into rows and columns, with related objects aligned either horizontally or vertically.
### Sensor readings 
Sensor output is usually collected in a standardized format, which may vary by manufacturer. Individual readings may be separated only by a delimiter or may be time dependent, such as 1 output per second, separated by timestamps.
### Transactional Records 
Records of transactions can be stored in many different formats, depending on the type of transaction and its source. Some transactions are entered manually into forms, while others can be machine generated.
## Unstructured Data
Unstructured data is raw data, not organized in a predefined way. It does not possess a fixed schema that identifies the type of data or its format. This type of data lacks a set way of entering or grouping the data, and then analyzing the data.
Examples of unstructured data include the content of photos, audio, video, web pages, blogs, books, journals, white papers, PowerPoint presentations, articles, email, wikis, word processing documents, and text in general
### Sources of unstructured data

### NoSQL Databases and Data Lakes
Unstructured data is often stored in non-relational databases or in data lakes, which are centralized repositories for data obtained from IoT devices, web sites, mobile apps, social media and other sources of raw data. These types of repositories are used to store real-time data in its original format. We will learn about NoSQL later in the course.
### Web Scraping
Web pages are created to provide data to humans, not machines. “Web scraping” tools automatically extract various forms of data from HTML pages. Typically, web scraping is an automated process which uses a bot or web crawler to gather and copy specific data from the web to a database or spreadsheet. The data can then be easily analyzed.
### Application Program Interfaces (APIs)
Many large web service providers, such as Facebook, provide standardized interfaces to collect data from them automatically, using APIs. The most common approach is to use RESTful application program interfaces (APIs). RESTful APIs use HTTP as their communication protocol and JSON files to store the data. Internet websites like Google and Twitter gather large amounts of static and streaming data. APIs for these sites allow data analysts and engineers to access subsets of the large amounts of data they are constantly generating.

## Formulas and Functions


Excel supports a wide range of formulas and function capabilities—the only difference between these is that functions use keywords and are predefined by Excel, while users can build custom formulas themselves using operators. There are strict rules to follow when creating formulas, so it is a good idea to plan out how you want the calculations to work before you start entering them into your spreadsheet.

First, the basics: all Excel formulas start with an equal sign (=). The equals sign indicates that the data in the cell is not text or a number, but a calculation. This ensures that your formula will not be displayed in the cell instead of the result of the calculation. For example, =1+2 entered into a cell (with the equals sign as the first character) will display the value 3, not the text =1+2.

## Relative and Absolute References

Calculations can be performed on either a constant, like the number 5, or the data contained at a specific location (usually a cell or range of cells). For example, the formula =L1/L7 divides the value in cell L1 by the value in cell L7.

Within a formula or function, when there are cell or range references, they can be either relative or absolute. A reference is relative when its value depends on the location of the reference itself, while an absolute reference refers to the same cell or range no matter where the reference appears. For example, when you did the Manipulate Data lab, you copied and pasted formulas from one row into the rows below it. When you did that, because the formulas had relative references, they used the values from the lower rows to make the calculations for those rows. This is the default behavior for formulas and functions.

If you want a formula to refer to the same cell or range of cells no matter where the formula is pasted, you can make the reference absolute by adding a dollar sign ($) before the column or row indicator for that reference. Let’s use the example referenced above, =L1/L7. If you wanted to use this formula in multiple places in your spreadsheet and always have it use the values in L1 and L7, rather than the values that correspond to the formula’s new location, you would write it as =$L$1/$L$7.

Both the column indication and the row indication can have this attribute, independently of each other, so you can also add the dollar sign to only the column reference or only the row reference.

## Functions

Built-in functions are formulas that start with a keyword that identifies a specific function to be performed. Most function keywords describe the calculation that the function will perform. Correct syntax varies by function, but usually has a similar pattern. For example, the syntax for the AVERAGE function accepts a range or list of cells to calculate the average of the values within the range, such as =AVERAGE(L2:L37) or =AVERAGE(L2, L5, L6).

Note: You must make sure to close all parenthesis and brackets, or you will receive an error message when you press enter to complete the entry. For long functions this can be difficult.

When you start a cell entry with an equal sign, as you type the function name, a menu of functions matching your entry will usually appear and show the short description of each function listed. If this doesn’t happen automatically, you can also right-click on a cell and enter the equals sign in the text field that says “Search the menus” to show this menu. Selecting the function that you want places the function name and an open parenthesis on the formula bar and in the cell








    



