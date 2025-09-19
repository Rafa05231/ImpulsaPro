# 🚀 Impulsa Pro

**Impulsa Pro** es un software modular desarrollado por **Tecnologías JH**, creado para apoyar a **universidades, empresas, estudiantes y egresados** en la gestión de prácticas, convenios y oportunidades laborales.  

Actualmente, el proyecto está en desarrollo y el primer módulo implementado es el **Gestor de Prácticas Empresariales**.

---

## 📌 Descripción del proyecto

El propósito de **Impulsa Pro** es ser una plataforma flexible y escalable que facilite la conexión entre **instituciones académicas, organizaciones y estudiantes**.  
Cada cliente podrá activar los módulos que necesite según sus requerimientos.

### 🔹 Módulos principales
1. **Gestión de prácticas estudiantiles** (en desarrollo).  
   - Roles: **Estudiante, Coordinador de Prácticas, Administrador/Soporte**.  
   - Funcionalidades: registro de estudiantes, postulaciones a ofertas, favoritos, control de estado de postulaciones, entre otros.  

2. **Gestión de convenios entre universidades y empresas** (planificado).  

3. **Apoyo a egresados en la búsqueda de empleo** (planificado).  

---

## ⚙️ Tecnologías utilizadas

- **Lenguaje principal:** [Python](https://www.python.org/) 🐍  
- **Framework web:** [Django](https://www.djangoproject.com/) 🌐 (patrón **MVT**)  
- **Base de datos:** [MySQL](https://www.mysql.com/) 🗄️  
- **Frontend:** [Bootstrap](https://getbootstrap.com/) 🎨  
- **Control de versiones:** Git + GitHub  

---

## 📂 Estructura del proyecto

```bash
impulsa_pro/
│── env/                  # Entorno virtual (ignorado en Git)
│
├── impulsa_pro/          # Carpeta principal del proyecto
│   ├── accounts/         # App para gestión de usuarios y autenticación
│   ├── core/             # App núcleo: datos maestros compartidos (universidades, empresas, sectores, programas, módulos)
│   ├── impulsa_pro/      # Configuración principal de Django (settings, urls, wsgi, asgi)
│   ├── practicas/        # App del módulo de prácticas empresariales
│   ├── .gitignore        # Archivos y carpetas ignoradas en Git
│   └── manage.py         # Script principal para ejecutar comandos de Django
