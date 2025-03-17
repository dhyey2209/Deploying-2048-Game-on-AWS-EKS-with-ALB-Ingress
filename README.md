# Deploying-2048-Game-on-AWS-EKS-with-ALB-Ingress

For a complete breakdown of the project, including the challenges of traditional Kubernetes deployment and how AWS EKS with ALB Ingress addresses these issues, visit my [Hashnode blog](https://dhyey-devops.hashnode.dev/deploying-the-classic-2048-game-on-aws-eks-with-alb-ingress)


## Kubernetes Manifests

📂 **deployment-manifests/**

- `deployment.yaml` → Defines the **2048 Game Deployment**
- `service.yaml` → Exposes the application within the cluster
- `ingress.yaml` → Configures **AWS ALB Ingress** for public access
- `namespace.yaml` → Creates the **game-2048 namespace** for resource isolation


