
# Plug Tech E-Commerce Performance Analysis

## Company Overview

<p align="center">
  <img src="pic/Company%20logo2.png" alt="Company Logo" width="600">
</p>

**Plug Tech**, founded in 2018, is a global e-commerce retailer specializing in consumer electronics products. The company sells popular brands such as Apple, Samsung, and Lenovo through its online platform and serves customers across multiple regions including North America, Europe, Middle East & Africa, Asia-Pacific, and Latin America. 

Between **2019 and 2022**, Plug Tech experienced rapid growth in order volume and product demand, supported by multiple marketing channels such as direct traffic, email marketing, social media, and affiliate partnerships. To strengthen customer retention and encourage repeat purchases, the company also introduced a **loyalty program** in 2019.

As the business expands, management aims to better understand sales performance, customer behavior, and operational challenges across products and regions.


<details open>
<summary><strong>Business Context & Problem Statement</strong></summary>
<br /> 
Despite strong growth, Plug Tech began to observe uneven business performance across markets and customer segments.

While order volume remained high, leadership identified several concerns:

- Revenue fluctuations across years despite increasing transaction volume
- Heavy dependence on a small number of products and regions
- Unclear effectiveness of marketing channels in attracting high-value customers
- Uncertainty around whether the loyalty program was generating meaningful business value
- Potential operational inefficiencies affecting customer experience

</details>



<details open>
<summary><strong>Stakeholder Questions</strong></summary>
<br /> 

1. How is the business performing over time?
2. Did the loyalty program contribute to stronger customer value and purchasing behavior?
3. Which products contributed most to sales performance across markets?
4. Which marketing channels attracted the most valuable customers?
  
</details>


<details>
<summary><strong>Data Structure & ERD</strong></summary>
<br /> 
Plug Tech's database structure consists of four tables: orders, customers, geo_lookup and order_status, including near 88,000 customers and over 108,000 transactions.
<br /> 
<img src="pic/ERD.png" alt="ERD" width="700">
</details>

## Executive Summary

<img src="pic/Revenue%20Growth.png" alt="Revenue Growth" width="800">

## Key Insights

### Time-Based Sales Trends

#### A. Yearly Trend

<img src="pic/Growth%20Trend.png" alt="Growth Trend" width="900">

- The company experienced strong growth in 2020, where revenue increased significantly from **$3.9M to $10.2M**, supported by both higher order volume and AOV. This suggests that the business was not only acquiring more customers, but also generating higher-value transactions, likely driven by stronger demand or a favorable product mix.

- In 2021, order count continued to grow and reached its highest level at **35,858** orders. However, despite this increase in transaction volume, total revenue declined by **10%**, while AOV fell from **$300 to $255**. This indicates that business growth became increasingly volume-driven rather than value-driven. Customers were still purchasing, but they were spending less per order, which may suggest a shift toward lower-priced products, reduced premium sales, or changing customer purchasing behavior.

- By 2022, the business showed a significant slowdown. Revenue dropped by **46%**, order volume declined by **40%**, and AOV returned to **$230**, matching 2019 levels. This suggests weakening demand and reduced transaction quality. This may indicate a broader contraction in business performance that warrants further investigation into customer retention, product mix, or market conditions.



#### B. Monthly Trend

<img src="pic/Monthly%20Trend.png" alt="Monthly Trend" width="900">






**December** consistently generating the highest revenue ($2.85M) and highest order volume (10,791 orders). This strongly suggests a holiday-driven demand cycle. 

**November** also showed strong recovery, with revenue growth of 18% and order growth of 24%, reinforcing that Q4 is the company’s most important commercial period. From a business standpoint, Plug Tech appears highly dependent on year-end sales momentum, meaning inventory planning, fulfillment capacity, and marketing investment during Q4 are likely critical to annual performance.
  
**September–October** showed strong transaction quality, even if not always the highest volume months. AOV peaked in October ($272) and remained strong throughout the fall season. This indicates that customers may purchase higher-value products during this period, possibly premium electronics or larger-ticket items. For the business, fall appears to be a high-value sales window, not just a high-volume one.

**February** was the weakest-performing month, with the lowest revenue ($1.91M) and significant declines in both revenue (-25%) and orders (-27%). This suggests a post-holiday demand drop, which is common in e-commerce after peak seasonal spending. 

Similarly, **October** showed an unusual contradiction: it recorded the highest AOV, but one of the lowest order counts (7,212) and the sharpest monthly declines in revenue (-28%) and orders (-29%). This indicates fewer but higher-value purchases, suggesting revenue was supported by premium transactions rather than broad customer demand.


#### C. Seasonal Trend

- Plug Tech showed moderate seasonal variation. Revenue, refund rates and broader regional performance remained relatively stable, suggesting that seasonality had limited impact on customer refund behavior and geographic demand patterns.

- **Winter** was still the strongest-performing season, generating the highest revenue ($7.32M) and order volume (28,039), suggesting increased customer demand during year-end periods, likely influenced by holiday shopping and promotions.

- **Autumn** generated the highest-value transactions. recorded the highest AOV at $266.38 despite having the lowest order count, indicating stronger revenue efficiency and a higher-value product mix during this period.

### Regional Performance

- North America was Plug Tech’s strongest-performing region, contributing 52% of total revenue and over half of total orders. While this highlights strong market demand, it also creates geographic concentration risk. To improve long-term stability, Plug Tech should reduce overreliance on North America by expanding growth efforts in underpenetrated markets such as APAC and LATAM.

- Regional performance was primarily driven by order volume rather than customer spending behavior. Although average order value (AOV) remained relatively stable across regions, North America and EMEA generated significantly higher sales due to stronger transaction volume. This suggests that improving customer acquisition and market penetration in lower-volume regions such as LATAM and APAC may support more balanced long-term growth.

- LATAM showed the weakest commercial performance across all regions, contributing only 6% of total revenue while recording the lowest order volume and AOV. This may indicate lower market penetration or weaker customer demand. To support long-term growth, Plug Tech could evaluate targeted expansion strategies and localized marketing efforts to strengthen performance in this underdeveloped market.

- Regional performance varied across markets. Although Japan contributed a smaller share of total revenue, it recorded the highest average order value (AOV), indicating stronger per-transaction customer value. This suggests that Plug Tech may benefit from strengthening premium product positioning and targeted growth strategies in high-value markets such as Japan.
### Loyalty Program






