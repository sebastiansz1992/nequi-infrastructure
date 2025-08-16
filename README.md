# 🚀 Terraform AWS Infrastructure

Este repositorio contiene la infraestructura en **AWS** desplegada con **Terraform**, incluyendo:

- **Amazon VPC** con subnets públicas y privadas.  
- **Security Groups** con acceso público controlado.  
- **Amazon ECS (Fargate)** para ejecutar contenedores serverless.  
- **Amazon ECR** como registro de imágenes de Docker.  
- **Application Load Balancer (ALB)** para balanceo de carga.  
- **Amazon RDS (MySQL Free Tier)** como base de datos relacional.  

---

## 📋 Requisitos

Antes de comenzar asegúrate de tener instalado:

- [Terraform](https://developer.hashicorp.com/terraform/downloads) `>= 1.5`
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- Una cuenta de **AWS** con credenciales configuradas (`aws configure`).
- **Docker** (para construir y subir imágenes a ECR).

---

## ⚙️ Configuración

1. **Clonar el repositorio**

```bash
git clone https://github.com/tu-usuario/terraform-aws-infra.git
cd terraform-aws-infra
