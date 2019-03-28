**Opps! my computer keeps freezing! Could it be a livelock?**

Livelock happens in operating systems when two or more processes keep changing their state without progressing.
Why!?
Suppose you have 2 running processes A and B,  and each holds a resource R1 and R2 respectively. 

A requires R2 to complete its job and B requires R1 to complete its job. A requested R2 from B, and at the same time B requested R1 from A. So, they swap their resources. 

Now, each process has again only one resource, and requests the other one. Basically, they will keep exchanging the resources without doing the computation. 


![](figures/image-1-105-livelock.jpg)
