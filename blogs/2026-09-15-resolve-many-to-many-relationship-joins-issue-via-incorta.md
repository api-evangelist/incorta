---
title: "Resolve Many to Many relationship Joins issue via Incorta Virtual Joins"
url: "https://community.incorta.com/t5/data-schema-discussions/resolve-many-to-many-relationship-joins-issue-via-incorta/m-p/7113#M604"
date: "2026-09-15"
author: "nikhil_cr"
feed_url: "https://community.incorta.com/wdmcw32433/rss/Community?interaction.style=forum"
---
Goal: I have a CustomerGroup table where a customer can appear multiple times (one row per Concept per time period), so customer_code is not unique in this table. I want users to filter by Concept on a dashboard and have that filter apply to our sales-orders table (SL_CustomerOrders) - showing only sales for customers who belong to the selected Concept - without duplicating or losing any sales rows . Schema setup: Customer (master table, unique key: Code + Company) CustomerGroup - Child of Customer, joined on CustomerGroup.Code = Customer.Code AND CustomerGroup.Company = Customer.Company.
