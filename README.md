
<h1>1. Customers-segmentation-with-RFM </h1>

<h3>2. Packages Used to solve this problem </h3>

      a. import numpy as np
      b. import pandas as pd
      c. import matplotlib.pyplot as plt
      d. import seaborn as sns
      
<h3>3. Load the dataset   </h3>  
<h3>4. Understand the problem and objectives </h3>

        a. Shape of the dataset  (537979, 12)

<h3>5. Checking for missing values. </h3>

          CustomerID           133789
          Item Code                 0
          InvoieNo                  0
          Date of purchase          0
          Quantity                  0
          Time                      0
          price per Unit            0
          Price                     0
          Shipping Location         0
          Cancelled_status     529625
          Reason of return     537967
          Sold as set          537970
          
        a. Removed Cancelled Status, Reason of return and sold as set becouse they have more than 5 lakhs null values
        b. droped all null vlaues present in Customer ID.
 
 <h3>6. EDA </h3>
 
 <h3>7. Monthly Key Performance Indicator </h3>
 
 <h3>8. Monthly KPI Visualization </h3>
 
 
        a. Location countplot
 
 ![Alt Text](https://github.com/Aamir8539/Customers-segmentation-with-RFM/blob/main/location%20count%20plot.png)
 
        b. Monthly Price Line Plot
 
 ![Alt Text](https://github.com/Aamir8539/Customers-segmentation-with-RFM/blob/main/Monthly%20price.png)
 
        c. Monthly Aeverage Order Plot
 
 ![Alt Text](https://github.com/Aamir8539/Customers-segmentation-with-RFM/blob/main/Average%20order.png)
 
        d. Monthly Active Customers Line Plot
 
 ![Alt Text](https://github.com/Aamir8539/Customers-segmentation-with-RFM/blob/main/Monthly%20active%20costumers.png)
 
        e. Monthly Order Line Plot
 
 ![Alt Text](https://github.com/Aamir8539/Customers-segmentation-with-RFM/blob/main/Monthly%20order.png)
 
 
 <h3>9. RFM </h3>
 
 <h5> Recency - Given a current or specific date in the past, when was the last time that the customer made a transaction. </h5>
 <h5> Frequency - Given a specific time window, how many transactions did the customer do during that window. </h5>
 <h5> Monetary Value or Revenue - Given a specific window, how much did the customer spend. </h5>
 
 <h3>10. RFM Table with customers category </h3>
 
         customer_id   r_quartile	   f_quartile	    m_quartile	   score	  tier

        3015.0	          4	            4	            4	            12	    Gold
        2762.0	          3	            4	            3	            10	    Gold
        616.0	            3	            4	            4	            11	    Gold
        1033.0	          3	            3	            3	            9	      Gold
        2137.0	          4	            3	            3	            10	    Gold
 
        
        a. RFM Category
 
 ![Alt Text](https://github.com/Aamir8539/Customers-segmentation-with-RFM/blob/main/Tier%20histogram.png)
 
 
 <h3>11. Conclusion </h3>
 
         The work described in this ppt is based on a dataset providing details on purchases made on an 
         E-commerce platform over a period of 13 months. Each entry in the dataset describes the purchase of 
         a product, by a particular customer and at a given date. In total, approximately 4000 clients appear 
         in the dataset. Given the available information, i decided to group customers on the basis of RFM Score, 
         and made 3 categories. The most valuable customers are in Gold Category and leveled down to Silver and 
         Bronze.
         
 <h3>12. Insights </h3>
 
         1. After all the analysis I have come the conclusion that the company has to focus more on the customers who are categorized in Bronze category 
         2. For the Customers who are categorized in Bronze, the company should provide them exciting offers, discount coupons etc.
         3. To make the customers in Bronze to attract them for more purchases we can use close marketing strategies.
         4. For retaining the Customers in Gold we can provide them Premium account options.
         5. Loyalty cards, free trials, cash back offer, random rewards, for silver customers to encourage them to purchase frequently.
 
