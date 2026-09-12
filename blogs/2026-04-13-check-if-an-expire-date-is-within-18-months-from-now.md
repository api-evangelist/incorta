---
title: "check if an expire date is within 18 months from now"
url: "https://community.incorta.com/t5/data-schema-discussions/check-if-an-expire-date-is-within-18-months-from-now/m-p/6993#M594"
date: "2026-04-13"
author: "Samiran"
feed_url: "https://community.incorta.com/wdmcw32433/rss/Community?interaction.style=forum"
---
Is this expression supposed to work? SO that the count of such "matches" can be aggregated in an insight to report on: case( (addMonths( $currentDate , 18 ) > WPR_test.Lease.Expire_Date ) , 1 , 0 )
