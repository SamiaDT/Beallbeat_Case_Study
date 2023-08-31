# Beallbeat Case Study
*This case study is conducted in partial fulfilment of the requirements of the  DTI x Coursera Google Data Analytics course.*
## Case Study: How Can a Wellness Technology Company Play It Smart?

This case study is conducted in partial fulfilment of the requirements of the 
DTI x Coursera Google Data Analytics course.
Data Analyst: Rosamia Tubo
Company Details1
Cofounder and Chief Creative Officer: Urška Sršen
Mathematician and Bellabeat’s cofounder: Sando Mur

## About the company
Urška Sršen and Sando Mur founded Bellabeat, a high-tech company that manufactures health-focused smart products. Sršen used her background as an artist to develop beautifully designed technology that informs and inspires women around the world. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women.

By 2016, Bellabeat had opened offices around the world and launched multiple products. Bellabeat products became available through a growing number of online retailers in addition to their own e-commerce channel on their website. The company has invested in traditional advertising media, such as radio, out-of-home billboards, print, and television, but focuses
on digital marketing extensively. Bellabeat invests year-round in Google Search, maintaining active Facebook and Instagram pages, and consistently engages consumers on Twitter. Additionally, Bellabeat runs video ads on Youtube and displays ads on the Google Display Network to support campaigns around key marketing dates.

### Products:
Bellabeat app: The Bellabeat app provides users with health data related to their activity, sleep, stress, menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and make healthy decisions. The Bellabeat app connects to their line of smart wellness products.
Leaf: Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace, or clip. The Leaf tracker connects to the Bellabeat app to track activity, sleep, and stress.
Time: This wellness watch combines the timeless look of a classic timepiece with smart technology to track user activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your daily wellness.
Spring: This is a water bottle that tracks daily water intake using smart technology to ensure that you are appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your hydration levels.
Bellabeat membership: Bellabeat also offers a subscription-based membership program for users. Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health and beauty, and mindfulness based on their lifestyle and goals.



## I. Objectives
### Business Task
Identify the trends in Bellabeat’s device usage to help Bellabeat devise their marketing strategy.
### Stakeholders
The primary stakeholders are the marketing team manager, the vice president, the president, and the CEO of the company. They will be the ones who would decide to implement the recommendations. The secondary stakeholders are the rest of the marketing team and the finance department. The tertiary stakeholders are the manufacturing workers/contractors and consumers.
### Deliverable
To visualize the trends of ellabeat’s device usage and recommend marketing strategies.

## II. Preparation
Data Sources
The data analyzed was a dataset available in Kaggle, the FitBit Fitness Tracker Data stored by Mobius. It is a dataset collected through Amazon Mechanical Turk from March 12, 2016 to May 12, 2016 from thirty eligible Fitbit users. 

### Data description
The data has structure options. All of the data sets, except the ‘minute’ datasets, only have the long format (per time per user metric). For the ‘minute’ datasets, there are two separate sheets per metric: one with long format (per time per user number of steps) and one with wide format (per time per user per number of steps).
		
All of the data sets can be sorted and filtered by date or by user ID or by metric, depending on how it will be analyzed.

### Data credibility and limitations
The thirty respondents consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. Individual reports can be parsed by export session ID (column A) or timestamp (column B). Variation between output represents use of different types of Fitbit trackers and individual tracking behaviors/preferences. The data has no copyright and is on a CC0 1.0 Universal (CC0 1.0) Public Domain Dedication license which allows the distribution of data by any means.

Compared to the overall number of Bellabeat users, a sample of thirty cannot represent the whole diverse population. Other factors like gender (which can affect the BMI results reference), demographics, and living conditions are not indicated on the dataset. Despite these limitations, this data set can still be a good way to analyze  the trends for the metrics for this sample with the use of proper tools and proper representation.


## III. Process
### Data tools
R was used in the analysis due to its capability to process big data and create various types of graphical illustrations that are effective for the visualization.

### Data cleaning
Formatting coherency of the data on the tables were ensured. To allow data merging, the columns with date-time format were split to two columns.
Null or error values were dropped in plotting and measuring the mean and median.

### Data integrity
Apart from the lack of gender identification of the respondents (it affects the BMI reference), there were only 8 participants who participated in the weight data collection. This low number of samples, that can be considered insignificant compared to the whole population, the data cannot be treated as the reflection of all Bellabeat device users.

### Data verification
The analyst browsed on the data sets and found some null values - these were excluded in the succeeding analyses. All the other values are logical per the metric measured. Date formatting differences were also resolved during cleaning thus the tables used have common date formats.

## IV. Analysis and Visualizations
### Activity intensity
Summary
Histogram of Activity intensity vs. Hour


### Total Steps

### Sleep time
