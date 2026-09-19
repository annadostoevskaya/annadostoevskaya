# Temirbek Rakhimgalyiev

### Site Reliability & Platform Engineer
**Astana, Kazakhstan (Open to Worldwide Remote)**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?logo=linkedin)](https://www.linkedin.com/in/temirbek-rakhimgalyiev-443174246/)
[![Telegram](https://img.shields.io/badge/Telegram-@celeb__18-2CA5E0?logo=telegram)](https://t.me/celeb_18)
[![Email](https://img.shields.io/badge/Email-temirbek.18052003@gmail.com-D14836?logo=gmail)](mailto:temirbek.18052003@gmail.com)

---

## About

Site Reliability and Systems Engineer specializing in bare-metal fleet operations, high-availability container platforms, and declarative infrastructure automation. Practical experience spanning on-premises hardware provisioning (PXE/iPXE, IPMI/Redfish), Linux kernel and network tuning, and operating mission-critical production services.

* **Education:** Master of Science in Cybersecurity (ENU, ongoing) · BSc in Radio Engineering & Telecommunications (Honors / High Distinction).
* **Experience:** DevOps Engineer at Rocket Tech (2.5+ yrs), Infrastructure Engineer on bare-metal compute platforms, Backend Engineer (HealthTech).
* **Focus Areas:** Bare-metal provisioning, Kubernetes control-plane HA (`kube-vip`), FluxCD GitOps, PostgreSQL reliability (PITR), out-of-band telemetry, and Linux kernel parameter tuning (USE method).

---

## Featured Engineering Projects

| Project | Description | Primary Tech |
| :--- | :--- | :--- |
| [**baremetal-rke2-gitops-fleet**](https://github.com/annadostoevskaya/baremetal-rke2-gitops-fleet) | Sanitized reference architecture for an 8-node physical Oracle Linux compute fleet running HA RKE2 with `kube-vip` virtual IP failover, Redfish out-of-band telemetry, and FluxCD GitOps. | `RKE2`, `kube-vip`, `FluxCD`, `iPXE`, `Python` |
| [**iot-telemetry-platform**](https://github.com/annadostoevskaya/iot-telemetry-platform) | Cloud-native IoT telemetry ingestion, time-series storage, and observability platform packaged into production Helm charts with zero-trust secret templates. | `Kubernetes`, `Helm`, `ChirpStack`, `InfluxDB`, `PostgreSQL` |
| [**zero_runtime**](https://github.com/annadostoevskaya/zero_runtime) | Minimalist zero-runtime implementation in Assembly & C demonstrating direct Linux kernel system call invocation without standard library overhead. | `Assembly`, `C`, `Linux Syscalls` |
| [**greenhouse**](https://github.com/annadostoevskaya/greenhouse) | Industrial-grade IoT telemetry and environmental monitoring system linking physical embedded AVR microcontrollers (SPI W5100) to Prometheus & Grafana. | `C++`, `Docker Compose`, `Prometheus`, `GitLab CI` |

---

## Technical Taxonomy

```text
├── Systems & Kernel    : Oracle Linux, Ubuntu, UEFI iPXE, Kickstart, IPMI/Redfish, systemd, sysctl, cgroups, NUMA
├── Orchestration & IaC : Kubernetes (RKE2, kube-vip), FluxCD GitOps, Helm, Kustomize, Terraform, Ansible, OpenStack
├── Observability       : Prometheus, Grafana, Alertmanager, Node Exporter, Loki, InfluxDB, Telegraf
├── Data & Security     : PostgreSQL (WAL-G, streaming replication, PITR), HashiCorp Vault, Redis, S3/MinIO
├── Networking & Edge   : Nginx, Caddy, HAProxy, TCP/IP, TLS/PKI, VLANs, 802.3ad LACP bonding, WireGuard
└── Languages           : Python, Bash, C/C++, Go, SQL, Assembly (x86_64)
```

---

> *Notice: Reference architecture repositories are sanitized and decoupled from proprietary employer data and internal networks to guarantee complete confidentiality and NDA compliance.*
