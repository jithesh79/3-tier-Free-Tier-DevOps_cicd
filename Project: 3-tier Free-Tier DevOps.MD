3tier-devops-free-tier/
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
│   └── provider.tf
├── ansible/
│   ├── inventory.yml
│   ├── playbooks/
│   │   └── site.yml
│   └── roles/
│       ├── common/
│       │   └── tasks/main.yml
│       ├── docker/
│       │   └── tasks/main.yml
│       ├── jenkins/
│       │   └── tasks/main.yml
│       ├── k3s/
│       │   └── tasks/main.yml
│       ├── web/
│       │   └── tasks/main.yml
│       ├── app/
│       │   └── tasks/main.yml
│       ├── db/
│       │   └── tasks/main.yml
│       ├── sonarqube/
│       │   └── tasks/main.yml
│       ├── nexus/
│       │   └── tasks/main.yml
│       └── argocd/
│           └── tasks/main.yml
├── web/
│   └── index.html
├── app/
│   ├── app.py
│   └── requirements.txt
├── db/
│   └── database.db
├── k8s/
│   ├── app-deployment.yml
│   └── web-deployment.yml
└── Jenkinsfile
