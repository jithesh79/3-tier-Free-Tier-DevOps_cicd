✅ How to Run

terraform init && terraform apply -auto-approve → provisions EC2 + networking

Update ansible/inventory.yml with EC2 public IP

ansible-playbook playbooks/site.yml → installs Docker, Jenkins, K3s, apps, monitoring

Access via browser:

Jenkins: 8080

Web: 80

App: 5000

ArgoCD: 8081

SonarQube: 9000

Nexus: 8082
