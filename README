
# 🚀 Laboratorio: Automatización de Despliegues con Ansible y GitHub Actions

> **Curso:** Profesionalización en DevOps

![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-Automation-success?style=for-the-badge)

---

# 📖 Descripción

En este laboratorio se implementará un pipeline de **Integración Continua (CI)** utilizando **GitHub Actions** para ejecutar automáticamente un **playbook de Ansible**.

Durante la práctica se configurará un entorno virtual de Python, se instalarán las dependencias del proyecto y se ejecutará un playbook en **modo de simulación (`--check`)**, validando la infraestructura antes de cualquier despliegue real.

---

# 🎯 Objetivos

Al finalizar este laboratorio el estudiante será capaz de:

- ✅ Configurar un entorno de automatización con **Ansible**.
- ✅ Ejecutar playbooks desde **GitHub Actions**.
- ✅ Crear un ambiente virtual de Python para el pipeline.
- ✅ Instalar automáticamente las dependencias del proyecto.
- ✅ Validar un playbook utilizando **Ansible Check Mode**.
- ✅ Interpretar los resultados obtenidos durante la ejecución del workflow.

---

# 🏗️ Arquitectura del laboratorio

```mermaid
flowchart LR

A["💻 Código Fuente"]

--> B["📤 Git Push"]

--> C["⚙️ GitHub Actions"]

--> D["🐍 Entorno Virtual Python"]

--> E["📦 pip install -r requirements.txt"]

--> F["🤖 Ansible Playbook (--check)"]

--> G["✅ Validación del Despliegue"]
```

---

# 📂 Estructura del proyecto

```text
.
├── .github
│   └── workflows
│       └── ansible.yml
├── ansible.cfg
├── inventory
│   └── hosts.ini
├── playbooks
│   ├── webserver.yml
│   └── uninstall_webserver.yml
├── files
│   └── index.html
└── requirements.txt
```

---

# ⚙️ Flujo de ejecución

El workflow realiza automáticamente las siguientes actividades:

1. 📥 Descarga el repositorio.
2. 🐍 Configura Python.
3. 📦 Crea un entorno virtual.
4. 📚 Instala las dependencias definidas en `requirements.txt`.
5. 🤖 Ejecuta el playbook mediante **Ansible**.
6. 📋 Muestra el resultado de la validación.

---

# 🔧 Tecnologías utilizadas

- 🤖 Ansible
- ⚙️ GitHub Actions
- 🐍 Python
- 🐧 Ubuntu
- 🐙 GitHub

---

# 📚 Conceptos aplicados

Durante este laboratorio se ponen en práctica los siguientes conceptos de DevOps:

- Infraestructura como Código (IaC).
- Automatización de tareas.
- Integración Continua (CI).
- Entornos virtuales de Python.
- Playbooks de Ansible.
- Validación automática de infraestructura.

---

# 🔄 Flujo CI

```mermaid
sequenceDiagram

participant D as 👨‍💻 Desarrollador
participant G as GitHub
participant A as GitHub Actions
participant P as Python
participant AN as Ansible

D->>G: Push al repositorio

G->>A: Ejecutar Workflow

A->>P: Crear entorno virtual

P-->>A: Instalar dependencias

A->>AN: Ejecutar playbook (--check)

AN-->>A: Resultado de validación

A-->>G: Success / Failure
```

---

# 🎓 Competencias desarrolladas

Al completar esta práctica el estudiante fortalecerá habilidades relacionadas con:

- 🚀 Automatización de despliegues.
- 📦 Gestión de dependencias.
- ⚙️ Ejecución de pipelines CI.
- 🤖 Uso profesional de Ansible.
- 🔍 Validación de infraestructura antes del despliegue.
- 📋 Interpretación de resultados de GitHub Actions.

---

# 📌 Resultado esperado

Al finalizar correctamente el laboratorio:

- ✅ El entorno virtual de Python será creado automáticamente.
- ✅ Las dependencias del proyecto serán instaladas.
- ✅ El playbook de Ansible se ejecutará correctamente.
- ✅ GitHub Actions mostrará el estado **Success**.
- ✅ El pipeline validará la infraestructura sin realizar cambios gracias al modo **Check**.

---

# 💡 Buenas prácticas implementadas

- 🔒 Uso de un entorno virtual independiente.
- 📦 Instalación automática de dependencias.
- 📁 Separación entre inventario, playbooks y archivos estáticos.
- 🧪 Validación previa mediante `ansible-playbook --check`.
- ⚙️ Automatización completa del proceso mediante GitHub Actions.

---

# 📈 Flujo general del laboratorio

```mermaid
flowchart TD

A["📂 Repositorio GitHub"]

--> B["⚙️ GitHub Actions"]

--> C["🐍 Configurar Python"]

--> D["📦 Crear Virtual Environment"]

--> E["📥 Instalar Requirements"]

--> F["🤖 Ejecutar Ansible"]

--> G["🧪 Check Mode"]

--> H["📋 Resultado del Pipeline"]

--> I["✅ Success / ❌ Failure"]
```

---

> **🎯 Objetivo del laboratorio:** comprender cómo integrar **Ansible** dentro de un pipeline de **GitHub Actions**, automatizando la validación de infraestructura como código (IaC) mediante un proceso reproducible, seguro y alineado con las buenas prácticas de DevOps.
