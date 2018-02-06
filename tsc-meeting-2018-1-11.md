## OpenSDS TSC Meeting Jan 11, 2018 

## Attendees:
Steven (Huawei), Rakesh (IBM), Reddy (Intel), Allen (WD), Jay (Lenovo), Kei (NTT Comms), George (Dell-EMC), Xing Yang (Huawei)

## Agenda
1.	Updates - 15mins
2.	Aruba Release Design Discussion 

## Minutes
1.	Group is a base class for snapshot consistency, batch operations, replication etc.
2.	Group will use DELETE instead of POST - deleting a group removes the relationship of volumes in that group but does not delete volumess.(Steve's afterthought-the group policy will determine what we do with the volumes after the group is deleted)
3.	Multiple DC, cross-region replications is important but we will focus on solving single site problem first.
4.	Host based replication serves 2 purposes, 1. active volume replication requires the host-based replicator (HBR) to be on the same host 2. Inactive volume replication allows the HBR to be on another host
5.	Update to a replication group is limited to minor changes, major changes require a new replication to be created
6.	We need a feedback mechanism to the northbound container orchestrator to coordinate storage orchestration
 

