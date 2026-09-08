# Banco Digital - Panel de Administracion Web (Frontend)

Este repositorio contiene el prototipo del Panel de Administracion Web para nuestro proyecto de Banco Digital. Esta disenado exclusivamente para el uso del personal interno del banco (administradores y auditores).

## Tecnologias y Versiones
- Framework: Angular v22.0.0
- Lenguaje: TypeScript
- Estilos: SCSS (Sass)
- Entorno: Node.js (LTS)

## Historias de Usuario Implementadas (EP10)
Este prototipo cubre las siguientes historias de usuario requeridas para la gestion de la plataforma:
- ADM-01 (Login): Inicio de sesion exclusivo para rol de administrador.
- ADM-02 (Usuarios): Listado y busqueda de cuentas registradas.
- ADM-03 (Transacciones): Detalle y auditoria de transferencias.
- ADM-04 (Fraude): Visualizacion de alertas de seguridad y bloqueo de cuentas.
- ADM-05 (Monitoreo): Panel de estado de salud (Healthchecks) de los microservicios.

## 📂 Estructura de Carpetas (Arquitectura Angular)

```text
banca-web/
|-- src/
|   |-- app/
|   |   |-- core/       <-- (Servicios centrales, Guards de autenticacion)
|   |   |-- shared/     <-- (Componentes UI reutilizables, Navbar, Sidebar)
|   |   |-- features/   <-- (Modulos principales por funcionalidad)
|   |   |   |-- auth/            <-- Componentes de Login (ADM-01)
|   |   |   |-- dashboard/       <-- Layout principal del panel
|   |   |   |-- users/           <-- Listado de usuarios (ADM-02)
|   |   |   |-- transactions/    <-- Auditoria de transacciones (ADM-03)
|   |   |   |-- fraud/           <-- Alertas de fraude (ADM-04)
|   |   |   |-- health/          <-- Monitoreo de microservicios (ADM-05)
|   |-- assets/         <-- (Imagenes, iconos y tipografias estaticas)
|-- package.json        <-- (Dependencias del proyecto)
```

## Guia de Ejecucion Local
1. Instalar las dependencias de Node: npm install
2. Levantar el servidor de desarrollo: ng serve -o
3. La aplicacion se abrira automaticamente en http://localhost:4200
