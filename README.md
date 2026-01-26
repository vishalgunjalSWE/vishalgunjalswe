<!-- Banner Image -->

<img src="image.jpeg" alt="GitHub Banner" width="100%" /> 


<!-- Introduction -->

# 👋 Hi, I'm Vishal Gunjal

**DevOps Engineer | Site Reliability Engineering | Cloud-Native Platform Architecture**

Building production-grade cloud platforms on AWS with Kubernetes, Terraform, and GitOps. Passionate about automation, observability, and system reliability.

---

## 🚀 What I Do

I specialize in **cloud-native infrastructure** and **platform engineering**, with hands-on experience building:

- **Microservices platforms** on AWS EKS with event-driven architecture (RabbitMQ, Kafka)
- **Infrastructure as Code** using Terraform with modular, reusable patterns
- **GitOps workflows** with ArgoCD for declarative, drift-free deployments
- **Full observability stacks** (Prometheus, Grafana, ELK, Jaeger)
- **DevSecOps pipelines** with automated security scanning (SonarQube, Trivy)

---

## 💼 Current Focus

- 🔨 Building production-grade DevOps projects demonstrating enterprise patterns
- 📚 Deep-diving into **Kubernetes** (RBAC, Network Policies, Security, Operators)
- 🔐 Implementing **DevSecOps** practices (shift-left security, policy-as-code)
- 📊 Designing **SRE observability** systems (SLIs, SLOs, error budgets)
- 🤖 Exploring **MLOps** and **AI-driven infrastructure automation**

---

## 🧠 Engineering Philosophy

**I believe in:**
- **Infrastructure as Code** - Everything reproducible, version-controlled, tested
- **GitOps Over ClickOps** - Declarative state, automated reconciliation
- **Observability First** - Metrics, logs, traces before production
- **Security by Default** - RBAC, Network Policies, zero-trust networking
- **SRE Principles** - SLIs/SLOs, error budgets, toil reduction

**I don't believe in:**
- Manual deployments or "works on my machine" syndrome
- Infrastructure without monitoring
- Code without tests or automation without guardrails

---

## 🛠️ Tech Stack

<table align="center">
  <tr>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=aws" width="48" /><br>AWS
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=azure" width="48" /><br>Azure
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=gcp" width="48" /><br>GCP
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=kubernetes" width="48" /><br>Kubernetes
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=docker" width="48" /><br>Docker
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=terraform" width="48" /><br>Terraform
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=ansible" width="48" /><br>Ansible
    </td>
    <td align="center" width="96">
      <img src="https://th.bing.com/th/id/OIP.ItRTdPy1CgAol_osPwc-sAHaHa?w=158&h=180&c=7&r=0&o=7&pid=1.7&rm=3" width="60" /><br>Helm
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=linux" width="48" /><br>Linux
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=jenkins" width="48" /><br>Jenkins
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=githubactions" width="48" /><br>GitHub Actions
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/argo-cd.png" width="48" /><br>ArgoCD
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=grafana" width="48" /><br>Grafana
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=prometheus" width="48" /><br>Prometheus
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=elasticsearch" width="48" /><br>ELK
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=go" width="48" /><br>Go
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=python" width="48" /><br>Python
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=git" width="48" /><br>Git
    </td>
  </tr>
</table>

---

## 🏗️ What I Build

### **Production-Grade Cloud Platforms**
I architect and implement complete cloud-native systems, not just tutorials or toy projects:

**Complexity Level:**
- ✅ Multi-service architectures (8+ microservices)
- ✅ Event-driven patterns (async messaging, pub/sub, DLQs)
- ✅ Multi-AZ infrastructure (HA, fault tolerance, disaster recovery)
- ✅ Full observability (metrics, logs, traces - three pillars)
- ✅ Security hardening (RBAC, Network Policies, IRSA, Pod Security)
- ✅ GitOps workflows (Git as single source of truth)

---

## 📚 Featured Work

### 1️⃣ [Cloud-Native E-Commerce Platform](https://github.com/vishalgunjalSWE/cloud-native-retail-platform)
**Production-grade microservices on AWS EKS**

**What makes this different:**
- 8 independent microservices with proper domain boundaries (DDD principles)
- Event-driven architecture preventing cascading failures
- Multi-AZ infrastructure with automated failover
- Distributed caching reducing database load
- Full observability with correlation IDs for request tracing

**Architecture Decisions:**
```
Why RabbitMQ over Kafka?
→ Simpler ops for project scale, better routing patterns, DLQ support

Why Redis cache-aside pattern?
→ Handles cache misses gracefully, prevents stampede on cache clear

Why IRSA over hardcoded credentials?
→ Temporary credentials, automatic rotation, AWS IAM integration

Why GitOps with ArgoCD?
→ Git as audit trail, automated drift correction, declarative state
```

**Tech:** Go, Java, Node.js | Kubernetes (EKS) | Terraform | ArgoCD | RabbitMQ | Redis | Prometheus | Grafana | Jaeger

**Skills Demonstrated:**
- Microservices decomposition
- Event-driven architecture
- Distributed caching strategies
- Kubernetes security (RBAC, Network Policies, Pod Security)
- Infrastructure as Code (Terraform modules, remote state)
- GitOps automation
- SRE observability (RED metrics, SLOs, distributed tracing)

---

### 2️⃣ [Enterprise DevSecOps Platform](https://github.com/vishalgunjalSWE/wanderlust-devsecops-gitops)
**Shift-left security with automated CI/CD and observability**

**What makes this different:**
- Reusable pipeline logic (Groovy shared libraries)
- Security scanning at multiple stages (SAST, container, IaC)
- Centralized logging with request correlation
- Infrastructure drift detection and remediation
- DORA metrics tracking for continuous improvement

**Architecture Decisions:**
```
Why Jenkins shared libraries?
→ DRY principle, standardized pipelines, easier maintenance

Why ELK over CloudWatch?
→ Better aggregation, custom dashboards, correlation IDs, cost control

Why scheduled drift detection?
→ Catch manual changes, enforce GitOps, prevent config drift

Why Infracost integration?
→ Cost awareness before apply, prevent bill shock, FinOps culture
```

**Tech:** Jenkins (Groovy) | Terraform | SonarQube | Trivy | ELK Stack | ArgoCD | Prometheus | Grafana

**Skills Demonstrated:**
- CI/CD pipeline engineering
- Shift-left security (DevSecOps)
- Centralized logging and correlation
- Infrastructure automation
- Cost optimization awareness
- Platform observability

---

<!-- ## 📝 Technical Writing

I write in-depth technical articles explaining the "why" behind infrastructure decisions:

**Recent Articles:**
- **Kubernetes RBAC Deep-Dive** - Implementing least-privilege access patterns
- **GitOps vs Traditional CD** - Trade-offs and decision framework
- **Terraform State Management** - Remote state, locking, and team collaboration
- **Observability Patterns** - Metrics, logs, traces, and correlation strategies

  </a>
    <a href="https://medium.com/@vishalgunjal" target="_blank">
    <img src="https://img.shields.io/badge/Read on Medium -12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/>
  </a>
</p> -->
## 📝 The "1% SRE Roadmap" Series

I document my journey from fundamental concepts to advanced SRE implementations on Medium.

➡️ [Read more articles on Medium](https://medium.com/@vishalgunjal)

---

## 🌐 Community Involvement

**Active Participation:**
- **Google Developer Group (GDG) Pune** - Cloud-native discussions, hands-on labs
- **CNCF Community** - Kubernetes, service mesh, observability
- **AWS User Group Pune** - Best practices, architecture patterns
- **Atlassian Community Pune** - CI/CD, DevOps automation

---

## 🎯 2025 Goals

**Technical:**
- ✅ Build 4 production-grade cloud platforms (Complete)
- 🔄 Contribute to CNCF projects (Kubernetes, Prometheus, ArgoCD)
- 📚 Deep-dive into Kubernetes operators and CRDs
- 🔐 Master service mesh (Istio/Linkerd) and zero-trust networking
- 🤖 Explore MLOps and infrastructure for ML workloads

**Professional:**
- 📝 Publish 25+ in-depth technical articles
- 🎤 Present at GDG Pune and AWS User Group
- 💼 Land first DevOps/SRE role at product company or cloud-native startup
- 🌟 Contribute to open-source (Kubernetes, Terraform providers, Helm charts)

**Learning:**
- 📖 Complete AWS DevOps Professional certification
- 📖 Complete CKA and CKS certifications
- 📖 Study distributed systems papers (Raft, Paxos, CAP theorem)

---

## 💡 What Drives Me

I'm fascinated by **systems that scale, self-heal, and never go down.**

Questions that keep me up at night:
- How does Kubernetes reconcile desired vs actual state?
- What trade-offs did AWS make in EKS networking design?
- How do Netflix and Google achieve 99.99% uptime?
- What's the right balance between consistency and availability?
- How do you design alerts that don't cause alert fatigue?

**I don't just want to use tools - I want to understand how they work under the hood.**

---

## 📈 Contribution Graph

[![Vishal's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=vishalgunjalSWE&theme=tokyo-night&hide_border=true)](https://github.com/vishalgunjalSWE)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=vishalgunjalSWE&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views"/>
</p>

<p align="center">
  <i>⚡ "Automation is not about replacing humans, it's about freeing them to do what they do best."</i>
</p>

---

**💼 Open to opportunities:** DevOps Engineer | SRE | Platform Engineer | Cloud Engineer  
**📍 Location:** Pune, India (Open to Remote & Relocation)  
**📧 Contact:** vishalgunjal0287@gmail.com
