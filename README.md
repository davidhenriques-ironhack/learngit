<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Project: Competitive Landscape

## Content

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Project Deliverables](#deliverables)

<a name="project-overview"></a>

## Project Overview

You were hired by Ironhack to perform an analytics consulting project to understand Ironhack's competitive landscape: which other coding schools are there and what drives their success or lack thereof relative to Ironhack.

Your mission is to design, create and populate an appropriate database with information about coding schools that are our competition, as well as design suitable queries that answer business questions of interest (to be defined by you).

---

<a name="project-overview"></a>

## Getting Started

The notebook attached to the project connects to a bootcamp review website (www.switchup.com) and scrapes some information into dataframes. This will be the basis of the information to design your database. Read the script and get a general understanding each function. Comment the code appropriately.

*   Populate the list of schools with a wider variety of schools (how are you going to get the school ID?)

* Take a look at the obtained dataframes. What dimensions do you have? What can work as useful metrics? What keys do you have? How could the different dataframes be connected?

* Go back to the drawing board and try to create an entity relationship diagram for tables available

* Once you have the schemas you want, you will need to:
  - Create the suitable SQL queries to create the tables and populate them
  - Run these queries using the appropriate Python connectors
  - Crucial hint: check out the following tutorial:
https://www.dataquest.io/blog/sql-insert-tutorial/
  

---

<a name="deliverables"></a>

## Project Deliverables

We will henceforth list the requirements for each project in three groupings to help you prioritize your work

* MVP (Minimum Viable Product): these are the absolute minimum requirements that you will have to achieve for your project to be considered completed. *They should absolutely be your priority* as failure to meet these requirements means an insufficient delivery, even if you go above and beyond on other requirements. Plan around unforesseable situations to make sure you have time to at least deliver the MVP. A good way of doing this is to plan on having the MVP well in advance of the deadline for the project.

* Expected improvements: these are suggestions on how to improve your product, features that are not critical but that we expect most students to be able to deliver *some* of these features. They will often be stated in more open-ended description so that you can customize and differentiate your project and make it a tailored part of your portfolio.

* Nice-to-haves: these are suggestions on how to go above and beyond. We do *not* expect your products to contain these features / use these technologies (but we will not actively discourage you from pursuing them as well). The nice-to-haves exist more to help you find resources that may not be taught in class and put some icing on your product, potentially even *after* the bootcamp.

The Deliverables for this project are:

#### Minimum Viable Product

[ ] Files that contain your solution submitted via a GitHub repo

  - .py or .ipnby files to extract and transform the data scraped in the attached notebook as well as running the business analysis

  - An exported .sql file with the final schema

  - A requirements.txt file that allows the replication of your Python environment

[ ] A presentation that showcases your product

  - The presentation includes a business analysis built on top of your database where clear business hypotheses should be tested and some actionable conclusion must be presented

  - The presentation includes a component about design choices for your database, with at least a presentation of the final ERD

  - The presentation includes a component about technical challenges faced

#### Expected improvements

[ ] Additional depth in business analysis

  - Deeper data gathering: more of the same datapoints (schools, locations, comments) AND/OR different data points (prices, recommendations, etc) 

  - Enriching data gathering: more sources of data (e.g. demographics by city, salaries per country etc.)

  - Multi-layered questions: use your answers to basic hypotheses to generate more refined hypotheses (which may require more sophisticated scraping/ETL)

  - Charting: use visual intuition to drive your analysis


[ ] Improved engineering and design of your solution

  - Deployment of the solution to a cloud database

  - Creation of auxiliary functions that test the database for data quality issues


#### Nice-to-haves

[ ] Improved engineering of solution

  - Encoding of primary key - foreign key relation in database design

  - Differential update of database (include only most recent data when you re-run the script)

