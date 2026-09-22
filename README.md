# 💜 Freebies BTS: control del grupo

Página para organizar los freebies que vamos a regalar en el concierto de **BTS World Tour "Arirang"** en el Estadio Nacional de Santiago (16 y 17 de octubre de 2026).

Somos 9 y hacemos entre todas **450 pulseras**, **limpiapipas con carita** y **moños**, repartidos de forma pareja entre los 7 integrantes.

## Qué tiene la página

- **Cuenta regresiva** en vivo hasta el concierto.
- **Progreso de cada freebie** con un gráfico de dona y una tarjeta con foto por integrante, para que ninguno quede con menos.
- **Contadores** para anotar pulseras, limpiapipas y moños por integrante, BTS completo y canciones.
- **Outfit, outfit 2, hanbok y maquillaje**: cada una marca lo que tiene listo.
- **Recordatorios compartidos** con fecha límite.
- **Música**: canciones que se abren en YouTube.
- **Confeti** al cumplir metas. 🎉

Todo lo que se anota se guarda en Firebase y lo ven las 9 al mismo tiempo.

## Cómo entrar

1. Abre el link de la página (GitHub Pages).
2. Escribe el **código del grupo** cuando lo pida. Solo se pide una vez por celular.
3. Elige tu nombre y empieza a anotar.

> El código del grupo **no** está en este repositorio a propósito. Pídeselo a alguien del grupo o usa el link de invitación que está en **Ajustes**.

Si alguien ve la página vacía, probablemente escribió mal el código. Se arregla en **Ajustes → Cambiar código del grupo**.

## Cómo actualizar la página

1. Pide los cambios y descarga el `index.html` nuevo.
2. Revisa que tenga la configuración de Firebase (busca `FIREBASE_CONFIG` casi al inicio del código).
3. En este repositorio, toca **Add file → Upload files**, sube el `index.html` y toca **Commit changes**.
4. Espera 1 o 2 minutos y recarga.

Los datos **no se borran** al actualizar, porque viven en Firebase, no en el archivo.

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La página completa: diseño, fotos y funciones. |
| `reglas-firestore.txt` | Reglas de seguridad para pegar en Firebase → Firestore Database → Reglas. |
| `README.md` | Este archivo. |

## Datos y seguridad

- Los datos se guardan en **Cloud Firestore** (proyecto `freebies-bts`), dentro de `grupos/<código>/`.
- Las reglas solo permiten leer y escribir dentro de un grupo, y nadie puede listar los grupos. Sin el código, no se encuentran los datos.
- Cualquiera que tenga el código puede anotar y borrar, así que compártanlo solo entre nosotras.

---

Hecho con cariño por y para ARMY. Borahae 💜
