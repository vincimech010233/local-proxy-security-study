# Estudio acotado de seguridad en un proxy inverso

[English](README.md)

Ejercicio de investigación defensiva sobre cómo circula la información de identidad por una cadena de proxies aislada en local. El trabajo combinó revisión de código, un laboratorio local, controles negativos y una revisión adversarial interna.

## Estado y límites

El estudio produjo un **posible problema condicionado a un laboratorio concreto**. No se ha comunicado a ningún proveedor, no existe confirmación externa y no demuestra una vulnerabilidad general ni un impacto amplio en instalaciones reales. No se accedió a infraestructura de terceros.

Los detalles técnicos se mantienen privados mientras se decide cómo actuar con divulgación responsable. Esta página no identifica el producto afectado, su configuración ni el patrón de solicitud. No es una guía de explotación ni un aviso de proveedor.

## Evidencia

- **VERIFIED dentro del laboratorio local:** el resultado solo se observó en las versiones y la configuración probadas, junto con controles negativos.
- **INFERRED:** se desconoce su relevancia fuera del laboratorio.
- **NOT_VERIFIED:** frecuencia, impacto en producción, interpretación del proveedor e informes privados duplicados.
