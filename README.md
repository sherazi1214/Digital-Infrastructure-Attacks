# Digital-Infrastructure-Attacks

## Digital Infrastructure Attacks – Definition
**English:**
A Digital Infrastructure Attack targets the underlying IT systems that support an organization — such as networks, servers, DNS, routing, cloud platforms, and data storage — to disrupt, damage, or steal information.
**Urdu:**
Ye wo attacks hain jo organization ke IT backbone (networks, servers, DNS, routing, cloud, storage) pe hote hain taake system disrupt, damage ya data steal ho sake.

## Types of Attacks (Common in Security+)

**Spoofing Attack**	Pretending to be a trusted device, person, or service by falsifying identity (IP, MAC, email).	Fake email jo real company ban ke bheji jati hai.

**Poisoning Attack**	Injecting false information into a system so it behaves incorrectly.	DNS records badal ke user ko fake site pe bhejna.

**Hijacking Attack**	Taking over an ongoing connection or session without permission.	Kisi ka active login session chura lena.

**DoS / DDoS Attack**	Overloading a system or network so it becomes unavailable.	Website pe bohot zyada traffic bhej ke usay crash kar dena.

## Attack Categories (CompTIA Style)

**Network-based Attacks** – Target routers, switches, firewalls, DNS.

**Application-based Attacks** – Exploit software flaws.

**Infrastructure-based Attacks** – Hit core services (DNS, routing, cloud).

**Physical Attacks** – Destroy hardware or cables.

## Specific Attacks – Details

### Spoofing Attacks
**IP Spoofing** – Faking source IP address to bypass security filters.

**MAC Spoofing** – Changing network card’s MAC to impersonate another device.

**Email Spoofing** – Faking sender address to trick the recipient.

#### Impact:

Bypass authentication, deliver malware, trick users.

#### Mitigation:

Packet filtering, SPF/DKIM for email, MAC binding.

## Poisoning Attacks
**DNS Poisoning** – Redirect users to malicious sites.

**ARP Poisoning** – Trick devices into sending data to attacker.

**Cache Poisoning** – Alter stored data to serve false responses.

#### Impact:

Data theft, phishing, man-in-the-middle.

#### Mitigation:

DNSSEC, static ARP entries, cache validation.

## Hijacking Attacks
**Session Hijacking** – Steal active session tokens.

**Domain Hijacking** – Take control of domain name.

**Clickjacking** – Hide malicious links under UI elements.

#### Impact:

Unauthorized access, account theft.

#### Mitigation:

HTTPS everywhere, secure cookies, MFA.

## DoS / DDoS Attacks
**DoS** – Single source floods target.

**DDoS** – Botnet sends massive traffic from multiple sources.

#### Impact:

Service downtime, lost revenue, reputational damage.

#### Mitigation:

Load balancers, rate limiting, CDN with DDoS protection.
