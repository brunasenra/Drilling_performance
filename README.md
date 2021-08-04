# Drilling Performance

## Introduction

Measurement of performance is vital to business success and most performance studies are related to key performance indicators (KPIs). A Key performance indicator is a metric, measuring how well the organization is performing on operational, tactical or strategic activities that is critical for the current and future success of the organization.
In the Oil and Gas industry, KPIs can be used for monitoring and measuring operational quality performance. In Drilling, a process whereby a hole is bored using a drill bit to create a well for oil and natural gas production, one example of KPI would be the Slip to Slip connection time. This KPI can offer significant improvements in identifying sources of Non-Productive Time.
The Slips is a device used to grip and hold the upper part of a drill pipe to the drill floor, which is the area where the pipe begins its trip into the earth. The Slips is used when making a connection: the pipes are jointed in order to advance further into the hole. Therefore, each pipe is picked up by a hook, temporarily gripped by the slips and then jointed to another pipe. After the joint, the slips is removed and the entire pipe is carefully lowered into the hole, resuming the
drilling. A skilled rig crew can physically accomplish all of those steps in a minute or two.


## The challenge

In this challenge, you should do an Exploratory Data Analysis (EDA) in order to extract useful information for the development of the KPI mentioned in the Introduction (Slip to Slip connection time).
We expect you to:
Describe the data;
Preprocess the data;
Define which strategy you used for missing values, if there are any;
Define which strategy you used for duplicated values, if there are any;
Usually sensor data has embedded some amount of noise. Analysis of such raw data may often fail to give accurate information. Define which strategy you used for dealing with noise.
Machine learning methods are usually based on the assumption that the data generation mechanism does not change over time. However, some series in the dataset don't present this characteristic, having its statistical properties changing over time. Define which strategy you used to deal with this problem.
Identify the most important variables for detecting when the slips is on or off ;
Identify relations between variables;
Build additional features that can help the detection of when the slips is on or off ;
Outline the conclusions you could reached with your analysis;

## Data

The data that represents a multivariate time series collected by sensors during a drilling operation and it's discretized by 1 second. In this operation, the pipe connections happen in the same manner as explained in the Introduction section.
In the data/ folder, you'll find:
challenge_dataset.csv - The file containing the data for the challenge, separated by comma.
variables_dictionary.txt - A text file explaining the meaning of each column in the dataset.

## Solution

After conducting research on the area and talking to Petrobras drilling professionals, I performed a data cleaning and data analysis in order to determine the slip-to-slip connection moments. 
