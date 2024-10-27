# EPEII App Móvil 📱

Aplicación móvil creada con **Apache Cordova** para la gestión de actividades sostenibles y eco-friendly. Este proyecto es parte de un ejercicio académico y está diseñado para permitir a los usuarios registrar sus metas de sostenibilidad, calcular su huella de carbono y acceder a recursos de concienciación ambiental.

---

## Tabla de Contenidos

- [Descripción](#descripción)
- [Funcionalidad](#funcionalidad)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Proceso de Desarrollo](#proceso-de-desarrollo)
- [Decisiones de Diseño](#decisiones-de-diseño)
- [Instalación](#instalación)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

---

## Descripción

Esta aplicación permite a los usuarios llevar un registro diario de sus actividades sostenibles. Incluye herramientas para establecer metas y objetivos, un cálculo básico de huella de carbono, y recursos para fomentar hábitos eco-amigables. La aplicación está diseñada para **iOS** y **Android**.

---

## Funcionalidad

- **Inicio de Sesión y Registro de Usuario:** Vistas para que los usuarios puedan registrarse e iniciar sesión de manera sencilla.
- **Metas y Objetivos:** Sección donde los usuarios pueden establecer metas anuales, como reducir su huella de carbono, y objetivos semestrales, como registrar cinco actividades sostenibles.
- **Consejos y sugerencias:** Sección que proporciona recomendaciones prácticas y útiles sobre sostenibilidad y reducción de huella de carbono.
- **Calculadora de Huella de Carbono:** Herramienta para que los usuarios puedan introducir datos y recibir información sobre su impacto ambiental.
- **Registro de Actividades:** Los usuarios pueden registrar actividades sostenibles y recibir reconocimientos.
- **Recursos Educativos:** Sección que contiene enlaces a recursos sobre sostenibilidad y reducción de huella de carbono.

---

## Tecnologías Utilizadas

- **Apache Cordova**: Framework para crear aplicaciones móviles multiplataforma.
- **HTML, CSS, JavaScript**: Base para la estructura, estilo y funcionalidad de la aplicación.
- **Android SDK**: Para desarrollar y construir el proyecto en Android.
- **Android Studio**: Entorno de desarrollo integrado (IDE) para construir y probar aplicaciones en Android.
- **Gradle**: Herramienta de construcción de automatización.
- **Git/GitHub**: Control de versiones y colaboración.

---

## Proceso de Desarrollo

1. **Configuración del Entorno**:
   - Se instalaron Apache Cordova, el SDK de Android y Gradle.
   - Configuración de las variables de entorno `ANDROID_HOME`, `JAVA_HOME` y PATH.
   
2. **Desarrollo de Funcionalidades**:
   - Implementación de vistas HTML para `inicio de sesión`, `creación de usuario`, `metas`, `Consejos y sugerencias`, `Registro de actividades`, `calculadora` y `recursos`.
   - Uso de Cordova para compilar y probar en emuladores y dispositivos Android.

3. **Pruebas y Depuración**:
   - Se realizaron pruebas en Android Studio para verificar la funcionalidad en diversas resoluciones de pantalla y sistemas operativos.
   - Ajustes en la interfaz para mejorar la usabilidad y corrección de errores.

---

## Decisiones de Diseño

- **Esquema de Colores**: Se eligieron los colores verde, gris y azul como principales para reflejar los valores de sostenibilidad y armonía con el medio ambiente.
- **Navegación Intuitiva**: La estructura de navegación se mantuvo simple y fácil de seguir.
- **Enfoque Eco-Friendly**: Cada funcionalidad está orientada a motivar a los usuarios a tomar decisiones más amigables con el medio ambiente.

---

## Instalación

Para clonar e instalar el proyecto, sigue los pasos a continuación:

1. **Clonar el Repositorio**:
   ```bash
   git clone https://github.com/juanMarinP/desarrollo-app-epeII.git
   cd desarrollo-app-epeII
   ```
   
2. **Instalar dependencias de Cordova**:
 ```bash
   npm install -g cordova
   cordova prepare
   ```

3. **Construir y ejecutar**:
 ```bash
   cordova build android
   cordova run android
   ```
