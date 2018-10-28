=================
Llama - (Level 2)
=================

* Have logging / monitoring / alerting thresholds been identified and documented?
* Are we being notified by an alerting system when an issue arises?
* Do we receive a system down alert before our customer calls us?
* Does some form of monitoring exist, and does the monitoring see critical metrics? (system down)
* Does the system implement server or host down alerting?
* Are application stack traces logged to a different file than the operational log? 
* Does the application have its own dedicated log file?
* If the system is logging to the local hard drive, has log rotation been implemented?
* Does the system collect usage data? (number of current users, current bandwidth, hits per hour, etc)
* Have the systems data plane and control plane microservices availability reporting been broken up and reported on independently?

