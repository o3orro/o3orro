# 👋 안녕하세요, DevOps / Cloud Engineer를 준비하고 있습니다.

Kubernetes 기반 인프라 구축과 자동화에 관심을 가지고 있으며,  
On-Premise 환경에서 **인프라 구축 → 자동화 → CI/CD → 모니터링 → DR**까지 직접 구현한 경험이 있습니다.

현재는 On-Premise 환경에서의 경험을 기반으로  
**AWS · ROSA · Terraform을 활용한 Cloud / OpenShift 환경**으로 영역을 확장하고 있습니다.

---

## 🛠 Tech Stack

### Container & Orchestration
`Kubernetes` `OpenShift` `Docker` `containerd` `k3s`

### DevOps & Automation
`Ansible` `Jenkins` `Argo CD` `Kustomize` `Terraform` `Git`

### Cloud
`AWS` `ROSA`

### Infrastructure
`HAProxy` `Keepalived` `NGINX Gateway Fabric` `Harbor` `NFS` `MinIO`

### Database
`MariaDB` `MaxScale`

### Monitoring
`Prometheus` `Grafana` `Alertmanager` `Loki`

### OS & Network
`Linux` `CentOS Stream` `DNS` `NTP` `TCP/IP`

---

## 🚀 Featured Project

### NeuroPlan — On-Premise Kubernetes Infrastructure

고가용성 Kubernetes 인프라에서 애플리케이션을 안정적으로 운영할 수 있도록  
**인프라 자동화, CI/CD, GitOps, 모니터링 및 DR 환경**을 구축한 프로젝트입니다.

**담당 영역**
- Ansible 기반 공통 인프라 구성 및 자동화
- Jenkins 기반 CI 파이프라인 구축
- Harbor Private Registry 연동
- Kustomize + Argo CD 기반 GitOps CD 구성
- Kubernetes / VM Health Check 자동화
- Prometheus · Grafana 기반 모니터링
- k3s 기반 DR 환경 자동화
- 장애 시나리오 및 복구 검증

**Architecture**

```text
Developer
    │
    ▼
  GitHub
    │
    ▼
 Jenkins
    │
    ▼
 Docker Build
    │
    ▼
  Harbor
    │
    ▼
Kustomize
    │
    ▼
 Argo CD
    │
    ▼
Kubernetes
```

### Repositories

- 🧩 [Ansible Automation](../neuroplan-ansible)
- 🔄 [GitOps Configuration](../neuroplan-gitops)
- 💻 [NeuroPlan Application](../neuroplan-app)

---

## ☁️ Currently Learning

On-Premise Kubernetes 환경에서의 구축 경험을 바탕으로  
Cloud Native 환경으로 기술 영역을 확장하고 있습니다.

`AWS` `ROSA HCP` `Terraform` `OpenShift GitOps` `RDS` `ECR`

---

## 🎯 Interests

- Infrastructure as Code
- Kubernetes / OpenShift
- Infrastructure Automation
- CI/CD & GitOps
- High Availability
- Monitoring
- Disaster Recovery
- Cloud Infrastructure
