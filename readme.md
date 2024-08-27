# Multi-Tier

## Descripción General
Este proyecto es una aplicación web de tier list multiusuario que permite a los usuarios crear y compartir tier lists de manera dinámica y accesible. La aplicación no requiere un sistema de login tradicional, lo que facilita su uso inmediato por parte de los usuarios.

## Tecnologías Utilizadas

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)

### Backend
- Node.js
- Express.js

### Base de Datos
- MongoDB

## Características Principales

1. **Interfaz de Usuario Intuitiva**
   - Diseño responsive utilizando HTML5 y CSS3
   - Interacciones dinámicas implementadas con JavaScript vanilla

2. **Persistencia de Datos**
   - Almacenamiento de tier lists en MongoDB
   - Uso de localStorage para almacenar el nombre de usuario

3. **Funcionalidad Multiusuario**
   - Acceso sin necesidad de crear una cuenta
   - Identificación de usuarios mediante un nombre único almacenado en localStorage

4. **Backend Robusto**
   - API RESTful construida con Node.js y Express.js
   - Manejo eficiente de solicitudes para crear, leer, actualizar y eliminar tier lists

5. **Sin Sistema de Login**
   - Los usuarios ingresan su nombre una sola vez
   - La "eliminación de cuenta" se realiza simplemente borrando los datos del localStorage

## Flujo de Uso
1. El usuario ingresa a la aplicación y proporciona un nombre de usuario
2. El nombre se almacena en localStorage para futuras visitas
3. El usuario puede crear una nueva tier list o acceder a una existente
4. Las tier lists se sincronizan con el backend para su persistencia
5. Los usuarios pueden compartir sus tier lists mediante URLs únicas

## Consideraciones Técnicas
- Implementar validación en el frontend y backend para garantizar la integridad de los datos
- Utilizar técnicas de optimización para manejar grandes cantidades de tier lists
- Implementar medidas de seguridad básicas para prevenir abusos del sistema sin login

## Futuras Mejoras Potenciales
- Implementación de características de colaboración en tiempo real
- Adición de opciones de personalización para las tier lists
- Integración de un sistema de estadísticas y análisis de tier lists populares

Este proyecto busca ofrecer una experiencia fluida y accesible para la creación y compartición de tier lists, aprovechando la simplicidad del frontend con vanilla JavaScript y la robustez de un backend Node.js con MongoDB.
