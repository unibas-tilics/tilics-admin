# Deadlock

Imagine an uncontrolled intersection without any traffic signs. Here, drivers have to respect the priority to the right system. In the situation shown in the picture, none of the three cars can continue. In practice this is solved by one driver giving up their priority using a hand-sign.

The same happens when several computer processes running in parallell want to access shared resources. One example would be a so-called *circular wait*. Processes P1, P2, and P3 all hold a different resource. In order to continue execution, P1 needs the resource held by P3, P2, the one held by P1, and P3 the one held by P2. Since computer processes cannot hand wave at ech other, clear rules are needed to avoid this situation in the first place. A solution would be to give every resource a unique number and allow access only by increasing order of numbering.

In the traffic example, the deadlock could be avoided by placing traffic lights at the intersection.

## Author
pk, 2019-03-28
