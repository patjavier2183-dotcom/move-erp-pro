# MOVE ERP PRO

Repositorio independiente para el ERP de MOVE.

## Fuente original
- MOVE ERP V62: archivo HTML original recuperado de respaldo.
- Objetivo: preservar la interfaz y módulos originales, sin rediseño no solicitado.
- PWA piloto: index.html, manifest.webmanifest, sw.js e iconos.

## Seguridad y despliegue
- No cargar datos reales ni publicar como sistema operativo hasta verificar autenticación, permisos y persistencia central.
- El piloto actual usa almacenamiento local; no hay sincronización multiusuario verificada.
- Cloudflare Pages debe conectarse a este repositorio privado; la rama principal será fuente de despliegues.

## Pendiente
- Incorporar archivos V62 al repositorio.
- Revisar funcionalidad de asistencia, remuneraciones, presupuestos y compras.
- Verificar instalación PWA en Android y controles de acceso.
