# voicemaster
  Voicemaster Voip advanced routing/billing platform for  every one!


I've been working  on this system for a while,  and now would love to share my expierence and resources of this wonderfull and powerfull Voip platform .
The system consist of two servers  :  

  - VoiceMaster VM2000:   Billing/Routing    ( Kamailio with Sybase database )
  - Sysmaster SM7000:  Media proccessing ( asterisk with PRI cards )

This system Key Features :

  Standard and Advanced VoIP Billing Functionality
  Advanced Management of Class 4 Service
  Multiple Authentication Methods
  Selection of Call Legs for Billing Purposes
  Real-time Monitoring and Alerts
  Comprehensive Reporting
  Virtual Server Partitioning
  Carrier Grade Reliability
  Modular Architecture
  Unlimited Rate Tables
  High Call Capacity

Here is a few training video in the past, it gives the general overvew of the  main functions.
Includes a demo for setup PBX Extension , VoiceMail, VirtiualOffice, Conference using Customer Portal,  Redundancy, Cloud PBX setup. 


https://vimeo.com/user36231282/videos



in 2024 the project still alive and growing.
 We have running a number of VoiceMaster servers,  providing support and security services  for them. 

    - Automatic firewall generation based on information from the database  ( customer, Voip provider Gateways IP list dynamically generated and feede for the iptables firewall whitelisting )
    - Cluster support for Redundancy  - Live replication between Master -> Slave , and automatic takeover.
    - DB backups, restore 

![image](https://github.com/a4business/voicemaster/assets/30354660/e19a556e-d051-45dc-be27-c4514052a944)

Its not good idea to run SIP proxy on default port 5060, so we always try to use random ports in setup.
If you still want to use a default  SIP port:  5060, then it must be closed initially, so only  whitelisted IPs  has access to it.

![image](https://github.com/a4business/voicemaster/assets/30354660/0a8a916f-c51d-492c-a279-01215fbacb7a)

Improoved rating system   :
Provider rate definition:
![image](https://github.com/a4business/voicemaster/assets/30354660/01021aed-930c-4b28-9f2c-e19e5ab5749b)

Customer Rate Definition:
![image](https://github.com/a4business/voicemaster/assets/30354660/2f27e339-02c5-4edd-be61-5d8c7dc9d29b)


  We are opened for new integrations and setups. 
  you can comment or write us via contact-Us form at :
  
   https://a4business.com




    
