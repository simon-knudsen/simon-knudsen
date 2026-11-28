# Simon Knudsen — Cloud / DevOps Engineer

I work with Terraform, Ansible, and Kubernetes on AWS. Three projects below.
Each one is a repo you can open, with notes on the choices I made.

📍 Copenhagen · AWS Certified — <Cloud Practitioner / Solutions Architect – Associate>

**Contact:** [GitHub](https://github.com/simonknudsen) · [LinkedIn](https://linkedin.com/in/simonknudsen) · [simon.knudsen@example.com](mailto:simon.knudsen@example.com)

---

## Projects

### [AWS Infrastructure with Terraform →](./terraform-aws-infrastructure/README.md)

**Problem:** setting up dev and staging by hand meant they never quite matched.

**Technologies used:** `Terraform` · `AWS` · `VPC` · `IAM` · `S3`

Reusable modules so dev and staging come from the same code instead of being
set up by hand, so they end up the same every time. The one difference I left in
on purpose: staging runs a NAT gateway and dev doesn't, since there's no point
paying for traffic dev never sends.

### [Server Configuration with Ansible →](./ansible-config-automation/README.md)

**Problem:** every new server was set up by hand, so no two ended up configured the same.

**Technologies used:** `Ansible` · `Linux` · `Docker` · `Nginx`

Roles that take a fresh Ubuntu machine and set it up with Docker and sensible
login security, the same way every time. The SSH settings live in their own file
so it's easy to see what's being changed, and passwords and keys go in
ansible-vault for security purposes.

### [Kubernetes on EKS with Helm →](./kubernetes-eks-platform/README.md)

**Problem:** shipping the same app to dev and staging meant hand-editing manifests each time.

**Technologies used:** `Kubernetes` · `Helm` · `AWS EKS` · `Docker`

One Helm chart that deploys the app to both dev and staging — to switch
environments I just change a config file instead of rewriting everything by
hand. Each environment gets its own space on the cluster with resource limits
and an ingress for traffic. Every container is given a set amount of CPU and
memory so one app can't take it all, and image versions are pinned instead of
using `latest`, so what you deploy is what you tested.

---

## Skills

- **Cloud:** AWS (VPC, IAM, EC2, S3, EKS)
- **IaC:** Terraform, Ansible
- **Containers:** Docker, Kubernetes, Helm
- **Monitoring:** Prometheus, Grafana
- **CI & scripting:** Git, Jenkins, Python, Bash



-------




# 👋 Hi, I'm Simon!
👩🏻‍💻 Cloud DevOps Engineer sharing about my journey and learnings in tech<br/>
👩🏻‍🎓 Studied DevOps through Bootcamp and AWS/Azure Certifications<br/>
💭 Currently learning about Ansible and Prometheus!<br/>

# 💻 Tech Stack
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=for-the-badge&logo=Prometheus&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)
![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![Maven](https://img.shields.io/badge/apachemaven-%23C71A36.svg?style=for-the-badge&logo=apachemaven&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-%236DA55F.svg?style=for-the-badge&logo=node.js&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)

# 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api?username=simon-knudsen&theme=radical&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://github-profile-trophy.vercel.app/?username=simon-knudsen&theme=radical&no-frame=false&no-bg=true&margin-w=4)
