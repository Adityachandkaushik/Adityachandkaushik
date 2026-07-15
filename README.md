<div align="center">

![Banner](https://capsule-render.vercel.app/api?type=waving&color=0:0B0F19,100:1F2937&height=180&section=header&text=Aditya%20Kaushik&fontSize=42&fontColor=00D9FF&animation=fadeIn&fontAlignY=40&desc=DevOps%20Engineer%20%7C%20AWS%20%7C%20CI%2FCD%20%7C%20Docker&descAlignY=62&descSize=16&descColor=9CA3AF)

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3000&pause=1200&color=00D9FF&center=true&vCenter=true&width=600&lines=Building+CI%2FCD+pipelines+with+Jenkins;Deploying+applications+on+AWS+EC2;Learning+Terraform+%26+Kubernetes" alt="Typing SVG" />

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B0F19?style=for-the-badge&logo=linkedin&logoColor=00D9FF)](https://www.linkedin.com/in/aditya-kaushik-11b39b276/)
[![GitHub](https://img.shields.io/badge/GitHub-0B0F19?style=for-the-badge&logo=github&logoColor=FF9900)](https://github.com/Adityachandkaushik)
![Profile Views](https://komarev.com/ghpvc/?username=Adityachandkaushik&style=for-the-badge&color=0B0F19&label=PROFILE+VIEWS)

</div>

<br/>

## About Me

I'm a **DevOps Engineer** at **MetConnect Infotech Pvt Ltd**, based in Patna, Bihar, India.

I work on building CI/CD pipelines, containerizing applications with Docker, and deploying them on AWS. Most of my day-to-day involves Jenkins, EC2, and getting code from a commit to a running deployment reliably.

I learn best by building things, not just reading about them — every tool on this profile is something I've actually used in a project, not just read a blog post about.

- 🔧 Working with **Docker, Jenkins, AWS EC2, Aurora RDS, Nginx**
- 🔍 Adding **SonarQube** and **Trivy** into my pipelines for code quality and security scanning
- 📚 Currently learning **Terraform** and **Kubernetes** — not production-ready yet, actively building with them
- 📝 I document what I learn on LinkedIn

<br/>

## Tech Stack

**Currently using in projects:**

![AWS](https://img.shields.io/badge/AWS-0B0F19?style=flat-square&logo=amazonaws&logoColor=FF9900)
![EC2](https://img.shields.io/badge/EC2-0B0F19?style=flat-square&logo=amazonec2&logoColor=FF9900)
![IAM](https://img.shields.io/badge/IAM-0B0F19?style=flat-square&logo=amazoniam&logoColor=FF9900)
![VPC](https://img.shields.io/badge/VPC-0B0F19?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Route53](https://img.shields.io/badge/Route53-0B0F19?style=flat-square&logo=amazonroute53&logoColor=FF9900)
![CloudWatch](https://img.shields.io/badge/CloudWatch-0B0F19?style=flat-square&logo=amazoncloudwatch&logoColor=FF9900)
![S3](https://img.shields.io/badge/S3-0B0F19?style=flat-square&logo=amazons3&logoColor=FF9900)
![Aurora RDS](https://img.shields.io/badge/Aurora_RDS-0B0F19?style=flat-square&logo=amazonrds&logoColor=FF9900)
![WAF](https://img.shields.io/badge/AWS_WAF-0B0F19?style=flat-square&logo=amazonaws&logoColor=FF9900)

![Docker](https://img.shields.io/badge/Docker-0B0F19?style=flat-square&logo=docker&logoColor=00D9FF)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-0B0F19?style=flat-square&logo=docker&logoColor=00D9FF)
![Jenkins](https://img.shields.io/badge/Jenkins-0B0F19?style=flat-square&logo=jenkins&logoColor=00D9FF)
![SonarQube](https://img.shields.io/badge/SonarQube-0B0F19?style=flat-square&logo=sonarqube&logoColor=00D9FF)
![Trivy](https://img.shields.io/badge/Trivy-0B0F19?style=flat-square&logo=aquasecurity&logoColor=00D9FF)
![Git](https://img.shields.io/badge/Git-0B0F19?style=flat-square&logo=git&logoColor=00D9FF)
![GitHub](https://img.shields.io/badge/GitHub-0B0F19?style=flat-square&logo=github&logoColor=00D9FF)
![Linux](https://img.shields.io/badge/Linux-0B0F19?style=flat-square&logo=linux&logoColor=00D9FF)
![Bash](https://img.shields.io/badge/Bash-0B0F19?style=flat-square&logo=gnubash&logoColor=00D9FF)
![Nginx](https://img.shields.io/badge/Nginx-0B0F19?style=flat-square&logo=nginx&logoColor=00D9FF)

**Currently learning (not production experience yet):**

![Terraform](https://img.shields.io/badge/Terraform-0B0F19?style=flat-square&logo=terraform&logoColor=7B61FF)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0B0F19?style=flat-square&logo=kubernetes&logoColor=7B61FF)
![Helm](https://img.shields.io/badge/Helm-0B0F19?style=flat-square&logo=helm&logoColor=7B61FF)
![ArgoCD](https://img.shields.io/badge/ArgoCD-0B0F19?style=flat-square&logo=argo&logoColor=7B61FF)
![Prometheus](https://img.shields.io/badge/Prometheus-0B0F19?style=flat-square&logo=prometheus&logoColor=7B61FF)
![Grafana](https://img.shields.io/badge/Grafana-0B0F19?style=flat-square&logo=grafana&logoColor=7B61FF)
![Ansible](https://img.shields.io/badge/Ansible-0B0F19?style=flat-square&logo=ansible&logoColor=7B61FF)
![AWS ECS](https://img.shields.io/badge/AWS_ECS-0B0F19?style=flat-square&logo=amazonecs&logoColor=7B61FF)
![AWS EKS](https://img.shields.io/badge/AWS_EKS-0B0F19?style=flat-square&logo=amazoneks&logoColor=7B61FF)

<br/>

## CI/CD Pipeline (what I actually build)

```
GitHub Push → Jenkins Trigger → Checkout → Build → Test
              → SonarQube (code quality) → Trivy (security scan)
              → Docker Build → Docker Push → Deploy to EC2
```

This is the pipeline structure I use in my Jenkins projects — checkout, build, quality/security scanning, then containerized deployment.

<br/>

## Projects

**GoPass Backend**
Backend service built with Node.js, Express, and MongoDB, deployed on AWS EC2 with Aurora RDS. AWS WAF configured in front of it for basic protection.

**Docker Production Setup**
Multi-container MERN application using Docker Compose — separate frontend, backend, and database containers with custom networking and persistent volumes.

**Jenkins Pipeline**
A CI/CD pipeline that checks out code from GitHub, builds and tests it, runs it through SonarQube and Trivy, then builds and pushes a Docker image.

**Jenkins Shared Library**
Reusable Groovy pipeline functions so I don't repeat the same Jenkins stages across projects.

**Docker + Jenkins Deployment**
End-to-end setup connecting the Jenkins pipeline above to an actual Docker deployment step.

[**See all repositories →**](https://github.com/Adityachandkaushik?tab=repositories)

<br/>

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Adityachandkaushik&show_icons=true&hide_border=true&count_private=true&bg_color=0B0F19&title_color=00D9FF&icon_color=FF9900&text_color=9CA3AF&border_color=1F2937" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Adityachandkaushik&layout=compact&hide_border=true&bg_color=0B0F19&title_color=00D9FF&text_color=9CA3AF&border_color=1F2937" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Adityachandkaushik&hide_border=true&background=0B0F19&stroke=1F2937&ring=00D9FF&fire=FF9900&currStreakNum=F3F4F6&sideNums=F3F4F6&currStreakLabel=00D9FF&sideLabels=9CA3AF&dates=9CA3AF" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Adityachandkaushik&bg_color=0B0F19&color=00D9FF&line=FF9900&point=F3F4F6&area=true&area_color=00D9FF&hide_border=true" width="97%"/>

</div>

<br/>

## Career Objective

I want to grow into a well-rounded Cloud & DevOps Engineer. Right now that means going deeper into **Terraform** for infrastructure as code and **Kubernetes** for container orchestration — both are things I'm actively learning through projects, not tools I'm claiming production experience with yet.

<br/>

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B0F19?style=for-the-badge&logo=linkedin&logoColor=00D9FF)](https://www.linkedin.com/in/aditya-kaushik-11b39b276/)
[![GitHub](https://img.shields.io/badge/GitHub-0B0F19?style=for-the-badge&logo=github&logoColor=FF9900)](https://github.com/Adityachandkaushik)

</div>

<br/>

<div align="center">
<sub>Aditya Kaushik · DevOps Engineer · Patna, India</sub>
</div>
