# DespAppWeb
# Práctica de Uso de Git y GitHub

Esta práctica te guiará a través de los pasos básicos para trabajar con repositorios en GitHub utilizando Git. Aprenderás a crear un repositorio, clonar el repositorio localmente, modificar archivos, y subir cambios al repositorio remoto utilizando un token de acceso personal.

## Contenido

1. [Prerrequisitos](#prerrequisitos)
2. [Pasos a Seguir](#pasos-a-seguir)
   - [1. Crear un Repositorio en GitHub](#1-crear-un-repositorio-en-github)
   - [2. Crear un Token de Acceso Personal](#2-crear-un-token-de-acceso-personal)
   - [3. Clonar el Repositorio a Local](#3-clonar-el-repositorio-a-local)
   - [4. Modificar el README](#4-modificar-el-readme)
   - [5. Hacer un Commit](#5-hacer-un-commit)
   - [6. Hacer un Push](#6-hacer-un-push)
3. [Notas Adicionales](#notas-adicionales)

## Prerrequisitos

- **Cuenta en GitHub:** Asegúrate de tener una cuenta activa en [GitHub](https://github.com/).
- **Git Instalado:** Debes tener Git instalado en tu máquina local. Puedes descargarlo desde [aquí](https://git-scm.com/downloads).

## Pasos a Seguir

### 1. Crear un Repositorio en GitHub

1. Inicia sesión en tu cuenta de GitHub.
2. Haz clic en el botón **"New"** o **"Nuevo"** para crear un nuevo repositorio.
3. Completa los detalles del repositorio:
   - **Nombre del Repositorio:** Elige un nombre descriptivo.
   - **Descripción:** (Opcional) Agrega una breve descripción.
   - **Visibilidad:** Público o Privado.
4. **Inicializar con un README:** Puedes seleccionar esta opción para que se cree automáticamente un archivo `README.md`.
5. Haz clic en **"Create repository"**.

### 2. Crear un Token de Acceso Personal

1. En GitHub, ve a **Settings** (Configuración) haciendo clic en tu avatar en la esquina superior derecha.
2. Navega a **Developer settings** > **Personal access tokens**.
3. Haz clic en **"Generate new token"**.
4. Asigna una **nota** descriptiva al token.
5. Selecciona los **alcances (scopes)** necesarios, generalmente:
   - `repo` para acceso completo a los repositorios privados y públicos.
6. Haz clic en **"Generate token"**.
7. **Importante:** Copia y guarda el token en un lugar seguro. No podrás verlo nuevamente.

### 3. Clonar el Repositorio a Local

Abre tu terminal o línea de comandos y ejecuta:

```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
