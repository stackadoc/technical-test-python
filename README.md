# Welcome

We are very cheerful that you have chosen to join us. The objective of this test is to understand your technical abilities and your code practices. If you are stuck, feel free to send us an email and we will be very happy to help you.

# Instructions

All the code must be made with Python 3.

You can't fork this project. You don't want to share your work with other candidates ;) Just send us the link to your github when you are done. 

## I. Watson's Wine scraping
Go to the Watson's Wine shop (https://www.watsonswine.com/) and download all the **champagne** offers (use the search input on the top left corner). For each offer, we need these fields:
* title
* final price
* if there is a special offer, the full price without promotion
* URL of the picture
* URL of the product page
* information about the stock or the lack of stock
Store the result in a CSV file.

## II. Instacart scraping
Go to Instacart marketplace (https://www.instacart.com/), select the address "601 Diamond St, San Francisco, CA 94114" on **delivery** then select the **Safeway** shop. Download all the **champagne** offers (same data as the previous exercise) and store it in a CSV file.

This exercise is much more difficult than Watson's Wine. Don't worry if you can't get all the products. The help of an headless browser (like Selenium) is very recommended.

## III. Data analysis
Use the Watson's Wine data and extract these information from each product :
* Height and width of the picture (in pixels).
* Vintage of the champagne (year of production). If it's not specified, just leave the field empty.
* The type of product: is it a glass or an actual bottle of champagne ? Multiple solutions are welcome. If you can't manage to code them, pseudo-code solutions are accepted.
