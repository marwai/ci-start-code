# Ci start code 
SLDC - Software development lifecycle - is a framework to define tasks performed at each step in the software development process
## Three main stages   
### ```Development```
 
### ```Testing``` - Ran tests to fail, fix,
example runnig nginx, past/fail. Until all testing it working under rake spec
integration tests/unit tests and then when all quality assurance, user acceptance testing accepts 
the system when connecting to other users. 
- Load balancer should be implemented when limit has been reached, letting know user limit has been reached before 404 page. 
Product is not given to user on live or client until testing has been implemented 
- Not all the tests has to be automated
- Test stages depends on company: defined unit testing for each line of code. In our case, jenkins will be used.

### ```Deployment (Production Environment)```

## Pre-DevOps Time
Historical was very slow. DevOps was introduced to acquire quick deploymet time, faster testing time. 

## Benefits
- Modernising things 

## What's difference CI delivery and CI deployment
- Ci delivery
	- Sends it constant state to be ready for deployment 
	- Ci delivery is after integration and done manually (Node app.js manually) and operates before the release to the client
- Ci Deployment 
	- Ci deployment is done automated with reverse proxy using just node app.js - only when all tests pass - After release to client 
