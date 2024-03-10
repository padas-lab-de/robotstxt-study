---
layout: table
table_include: tables/overview.html
---

Overview
====

Since 2016, [Common Crawl](https://commoncrawl.org/) regularly publishes the [robots.txt files](https://commoncrawl.org/blog/robotstxt-and-404-redirect-data-sets) that have been fetched during the CCBot's web crawl. The [robots.txt dumps](https://commoncrawl.org/the-data/get-started/) are published along with the regular WARC, WAT and WET files in intervals of approximately two to three months. We have parsed the last robots.txt dumps of each year since 2016, resulting in eight years of collected statistics.

* [File statistics](file-statistics) - Average content length (file size), Average number of lines and user agents
* [Top user agents](top-user-agents) - Most frequently mentioned agent names
* [User agent bias](user-agent-bias) - Number of *disallow all* instructions per user agent
* [Resources](resources) - Dataset of extracted links to valid robots.txt files and sitemaps

The following table outlines each year together with the period, in which the robots.txt were fetched (capture time). As the dumps also contain unsuccessful fetches (e.g. HTTP status code 404) and unparsable files, the table also yields the total number of successfully parsed robots.txt files and gives an estimation of the adoption rate of robots.txt among websites (to be more precise, hosts).
