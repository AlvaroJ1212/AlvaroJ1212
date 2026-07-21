<div align="center">

# Hola, soy Álvaro 👋
### Software Developer | Cloud Infrastructure & DevOps

Desarrollador de software con un fuerte interés en la automatización de infraestructura en la nube, la cultura DevOps y las metodologías GitOps. Combino el desarrollo de software tradicional con herramientas de Infraestructura como Código (IaC) y automatización para construir entornos reproducibles, escalables y fáciles de mantener.

</div>

---

## Stack Tecnológico y Herramientas

Trabajo con tecnologías que abarcan desde la provisión de infraestructura hasta el desarrollo de aplicaciones y la integración continua:

** Infraestructura & Cloud:**
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-326CE5.svg?&style=for-the-badge&logo=kubernetes&logoColor=white)

** Desarrollo & Bases de Datos:**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white)

** CI/CD & Version Control:**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-330F63?style=for-the-badge&logo=gitlab&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Infraestructura Cloud e IaC

Mi aproximación a la infraestructura se basa en los principios de automatización, reproducibilidad y gestión declarativa. Siempre que es posible, la infraestructura se define mediante código y queda versionada junto al resto del proyecto.

### 1. Arquitectura GCP Desacoplada (Blueprint/Component Pattern)

He desarrollado una infraestructura modular sobre Google Cloud Platform utilizando Terraform. El entorno se organiza mediante módulos versionados y reutilizables para servicios como redes VPC, almacenamiento, IAM, Pub/Sub y monitorización, favoreciendo la separación de responsabilidades y la mantenibilidad del código.

### 2. Gestión de Estado y Separación de Entornos

Aplico una separación clara entre entornos de Desarrollo y Producción. Para ello utilizo backends remotos en Google Cloud Storage para la gestión del `terraform.tfstate`, garantizando la consistencia del estado y facilitando la evolución segura de la infraestructura.

### 3. Automatización de Pipelines (CI/CD)

He trabajado con flujos de integración y despliegue continuo tanto en **GitHub Actions** como en **GitLab CI/CD**, automatizando tareas habituales del ciclo de vida de la infraestructura.

* **Validación Continua:** Ejecución automatizada de `terraform fmt` y `terraform validate` sobre cada cambio.
* **Seguridad (Shift-Left):** Integración de análisis estático sobre el código de infraestructura.
* **Despliegues Controlados:** Automatización de `terraform plan` y despliegues condicionados según el entorno de destino.

---

<div align="center">
  <i>Te invito a explorar los repositorios fijados a continuación para conocer la estructura de los proyectos, la organización de la infraestructura y la configuración de los pipelines.</i>
</div>
