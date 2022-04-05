---
layout: post
title: OLAP vs OLTP
image: /assets/img/blog/steve-harvey@0,25x.jpg
description: >
  OLAP vs OLTP, let's draw the comparison and understand which to use in which condition.
---

# OLAP vs OLTP

In this post, we will learn about the difference between OLAP and OLTP. 

* toc
{:toc}

OLTP and OLAP: The two terms look similar but refer to different kinds of systems. Online transaction processing (OLTP) captures, stores, and processes data from transactions in real time. Online analytical processing (OLAP) uses complex queries to analyze aggregated historical data from OLTP systems.


### What is OLTP?
OLTP - Online Transaction Processing ingests and maintains transaction data of any application. It takes care of each transaction taking place in the system and each transaction corresponds to a unique record in the database. The idea is to process the data fast and frequently. If a transaction fails, built-in system logic ensures data integrity.

Example - banking system like credit card activity. This data is used in real-time to identify any fraudulent activity.

### What is OLAP?
OLAP - Online Analytical Processing is used for Data Analysis or Business Analytics and Intelligence. The data here is not transaction basis rather it is an aggregated data retrieved from multiple database systems. 
OLAP databases and data warehouses give analysts and decision-makers the ability to use custom reporting tools to turn data into information.Query failure in OLAP does not interrupt or delay transaction processing for customers, but it can delay or impact the accuracy of business intelligence insights.

Example - Data Warehouse of User Tracing Data, User Personal Information. This data can be analyzed to give personal recommendation to a user.