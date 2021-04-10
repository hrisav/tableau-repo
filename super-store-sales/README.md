# Super Store Sales Dashboard

About Dataset
--

The Superstore dataset has details of 9994 orders of products purchased across US. It also has quantities purchased, Selling Price, Profit, Discount. The products are subdivided into Categories and Sub-Categories.

Findings
--

<img src="super-store-sales/images/store1.JPG" width="700">

**Sub-category wise: Profit vs Sales**

* Phones and Chairs have got the maximum sales.
* Point of concern is Tables where even though the sales is fourth largest, it's the most loss making.
* Profit to Sales ratio for Copiers is very encouraging.

**Region wise: Profit vs Sales**

* In terms of Profit vs Sales, West is performing best while Central is doing worst.
* Need to do detailed study to understand what are the factors which are pulling down the profit of Central compared to others.

**Sub-category wise: Sales Growth over Years**

* We are comparing Jan 2014 data vs Dec 2017 data to understand growth of Sales across Sub-categories.
* Sales of Chairs have taken the maximum jump during that period.
* There's not been much sales for products like Fasteners, Envelopes, Labels.

**Sub-category wise: Sales vs Avg Discount**

* Binders - getting highest discount, but not getting highest sales. So product getting high discount, doesn't mean will give high sales.
* Chairs and Phones have highest sales, which have average discount of around 15%.

<img src="super-store-sales/images/store2.JPG" width="700">

**State wise: Profit vs Sales**

* Bubble size talks about Sales, and Colour talks about Profit.
* New York, California - high on sales, high on profit.
* Texas - high on sales, but not profit making. So need to drill down to understand which cities and which products are pulling down the profit in Texas.

**Sub-category wise - Profit Percent**

* Box plot shows individual transactions profit percent for each sub-category.
* If we compare Art and Appliances, Art has high variance, while Appliances has lot of outliers, bigger IQR. Need to understand which transactions pulled the profit percent down for Appliances as it is generally profit making.

**Category wise: Yearly Profit and Sales**

* Products under Technology category are most profitable.
* Furniture has been doing poorly. Even though sales have increased from 2014 to 2015 and from 2016 to 2017, profit has gone down, which is a point of concern.
