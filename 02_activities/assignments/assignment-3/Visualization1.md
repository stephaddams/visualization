## Visualization #1


## Average Price per Litre for Fuels in Ontario, since 1990.

The visualization represents the average price for fuels in Ontario from 1990 to the most recently completed year. Prices are represented in cents per litre. The fuels considered are:
* Auto Propane
* Compressed Natural Gas
* Diesel
* Mid-Grade Gasoline
* Premiumn Gasoline
* Regular Unleaded Gasoline

---


I used Microsoft Excel to create the data visualization. Excel provides a practical and efficient environment for organizing, analyzing, and visualizing structured datasets. Its built-in tools—such as Pivot Tables, filtering, sorting, and chart customization—allow for streamlined data preparation and rapid iteration. Excel is widely accessible and commonly used in both academic and professional settings, which makes the visualization easy to share, review, and replicate by others without requiring specialized software.

The intended audience includes policymakers, researchers, students, business professionals in the energy and transportation sectors, and residents of Ontario who are interested in understanding long-term fuel price trends. Because fuel prices directly affect household budgets, transportation planning, and economic policy, the visualization was designed to be accessible to both technical and non-technical audiences.

The primary message of the visualization is to show how fuel prices in Ontario have evolved over time, highlighting long-term trends, fluctuations, and potential periods of volatility. By presenting the data in a continuous area graph, viewers can easily observe patterns such as gradual increases, sharp spikes, or periods of relative stability. The goal is not only to present raw data, but to make historical price evolution immediately interpretable. 

Several design principles guided the creation of the visualization. First, clarity and readability were central considerations. I used a font size of 20 for the main title, and 14 for notes to create a clear visual hierarchy. This ensures that viewers can quickly identify the purpose of the graph and interpret contextual information without straining to read small text. Second, color was intentionally leveraged to differentiate fuel types, allowing viewers to quickly distinguish between lines without confusion. The colors were selected to provide contrast while maintaining visual harmony.

Third, consistency was applied to axes and labeling. The x-axis represents time (years), and the y-axis represents price in cents per litre, clearly labeled to avoid ambiguity. The chart avoids unnecessary visual clutter, such as excessive gridlines or decorative elements, so that attention remains on the data trends. 

Reproducibility was supported by maintaining a structured dataset, imported directly from the web, removing the need to replicate the folder structure for the files, and providing a ReadMe tab at the beigining of the document. The data cleaning steps—such as identifying missing values and replacing them using the average of the previous four years based on observed trends—were documented. By keeping formulas visible and organizing the workbook logically (raw data sheet, cleaned data sheet, pivot table sheet, and visualization sheet), others can follow the same steps and recreate the chart.

While Excel is not inherently version-controlled like programming tools, it remains reproducible as long as the dataset and documented steps are shared. The main limitation is that manual edits can be harder to track, which could slightly reduce transparency if documentation is incomplete. However, clear documentation mitigates this risk.

Accessibility was addressed in several ways. First, distinct colors were used to differentiate fuel types clearly. Second, the chart includes a descriptive title and labeled axes, ensuring that viewers understand the units and time range. Most importantly, an alternative text (alt text) description was added to the graph to support individuals with visual impairments who use screen readers. The alt text provides a concise explanation of what the chart shows, including overall trends and comparisons among fuel types. Additionally, for a better understanding, a condensed table was added at the bottom of the graph for those who might have a visual impairment to distinguis the colors.

Ontario residents, commuters, trucking and logistics companies, policymakers, and environmental analysts may all be impacted by this visualization. Fuel prices influence transportation costs, business expenses, consumer spending, and broader economic trends. Communities that rely heavily on personal vehicles or long-distance transportation may be particularly sensitive to fuel price fluctuations. Policymakers may use such visualizations to inform tax decisions, energy policy, or infrastructure planning.

The primary focus was on average annual prices in cents per litre for major fuel types from 1990 onward. I selected these variables because they directly support the objective of showing long-term pricing trends. More granular data, such as monthly fluctuations or regional breakdowns within Ontario, were excluded to maintain clarity and avoid overcrowding the visualization. Including too many dimensions would have reduced readability and diluted the central message. The chosen features balance comprehensiveness with interpretability.

Significant behind-the-scenes work supported the final product. This included cleaning the dataset, verifying consistency across years and fuel categories, identifying and handling missing values, and validating that price units were consistent (cents per litre). Pivot Tables were used to explore the structure of the data and locate anomalies. Replacing missing values using the previous four years required trend examination and justification to maintain logical continuity. Additionally, iterative adjustments to formatting, color selection, legend placement, and axis scaling were necessary to achieve clarity and visual balance. This preparatory work, although not immediately visible in the final chart, was essential to ensure accuracy, clarity, and credibility.
