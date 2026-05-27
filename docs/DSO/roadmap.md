# 🔐 DSO — Learning Roadmap

> From Linux fundamentals to platform engineering mastery.

---

## 1️⃣ Linux

- [ ] Commands, tools, shell scripting (Bash)
- [ ] Administration: users, files, processes, logs, systemd, cron
- [ ] Security: firewalls (iptables/nftables), SELinux, access controls

## 2️⃣ Networking Fundamentals

- [ ] TCP/IP, HTTP, SSL/TLS, mTLS, HTTP/2
- [ ] DNS: resolution, caching, DNSSEC, DNS over TLS/HTTPS
- [ ] SSH: authentication, key management, tunneling, config
- [ ] VPN: IPsec, OpenVPN, WireGuard
- [ ] Load balancing: L4 vs L7, HAProxy, NGINX, AWS ALB/NLB
- [ ] CDN: CloudFront, Cloudflare
- [ ] Network troubleshooting: diagnostics, packet analysis, performance

## 3️⃣ Git & Collaboration

- [ ] Branching models: GitFlow, trunk-based development
- [ ] Merge strategies, hooks, monorepo vs polyrepo

## 4️⃣ CI/CD Pipelines

- [ ] Pipeline design: build → test → scan → deploy → verify
- [ ] Tools: Jenkins, GitHub Actions, GitLab CI
- [ ] Artifact management, versioning, promotion strategies
- [ ] DevOps lifecycle, feedback loops

## 5️⃣ Infrastructure as Code

- [ ] Terraform: modules, state management, workspaces, drift detection
- [ ] Ansible: playbooks, roles, vault, idempotency
- [ ] Crossplane: Kubernetes-native provisioning
- [ ] Testing: Terratest, checkov, tflint

## 6️⃣ Containerization

- [ ] Docker: images, multi-stage builds, networking, volumes
- [ ] Docker security: image scanning, isolation, secrets, resource limits
- [ ] Container registries, tagging strategies

## 7️⃣ Kubernetes

- [ ] Core: pods, deployments, services, ingress, configmaps, secrets
- [ ] Networking: CNI, network policies, service discovery
- [ ] Storage: PV/PVC, StorageClasses, CSI drivers
- [ ] RBAC, service accounts, pod security standards
- [ ] Helm, Kustomize
- [ ] Scaling: HPA, VPA, cluster autoscaler
- [ ] Troubleshooting: logs, events, debugging pods

## 8️⃣ Monitoring & Observability

- [ ] Metrics: Prometheus, Grafana, golden signals (latency, traffic, errors, saturation)
- [ ] Logging: ELK/EFK stack, structured logging, log rotation
- [ ] Tracing: OpenTelemetry, Jaeger
- [ ] Alerting: rules, escalation, on-call, PagerDuty
- [ ] Incident response: runbooks, post-mortems, SLI/SLO/SLA

## 9️⃣ Security (DevSecOps)

- [ ] Security testing in pipelines: SAST, DAST, IAST, SCA
- [ ] Container security: Trivy, Snyk, Falco (runtime)
- [ ] Supply chain: SBOM, signed images, dependency pinning
- [ ] Web application security: OWASP, WAF (ModSecurity, AWS WAF, Cloudflare)
- [ ] API security: authentication, authorization, rate limiting
- [ ] Cloud security: IAM, Security Groups, GuardDuty, Config
- [ ] Secrets management: Vault, AWS Secrets Manager, sealed-secrets
- [ ] Compliance: PCI DSS, HIPAA, GDPR, ISO 27001, SOC 2

## 🔟 Cloud Platforms (AWS focus)

- [ ] Compute: EC2, ECS, EKS, Lambda, Fargate
- [ ] Storage: S3, EBS, EFS, RDS, DynamoDB
- [ ] Networking: VPC, Route53, CloudFront, API Gateway
- [ ] Cost optimization: right-sizing, spot instances, reserved capacity
- [ ] Multi-account strategy: Organizations, landing zones

## 1️⃣1️⃣ Backup & Disaster Recovery

- [ ] Backup strategies: full, incremental, point-in-time recovery
- [ ] Automated backup with retention policies
- [ ] DR planning: RTO/RPO, failover, multi-region
- [ ] Velero for Kubernetes backup
- [ ] Restore testing and verification

## 1️⃣2️⃣ GitOps

- [ ] ArgoCD: app-of-apps, sync waves, health checks
- [ ] Flux as alternative
- [ ] Environment promotion patterns

## 1️⃣3️⃣ Advanced

- [ ] Service Mesh: Istio, Linkerd — traffic management, mTLS, observability
- [ ] Progressive delivery: Canary, Blue-Green with Argo Rollouts
- [ ] Multi-cluster Kubernetes
- [ ] Chaos engineering: Litmus, Chaos Monkey
- [ ] Platform engineering: internal developer platforms, Backstage
