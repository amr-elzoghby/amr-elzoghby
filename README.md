<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=220&section=header&text=Hi%20there,%20I'm%20Amr!%20👋&fontSize=55&animation=fadeIn&fontAlignY=38&desc=DevOps%20%26%20Platform%20Engineer%20%7C%20Cloud%20Infrastructure%20%7C%20AWS%20%2F%20Kubernetes%20%2F%20Terraform&descAlignY=57&descAlign=50&descSize=17" />
</div>

<h3 align="center">
  Automating infrastructure, building Internal Developer Platforms, and shipping production-grade systems.
</h3>

<div align="center">
  <a href="https://d2udg2xbc863j7.cloudfront.net">
    <img src="https://img.shields.io/badge/🌐%20Portfolio-Visit%20Now-0D1117?style=for-the-badge&labelColor=2D9CDB" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/amr-saad-27070b3a8">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:amr.s.elzoghby@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</div>

<br />

---

## 🚀 About Me

- 🔭 Currently focused on **Platform Engineering, Cloud Infrastructure (AWS), IaC (Terraform/Crossplane), and Kubernetes**
- 🏗️ Just shipped: A multi-tenant **Internal Developer Platform (IDP)** on AWS EKS with Crossplane self-service & Kyverno guardrails
- ⚡ Also built: A high-scale **E-Commerce Microservices Platform** on AWS EKS, load-tested for **15,000+ concurrent users**
- 💼 **Available immediately for full-time remote opportunities.**
- 🎓 High school graduate (Class of 2026) | Entering University Degree Program (Fall 2026)

---

## 🛠️ Tech Stack & Tools

<div align="center">

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Crossplane](https://img.shields.io/badge/Crossplane-3776AB?style=for-the-badge&logo=crossplane&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)

**CI/CD, GitOps & Multi-Tenancy**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![vCluster](https://img.shields.io/badge/vCluster-2563EB?style=for-the-badge&logo=kubernetes&logoColor=white)
![Karpenter](https://img.shields.io/badge/Karpenter-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Governance, Security & Observability**

![Kyverno](https://img.shields.io/badge/Kyverno-009639?style=for-the-badge&logo=kyverno&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5C400?style=for-the-badge&logo=grafana&logoColor=black)
![Trivy](https://img.shields.io/badge/Trivy-1D262F?style=for-the-badge&logo=aquasecurity&logoColor=white)
![Falco](https://img.shields.io/badge/Falco-00A89D?style=for-the-badge&logo=falco&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## 🔥 Featured Projects

### 🛠️ 1. Internal Developer Platform (IDP)

> Self-service cloud infrastructure & multi-tenant GitOps platform built on AWS EKS.

| | |
|:---|:---|
| ☁️ **Cloud & Multi-Tenancy** | AWS EKS, Terraform, **vCluster** virtual control planes, **Karpenter** autoscaling |
| 📦 **IaC Self-Service** | **Crossplane** (RDS, S3, Redis, EC2 & SecurityGroups via K8s CRDs) |
| 🔄 **GitOps & CI/CD** | **ArgoCD ApplicationSets** + **GitHub Actions OIDC** + ECR auto-builds |
| 🛡️ **Governance & Security** | **Kyverno** ClusterPolicies (Pod security & Crossplane cost guardrails), Trivy |
| 🔒 **Network & Security** | AWS KMS encryption, IMDSv2, IRSA IAM roles, non-NAT VPC Endpoints |

<br>
<div align="center">

[![IDP Repo](https://img.shields.io/badge/GitHub-Internal--Developer--Platform-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amr-elzoghby/Internal-Developer-Platform)

</div>
<br>

---

### 🛒 2. ShopScale — High-Scale E-Commerce Platform

> Production-grade e-commerce microservices platform, engineered for scale.

| | |
|:---|:---|
| ☁️ **Infrastructure** | Modular Terraform IaC (VPC → EKS) with isolated state layers |
| ☸️ **Orchestration** | Node.js & Python FastAPI on **Kubernetes EKS** with **gRPC** |
| ⚡ **Auto-Scaling** | HPA + Cluster Autoscaler — **15,000+ concurrent users** load-tested |
| 🔄 **CI/CD & GitOps**| GitHub Actions (OIDC) + **ArgoCD** for zero-touch deployments |
| 🔒 **Security** | IRSA, Trivy, Falco, VPC Endpoints (no NAT Gateway) |
| 📊 **Observability** | Prometheus + Grafana + Loki — auto-deployed via Helm |

<br>
<div align="center">

[![ShopScale Repo](https://img.shields.io/badge/GitHub-High--Scale--Ecommerce--K8s--15K--Concurrent-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amr-elzoghby/High-Scale-Ecommerce-K8s-15K-Concurrent)

</div>
<br>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=amr-elzoghby&theme=tokyonight&hide_border=true&background=0D1117" alt="Amr's GitHub Streak" width="60%" />
</div>

<br>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=amr-elzoghby&theme=tokyonight&no-frame=true&no-bg=true&margin-w=10&column=6" alt="GitHub Trophies" />
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=100&section=footer" />
</div>
