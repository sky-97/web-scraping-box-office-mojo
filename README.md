# web-scraping-box-office-mojo

## Overview
Access the HTML of the webpage and extract useful information/data from it. This technique is called web scraping or web harvesting or web data extraction.


## Steps involved in web scraping:

* Send a HTTP request to the URL of the webpage you want to access. The server responds to the request by returning the HTML                content of the webpage. For this task, we will use a third-party HTTP library for python requests.
* Once we have accessed the HTML content, we are left with the task of parsing the data. Since most of the HTML data is nested,  we cannot extract data simply through string processing. One needs a parser which can create a nested/tree structure of the HTML data.
* There are many HTML parser libraries available but the most advanced one is html5lib.
 # Steps involved in web scraping:
* Step 1: Installing the required third-party libraries
          * BeautifullSoup
          * sqlite3
          * requests


Steps involved in web scraping:

    Send a HTTP request to the URL of the webpage you want to access. The server responds to the request by returning the HTML content of the webpage. For this task, we will use a third-party HTTP library for python requests.
    Once we have accessed the HTML content, we are left with the task of parsing the data. Since most of the HTML data is nested, we cannot extract data simply through string processing. One needs a parser which can create a nested/tree structure of the HTML data.
    There are many HTML parser libraries available but the most advanced one is html5lib.
    Now, all we need to do is navigating and searching the parse tree that we created, i.e. tree traversal. For this task, we will be using another third-party python library, Beautiful Soup. It is a Python library for pulling data out of HTML and XML files.

Step 1: Installing the required third-party libraries

    Easiest way to install external libraries in python is to use pip. pip is a package management system used to install and manage software packages written in Python.
    All you need to do is:


