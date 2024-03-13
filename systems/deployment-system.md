# Deployment system

## Stocks

* Pull requests
* Ready commits
* Deployed commits
* Incidents
* Reverted commits

## Flows

* Code review rate
* Deploy rate
* Defect rate
* Recovery rate
* Debug rate

## System

* ___Pull requests___ are converted into ___ready commits___ based on ___code review rate___.
* ___Ready commits___ convert into ___deployed commits___ at ___deploy rate___.
* ___Deployed commits___ convert into ___incidents___ at ___defect rate___.
* ___Incidents___ are remediated into ___reverted commits___ at ___recovery rate___.
* ___Reverted commits___ are debugged into new ___pull requests___ at ___debug rate___.
