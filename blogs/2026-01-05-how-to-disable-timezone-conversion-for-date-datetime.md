---
title: "How to Disable Timezone Conversion for Date/Datetime Columns in Incorta?"
url: "https://community.incorta.com/t5/data-schema-discussions/how-to-disable-timezone-conversion-for-date-datetime-columns-in/m-p/6876#M591"
date: "2026-01-05"
author: "stalha_tariq"
feed_url: "https://community.incorta.com/wdmcw32433/rss/Community?interaction.style=forum"
---
We are running into an issue where date or datetime values are shifting by one day after being loaded into Incorta. Our source system does not include any timezone information in these fields, but Incorta still seems to apply a timezone conversion somewhere during ingestion or display. Because of this, dates are not preserved as‑is, and the shift is impacting downstream reporting.
