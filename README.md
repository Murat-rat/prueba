# SimpleFit

> **Proyecto Integrador - Desarrollo de Aplicaciones Móviles**
>
> **Semestre:** 4°E
> **Fecha de entrega:** 11 de Diciembre

---

## Equipo de Desarrollo

| Nombre Completo | Rol / Tareas Principales | Usuario GitHub |
| :--- | :--- | :--- |
| Murat Castro Álvarez | Diseño de la UI, Creación del Repo, Login y registro | @Murat-rat |
| Leonardo Díaz Espinosa | Pantalla principal, Pantalla de sesión en curso, Cards | @LeonardoDiazz |
| Shanny Odeth Ramos Santiesteban | Configuración del sensor, Retrofit, Base de Datos, Pruebas | @ShannyRamos17 |

---

## Descripción del Proyecto

**¿Qué hace la aplicación?**
La aplicación es un podómetro simple que permite registrase e iniciar sesión para poder registrar nuestras sesiones de actividad física al caminar o correr.

En la pantalla principal la aplicación muestra tarjetas en las que se puede ver la información de los registros de actividad física, muestra los siguientes datos:
- Nombre de usuario
- Duración acomulada de la sesión
- Distancia aproximada recorrida
- Velocidad promedio 
- Fecha en la cual se actualizó por última vez la sesión

Se puede dar click a las tarjetas para reanudar una sesión, manteniendo los datos que ya tenía almacenada la sesión y añadiendo a ellos. Cada tarjeta también
tiene un botón que permite eliminar el registro de la base de datos.

La aplicación busca ser una solución simple para personas que disfrutan salir a caminar o correr de manera casual, pero que a la vez les gustaría tener un
registro de su actividad.

**Objetivo:**
Demostrar la implementación de una arquitectura robusta en Android utilizando servicios web y hardware del dispositivo.

---

## Stack Tecnológico y Características

Este proyecto ha sido desarrollado siguiendo estrictamente los lineamientos de la materia:

* **Lenguaje:** Kotlin 100%.
* **Interfaz de Usuario:** Jetpack Compose.
* **Arquitectura:** MVVM (Model-View-ViewModel).
* **Conectividad (API REST):** Retrofit.
    * **GET:** [Explica brevemente qué datos obtienes]
    * **POST:** [Explica qué datos envías/creas]
    * **UPDATE:** [Explica qué se actualiza]
    * **DELETE:** [Explica qué se borra]
* **Sensor Integrado:** [Menciona aquí el sensor usado: Ej. Cámara, GPS, Giroscopio]
    * *Uso:* [Explica brevemente para qué se usa el sensor en la app]

---

## Capturas de Pantalla

[Coloca al menos 3 (investiga como agregarlas y se vean en GitHub)]

| Pantalla de Login | Pantalla de Inicio | Registro de Actividad |
| :---: | :---: | :---: |
| ![Inicio](url_imagen) | ![CRUD](url_imagen) | ![Sensor](url_imagen) |

---

## Instalación y Releases

El ejecutable firmado (.apk) se encuentra disponible en la sección de **Releases** de este repositorio.

1.  Ve a la sección "Releases" (o haz clic [aquí](https://github.com/Murat-rat/SimpleFit/releases/tag/v1.0.0)).
2.  Descarga el archivo `.apk` de la última versión.
3.  Instálalo en tu dispositivo Android (asegúrate de permitir la instalación de orígenes desconocidos).
