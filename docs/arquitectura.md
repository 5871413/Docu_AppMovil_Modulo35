# Arquitectura del Sistema - App Delivery/Repartidor

## 1. Descripción

La aplicación móvil utiliza una arquitectura compuesta por la aplicación móvil, los servicios de la aplicación, una API REST y una base de datos.

## 2. Componentes

### Aplicación Móvil

Es la interfaz utilizada por el cliente y el repartidor.

### Servicio / Controlador

Procesa las acciones realizadas desde la aplicación.

### API REST

Recibe las solicitudes HTTP y procesa los datos.

### Base de Datos

Almacena usuarios, pedidos, productos y estados de entrega.

## 3. Flujo General

Usuario
↓
Aplicación Móvil
↓
Servicio / Controlador
↓
API REST
↓
Base de Datos

## 4. Roles

### Cliente

- Registrarse.
- Iniciar sesión.
- Consultar productos.
- Realizar pedidos.
- Consultar el estado del pedido.

### Repartidor

- Iniciar sesión.
- Consultar pedidos asignados.
- Actualizar el estado.
- Confirmar entregas.