# Retail-Analytics-Customer-Intelligence-Dashboard
## 1. Sales Page

<img width="1321" height="752" alt="image" src="https://github.com/user-attachments/assets/eafd3509-ee89-4a3e-901a-1dd9c9353dab" />

the purpose of this page is to tell users How Sales Are doing, it shows Sales by time (year/Quarter/month)
and The Average Delivery Time in Days and Some Important Kpis along with its (YOY) Value Like :
- Total Sales
- Number of Customers
- Profit Margin
- Average Delivery Time
- Average Order Value
- Number of Orders
  
Not only that but it can Filter the sales by Stores or Countries that made that sales.

## 2. MBA Page
<img width="1269" height="690" alt="image" src="https://github.com/user-attachments/assets/1c7d4e96-8332-4de9-885e-d860e5707405" />


### Importance

Market Basket Analysis is a data mining technique that is used to uncover associations between products by identifying items that are frequently purchased together.
and this can be useful in different areas and scenarios :

- Cross-Selling & Bundling: If there is a customer that frequently buy a laptop with a laptop bag, or a smartphone with a case, businesses can create "Product Bundles" to increase **the Average Order Value (AOV)** . This is also an effective way to move slow-selling inventory.

- Store Layout Optimization: By placing associated products near each other, businesses can trigger impulse buys, ensuring that a customer who came for one item leaves with two.

- Recommendation Engines: For e-commerce platforms, these insights  may help in recommedning related products to what user may buy, potentially increasing sales.

- Loss Leader Strategy: Marketing teams can apply a "Loss Leader" tactic offering a deep discount on a high demand product to rank higher in price filters in websites, While the profit on that item is low, the business recovers the margin through the associated products the customer buys alongside it.

- Inventory & Supply Chain Planning: If a core product is restocked, its associated items should be restocked in tandem to avoid missed sales opportunities.

### Implementation

- We have 2 main Visuals One that represent the Baskets (group of items) that are bought, and the other is the products that are bought in these baskets
- Now a user can determine how frequently a basket is sold and the **ATV** of that basket and choose a product and the basket that contains this products will appear
- the color represent the margin green is high , orange is medium, red is low
- also the products are displayed by their IDs as their names are long but the name of the product and basket products appear in the tool tip 

**Note** on Methodology: While I have successfully implemented this analysis using Power BI for visualization, it is worth noting that these kinds of analysis are better using progrmming language like R/Python as Statistical methods will be used and the result will be accurate as they ensure that associations are mathematically significant and not just coincidental.
## 3. RFM Page

<img width="1324" height="723" alt="image" src="https://github.com/user-attachments/assets/82b83e0b-9d38-4925-9580-99f78504440c" />


### Importance

RFM is a customer segmentation technique that categorizes customers based on three keys :

- Recency: How long has it been since the customer’s last purchase?
- Frequency: How often does the customer purchase within a specific period?
- Monetary: How much total value has the customer spent?

By analyzing these three factors, we can identify high-value segments and those at risk:

- Best Customers (Champions): These are customers who shop frequently, spend the most, and have purchased very recently.

- At-Risk Customers: These are customers who used to buy frequently and spend large amounts, but haven't returned in a long time.
- Identifying this group is vital for re-engagement and retention strategies.

### Implementation
The user Can see some Kpis with (YOY) for all segment (and can filter by segment) like :
-  total sales for all segments (can filter by a specific segment)
-  Average Recency (in days) for the customers of the current year.
-  Average Monetary (in days) for the customers of the current year.
-  Average Frequency (in days) for the customers of the current year.


Also the user can see these Kpis for a specific segment, and can see segments By (Store, Country of customers, year).

The user can also view the sales and customer count across (years/Quarters/Months).
## 4. Data Model 

<img width="1080" height="623" alt="image" src="https://github.com/user-attachments/assets/0468a24f-73a9-46a1-ae22-178ff78344c6" />




