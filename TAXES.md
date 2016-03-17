# How to do your taxes (in CT)

1. Prove you have health insurance.
2. Account for all of your non-taxed online orders (i.e. every Amazon.com order).

## Health Insurance

## Connecticut Use Tax

How to calculate your use tax liability:

  1. Log-in to Amazon.com.
  * Navigate to *Your Account* > *Your Orders*.
  * Select the year of taxation (e.g. `2015` from the order filter dropdown).
  * For each order on the page, click on its invoice link to download a .pdf document.
  * Sum up the total order amount, including shipping and handling costs. Then multiply it by the applicable sales tax rate (e.g. 6.35%).

### Order Filter Dropdown

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

### Invoice Links

```` html
<a class="a-link-normal" href="/gp/css/summary/print.html/ref=abcdefg?ie=UTF8&amp;orderID=100-0000000-0000000">Invoice</a>
````
