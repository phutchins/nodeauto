# nodeauto
## Goals
+ The GUI will only interface with the API via REST
+ All features and functions should be implemented on the backend first
+ API automatically has the ability to utilize new features on the backend
+ Security should be first in mind
+ User membership and permissions is taken into account from the beginning


## Backend
The backend will be comprised of a runner script that kicks off tasks categorized in to modules that are auto laoded when dropped in

### Runner

### Modules

### Resources (libraries to make working with the OS transparent)
#### Node Level
+ Template
+ File
+ Link
+ Service
+ Scheduler
#### Cluster Level
+ Cluster
+ Service (restarts possible with no downtime)


## API
+ Authentication


## Frontend

### Cluster Administration
### Cluster visualization
+ Utilize D3 for viewing cluster
+ Shows Health of cluster
  + Network connectivity
  + Connection latency
  + Application Health (with ability to add custom checks that could control a loadbalancer)
  + Loadbalancer Status
  + System Resources
  + Firewall Rules & Open Ports
  + Errors & Error Rates
+ Ability to move services from host to host via dragging service
