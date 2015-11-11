# Domain list

A crowdsourced (open to contributions!) list of domains (including CDN domains) belonging to big Internet silos i.e. Facebook, Amazon, Adobe etc.

This list is useful for any application willing to filter, block or just recognize DNS queries to the expanding empires of big companies which nowadays accept connections via a variety of hostnames rather than just a domain, be it for CDN/round-robin operations, to distribute load or to deceive clients.

# Organization

The list is organized in files: each file has the name of the conglomerate (i.e. "facebook") and the file contains a newline separated list of domains belonging to the conglomerate.

# Contributing

It's github, just file a pull request!

# How to find out

This is the fun part! We all need to coopearate in order to find out using various techniques, for instance monitoring the DNS queries going out of your home and office, or running rDNS queries on company IP ranges.

Please share your experience, how-to guides and scripts with us here.

# FAQ

> How about a list of IPs?

IPs are another ball of wax. However IP lists are available here https://www.iblocklist.com/lists.php in the form of ranged ip notation that is somehow more complex to parse. The fastest open source parser for those is in portable C++ inside Peerguardian http://sourceforge.net/projects/peerguardian

# Contact

Come over on irc.dyne.org channel #dyne

Also via web: https://irc.dyne.org
