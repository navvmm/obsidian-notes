Translates human-readable names into computer-readable IP addresses

Hierarchical
- Follow the path

Distributed database
- Many DNS servers
- 13 root servers clusters (Over 1,000 actual servers)
- Hundreds of generic top-level domains (gTLDs) - .com, .org, .net, etc.
- Over 275 country code top-level domains (ccTLDs) - .us, .ca, .uk, etc.

**-- The DNS hierarchy --**
![[Pasted image 20241119140255.png]]
- 
---
**-- DNS records --**
Resource Records (RR)
- The database records of domain name services

Over 30 record types
- IP addresses, certificates, host alias names, etc.

**These are important and critical configurations**
- Make sure to check your settings, backup, and test!

**-- Address records (A) (AAAA) --**
Defines the IP address of a host
- This is the most popular query

A records are for IPv4 addresses
- Modify the A record to change the host name to IP address resolution

AAAA records are for IPv6 addresses
- The same DNS server, different records

-www.professormesser.com- IN A 162.159.246.164 ; Professor Messer
- 
---
**-- Mail exchanger record (MX) --**
Determines the host name for the mail server
- This isn't an IP address it's a name
![[Pasted image 20241119142216.png]]
- 
---
**-- Text Records --**
Human-readable text information
- Useful public information
- Was originally designed for informal information

Can be used for verification purposes
- If you have access to the DNS, then you must be the administrator of the domain

Commonly used for email security
- External email servers validate information from your DNS
---
**-- Sender Policy Framework (SPF) --**
SPF protocol
- A list of all servers authorized to send emails for this domain
- Prevent mail spoofing
- Mail servers perform a check to see if incoming mail really did come from an authorized host
---
**-- Domain Keys Identified Mail (DKIM) --**
Digitally sign a domain's outgoing mail
- Validated by mail servers, not usually seen  by the end user
- The public key is in the DKIM TXT record
![[Pasted image 20241119142851.png]]
- 
---
**-- DMARC --**
Domain-based Message Authentication, Reporting, and Conformance (DMARC)
- Prevent unauthorized email use (spoofing)
- An extension of SPF and DKIM

You decide what external email servers should do with emails that don't validate through SPF or DKIM
- That policy is written into a DMARC TXT record
- Accept all, send to spam, or reject the email
- Compliance reports can be sent to the email administrator