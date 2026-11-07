## Qué cambia

<!-- Una o dos frases. Enlace al issue o a la sección de la especificación. -->

## Fase y alcance

- Fase: <!-- 0, 1, 2… -->
- Repositorio: <!-- platform, windows-connector, .github -->
- ¿Toca la especificación (`docs/spec/`)? <!-- sí/no; si sí, qué sección -->
- ¿Agrega o cambia una decisión? <!-- enlace al ADR nuevo o a open-questions.md -->

## Terminado para cualquier PR

- [ ] Compila; lint, typecheck y pruebas pasan (pegar el comando y el resultado).
- [ ] Autenticación y autorización revisadas, con pruebas para rutas nuevas.
- [ ] Migraciones y contratos compatibles (expand/contract) y documentados.
- [ ] Logs con `request_id` y sin datos sensibles.
- [ ] Errores en español claro para el usuario (02 §8); detalle técnico solo en logs.
- [ ] Decisiones e incertidumbres registradas en `docs/decisions/`.
- [ ] Instrucciones de validación con datos sintéticos.
- [ ] Sin datos reales, secretos ni imágenes con datos reales.

## Checklist de diseño (02 §12) — obligatorio si toca interfaz

- [ ] ¿Una sola acción principal por vista?
- [ ] ¿Estados vacío, error y carga definidos?
- [ ] ¿Color con significado y siempre acompañado de texto o forma?
- [ ] ¿Verbos consistentes entre botón, toast y resultado?
- [ ] ¿Probado en tema oscuro y a 390 px?
- [ ] ¿Solo tokens y componentes de `packages/ui` (sin hex, sombras ni colores propios)?
- [ ] ¿axe-core sin violaciones serias o críticas?
- [ ] ¿Presupuestos de 02 §11 (LCP, INP, CLS, JS) medidos?

## Evidencia

<!--
Comandos ejecutados y su salida relevante. Capturas o video si es interfaz.
Para cambios de datos: fixtures usados y totales esperados.
-->

## Riesgos y bloqueos

<!-- Lo que no se pudo probar y por qué; entradas nuevas en open-questions.md. -->
