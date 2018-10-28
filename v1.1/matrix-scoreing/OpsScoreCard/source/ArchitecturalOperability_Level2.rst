=====================================
Architectural Operability - (Level 2)
=====================================

* Has the operations team been involved in planning of the system prior to writing any code?
* Has this application / system eliminated all shared user accounts and shared access?
* Are all components of the system deployed in a production data center? (non lab)
* Have key capacity metrics been documented and made available for consumption?
* Does the system have a defined maximum sizing / maximum load / maximum requests / maximum throughput based KPI? (key performance indicators)
* Are the capacity expansion thresholds defined? (when would operations or auto-scale add capacity and what type)
* Has a capacity expansion test been performed? (add new servers, add a new region, etc)
* Has the system been designed in a manner that allows for impersonation instead of requiring the customers API key?

