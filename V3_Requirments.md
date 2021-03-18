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

 - View/Edit/Create region/forest level template info
	- Edit tree default values
	- Edit Audit Rules

  	dont need
	- edit volEq
	- edit reports
	
 - Export data as csv, excel, pdf
 - Import data as csv, excel (low priority)

 x Design and optimize Cruises based on historical/recon data 
 x View/Edit processing settings (Volume Equations, Reports,  Tree Defaults, ...)
 

### Web Application National Cruise 
---------------------------------- 

### Provision Servers
	Dev - Requested and Pending provisioning.
	Test - Architecture Approval Needed
	Prod - Architecture Approval Needed
	
#### EAD CI pipeline / Github

### User Roles:
	Define user roles and actions.
	
#### Authentication service
	Login.gov for externals  (proof of concept)
	Eauth for Internals (FSAPPS)
	
#### Security Review
	Transferring data to and from the national cruise system to mobile devices. 
	(could require specific architecture design decisions. )

#### National Database
	A super set of the design used for SQLite, includes user model, as well as organizations and teams
	Processing / Stats tables or views for speed.

#### Web Interface
	Everything that desktop application does plus:
	- manage users, organizations and teams
	- control user access to projects based on roles, orgs and teams
	- view generated reports and manage stored reports

#### Cruise Template Service	

#### Upload data Service
	Ingest cruise data and merge with database

#### Processing Service
	Processes cruise data
	Compiles Stats

#### Reporting Services
	Gather Requirements on what is a report vs data check.
	
#### Testing White box Internal 
	Develop test plan / cases
	
#### Testing Black box
	User Acceptance Testing
	
#### Release Management and Deployment 

#### Training and Documentation