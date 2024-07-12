Overview

This project focuses on developing a data warehousing solution to manage and analyze a publishing company's operations. Utilizing the "publishers" dataset, the solution covers the entire publishing process, from tracking title sales and managing author contracts to handling publisher information and employee details.

Dataset

The dataset includes tables for authors, titles, publishers, sales, stores, discounts, royalties schedules, title authors, publisher information, and employees and jobs. These tables enable a comprehensive analysis of the publishing process.

Dimensional Modeling

High-Level Modeling: Our bus matrix captures core business processes such as Title Sales, Store Sales, and Publisher Owned Titles, each associated with a specific fact table.

Detail-Level Modeling: Identified dimension tables include dim_title, dim_store, dim_discount, and dim_publisher, among others, which provide context for the facts.

Implementation

Tools Used: Azure Data Studio, MinIO S3, Snowflake, DBT Cloud, and Power BI.

Process: Data is initially staged in Snowflake, transformed using DBT Cloud based on our business processes, and visualized using Power BI dashboards.
