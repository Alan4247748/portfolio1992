---
f_category: Work
f_sort-order: 2
title: Data warehouse transformation in the food sector
f_post-summary: >-
  A case study about a European food producer moving towards real-time data in
  the food sector.
f_main-image:
  url: >-
    https://uploads-ssl.webflow.com/62bacadaf1acd7b704187dd2/62c826fc47e4132470ad0de5_Artboard%2015.png
  alt: null
f_thumbnail-image:
  url: >-
    https://uploads-ssl.webflow.com/62bacadaf1acd7b704187dd2/62c82703726af143c8deeec8_Artboard%2014.png
  alt: null
slug: data-warehouse-transformation
updated-on: '2022-07-10T13:30:15.232Z'
created-on: '2021-08-25T07:01:10.389Z'
published-on: '2022-07-10T13:55:17.543Z'
f_layout: "Layout 1\_"
layout: '[post].html'
tags: post
---

01\. THE QUESTION
-----------------

A mid-sized company in the food retail and production sector approached Addestino with a request to audit their existing Data warehouse infrastructure, draft a transformation plan, and help them execute it.

The customer focused on one type of food, but as consumers’ food patterns shifted, they significantly broadened their portfolio. The complexity of their operations increased, resulting in a need for better insights, predictive models, and smoother reporting. This all culminated in a significant strain on their existing data architecture systems.

02\. THE PROCESS
----------------

We started by looking at the pure technology stacks and found several streets running in parallel. We found a whole SAP street, a .NET environment with 100 plus applications and some exotics, yielding a hybrid environment. We then looked from the user’s point of view and the business context to understand.

*   What are the reporting demands?
*   What are the use cases?
*   What are the key business drivers?

We drilled down into the financials to understand operating costs, maintenance efforts, and IT roadmaps. We looked at the data quality from different dimensions and used it to create a map of the world.

03\. THE INSIGHTS
-----------------

We applied set-based design thinking, where we evaluated multiple routes and merged them into a single solution. The existing data warehouse was solid. The challenge was in the disparity between streets and data sources. So, we defined an ETL layer, **see infographic above,** where we could extract, transform, and load the data from different silos. For example, (retail vs production vs logistics,) we could then capture all the data and integrate it into their existing central warehouse.

The second step was selecting an open-source data model which works well in retail environments and can be tuned to production environments. We could then model all of that data and add the relationships into a schema which defines all the tables and relations—resulting in many insights.

*   Sale price
*   Volume sold
*   When was it sold?
*   Where was it sold?

From there, we could make a generic data model. The customer had several reporting sites where they did shadow and ad hoc reporting. Instead of going through the Data warehouse, they worked straight on operational data systems. It’s logical because they needed fast access to the data, and the Data warehouse was too slow and didn’t have all of the data. However, the disadvantage is that you can not reproduce what you did because; as soon as you measured the data, it changed.

We conceptualised a system where all data entered the loading dock and designed an update frequency of thirty minutes. Consequently, we could eliminate the need for shadow and ad hoc reporting, creating a beautiful business intelligence environment with integrated reporting and dashboards.

04\. THE RESULT
---------------

We presented the layout to our client, and they were delighted because much of their prior investments in the Data warehouse and environment could be used.

In a three-month project, we defined a transformation approach with maximal reuse of existing infrastructure and a programme where we deliver results every month instead of a two-year, lengthy roadmap at high risk and high investment.

It is a solid illustration of lead time and risk reduction by creating business value combined with a focus on technology. At Addestino, we’re up for the challenge, no matter the complexity.

‍
