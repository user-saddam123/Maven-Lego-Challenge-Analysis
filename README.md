# Maven-Lego-Challenge-Analysis

## Created & Analyzed by Saddam Ansari @Aspirirng Data Analyst [Linkedin](https://www.linkedin.com/in/saddam-ansari-dataanalyst/)

### Live Dashboard at Novypro [Live_link_Novypro](https://www.novypro.com/project/maven-lego-challenge-analysis-by-saddam-ansari)
### Live Dashboard at Maven Analytics ShowPage [Link](https://mavenanalytics.io/project/12351)

#
## Table of Content:
 1. [Objective](#challenge-objective)
 2. [About The Data Set](#about-the-data-set)
 3. [Dashboard Overview](#dashboard-overview)
 4. [Tools Used](#tools-used)
 5. [Tips for using Bookmarks](#important-tips-for-using-bookmarks)
 6. [Detailed Explanation](#detailed-explanation)
 7. [Trend Overview](#trend-overview-1)
 8. [Category Based Insights](#category-based-insights-1)
 9. [Themes Based Insights](#themes-based-insights)
10. [Sub Theme Based Insights](#sub-theme-based-insights-1)
11. [ThemeGroup Based Insights](#themegroup-based-insights)
12. [SECOND PAGE](#second-page)
13. [Learnings](#learning-through-this-project)
14. [End](#the-end)

#

## Challenge Objective: 
[🔁Home](#table-of-content)
The Objective of this Maven LEGO Challenge, we'll need to stack our imagination and analytical prowess to piece together an interactive dashboard or visual that lets users(Client) explore the insight from history and evolution of LEGO sets from the past 5 decades.

## About The Data Set:
[🔁Home](#table-of-content)
For this project I have provided a CSV file type dataset. This dataset comprises a single table containing 18,459 records and 14 fields.

Specifically, the dataset focuses on LEGO sets released from 1970 to 2022, encompassing various details such as each set's theme, number of pieces, recommended age, retail price, and an image associated with each set.

### Data Dictionary & Secrets:
[🔁Home](#table-of-content)
Before proceeding further with the project, here is a brief overview of the data and its fields:

 *  set_id : The official LEGO item number, ensuring 100% uniqueness.

 * name: The name of the LEGO set.

 * year: The release year of the set.

 * theme: The LEGO theme to which the set belongs, with 152 distinct values.

 * subtheme: The subtheme within the theme. This field contains blank values in 18.17% of rows and has 874 distinct values.

 * themeGroup: The overall group to which the theme belongs, with 17 distinct values.

 * category: The type of set, categorized into 7 distinct values.

 * pieces: The number of pieces in the set. Approximately 21% of rows have blank values, totaling 3,924.

 * minifigs: The number of mini figures included in the set. Approximately 54% of rows have blank values, indicating 10,058 rows with no minifigure data.

 * agerange_min: The minimum recommended age for the set.

 * US_retailPrice: The US retail price at launch. Around 62% of rows are blank, amounting to 11,475 rows with no average price data.

 * bricksetURL: The URL for the set on brickset.com.

 * thumbnailURL: A small image of the set.

 * imageURL: The full-size image of the set.

### Dashboard Overview:
[🔁Home](#table-of-content)
I have developed a Power BI dashboard consisting of two pages to meet the objectives of the challenge. The first page is divided into six sections, each providing detailed insights and analysis as follows:

* #### Quick Insight Section: 
This section includes key performance indicators (KPIs), headings, project objectives, and other relevant information.

* #### Trend Overview: 
In this section, I have analyzed various trends over the years, presenting different insights based on temporal analysis.

* #### Category-Based Insights: 
Visualizations and analysis related to categories are presented in this section, offering insights into different sets based on their categories.

* #### Theme-Based Insights: 
This section focuses on theme-based visuals and insights, providing a deeper understanding of the data categorized by themes.

* #### Sub-Theme-Based Insights: 
Here, analysis and visuals are based on sub-themes, offering insights into the subsets within larger themes.

* #### Theme Group-Based Insights: 
Insights and analysis based on theme groups are presented in this section, providing a broader perspective on thematic categorization.

The second page is designed to be user-friendly, featuring standard and new KPIs along with slicers. Users can easily select a specific LEGO set and gain insights about it in an easy-to-understand manner, facilitating interactive exploration of the data.

### Tools Used:
[🔁Home](#table-of-content)
In line with the objectives and project requirements, I have utilized Power BI, a powerful business intelligence tool, for dashboard creation. Additionally, I have employed Excel to some extent to ensure that the data is formatted clearly and in a usable manner.

### Important tips for using bookmarks:
[🔁Home](#table-of-content)
Sometimes, after clicking on a bookmark, the filters may not apply as expected. In such cases, try clicking on another bookmark within the same group and then return to the desired bookmark. This action often resolves any issues with the bookmark filters not applying correctly.

#

## Detailed Explanation:
[🔁Home](#table-of-content)
At the top of my dashboard, I have incorporated 7 key performance indicators (KPIs) to provide a quick overview and basic understanding of the dataset and dashboard. These KPIs are as follows:

![1](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/a98d9285-11bd-44c5-bf8b-2866e91eef43)

* 1.Total Sets Released: 18.46 thousand

* 2.Total Pieces Released: 3.29 million

* 3.Average Price: $37.53

* 4.Total LEGO Themes: 152

* 5.Total Theme Groups: 17

* 6.Total LEGO Categories: 7

* 7.Total Minifigures: 22.37 thousand

### Quick Insights - Top 5 Highlights
In the Quick Insights section, you can easily view top 5 quick insights presented in different tabular views:

![aa](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/a7b8f01e-9817-4b6c-a2f0-ced8ea61882e)

#### 1. LEGO Sets with Most Sets:
 * Category: Bonus/Value Pack
 * Category Type: Collection
 * Total Sets: 167

#### 2. LEGO with Most Pieces:
 * Category: Bonus/Value Pack
 * Category Type: Collection
 * Total Pieces: 38,187

#### 3. Most Expensive LEGO:
 * Set Name: Millennium Falcon
 * Category: Normal
 * Price: $1,309.96

#### 4. Cheapest LEGO:
 * Set Name: Gift Tag Stickers
 * Category: Gear
 * Price: $1.49

#### 5. LEGO Sets with Most Minifigures:
 * Set Name: City Advent Calendar
 * Category: Normal
 * Minifigures: 131

#

## Trend Overview
[🔁Home](#table-of-content)
The Trend Overview section provides a high-level view of the evolution of LEGO sets over year. It includes two bookmark buttons that allow users to switch between two different visuals.

### 1.Lego Sets Released by Year

![trend1](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/629147fd-2ed0-4416-81c4-ba5cc9b8221d)

The number of LEGO sets released per year has increased significantly over the past 50 years. In 1970, only 41 sets & 8 theme were released, while in 2022, there were 967 sets & 17 lego theme released. This represents an increase of 2258.54%.

### 2.Total Pieces Released by Year

![trend2](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/558a9373-028a-4e9e-b347-024e45a8b22d)

The total number of pieces per year has also increased dramatically. In 1970, there were a total of 3706 pieces, while in 2022, there were a total of 279,700 pieces. This represents an approx increase of 7447.14%.

### 3.Total Minifig by Year

![trend3](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/4cdd066f-b955-4d86-99a0-102dbd21f4e2)

The dataset starts from 1970, but the minifig related data is available from 1975 onwards. Therefore, according to the data, there were 37 minifigs in 1975, which was about 0.17% of the total minifigs. Moreover, from 1975 to 2022, the number of Lego minifigs increased by approximately 3215.22%, reaching 1227 minifigs in 2022, which was about 5.48% of the total minifigs.

### 4.AVG Lego Price by Year

![trend4](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/285ca441-01c2-4883-85a2-f2a4828a3406)

Similarly, the data spans from 1970 to 2022, but the price related data is only provided from 1991 to 2022. Hence, the average Lego price in 1991 was 23.99$, which increased by 119.16% to 52.58$ in 2022. An important point to note is that the lowest average price was in 1993, which was 4.99$, and the highest average price was in 2021, which was 52.95$.

#

## Category Based Insights
[🔁Home](#table-of-content)
The Category Based Insights section provides a detailed view of the distribution of LEGO sets, pieces, minifigure, and avg price across different categories. It includes four bookmark buttons that allow users to switch between four different visuals.

### 1.Total Set Released by Category

![cbi1](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/9819cc53-04b5-4235-a9ba-72a37115c48f)

The data shows that the majority of LEGO sets have been released in the Normal category, with 12,757 sets, or 69.12% of the total. The Random category has the fewest number of sets, with only 64 sets released.

### 2.Total Lego Pieces by Category

![cbi2](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/b784d568-1636-4e53-aa46-6b7bc532c51d)

The data shows that the majority of LEGO Pieces have been released in the Normal category, with 2.99M, or 90.81% of the total. The Random category has the fewest number of pieces, with only 70 pieces released.

### 3.Total Minifigs by Category

![cbi3](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/b1191e3f-3ac3-4c1c-8ccd-f7a6947981dd)

The data shows that the majority of LEGO minifig have been released in the Normal category, with 20205 Minifigs, or 90.31% of the total. The Book category has the fewest number of minifig, with only 53 minifig released.

### 4.AVG Retail Price by Category

![cbi4](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/c839b376-38eb-48c4-b707-1c35e80132b5)

The data shows that the Collection category has the highest average price, at $44.86. The Extended category has the lowest average price, at $14.21.

#

## Themes Based Insights
[🔁Home](#table-of-content)
The Theme Based Insights section provides a detailed view of the distribution of LEGO sets, pieces, minifigure, and avg price across different Theme. It includes four bookmark buttons that allow users to switch between four different visuals.

### 1.Top 10 Theme by total Lego Sets

![tbi1](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/ac56b176-c5ab-4183-872f-de742009d046)

The data shows that the majority of LEGO sets have been released in the Gear theme, with 2832 sets, or 15.34% of the total. The Random theme has the fewest number of sets, with only 64 sets released.

### 2.Top 10 Theme by total Pieces

![tbi2](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/f1b9a57a-2d53-404a-9f71-2c8438d6b97d)

The data shows that the majority of LEGO Pieces have been released in the Star War Theme, with 0.34M, or 10.31% of the total. The System Theme has the fewest number of Pieces, with only 8 pieces released.

### 3.Top 10 Theme by total minifig

![tbi3](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/be9457b0-c153-46ec-97ce-b21ddc719eb0)

The data shows that the majority of LEGO minifig have been released in the Star Wars theme, with 2108 Minifigs, or 9.42% of the total. and 5 theme has the fewest number of minifig, with only 1,1, minifig released.

### 4.Top 10 Theme by AVG Price

![tbi4](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/4162b949-12c6-4334-8296-5b8fd9a5056a)

The data shows that the Serious Play theme has the highest average price, at $516.74. The Collectable minifigures has the lowest average price, at $4.29.

#

## Sub Theme Based Insights
[🔁Home](#table-of-content)
The Sub Theme Based Insights section provides a detailed tabular view of the distribution of LEGO sets, pieces, minifigure, and avg price across different Sub Theme. It includes four bookmark buttons that allow users to switch between four different visuals.

### 1.Lego Set by Sub Theme

![sbi1](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/b511bcb4-8501-49d4-ad2d-48ec4279274c)

This tabular visual shows the number of LEGO sets released in each subtheme. The data shows that the majority of LEGO sets have been released in the Magazine Gift subtheme, with 563 sets, or 3.05% of the total. There are 3,356 sets, or 19.27% of the total, whose subtheme is not provided in the dataset.

### 2.Lego Pieces by Sub Theme

![sbi2](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/74cd5266-4f0b-4d4c-b8d9-4b9eb85a4455)

This tabular visual shows the number of LEGO piece released in each subtheme. The data shows that the majority of LEGO Piece have been released in the Product Collection subtheme, with 5154.18k Piece, or 4.68% of the total. There are 744.57k Pieces, or 22.62% of the total, whose subtheme is not provided in the dataset.

### 3.Lego Minifig by Sub Theme

![sbi3](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/28729f69-9c4f-458f-abf0-aef184ae12fb)

This tabular visual shows the number of LEGO minifig released in each subtheme. The data shows that the majority of LEGO minifig have been released in the Duplo subtheme, with 428 minifig, or 1.91% of the total. There are 3995 minifig, or 17.86% of the total, whose subtheme is not provided in the dataset.

### 4.Lego AVG Price by Sub Theme

![sbi4](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/0ae48b6d-4a10-43ec-8d61-3f8337ebea4c)

This tabular visual shows the number of LEGO AVG Price in each subtheme. The data shows that the highest LEGO AVG Price have the Castle System subtheme, with $399.99.

#

## ThemeGroup Based Insights
[🔁Home](#table-of-content)
The ThemeGroup Based Insights section provides a detailed view of the distribution of LEGO sets, pieces, minifigure, and avg price across different ThemeGroup. It includes four bookmark buttons that allow users to switch between four different visuals.

### 1.Lego Sets by ThemeGroup

![gbi1](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/e540105d-f33e-4a89-a6d4-b3cb277449fd)

This Visual shows that the majority of LEGO sets have been released in the Miscellaneous ThemeGroup, with 5891 sets, or 31.91% of the total. The Air & Crafts ThemeGroup has the fewest number of sets, with only 84 sets released.

### 2.Lego Pieces by ThemeGroup

![gbi2](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/38f48469-2a2f-48d1-a9cb-6a376a2b4bd6)

This Visual shows that the majority of LEGO Pieces have been released in the Licensed ThemeGroup with 0.86M, or 26.18% of the total. The Junior ThemeGroup has the fewest number of Pieces, with only 14306 pieces released.

### 3.Lego Minifg by ThemeGroup

![gbi3](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/b546de2a-a787-40e4-a5f6-992d9069606d)

This Visual shows that the majority of LEGO minifig have been released in the Licensed ThemeGroup, with 5952 Minifigs, or 26.60% of the total. and Technical ThemeGroup has the fewest number of minifig, with only 55 minifig released.

### 4.Lego Avg Price by ThemeGroup

![gbi4](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/fef3658f-8b6f-4c7a-89eb-952fccb2b59d)

This Visual shows that the Educational ThemeGroup has the highest average price, at $172.13. The Constraction has the lowest average price, at $16.38.

#

## SECOND PAGE
[🔁Home](#table-of-content)

### Page 2: Deep Dive into LEGO Sets
The second page is designed to be user-friendly, featuring standard and new KPIs along with slicers. Users can easily select a specific LEGO set and gain insights about it in an easy-to-understand manner, facilitating interactive exploration of the data.

or,

This interactive page allows users to explore individual LEGO sets and gain valuable insights. It caters to users who want to go beyond the surface-level information and delve deeper into specific sets.

### Key Features:
 * Slicers: Users can utilize interactive filters to select specific criteria and customize their exploration. This allows users to:
   * Filter by theme, category.

 * Search bar: Through this search bar Users can utilize interactive filters to select specific Lego set by name.
 * Standard and New KPIs: This section displays key performance indicators (KPIs) related to the selected LEGO set image.

Along with

  * Set Name

  * Theme

  * Category

  * Theme Group

  * Sub Theme

* An another group of KPIs: This section displays key performance indicators (KPIs) related to the selected LEGO set and in default its show overall insights.

* Line chart: Show the number of Lego Sets by year.

* New Slicers: In Last of this page I utilized a new slicers , through this Users can utilize interactive filters to select specific set name also sets image displayed on top of every set name.

![3](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/6fd56ac7-6409-4d68-b2f1-13cc61ebc2a9)


or,


![7](https://github.com/user-saddam123/Maven-Lego-Challenge-Analysis/assets/123800896/2264439b-8190-4b3c-9e36-3e0bd5e5b72a)

#

## Learning through this project:
[🔁Home](#table-of-content)
This project has been truly rewarding, allowing me to showcase my work and further my journey as an aspiring data analyst. It not only adds value to my portfolio but also demonstrates my capabilities in handling complex datasets.

This marks my first project where I have implemented 18 bookmarks and utilized new KPIs. The extensive detailing involved in this project took more than 14 days to complete.

Your feedback is highly appreciated, and I encourage you to like, comment, and provide your insights. Feedback plays a crucial role in my growth, so please feel free to share any suggestions.

Apart from this project, I have also completed over 18 Power BI projects, which you can explore on NovyPro at [NovyPro Portfolio](https://www.novypro.com/profile_projects/saddamansari)

Thank you for taking the time to view my project. I hope you enjoyed it.

#

Created and Analyzed by:

Saddam Ansari @Aspiring Data Analyst LinkedIn Link

Location: India

### THE END
[🔁Home](#table-of-content)
