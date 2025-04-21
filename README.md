# XYZ-Sports-Company-Customer-Segmentation

This Clustering project was developed in the Data Mining's course. The goal was to use unsupervised learning techniques to better understand the type of customer's clusters, in a gym, and later provide marketing strategies to better serve these customers. We firmly believe that our work will be essential in better understanding the company's customers and understand the values and demographics of each cluster.

## Introduction

Finding new customers is vital in every industry. The process for finding new customers begins by learning as much as possible from the existing customers. Understanding current customers allow organizations to identify groups of customers that have different product interests, different market participation, or different response to marketing efforts. With this, we will be able not only to serve better our customers, but also to improve the targeting of prospective customers.

Market segmentation, the process of identifying customers’ groups, makes use of geographic, demographic, psychographic, and behavioral characteristics of customers. By understanding the differences between the different segments, organizations can make better strategic choices about opportunities, product definition, positioning, promotions, pricing, and target marketing.

XYZ Sports Company is a well-established fitness facility that has been serving the community for several years. To enhance its marketing strategies, improve customer engagement, and tailor its services, the company aims to develop a comprehensive customer segmentation strategy. This project will focus on dividing the customer base into distinct segments based on various characteristics and behaviors. 

## Final Solution

After preprocessing the data, we proceeded to computing the segmentation. We experimented with 4 different clustering algorithms: **K-Means**, **DBSCAN**,**Self Organizing Map** and **Mean Shift algorithm**.

After several attempts, it was decided that the **K-Means** solution, with **3 different clusters** was the best segmentation possible. 



**Cluster 0**: This cluster has the **youngest clients**, **most attended classes**, the one that goes **more times per week to the gym** and by far the **highest number of renewals**. With that in mind, a satisfactory **marketing approach** would be to **launch fitness challenges** and **online competitions** on social media platforms for **younger audiences** that are relevant in this clustering and use influencers to promote those events to increase brand visibility and appeal to this age group's digital habits. This cluster also displays the highest number of people attending **WaterActivities** and **TeamActivities**. With this in mind, we recommend the gym to make sure that the **swimming** and **TeamActivities materials** are always in **good state**, as these will suffer more **wear**, since are more used by the people of this cluster. To keep these clients satisfied, the gym should always invest in **good equipment**.



**Cluster 1**: This cluster is the one with the **highest age** and both **second largest number of frequencies and renewals**. A relevant **marketing strategy** for this group could be creating **wellness programs** focused on **senior age people**. By doing this the academy could develop programs like **low-impact aerobics classes or yoga**, which can cater to their specific health needs, interests and be a well-suited place for social interaction. This is the cluster where people attend the **most SpecialActivities**. Given this fact, the gym should make sure that it has the **right disability inclusive infrastructure** and workers prepared to help people with **disabilities**.



**Cluster 2**: As this is the cluster with the **least number of renewals and frequencies**, and presents a **high percentage of young people**, a possible **marketing strategy** could be **decreasing renewals costs** for these clients, such as contractual costs or maybe creating a new monthly payment category for clients of younger ages, to ensure that these continue linked to the company. Since they **show up the least in the gym**, and don’t take part in most of the classes provided by the gym, the gym could create a **new activity**, to attract them. A good example of a new type of activity could be **Padel**. Even though the gym already offers RacketActivities, but if so far, this has not been enough to attract young people, maybe it should redirect its focus towards a trending sport nowadays, like Padel. Also, by looking at the frequency of these cluster’s clients in the different activities, we see that the 3rd most frequent activity is CombatActivities. A possible approach could be increasing the gym’s offer in terms of this activity, because there are a lot of different types of combat activities and diversifying it could help captivating its customers.
