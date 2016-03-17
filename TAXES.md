# How to do your taxes (in CT)

1. Prove you have health insurance.
2. Account for all of your non-taxed online orders (i.e. every Amazon.com order).

## Health Insurance

## Connecticut Use Tax

How to calculate your `use tax liability`:

### Amazon

  1. Log-in to Amazon.com.
  * Navigate to *Your Account* > *Your Orders*.
  * Select the year of taxation (e.g. `2015` from the order filter dropdown).
  * For each order on the page, click on its invoice link to download a .pdf document. If there are more than one page, repeat the process for each page.
  * Sum up the total order amount, including shipping and handling costs. Do this only for non-taxed orders. Then multiply the total by the `applicable sales tax rate` (e.g. `6.35%`).

Order Filter Dropdown:

```` html
<select name="orderFilter" autocomplete="off" id="orderFilter" tabindex="-1" class="a-native-dropdown">
    <option value="last30" id="orderFilterEntry-last30">
        last 30 days
    </option>
    <option value="months-6" id="orderFilterEntry-months-6" selected="">
        past 6 months
    </option>
    <option value="year-2016" id="orderFilterEntry-year-2016">
        2016
    </option>
    <option value="year-2015" id="orderFilterEntry-year-2015">
        2015
    </option>
    <option value="year-2014" id="orderFilterEntry-year-2014">
        2014
    </option>
</select>
````

Invoice Links:

```` html
<a class="a-link-normal" href="/gp/css/summary/print.html/ref=abcdefg?ie=UTF8&amp;orderID=100-0000000-0000000">Invoice</a>
````

Pagination:

```` html
<div class="a-text-center pagination-full">
  <ul class="a-pagination">
    <li class="a-disabled">←<span class="a-letter-space"></span><span class="a-letter-space"></span>Previous</li>
    <li class="a-selected"><a href="/gp/your-account/order-history/ref=oh_aui_pagination_1_1?ie=UTF8&amp;orderFilter=year-2015&amp;search=&amp;startIndex=0">1</a></li>
    <li class="a-normal"><a href="/gp/your-account/order-history/ref=oh_aui_pagination_1_2?ie=UTF8&amp;orderFilter=year-2015&amp;search=&amp;startIndex=10">2</a></li>
    <li class="a-last"><a href="/gp/your-account/order-history/ref=oh_aui_pagination_1_2?ie=UTF8&amp;orderFilter=year-2015&amp;search=&amp;startIndex=10">Next<span class="a-letter-space"></span><span class="a-letter-space"></span>→</a></li>
  </ul>
</div>
````

### Godaddy

 1. Log-in to godaddy.com
 * Navigate to *Visit My Account*.
 * Click *Account Settings* > *Order History*.
 * Click *Filter By* > *Date Range* then specify the first and last day of the year.
 * Click *Select All*.
 * Click *Export to CSV*.
 * Open the spreadsheet and sum up the total `Subtotal amount`.
