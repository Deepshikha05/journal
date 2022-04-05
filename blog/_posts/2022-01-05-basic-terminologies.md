---
layout: post
title: Introduction to Data Warehouse
image: /assets/img/blog/jj-ying.jpg
description: >
  Introduction to Data Warehouse and basic terminologies
---

# Basic Terminologies

In this post, I will be covering about the basic terminologies that I have learned and make use of. 

* toc
{:toc}

### Basic Terminologies

1. **Data Warehouse**: Data Warehouse is a type of Data Management System that supports and enable Business Intelligence. Analytical processing within a DW is performed on data that has been readied for analysis, contextualized, and transformed with the purpose of generating analysis based insights. 
- Can contain only Structured Data - data that is clean and easy to query.
- Reliable.
- Hard and expensive to scale.
- Loss of valuable potential by not taking advantage of unstructured data.
- expensive to build for large volume of data.

2. **Data Lake**: Data Lake stores unfiltered data to be used later. Data is collected in raw form from various sources like business apps, social media, IoT devices and more. The structure, integrity, selection and format of various datasets is derived at time of analysis.
- Can hold different types of data.
- Easier to scale.
- Rely on cloud storage which is cheap [s3]. This allows organizations to capture and keep all of their data even if they are not quite sure what to do with it.
- Less expensive - separate data storage costs from data compute costs.
- Query speed can be imapcted in Data Lakes.

3. **Data Mart**: A data mart is a simple form of DW focused on a single subject or line of business. With a data mart, user can access data and gain insights faster, because they don’t have to spend time searching within a more complex DW or manually aggregating data from different sources.

### Difference between DW, Data Lake and Data Mart
DW often contain large amounts of data, including historical data. The data within a DW usually is derived from a wide range of sources, such as application log files and transactional applications. A DW stores structured data, whose purpose is usually well-defined.

A Data Lake allows organizations to store large amounts of raw structured and unstructured data to immediately make it available for real-time analytics, data science, and machine learning use cases. 

The key difference between a Data Lake and a DW is that data lakes store vast amounts of raw data, without a predefined structure. Organizations do not need to know in advance how the data will be used.

A data mart is a simple form of a DW that is focused on a single subject or line of business, such as sales, finance, or marketing. Given their focus, data marts draw data from fewer sources than DW. Data mart sources can include internal operational systems, a central DW, and external data.