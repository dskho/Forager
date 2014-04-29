Intel-Master
============

Gathers Threat Intelligence from various open-source feeds and formats them into new-line separated files for each feed.

NOTE:
The script creates a file for malicious IP addresses and a file for malicious domains for EACH feed in feeds.py, and then places them in a folder entitled "intel" 


Feeds function
---------------

(Invoked with --feeds)

1. 'list' option -- Lists all feeds and allows user to choose a single feed to update. 
2. 'update' option -- Updates all feed modules in feeds.py

Search function
---------------

(Invoked with --search)

1. '-f <file path>' Provides the capability to search through the intel directory results for a specific list of indicators
2. '-s <IPv4 address>' Searches through intel directory for a single IP address 
