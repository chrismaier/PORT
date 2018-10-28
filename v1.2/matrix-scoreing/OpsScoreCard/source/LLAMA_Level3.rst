=================
Llama - (Level 3)
=================

* Does the system have a centralized logging solution in place?
* Have log entry format standards for all portions of the system been defined and documented?
* Are alerts published to a dashboard that all support teams can consume to know that a system is down?
* Is all logging and monitoring data visible to the company? 
* Is the logging and monitoring data dashboard protected by SSO login?
* Does the system have a usage dashboard? (number of current users, current bandwidth, hits per hour, etc.)
* Is sensitive log data filtered out or hashed before being shared, archived or made searchable?
* Have known thresholds been defined and documented?
* Are logging and audit data used to trigger monitoring alerts when known thresholds are exceeded?
* Does the system have defined errors and error codes and is proper context provided in notifications?
* Can a Racker determine which specific customers are on the alerting device?
* Is there a reporting mechanism for failed provisioning attempts, hung processes, and other poor customer experience opportunities related to the product (beyond is it just “up” or “down”)
* Do the customer facing control panel(s) integrate monitoring alerts to show contextually relevant information to customers when there is an issue?
* Are all create, update, and delete activities logged and tracked?
* Are alert escalations defined?
* Are alert escalations tested every 30 days or less?
* Are alerts provided by way of NON asynchronous delivery? (NOT using SMTP for alerts)
* Do all alerts provid actionable items or tasks?
* Can the person being alerted restore the system to a functional state without additional data?
* Can the logging level be altered without requiring the applicaiton server to be restarted?
* Can the logging level be altered in a manner that preserves the current application server state?
* Does the availability dashboard break availability up in to the three parts (UP, Degraded/Impacted, Down/Unavailable)?
* Are all events for this product made available in Cloud Feeds or relevant usage system?
* Are CRUD logs available to customers to track event history?

