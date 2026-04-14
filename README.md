# retail-marketing-analytics
This comprehensive analytics project demonstrates a complete data science workflow for retail and marketing analytics, from data acquisition to actionable insights and dashboard creation.
11. DASHBOARD CREATION
Step 1: Power BI Dashboard (Recommended)
Instructions for Power BI:
1.	Install Power BI Desktop (Free from Microsoft)
2.	Import Data: 
o	Open Power BI Desktop
o	Click "Get Data" → "Text/CSV"
o	Import the following files: 
	data/processed/cleaned_retail_sales.csv
	data/processed/customer_segments.csv
	data/processed/rfm_analysis.csv
	data/processed/monthly_kpis.csv
3.	Create Relationships: 
o	Go to "Model" view
o	Connect tables via Customer_ID and other common keys
o	Set appropriate cardinality (1-to-many, many-to-one)
4.	Build Dashboard Pages: Page 1: Executive Summary 
o	KPI Cards: Total Revenue, Total Customers, AOV, CLV
o	Line Chart: Monthly Revenue Trend
o	Bar Chart: Revenue by Category
o	Map Visual: Revenue by Region
Page 2: Customer Analytics 
o	Donut Chart: Customer Segments Distribution
o	Table: Top 10 Customers
o	Scatter Plot: RFM Analysis (Recency vs Frequency, size by Monetary)
o	Cohort Retention Heatmap
Page 3: Product Performance 
o	Treemap: Category Performance
o	Bar Chart: Top 20 Products by Revenue
o	Line Chart: Product Sales Trend
o	Table: Product Performance Metrics
Page 4: Marketing Insights 
o	Funnel Chart: Customer Journey
o	Gauge Charts: Retention Rate, Churn Rate
o	Column Chart: CLV by Segment
o	Matrix: Campaign Performance (if available)
5.	Add Interactivity: 
o	Add slicers for Date Range, Category, Region
o	Enable cross-filtering between visuals
o	Add drill-through pages for detailed analysis
6.	Format Dashboard: 
o	Apply consistent color scheme
o	Add company logo and title
o	Use appropriate fonts and sizing
o	Add tooltips for user guidance
7.	Publish: 
o	Save as .pbix file in dashboards/ folder
o	Export as PDF for presentation
o	Publish to Power BI Service (if available)

