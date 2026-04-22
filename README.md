# Azure Secure Microservices Architecture 🚀

This project demonstrates a production-grade Azure architecture focusing on:

- Fault Tolerance
- Cost Optimization
- Security Best Practices

## 🧱 Architecture

- Azure Kubernetes Service (AKS)
- Azure Front Door
- Application Gateway (WAF)
- Azure SQL + Cosmos DB
- Azure Cache for Redis
- Azure Key Vault
- Azure Monitor & Application Insights

## ⚙️ Features

- Auto-scaling microservices (AKS)
- Multi-region failover (Front Door)
- Secure secrets management (Key Vault)
- CI/CD pipeline using GitHub Actions
- Infrastructure as Code (Terraform)

## 🔐 Security

- Managed Identity (no hardcoded secrets)
- Private Endpoints
- Network Security Groups
- HTTPS enforced

## 💰 Cost Optimization

- Auto-scaling to reduce idle cost
- Spot instances for AKS
- Storage tiering
- Azure Cost Monitoring

## 🚀 Deployment Steps

1. Clone repo
2. Configure Terraform variables
3. Run:
   ```
   terraform init
   terraform apply
   ```
4. Deploy app to AKS:
   ```
   kubectl apply -f k8s/
   ```

## 📊 Monitoring

- Azure Monitor
- Log Analytics
- Application Insights

---

## 👩‍💻 Author
Swati Panwar
