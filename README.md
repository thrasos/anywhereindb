# anywhereindb

Comprehensive Search on MYSQL database

* Needle in a Haystack * 
* Comprehensive Search on MYSQL Database. *

select * from anywhereindb where anyfield like %search_text%
Sometime we need to find out a small piece of string in big Database. Like where is the configuration is saved, or where is Jon's Date of birth is saved. This code is search all the tables and all the rows and columns in a MYSQL Database. The code is written in PHP. For faster result, we are only searching in the varchar field. (if anyone needs to search in other field, he can just comment the varchar selecting part.)

This code is written to help out the web developers as tool.

### How To Install 
1. Download the anywhereindb.php
2. Drop it in your htdocs or www folder, and run it in your browser 
3. Give your Database connection information 
4. It's ready for work, search any string

###Working

Collapse All Result
This will hide all the search result, and show how many results are there in each table

###Expand All Result
This will show all the search result.

###SQL
This is will show/hide SQL query for the particular tables result.

###Result
This is will show/hide the particular tables result.

###Helpful for whom
searching a data in the database
understanding a new system
quickly find out a setting string in the database

#Don't forget to delete it if it's in a public folder.

Automatically exported from code.google.com/p/anywhereindb
