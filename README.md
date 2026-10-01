# 🚨 App de Asistencia y Gestión de Catástrofes

Aplicación móvil nativa para **Android**, desarrollada en **Kotlin**, orientada a la prevención, respuesta ante emergencias y asistencia comunitaria frente a catástrofes naturales.

El proyecto integra **Firebase, Google Maps, geolocalización, sensores del dispositivo, multimedia y servicios externos**.

---

## ✨ Funcionalidades

* 🚨 Números de emergencia sincronizados con Firebase.
* 📞 Llamadas directas a servicios de emergencia.
* 🌦️ Información meteorológica mediante API.
* 🔦 Linterna.
* 📹 Grabación de video y 🎙️ audio.
* 🔋 Estimación de batería.
* 📍 Geolocalización y Google Maps.
* 🤝 Mapa comunitario para solicitar y ofrecer ayuda.
* 💬 Chat de asistencia en tiempo real.
* 🚨 Alertas ante catástrofes.
* 📚 Guías de acción ante emergencias.
* 🎙️ Comandos por voz.

---

## 🤝 Punto de innovación

### Red de Ayuda Comunitaria

La aplicación incorpora un mapa donde los usuarios pueden:

* 🆘 **Solicitar ayuda o recursos.**
* 🤝 **Ofrecer ayuda o recursos.**
* 📍 Visualizar estos puntos en el mapa en tiempo real.

La información se almacena mediante **Firebase Cloud Firestore**.

---

## 🛠️ Tecnologías

* **Kotlin**
* **Android / Jetpack Compose**
* **Firebase Cloud Firestore**
* **Google Maps SDK**
* **API meteorológica**
* **GPS y geolocalización**
* **Cámara y micrófono**

---

# 📥 Descargar y ejecutar

## Requisitos

* Android Studio **Hedgehog / Iguana / Jellyfish o superior**
* **JDK 17**
* Android SDK 34
* Dispositivo Android o emulador
* Google Play Services
* Conexión a Internet

---

## 1. Clonar el repositorio

```bash
git clone https://github.com/lourdesibanez/TP1.git
cd TP1
```

También podés descargar el proyecto desde:

**[📦 Repositorio en GitHub](https://github.com/lourdesibanez/TP1)**

---

## 2. Abrir el proyecto

Abrir **Android Studio → Open** y seleccionar la carpeta `TP1`.

Esperar a que termine la sincronización de **Gradle**.

---

## 3. Configurar Firebase

Crear un proyecto en [Firebase Console](https://console.firebase.google.com/) y agregar una aplicación Android utilizando el mismo package name del proyecto.

Descargar:

```text
google-services.json
```

y colocarlo en:

```text
TP1/
└── app/
    └── google-services.json
```

---

## 4. Configurar Google Maps

Crear una API Key en **Google Cloud Console** con `Maps SDK for Android` habilitado.

En `local.properties`:

```properties
MAPS_API_KEY=TU_CLAVE_AQUI
```

---

## 5. Ejecutar

Conectar un dispositivo Android con **depuración USB activada** o iniciar un emulador.

En Android Studio:

```text
Run ▶️
```

o:

```text
Shift + F10
```

---

## 📁 Arquitectura

El proyecto utiliza una arquitectura por capas, separando **Presentación** y **Datos**:

```text
presentation/
├── pantalla/
├── componentes/
└── viewmodel/

data/
├── model/
├── remote/
└── repository/
```

---

## 👩‍💻 Proyecto

Desarrollado como **Trabajo Práctico de Aplicaciones Móviles**.

**Kotlin + Firebase + Android**
