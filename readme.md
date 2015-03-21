# UF-TA-killrest : Splunk Add-on for Disabling the Rest API Port on Universal Forwarders

Author: George Starcher (starcher)
Email: george@georgestarcher.com

#Description:

This is a very simple app for killing the rest port (8089) on Universal Forwarders it is sent to. I use this since in a lot of cases I do not need REST API or CLI commands on a UF.
This reduces the SSL attack surface if there are new vulnerabilities like Heartbleed.

#SETUP:

1. Send to the universal forwarders you wish to disable 8089 on.
2. Do NOT send to Splunk servers as 8089 is used all the time for Splunk server.


#COMMENTS:

1. Use this only if you are sure you do not need REST or CLI functions on a Splunk Universal Forwarder.
