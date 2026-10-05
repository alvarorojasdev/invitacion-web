# Invitación web de boda

Sitio de invitación de boda, hecho en **Astro** con componentes de **React**. Esta es una versión de demostración: los nombres, la fecha, los lugares, las cuentas y las imágenes son de ejemplo.

## Qué incluye

- Portada con video y música de fondo, con control de reproducción.
- Cuenta regresiva hasta la fecha del evento.
- Ceremonia y celebración con horario y enlace al mapa.
- Código de vestimenta, consejos, playlist sugerida y regalos, en ventanas modales.
- **Confirmación de asistencia** con formulario validado (`react-hook-form`) guardado en **Firebase Firestore**.
- Transmisión en vivo para invitados a distancia, con hora local del visitante.
- Diseño responsive con Tailwind CSS.

## Correr en local

```bash
npm install
npm run dev
```

Sin configurar Firebase, el sitio corre en **modo demo**: el formulario de asistencia simula el envío y no guarda nada. Para guardar confirmaciones de verdad, copia `.env.example` a `.env` y completa los datos de tu proyecto de Firebase.

## Stack

Astro · React · Tailwind CSS · Firebase Firestore · react-hook-form

## Autor

Desarrollado por [Álvaro Rojas](https://github.com/alvarorojasdev).
