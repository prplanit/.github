<div align="center">

![Banner](../assets/PrecisionPlanIT.com-Banner.png)

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=435&lines=The+Real+World;Requires+Real+Results...;You+Have+Real+Expectations;Precision+Plan+IT" alt="Typing SVG" />

[![PrPlanIT GitHub](https://img.shields.io/badge/PrPlanIT-181717?style=flat&logo=github&logoColor=white)](https://github.com/PrPlanIT)
[![HomeLabHD GitHub](https://img.shields.io/badge/HomeLabHD-181717?style=flat&logo=github&logoColor=white)](https://github.com/HomeLabHD)
[![PrPlanIT GitLab](https://img.shields.io/badge/PrPlanIT-FC6D26?style=flat&logo=gitlab&logoColor=white)](https://gitlab.prplanit.com/PrPlanIT)
[![HomeLabHD GitLab](https://img.shields.io/badge/HomeLabHD-FC6D26?style=flat&logo=gitlab&logoColor=white)](https://gitlab.prplanit.com/PrPlanIT/HomeLabHD)
[![prplanit Docker](https://img.shields.io/badge/prplanit-2496ED?style=flat&logo=docker&logoColor=white)](https://hub.docker.com/u/prplanit)
[![hlhd Docker](https://img.shields.io/badge/hlhd-2496ED?style=flat&logo=docker&logoColor=white)](https://hub.docker.com/u/hlhd)
[![donate](https://img.shields.io/badge/donate-FF5E5B?style=flat&logo=ko-fi&logoColor=white)](https://ko-fi.com/sofmeright)
[![sponsor](https://img.shields.io/badge/sponsor-EA4AAA?style=flat&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/PrPlanIT)

</div>

---

## Tooling we Adopt in Our Reference Platform

### Infrastructure & Virtualization
![Proxmox](https://img.shields.io/badge/Proxmox_(VE%2FBS)-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Ceph](https://img.shields.io/badge/Ceph-EF5C55?style=for-the-badge&logo=ceph&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Networking
![Cilium](https://img.shields.io/badge/Cilium-F8C517?style=for-the-badge&logo=cilium&logoColor=black)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=for-the-badge&logo=istio&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=for-the-badge&logo=pfsense&logoColor=white)
![BGP](https://img.shields.io/badge/BGP-0078D4?style=for-the-badge&logoColor=white)

### Identity & Security
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)
![Zitadel](https://img.shields.io/badge/Zitadel-6C48C5?style=for-the-badge&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=for-the-badge&logo=wazuh&logoColor=white)
![Crowdsec](https://img.shields.io/badge/Crowdsec-1D5D8C?style=for-the-badge&logoColor=white)

### DevOps
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Monitoring & Observability
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![VictoriaMetrics](https://img.shields.io/badge/VictoriaMetrics-621773?style=for-the-badge&logoColor=white)
![Alloy](https://img.shields.io/badge/Alloy-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Gatus](https://img.shields.io/badge/Gatus-46A758?style=for-the-badge&logoColor=white)

### Registries & Artifacts
![Harbor](https://img.shields.io/badge/Harbor-60B932?style=for-the-badge&logo=harbor&logoColor=white)
![JFrog](https://img.shields.io/badge/JFrog-41BF47?style=for-the-badge&logo=jfrog&logoColor=white)

---

## Featured Projects

### DevOps & Infrastructure Tools

<table>
<tr>
<td width="50%">

#### [StageFreight](https://github.com/PrPlanIT/StageFreight)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**Declarative CI/CD engine** for container images. Detect, build, scan, sign, and release — driven by a single `.stagefreight.yml` manifest.

- Multi-registry publishing with tag policies
- Retention, README sync, release badges
- GitLab CI component available

</td>
<td width="50%">

#### [HASteward](https://github.com/PrPlanIT/HASteward)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**High Availability Steward** for stateful database services. Triage, repair, backup, and restore — safely.

- Engines: CloudNativePG (PostgreSQL), Galera (MariaDB)
- Escrow backups before repair, restic-backed
- Runs as a K8s Job, no cluster privileges required

</td>
</tr>
<tr>
<td width="50%">

#### [Fairer-Pages](https://github.com/PrPlanIT/fairer-pages)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)

**Custom error and default page server** for Gateway API / reverse proxy environments.

- Serves branded error pages (404, 502, etc.)
- Catch-all HTTPRoute fallback across gateways
- Lightweight, single binary

</td>
<td width="50%">

#### [VirtualDisplayDriver_Wizard](https://github.com/PrPlanIT/VirtualDisplayDriver_Wizard)
![AutoHotkey](https://img.shields.io/badge/AutoHotkey-334455?style=flat&logo=autohotkey&logoColor=white)
![Stars](https://img.shields.io/github/stars/PrPlanIT/VirtualDisplayDriver_Wizard?style=social)

**AutoHotkey GUI** for Indirect Display Driver management. Integrates with Sunshine for remote gaming/desktop streaming.

- One-click install/uninstall/reload
- Driver configuration management
- Virtual display setup for headless hosts

</td>
</tr>
<tr>
<td width="50%">

#### [DD-UI](https://github.com/PrPlanIT/DD-UI)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Stars](https://img.shields.io/github/stars/PrPlanIT/DD-UI?style=social)

**Declarative, security-first Docker orchestration engine.**

*"Sometimes you need someone else to take the wheel... Please Docker responsibly."*

- Declarative configuration
- Security-first architecture
- Simplified container management

</td>
<td width="50%">

#### [PVE_Ceph-Disaster_Recovery](https://github.com/HomeLabHD/PVE_Ceph-Disaster_Recovery)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![Stars](https://img.shields.io/github/stars/HomeLabHD/PVE_Ceph-Disaster_Recovery?style=social)

**Shell-based recovery** for Ceph monitor stores when your Proxmox cluster has lost all monitors.

- Restore monitor quorum from OSDs
- Automated disaster recovery process
- Battle-tested on production clusters

</td>
</tr>
</table>

### Container Images

<table>
<tr>
<td width="50%">

#### [oh-ci](https://github.com/PrPlanIT/oh-ci)
![Dockerfile](https://img.shields.io/badge/Dockerfile-2496ED?style=flat&logo=docker&logoColor=white)

Minimal CI/automation image. bash, coreutils, curl, git, jq, envsubst, and a Pokémon.

</td>
<td width="50%">

#### HomeLab Helpdesk Catalog
[![HomeLabHD](https://img.shields.io/badge/HomeLabHD-181717?style=flat&logo=github&logoColor=white)](https://github.com/HomeLabHD)
[![Docker Hub](https://img.shields.io/badge/hlhd-2496ED?style=flat&logo=docker&logoColor=white)](https://hub.docker.com/u/hlhd)

Community container images for homelab and CI — [apt-cacher-ng](https://github.com/HomeLabHD/apt-cacher-ng), [ansible](https://github.com/HomeLabHD/ansible), [nginx-extras](https://github.com/HomeLabHD/nginx-extras), [ark-se-server](https://github.com/HomeLabHD/ark-se-server), and more.

</td>
</tr>
</table>

---

## Contributing

- Fork the repository
- Submit Pull Requests / Merge Requests
- Open issues with ideas, bugs, or feature requests

---

## Disclaimer

The Software provided hereunder is licensed "as-is," without warranties of any kind. The developer makes no promises about functionality, performance, or availability. Not responsible if your CI pipeline automates itself out of a job, your retention policies work so well your registry bill drops and finance gets confused, or your infrastructure becomes so stable you forget how to troubleshoot.

Any resemblance to working software is entirely intentional but not guaranteed. The developer claims no credit for anything that actually goes right — that's all you and the unstoppable force of the Open Source community.

---

## License

Distributed under the **AGPL-3.0-only** License.

Most projects can be inferred as AGPL-3.0 FOSS with the following terms:

- **Personal / homelab use** — free forever
- **Non-profit / charitable organizations** — free forever
- **Commercial use** — free under 50 users and under $120K annual revenue
- Beyond those thresholds, reach out for a commercial license

See each repository for specific licensing details.
