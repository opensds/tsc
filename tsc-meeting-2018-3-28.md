## OpenSDS TSC Meeting Mar 28, 2018 

## Attendees:
Scott Nicholas, Reddy, Allen Samuels, Rakesh Jain, Steven Tan, Jay Bryant, Xing Yang, Sean McGinnis

## Agenda
1.General Discussions

	a.General Updates

	b.Org Chart proposal

	c.Events Preparation

		i.Mini-Summit Copenhagen / CloudNativeCon preparation

		ii.OpenStack Vancouver

	d.Release Process and some other things – Sean McGinnis

2.Aruba Development Discussions

	a.Thin OpenSDS Proposal

	b.Project Update

	c.Replication

	d.Dashboard

	e.NVMeoF

3.Wrap-up 


## Minutes
1.Scott Nicholas presented the proposed OpenSDS Participation Agreement and EUAC Charter; will circulate updated docs to TSC for final feedback and approval

2.Steve proposed the new org chart to include 3 roles – all TSC members approved proposal

	a.Xing Yang as Lead Architect responsible for Project and Architecture

	b.Sean McGinnis as Community and Release Manager  

	c.Howard Huang as Ecosystem Manager

	d.All roles will need to influence/grow awareness in other open source communities

3.OpenSDS Mini Summit Copenhagen talks

	a.All Developer talks confirmed

	b.End User talks – NTT Communications and Yahoo Japan confirmed; Vodafone pending

	c.Technology talks – Allen, Saad (Google), and Philip (Linbit) confirmed; Xing to check with Redhat, and Sean will check with Swordfish if we don’t hear anything from Philip Kufeldt

4.Sean McGinnis presented initial plans for community and release management. Twitter account @opensds_io, and hashtag #opensds. Rakesh suggested linking website to github for blogs; Steve to get Sean website rights   

5.Xing confirmed development participation from Linbit and Intel developers

6.Xing gave update on development.

	a.Thin OpenSDS proposal – to go with API to Dock, etcd is optional block for stateless requirement. Rakesh stated need for easy consumption of OpenSDS, tighter integration with Kubernetes

	b.Aruba Update

		i.Roland started to look into replication design for DRBD. Steve stated need for replication to cloud AWS, Azure, GCP.  

		ii.Jerry started work on driver for array-based replication based on Huawei Dorado; when driver is ready, Rakesh will push IBM for development of driver for XIV replication

		iii.Reddy mentioned Intel NVMeoF is ready for integration with OpenSDS, Shane will present design in next technical meeting

	c.UI

		i.Steve mentioned need for UI flow for setting up replication

		ii.Rakesh proposed splitting replication as a separate profile from Storage Profile

		iii.Allen mentioned need for separate Storage Profiles in multiple volume provisioning use case to support different storage requirements (eg. logs, cache etc. in database)  

7.Wrap Up

	a.Steve proposed inviting Jay into TSC – all TSC members approved invitation

8.Action Items

	a.Steve to send registration code for KubeCon + CloudNativeCon for TSC members

