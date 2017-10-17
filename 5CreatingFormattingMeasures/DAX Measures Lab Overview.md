> In this lab, you will write several DAX expressions to create measures to be used to analyze VanArsdel’s sales data. Specifically, you will create the following measures:

*	Total Sales: calculates the total sales.
*	LY Sales: calculates last year sales.
*	Sales Var: calculates sales variance between this year and last year sales.
*	Sales Var %: calculates sales variance between this year and last year sales in percentage.
*	YTD Sales: calculates YTD sales.
*	LY YTD Sales: calculates last year YTD sales.
*	YTD Sales Var: calculates sales variance between this year and last year YTD sales.
*	YTD Sales Var %: calculates sales variance between this year and last year YTD sales in percentage.
*	Total VanArsdel Sales: calculates sales for VanArsdel manufactured goods.
*	% Sales Market Share: calculates the percentage of VanArsdel manufactured goods from the total sales.

## Scenario
VanArsdel is a company that manufactures and sells sporting goods. The company has offices in the United States (US) and several other countries. Its sales comprise of US sales and International sales. VanArsdel’s sales come from its owned manufactured products, as well as other manufacturers’ products.

In the previous modules, you successfully brought the US sales data from the SQL database and the International sales data from a collection of CSV files, to an Excel data model. Now, you will expand upon this as you start to analyze VanArsdel's worldwide sales. With this data model (provided below), you can easily create pivot tables to analyze the data, as shown in Module 3. However, you need to create additional measures to perform more advanced analysis with your data, which includes:
*	Comparing last year sales and last year year-to-date / YTD sales.
*	Comparing sales of VanArsdel's manufactured goods to other manufacturers.

