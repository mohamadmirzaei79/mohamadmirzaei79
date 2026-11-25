<p align="center"><img src="./profile-banner.png" alt="Mohamad Mirzaei · Python Backend Developer and DevOps Engineer"></p>

## About me

Hi, I’m Mohamad 👋 I’m a Python backend developer in Isfahan, Iran. At Sobhan Tech, I build and test FastAPI services and deploy them to Kubernetes. I started in DevOps, and I still enjoy figuring out how a service behaves once it’s running.

I’m open to remote roles and freelance projects. [Connect on LinkedIn](https://www.linkedin.com/in/mohammad-mirzaei-3802b724a).

## Tech stack

| Area | Tools |
| --- | --- |
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-007F73?style=flat&logo=fastapi&logoColor=white) ![Chainlit](https://img.shields.io/badge/Chainlit-435269?style=flat&logo=chainlit&logoColor=white) |
| **Delivery** | ![Docker](https://img.shields.io/badge/Docker-186BB0?style=flat&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-345BC5?style=flat&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-263381?style=flat&logo=helm&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo%20CD-B34C30?style=flat&logo=argo&logoColor=white) ![GitLab CI/CD](https://img.shields.io/badge/GitLab%20CI%2FCD-993E1E?style=flat&logo=gitlab&logoColor=white) |
| **Monitoring** | ![Prometheus](https://img.shields.io/badge/Prometheus-AD402A?style=flat&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-92501C?style=flat&logo=grafana&logoColor=white) |

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [RelayDesk](https://github.com/mohamadmirzaei79/RelayDesk)

**Incident response & shift handoff**

[![RelayDesk incident queue and timeline](https://raw.githubusercontent.com/mohamadmirzaei79/RelayDesk/main/preview.png)](https://mohamadmirzaei79.github.io/RelayDesk/)

Open **INC-1042**, record a mitigation, and see the next shift’s briefing update. The demo keeps edits in your browser.

In the connected edition, a Node.js gateway talks to FastAPI. PostgreSQL stores each decision with its timeline entry, and a version check prevents one operator from overwriting another’s update.

[Try the incident desk ↗](https://mohamadmirzaei79.github.io/RelayDesk/) · [API](https://github.com/mohamadmirzaei79/RelayDesk/blob/main/api.py) · [Integration test](https://github.com/mohamadmirzaei79/RelayDesk/blob/main/test_gateway.mjs)

</td>
<td width="50%" valign="top">

### [ReleaseScope](https://github.com/mohamadmirzaei79/ReleaseScope)

**Deployment performance analysis**

[![ReleaseScope checkout latency before and after deployment](https://raw.githubusercontent.com/mohamadmirzaei79/ReleaseScope/main/dashboard.png)](https://mohamadmirzaei79.github.io/ReleaseScope/)

Compare checkout traffic across a deployment. In the sample release, p95 latency rises from **225 to 374 ms**. Switch to the error chart to see what else changed.

The FastAPI endpoint accepts custom request timings and HTTP status codes. It uses the same Python analysis functions as the public demo, so every flagged release has an inspectable reason.

[Explore a release ↗](https://mohamadmirzaei79.github.io/ReleaseScope/) · [Analysis code](https://github.com/mohamadmirzaei79/ReleaseScope/blob/main/analysis_core.py) · [Tests](https://github.com/mohamadmirzaei79/ReleaseScope/blob/main/test_analysis.py)

</td>
</tr>
</table>

## Engineering experience

**Sobhan Tech · Python Backend Developer**  
November 2024 – present

- I build APIs with FastAPI and conversational interfaces with Chainlit. My tests cover individual functions, interactions between components, and end-to-end user flows.
- I maintain CI/CD pipelines and Docker image repositories. I package applications with Helm and deploy them to Kubernetes with Argo CD.

**Mohaymen ICT · DevOps Engineer**  
June 2022 – October 2024

- I containerized applications with Docker, helped migrate them to Linux, and managed Kubernetes deployments with Argo CD.
- I introduced infrastructure as code and GitOps practices with GitLab. I used Prometheus metrics and Grafana dashboards to track how services behaved after deployment.

## Let’s connect

If your team needs someone who can build a Python service, test it, and own its path to Kubernetes, [reach me on LinkedIn](https://www.linkedin.com/in/mohammad-mirzaei-3802b724a).

<sub>Electrical engineering graduate of Isfahan University of Technology · Third place in junior robot soccer, Iran Open RoboCup 2018.</sub>
