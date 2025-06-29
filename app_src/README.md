# app_src

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Configuración de Google Cloud

Para que el inicio de sesión con Google funcione en Firebase debes activar el
servicio **Identity Toolkit API** en la consola de Google Cloud. Después, en la
consola de Firebase habilita el proveedor **Google** dentro de
**Authentication** y genera un cliente OAuth 2.0. Descarga los archivos
`google-services.json` y `GoogleService-Info.plist` y colócalos en los proyectos
de Android e iOS respectivamente.
