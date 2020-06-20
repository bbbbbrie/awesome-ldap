# Awesome LDAP
> Useful resources for learning more about and using LDAP whether you are a developer, pentester, network defender or something else cool! 

You can visit this page at [https://brie.gitlab.io/awesome-ldap/](https://brie.gitlab.io/awesome-ldap/). You can contribute to this page at [https://gitlab.com/brie/awesome-ldap](https://gitlab.com/brie/awesome-ldap).

My objective is to make this a useful resource for people with varying levels of experience with LDAP. Do not hesitate to suggest good quality introductory material. 

## Implementations
  - [OpenDJ](https://www.openidentityplatform.org/opendj)
  - [OpenLDAP](https://www.openldap.org/)
  - [389 Directory](https://directory.fedoraproject.org/)
  - [ReOpenLDAP](https://github.com/erthink/ReOpenLDAP) - A production-ready replacement for OpenLDAP

### Suites
  - [FreeIPA](https://www.freeipa.org/page/Main_Page) - An integrated security information management solution that includes 389 Directory Server

## :whale: Containers
  - [osixia/openldap](https://hub.docker.com/r/osixia/openldap/) - One of the most recommended OpenLDAP containers
  - [osixia/phpldapadmin](https://hub.docker.com/r/osixia/phpldapadmin/) - A great companion to the container above! This [guide](https://scytalelabs.com/setup-and-configure-openldap-using-docker-image-on-ubuntu-16-04/) walks you through configuring them together.

## LDAP Clients, Tools and Utilities
  - [Apache Directory Studio](https://directory.apache.org/studio/)
  - [Client APIs](https://ldap.com/client-apis/) - List of LDAP libraries for languages from Ada to Swift on `ldap.com`
  - [lb - LDAP benchmarking tool](https://github.com/hamano/lb)
  - [LDAP Tool Box project](https://ltb-project.org/doku.php)
  - [OpenLDAP Helper Scripts](https://www.port389.org/docs/389ds/scripts.html)
  - [phpLDAPadmin](http://phpldapadmin.sourceforge.net/wiki/index.php/Main_Page) - Web-based LDAP browser to manage your LDAP server

## Security
  - [LDAP Injection Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/LDAP_Injection_Prevention_Cheat_Sheet.html)
  - [LDAP Injection & Blind LDAP Injection in Web Applications](https://www.blackhat.com/presentations/bh-europe-08/Alonso-Parada/Whitepaper/bh-eu-08-alonso-parada-WP.pdf)
  - [Testing for LDAP Injection (OTG-INPVAL-006)](https://kennel209.gitbooks.io/owasp-testing-guide-v4/en/web_application_security_testing/testing_for_ldap_injection_otg-inpval-006.html)
  - [Understanding and Exploiting Web-based LDAP](https://www.sans.org/blog/understanding-and-exploiting-web-based-ldap/)
### NSE Scripts
  - [ldap-search](https://nmap.org/nsedoc/scripts/ldap-search.html)
  - [ldap-rootdse](https://nmap.org/nsedoc/scripts/ldap-rootdse.html)

#### Using NSE Scripts
  - [Searching LDAP using Nmap's ldap-search.nse script](https://fadedlab.wordpress.com/2017/07/25/searching-ldap-using-nmaps-ldap-search-nse/) - Several practical applications

## Articles, Papers Walkthroughs
  - [Build an OpenLDAP Docker Image That’s Populated With Users](https://medium.com/better-programming/ldap-docker-image-with-populated-users-3a5b4d090aa4)
  - [Creating Active Directory Accounts: Using LDIF files and OpenLDAP tools](http://pig.made-it.com/pig-adusers.html)
  - [Hacking into an LDAP or Active Directory service](https://pub.nethence.com/server/active-directory) - "note: this isn't pentesting but just gentle digging"
  - [2020 LDAP channel binding and LDAP signing requirements for Windows](https://support.microsoft.com/en-us/help/4520412/2020-ldap-channel-binding-and-ldap-signing-requirements-for-windows)

## LDIF 
LDIF is the LDAP Data Interchange Format. LDIF files are flat text files. 

  - [dbgen.pl](https://linux.die.net/man/1/dbgen.pl) - Perl
  - [LDIF Parser and Generator](https://www.python-ldap.org/en/latest/reference/ldif.html) - Python 
  - [LDIFDE - Export / Import data from Active Directory - LDIFDE commands ](https://support.microsoft.com/en-us/help/555636)

## RFCs
  - [RFC 2849](https://tools.ietf.org/html/rfc2849) - The LDAP Data Interchange Format (LDIF) - Technical Specification
  - [RFC 4510](https://tools.ietf.org/html/rfc4510) -  Lightweight Directory Access Protocol (LDAP): Technical Specification Road Map
  - [RFC 4515](https://tools.ietf.org/html/rfc4515) - Lightweight Directory Access Protocol (LDAP): String Representation of Search Filters

## Terminology
These are some of the best available glossaries and other resources for learning more about LDAP terminology.

  - [Glossary of LDAP and Directory Terminology](https://ldapwiki.com/wiki/Glossary%20Of%20LDAP%20And%20Directory%20Terminology)
  - [LDAP - Object Classes and Attributes](https://www.zytrax.com/books/ldap/ape/)

## Other Awesome Lists
  - [LDAP section of awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin#ldap)

## Books
  - [Understanding LDAP Design and Implementation](https://www.redbooks.ibm.com/redbooks/pdfs/sg244986.pdf) - Free PDF from IBM
## Conferences and Education
  - [LDAPCon](https://ldapcon.org/2019/)
  - [Videos from LDAPCon 2019](https://www.youtube.com/channel/UCbozYVV-XTqzx-eTSI4I84A/videos)

## Support Channels
  - [OpenLDAP Issue Tracking System](https://bugs.openldap.org/)
  - [openldap.org mailing lists](https://lists.openldap.org/hyperkitty/) - If you are reading this, you may wish to subscribe to `openldap-technical`. 

## Miscellaneous
  - [/r/ldap](https://reddit.com/r/ldap) - The LDAP subreddit
  - [Public LDAP Servers](https://ldapwiki.com/wiki/Public%20LDAP%20Servers)
