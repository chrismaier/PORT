======================
Automation - (Level 3)
======================

* Are deploys orchestrated in a way that can be called from an automation tool like Jenkins or Ansible?
* Does the system implement any kind of verification that current system state is "correct"?
* Is there a defined process to execute when an invalid system state is detected and adjust nodes to a known good state?
* Is there automated reporting that ties to a CVE (Common Vulnerabilities and Exposures) database for all software files on the system?
* Can the product manager or other interested party retrieve via API the current configuration state of the system?
* Does the system have an automated way to return a list of the currently deployed application software artifacts?
* Are all data changes performed via API for all the stored data attributes and elements? (no logging in and running SQL commands)
* Are all data element corrections performed via API? (no SQL, LDIF, or other manual back end data manipulation)
* Does the system prevent the submission of ad-hoc data retrieval queries?
* Are all data retrieval and manipulation operations performed by discrete API functions? (no API calls that accept raw SQL etc.)
* Are all system configuration elements stored in a version control repository that feeds a configuration management process or system?
* Are all bulk export operations performed by an ETL job or system? 
* Are all bulk load operations limited to initial system setup, release, and migration events?

