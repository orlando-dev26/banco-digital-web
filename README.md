# Banco Digital - Panel de Administración Web (Frontend)

Este repositorio contiene el prototipo del **Panel de Administración Web** para nuestro proyecto de Banco Digital. Está diseñado exclusivamente para el uso del personal interno del banco (administradores y auditores).

## �h Tecnologías y Versiones
- **Framework:** Angular >= v22.0.0
- **Lenguaje:** TypeScript
- **Estilos:** SCSS (Sass)
- **Entorno:** Node.js (LTS)

## 📍 Historias de Usuario Implementadas (EP10)
Este prototipo cubre las siguientes historias de usuario requeridas para la gestión de la plataforma:
- **ADM-01 (Login):** Inicio de sesión exclusivo para rol de administrador.
- **ADM-02 (Usuarios):** Listado y búsqueda de cuentas registradas.
- **ADM-03 (Transacciones):** Detalle y auditoría de transferencias.
- **ADM-04 (Fraude):** Visualización de alertas de seguridad y bloqueo de cuentas.
- **ADM-05 (Monitoreo):** Panel de estado de salud (Healthchecks) de los microservicios.

## �	Estructura de Carpetas (Arquitectura Angular)

```text
banca-web/
|-- src/
|   |-- app/
|   |   |-- core/       <-- (Servicios centrales, Guards de autenticación)
|   |   |-- shared/     <-- (Componentes UI reutilizables, Navbar, Sidebar)
|   |   |-- features/   <-- (Módulos principales por funcionalidad)
|   |   |   |-- auth/            <-- Componentes de Login (ADM-01)
|   |   |   |-- dashboard/       <-- Layout principal del panel
|   |   |   |-- users/           <-- Listado de usuarios (ADM-02)
|   |   |   |-- transactions/    <-- Auditoqía de transacciones (ADM-03)
|   |   |   |-- fraud/           <-- Alertas de fraude (ADM-04)
|   |   |   |-- health/          <-- Monitoreo de microservicios (ADM-05)
|   |-- assets/         <-- (Imágenes, íconos y tipografías estáticas)
|-- package.json        <-- (Dependencias del proyecto)
```

## 🚀 Guía de Ejecución Local
1. Instalar las dependencias de Node: `npm install`
2. Levantar el servidor de desarrollo: `ng serve -o`
3. La aplicación se abrirá automáticamente en `http://localhost:4200`