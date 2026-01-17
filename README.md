[![Image](https://github.com/RakeshsarmaKarra/USA-Sales-Performance-Analysis-2014-2017-/blob/main/USA%20sales%20dashboard%20picture.jpg)](https://myunt-my.sharepoint.com/:u:/r/personal/rakeshsarmakarra_my_unt_edu/Documents/Sales%20Dashboard.pbix?csf=1&web=1&e=gNKJIZ)

## Project Overview
This interactive Power BI dashboard analyzes four years of sales data across the United States, providing actionable insights into regional performance, product category trends, and geographic profitability patterns. The analysis examines over 631,000 postal code records spanning multiple customer segments, shipping modes, and product categories to identify key business drivers and optimization opportunities.

### Tools & Technologies: 
Power BI Desktop, CSV Data Import, Custom Visual Integration (Heatmap by Weiwei Cui)

### Dashboard Link: [View Interactive Dashboard](https://myunt-my.sharepoint.com/:u:/r/personal/rakeshsarmakarra_my_unt_edu/Documents/Sales%20Dashboard.pbix?csf=1&web=1&e=b5xGsn)

### Business Context
Understanding where revenue is generated and how profitability varies across regions and product lines is fundamental to strategic decision-making. This analysis was designed to answer critical questions for stakeholders:

Which regions are driving the most profit, and where should we focus expansion efforts?

How are different product categories performing over time?

Are there geographic patterns in profitability that suggest market opportunities or challenges?

What trends can inform inventory planning and resource allocation?

### Data Exploration & Preparation
The dataset contains comprehensive sales transactions from 2014 to 2017, including:

4 shipping modes (Standard Class, First Class, Second Class, Same Day)

3 customer segments (Consumer, Corporate, Home Office)

4 geographic regions (West, East, Central, South)

3 product categories (Furniture, Office Supplies, Technology)

### Key metrics: 
Sales revenue, profit margins, quantity sold, discount rates

After importing the CSV data into Power BI Desktop, I conducted exploratory data analysis to understand data distributions and identify the dimensions most critical to business performance. This groundwork informed the selection of visualizations that would tell the most compelling story.

### Key Visualizations & Insights
### 1. Regional Profit Analysis (Bar Chart)
Objective: Identify which regions are delivering the strongest financial performance.

![bar](https://github.com/RakeshsarmaKarra/USA-Sales-Performance-Analysis-2014-2017-/blob/main/Profit%20For%20Each%20Region.jpg)

Design Approach:
I created a horizontal bar chart to compare profit across the four U.S. regions, selecting this format because it makes magnitude comparisons immediately clear and accommodates region labels effectively. The visual was customized with professional formatting—clear axis titles, readable fonts, and a clean layout that highlights the data without distraction.

Key Insights:

West region leads profitability at $11.4M, establishing itself as the top-performing market

East region follows closely with $10.3M in profit, indicating strong market presence

Central region generates $8.5M, showing solid but lower performance than coastal markets

South region trails at $5.8M, representing a potential growth opportunity or a market requiring strategic intervention

Business Implications:
The West and East regions are clear profit centers and should receive continued investment and resource allocation. The South region's underperformance warrants deeper investigation—is this due to market maturity, competitive pressure, pricing strategies, or operational inefficiencies? Understanding these drivers could unlock significant revenue potential.

### 2. Category Performance Trend Analysis (Line Chart)
Objective: Understand how product categories have performed over the four-year period and identify growth patterns.

![Line](https://github.com/RakeshsarmaKarra/USA-Sales-Performance-Analysis-2014-2017-/blob/main/Profit%20on%20Each%20Year%20And%20Category.jpg)
Design Approach:
I built a multi-line chart tracking profit trends by category from 2014 through 2017. Line charts are ideal for temporal analysis, allowing viewers to easily identify growth trajectories, seasonal patterns, and inflection points. Each category was color-coded for quick differentiation.

Key Insights:

Technology shows the strongest growth trajectory, with profit climbing from approximately $2M in 2014 to $7M+ by 2017—representing more than 3x growth

Office Supplies demonstrates steady, consistent performance, maintaining moderate profit levels with gradual increases throughout the period

Furniture exhibits volatility, with notable fluctuations year-over-year, suggesting either seasonal demand patterns or category-specific challenges

Business Implications:
Technology products are the clear growth driver and deserve strategic focus—expanding inventory depth, enhancing marketing efforts, and capitalizing on customer demand could further accelerate this trend. The stability of Office Supplies makes this category a reliable revenue foundation, while Furniture's inconsistency suggests a need for demand forecasting improvements and possible product line optimization.

### 3. Geographic Profit Distribution (Interactive Heatmap)
Objective: Visualize profit patterns across U.S. postal codes to identify high-value geographic markets and potential expansion zones.

![G1](https://github.com/RakeshsarmaKarra/USA-Sales-Performance-Analysis-2014-2017-/blob/main/Profit%20On%20Each%20Postal%20Code.jpg)

Design Approach:
To bring geographic intelligence to life, I integrated a custom heatmap visual (Weiwei Cui) from the Power BI marketplace. I mapped postal codes to location coordinates and profit values to color intensity, experimenting with multiple visualization modes (Aerial, Gray, Dark - Check these in Appendix) and rendering types (Heat, Contour) to determine the most effective display. The contour rendering with color gradients provided the clearest view of profit concentration patterns.

The heatmap was configured with:

Postal codes as location identifiers

Profit values determining heat intensity

Custom color scales to distinguish high-profit areas ($0 - $2.44M range)

Interactive zoom and pan capabilities for detailed exploration

Key Insights:

Coastal urban centers demonstrate concentrated high profitability, with darker heat signatures visible in major metropolitan areas

Midwest and Southern regions show more dispersed, lighter-intensity profit patterns, suggesting lower market penetration or smaller transaction volumes

Clear profit corridors emerge along major population centers and transportation hubs

Rural and remote postal codes show minimal heat, indicating untapped markets or logistical challenges

Business Implications:
The geographic visualization reveals actionable intelligence for market strategy. High-density profit zones should be protected and nurtured through dedicated account management and service excellence. Mid-density areas represent expansion opportunities where targeted marketing and improved distribution could drive growth. Low-intensity regions require careful evaluation—are these markets worth pursuing, or are there structural barriers that make them less viable?

### Technical Implementation
Data Connectivity:
I imported the sales dataset using Power BI's native CSV connector, selecting the "Load" option directly since the data required no transformation. This streamlined approach allowed for rapid prototyping and iteration.

Visual Customization:
Each visualization was carefully formatted for clarity and professionalism:

Typography: Consistent font families, appropriate sizing, and bold emphasis on key labels

Color schemes: Purposeful color selection to enhance readability and draw attention to important data points

Layout: Strategic placement and sizing to create visual hierarchy and guide the viewer's eye

Interactivity: Cross-filtering enabled across visuals, allowing users to drill down into specific regions, categories, or time periods

### Custom Visual Integration:
To achieve the geographic analysis capabilities required, I extended Power BI's native functionality by importing the Heatmap visual from AppSource. After downloading and adding the visual to my workspace, I configured location mapping and tested multiple rendering modes to optimize for both aesthetic appeal and analytical clarity.

### Dashboard Integration
While individual visualizations provide focused insights, the real power emerges when they're combined into a cohesive dashboard. The final implementation brings together:

Regional profit comparison for macro-level strategic assessment

Category trend analysis for product planning and inventory decisions

Geographic heatmap for market expansion and territory management

Together, these views enable stakeholders to understand not just what is happening in the business, but where and how performance is evolving—equipping decision-makers with the context needed for confident action.

### Skills Demonstrated
Data Analysis: Exploratory data analysis, metric selection, business context interpretation

Visualization Design: Chart type selection based on data characteristics, visual hierarchy, user experience considerations

Power BI Proficiency: Data import, visual configuration, custom visual integration, formatting and styling

Business Intelligence: Translating data patterns into actionable business insights, strategic recommendation development

Technical Problem-Solving: Extending platform capabilities through marketplace integrations, iterative refinement of visual designs

### Learning Resources
This project was developed through self-directed learning using comprehensive Power BI tutorials available on YouTube, demonstrating my ability to independently acquire new technical skills and apply them to real-world business scenarios.

### Conclusion
This Power BI analysis transforms four years of sales data into a clear, actionable narrative about business performance. By combining multiple visualization techniques—comparative bar charts for regional analysis, temporal line charts for trend identification, and geographic heatmaps for spatial intelligence—the dashboard provides a comprehensive view of the factors driving profitability.

The insights revealed through this analysis can directly inform strategic decisions around resource allocation, market expansion, product focus, and operational optimization. More importantly, the interactive nature of the Power BI platform ensures that stakeholders can explore the data themselves, asking and answering their own questions in real-time.

This project reflects my approach to data analysis: start with clear business questions, explore the data thoroughly, select the right visual tools for the story you need to tell, and deliver insights that drive meaningful action.

### Appendix:
<div align="center">
  <table>
    <tr>
      <td><img src="https://github.com/RakeshsarmaKarra/USA-Sales-Performance-Analysis-2014-2017-/blob/main/Profit%20On%20Each%20Postal%20Code1.jpg" width="450" height="300" alt="Aerial View"/></td>
      <td><img src="https://github.com/RakeshsarmaKarra/USA-Sales-Performance-Analysis-2014-2017-/blob/main/Profit%20On%20Each%20Postal%20Code2.jpg" width="450" height="300" alt="Gray Scale View"/></td>
    </tr>
    <tr>
      <td><img src="https://github.com/RakeshsarmaKarra/USA-Sales-Performance-Analysis-2014-2017-/blob/main/Profit%20On%20Each%20Postal%20Code3.jpg" width="450" height="300" alt="Dark Mode View"/></td>
      <td><img src="https://github.com/RakeshsarmaKarra/USA-Sales-Performance-Analysis-2014-2017-/blob/main/Profit%20On%20Each%20Postal%20Code4.jpg" width="450" height="300" alt="Contour View"/></td>
    </tr>
  </table>
</div>


