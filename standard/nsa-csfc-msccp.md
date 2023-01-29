---
element: Standard
complete: true
nispid: nsa-csfc-msccp
url: /standard/nsa-csfc-msccp.html
nisptag: "CSfC MSC CP Ver 1.0"
orgid: nsa
document:
  org: nsa
  pubnum: "CSfC MSC CP Ver 1.0"
  title: "CSfC Multi-Site Connectivity Capability Package Ver 1.1"
  date: "2017-02-23"
  version: "1.0"
applicability: >2
    The Commercial Solutions for Classified (CSfC) program within the National Security Agency (NSA) Directorate of Capabilities uses a series of Capability Packages (CPs) to provide configurations that will allow customers to independently implement secure solutions using layered Commercial Off-the-Shelf (COTS) products. The CPs are vendor-agnostic and provide high-level security and configuration guidance for customers and/or Solution Integrators.

    The NSA is delivering the CSfC Multi-Site Connectivity (MSC) CP to meet the demand for data in transit solutions using approved cryptographic algorithms and National Information Assurance Partnership (NIAP) evaluated components. These algorithms, known as the Commercial National Security Algorithm (CNSA) Suite, are used to protect classified data using layers of COTS products. MSC CP Version 1.0 enables customers to implement layered encryption between two or more sites.

    This Capability Package describes how to protect classified data in transit across an untrusted network using multiple encrypted tunnels implemented with Internet Protocol Security (IPsec), Media Access Control Security (MACsec), or both encryption protocols.

  
rp: fmn-cpwg
status:
  uri: https://www.nsa.gov/Resources/Commercial-Solutions-for-Classified-Program/Capability-Packages/#multi-site
  history: 
    - flag: added
      date: 2018-10-31
      rfcp: 11-57
      version: 12.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 7610997d-53cf-4e46-857a-ffdae5e61beb
coverdocument:
consumers:
  - fmn3-inter-autonomous-systems-ip-communications-security-profile
  - fmn4-20211022-prf-58
---
