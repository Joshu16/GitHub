# 🌐 Proyecto Web: Introducción a Git y GitHub

Este proyecto web moderno y minimalista fue creado con HTML y CSS, con el objetivo de explicar de forma clara y sencilla los conceptos más importantes sobre Git, GitHub y control de versiones.

Ideal para principiantes que desean entender cómo funciona Git y empezar a colaborar en proyectos reales.

---

## 🧠 ¿Qué es Git?

**Git** es un sistema de control de versiones que permite gestionar y registrar los cambios realizados en los archivos de un proyecto. Fue diseñado para trabajar de manera rápida y eficiente incluso con proyectos grandes.

### Características principales:
- Guarda el historial de cambios del proyecto.
- Permite volver a versiones anteriores si ocurre un error.
- Facilita la colaboración entre múltiples desarrolladores.
- Soporta el trabajo con ramas para desarrollar nuevas funciones sin afectar el código principal.

---

## 🐙 ¿Qué es GitHub?

**GitHub** es una plataforma basada en la nube que permite almacenar repositorios de Git en línea. Es una herramienta clave para el trabajo colaborativo en desarrollo de software.

### ¿Para qué sirve?
- Hospedaje de repositorios remotos.
- Colaboración mediante pull requests.
- Seguimiento de errores y mejoras con issues.
- Revisión de código y gestión de ramas.

---

## 📁 ¿Qué es un repositorio?

Un **repositorio** es un espacio de almacenamiento donde se guardan todos los archivos y el historial de cambios de un proyecto. Puede estar en tu computadora (local) o en la nube (remoto).

### Tipos:
- **Repositorio local**: existe en tu equipo, puedes trabajar sin conexión.
- **Repositorio remoto**: alojado en GitHub u otra plataforma, permite compartir tu proyecto.

---

## 🔧 Commits, ramas, push y pull

### ✅ Commit

Un **commit** guarda un cambio en el historial del repositorio. Incluye un mensaje que describe qué se hizo.

```bash
git add .
git commit -m "Agregada sección de commits"
```

### 🌿 Rama (Branch)

Las **ramas** permiten trabajar en nuevas funciones sin modificar el código principal. Ideal para desarrollo paralelo.

```bash
git branch nueva-funcion
git checkout nueva-funcion
```

### 📤 Push

El comando **push** envía tus cambios locales al repositorio remoto.

```bash
git push origin main
```

### 📥 Pull

El comando **pull** descarga y fusiona los cambios del repositorio remoto con tu código local.

```bash
git pull origin main
```

