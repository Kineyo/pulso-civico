# Política de Seguridad

## Reportar una vulnerabilidad
**No abras un Issue público.** Escribe en privado a los mantenedores:
- Canal de Telegram Oficial: [Telegram](https://t.me/c/3988513813/1).
- Correo: **No disponible por el momento**.

Incluye: descripción, pasos para reproducir y posible impacto. Respondemos en un máximo de 7 días.

> [!TIP]
> **Generador de Reportes:** Puedes utilizar el formulario interactivo local [**`reporte_seguridad.html`**](reporte_seguridad.html) para estructurar tus datos, verificar que no incluyas secretos reales, generar el hash SHA-256 de integridad y copiar o descargar el reporte en Markdown listo para enviar.

## Alcance
- Exposición de archivos internos (`storage/`, `.env`, logs).
- XSS, inyecciones, ejecución remota.
- Manipulación de datasets publicados.

## Buenas prácticas para colaboradores
- Nunca subir `.env`, cookies, tokens ni credenciales.
- Si subiste un secreto por error, avisa de inmediato: hay que rotarlo y limpiar el historial.
