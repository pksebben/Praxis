# Firewalls
Firewalls are network security implementations that can be physical or software.

REF: https://en.wikipedia.org/wiki/Firewall_(computing)
(this reference isn't great.  It could be replaced by a wiki)
There are three general types of firewall:
1. Stateless (packet filtering) Firewalls

Inspects each packet individually and checks 

2. Stateful Firewalls

Also known as circuit-level gateways.  These are essentially the second-generation of stateless firewalls and remember information regarding the specific connections that are open between machines (using the IP adress info at the transport layer).

These types of firewalls are vulnerable to DDoS attacks, as they maintain information regarding every open connection

3. Application Firewalls

Application firewalls operate on the application layer of the OSI model, and can inspect much more information about data and connections.  Application layer firewalls can restrict particular apps from accessing the open internet, and detect if a protocol is being abused (used for a purpose that it wasn't intended for.)

4. NGFW (Next-Generation FireWall)

These are Application firewalls that have expanded capapbilities like Intrusion Prevention Systems, User Identity Management, and Web Application Firewalls
