==========================
Recoverability - (Level 3)
==========================

* Do notifications get sent via a real-time messaging protocol when a failure is detected?
* Is the user and system data replicated to secondary data center? (real-time or as a backup)
* Are all software components actively developed and maintained by a dedicated development team?
* Is there a documented manual process for recreating system components / environments?
* Has the system recreation process been successfully been tested?
* Is there a documented manual process to recover the system and user data?
* Has the recovery process been tested and resulted in a successful recovery of all system and user data?
* Are recovery tests performed at least every 30 days or prior to a release?
* When doing a release, have the backout procedures been successfully tested?
* Does the recovery SLA accurately reflect the time to recover? (based on a successful recovery test)
* Have network device fail-over testes been executed and resulted in succss with zero down time to the application?
* If an error occurs, is any data entered by the user retained for reprocessing? (eventual consistency)
* If the product stores data, has the product been tested with backup solutions (Cloud Backup, imaging, Commvault)?


