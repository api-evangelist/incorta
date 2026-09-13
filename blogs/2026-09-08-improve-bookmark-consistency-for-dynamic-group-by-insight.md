---
title: "Improve bookmark consistency for dynamic group by insight-state columns"
url: "https://community.incorta.com/t5/dashboards-analytics-discussions/improve-bookmark-consistency-for-dynamic-group-by-insight-state/m-p/7112#M854"
date: "2026-09-08"
author: "mmastropaolo"
feed_url: "https://community.incorta.com/wdmcw32433/rss/Community?interaction.style=forum"
---
When saving a bookmark with specific groups selected in a dynamic group by aggregated table, the bookmark "remembers" the columns that you have chosen. More specifically, it remembers the column numbers that you have chosen - this can be proven by looking at the tenant xml of a dashboard with one of these bookmarks. The problem is that these column numbers within the saved bookmark xml do not change even if the respective insight is later updated and a new column is added to that insight.
