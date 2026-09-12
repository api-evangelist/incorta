---
title: "INC_03020207 – History MV fails after adding new column to source PySpark MV"
url: "https://community.incorta.com/t5/data-schema-discussions/inc-03020207-history-mv-fails-after-adding-new-column-to-source/m-p/7008#M598"
date: "2026-04-28"
author: "saiteja1_cdns"
feed_url: "https://community.incorta.com/wdmcw32433/rss/Community?interaction.style=forum"
---
We are using a PySpark script inside Incorta to call an API and load data into a Materialized View (full load). Since loading this MV directly into a table is not feasible, we store the data in a history Materialized View (incremental mode) to maintain snapshots. When a new column is added to the source MV, the full load completes successfully; however, the incremental load of the history MV fails with INC_03020207 (schema mismatch) .
