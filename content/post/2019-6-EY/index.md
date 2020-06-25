---
title: '2019.06: Ranked top 10 in HK (6.2%) in EY Data Science Competition,
  "Smart City"'
subtitle: ""
date: 2019-06-05T13:15:20.467Z
summary: ""
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: true
---
EY NextWave Data Science competition 2019 focuses on how data can help the next smart city thrive, and boost the mobility of the future.  In this competition, systematic data mining and processing ideas are used here. I am glad to share them.

### 1.Understand the problem

#### 1.1 Dataset Description

The dataset contains the anonymized geolocation data of multiple mobile devices in the City of Atlanta (US) for 11 working days in October 2018. There are approximately 210,000 devices and 11 columns in the dataset. The variables in the dataset are as follows:

![](dataset_decription.png)

Every device ID resets every 24 hours. Therefore, we will not be able to trace the same device across different days.

#### 1.2 Task and goal

Our task is to produce a model that helps authorities to understand the journeys of citizens while they move in the city throughout the day. 

Each journey is formed by several trajectories. A trajectory is defined as the route of a moving
person in a straight line with an entry and an exit point. Below is an example of one trajectory
from one of the devices:

![](trajectory_of_vehicles.png "trajectory of a vehicle")

For each device, you will get multiple trajectories, like this:

![](full_journey.png)

We are expected to predict the location of this last exit point and whether this device is within
the city center or not. The target variable is the latter. Here is a graphic example.

![](city_center.png)

After we estimate the position of each target, we need to classify that point based on
whether it is located inside the city center or not.





### 2.Methodology

#### 2.2 Data Preprocess

### 3.Prospect

Hopefully, our work could inspire solutions that help city authorities anticipate disruptions, make real-time decisions, design new services, and reshape infrastructures in order that cities as smart as their citizens.