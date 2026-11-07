# Reportar una vulnerabilidad

No abras un issue público con detalles de seguridad.

Escribe a **seguridad@niva.mx** con:

- componente afectado (repositorio y ruta);
- versión o commit;
- pasos para reproducir;
- impacto que crees que tiene;
- si ya existe un borrador de corrección.

Compromiso de respuesta: acuse en 2 días hábiles y plan de corrección en 10 días hábiles. No incluyas datos reales de clientes ni credenciales en el reporte.

Quedan fuera de alcance: denegación de servicio, ingeniería social y pruebas sobre cuentas o datos de terceros.

## Manejo de secretos

Nunca subas llaves, tokens ni certificados. Si un secreto llega a un repositorio, considéralo comprometido: rótalo y avisa de inmediato. En los repositorios privados del plan actual el escaneo de secretos de GitHub no está disponible; la revisión es manual y en CI con `gitleaks` cuando exista el workflow.
