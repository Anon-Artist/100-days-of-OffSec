# External Reconnaissance

### What is External Reconnaissance

External reconnaissance is an essential phase in red teaming, which involves gathering information and assessing the security posture of a target organization from an external perspective. The goal is to identify vulnerabilities, weaknesses, and potential attack vectors that an adversary might exploit.

Every time start with passive reconnaissance and if needed use active reconnaissance.

### Passive Reconnaissance

Passive reconnaissance involves gathering information without directly interacting with the target systems or network. It typically relies on publicly available information and does not involve any intrusive actions

### Active Reconnaissance

Active reconnaissance involves more direct interaction with the target systems or network to gather information. This approach typically involves probing, scanning, or interacting with the target in various ways to identify potential vulnerabilities, weaknesses, or attack vectors.

### How to Perform External Reconnaissance

It is purely based on the type of red team exercise that you are performing. If it is an end to end red team exercise then you have to recon people, process and technologies. For that you can perform.

1. OSINT (Open Source Intelligence Gathering)

Open-Source Intelligence (OSINT) is defined as intelligence produced by collecting, evaluating and analyzing publicly available information.

For more information:&#x20;

* [https://osintframework.com/](https://osintframework.com/)
* [https://github.com/jivoi/awesome-osint](https://github.com/jivoi/awesome-osint)

2.  Passive Gathering

    * Hacker Search Engines - Shodan, Censys, ZoomEye, FOFA,&#x20;
    * Social Media Websites - LinkedIn, Twitter
    * DNS Enumeration - PureDNS, DNSdumpster
    * Passive Subdomain Enumeration - ReconFTW
    * Web Archives - Wayback Machines
    * Google Dorks - GHDB
    * GitHub - Github
    * S3 Buckets - S3Scanner
    * Data breaches - Dehashed


3. Active Gathering
   * Active Subdomain Enumeration - ReconFTW, reNgine
   * Port Scanning - rustscan, massscan, nmap
   * Vulnerability Scanning - nuclei,&#x20;
   * Public facing application directory brute-force - dirsearch, ffuf

{% hint style="info" %}
If you are lucky then you can validate these Corporate email's, Phone number's or usernames from the organization assets such as public facing websites or any portals by utilizing their signup, login or password reset functionality
{% endhint %}

{% hint style="info" %}
Never forget to test default credentials on public facing portals
{% endhint %}

There are many other techniques such as Certificate Transparency, DNS Zone Transfer etc.. also there are multiple tools and frameworks out there. Use the reference below to learn more.

### References

1. [https://www.linode.com/docs/guides/red-team-reconnaissance-techniques/](https://www.linode.com/docs/guides/red-team-reconnaissance-techniques/)
2. [https://sidxparab.gitbook.io/subdomain-enumeration-guide/](https://sidxparab.gitbook.io/subdomain-enumeration-guide/)
