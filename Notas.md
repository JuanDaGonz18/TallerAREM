# Registro de Trabajo en Clase - Taller 4

## Fecha de la sesión
7 de Abril de 2026

## Integrantes presentes
- Juan David González  
- Julián Barragán  
- Josué Sarmiento  

## Actividades realizadas en clase

Durante la sesión se analizó el caso base RedExpress con el objetivo de comprender la arquitectura tecnológica de la plataforma logística y construir un mapa preliminar de infraestructura.

El equipo discutió los componentes principales del sistema y cómo se relacionan entre sí dentro de una arquitectura por capas. Se identificaron los elementos clave que debían aparecer en el diagrama, como las aplicaciones cliente, la capa de acceso, los servicios de aplicación, la base de datos y los sistemas de monitoreo.

A partir de este análisis se decidió organizar la arquitectura en las siguientes capas:

- Client Layer (aplicaciones móviles y plataforma web)
- Edge / Access Layer (balanceador de carga y API Gateway)
- Application Layer (servicios en contenedores como el motor de rutas y el servicio de rastreo)
- Data Layer (base de datos principal y réplicas de lectura)
- Monitoring and Alerts
- Servicios externos de notificación

Para el modelado del diagrama se utilizó la herramienta **draw.io (diagrams.net)**, la cual permitió representar la arquitectura de forma clara mediante un esquema por capas.

Durante la clase se logró construir el mapa de infraestructura preliminar del caso RedExpress, identificando además posibles puntos críticos como el API Gateway y la base de datos principal, los cuales podrían representar cuellos de botella en escenarios de alta demanda.

El diagrama de la Parte 1 fue desarrollado por **Juan David González y Julián Barragán**, quienes se encargaron del modelado inicial de la arquitectura y del análisis del caso base.

## Boceto inicial del modelo

El boceto inicial corresponde al diagrama de infraestructura desarrollado en draw.io durante la sesión de clase, el cual representa las capas de la arquitectura y los principales componentes del sistema RedExpress.

## Tareas definidas para complementar el taller

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Modelado del mapa de infraestructura (Parte 1) | Juan David González, Julián Barragán | Realizado en clase |
| Investigación del caso base RedExpress | Juan David González, Julián Barragán | Realizado en clase |
| Desarrollo de la Parte 2 del taller (análisis e informe) | Josué Sarmiento | Antes de la entrega |

---

Este documento resume el trabajo colaborativo realizado durante la sesión del Taller 4 en el curso de Arquitectura Empresarial de la Universidad de La Sabana.