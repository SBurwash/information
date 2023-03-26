# Description
This repository is solely meant as a quick respository to list information on one Stephane Burwash (Sort of like a CV, but a lot less pretty). 
It will probably quickly become disogranized, but a disorganized repo is better than none at all.

# Presentations
A list of all my presentations, in chronological order.
### February 17th, 2023 - Montreal MLOps Meetup Kickoff

**Event Description**: Kickoff of new MLOps community in Montreal. The goal was to test the waters and size up the interest of the community. We did not have high expectations of the turnout. Finally, we got around 110 "going" responses on the Meetup page, with around 60-70 physical attendees at the end.

**Presentation Description**: A TLDR on data ops and how MLOps practitioners should actively pay attention to data engineering best practices (and not only worry about models and ML pipelines). 

**Resources**
- [Link to event details](https://www.meetup.com/montreal-mlops-community/events/291406311).
- [Link to presentation slides](/resources/mlops_conference_slides.pdf).


### March 22nd, 2023 - Montreal Analytics dbt Meetup (data quality)

**Event Description**: Meetup on #dataquality and #datatesting. The first presentation was made by me presenting [Elementary](https://www.elementary-data.com/) as a data observability solution, while the second and third were about [data-diff](https://www.datafold.com/dbt) and data testing best practices respectivaly.

**Presentationed description**: Presentation of the real usecase of why we originally impletemented elementary at Potloc (dbt test artifact storage), and why we subsequently fell in love with the integration (anomaly detection + UI). Also gave a few pointers on best practices when trying to tackle integrity issues (kickoffs, test to monitor, test to have action items, etc.). 

**Resources**:
- [Link to event details](https://www.meetup.com/montreal-dbt-meetup/events/291595000).
- [Link to presentation slides](/resources/dbt_meetup_march_22nd_2023.pdf).


# Reading material / teachings
A list of different articles / books I have read and what we learnt from them.

### Agile Data Warehouse Design
[Link to book](https://www.amazon.ca/dp/0956817203/ref=cm_sw_r_api_i_RN0Z16B6Q3SBJ0EG39PQ_0)

**Finished reading**: January 1st 2023

**Synopsis**: Agile data warehouse design and how to build a data mart from the ground up.

**Lessons / Concepts**
- Dimensions / Facts
- Agile dimensional modeling using Business Event Analysis & Modeling (BEAM)
- Modelstorming: data modeling that is quicker, more inclusive, more productive, and frankly more fun!
- Telling dimensional data stories using the 7Ws (who, what, when, where, how many, why and how)
- Modeling by example not abstraction; using data story themes, not crow’s feet, to describe detail
- Storyboarding the data warehouse to discover conformed dimensions and plan iterative development
- Visual modeling: sketching timelines, charts and grids to model complex process measurement – simply
- Agile design documentation: enhancing star schemas with BEAM dimensional shorthand notation
- Solving difficult DW/BI performance and usability problems with proven dimensional design patterns

### Fundamentals of Data Engineering
[Link to book](https://www.amazon.ca/Fundamentals-Data-Engineering-Robust-Systems/dp/1098108302).

**Finished reading**: April 1st 2023

**Synopsis**: Everything you need to know about data engineering, from setting up on-prem warehouses all the way to managing data marts and implementing reverse-etl. Incredibly insightful, but a bit dense - would recommend this as a book once you have a basic grasp on concepts, or else you may gloss over some key insights (god knows I have).

This book is much more focused on best practices than on actual technologies, which makes it a bit more timeless.

**Lessons / Concepts**:
- Get a concise overview of the entire data engineering landscape
- Assess data engineering problems using an end-to-end framework of best practices
- Cut through marketing hype when choosing data technologies, architecture, and processes
- Use the data engineering lifecycle to design and build a robust architecture
- Incorporate data governance and security across the data engineering lifecycle

