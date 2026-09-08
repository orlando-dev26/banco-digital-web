# 🌐 Banco Digital - Frontend Web (Angular)

Este repositorio contiene la aplicación **Frontend Web (Portal Bancario)** de nuestro proyecto de Banco Digital. Está desarrollado utilizando el framework **Angular** y preprocesador de estilos **SCSS**.

Esta aplicación web funciona en conjunto con una arquitectura completa de microservicios y clientes móviles.

---

## 🏗️ Estructura Global del Proyecto (Arquitectura)

Actualmente, nuestro ecosistema bancario está dividido en múltiples tecnologías para asegurar escalabilidad. La arquitectura conceptual de los repositorios es la siguiente:

`	ext
ProyectoIntegrador2Banca/
│
├── Fronted/
│   └── banca-web/                 <-- 📍 ESTÁS AQUÍ (Frontend Web - Angular)
│
├── DigitalBankApp/
│   ├── app/                       <-- (Frontend Móvil - Kotlin/Android Nativo)
│   └── backend/
│       ├── kyc/                   <-- (Microservicio IA Biométrica - Python/FastAPI)
│       └── app-banco-backend/     <-- (Microservicios Core Bancario - Java/Spring Boot)
│           ├── user-microservice/
│           ├── discovery-service/
│           └── api-gateway/
`

### 🧩 Tecnologías Principales del Ecosistema:
*   **Cliente Web:** Angular, SCSS.
*   **Cliente Móvil:** Android Nativo (Kotlin, Jetpack Compose).
*   **Core Bancario (Microservicios):** Java (Spring Boot), PostgreSQL, Docker.
*   **Seguridad / Inteligencia Artificial:** Python (FastAPI), OpenCV, MediaPipe, EasyOCR.

---

## 🚀 Guía de Desarrollo Rápido (Angular)

### Prerrequisitos
Asegúrate de tener instalado:
*   [Node.js](https://nodejs.org/) (LTS)
*   Angular CLI: 
pm install -g @angular/cli

### Ejecución Local
1. Abre una terminal en la raíz de este proyecto.
2. Instala las dependencias: 
pm install
3. Levanta el servidor: 
g serve -o
   *(Se abrirá automáticamente en http://localhost:4200)*
