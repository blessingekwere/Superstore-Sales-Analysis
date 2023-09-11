# Superstore-Sales-Analysis

![](https://github.com/blessingekwere/Superstore-Sales-Analysis/blob/main/Superstore%201.jpg)
Photo Source: Google

## Introduction
In the dynamic landscape of retail, the pursuit of profitability is an ever-present challenge for business managers. The ability to identify and fortify weak areas within an operation can often be the difference between success and stagnation. In this context, we delve into the world of the Superstore, a thriving retail entity. The Superstore has entrusted us, as business managers, with the critical task of scrutinizing its sales data to pinpoint those elusive weak links that, once fortified, can pave the way for enhanced profitability.

![](https://github.com/blessingekwere/Superstore-Sales-Analysis/blob/main/Superstore%202.jpg)
Photo Source: Google


## Aim of the project
Our aim in this comprehensive analysis report is two-fold. Firstly, we seek to unearth the hidden challenges within the Superstore's sales operations, be they in product categories, customer segments, geographical regions, or operational processes. These challenges may manifest as underperforming product lines, untapped market segments, or inefficiencies in the supply chain.

Secondly, our aim is to provide actionable insights and strategic recommendations. Armed with these insights, the Superstore's management can embark on a journey of improvement, addressing weaknesses, optimizing strengths, and ultimately fostering an environment conducive to greater profitability.

## Objective of the project

Identify Weak Areas: Our primary objective is to diligently identify and scrutinize areas within the Superstore's sales ecosystem where performance falls short of its full potential. This includes analyzing sales by category, subcategory, customer segment, geographical region, and operational efficiency.

Provide Strategic Insights: Building upon our findings, we aim to provide strategic insights that shed light on the root causes of weaknesses. This entails uncovering underlying factors contributing to suboptimal performance and understanding their implications.

Recommendations for Enhancement: Based on our analysis, we will formulate a set of actionable recommendations. These recommendations will serve as a roadmap for the Superstore to address identified weak areas, maximize profitability, and achieve sustainable growth.


## Data Sourcing
The dataset was gotten from [here](https://bit.ly/3i4rbWl)

## Data Preprocessing and Cleaning
After downloading the dataset to my local computer, I opted to utilize Power BI as the primary tool for this project. Although the dataset was reasonably clean, ensuring its suitability for further analysis necessitated several data preparation steps, which were accomplished using Power Query Editor for data transformation.

Data Loading and Initial Transformation: 
* I initiated the process by importing the data into Power BI as a CSV file using the "Get Data" command.

* Subsequently, I accessed Power Query Editor by clicking on the "Transform" button to facilitate data transformation.

* Data Quality Assessment: To ensure data integrity, I conducted a thorough examination of each column individually. This involved scrutinizing for potential issues such as missing values, incorrect formatting, duplicates, null values, and spelling errors.

* Data Formatting and Integration: Following the assessment, I proceeded to format all the columns in their appropriate formats to maintain consistency and data accuracy.
The formatted dataset was then integrated into Power BI Desktop for further analysis.

* KPI Calculation: To derive specific Key Performance Indicators (KPIs) essential for the analysis, I harnessed the capabilities of calculated measures. These DAX (Data Analysis Expressions) calculations were employed to generate meaningful insights that would be featured prominently in the analysis.

This meticulous data cleaning and preprocessing stage ensured that the dataset was primed for analysis, promoting the accuracy and reliability of subsequent findings and insights in this project.

## Dashboard

![](https://github.com/blessingekwere/Superstore-Sales-Analysis/blob/main/Superstore%20Analysis-1.jpg)
Sales Dashboard

![](https://github.com/blessingekwere/Superstore-Sales-Analysis/blob/main/Superstore%20Analysis-2.jpg)
Profit Dashboard

You can click [here](https://app.powerbi.com/view?r=eyJrIjoiODRmMzhiOWEtOTk4NS00ZjhhLTg3Y2QtYzEzOGRhNGY2MjFlIiwidCI6IjMwMDM2MmQ4LTZkNmItNGY5ZC04YjQwLTUwZjhkNjkxNmVjZCJ9) to view the interactive dashboard.

## Insights
#### Sales Analysis
  
* Category Sales Comparison: Technology emerged as the top-performing category with total sales of $836,154.03, surpassing Office Supplies by 16.29% (Office Supplies had sales of $719,047.03). The breakdown of top categories includes Technology at $836,154.03, Furniture at $741,999.80, and Office Supplies at $719,047.03. Technology contributed to 36.40% of total sales.
 
* Top Subcategories: Among the top 5 subcategories by total sales, Phones led with $330,007.05 in sales, outperforming Binders by 62.24% (Binders had sales of $203,412.73). Phones represented 25.53% of total sales, with sales ranging from $203,412.73 to $330,007.05 across all 5 subcategories.
  
* Consumer Segment Sales: The Consumer segment generated the highest sales, totaling $1,161,401.35, followed by Corporate at $706,146.37 and Home Office at $429,653.15. Consumer accounted for 50.56% of total sales.
  
* Shipping Mode Comparison: Standard Class shipping mode recorded the highest sales at $1,358,215.74, surpassing Same Day by a significant margin of 958.10% (Same Day had sales of $128,363.13). The top shipping modes were Standard Class, Second Class, First Class, and Same Day, with Standard Class contributing to 59.12% of total sales.
  
* Regional Sales Analysis: The West region achieved the highest sales, totaling $725,457.82, followed by the East region with $678,781.24. The Central region recorded sales of $501,239.89, while the South region reported sales of $391,721.91.

#### Profit Analysis
* Category Profit Comparison: Technology also led in terms of profit, generating $145,454.95, which was 688.32% higher than Furniture's profit of $18,451.27. The top categories by profit were Technology at $145,454.95, Office Supplies at $122,490.80, and Furniture at $18,451.27. Technology contributed 50.79% of the total profit.

* Top Subcategories by Profit: Copiers stood out with the highest profit at $55,617.88, surpassing Binders by 84.03% (Binders had a profit of $30,221.48). Copiers represented 26.95% of the total profit, with profits ranging from $30,221.48 to $55,617.88 across all 5 subcategories.

* Profit by Consumer Segment: The Consumer segment generated the highest profit, totaling $134,119.21, followed by Corporate at $91,979.13 and Home Office at $60,298.68. Consumer contributed to 46.83% of the total profit.

* Shipping Mode Profit Comparison: Standard Class shipping mode recorded the highest profit at $164,088.79, surpassing Same Day by 932.54% (Same Day had a profit of $15,891.76). The top shipping modes by profit were Standard Class, Second Class, First Class, and Same Day, with Standard Class contributing to 57.29% of total profit.

* Top Profitable States: The top 3 states by profit were California with $76,381.39, New York with $74,038.55, and Washington with $33,402.65.

This analysis provides valuable insights into sales and profit performance across different categories, subcategories, consumer segments, shipping modes, regions, and states within the superstore dataset.



## Recommendation

#### Sales Improvement Recommendations:

* Category Promotion: Given that Technology products have the highest sales, consider promoting and expanding the product range within the Technology category. This can include introducing new tech products, offering bundles, or running targeted marketing campaigns.

*	Subcategory Focus: Concentrate on the top-performing subcategories such as Phones. Develop marketing strategies to highlight these subcategories, improve product visibility, and potentially introduce complementary products or accessories to boost sales.

*	Consumer Segment: As the Consumer segment contributes the most to sales, invest in understanding consumer preferences and behavior. Tailor marketing campaigns, discounts, and loyalty programs to cater to the needs and preferences of this segment.

*	Regional Strategies: Explore opportunities to increase sales in regions with lower performance, such as the Central and South regions. This could involve localized marketing, partnerships with local businesses, or adjusting product offerings to align with regional preferences.

*	Shipping Mode Optimization: Since Standard Class is the dominant shipping mode, optimize the shipping process to improve delivery times and customer satisfaction. Consider offering additional shipping options, such as same-day delivery, for customers willing to pay extra for faster service.


#### Profitability Improvement Recommendations:

*	Profitable Category Expansion: While Technology is the top-performing category in terms of profit, consider expanding the product range within this category, especially focusing on high-margin products. Additionally, explore opportunities for cost optimization within this category.

*	Subcategory Profit Maximization: Continue to promote high-profit subcategories like Copiers and identify ways to increase sales further. This could involve bundling related products, offering maintenance plans, or targeting B2B customers.

*	Consumer Segment Profitability: Focus on increasing profitability within the Consumer segment by optimizing pricing strategies, cross-selling high-margin products, and implementing effective cost management practices.

*	Shipping Mode Cost Control: Review and optimize the costs associated with different shipping modes, especially Same Day, to ensure profitability. Implement cost-effective shipping solutions without compromising on service quality.

*	Geographical Profit Focus: Concentrate on states with the highest profitability, such as California and New York. Consider expanding market share in these regions through targeted marketing and promotion of high-margin products.

*	Inventory Management: Implement efficient inventory management practices to minimize carrying costs and reduce the risk of overstocking or understocking. Utilize data analytics to forecast demand accurately.

*	Customer Retention: Implement customer retention strategies to encourage repeat purchases and increase customer lifetime value. Loyalty programs, personalized recommendations, and excellent customer service can help achieve this.

*	Operational Efficiency: Continuously evaluate and improve operational processes to reduce operational costs. Streamline supply chain management, optimize warehouse operations, and invest in technology solutions that enhance efficiency.

It's important to note that these recommendations should be implemented in a strategic and data-driven manner. Regularly monitor the impact of changes, gather feedback from customers, and adapt strategies as needed to achieve sustainable growth in sales and profitability for the superstore.


#### Overall Business Recommendations:

*	Data-Driven Decision-Making Culture: Foster a data-driven culture within the organization. Ensure that data analysis and insights are integrated into decision-making processes at all levels. Provide training and resources to empower employees to make informed decisions based on data.

*	Category and Subcategory Optimization: While Technology and Phones are performing well, continue to optimize product offerings within these categories. Monitor market trends and customer preferences to introduce innovative products and stay ahead of the competition.

*	Customer-Centric Approach: Place a strong emphasis on understanding customer needs and preferences. Conduct regular customer surveys and gather feedback to tailor product offerings, pricing strategies, and customer experiences to align with customer expectations.

*	Regional Expansion Strategy: Explore opportunities for expansion into regions with untapped potential. Conduct market research to identify regions with high growth potential and develop targeted expansion plans. Leverage local partnerships and marketing campaigns to gain a foothold in new markets.

*	Supply Chain Efficiency: Invest in supply chain optimization to reduce operational costs and improve product availability. Implement advanced inventory management systems, optimize shipping routes, and explore opportunities for bulk purchasing to achieve cost savings.

*	Profitability Maximization: Continue to focus on high-margin products and subcategories, such as Copiers. Identify cross-selling opportunities and upsell premium products to increase overall profitability. Implement effective cost control measures in all aspects of the business.

*	Customer Retention and Loyalty: Implement customer retention strategies to foster long-term customer relationships. Develop loyalty programs, personalized marketing initiatives, and exceptional customer service to incentivize repeat business and increase customer lifetime value.

*	Operational Efficiency: Regularly assess and streamline operational 

## Conclusion

In conclusion, our analysis of the superstore's sales and profit data has provided valuable insights into its performance across various categories, subcategories, customer segments, shipping modes, regions, and states. These insights offer a clear picture of what is working well and where opportunities for improvement lie.

By leveraging these insights and implementing the recommended strategies, the superstore can drive growth in both sales and profitability. A data-driven approach, customer-centricity, efficient operations, and a focus on high-margin products are key pillars to achieve sustainable success in a competitive market.

The superstore is well-positioned to not only meet but exceed customer expectations while optimizing its business operations. With a commitment to continuous improvement and adaptability to changing market dynamics, the superstore can navigate challenges and thrive in the ever-evolving retail landscape.

Thank you for reading. Your comments, suggestions and recommendations will be highly appreciated

Kindly comment with me on [Twitter](https://twitter.com/Eddie_Gregs?t=dF3996shVxvPJTePTtxDdw&s=09) and [LinkedIn](www.linkedin.com/in/blessing-ekwere-857326216)

See you next time🙂
