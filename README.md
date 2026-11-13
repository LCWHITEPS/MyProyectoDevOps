# MyProyectoDevOps

Repositorio académico orientado a la organización de proyectos de software y la aplicación de prácticas básicas de DevOps mediante Git, GitHub y herramientas de automatización.

## 1. Descripción del proyecto

**MyProyectoDevOps** es un proyecto desarrollado con fines académicos para comprender cómo se organiza, documenta y administra un repositorio de software.

Su estructura permite separar los diferentes componentes de un proyecto, mantener organizada la documentación y establecer una base para implementar procesos de integración y despliegue continuo (CI/CD).

## 2. Objetivo

Establecer una estructura organizada y documentada que facilite la administración, el mantenimiento y la colaboración dentro de un proyecto de software, utilizando herramientas de control de versiones y automatización.

## 3. Estructura del proyecto

El repositorio está organizado en diferentes directorios, cada uno destinado a una función específica.

```text
MyProyectoDevOps/
│
├── .github/
│   └── workflows/
│
├── backend/
│
├── database/
│
├── docs/
│
├── frontend/
│
├── images/
│
├── .gitignore
├── LICENSE
└── README.md
```

### Descripción de los directorios

| Directorio o archivo | Descripción |
|---|---|
| `backend/` | Espacio destinado a la lógica y los servicios del servidor. |
| `frontend/` | Contiene los elementos relacionados con la interfaz de usuario. |
| `database/` | Destinado a los scripts y recursos relacionados con la base de datos. |
| `docs/` | Almacena la documentación técnica y organizativa del proyecto. |
| `images/` | Almacena imágenes y recursos gráficos utilizados en el proyecto. |
| `.github/workflows/` | Contiene los archivos YAML para configurar automatizaciones mediante GitHub Actions. |
| `.gitignore` | Define los archivos y directorios que Git debe excluir del seguimiento. |
| `LICENSE` | Establece los permisos y condiciones de uso del proyecto. |
| `README.md` | Documento principal con información general e instrucciones del repositorio. |

## 4. Tecnologías y herramientas

Para la administración y documentación del repositorio se consideran las siguientes herramientas:

- **Git:** Sistema de control de versiones.
- **GitHub:** Plataforma para alojar y administrar el repositorio.
- **GitHub Actions:** Herramienta para configurar flujos de trabajo automatizados.
- **Markdown:** Lenguaje de marcado utilizado para elaborar la documentación.

## 5. Requisitos previos

Para obtener una copia local del repositorio y trabajar con sus archivos se requiere:

- Tener instalado Git.
- Contar con una cuenta de GitHub.
- Disponer de una terminal, como PowerShell, CMD o Git Bash.
- Tener acceso al repositorio.

## 6. Instalación y configuración

Actualmente, el procedimiento permite descargar el repositorio y acceder a su estructura de directorios.

### 6.1. Clonar el repositorio

Abrir una terminal y ejecutar el siguiente comando:

```bash
git clone https://github.com/LCWHITEPS/MyProyectoDevOps.git
```

### 6.2. Acceder al proyecto

Ingresar al directorio descargado:

```bash
cd MyProyectoDevOps
```

### 6.3. Verificar el estado del repositorio

Comprobar que Git reconoce correctamente el repositorio:

```bash
git status
```

### 6.4. Abrir el proyecto

Abrir la carpeta `MyProyectoDevOps` con el editor de código de preferencia para consultar y modificar sus archivos.

> **Nota:** La instalación anterior corresponde a la descarga y configuración inicial del repositorio. La ejecución de aplicaciones o servicios se documentará cuando se incorporen sus respectivas configuraciones y dependencias.

## 7. Documentación del proyecto

Dentro del directorio `docs/` se organizará la documentación técnica para explicar la estructura, configuración y administración del repositorio.

Los siguientes documentos se proponen como parte de la documentación:

| Documento | Contenido |
|---|---|
| `estructura.md` | Explicación de los directorios y archivos principales del proyecto. |
| `instalacion.md` | Requisitos, descarga y configuración inicial del repositorio. |
| `flujo-git.md` | Procedimientos para trabajar con ramas, commits, push y pull. |
| `automatizacion.md` | Descripción de los flujos de trabajo y configuraciones de GitHub Actions. |

Estos documentos complementarán la información general presentada en este README.

## 8. Control de versiones

El proyecto utiliza Git y GitHub para registrar los cambios realizados en sus archivos.

Para guardar y publicar modificaciones se puede utilizar el siguiente procedimiento:

```bash
git add .
git commit -m "Actualizar documentación del proyecto"
git push origin main
```

Este flujo permite mantener actualizada la versión del repositorio y conservar un registro de los cambios realizados.

## 9. Archivos principales

- **README.md:** Presenta la información general, estructura e instrucciones del proyecto.
- **LICENSE:** Define las condiciones de uso y distribución.
- **.gitignore:** Evita que archivos innecesarios o temporales sean agregados al repositorio.
- **GitHub Actions:** Permite establecer procesos automatizados mediante archivos de configuración YAML.

## 10. Estado del proyecto

**Estado actual:** En desarrollo.

El repositorio funciona como una base académica para organizar y documentar los componentes de un proyecto de software. Su estructura podrá ampliarse conforme se incorporen nuevas configuraciones, documentación y procesos de automatización.

## 11. Autor

Proyecto desarrollado con fines académicos para el aprendizaje de Git, GitHub, organización de repositorios y fundamentos de DevOps.

---