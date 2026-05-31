<div align="center">

# Hola, soy Álvaro 👋
### Junior Software Developer | Cloud Infrastructure & DevOps

Desarrollador de software con un enfoque especializado en la automatización de infraestructura en la nube, cultura DevOps y metodologías GitOps. Combino el desarrollo de software tradicional con la orquestación de sistemas complejos para construir entornos resilientes, seguros y orientados a eventos.

</div>

---

## 🛠️ Stack Tecnológico y Herramientas

He consolidado un ecosistema de herramientas que abarca desde la provisión de infraestructura hasta el desarrollo de aplicaciones y la integración continua:

**☁️ Infraestructura & Cloud:**
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-326CE5.svg?&style=for-the-badge&logo=kubernetes&logoColor=white)

**💻 Desarrollo & Bases de Datos:**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white)

**⚙️ CI/CD & Version Control:**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-330F63?style=for-the-badge&logo=gitlab&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🏗️ Filosofía de Arquitectura e IaC

Mi aproximación a la infraestructura se basa en los principios de inmutabilidad y mínimo privilegio. No despliego servidores manualmente; los programo.

### 1. Arquitectura GCP Desacoplada (Blueprint/Component Pattern)
He diseñado y mantengo una infraestructura base en Google Cloud Platform completamente modular. Utilizando Terraform, orquesto un entorno que invoca módulos externos versionados semánticamente (APIs, Redes VPC, Storage, Pub/Sub, IAM y Monitorización). Esto garantiza la separación estricta de responsabilidades y facilita la escalabilidad.

### 2. Gestión de Estado y Aislamiento de Entornos
Implemento una separación rigurosa entre los entornos de Desarrollo y Producción. Utilizo backends remotos en Google Cloud Storage para la gestión del `terraform.tfstate`, asegurando el bloqueo de estado para equipos concurrentes y previniendo la corrupción de datos durante los despliegues.

### 3. Automatización de Pipelines (CI/CD)
Tengo experiencia configurando y gestionando flujos de integración y despliegue continuo robustos, adaptables tanto a ecosistemas de **GitHub Actions** (mediante *reusable workflows*) como a los pipelines de **GitLab CI/CD**. 
* **Validación Continua:** Ejecución automatizada de `terraform fmt` y `terraform validate` en cada Pull Request o Merge Request.
* **Seguridad (Shift-Left):** Integración de análisis estático de seguridad en el código de infraestructura antes del despliegue.
* **Despliegues Controlados:** Automatización de `terraform plan` con revisión obligatoria y `terraform apply` condicionado por el entorno de destino.

---

<div align="center">
  <i>Te invito a explorar los repositorios fijados a continuación para auditar el código fuente, la estructura de mis módulos de Terraform y la configuración de mis pipelines.</i>
</div>
