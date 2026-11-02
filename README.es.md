# Waze para Vehículos BYD

[![Último Release](https://img.shields.io/github/v/release/kolmant/waze-for-byd?color=blue&label=%C3%9Altimo%20Release)](https://github.com/kolmant/waze-for-byd/releases)

> [!TIP]
> 🇺🇸 **English version:** You can read the [English version here](README.md).

Una versión adaptada de Waze para las pantallas de vehículos BYD. Redirige las instrucciones de voz al canal de audio de navegación exclusivo del vehículo para que el volumen de la música y el de las direcciones sean independientes.

---

## ¿Qué hace este proyecto?

En las pantallas de los vehículos BYD, la versión oficial de Waze reproduce las indicaciones de voz a través del canal general de música o multimedia. Esto genera molestias habituales:
* Si bajas el volumen de la música o la silencias, las indicaciones de navegación también se silencian.
* Cada vez que ajustas el volumen de la música, alteras directamente el volumen con el que te habla el GPS.

**Este proyecto soluciona ese inconveniente:**  
Adaptamos Waze para que las instrucciones de voz se envíen al **canal de Navegación** de tu auto BYD. De esta forma, el sistema del vehículo gestiona el volumen del mapa de manera totalmente independiente al de Spotify, la radio o cualquier otra fuente de música.

---

## ¿Qué son los "Releases"?

Si no estás familiarizado con GitHub, no necesitas saber programación para utilizar esto:

* En desarrollo de software, un **Release** (lanzamiento) es una versión terminada y lista para usar.
* Cada vez que Waze publica una actualización, nuestro sistema automatizado genera un archivo instalable para Android (`.apk`) y lo publica en la sección **[Releases](https://github.com/kolmant/waze-for-byd/releases)**.
* Solo debes ingresar a la pestaña **Releases**, buscar la versión más reciente y descargar el archivo `.apk` ubicado en el desplegable de **Assets**.

---

## Instrucciones de Instalación

1. **Desinstala cualquier versión previa:**  
   Si tienes instalada la versión de Google Play Store u otra compilación anterior en la pantalla de tu auto, desinstálala primero.
2. **Descarga el APK:**  
   Dirígete a la sección **[Releases](https://github.com/kolmant/waze-for-byd/releases)** y descarga el archivo `.apk` más reciente (por ejemplo, `waze-navi-X.XX.X.X.apk`).
3. **Instálalo en tu auto:**  
   Copia el archivo descargado en una memoria USB, conéctala en tu BYD, abre el **Administrador de Archivos** del vehículo y toca el archivo APK para iniciar la instalación.
4. **Aviso de Google Play Protect:**  
   Dado que esta aplicación está refirmada de forma comunitaria, el sistema o Google Play Protect puede solicitar confirmación advirtiendo sobre una "fuente desconocida". Puedes continuar la instalación con total tranquilidad.

---

## Descargo de Responsabilidad

Este es un proyecto comunitario independiente y no está afiliado, respaldado ni asociado con Waze, Google ni BYD Auto.
