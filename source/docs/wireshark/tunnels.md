# Tunneling traffic

Traffic tunnelling is (also known as "port forwarding") transferring the data/resources in a secure method to 
network segments and zones. It can be used for "internet to private networks" and "private networks to internet" 
flow/direction. There is an encapsulation process to hide the data, so the transferred data appear natural for 
the case, but it contains private data packets and transfers them to the final destination securely.

Tunnelling provides anonymity and traffic security and is heavily used by enterprise networks. As it gives a 
significant level of data encryption, attackers use tunnelling to bypass security perimeters using the standard and 
trusted protocols used in everyday traffic like ICMP and DNS. It is crucial to have the ability to spot ICMP and 
DNS anomalies.

## Questions below

Use the `Desktop/exercise-pcaps/dns-icmp/icmp-tunnel.pcap` file.

**Investigate the anomalous packets. Which protocol is used in ICMP tunnelling?**

Use the `Desktop/exercise-pcaps/dns-icmp/dns.pcap` file.

**Investigate the anomalous packets. What is the suspicious main domain address that receives anomalous DNS queries? (Enter the address in defanged format.)**
