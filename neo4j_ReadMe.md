This is a draft

# Idea
- Take as input the various <a href="#InputDataSources">lists</a> that folks are creating 
- Model this input as a graph, using Neo4j
- Make the graph database available as a tool for use by the community
 
# Goal
- Create a tool to visualize/represent/understand/analyze EPA datasets using graph databases
- Build an interface very similar to this (link to ICYJ Panama Papers) 
- Tech Tool for #DataRefuge #DataRescue #GuerillaArchiving projects

# Why
- Can be used to 
  - Help understand the EPA data universe, explore structure and infrom priorities
  - Track growth in nomination and archival of the EPA data network
  - Prioritize monitoring efforts (to see if links are active) 
  - Detect shifts in vulerability 

# Steps
- Model the EPA data universe and nominations as a graph using Neo4j 
- Seed the graph with source data - use data from nomination and scraping projects as data source for the graph model 
- Process on how to add relationships to the data model 
- Ability to visualize, browse and query EPA data by value, vulnerability, archival status and other properties
- Interface to share and interact with data product 

# Data Sources
- Use data lists / data catalogs from:
  - Nominations: from projects where people are creating lists of the data, and flagging for protection 
  - Scraper tools 
  - Other Events: 
  - Other Projects: 

- Seed Data 
  -  Gureilla Archiving Event in Toronto, Hackathon Group 1 : 
  - <a href="http://www.ppehlab.org/datarefuge">PPEH Lab Data Refuge </a> : Gov Climate Datasets Archive
  - https://nepis.epa.gov/EPA/html/pubs/pubtitle.html

# Graph Model 

- Entities:
  - Agency
  - Program
  - Datasets
  - Resources
  
- Relationships (insert graph)


# How to Use 
- Download the Neo4J database here 
- Requirements:
  - ..
  - ..
  - ..


# Challenges
- Data quality : completeness, duplicates, currency

# Forward Looking
- Infer schema and meta-data from data sources using projects like this (insert link) 
- Create a data portal for all additional input sources (using CKAN for meta-data and API) 
- Set up scripts to import new data sources, infer schema and meta-data into the Neo4j graph data model from the portal
- Set up process for new additions of data
- Set up process for defining relationships

# ICYJ Approach
- They extracted the metadata of documents using Apache Solr and Tika, 
- Then connected all the information together using the leaked databases, 
- Creating a graph of nodes and edges in Neo4j and 
- Made it accessible using Linkurious’ visualization application. 
 
# Contributors


# Inspiration
ICYJ 

