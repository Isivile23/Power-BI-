# Power-BI
## Describing the capabilities of Micosoft Power BI

### Describe using Power BI to build data-driven analytics


Businesses have a lot of data but struggle to understand it. Power BI is a Microsoft tool that helps turn complex data into easy-to-understand visuals and reports. It allows you to connect to various data sources, clean and analyze the data, and then share it with others. Power BI comes in three versions: a desktop application, an online service, and mobile apps.

### Explore the different Power BI elements

#### Capacities

Businesses have a lot of data but struggle to understand it. Power BI is a Microsoft tool that helps turn complex data into easy-to-understand visuals and reports. It allows you to connect to various data sources, clean and analyze the data, and then share it with others. Power BI comes in three versions: a desktop application, an online service, and mobile apps.

#### Workspaces

Power BI uses workspaces to organize reports, dashboards, and data. There are two main types:

* My Workspace: This is your personal space for creating and working on your own reports and dashboards.
* Workspaces: These are for collaboration. You can invite colleagues to work together on reports, dashboards, and even create shareable apps (collections of reports and dashboards) for others in your organization. Unlike "My Workspace," most users in a collaborative workspace need a Power BI Pro license.

#### Semantic models

In Power BI, a semantic model is like a central hub for your data. It can connect to and import information from various sources, including Excel files, cloud databases, and even other semantic models.  These models are linked to workspaces, allowing you and your colleagues (with the right permissions) to access and share the data in reports and dashboards.

#### Shared semantic models

Sharing well-defined "semantic models" is crucial for good business intelligence with Power BI. These models act as a single, reliable source of truth for your data, created by experts and reusable by report builders. This ensures consistency and accuracy in reports and data-driven decision making throughout your organization. When creating reports in Power BI, simply choose "Power BI semantic models" to leverage these shared models.

#### Reports

Power BI reports are collections of visualizations (charts, maps, etc.) built from datasets. You can create them from scratch, import them, or have Power BI generate them when connecting to data sources.  There are two ways to interact with reports:

* Reading view (default): This is for viewing and exploring the report.
* Editing view (requires permission): This allows modifying the report's layout and visualizations.
  
Reports are listed under the Reports tab in a workspace and can be opened from there.  Within apps (collections of reports and dashboards), you can access reports by clicking on dashboard tiles linked to those reports.

#### Dashboards

In Power BI, a dashboard is a single screen that brings together important information from reports and Q&A. It displays these insights as tiles or widgets, allowing you to:

* See everything you need to make a decision at a glance.
* Monitor key business metrics.
* Ensure everyone in your team is on the same page with the same data.
* Track the health of various aspects of your business.
* Create personalized views of dashboards focused on what matters to you.

Dashboards are listed under the Dashboards tab in a workspace and can be opened directly. Within apps (collections of reports and dashboards), the dashboard is the first thing you see. You can also access reports from the dashboard by clicking on linked tiles.  Depending on how the dashboard was shared with you, you may have viewing or editing permissions.

#### Tempelate Apps

Power BI template apps are pre-built analytics tools for Power BI. They are designed by Power BI partners and allow for easy customization by the end user. This lets businesses leverage the expertise of these partners without extensive coding, and ultimately understand their data better.

### Describe cleaning and transforming data in Power BI Desktop

Working with data from multiple sources often requires cleaning and transformation before it can be analyzed together.

* Data might be in different formats or have unnecessary details.

* Power BI Desktop helps clean and transform data for analysis.

It has three views:

  * Report view: Build and arrange visualizations.
  * Data view: See the data structure and make changes.
  * Model view: Manage relationships between different data sets.
    
Power Query Editor within Power BI Desktop helps reshape and transform the data for better use in reports and visualizations.
To begin, select Edit from the Navigator window to launch Power Query Editor. You can also launch Power Query Editor directly from Power BI Desktop by using the Transform Data button on the Home ribbon.

#### Transform data 

* Transforming data is the process of putting data into a format that is useable in your reports. Examples of the available transformations include removing a column from the table, duplicating the column under a new name, or replacing values.

#### Clean data

Power BI prefers data in a columnar format for visualizations and analysis, even though it can import from various sources. Spreadsheets, for instance, might not be ideal as their layout can hinder Power BI's functionalities.

Here's the issue:

* Spreadsheets may have headers spanning multiple columns, confusing Power BI for automated tasks.
  
Data cleaning in Power Query helps transform the data into a format suitable for Power BI. This could involve:

* Combining rows with multi-column headers into single rows.
* Aggregating numeric data for better visualization.

### Describe using AI Insights to spot trends and anomalies

Businesses struggle to find trends and spot oddities in their data as it happens. For instance, a sales drop during the holiday season or a random sales spike in August would be unexpected. Identifying these anomalies quickly is crucial for taking corrective actions.

Power BI's insights come to the rescue! It automatically analyzes your reports, dashboards, and visualizations to uncover trends and anomalies. It even explains these insights to you, so you can understand why they're important. This feature works on any report without any setup, giving you valuable insights from your data straightaway.

Power BI has multiple insights features that use artificial intelligence (AI):

* Insights for reports: Analyzes data and finds anomalies and trends in your data as you interact with reports.

* Insights for individual visuals: Analyzes and explains the fluctuations of data points in visuals.

* Insights for dashboard tiles: Looks at the data being used to render that tile and presents them in interactive visuals.

* Quick Insights for datasets: Automatically generate data insights on a dataset in the Power BI service.

* AI Insights for data models in Power Query: Provide access to pretrained machine learning models from Azure Cognitive Services.

#### Notifications

In Power BI, notifications are key for staying informed about insights. Here's how it works:

* Power BI analyzes your reports and visuals as you work.
* If it discovers noteworthy trends or anomalies (called insights), you'll see a notification.
* You can then choose to explore these insights or dismiss them.

This helps you stay on top of important changes in your data, like a sudden sales increase in a particular region. The notifications focus on the most important insights (top insights) to avoid overwhelming you with information.

### Get insights on report and visuals 

#### Insights

* Anomalies: Represents something that is out of the ordinary from what is expected. For example, a smart thermostat that suddenly reads the temperature as 100 F when it's typically 72 F would be considered an anomaly.

* Trends: Represents a pattern that is found in time-series datasets. For example, if a company’s sales are steadily increasing through the month of April that would represent a trend.

* Key Performance Indicator (KPI) analysis: Helps you evaluate the current value against a defined target. For example, a company might set a sales goal at 1.2 million, but currently they are at 1 million.

##### Anomalies

In Power BI, anomalies are unexpected spikes or dips in your data over time.  An algorithm is used to define a normal range for the data, and anything outside that range is flagged as an anomaly. There are three main types of anomaly insights:

* Significant anomaly: This is a major deviation from the expected value.
* Recent anomaly: This is the newest anomaly identified.
* Anomaly summary: This highlights multiple related anomalies.
  
When an anomaly is found, Power BI analyzes your data to see what might be causing it. These potential explanations are ranked by how likely they are to be the true cause. This helps you understand why the anomaly might have happened.

##### Trends

A trend occurs when there's a prolonged increase or decrease in time-series data. There are a series of steps the Power BI algorithm uses to find meaningful trends. It first performs data smoothening, interpolation, and time-series sampling. The trends are then identified for statistical significance based on the slope and length of a change in value. The algorithm removes noise like seasonality and outliers. For example, if sales jump in December, the algorithm doesn't mark that as a noteworthy trend because it's common for sales to jump around the holidays.

There are four main trends flagged:

* Long trend: The trend is significant and is the longest trend within a single series or across multiple series in a visual.

* Steep trend: The trend is significant and is the steepest trend within a single series or across multiple series in a visual.

* Recent trend: The trend is significant and is the most recent trend within a single series or across multiple series in a visual.

* Trend reversal: Recent trend in a single series or across multiple series in a visual where the reversal is significant, compared to the previous trend segment.

When a trend in your data is flagged, Power BI looks for and identifies the categories that most influenced the increase or decrease in the identified trend. Possible explanations are ranked based on the relative contributions from different categories to the increase or decrease in trend.

##### KPI analysis

Power BI analyzes your Key Performance Indicators (KPIs) to see if they are performing as expected. There are two main KPI analysis types:

* With Target: This compares the current KPI value to a specific target and identifies significant variations (high or low) compared to other categories.
* Without Target: This analyzes the KPI value itself and flags high or low values compared to other categories.
  
For both KPI analysis types, Power BI investigates the reasons behind these variations and ranks potential explanations. Here's how the ranking works:

* With Target: Ranked by how much a category's value differs from its target (based on Z-scores).
* Without Target: Ranked by the Z-scores of the KPI value itself.
In essence, Power BI helps you understand why your KPIs might be deviating from expectations.

### Build a basic dashboard

Now that we introduced you to some of the core concepts in Power BI such as reports, dashboards, and workspaces, let’s see how these different elements would be used to support common business scenario. Managers often want to see how their salespeople are performing. It wouldn't be uncommon for your manager to ask to see your latest sales and profit figures by the end of the day. Many individuals keep those details in an Excel spreadsheet on their computer. Historically, getting that data into a format that a manager can easily consume could take several hours if not days.

With Power BI, we can easily create and share a dashboard with a manager by connecting to a data source such as an Excel spreadsheet on your laptop. While the data sources that you use might be different, the process for building and sharing a dashboard are same.

You need to take the following steps:

* Prepare your data: Preparing the data ensures that it's in a format that Power BI can easily consume.

* Build a report: The report contains the visuals that you want to include in your dashboard. Depending on the scenario, reports can be built in either Power BI Desktop or using the Power BI Service.

* Pin the report visuals to a dashboard: Dashboards are the primary element that users use for viewing data. They can include data from multiple reports as needed.

* Share a link to the dashboard: Any users with the link and the necessary permissions are easily able to view and interact with the data.

### Prepare the data

* Data Cleaning and Transformation: Ensure your data is ready for analysis using Power Query, especially for large datasets or complex sources.
* Excel Spreadsheets: Data should be in a flat table format with a header row but no totals (handled in Power BI visualizations later).
* Data Types: Each column should have the correct data type assigned (text, date, number, currency).

### Upload your data to the Power BI service

The Power BI service is where you're able to create reports that connect to your data sources. This includes Excel files that live on your computer. With a few simple clicks, you can attach to a dataset, and Power BI creates a blank dashboard where you're able to place visuals later.

### Build your report

After connecting your data source (like an Excel workbook in this case), you can create or edit reports in Power BI. Here's a breakdown:

* Editing Reports: Reports allow you to visually present your data. You can use the editing view to modify existing reports or create new ones.
* Fields Pane: This pane lists the available data fields from your connected source (e.g., column headings from your Excel sheet).
* Visualizations Pane: This pane offers various chart types (bar charts, maps, etc.) to represent your data. Choose the visualization that best suits the information you want to convey. (The example uses bar charts and a map to show unit sales by country).
* Filters and Controls: Each visualization allows you to customize how data is displayed. You can change what data is shown on the axes (e.g., switch from units sold to profit).
* Expanding Power BI: Power BI is constantly adding new features. One example is the Power Apps visualization, which lets you create interactive mini-applications within your report. These apps can connect to your data and even take actions based on user interaction (e.g., sending emails based on report insights).

### Pin to a dashboard

