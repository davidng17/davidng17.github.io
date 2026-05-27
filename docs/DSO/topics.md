# 🔐 DSO — Topics & Blog Ideas

> Deep-dive subjects across the DevSecOps landscape.

---

## 🐧 Must-Know Foundations

- [ ] Linux administration: systemd, cron, file permissions, process management
- [ ] Networking essentials: TCP/IP, DNS resolution, firewalls (iptables/nftables), NAT
- [ ] Shell scripting: Bash, automation patterns, error handling
- [ ] Git workflows: branching models, merge strategies, hooks

## 🔄 CI/CD & Automation

- [ ] From "it runs on my machine" to "it works on my cluster"
- [ ] Fully automated deployment pipelines
- [ ] Pipeline design: build → test → scan → deploy → verify
- [ ] Artifact management: container registries, versioning strategies
- [ ] Feature flags and progressive delivery

## 🐳 Containers & Orchestration

- [ ] Docker: image optimization, layer caching, security scanning
- [ ] Kubernetes: networking (CNI), storage (PV/PVC), RBAC, resource limits
- [ ] Helm vs Kustomize: when to use which
- [ ] How do our apps look like in traditional or cloud-native world or hybrid world?

## 🚀 GitOps & Delivery

- [ ] GitOps: ArgoCD — app-of-apps, sync waves, health checks
- [ ] Service Mesh: Istio, Linkerd, Consul — when do you actually need one?
- [ ] Blue-Green, Canary, Rolling deployments in Kubernetes

## 🏗️ Infrastructure as Code

- [ ] Terraform: modules, state locking, workspaces, drift detection
- [ ] Ansible: idempotency, roles, vault for secrets
- [ ] Crossplane: Kubernetes-native infrastructure provisioning
- [ ] Infrastructure testing: Terratest, checkov, tflint

## 📊 Monitoring & Observability

- [ ] Metrics: Prometheus, Grafana dashboards, alerting rules (golden signals)
- [ ] Logging: ELK/EFK stack, structured logging, log rotation
- [ ] Tracing: OpenTelemetry, Jaeger — distributed request tracing
- [ ] Incident response: runbooks, on-call, post-mortems, SLI/SLO/SLA

## 💾 Backup & Disaster Recovery

- [ ] Database backup strategies: full, incremental, point-in-time recovery
- [ ] Automated backup with retention policies and lifecycle rules
- [ ] Disaster recovery planning: RTO/RPO, failover, multi-region
- [ ] Backup verification: restore testing, data integrity checks
- [ ] Velero for Kubernetes backup and migration

## 🛡️ Security (DevSecOps)

- [ ] Security testing: SAST, DAST, IAST, SCA — tools and pipeline integration
- [ ] Container security: image scanning (Trivy, Snyk), runtime protection (Falco)
- [ ] Cloud Security: AWS (IAM, Security Groups, GuardDuty, Config)
- [ ] Secrets management: HashiCorp Vault, AWS Secrets Manager, sealed-secrets
- [ ] Supply chain security: SBOM, signed images, dependency pinning
- [ ] Security Compliance: PCI DSS, HIPAA, GDPR, ISO 27001, SOC 2

## 🌐 Networking & Access

- [ ] Load balancing: L4 vs L7, HAProxy, NGINX, AWS ALB/NLB
- [ ] TLS/mTLS: certificate management, cert-manager, Let's Encrypt
- [ ] VPN & Zero Trust: WireGuard, Tailscale, BeyondCorp model
- [ ] DNS management: Route53, external-dns, split-horizon DNS
- [ ] WAF: ModSecurity, AWS WAF, Cloudflare — rule tuning

## ☁️ Cloud Platforms

- [ ] AWS core services: VPC, EC2, EKS, RDS, S3, CloudFront, Lambda
- [ ] Cost optimization: right-sizing, spot instances, reserved capacity
- [ ] Multi-account strategy: AWS Organizations, landing zones
