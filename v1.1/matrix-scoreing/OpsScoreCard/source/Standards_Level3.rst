=====================
Standards - (Level 3)
=====================

* Is the system using the organizational standards for hardware, software, and support? (or migrating to them)
* Does the system implementation follow industry best practices?
* Does the system meet most security & compliance best practices as defined by GSS and Security Engineering?
* Has the least privilege access model been implemented for all data and system access?
* Are all code artifacts written in a manner consistent with community and industry best practices?
* Is the code packaged in a manner consistent with the language it is written in? (egg, wheel, PyPy, Jar, maven, gem, etc.)
* Are all code artifacts signed during the build process?
* Has a code review process been implemented that follows industry best practices? (at least two reviewers etc.)
* Have network segregation and isolation standards been implemented?
* Have all the network ports necessary to run the application been identified and documented?
* Have host level access controls been implemented to prevent all non-essential network communication between hosts?
* Is SSH access to all nodes limited to the bastions and explicitly denied between nodes? (bastions/deployment automation)


