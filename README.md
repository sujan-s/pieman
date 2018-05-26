# PIEMan — A Personal Income and Expenditures MANager built on Google Sheets.
#### v0.3.0beta, more changes in the coming week.

#### Changelog
v0.3.0 — Removed shortcodes, categories are now selectable via dropdown.

I have tried a zillion apps that promise to help me track my expenses— some read my texts, some I have to enter manually, some ask for access to my bank details. But they all have one shortcoming or the other, and so I ended my creating my own system.

Please click to see a larger version
![PIEMan](https://i.imgur.com/jIEePJr.png)

### First, get the file here: https://docs.google.com/spreadsheets/d/1JaT_RbjUC5_0Gr5IoyBlk1PvugIJ3G1wiVdNkZSUqgw/edit?usp=sharing

**The file is comment-only, so go to File > Make a copy, and save it to your Google Drive. Now you can make edits.**

----
## How to use

### Getting started
PIEMan works one file per year, and each file has 14 sheets— one main Insights page that displays collated info from other sheets, one page to maintain your expense categories, and 12 individual sheets, one for each month. Basically, you can manage all your expenses, one file per year. For 2019, duplicate this file, and simply delete the data and start afresh.

Right now, there are thirty basic categories to classify your expenses, which you can see in the CATEGORIES sheet.

### Adding an expense
![Adding an expense](https://imgur.com/download/Sz3Vq1d)

Dates are displayed vertically, with the day's total, and then the list of expenses for that day. To add an expense, simply add a category, the description and finally, the amount in the cell below that.

For an expense, please add a minus '-' before the amount value. For an *income*, just don't add the minus. This is so that PIEMan knows what to deduct and what to add.

As you can see, the day's total(All incomes minus all expenditures) is diplayed in column-B, and the month's total(Sum of all values in column-B) in F1. 

Scroll past the dates, and you will see a breakdown of all expenses that month, broken down by category. PIEMan scans the sheet for all the cells containing a particular shortcode, and picks up all the amounts under that category, and adds them all up. Nifty, huh?
