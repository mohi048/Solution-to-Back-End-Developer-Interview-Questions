# Solution-to-Back-End-Developer-Interview-Questions




Questions source -: https://github.com/arialdomartini/Back-End-Developer-Interview-Questions

Q - What is downside of caching ?

A - stale data , overhead , complexity

  Stale data - you are at risk of presenting old data that's no longer relevant to the new situation

  overhead data - excess data 

  complexity - leads to more code that you need to maintain and understand.

-----------------


Q - Scale out vs scale up: how are they different? When to apply one, when the other?

A - **Scale-up** is done by adding more resources to an existing system to reach a desired state of performance. It is taking what you’ve got, and replacing it with something more powerful.

The time it takes to procure additional recourses to scale-up a given system could take weeks or months in a traditional on-premises environment while scaling-up in the cloud can take only minutes.


**Scale-out** is usually associated with distributed architectures. It takes the infrastructure you’ve got, and replicates it to work in parallel. 

This has the effect of increasing infrastructure capacity roughly linearly. It is a viable scaling solution until it is impossible to scale up individual components any larger.



