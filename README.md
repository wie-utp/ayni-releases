# AYNI · Versiones

Canal oficial de descarga de **AYNI**, la aplicación gratuita y sin conexión que
apoya a niños con Trastorno del Espectro Autista (TEA) y orienta a sus familias.

Este es un repositorio [F-Droid](https://f-droid.org) propio: solo contiene los
APK firmados y un índice firmado. El código fuente vive en un repositorio privado.

**Página de instalación:** https://wie-utp.github.io/ayni-releases/

Un proyecto de **WIE UTP**, la rama estudiantil de Women in Engineering de la
Universidad Tecnológica del Perú, con apoyo de **IEEE EPICS**.

---

## Instalar AYNI en una tablet

1. Instala el cliente **F-Droid** en la tablet desde [f-droid.org](https://f-droid.org).

2. Abre F-Droid y ve a **Ajustes → Repositorios**, toca el botón **+** y agrega:

   ```
   https://wie-utp.github.io/ayni-releases/repo
   ```

   O escanea este código QR en F-Droid para agregar el repositorio (incluye la huella de seguridad):

   ![Agregar el repositorio F-Droid de AYNI](repo-qr.png)

3. Busca **AYNI** y toca Instalar.

4. La primera vez que abras el módulo de consultas, AYNI te pedirá **descargar
   sus modelos de inteligencia artificial** (una sola vez, con Wi-Fi). Después,
   la aplicación funciona completamente sin conexión.

## Actualizaciones

F-Droid revisa este repositorio periódicamente. Cuando hay una versión nueva,
muestra una notificación de actualización. Toca Actualizar: el APK se descarga
por Wi-Fi en pocos segundos y se instala sobre la app existente. Tus ajustes y
datos se conservan.

## Privacidad

AYNI no envía datos a ningún servidor. Toda la inteligencia artificial (búsqueda
de respuestas, asistente de lenguaje y la señal del semáforo emocional) se
ejecuta dentro del dispositivo. La información del niño nunca sale del equipo.

## Modelos de IA

Los modelos grandes (el buscador de respuestas y el asistente de lenguaje) no se
incluyen dentro del APK; la aplicación los descarga la primera vez desde la
sección de [Releases](https://github.com/wie-utp/ayni-releases/releases) de este
repositorio, verificando su integridad con SHA-256.

## Qué hay en este repositorio

```
index.html         página de instalación (servida por GitHub Pages)
repo-qr.png        código QR del repositorio F-Droid
repo/
├── index-v1.jar   índice firmado del repositorio (lo lee F-Droid)
├── *.apk          versiones firmadas de la aplicación
└── ...
```

## Huella del repositorio

Para verificación manual, la huella de la clave de firma del repositorio es:

```
24725C42938F2BEC551ABE958D043B6BD3FF500146011B7E204D41C34FBA4D8B
```

---

Licencia Apache 2.0 · *Juntos aprendemos*
