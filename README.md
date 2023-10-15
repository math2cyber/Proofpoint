<h1>Proofpoint_Investigation_PJ</h1>
Objective: To display my ability to investigate an alert in Proofpoint within an environment.
<p align="center">
Proofpoint Alert: <br/>
<img src="https://imgur.com/c0VakU2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">
Proofpoint Alert: <br/>
<img src="https://imgur.com/9fT3hBU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />  

<h2>Threat Objective</h2>
Proofpoint labeled the threat as a credential harvester.  The emails had an Excel document attached to them.  The attachment’s hash value was found to be malicious by VirusTotal.  On VirusTotal, vendors classified the attachment as a trojan.  One vendor stated the attachment is the Folina trojan.  The Excel document had malicious macros enabled to infect the host machine.  No user downloaded the attachment nor deleted the email.  The attachment is still in the user's inbox.
<br />

<h2>Proofpoint Credential Harvester Email</h2>
Emails sent: 2 messages sent
<br>
Emails blocked: 0 messages blocked
<br>
Emails delivered: 2 delivered
<br>
Clicks: 0 clicks 
﻿<br>
Time Delivered: 2023/07/11 - 03:46 (UTC +02:00)
<br>
Envelope Sender: frederic[.]cxrxvxlla@xxxxeranetxxx[.]fr
<br>
Envelope Recipients: accountspayable@xxxxxxx.com
<br>
Subject: Re: URI REMlT
<br>
Header From:	frederic cxrxvxlla <frederic[.]cxrxvxlla@xxxxeranetxxx[.]fr>
<br>
Header To: wire.payment@xxxx.com
<br>
Sender IP Address: 1X5.XXX.5.XXX

<h2>VirusTotal Hash Value Reputation Check</h2>
VirusTotal Risk Score: 17/61 vendors flagged the IP address as malicious.
<p align="center">
VirusTotal <br/>
<img src="https://imgur.com/nT2cPKO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>IP Reputation Check</h2>
VirusTotal Risk Score: 0/87 vendors flagged IP as malicious.  The IP is clean.
<p align="center">
 <br/>
<img src="https://imgur.com/EXz8vfD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />  
abuseIPDB Risk Score: IP address not found in database. The IP is clean.
<p align="center">
 <br/>
<img src="https://imgur.com/nFzZnaP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />  

<h2>Declaration</h2>
This is a true positive because VirusTotal verified the attachment was malicious and the emails were delivered to the user’s inbox.

<h2>Recommendation(s)</h2>
I recommended the messaging team purge the emails from the user’s inbox and block the sender’s email address.
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
