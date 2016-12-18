This is a draft

# Idea
- Create a tool to visualize/represent/understand/analyze EPA data universe as a network graph, using Neo4j
- The various <a href="#InputDataSources">lists</a> that folks are creating as part of the Nomination & Scraper projects would be used as input data sources
- Model this data collection as a graph database and make a tool tor visualization / query the EPA data network
 
# Goal
- Build a Neo4j project with an interface very similar to <a href="https://neo4j.com/blog/panama-papers-graph-database-download/">this</a> (link to ICIJ Panama Papers with Neo4J) 

# Why
- Useful tech tool to support toolkit project for #DataRefuge #DataRescue #GuerillaArchiving projects
- Can be used to 
  - Ability to visualize, browse and query EPA data by value, vulnerability, archival status and other properties 
  - Help understand the EPA data universe, explore structure and infrom priorities
  - Track growth in nomination and archival of the EPA data network
  - Prioritize monitoring efforts (to see if links are active) 
  - Detect shifts in vulerability 

# What we did in the Hackathon (Dec 17 2016)
- Prelimiary graph data model of the EPA data universe using data from the 
- Seeded the graph with some of this source data 
- Set up a basic interface to share and interact  

# How to Use 
- Download the Neo4J database and start exploring
- Script to import new data lists
- How to define relationships

# Identified Data Sources
- Nominations spreadsheet at the Gureilla Archiving Event in Toronto
- EPA site maps scraped as XML or CSV
- EPA search tools
- <a href="http://www.ppehlab.org/datarefuge">PPEH Lab Data Refuge </a> : Gov Climate Datasets Archive
- https://nepis.epa.gov/EPA/html/pubs/pubtitle.html

# Preliminary Graph Model 

- Entities:
  - Agency
  - Program
  - Datasets
  - Resources
  
- Relationships (insert graph)
 - Program publishes data sets
 - Data set contains Resources
 - Resource is described by Meta-data

# Resources
- https://neo4j.com/blog/analyzing-panama-papers-neo4j/


# To Do 
- Refine graph data model 
- Set up process for new additions of data
- Set up process for defining relationships and adding to graph
- Infer schema and meta-data from data sources using projects like this (insert link) 
- Create a data portal for all additional input sources (using CKAN for meta-data and API) 
- Set up scripts to import new data sources, infer schema and meta-data into the Neo4j graph data model from the portal
- Get data lists / data catalogs from  Nominations (i.e from projects where people are creating lists of the data, and flagging for protection),Scraper tools, Other Events, Other Projects: 


# ICIJ Approach
- They extracted the metadata of documents using Apache Solr and Tika, 
- Then connected all the information together using the leaked databases, 
- Creating a graph of nodes and edges in Neo4j and 
- Made it accessible using Linkurious’ visualization application. 
 
# Challenges
- Data quality : completeness, duplicates, currency

# Contributors
