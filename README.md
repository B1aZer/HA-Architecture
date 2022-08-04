# HA-Architecture

![image](https://github.com/B1aZer/HA-Architecture/blob/main/Untitled%20Diagram.drawio(10).png?raw=true)

Highly Available Architecture Diagram for k8s:

1. HA k8s with multiple CP nodes and worker nodes in different AZ and horizontal and vertical autoscaling for pods
2. HA Vault for secrets with web UI and API for devs
3. Service mesh (Consul/Istio) for tls connections/backend routes
4. Artifactory for repo management and security checks
5. Agrocd for deployment on k8s
6. GitHub actions for CI
7. NGINX Ingress network LB
8. Route 53 for DNS management
9. Distributed caching (Redis)
10. Master-slave RDS
11. Distributed NoSQL (Dynamo DB/Etcd)
12. Distributed ElasticSearch analytics
