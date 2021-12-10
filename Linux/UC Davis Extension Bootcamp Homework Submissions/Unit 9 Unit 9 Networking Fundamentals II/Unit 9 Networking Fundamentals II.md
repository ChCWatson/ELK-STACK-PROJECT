Mission 1

Determine and document the mail servers for starwars.com using NSLOOKUP.

![](https://github.com/Plampking/ELK-STACK-PROJECT/blob/main/Linux/Images/Capture.JPG)

Explain why the Resistance isn't receiving any emails.
```
The resistance isn’t receiving any emails because the primary email server is not listed.
```

Document what a corrected DNS record should be.
```
The correct DNS record should be asltx.l.google.com as the primary, with a priority of 1.
It should also have asltx.2.google.com as the secondary with a priority of 5.
```











Mission 2


Your mission:
Determine and document the SPF for theforce.net using NSLOOKUP.

![](https://github.com/Plampking/ELK-STACK-PROJECT/blob/main/Linux/Images/nslookupNS.JPG)

Explain why the Force's emails are going to spam.
```
New IP address is not listed 45.23.176.21
```
Document what a corrected DNS record should be.
```
Add the new IP address.
```

Mission 3
Your mission:
Document how a CNAME should look by viewing the CNAME of www.theforce.net using NSLOOKUP.

 ![](https://github.com/Plampking/ELK-STACK-PROJECT/blob/main/Linux/Images/nslookupNS.JPG)

Explain why the sub page of resistance.theforce.net isn't redirecting to theforce.net.
The sub page isn’t redirecting to theforce.net because the address to theforce.net is www.theforce.net.


Document what a corrected DNS record should be.
Replace existing CNAME sub page to resistance.theforce.net


Mission 4

Your mission:
Confirm the DNS records for princessleia.site.


Document how you would fix the DNS record to prevent this issue from happening again.
Add the backup DNS server: ns2.galaxybackup.com


Mission 5


Your Mission:
View the Galaxy Network Map and determine the OSPF shortest path from Batuu to Jedha.


Confirm your path doesn't include Planet N in its route.


Document this shortest path so it can be used by the Resistance to develop a static route to improve the traffic.
Batuu > D > G > O > R > Q > T > V > Jedha



Mission 6
Issue: Due to all these attacks, the Resistance is determined to seek revenge for the damage the Empire has caused.
You are tasked with gathering secret information from the Dark Side network servers that can be used to launch network attacks against the Empire.


You have captured some of the Dark Side's encrypted wireless internet traffic in the following pcap: Darkside.pcap.


Your Mission:
Figure out the Dark Side's secret wireless key by using Aircrack-ng.



Once you have decrypted the traffic, figure out the following Dark Side information:




Mission 7
As a thank you for saving the galaxy, the Resistance wants to send you a secret message!
Your Mission:
View the DNS record from Mission #4.


The Resistance provided you with a hidden message in the TXT record, with several steps to follow.


Follow the steps from the TXT record.


Note: A backup option is provided in the TXT record (as a website) in case the main telnet site is unavailable
Take a screenshot of the results.




