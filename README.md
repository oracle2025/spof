# SPOF - Single Point Of Failure

This Projects aims to install a complete Ubuntu based Development Server for a
Small Team.

Under a base Linux Install Docker containers will be created for the individual services

* Features would include:
* Git+Issue Tracker
* Mail
* Website+Releases
* Mailinglists
* Chat
* Logging, Health Monitoring
* Jenkins+CI for releases
* LDAP for Accounts
* Webmail
* OpenVPN? Alternatives?
* Https letsencrypt
* Transparent proxy for server updates
* Automatic Updates for all Services
* "internal" DNS

since everything runs on one server, everything will fail when this server goes down.
