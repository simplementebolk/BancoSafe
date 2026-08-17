# BancoSafe 💰

BancoSafe es una aplicación web de banca digital desarrollada con **Spring Boot** y **Bootstrap 5**, diseñada para ofrecer una experiencia rápida, moderna y segura.

---

## 🚀 Requisitos previos

Antes de clonar y ejecutar el proyecto, asegúrate de tener instalado en tu computadora:
*   **Java JDK** (Versión 21).
*   Un entorno de desarrollo (IDE) como **IntelliJ IDEA**, **Eclipse**, **VS Code** o similar.

*Nota: No necesitas instalar Maven por separado, ya que el proyecto incluye el **Maven Wrapper** (`mvnw`), que se encarga de descargar la versión correcta automáticamente.*

---

## 📂 Estructura del Proyecto

```text
bancosafe/
├── .mvn/                   <-- Configuración de Maven Wrapper
├── src/
│   ├── main/
│   │   ├── java/com/...    <-- Código fuente en Java (Controladores, etc.)
│   │   └── resources/
│   │       ├── static/     
│   │       └── application.properties <-- Configuración global de la app
│   └── test/               <-- Pruebas unitarias
├── mvnw                    <-- Script para Linux / macOS
├── mvnw.cmd                <-- Script para Windows
└── pom.xml                 <-- Dependencias del proyecto
```

## 🛠️ Cómo Buildear y Ejecutar el Proyecto

Opción A: Si estás en Linux / macOS

Abre tu terminal en la raíz del proyecto.

```text
Bash

chmod +x mvnw
```

Compila y ejecuta el proyecto:

```text
Bash

./mvnw spring-boot:run
```
Opción B: Si estás en Windows

Abre la Terminal, CMD o PowerShell en la carpeta raíz del proyecto.

Ejecuta el siguiente comando:


```text
DOS

mvnw.cmd spring-boot:run

```
(O si usas IntelliJ IDEA, puedes abrir la pestaña lateral de Maven y hacer doble clic en spring-boot -> spring-boot:run).

# 🌐 Acceso a la Aplicación

Una vez que la consola indique que la aplicación se ha iniciado correctamente (verás el logo de Spring y el puerto 8080), abre tu navegador web favorito e ingresa a:

👉 http://localhost:8080

Desde allí podrás navegar entre la página de bienvenida, el inicio de sesión y el registro.

