# Here is a scheme and IP plan of the lab data center.

**Lab DC is based on a CLOS topology and it's simulated by EVENG tool**

<img src="https://github.com/Inqex/dc_labs/blob/main/lab1/assets/clos_topology.png"  width="400" height="350">






Task 1: Generate an IP plan


| Segment | Loopback's     | ptp's           |
| ------- | -------------- | --------------- |
| Spine   | 172.16.0.0/27  | 172.16.0.64/26  |
| Leaf    | 172.16.0.32/27 | 172.16.0.128/26 |
