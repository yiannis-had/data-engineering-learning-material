# Data-Engineering-material
## Intro
- https://www.youtube.com/watch?v=qWru-b6m030
- https://www.youtube.com/watch?v=Y6Ev8GIlbxc
- [The AI hierarchy of needs](https://hackernoon.com/_next/image?url=https%3A%2F%2Fcdn.hackernoon.com%2Fhn-images%2F1*7IMev5xslc9FLxr9hHhpFw.png&w=1920&q=75) - *pyramid picture*

## Roadmap
- https://github.com/datastacktv/data-engineer-roadmap

## Python
- https://gto76.github.io/python-cheatsheet/

## SQL
- https://i.redd.it/g79fnqndd6s71.jpg
- https://towardsdatascience.com/sql-cheat-sheet-for-interviews-6e5981fa797b
- https://www.eversql.com/sql-order-of-operations-sql-query-order-of-execution/
- https://www.youtube.com/channel/UCuDWqzSSHgHkD0zBwrIXSNQ/playlists
- https://extendsclass.com/mysql-online.html

## More Python
- https://www.scrapingbee.com/blog/web-scraping-101-with-python/
- https://towardsdatascience.com/introduction-to-pandas-apply-applymap-and-map-5d3e044e93ff

## Articles/Blogs/Discussions/Reddit
- https://martinfowler.com/articles/data-monolith-to-mesh.html
- https://martinfowler.com/articles/data-mesh-principles.html
- https://lakefs.io/the-state-of-data-engineering-in-2021/
- https://www.youtube.com/watch?v=Fvu2oFyFCT0 - *meta* data engineering
- https://maximebeauchemin.medium.com/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a ; https://www.youtube.com/watch?v=4Spo2QRTz1k
- https://www.youtube.com/watch?v=pzfgbSfzhXg - build *frameworks* not pipelines
- https://preset.io/blog/reshaping-data-engineering/
- https://databand.ai/blog/a-data-observability-model-for-data-engineers/
- https://medium.com/capital-one-tech/choosing-between-rest-web-apis-and-message-streaming-8e2f4813a058
- https://blog.discord.com/how-discord-stores-billions-of-messages-7fa6ec7ee4c7
- https://blog.twitter.com/engineering/en_us/a/2013/dremel-made-simple-with-parquet
- https://www.reddit.com/r/dataengineering/comments/p3kpq9/1_year_of_mustread_articles/
- https://www.startdataengineering.com/post/
- https://www.reddit.com/r/dataengineering/comments/pmtenl/data_warehouse_interview_question/
- https://www.reddit.com/r/dataengineering/comments/paid71/best_practices_to_orchestrate_ingestion_into/ha52vu2/ (also check the profile of the [replier](https://www.reddit.com/user/soundbarrier_io))
- https://www.reddit.com/r/dataengineering/comments/q1i98c/python_or_sql_for_etl_or_both/hfgl7fy/
- https://www.reddit.com/r/dataengineering/comments/rnmumx/kimball_vs_inmon_vs_vault/
- https://www.reddit.com/r/dataengineering/comments/r6lhgq/late_data_arrival/
- 
- https://martinfowler.com/articles/patterns-of-distributed-systems/
- https://martinfowler.com/architecture/
- https://discourse.getdbt.com/t/how-we-structure-our-dbt-projects/355
- https://calpaterson.com/how-a-sql-database-works.html

## Official training
- https://academy.databricks.com/user/consume/learning_pathway/42d2099f-7f8a-37ad-b4ba-964d7e8280d0 (johngate10)

## Offline Books
`file:///C:/Users/johng/OneDrive/Documents/Book%20PDFs/Big-Data-and-Databases/`
- https://www.youtube.com/playlist?list=PLeKd45zvjcDFUEv_ohr_HdUFe97RItdiB (DDIA)
- https://www.holistics.io/blog/how-to-read-data-warehouse-toolkit/ (DW Toolkit)

## 6.824: Distributed Systems
- https://pdos.csail.mit.edu/6.824/schedule.html

## Missing Semester of Your CS Education
- https://missing.csail.mit.edu/

## General
- https://github.com/viraptor/reverse-interview
- https://yangshun.github.io/tech-interview-handbook/

## https://www.reddit.com/r/dataengineering/comments/r14k34/which_tech_skills_are_the_most_marketable_in_the/hlwohpr/
No online course can necessarily teach these skills, but instead it comes with experience on the job. Here are a few topics to explore further:
- Writing DRY code 
- SOLID principles
- Creating generic applications that can be extended and applied to similar projects (this mainly falls under “abstraction” and the next point, configuration)
- Configuration: don’t hard-code variables, and make it easy to change configuration separately from logic
- Secrets: never check passwords or keys into git, or add them where visible in plain text (e.g. env vars on a container definition). I prefer fetching at runtime from an encrypted store like AWS SSM or Hashicorp Vault. 
- Debugging: know how to read logs and infer what the true error is from a traceback. Know how to step through code with breakpoints using an IDE. Know how to Google errors before bugging a coworker. 
- Infrastructure: at least know how and where your code is executing. You may not be a DevOps expert (though I’d argue you should start learning), but at least know the features and limitations of your runtime environment, which will eventually help with debugging. 
- Observability: think about what could go wrong, and how you will find out about it. Make sure you are the first to know, not your customers (internal or external). 
- Know when to ask for help: I’ve seen people struggle for days on a problem, then ask someone else and fix it in 5 minutes. You are (probably) on a team to share knowledge and help each other level up. Nobody knows everything, so don’t be afraid to ask for guidance from someone who has solved the problem before. Timebox problems and say if I can’t figure this out alone in X hours, let me ask other people. 

Those are some high level things I think about when it comes to engineering, and notice how none of them are specific to data engineering, or to any tools or frameworks. You can apply these to front end, back end, data science, data engineering, etc and take your career in any direction once you understand what it means to be a true engineer.
