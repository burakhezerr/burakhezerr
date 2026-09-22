### Hi, I'm Burak — AI/DevOps Engineer

I build and run cloud infrastructure, and I build the AI tooling that operates it. 3+ years of hands-on work on AWS, Kubernetes and Terraform, across **100+ customer projects**, from startups running their first workload to enterprises with multi-account, hybrid environments.

Day to day this means Terraform and Kubernetes, production operations for platforms that see sudden traffic peaks, cost and security reviews with the remediation work that follows them, incident response with written root cause analysis, and MCP servers and agents that answer operational questions about live AWS accounts.

Graduated in **July 2026** from **Bahçeşehir University — Computer Engineering** (full scholarship, 2022–2026), spending the last three years working full time in DevOps alongside my studies.

Istanbul, Türkiye

---

### AI & Agentic Engineering

- **MCP servers** — built with Python and FastAPI: an AWS DevOps assistant that answers operations, cost and security questions against live accounts through read-only AWS APIs, plus MCP servers for Notion, email and chart generation. Deployed to Kubernetes like any other service.
- **Agent quality** — evaluation harnesses that measure tool selection and answer accuracy across hundreds of questions, so an agent change can be compared instead of guessed at.
- **Chat integration** — a Microsoft Bot Framework bridge that puts an agent in Microsoft Teams, so non-engineers can ask infrastructure questions without a console or a CLI.
- **Agent-driven modernization** — AWS Transform (`atx`): custom transformation definitions run locally and in fleet mode on AWS Batch, for codebase analysis and Python, Java and Node.js version upgrades, with test runs before and after to verify what the agent changed.
- **Automation** — Playwright in Lambda container images for browser automation and scraping workloads.

---

### Cloud & Infrastructure

- **AWS** — multi-account architecture, VPC & subnet design, EKS, ECS (Fargate and EC2 capacity providers), EC2, Lambda, API Gateway, Elastic Beanstalk, Route53, RDS & Aurora, DynamoDB, ElastiCache Redis, MSK, SQS/SNS/EventBridge, ALB/NLB, CloudFront, WAF, Transit Gateway, Site-to-Site & Client VPN, VPC endpoints, IAM/IRSA, Organizations & SCPs, Secrets Manager, KMS, Local Zones
- **IaC** — Terraform (module design, multi-environment layouts, workspaces, remote state, `for_each`/`dynamic`/`templatefile`, preconditions that block an apply against the wrong environment, brownfield imports), CloudFormation
- **Containers & Orchestration** — Kubernetes on EKS and on-prem (RKE2/Rancher, Longhorn), Docker, Helm, Kustomize (base/overlay), HPA, KEDA, Cluster Autoscaler, Karpenter, pod disruption budgets, graceful shutdown and preStop handling, resource requests/limits tuning, RBAC
- **CI/CD** — GitHub Actions, Bitbucket Pipelines (OIDC-based AWS auth, no long-lived keys), AWS CodePipeline/CodeBuild/CodeDeploy with blue/green releases and automatic rollback, Argo CD, Jenkins
- **Platform Tooling** — FluentBit, Telegraf, Stakater Reloader, Secrets Store CSI Driver, ExternalDNS, cert-manager, SonarQube

---

### Observability Stack

- **Metrics** — kube-prometheus-stack, VictoriaMetrics, Prometheus, kube-state-metrics, node-exporter, CloudWatch
- **Logs** — VictoriaLogs (LogsQL), Grafana Loki, FluentBit routing, CloudWatch Logs with retention policies
- **Tracing** — OpenTelemetry Operator & Collector, Grafana Tempo
- **Dashboards & Alerting** — Grafana as code (HPA status, nginx access logs, pod resources, PHP-FPM metrics, API response codes/times, distributed traces) with custom alerting rules and notification policies; auditing alert rules against live metrics so they actually fire when something breaks
- **Load & performance testing** — k6 and JMeter, plus packet-level analysis when application symptoms and infrastructure metrics disagree

---

### Cost & Governance

- Cost optimization with Cost Explorer & Budgets — EC2 and container right-sizing from real utilization data, S3 lifecycle policies, CloudWatch log retention limits, releasing idle public IPv4 addresses, consolidating load balancers and NAT gateways, scheduling non-production environments to scale to zero outside working hours
- Reserved Instance and Savings Plan strategies, Spot for suitable workloads, Fargate vs EC2 comparisons backed by pricing models
- Multi-account tagging strategies for chargeback and per-team / per-project visibility
- AWS Organizations and Service Control Policies (SCPs) for compliance and cost guardrails
- AWS Well-Architected Reviews, account reviews and cloud security posture assessments, each delivered with a prioritized remediation plan
- Data residency work under KVKK/GDPR, including hybrid designs around what a region or Local Zone actually supports

---

### Languages & Tools

- **Python**, **Bash**, **SQL**
- Terraform, Helm, Kustomize, Docker, Git, Linux
- FastAPI for small internal services and MCP servers

---

### Engineering Practices

- Security — least-privilege IAM, keyless CI with OIDC, IRSA for pods, secrets from Secrets Manager rather than repositories or CI variables, WAF as code
- Reliability — incident response, root cause analysis and written RCAs, runbooks for rare but risky operations, capacity reports after major traffic events
- Automation first — if an incident does not end in an alert, a runbook or a piece of automation, it will happen again
- Testing — unit and integration testing, load and performance testing before traffic peaks rather than after
- Observability — structured logging, distributed tracing, dashboards and alerts kept in version control
- Documentation — architecture notes, platform guides and operations runbooks written so someone else can run the system

---

### AWS Certifications

<table>
  <tr>
    <td align="center">
      <a href="https://www.credly.com/badges/80ba4458-b85c-4e9d-99d1-e369135a386b" target="_blank">
        <img src="assets/cert-architect.png" width="120" alt="AWS Solutions Architect Professional"/><br/>
        <sub><b>Solutions Architect – Professional</b></sub><br/>
        <sub>Dec 2025 · Valid until Dec 2028</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://www.credly.com/badges/e8df7331-7d7e-4809-92d9-ddb6d38b9978" target="_blank">
        <img src="assets/cert-devops.png" width="120" alt="AWS DevOps Engineer Professional"/><br/>
        <sub><b>DevOps Engineer – Professional</b></sub><br/>
        <sub>Aug 2024 · Valid until Aug 2027</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://www.credly.com/badges/ad65a7eb-cbc6-40cd-9dc5-4c6e47e0235d" target="_blank">
        <img src="assets/cert-developer.png" width="120" alt="AWS Developer Associate"/><br/>
        <sub><b>Developer – Associate</b></sub><br/>
        <sub>Mar 2024 · Valid until Aug 2027</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://www.credly.com/badges/327453a5-8cc5-4838-8a73-c57550a75f3f" target="_blank">
        <img src="assets/cert-practitioner.png" width="120" alt="AWS Cloud Practitioner"/><br/>
        <sub><b>Cloud Practitioner</b></sub><br/>
        <sub>Oct 2023 · Valid until Dec 2028</sub>
      </a>
    </td>
  </tr>
</table>

---

### Connect

- LinkedIn: [burakhezerr](https://www.linkedin.com/in/burakhezerr/)
- Email: [25burak.hezer@gmail.com](mailto:25burak.hezer@gmail.com)
