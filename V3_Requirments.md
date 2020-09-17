# National Cruise System (NatCruise) Version 3 Requirements Document

## Desktop/Mobile

### FScruiser Android application
 - Cruise Data Entry
 - Spatial Data Collection

### Desktop application
 - Edit/Create cruise
 - Cruise Data entry
 - View Cruise Data in data grid that allows filtering and ordering
 - Merge cruise files
 - Export data as csv, excel, pdf
 - Import data as csv, excel (low priority)
 - Design and optimize Cruises based on historical/recon data 
 - View/Edit processing settings (Volume Equations, Reports,  Tree Defaults, ...)
 - Process (using processing web service)
 - View/Edit/Create region/forest level template info
 
 

### Web
---- 

#### Auth service
Authenticate non-forest service users, for forest service users we can probably use e-auth

#### Database
A super set of the design used for SQLite, includes user model, as well as organizations and teams

#### Processing service
Processes cruise data and generates output documents

#### Sync Service
Ingest cruise data and merge with database

#### Cruise Template Service
 - 

#### Web Application
 Everything that desktop application does plus:
 - manage users, organizations and teams
 - control user access to projects based on roles, orgs and teams
 - view generated reports and manage stored reports