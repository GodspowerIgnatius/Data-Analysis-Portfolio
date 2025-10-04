### Project Overview

This project analyzes e-commerce perfume listings (2,000 products: 1,000 men’s and 1,000 women’s) to uncover pricing patterns, availability trends, brand performance, and customer preferences. Using Power BI, I built an interactive dashboard that highlights sales performance across gender, regions, brands, and price categories to provide actionable insights for business decisions.

### Tools Used
* Power BI
* DAX (for calculated measures)
* Data cleaning in Power Query

### Steps
* Appended men’s and women’s perfume datasets (sourced from eBay).
* Cleaned data by handling nulls in *Sold* and *Last Updated*, standardizing availability values, and creating derived columns (Price Buckets, Gender, Date).
* Created DAX measures for **Total Revenue, Total Sold, Average Price, % Sales by Price Bucket**, etc.
* Designed a two-page interactive dashboard with KPIs and slicers (Date, Gender, Region, Price Bucket).

### KPIs
* Total Listings: 1,999
* Total Sold: ~12,000 units
* Total Revenue: $50M+
* Average Price: $38.50
* Availability: 12% of products out of stock
* Top Brands: Calvin Klein, Versace, Davidoff
* Top Locations: Hackensack, NJ (~$21M) and Dallas, TX (~$11M)
* Price Buckets: Majority of sales came from $20–$49 range (~67%), while premium perfumes ($100+) contributed less than 3% of sales.

### Recommendations
* Address Stock-Out Issues: Ensure faster replenishment for frequently out-of-stock products to prevent lost revenue.
* Leverage Top-Performing Brands: Strengthen partnerships with best-sellers (Calvin Klein, Versace, Davidoff) through bundles or exclusives.
* Focus on Sweet Spot Pricing ($20–$49): This range drives most sales; optimize marketing and inventory here while carefully testing premium offerings.
* Capitalize on High-Revenue Regions: Expand targeted ads and distribution in locations like Hackensack and Dallas.
* Investigate Revenue Spike (May 2024) A sharp spike in sales occurred; identifying its cause (promotion, event, bulk order) could inform future campaigns.
