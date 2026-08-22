<div align="center">

  <img src="https://github.com/Animetailapp/Animetail/blob/master/app/src/debug/res/mipmap-xxhdpi/ic_launcher.png?raw=true" alt="Animetail Logo" width="120" height="120" style="border-radius: 24px; box-shadow: 0 8px 24px rgba(0,0,0,0.2);" />

  # 🌙 Animetail Nightly Builds
  
  <p align="center">
    <strong>Compilaciones nocturnas y automatizadas con las últimas novedades de <a href="https://github.com/Animetailapp/Animetail">Animetail</a>.</strong>
     
    
  📰 **News:** [Gnews](https://akiled.org)

[![Discord server](https://img.shields.io/discord/1196139193664028762.svg?label=&labelColor=6A7EC2&color=7389D8&logo=discord&logoColor=FFFFFF)](https://discord.gg/fvskrQZb9j)
[![Gnews](https://img.shields.io/badge/News-Gnews-blue?logo=rss&logoColor=white)](https://akiled.org)
  </p>

  <p align="center">
    <a href="https://github.com/Animetailapp/Animetail-preview/actions/workflows/build.yml">
      <img src="https://github.com/Animetailapp/Animetail-preview/actions/workflows/build.yml/badge.svg" alt="Build Status" />
    </a>
    <a href="https://github.com/Animetailapp/Animetail-preview/releases">
      <img src="https://img.shields.io/github/v/release/Animetailapp/Animetail-preview.svg?style=flat&color=7289da&label=Latest%20Nightly" alt="Latest Release" />
    </a>
    <a href="https://github.com/Animetailapp/Animetail-preview/releases">
      <img src="https://img.shields.io/github/downloads/Animetailapp/Animetail-preview/total?style=flat&color=34d399&label=Downloads" alt="Total Downloads" />
    </a>
    <a href="https://github.com/Animetailapp/Animetail/blob/master/LICENSE">
      <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="License" />
    </a>
  </p>

  <p align="center">
    <a href="#-descargas">Descargar</a> •
    <a href="#-qu%C3%A9-es-animetail-nightly">¿Qué es Nightly?</a> •
    <a href="#-gu%C3%ADa-de-arquitecturas-apks">Arquitecturas</a> •
    <a href="#-instalaci%C3%B3n">Instalación</a> •
    <a href="#-comunidad">Comunidad</a>
  </p>

</div>

---

## ⚡ ¿Qué es Animetail Nightly?

Este repositorio aloja las **versiones en desarrollo (Nightly / Preview)** de **[Animetail](https://github.com/Animetailapp/Animetail)**. 

Se compilan automáticamente todos los días a las **17:30 UTC** directamente desde la rama principal cada vez que hay nuevos commits, permitiéndote probar las funciones más recientes antes de su lanzamiento oficial.

> [!WARNING]
> **Versiones de desarrollo (Bleeding Edge)**: Las builds nocturnas pueden contener errores, funciones experimentales o inestabilidad ocasional. Se recomienda realizar copias de seguridad periódicas de tus datos.

---

## 📦 Descargas

Puedes obtener la última versión directamente desde la pestaña de releases:

<div align="center">

👉 **[Ir a las Últimas Releases de Animetail Nightly](https://github.com/Animetailapp/Animetail-preview/releases)** 👈

</div>

---

## 📱 Guía de Arquitecturas (¿Qué APK descargar?)

Cada versión incluye paquetes optimizados para diferentes procesadores y dispositivos:

| Paquete / Archivo | Arquitectura | Dispositivos Compatibles | Recomendación |
| :--- | :--- | :--- | :--- |
| `animetail-arm64-v8a-r*.apk` | **ARM 64-bit** | Mayoría de teléfonos modernos (2017+) | 🌟 **Recomendado para la mayoría** (Menor tamaño) |
| `animetail-r*.apk` | **Universal** | Todos los procesadores | ✅ Úsalo si no conoces la arquitectura de tu móvil |
| `animetail-armeabi-v7a-r*.apk` | **ARM 32-bit** | Dispositivos antiguos | Dispositivos de 32 bits |
| `animetail-x86_64-r*.apk` | **x86 64-bit** | Emuladores / ChromeOS / PC | Emuladores de PC 64-bit |
| `animetail-x86-r*.apk` | **x86 32-bit** | Emuladores clásicos | Emuladores de PC 32-bit |

> [!TIP]
> Si no estás seguro de cuál elegir, descarga la versión **Universal (`animetail-r*.apk`)** o la versión **`arm64-v8a`** que funciona en prácticamente cualquier smartphone moderno.

---

## 🚀 Instalación y Actualización

1. **Descarga el APK** correspondiente a tu dispositivo desde [Releases](https://github.com/Animetailapp/Animetail-preview/releases).
2. Si es tu primera vez instalando un APK externo en Android, habilita la opción de **"Instalar aplicaciones de fuentes desconocidas"** en tu navegador o explorador de archivos.
3. Abre el archivo descargado y presiona **Instalar** (o **Actualizar** si ya tienes una versión previa).
4. *¡Disfruta de las últimas novedades!*

---

## ⚙️ Automatización CI/CD

El sistema de compilación y distribución se gestiona mediante **GitHub Actions**:

- 🤖 **Verificación Inteligente**: Compara automáticamente si existen nuevos commits en `Animetailapp/Animetail` contra la última versión publicada antes de iniciar una compilación.
- ☕ **Entorno Actualizado**: Compilado con **Java 25 (Temurin)** y **Gradle Action v6**.
- 🔐 **Firma y Checksums**: Cada APK se firma con keystore verificado y se generan hashes **SHA-256** para garantizar la integridad de las descargas.
- 📢 **Notificaciones**: Integración automática con Webhook de Discord para avisar a la comunidad sobre nuevos releases al instante.

---

## 🌐 Enlaces y Comunidad

- 📂 **Código Fuente Principal**: [Animetailapp/Animetail](https://github.com/Animetailapp/Animetail)
- 🐛 **Reportar Errores / Sugerencias**: [Issues](https://github.com/Animetailapp/Animetail/issues)
- 💬 **Discord**: Únete a nuestra comunidad para estar al día de anuncios y soporte.

---

<div align="center">
  <sub>Desarrollado con ❤️ para la comunidad de Animetail</sub>
</div>
