---
title: "Tracking Data lineage from Dashboard -> Business view -> Physical tables"
url: "https://community.incorta.com/t5/dashboards-analytics-discussions/tracking-data-lineage-from-dashboard-gt-business-view-gt/m-p/7017#M846"
date: "2026-04-30"
author: "Rohith"
feed_url: "https://community.incorta.com/wdmcw32433/rss/Community?interaction.style=forum"
---
I have a use case where I want to track all the columns used in a dashboard back to the business schema I am pulling from and also need the source column which points to the physical schema but I also need the capability to track lineage of these columns across the physical schemas in a table insight or an mv. Currently, the dashboard’s source column points to the Silver layer, which I can retrieve using inspector metadata. However, I also need the ability to track lineage across physical schemas—for example, from Silver back to Bronze—either at the column level or, if that’s not feasible, at 
