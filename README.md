# Awesome-Endpoint-Management-Software

# Awesome-Endpoint-Management-Software



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Unified Endpoint Management (UEM), Patch Management, Software Deployment & IT Asset Inventory*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Endpoint Management**. These tools help IT administrators inventory hardware and software, deploy patches and applications, enforce security policies, and manage endpoints across Windows, macOS, Linux, and mobile devices.



**Examples** include Microsoft Endpoint Configuration Manager (SCCM), Tanium, Ivanti Endpoint Manager, ManageEngine Endpoint Central, Broadcom Altiris, Quest KACE, HCL BigFix, Action1, NinjaOne, and PDQ Deploy (the category leaders).



**Open-source emphasis**: The open-source endpoint management ecosystem is **focused and purpose-built for specific workflows**. **OCO (Open Computer Orchestration)** is the most complete open-source UEM, providing self-hosted inventory, software deployment, and policy management for Linux, macOS, Windows, Android, and iOS from a single web interface . **Asseto** provides free IT asset management with equipment tracking, maintenance scheduling, gate pass management, and 2FA . This section documents these focused solutions honestly.



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global endpoint management market is estimated at **~$10B in 2026**, growing toward **~$25B by 2032**. The sector is **moderately fragmented** — **Microsoft Endpoint Configuration Manager** (SCCM) leverages Microsoft 365 distribution, **Tanium** leads the high-end enterprise tier with the **highest per-endpoint pricing in the market**, and **NinjaOne** competes aggressively on transparent per-device pricing. **Pricing varies dramatically**: Microsoft SCCM is licensed per managed device through **Microsoft Intune Plan 1 at $8/user/month** or **Microsoft 365 E3/E5 at $36–$57/user/month** ; **Tanium's XEM base platform runs $40–$65 per endpoint annually** at enterprise discount, with full modules reaching **$70–$100 per endpoint** ; **NinjaOne starts as low as $1.50/device/month at 10,000 endpoints**, rising to **$3.75 at 50 or fewer** ; **Action1 is free forever for the first 200 endpoints** with no feature limitations ; **ManageEngine Endpoint Central starts at $795/year for 25 endpoints** ; and **PDQ Deploy & Inventory costs $1,650 per admin per year** . No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Microsoft Endpoint Configuration Manager (SCCM)](https://www.microsoft.com/en-us/microsoft-365/endpoint-manager)** | **Microsoft's on-premises endpoint management suite.** Software deployment, patch management, OS deployment, and compliance settings for Windows, macOS, and Linux. | **Included with Microsoft Intune Plan 1**: **$8/user/month** (annual commitment) . **Microsoft 365 E3**: **$36/user/month** . **Microsoft 365 E5**: **$57/user/month** . **System Center / Core CAL Suite**: Per-device licensing under Enterprise Agreement — contact sales . | **No perpetual free tier**. **Microsoft 365 trial** available (30 days). | **~$281B revenue (Microsoft FY2025)** |

| **[Tanium](https://www.tanium.com/)** | **Enterprise-grade endpoint management and security.** Real-time visibility and control at massive scale. **Most expensive per-endpoint platform in the market** . | **XEM Base Platform**: **$40–$65/endpoint/year** at enterprise discount . **Endpoint Management module**: **$12–$22/endpoint/year** . **Threat Response module**: **$15–$25/endpoint/year** . **Full platform**: **$70–$100/endpoint/year** . **Global 500 deployments (200K+ endpoints)**: **$15M–$30M annually** . | **No free tier**. **Custom demo** required. | **Private (~$9B valuation est.)** |

| **[ManageEngine Endpoint Central](https://www.manageengine.com/products/desktop-central/)** | **Unified endpoint management for SMBs and enterprises.** Patch management, software deployment, asset inventory, and remote control. | **Professional**: **$795/year** (25 endpoints) . **Enterprise**: **$945/year** . **UEM**: **$1,095/year** . **Security**: **$1,695/year** . **MSP pricing (50 endpoints)**: **$1,045/year** (1 technician) . | **Free Edition**: **Up to 25 endpoints** with core features . | **Part of Zoho** |

| **[NinjaOne](https://www.ninjaone.com/)** | **Unified IT operations platform.** RMM, patch management, backup, and endpoint security in one console. | **Starts as low as $1.50/device/month at 10,000 endpoints**, increasing to **$3.75/device/month at 50 or fewer** . **No hidden fees** — support and implementation included free . | **No free tier**. **Free trial** available. | **Private (~$2B valuation est.)** |

| **[Action1](https://www.action1.com/)** | **Cloud-based patch management and vulnerability remediation.** | **Paid subscription** required for **more than 200 endpoints** . | **Free forever for the first 200 endpoints** with **no functionality limitations** . **Free one-time vulnerability assessment** for unlimited endpoints . **15-day trial** for larger environments . | **Private (Action1)** |

| **[Quest KACE](https://www.quest.com/kace/)** | **Systems management for endpoints.** Asset management, patch management, and software distribution. | **Starting at $4/device/month** . **Basic tier**: **$2.40** (Capterra) . | **Free trial** available . **No perpetual free tier**. | **Part of Quest Software** |

| **[HCL BigFix](https://www.hcltech.com/bigfix)** | **Endpoint management for large enterprises.** Patch management, security compliance, and software distribution. | **Per-endpoint licensing** — quote required. **GSA pricing examples**: **BigFix Platform for Workstations**: **$1.90/endpoint** (Premium Support) . **Systems Lifecycle Management Pack for Workstations**: **$1.69** . | **No free tier**. **Free trial** available. | **Part of HCLTech (~$13B revenue)** |

| **[PDQ Deploy & Inventory](https://www.pdq.com/)** | **On-premises patch management and software deployment for Windows.** Ideal for air-gapped environments. | **$1,650 per admin per year** (Standard plan) . **15% discount** for small business (<50 employees), non-profits, and schools . **No license sharing** . | **14-day fully functional free trial** . **No perpetual free tier**. | **Private (PDQ.com)** |

| **[Ivanti Endpoint Manager](https://www.ivanti.com/)** | **Unified endpoint management.** Patch management, security, and asset management. | **Custom enterprise pricing** — quote required. | **No free tier**. **Demo** required. | **Private (~$1B+ revenue est.)** |

| **[Broadcom Altiris](https://www.broadcom.com/products/altiris)** | **Enterprise endpoint management.** Client management, server management, and IT asset management. | **Custom enterprise pricing** — quote required. **Historical reference**: School district paid **$368,411/year** for Altiris Client Management + antivirus . | **No free tier**. **Demo** required. | **~$51B revenue (Broadcom FY2025 est.)** |



## 🔓 Open-Source GitHub Projects



| Repo | Description | Stars |

|------|-------------|-------|

| **[OCO (Open Computer Orchestration)](https://github.com/schorschii/OCO-Agent)** — **The most complete open-source UEM platform.** Self-hosted (on-premise) desktop and server inventory, software deployment, policy management, and mobile device management. **Manages Linux, macOS, Windows, Android, and iOS** from a single web interface . **Focus on ease of usability (UI/UX), simplicity (minimal external dependencies), and performance (manage many devices with minimal server resources)** . **Digital sovereign operation without vendor lock-in** . **Agent periodically contacts server** — no additional ports need to be opened . **Supports Debian 12/13, Ubuntu 24.04/26.04, macOS 13–26, Windows 7–11** . **Includes**: software deployment, user-computer logon overview, policy management, recognized software lists, and fine-grained permission/role system . | [![Stars](https://img.shields.io/github/stars/schorschii/OCO-Agent?style=social&color=white)](https://github.com/schorschii/OCO-Agent/stargazers) | ~500 |

| **[Asseto](https://github.com/VyrazuLabs/asseto-asset-management)** — **Free open-source IT asset management, equipment tracking, and maintenance scheduling system.** **Docker-based deployment** with interactive setup wizard . **Key features**: **Gate Pass Module** for inward/outward asset movements with QR code scanning and duplicate request prevention . **Recycle Bin** for soft-deleted record restoration . **CSV bulk upload** for locations, departments, product types, categories, and vendors . **Two-Factor Authentication (2FA)** with authenticator app support . **Firebase integration** for in-app and mobile push notifications . **Audit trails** of all approvals, rejections, and asset movements . **Stack**: Python/Django, MySQL/PostgreSQL, Docker, Nginx . | [![Stars](https://img.shields.io/github/stars/VyrazuLabs/asseto-asset-management?style=social&color=white)](https://github.com/VyrazuLabs/asseto-asset-management/stargazers) | ~200 |



**Additional open-source options worth exploring:**



| Repo | Description |

|------|-------------|

| **[Wazuh](https://github.com/wazuh/wazuh)** — Open-source security platform with endpoint inventory and policy management capabilities. |

| **[Osquery](https://github.com/osquery/osquery)** — SQL-powered operating system instrumentation. Query endpoint state for inventory and compliance. |

| **[NetBox](https://github.com/netbox-community/netbox)** — Infrastructure resource modeling for network and endpoint documentation. |

| **[GLPI](https://github.com/glpi-project/glpi)** — IT asset management and helpdesk with inventory and software deployment capabilities. |

| **[Snipe-IT](https://github.com/snipe/snipe-it)** — IT asset management for tracking hardware and software licenses. |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Endpoint management platforms handle sensitive system and user data; ensure proper access controls and compliance with organizational security policies.

- **Open-source reality**: The open-source ecosystem for endpoint management is **focused and purpose-built for specific workflows**. **OCO** is the most complete open-source UEM with self-hosted inventory, software deployment, and policy management across Linux, macOS, Windows, Android, and iOS . **Asseto** provides free IT asset management with gate pass tracking, 2FA, and Firebase notifications . However, **commercial platforms** (Tanium, Microsoft SCCM, NinjaOne, ManageEngine) provide **enterprise-scale visibility, managed infrastructure, and dedicated support** that open-source alternatives require significant operational investment to match. The open-source path is **genuinely viable** for small to mid-sized environments, digital sovereign operations, and organizations with strong IT engineering capacity.

- **Pricing caveat**: All pricing figures are **verified against cited search results** but may change without notice. **Tanium is the most expensive per-endpoint platform in the market** at **$40–$100/endpoint/year** depending on modules . **Action1 offers a genuinely free tier for the first 200 endpoints** . **NinjaOne's pricing starts at $1.50/device/month at scale** . **Microsoft SCCM requires an Intune or M365 subscription** . Always request a formal quote for accurate budgeting.



---



**Made for IT administrators, systems engineers, desktop support teams, and IT operations managers.**

Let's make endpoint management more open, transparent, and accessible.
