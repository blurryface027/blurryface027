<div align="center">

<img src="assets/hero.svg" width="100%" alt="deploy-profile.sh terminal animation"/>

</div>

<img src="assets/divider.svg" width="100%" alt=""/>

<!--
  ============================================================
   whoami
  ============================================================
-->

<div align="center">
<img src="assets/terminal.svg" width="100%" alt="whoami terminal"/>
</div>

<img src="assets/divider.svg" width="100%" alt=""/>

<!--
  ============================================================
   neofetch
  ============================================================
-->

<div align="center">
<img src="assets/neofetch.svg" width="100%" alt="neofetch system card"/>
</div>

<img src="assets/divider.svg" width="100%" alt=""/>

<!--
  ============================================================
   DevOps roadmap
  ============================================================
-->

<h3 align="center">DevOps Roadmap</h3>
<p align="center" style="color:#888">GitHub &rarr; Git &rarr; Dockerfile &rarr; Build &rarr; Image &rarr; ECR &rarr; ECS &rarr; Task Definition &rarr; Service &rarr; Load Balancer &rarr; Production</p>

<div align="center">
<img src="assets/deployment.svg" width="440" alt="deployment roadmap flowchart"/>
</div>

<img src="assets/divider.svg" width="100%" alt=""/>

<!--
  ============================================================
   Projects
  ============================================================
-->

<h3 align="center">~/projects</h3>

```

$ tree ~/projects -L 1

~/projects
├── aws-cicd-pipeline      → zero-touch GitHub Actions → ECR → ECS Fargate pipeline
├── gitops-kubernetes      → declarative cluster state, ArgoCD-style reconciliation
└── devsecops-pipeline     → shift-left security scanning baked into the build stage

```

<table align="center">
<tr>
<td width="33%" valign="top">

**[`aws-cicd-pipeline`](https://github.com/krishanmohansharma/aws-cicd-pipeline)**

Push-to-production pipeline: GitHub Actions builds the image, ships it to Amazon ECR, and rolls it out on ECS Fargate behind an ALB with zero manual steps.

`GitHub Actions` `Docker` `ECR` `ECS Fargate`

</td>
<td width="33%" valign="top">

**[`gitops-kubernetes`](https://github.com/krishanmohansharma/gitops-kubernetes)**

Cluster state lives in Git, not in `kubectl` history. Every merge reconciles the live cluster to match the repo automatically.

`Kubernetes` `Helm` `GitOps`

</td>
<td width="33%" valign="top">

**[`devsecops-pipeline`](https://github.com/krishanmohansharma/devsecops-pipeline)**

Security scanning — SAST, dependency audit, image scanning — runs inside the pipeline itself, before anything reaches a registry.

`Trivy` `SAST` `Docker` `CI/CD`

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt=""/>

<!--
  ============================================================
   Docker build → push
  ============================================================
-->

<h3 align="center">docker build &rarr; docker push</h3>

<div align="center">
<img src="assets/docker.svg" width="100%" alt="docker build and push animation"/>
</div>

<img src="assets/divider.svg" width="100%" alt=""/>

<!--
  ============================================================
   AWS architecture
  ============================================================
-->

<h3 align="center">Production Architecture</h3>

<div align="center">
<img src="assets/aws-architecture.svg" width="420" alt="AWS production architecture diagram"/>
</div>

<img src="assets/divider.svg" width="100%" alt=""/>

<!--
  ============================================================
   Cluster status
  ============================================================
-->

<div align="center">
<img src="assets/ecs.svg" width="100%" alt="kubectl and docker ps cluster status"/>
</div>

<img src="assets/divider.svg" width="100%" alt=""/>

<!--
  ============================================================
   Monitoring
  ============================================================
-->

<div align="center">
<img src="assets/monitoring.svg" width="100%" alt="production monitoring dashboard"/>
</div>


<!--
  ============================================================
   GitHub stats — theme locked to black / white / red
  ============================================================
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/krishanmohansharma/krishanmohansharma/output/assets/snake-dark.svg"/>
  <img alt="contribution snake animation" src="https://raw.githubusercontent.com/krishanmohansharma/krishanmohansharma/output/assets/snake.svg" width="100%"/>
</picture>

</div>

<img src="assets/divider.svg" width="100%" alt=""/>

<!--
  ============================================================
   Footer / status
  ============================================================
-->

<div align="center">
<img src="assets/footer.svg" width="100%" alt="systemctl status krishan.service"/>
</div>

<p align="center">
<sub>last deployed <!-- LAST_DEPLOY_START -->`2026-07-22 08:30 UTC`<!-- LAST_DEPLOY_END --> &middot; built with GitHub Actions, Docker and too much coffee</sub>
</p>
