## OpenSDS TSC Meeting May 2, 2018 

## Attendees:
Rakesh Jain, Steven Tan, Kei Kusunoki, Yusuke Sato, Xing Yang, Makoto Kawabata (HPE)

## Agenda
1. General Discussions
2. Aruba Development Status
3. Bali and Capri Roadmap Features
4. Wrap-up 

## Minutes
1.	Kei proposed starting regular bi-weekly EUAC meetings, proposed start May 21 week. Time is 10:00am JST
2.  Kei introduced HPE Makoto Kawabata-san to OpenSDS. Kawabata-san will discuss internally regarding OpenSDS participation
3.	Xing updated on Aruba status
4.	Request from NTT to package with keystone and config in dashboard for tenant management in Aruba. Xing to check resource
5.	Yahoo Japan requests native driver support for Huawei OceanStor V3 for replication
6.	Kei indicates hybrid cloud is important for NTT. Data stored in NTT to be replicated to AWS, Azure, Google
7.	Rakesh highlighted importance of supporting Kubernetes federation with OpenSDS multi-cloud
8.	Rakesh mentioned KPN is ok with using Cinder driver for IBM SVC so no native driver is required
9.	Bali feature priorities
  a.	Multi cloud - AWS, Azure
  b.	S3 object
  c.	Multi OpenStack 
  d.	Monitoring – a way to monitor performance QoS 
  e.	Metering – start with capacity usage configurable
  f.	Replication configurable through a single dashboard
    i.	multi-site
    ii.	multi-region 
  g.	Thin OpenSDS 
  h.	Swordfish to be moved to Capri unless we have more evidence of multi-vendor support
  i.	Modularize
  j.	NVMeoF
  k.	Group snapshot/replication 
  l.	To be discussed
    i.	Data migration?
    ii.	CSI (for Mesos? Docker?)
    iii.	Data migration (offline/online)
10.	Capri feature priorities
  a.	Swordfish
  b.	File support (may need to pull this into Bali for Yahoo and Swisscom)
  c.	Performance QoS
  d.	SDN support for Contrail ONOS requested by NTT
  e.	VMware support?

## Extras from the Mini Summit
Extras from the Mini Summit:
11.	Linbit officially joined OpenSDS with Linux Foundation PR annoucement
12.	Jay Bryant officially joined OpenSDS TSC
13.	KPN requested FC support, will be delivered in Aruba
14.	LinBit will provide volume driver for LinStor block storage
