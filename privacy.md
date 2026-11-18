# Política de privacidad — valadevs-publish

**Responsable:** ValaDevs · **Última actualización:** 2026-11-18

## Qué es
`valadevs-publish` es una herramienta personal y privada que publica en mis propias cuentas de YouTube, TikTok e Instagram vídeos que yo apruebo. No es un servicio para terceros: la usa una sola persona (el responsable).

## Datos que trata
- Identificadores de mi cuenta (id del canal / `open_id`, nombre visible) y los permisos concedidos (scopes).
- Tokens de acceso y renovación OAuth, guardados **cifrados** (AES-256-GCM) en mi servidor; la clave está fuera de la base de datos.
- Mis propios vídeos, títulos, descripciones y registros de publicación (fechas, estado, errores).

No se recogen datos de otras personas ni de espectadores, no hay analítica ni publicidad.

## Uso de los datos de Google (YouTube)
El uso y la transferencia de la información recibida de las API de Google a cualquier otra app cumplirá la [Política de datos de usuario de los servicios de API de Google](https://developers.google.com/terms/api-services-user-data-policy), incluidos los requisitos de Uso Limitado.
Solo se solicita `youtube.upload` (subir vídeos y miniaturas) y, si lo activo, `youtube.force-ssl` (subtítulos y listas). Los datos no se venden, no se comparten con terceros ni se usan para publicidad o para entrenar modelos.

## Conservación y borrado
Los tokens se conservan mientras la cuenta esté conectada. Al revocar una cuenta se revoca el acceso en el proveedor y se borra el token local. Los registros de publicación se conservan en mi servidor hasta que los borre. Puedo retirar el acceso en cualquier momento desde <https://myaccount.google.com/permissions> (Google), Ajustes → Seguridad y permisos (TikTok) o Ajustes → Apps y sitios web (Instagram).

## Seguridad
Servidor privado sin IP pública, salida a Internet restringida a una lista de dominios de las plataformas, TLS verificado, sin secretos en registros y acceso solo por mi red privada.

## Eliminación de datos
Para solicitar la eliminación de cualquier dato, abre una issue en <https://github.com/ValaDevs-AI/valadevs-legal/issues>; se atenderá en un plazo máximo de 30 días.

## Cambios
Los cambios se publicarán en esta misma URL con una nueva fecha.
