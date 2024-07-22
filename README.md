# wazuh-siem-setup

I set up a SIEM tool (Wazuh) on a personal web server that is connected to the internet with a domain name associated with it. One purpose of this project was to explore some skills I've learned from my journey earning the CompTIA Security+. Another purpose was to observe how automated attacks and reconnaissance works as well as how often it occurs.

What I've learned from this project is that automated attack tools primarily use credential stuffing on services operating on open ports or attempting to access sensitive files related to website configuration. The automated reconnaissance part of the attacks seem to be minimal, as aside from determining open ports, they seem to use the domain's name as a user for the credential stuffing and they also attempt to index all routes on a web server.

As for frequency of these attacks, Wazuh recorded over 5000 attacks in 24 hours. This is even with a service on the server automatically banning IPs that fail too many SSH logins.

What's contained in this repository is screenshots from the Wazuh dashboards as well as exports of the data that Wazuh collected.
