# EcoTrack: Plataforma de Monitoreo y Reducción de Huella de Carbono

## Descripción  
En la actualidad, muchas personas y pequeñas empresas desconocen su impacto ambiental y carecen de herramientas accesibles para medir y reducir su huella de carbono. EcoTrack es una plataforma que ayuda a los usuarios a calcular su impacto ecológico a partir de su consumo energético, transporte y hábitos de compra. Además, ofrece recomendaciones personalizadas y desafíos para reducir su huella.  

## Objetivo del Proyecto
EcoTrack tiene como objetivo proporcionar una plataforma accesible e intuitiva que permita a individuos y pequeñas empresas calcular, analizar y reducir su huella de carbono. A través del uso de datos de consumo energético, transporte y hábitos de compra, la plataforma ofrecerá informes detallados, recomendaciones personalizadas y un sistema de gamificación para incentivar la adopción de prácticas sostenibles.

El propósito es generar conciencia ambiental y promover acciones concretas que contribuyan a la mitigación del cambio climático, facilitando a los usuarios el seguimiento de su impacto ecológico y motivándolos a mejorar sus hábitos de manera progresiva.

## Integrantes  
- [Lewis Amado](https://github.com/lewisamado)  
- [Juan Tabares](https://github.com/juandatabares)  
 

## Módulos del Sistema  
1. *Autenticación y Gestión de Usuarios*: Control de acceso, perfiles y roles.  
2. *Cálculo y Análisis de Huella de Carbono*: Procesamiento de datos y visualización de impacto ambiental.  
3. *Recomendaciones y Gamificación*: Consejos personalizados, retos ecológicos y sistema de recompensas.


## Flujo del proyecto
1️ Inicio y Registro

Objetivo: Permitir el acceso a la plataforma y recopilar datos iniciales.

Flujo:

El usuario accede a la página web.

Se registra con email y contraseña o con Google/Facebook.

Completa un formulario inicial con datos básicos (país, tipo de vivienda, hábitos de consumo).

Es redirigido al dashboard principal.


2️ Dashboard Principal

Objetivo: Mostrar el estado actual de la huella de carbono del usuario.

Flujo:

El usuario ve su huella de carbono calculada a partir de los datos ingresados.
Se presentan gráficos con su impacto ambiental (energía, transporte, consumo).
El usuario puede acceder a opciones como:

 Más detalles sobre su impacto.

 Desafíos y metas personalizadas.

 Recomendaciones para reducir su huella.


3️ Cálculo y Seguimiento de la Huella de Carbono

Objetivo: Permitir al usuario registrar su consumo para un cálculo preciso.

Flujo:

El usuario ingresa información sobre:

 Consumo de electricidad y agua.

 Tipo y frecuencia de transporte utilizado.

 Hábitos de compra y alimentación.

EcoTrack recalcula la huella de carbono en tiempo real.

El usuario puede visualizar su progreso y comparación con promedios globales.


4️ Recomendaciones y Desafíos

Objetivo: Incentivar al usuario a mejorar su impacto ambiental.

Flujo:

Basado en sus datos, EcoTrack sugiere:

 Pequeños cambios (ej. reducir consumo de electricidad).

 Retos semanales (ej. usar bicicleta en lugar de auto).

El usuario puede aceptar desafíos y recibir puntos y recompensas.

Se muestra un ranking con amigos y la comunidad para motivación.


5️ Comunidad e Interacción

Objetivo: Fomentar la participación y el intercambio de experiencias.

Flujo:

El usuario puede compartir sus logros en redes sociales.

Puede participar en foros o grupos de discusión sobre sostenibilidad.

Las empresas pueden crear campañas ecológicas y patrocinar desafíos.


6️ Configuración y Cierre de Sesión

Objetivo: Permitir ajustes personalizados.

Flujo:

El usuario puede modificar su perfil y preferencias de notificación.

Puede exportar un informe de su impacto ecológico.

Opción para cerrar sesión o eliminar cuenta si lo desea.


Resumen del Flujo:

1️ Registro/Login → 2️ Dashboard → 3️ Ingreso de Datos → 4️ Recomendaciones y Retos → 5️ Comunidad → 6️ Configuración/Cierre de Sesión

## Tecnologías Utilizadas  
- *Frontend:* React.js  
- *Backend:* Node.js con Express  
- *Base de Datos:* MongoDB  
- *Autenticación:* Firebase / Auth0  

