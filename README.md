# Awesome-Continuous-Delivery

# Top Continuous Delivery (CD) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on GitOps, Deployment Automation, Progressive Delivery, Multi-Cloud Release & Kubernetes Continuous Delivery*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Continuous Delivery (CD)**. These systems automate the reliable release of software—from build artifacts to production—using pipelines, GitOps, progressive delivery, approvals, and multi-environment promotion.

**Examples** include Harness, Spinnaker, Argo CD, Octopus Deploy, Codefresh, GitLab CD, FluxCD, Azure DevOps Pipelines, Google Cloud Deploy, and Keptn (the category leaders).

**Open-source emphasis**: Continuous Delivery has one of the strongest open-source ecosystems. **Argo CD**, **Flux**, **Spinnaker**, **Tekton**, and related CNCF projects power production GitOps and multi-cloud delivery. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Harness](https://www.harness.io/)**  
  Enterprise continuous delivery platform with progressive delivery, governance, multi-cloud deployments, and strong Kubernetes support.

- **[Spinnaker](https://spinnaker.io/)**  
  Multi-cloud continuous delivery platform (open core with commercial support options) for high-velocity, confident releases across clouds.

- **[Argo CD (Enterprise / Akuity etc.)](https://argo-cd.readthedocs.io/)**  
  Declarative GitOps continuous delivery for Kubernetes; commercial distributions and managed offerings build on the open-source project.

- **[Octopus Deploy](https://octopus.com/)**  
  Mature deployment automation platform with modeled releases, approvals, rollback, and support for cloud, on-prem, and hybrid targets.

- **[Codefresh](https://codefresh.io/)**  
  Kubernetes-native CI/CD and GitOps platform focused on container and cloud-native continuous delivery.

- **[GitLab CD](https://about.gitlab.com/stages-devops-lifecycle/continuous-delivery/)**  
  Built-in continuous delivery within GitLab—pipelines, environments, deployments, and progressive delivery features.

- **[FluxCD (Enterprise / Weave)](https://fluxcd.io/)**  
  Open and extensible GitOps continuous delivery for Kubernetes; commercial support and platforms available around the core.

- **[Azure DevOps Pipelines](https://azure.microsoft.com/en-us/products/devops/pipelines)**  
  Microsoft’s CI/CD service for multi-platform builds and deployments to Azure and beyond.

- **[Google Cloud Deploy](https://cloud.google.com/deploy)**  
  Managed continuous delivery service for GKE, Cloud Run, and related Google Cloud targets with progressive rollout support.

- **[Keptn](https://keptn.sh/)**  
  Event-driven control plane for continuous delivery and automated operations (open source with enterprise options).

## Open-Source GitHub Projects
- **[Argo CD](https://github.com/argoproj/argo-cd)**  
  Leading CNCF declarative GitOps continuous delivery tool for Kubernetes—syncs desired state from Git and provides a powerful UI.

- **[Flux](https://github.com/fluxcd/flux2)**  
  Open and extensible continuous delivery solution for Kubernetes, powered by the GitOps Toolkit (CNCF).

- **[Spinnaker](https://github.com/spinnaker/spinnaker)**  
  Open-source multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.

- **[Tekton](https://github.com/tektoncd/pipeline)**  
  Cloud-native pipeline framework for building CI/CD systems on Kubernetes—flexible tasks and pipelines as code.

- **[PipeCD](https://github.com/pipe-cd/pipecd)**  
  GitOps-style continuous delivery platform for declarative Kubernetes, serverless, and infrastructure applications.

- **[GoCD](https://github.com/gocd/gocd)**  
  Open-source continuous delivery server focused on modeling and visualizing complex deployment workflows.

- **[Jenkins X](https://github.com/jenkins-x/jx)**  
  Automated CI+CD for Kubernetes with Tekton pipelines and preview environments on pull requests.

- **[Keptn](https://github.com/keptn/keptn)**  
  Open-source control plane for continuous delivery and automated operations driven by events and quality gates.

- **[Flagger / progressive delivery controllers](https://github.com/fluxcd/flagger)**  
  Open-source progressive delivery (canary, A/B) operators that integrate with Flux, Argo, and service meshes.

- **[Documentation and GitOps / CD playbooks](https://argo-cd.readthedocs.io/)**  
  Guides for Argo CD, Flux, Spinnaker, and Tekton deployments, app-of-apps patterns, and multi-cluster delivery.

### Additional Strong Open-Source Options
- Adopting **Argo CD** or **Flux** as the default GitOps engine for Kubernetes.
- Using **Spinnaker** when multi-cloud (beyond Kubernetes) delivery pipelines are required.
- Building pipelines with **Tekton** for fully cloud-native, portable CI/CD.
- Layering **Flagger** or similar for canary and progressive delivery.
- Accepting that enterprise governance, SSO, advanced analytics, managed control planes, and some multi-cloud convenience still drive adoption of commercial platforms (Harness, Octopus Deploy, Codefresh, Azure DevOps, Google Cloud Deploy, etc.).
- Focusing open-source efforts on Git as the source of truth, reproducibility, and freedom from vendor lock-in.

**Frameworks for building custom systems**: Store desired state in Git → reconcile with Argo CD or Flux → promote via Tekton or Spinnaker pipelines → add progressive delivery with Flagger → observe with open metrics. Suitable for platform and DevOps teams of any size. Large enterprises often combine open GitOps cores with commercial governance layers.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Continuous delivery systems can change production environments. Test thoroughly, use proper approvals, and maintain rollback capability. This list is not operational advice.

---
**Made for platform engineers, SREs, and open-source GitOps advocates.**
Let's keep delivery continuous, declarative, and as open as practical.
