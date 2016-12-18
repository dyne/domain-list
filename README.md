# Domain list

A crowdsourced (open to contributions!) list of domains (including CDN domains) belonging to Internet commercial silos i.e. Facebook, Amazon, Adobe etc. but also to indie organizations and groups.

This list is useful for any application willing to filter, block or just recognize DNS queries to the expanding empires of big companies which nowadays accept connections via a variety of hostnames rather than just a domain, be it for CDN/round-robin operations, to distribute load or to deceive clients.

# Organization

The list is organized in files: each file has the name of the conglomerate (i.e. "facebook") and the file contains a newline separated list of domains belonging to the conglomerate.

# Contributing

It's github, just file a pull request!

# How to find out

This is the fun part! We all need to coopearate in order to find out using various techniques, for instance monitoring the DNS queries going out of your home and office, or running rDNS queries on company IP ranges.

Please share your experience, how-to guides and scripts with us here.

# Similar projects maintained with git

Just searching `hosts block domains` is possible to find out lists occasionally collected and published by people on the interwebz. Yet all this misses a systematic effort to maintain and update lists, which can well be facilitated using a public git repository. Most of these lists are made to either block or to correctly resolve the domains from countries where the services are blocked by ISPs.

Here a list of efforts similar efforts maintained on git:

- https://github.com/StevenBlack/hosts
- https://github.com/vokins/yhosts
- https://github.com/highsea/Hosts
- https://github.com/txthinking/google-hosts
- https://github.com/superliaoyong/hosts
- https://github.com/babylon882004/hosts

Here below efforts that map domains to ipv6 addresses:

- https://github.com/lennylxx/ipv6-hosts
- https://github.com/popcorner/cernet-ipv6-hosts

## Help keep an archive backup

Projects like the ones above may or may not be maintained on the long term. Sometimes they disappear or are even taken down on request of providers and companies. To facilitate the backup of these repositories, they are included as submodules and they can all be downloaded locally with the commands:

```
git submodule init
git submodule update
```

To update the local archive with upstream, the command is:

```
git submodule foreach git pull --rebase
```

# FAQ

> How about a list of IPs?

IPs are another ball of wax. However IP lists are available here https://www.iblocklist.com/lists.php in the form of ranged ip notation that is somehow more complex to parse. The fastest open source parser for those is in portable C++ inside Peerguardian http://sourceforge.net/projects/peerguardian

> What do you intend to do with this list?

The scenarios in which domain-list can be useful may vary. Dyne.org has a project where this data is being used: Dowse http://github.com/dyne/dowse. The whitepaper that explains Dowse is visible on http://dowse.equipment.

> Is this legal?

Of course! all information collected here is already in the public domain: well visible in every connection we make to on-line services, on public documents released by ISC, Whois databases and rDNS lookups. This project just aims to be a point of collection for such information and related scripts.

# Contact

Come over on irc.dyne.org channel #dyne

Also via web: https://irc.dyne.org
