# MedSurgery Store – Shopify

Repositorio privado para el desarrollo, personalización y automatización de la tienda online MedSurgery Store en Shopify.

## Descripción

Este repositorio contiene el código fuente, assets y configuraciones necesarias para operar y escalar la tienda MedSurgery Store bajo las mejores prácticas de desarrollo web, automatización y seguridad para e-commerce médico.

## Estructura principal
/assets         → Imágenes, scripts y hojas de estilos personalizados
/sections       → Componentes Liquid para estructura de tienda
/snippets       → Fragmentos de código reutilizables
/templates      → Plantillas de páginas principales
/config         → Configuraciones del theme
/locales        → Archivos de localización y traducción

## Requisitos de desarrollo
- **Node.js** LTS
- **Shopify CLI** (v4+)
- **NPM** o **Yarn**
- **Git**

## Instalación y uso
1. Clonar el repositorio:
    ```bash
    git clone https://github.com/SuUsuario/Shopify.git
    cd Shopify
    ```
2. Instalar dependencias:
    ```bash
    npm install
    ```
3. Configurar variables de entorno (crear `.env` en la raíz si es necesario):
    ```
    SHOPIFY_API_KEY=...
    SHOPIFY_API_SECRET=...
    SHOPIFY_STORE_URL=...
    ```
4. Desplegar en entorno local:
    ```bash
    shopify theme serve
    ```

## Buenas prácticas
- Trabajar en ramas (`feature/*`, `fix/*`) y abrir Pull Requests para revisión.
- Mantener actualizado el archivo `.gitignore`.
- Realizar backup previo a cambios mayores en el theme.

## Contacto
**Titular:** Dr. Raymundo Adrián Huerta Ruíz  
**Email:** customer_service@medsurgery.store

