<!--
  README.md · Pinned to the root of the **planton‑acmecorp** GitHub organisation
  Audience: prospective & current PlantonCloud customers exploring our public demo assets
-->

<p align="center">
  <img src="acmecorp-logo.png" height="110" alt="ACME Corp logo">
</p>

<h2 align="center">Welcome to ACME Corp – PlantonCloud’s Public Demo Organisation</h2>

> **What you are looking at**  
> A curated set of **real, runnable repositories** that we use to demonstrate every major feature of <a href="https://planton.ai">PlantonCloud</a>—our Internal Developer Platform for multi‑cloud CI/CD & infrastructure automation.

---

## 🌐 What is ACME Corp?

ACME Corp is a *fictional but fully functional* software vendor we created to mimic the challenges faced by real‑world engineering teams:

* **Multi‑cloud reality** – Customers ask ACME to deploy workloads in **AWS, GCP, Azure or DigitalOcean**, sometimes in the customer’s own account.
* **Poly‑glot stack** – Code bases span **Node.js, Go, Python, Kotlin, Rust, React, Next.js** and more.
* **Full lifecycle** – From Buildpacks‑driven image builds to Pulumi‑backed infrastructure charts and post‑deploy dashboards.

Because **every repo here is wired into PlantonCloud pipelines and infra‑charts**, you can clone, fork or simply read the code to see *exactly* how we achieve one‑click deployments across clouds.

---
## Team

![Team Overview](https://www.mermaidchart.com/raw/8edcd02e-c0d0-428b-9689-f34fc0691a20?theme=light&version=v0.1&format=svg)

## 🚀 Quick Links

| Product / Demo | Description | Key Cloud Target | Repositories |
|----------------|-------------|------------------|--------------|
| **RetailHub** | E‑commerce toolkit (static storefront + REST & gRPC APIs) | AWS ECS Fargate | <a href="https://github.com/planton-acmecorp/retail-hub-checkout-service">`retail-hub-checkout-service`</a>, <a href="https://github.com/planton-acmecorp/orders-service">`orders-service`</a> |
| **HealthConnect** | HIPAA‑ready event ingestion & analytics | GCP Cloud Run / GKE | _(coming soon)_ |
| **EdgeIQ** | IoT edge telemetry & dashboard | DigitalOcean K8s / Azure AKS | _(coming soon)_ |
| **Org Chart** | Markdown + Mermaid visual of the ACME team (avatars included) | — | <a href="https://github.com/planton-acmecorp/acmecorp-team">`acmecorp-team`</a> |


## 📚 Learning Resources

| Resource | Where | What for |
|----------|-------|----------|
| **PlantonCloud Docs** | <https://docs.planton.cloud> | Platform concepts, CLI, API reference |
| **ACME Corp Deep‑Dive** | `acmecorp/README.md` (meta‑repo, coming soon) | Business narrative, demo playbooks, architectural decisions |
| **Community Discord** | <https://discord.gg/pwcSapdQAp> → `#acmecorp` | Ask questions, suggest improvements |
| **Webinars & Videos** | <https://youtube.com/@PlantonCloud> | Recorded live demos using these repos |

---

## 🙋 Why Open‑Source the Demo Code?

* **Transparency** – See exactly how PlantonCloud builds & deploys across providers.  
* **Learning** – Copy infra‑chart snippets or CI workflows into your own projects.  
* **Feedback loop** – Submit PRs or Issues to improve sample apps; we iterate fast.  

---

## 📝 Contributing

1. Fork the repository you want to improve.  
2. Keep code minimal—these apps are *reference* implementations, not production systems.  
3. Open a PR with a concise description; a maintainer will review within 2 business days.

All code is released under the **MIT License** unless stated otherwise.

---

## 📣 Stay in Touch

* **Twitter / X**: <https://twitter.com/PlantonCloud>  
* **Email**: hello@planton.ai  
* **Newsletter**: Sign up on <https://planton.ai> for monthly product & demo updates.

---

> **Legal & Disclaimer**  
> “ACME Corp” is a fictional entity used solely for demonstration.  
> The repositories are provided **as‑is** with no warranty; use at your own risk.

Happy exploring!  
— The PlantonCloud Team
