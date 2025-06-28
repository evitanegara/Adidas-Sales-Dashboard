# Adidas Sales Analysis Dashboard

## Project Background

This project analyzes Adidas sales performance across retailers, regions, and product categories using an interactive Power BI dashboard. It delivers visual insights into product trends, geographic performance, and sales channel efficiency to support data-driven decisions in marketing, merchandising, and supply chain planning. From identifying top-selling products by region to tracking seasonal sales peaks and evaluating sales methods, the dashboard balances high-level overviews with detailed transaction-level insights.

---

## Dataset Overview

The dataset contains transactional-level records with the following structure:

| Column            | Description                                        |
|-------------------|----------------------------------------------------|
| Retailer          | Name of the retailer selling Adidas goods          |
| Retailer ID       | Unique identifier for each retailer                |
| Invoice Date      | Transaction date                                   |
| Region            | Geographic region (e.g., Northeast, West)          |
| State             | U.S. state where the transaction occurred          |
| City              | City where the transaction occurred                |
| Product           | Product category                                   |
| Price per Unit    | Unit price of the product                          |
| Units Sold        | Quantity sold                                      |
| Total Sales       | Total revenue from the transaction                 |
| Operating Profit  | Profit from the sale                               |
| Operating Margin  | Profit margin in percentage                        |
| Sales Method      | Sales channel (In-store, Online, Outlet)           |

> Power BI was used for data modeling, cleaning, and visualization.

---

## Executive Summary

The Adidas Sales Dashboard analyzes **$899.9M** in total revenue from **2M units sold**, with an **operating profit of $332M**. Key sales are driven through in-store methods, with top-performing products being men's footwear. Geographically, the Northeast and West regions account for nearly half of the total revenue. This dashboard enables a deeper understanding of product and channel-level performance for data-driven retail decision-making.

---
## Visualizations
<p align="center">
  <img src="https://github.com/user-attachments/assets/53a8ef1b-1458-410b-b3da-28b8a4aa9870" alt="Adidas Sales Dashboard Page 1" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6fe03438-fee5-4360-92a8-7c26e640d809" alt="Adidas Sales Dashboard Page 2" width="700"/>
</p>



##  Insights Deep-Dive

### 1. Sales by Retailer and Product
- **West Gear** leads with **$243M**, driven by **Men’s Street Footwear ($53M)** and **Women’s Apparel ($47M)**.
- **Foot Locker** follows with **$220M**, with top sales in **Men’s Street Footwear ($57M)** and **Women’s Street Footwear ($36M)**.
- **Sports Direct** generates **$182M**, mainly from **Men’s Athletic Footwear ($39M)** and **Women’s Apparel ($37M)**.
- **Kohl’s** records **$102M**, led by **Women’s Apparel ($20M)** and **Men’s Street Footwear ($28M)**.
- **Amazon** and **Walmart** trail behind with total sales around **$78M** and **$75M** respectively.
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/c0952fbe-312e-4494-8296-ad225793febf" alt="Adidas Units Sold by Product" width="700"/>
</p>


### 2. Monthly Sales Trend
- **July** is the peak month at **$95M**, followed by **August ($92M)** and **December ($86M)**.
- **March ($57M)** and **February ($61M)** have the lowest sales.
- **October ($64M)** and **November ($68M)** are slightly below the annual average.
- Average monthly sales hover around **$75M**, with **May ($81M)** and **June ($75M)** just above the baseline.
<p align="center">
  <img src="https://github.com/user-attachments/assets/81883d88-13d3-460e-a876-c852144bec65" alt="Adidas Bottom States by Sales and Units" width="700"/>
</p>




### 3. Total Units Sold by Product
- **Men’s Street Footwear** tops with **593K units sold**.
- **Men’s Athletic Footwear (436K)** and **Women’s Apparel (434K)** follow closely.
- **Women’s Street Footwear (392K)** and **Women’s Athletic Footwear (317K)** also perform well.
- **Men’s Apparel** is the lowest-selling category at **307K units**.
<p align="center">
  <img src="https://github.com/user-attachments/assets/bf7a2c2b-8fe0-4cdc-be50-967676c05110" alt="Adidas State-Level Sales and Units" width="700"/>
</p>





### 4. Sales by Retailer and Sales Method
- **West Gear** leads with **$243M**, dominated by **in-store sales ($157M)**.
- **Foot Locker** shows a balanced mix: in-store, online, and outlet channels each contribute over **$70M**.
- **Sports Direct** and **Kohl's** rely heavily on **outlet sales** ($68M and $42M).
- **Amazon** is mostly **online-focused**, while **Walmart** shows low in-store and online figures but performs better in **outlet** ($43M).
<p align="center">
  <img src="https://github.com/user-attachments/assets/97471af7-7357-4f73-8bbb-6790de57eea9" width="700"/>
</p>



### 5. Sales by Region
- **West** has the highest sales at **$269.9M** (30% of total).
- **Northeast** follows with **$186.3M** (21%), together comprising nearly **half of total sales**.
- **Southeast ($163.2M)** and **South ($144.7M)** follow.
- **Midwest** records the lowest at **$135.8M** (15%).
<p align="center">
  <img src="https://github.com/user-attachments/assets/54d06db6-2b45-4d00-bca1-39866641006c" width="700"/>
</p>





### 6. Geographic Sales Overview
- **New York** leads with **$64.2M** in sales and **169K units sold**, followed by **California ($60.2M)**, **Florida ($59.3M)**, and **Texas ($46.4M)**.
- These four states account for a substantial portion of national sales and volume.
- **South Carolina ($29.3M)** and **Washington ($26.3M)** fall mid-range.
- **Nebraska ($5.9M, 19K units)**, **Minnesota ($7.4M)**, and **Iowa ($7.4M)** are the **bottom three states**, with sales under $8M and low unit volumes.
<p align="center">
  <img src="https://github.com/user-attachments/assets/47a57467-77ca-4ba4-ac3c-f705ed854eed" alt="Adidas Sales by Region" width="700"/>
</p>


---

##  Recommendations

### 1. Sales Channel Optimization
- **Reinforce In-Store Dominance:** Continue investing in in-store marketing, especially with top-performing retailers like West Gear and Foot Locker.
- **Strengthen Online Channels:** Boost digital sales for Amazon and Walmart through SEO, online exclusives, and targeted advertising.

### 2. Product Strategy
- **Double Down on Footwear:** Focus on best-sellers like Men’s Street and Athletic Footwear through bundles and seasonal drops.
- **Reposition Men’s Apparel:** Improve performance via pricing adjustments or refreshed marketing campaigns.

### 3. Regional Expansion
- **Scale High-Yield Markets:** Allocate more resources to the **West** and **Northeast**, which drive nearly half of total revenue.
- **Lift Midwest Presence:** Run local campaigns or expand distribution in underperforming Midwest states.

### 4. Seasonal Campaigns
- **Capitalize on Peak Months (July & December):** Align promotions and launches with periods of high demand.
- **Stimulate Low Months (March & October):** Use targeted discounts or new product releases to drive traffic.

---

##  Contact

For questions, collaboration, or dataset access, feel free to reach out:

**Evita Negara**  
evitanegara@gmail.com
