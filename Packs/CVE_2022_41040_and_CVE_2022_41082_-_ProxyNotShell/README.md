This pack is part of the [Rapid Breach Response](https://xsoar.pan.dev/marketplace/details/MajorBreachesInvestigationandResponse) pack.

Microsoft is investigating two reported zero-day vulnerabilities affecting Microsoft Exchange Server 2013, Exchange Server 2016, and Exchange Server 2019. The first one, identified as CVE-2022-41040, is a Server-Side Request Forgery (SSRF) vulnerability, and the second one, identified as CVE-2022-41082, allows Remote Code Execution (RCE) when PowerShell is accessible to the attacker.  

Currently, Microsoft is aware of limited targeted attacks using these two vulnerabilities.  In these attacks, CVE-2022-41040 can enable an authenticated attacker to remotely trigger CVE-2022-41082. It should be noted that authenticated access to the vulnerable Exchange Server is necessary to successfully exploit either vulnerability.

This playbook includes the following tasks:

* Collect detection rules, indicators and mitigation tools.
* Exploitation patterns hunting using Cortex XDR - XQL Engine.
* Exploitation patterns hunting using 3rd party SIEM products.
* Indicators hunting.
* Provides Microsoft mitigation and detection capabilities.

**References:**

[Analyzing attacks using the Exchange vulnerabilities CVE-2022-41040 and CVE-2022-41082](https://www.microsoft.com/security/blog/2022/09/30/analyzing-attacks-using-the-exchange-vulnerabilities-cve-2022-41040-and-cve-2022-41082/)

[Customer Guidance for Reported Zero-day Vulnerabilities in Microsoft Exchange Server](https://msrc-blog.microsoft.com/2022/09/29/customer-guidance-for-reported-zero-day-vulnerabilities-in-microsoft-exchange-server/)

[WARNING: NEW ATTACK CAMPAIGN UTILIZED A NEW 0-DAY RCE VULNERABILITY ON MICROSOFT EXCHANGE SERVER](https://gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html)

[ProxyNotShell— the story of the claimed zero days in Microsoft Exchange](https://doublepulsar.com/proxynotshell-the-story-of-the-claimed-zero-day-in-microsoft-exchange-5c63d963a9e9)