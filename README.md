# Alfa y Omega Logistics: app Android de mensajeros (archivo histórico)

![Estado: archivo histórico](https://img.shields.io/badge/Estado-archivo%20hist%C3%B3rico-lightgrey) ![Java](https://img.shields.io/badge/Java-orange) ![Android SDK 23](https://img.shields.io/badge/Android%20SDK%2023-3DDC84) ![GPS](https://img.shields.io/badge/GPS-blue)

> [!NOTE]
> Código original de la app Android que usaban los mensajeros de Alfa y Omega Logistics para recibir y cerrar servicios en 2018. El producto continúa en **[android-logistics-fleet-dispatch-platform](https://github.com/KevinAndrey96/android-logistics-fleet-dispatch-platform)**, que reúne todos sus componentes con documentación actualizada.
> 
> La raíz y la carpeta `AlfayOmegaLogistics(Mensajeros)/` guardan dos versiones del mismo proyecto; se mantienen ambas tal como se entregaron.

## Qué contiene

- Bandejas de servicios por asignar y por realizar (`PorAsignar`, `PorRealizar`).
- Ubicación actual del mensajero con el proveedor de localización de Android (`Menu`, `navigation`).
- Confirmación de entrega con fotografía y firma del destinatario (`FotoFirma`).
- Historial de servicios, cuenta del mensajero y cambio de contraseña.

## Stack original

| Componente | Tecnología |
| :--- | :--- |
| Lenguaje | Java |
| Plataforma | Android SDK 23 (mínimo 14) |
| Red | Apache HttpClient y HttpMime |
| Build | Gradle con Android Gradle Plugin 2.3 |

## Ejecutarlo localmente

Importa el proyecto en Android Studio. Usa Android Gradle Plugin 2.3, `compileSdkVersion 23` y Google Play Services 8.4, por lo que necesita un JDK 8 y un Gradle antiguo para compilar. Las llaves de Google Maps se reemplazaron por `YOUR_GOOGLE_MAPS_API_KEY`.

## Estado del repositorio

- Se conserva sin cambios funcionales como referencia del código original (2018).
- No recibe actualizaciones de dependencias; el mantenimiento ocurre en [android-logistics-fleet-dispatch-platform](https://github.com/KevinAndrey96/android-logistics-fleet-dispatch-platform).
- En noviembre de 2026 se depuró el historial completo: se retiraron 32 APK compilados y las carpetas `.idea/`. Todos los commits conservan su fecha original.

## Autoría

Kevin Andrey Herrera Silva ([@KevinAndrey96](https://github.com/KevinAndrey96)).

## Licencia

Código desarrollado para un cliente y publicado como muestra de portafolio. No incluye licencia de código abierto: todos los derechos reservados.
