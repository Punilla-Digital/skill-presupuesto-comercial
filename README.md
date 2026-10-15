# Presupuesto Comercial

Habilidad completa de Punilla Digital para crear y actualizar presupuestos y propuestas comerciales visuales. Reemplaza la versión básica de este repositorio.

## Alcance

- Problema, solución, alcance, entregables, inversión y condiciones.
- Tablas de precios con cantidades, periodicidad, descuentos e impuestos confirmados.
- Métodos de pago, financiación y condiciones adaptados a cada encargo.
- Logo y tema Punilla Digital: claro premium u oscuro premium.
- Gráfica 2D por defecto o 3D cuando se solicite.
- Iconos, imágenes, capturas y demos reales o conceptuales identificadas.
- PDF A4 vertical por defecto; PDF horizontal 16:9 a pedido.

## Archivos

- [SKILL.md](SKILL.md): flujo completo.
- [references/marca.md](references/marca.md): identidad y contactos.
- [references/condiciones.md](references/condiciones.md): importes, pagos y contratación.
- [references/visuales.md](references/visuales.md): gráficos, iconos, capturas y demos.
- [assets/punilla-digital-logo.png](assets/punilla-digital-logo.png): logo incluido.
- [assets/icon.svg](assets/icon.svg) y [agents/openai.yaml](agents/openai.yaml): icono y metadatos.

## Uso

Copiar la carpeta completa con el nombre `presupuesto-comercial` al directorio de habilidades de un agente compatible. Conservar referencias, logo e icono junto al SKILL.md. La publicación en GitHub no instala automáticamente la habilidad en ChatGPT.

Ejemplo:

> Usá Presupuesto Comercial para preparar una propuesta de sistema de gestión, con estos precios y condiciones, tema oscuro y gráfica 3D. Entregá PDF.

Aportar cliente, necesidad, alcance, importes, moneda y condiciones disponibles. Si falta un dato decisivo, generar un borrador con «A confirmar»; no inventar precios ni compromisos. Recalcular importes y separar costos iniciales, recurrentes, externos y opcionales.

## Herramientas necesarias

No incluye un generador propio. Requiere un agente con herramientas para crear PDF, renderizar y revisar todas las páginas. Las ilustraciones generadas necesitan una herramienta de imágenes; los editables requieren herramientas del formato solicitado. Las otras habilidades mencionadas son opcionales según la tarea y no están incluidas.

Los precios y ofertas deben verificarse antes de incorporarlos. Las condiciones históricas de otro cliente no se convierten en políticas generales. No enviar documentos a clientes ni publicar demos sin instrucción.

## Origen

Copia de la habilidad instalada en Complementos, publicada el 15/10/2026, con sus instrucciones, referencias y recursos. Esta publicación no modifica la habilidad instalada.

[Punilla Digital](https://punilladigital.com.ar/) · [Licencia](LICENSE)
