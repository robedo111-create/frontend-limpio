# Frontend para Mi API de Posts

Este es el frontend de una API de posts con autenticación JWT y base de datos PostgreSQL, desplegada en Render.

> ⚠️ **Nota importante sobre el despliegue:** El backend está alojado en el plan gratuito de Render. Si la aplicación no ha recibido tráfico en los últimos 15 minutos, el servidor "dormirá". La primera petición (como iniciar sesión o listar posts) puede tardar hasta 50 segundos en responder mientras el servicio se despierta. ¡Gracias por tu paciencia!

## 🚀 Tecnologías utilizadas
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Backend:** FastAPI (Python)
- **Base de datos:** PostgreSQL
- **Despliegue:** GitHub Pages (frontend) y Render (backend)

## 📋 Funcionalidades
- Crear posts
- Listar posts
- Editar posts
- Eliminar posts
- Autenticación JWT (registro e inicio de sesión)

## 🧪 Mi Rol como QA Tester en este Proyecto
Aunque este repositorio contiene el código del frontend, mi enfoque principal durante el desarrollo fue garantizar la calidad del sistema de extremo a extremo:

- **Diseño de Casos de Prueba:** Creé matrices de prueba para los endpoints (GET, POST, PUT, DELETE) validando códigos de estado HTTP (200, 201, 400, 401, 404) y la estructura de las respuestas JSON.
- **Pruebas de Seguridad:** Validé el flujo de autenticación JWT (registro, login, expiración de token y acceso denegado a rutas protegidas).
- **Pruebas de API:** Utilicé **Postman** para probar la integridad de los datos enviados y recibidos, así como pruebas automatizadas con Pytest (ver repositorio `api_stand_tests`).
- **Gestión de Defectos:** Documenté los bugs encontrados durante las pruebas manuales, priorizando según su impacto en el negocio.

🔗 **Evidencia de pruebas:** Puedes revisar mi suite de pruebas automatizadas para este proyecto en el repositorio [api_stand_tests](https://github.com/robedo111-create/api_stand_tests).

## 🔗 Enlaces del proyecto
- **Frontend:** [https://robedo111-create.github.io/frontend-limpio/](https://robedo111-create.github.io/frontend-limpio/)
- **API:** [https://mi-proyecto-apis.onrender.com](https://mi-proyecto-apis.onrender.com)
- **Documentación de la API (Swagger):** [https://mi-proyecto-apis.onrender.com/docs](https://mi-proyecto-apis.onrender.com/docs)

## 📦 Instalación local

1. Clona el repositorio:
   ```bash
   git clone https://github.com/robedo111-create/frontend-limpio.git
