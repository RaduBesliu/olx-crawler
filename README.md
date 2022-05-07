# OLX Crawler

## Description
OLX Crawler, as the name suggests, is a crawler for the popular website OLX, where users list items/services for different prices.<br>
This application searches through the listings of a given category. The name, description and price of each item is written in a file.<br>
Then, the text written in the file is matched against 10 regex categories ( with corresponding subcategories ), incrementing specific counters.<br>
A JSON object containing all the counters is created and passed to the server. The front end makes a GET request and displays the information.

## Technologies
1. Front End
    - HTML
    - CSS
    - Javascript
2. Back End
    - Node.js
    - Python
3. Additional Libraries
    - React
    - BeautifulSoup
    - lxml
    - axios
