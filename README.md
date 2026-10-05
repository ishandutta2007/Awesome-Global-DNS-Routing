# Awesome-Global-DNS-Routing
# Awesome-Global-DNS-Routing

## Top Global DNS Routing Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Authoritative DNS, Anycast Routing, Traffic Steering, Geo/Latency-Based Failover & Global Name Resolution*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Global DNS Routing**. These systems provide authoritative DNS, anycast delivery, health-checked traffic steering, geolocation/latency-based routing, and high-availability name resolution across worldwide networks.



**Examples** include Azure Traffic Manager, AWS Route 53, Cloudflare DNS, Google Cloud DNS, NS1, Dyn (Oracle), DNS Made Easy, Akamai Edge DNS, Neustar UltraDNS, and Constellix (the category leaders).



**Open-source emphasis**: Global anycast DNS and advanced traffic steering are dominated by commercial providers. Strong open-source authoritative servers (**PowerDNS**, **Knot DNS**, **CoreDNS**, **BIND**, **NSD**) and related tooling enable self-hosted DNS infrastructure. This section expands those while remaining realistic about the commercial gap for worldwide anycast PoPs and managed traffic policies.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Azure Traffic Manager](https://azure.microsoft.com/products/traffic-manager/)**  

  DNS-based traffic load balancer with priority, weighted, performance, geographic, multivalue, and subnet routing methods—supports external endpoints and nested profiles.



- **[AWS Route 53](https://aws.amazon.com/route53/)**  

  Highly available authoritative DNS with latency-based, geolocation, geoproximity, weighted, failover, and multivalue routing, plus health checks and deep AWS integration.



- **[Cloudflare DNS](https://www.cloudflare.com/dns/)**  

  Fast anycast authoritative DNS with one-click DNSSEC, CNAME flattening, and advanced traffic steering via Cloudflare Load Balancing and Argo.



- **[Google Cloud DNS](https://cloud.google.com/dns)**  

  Scalable, low-latency authoritative DNS service on Google’s global network with managed DNSSEC and integration into Google Cloud.



- **[NS1 (IBM NS1 Connect)](https://ns1.com/)**  

  Programmable DNS and traffic steering platform with filter chains, RUM-driven decisions, and sophisticated geo/health/cost-based routing.



- **[Dyn (Oracle)](https://www.oracle.com/cloud/networking/dns/)**  

  Oracle’s managed DNS and traffic management offerings descended from Dyn’s global authoritative platform.



- **[DNS Made Easy](https://dnsmadeeasy.com/)**  

  Enterprise managed DNS with secondary DNS, geo-routing, and high-availability anycast infrastructure.



- **[Akamai Edge DNS](https://www.akamai.com/products/edge-dns)**  

  Highly resilient authoritative DNS delivered on Akamai’s global edge network with advanced security and traffic management.



- **[Neustar UltraDNS](https://www.transunion.com/solution/neustar)**  

  Enterprise DNS and traffic management platform (historically Neustar UltraDNS) focused on reliability and advanced routing.



- **[Constellix](https://constellix.com/)**  

  Managed DNS with geo-proximity, weighted, and failover routing, plus APIs and multi-provider support.



## Open-Source GitHub Projects

- **[PowerDNS](https://github.com/PowerDNS/pdns)**  

  Feature-rich open-source authoritative server, recursor, and dnsdist load balancer—database-backed, REST API, Lua scripting, and DNSSEC support.



- **[CoreDNS](https://github.com/coredns/coredns)**  

  Flexible, plugin-based DNS server (CNCF graduated)—widely used in Kubernetes and for custom authoritative or forwarding setups.



- **[Knot DNS](https://www.knot-dns.cz/)**  

  High-performance open-source authoritative-only DNS server with excellent DNSSEC, IXFR, DDNS, and rapid reconfiguration.



- **[BIND 9](https://gitlab.isc.org/isc-projects/bind9)**  

  The classic open-source DNS server supporting authoritative and recursive modes, DNSSEC, and extensive configuration.



- **[NSD](https://github.com/NLnetLabs/nsd)**  

  Lightweight, high-performance open-source authoritative-only DNS server from NLnet Labs.



- **[dnsdist (PowerDNS)](https://github.com/PowerDNS/pdns)**  

  Open-source DNS-aware load balancer and traffic director for distributing and filtering DNS queries.



- **[Technitium DNS Server](https://github.com/TechnitiumSoftware/DnsServer)**  

  Cross-platform open-source DNS server with authoritative, recursive, and DHCP capabilities plus a modern UI.



- **[Unbound](https://github.com/NLnetLabs/unbound)**  

  Validating, recursive, caching DNS resolver often paired with authoritative servers for full-stack open DNS.



- **[Documentation and PowerDNS / Knot / CoreDNS playbooks](https://doc.powerdns.com/)**  

  Guides for deploying anycast, DNSSEC, secondary zones, and high-availability open DNS infrastructure.



- **[Self-hosted anycast and traffic-steering patterns](https://github.com/)**  

  Community architectures combining open authoritative servers with BGP anycast, health checks, and geo-aware response policies.



### Additional Strong Open-Source Options

- Running **PowerDNS**, **Knot DNS**, or **CoreDNS** as authoritative servers with database backends and APIs.

- Using **dnsdist** for DNS-level load balancing and filtering.

- Deploying multi-node anycast with open servers and BGP for geographic resilience.

- Accepting that true global anycast PoP density, managed health-checked traffic policies, RUM-driven steering, and SLA-backed worldwide resolution still favor commercial platforms (Route 53, Cloudflare, NS1, Azure Traffic Manager, Akamai Edge DNS, etc.).

- Focusing open-source efforts on ownership of zone data, DNSSEC control, and hybrid secondary setups.



**Frameworks for building custom systems**: Authoritative zones on PowerDNS/Knot/CoreDNS → secondary or anycast distribution → health-aware responses via scripting or external controllers → monitor with open telemetry. Suitable for organizations that need full control or hybrid DNS. Most global applications rely on commercial managed DNS for latency and availability.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- DNS is critical infrastructure. Misconfiguration can cause outages. Open-source servers require proper security hardening, monitoring, and operational expertise. This list is not operational advice.



---

**Made for network engineers, platform teams, and open DNS advocates.**

Let's keep name resolution fast, resilient, and as open as practical.
