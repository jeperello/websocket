# 🚀 Real-Time Messaging Service (Spring Boot + WebSocket)

Sistema de mensajería asíncrona construido con **Spring Boot** y el protocolo **STOMP**. Diseñado para ser consumido por clientes modernos como Angular.

## 🛠️ Stack Tecnológico
- **Backend:** Java 17/21, Spring Boot 3.x
- **Mensajería:** Spring WebSocket + STOMP
- **Testing:** JUnit 5, Mockito
- **CI/CD:** GitHub Actions

## 🏗️ Arquitectura
El proyecto utiliza un modelo de **Publish/Subscribe**.
- **Broker:** Gestiona la distribución de mensajes a los clientes suscritos.
- **Protocolo:** STOMP sobre WebSockets para facilitar el manejo de rutas y headers.

## 🚀 Instalación y Ejecución
1. Clonar el repositorio: `git clone ...`
2. Construir el proyecto: `./mvnw clean install`
3. Ejecutar: `./mvnw spring-boot:run`

## 🚦 Pipeline de Integración Continua (CI)
Este proyecto incluye **GitHub Actions**. Cada `Push` o `Pull Request` dispara:
1. Compilación del código.
2. Ejecución de tests unitarios e integración.
