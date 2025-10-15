Use process ID 10 for OSPF activation on all routers. 
- Activate OSPF using network statements and inverse masks on the routers in the Headquarters network.
- Activate OSPF by configuring the interfaces of the network devices in the Data Service network, where 
required.
 Configure router IDs on the multiaccess network routers as follows:
> BC-1: 6.6.6.6
> BC-2: 5.5.5.5
> BC-3: 4.4.4.4
- Configure OSPF so that routing updates are not sent into networks where they are not required.
- Configure router BC-1 with the highest OSPF interface priority so that it will always be the designated 
router of the multiaccess network.
- Configure a default route to the ISP cloud using the exit interface command argument.
- Automatically distribute the default route to all routers in the network.
- Configure the OSPF routers so that the Gigabit Ethernet interface cost will be 10 and the Fast Ethernet 
cost will be 100.
- Configure the OSPF cost value of P2P-1 interface Serial0/1/1 to 50.
- Configure the hello and dead timer values on the interfaces that connect P2P-1 and BC-1 to be twice the 
default values.
