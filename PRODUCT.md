# Product

## Register

product

## Users

**Dueño / Administrador general** — propietario de AmigosLeon. Supervisa todos los negocios desde un dashboard central. Revisa reportes de rendimiento, rentabilidad por negocio y alertas críticas. Frecuentemente accede desde celular para revisiones rápidas; hace trabajo administrativo profundo desde escritorio.

**Cajero / Vendedor** — opera en el punto de venta. Registra ventas, escanea códigos de barras con lector USB, consulta stock disponible. Trabaja casi exclusivamente desde escritorio o PC fija. Necesita pantallas rápidas y sin fricción; cada segundo cuenta cuando hay clientes esperando.

**Administrador de negocio** — gestiona un negocio específico (farmacia, carwash, tienda, etc.). Administra inventario, registra gastos, supervisa a su equipo. Usa la plataforma desde escritorio durante la jornada laboral.

**Encargado de inventario** — ingresa y controla productos y stock. Tareas repetitivas y de alta frecuencia: agregar productos, actualizar cantidades, revisar alertas de bajo stock. Desktop, contexto de bodega u oficina trasera.

## Product Purpose

Panel Administrativo Multi-Negocio para AmigosLeon (Guatemala). Centraliza la operación de hasta 5 negocios distintos (farmacia, carwash, tienda, mini market, otros) bajo una sola cuenta principal. Reemplaza el caos de hojas de Excel separadas con un sistema unificado que mantiene inventario, ventas y gastos separados por negocio pero permite al dueño ver toda la empresa de un vistazo.

Módulos principales: inventario por negocio, registro de ventas con código de barras, registro de gastos, usuarios y permisos por rol, dashboard general de empresa, dashboards individuales por negocio, reportes administrativos por fecha y rango.

Contexto local: moneda en quetzales (Q), operación en Guatemala, idioma español, negocios de mediana escala con personal no técnico.

Éxito = el dueño sabe qué negocio es más rentable esta semana en 10 segundos. El cajero completa una venta en 30 segundos sin errores.

## Brand Personality

Profesional, limpio, confiable. El sistema transmite que está terminado y es serio — no una plantilla genérica ni un prototipo. Tono neutro con warmth guatemalteco sutil. No grita, no entretiene; trabaja.

## Anti-references

- **Dark mode como base** — los usuarios trabajan en entornos iluminados (tiendas, farmacias, oficinas). Base clara obligatoria.
- **Minimalismo vacío** — no puede parecer MVP sin terminar. Cada pantalla debe sentirse completa y funcional.
- **Bootstrap genérico** — sin tablas grises sin personalidad, sin cards iguales en todo, sin el aspecto de "sistema de gestión de 2015".
- **Sobrecarga de color** — no multicolor tipo e-commerce festivo. Un acento claro, los demás colores con propósito semántico (éxito, advertencia, error).
- **ERP denso tipo Odoo** — no apilamiento de formularios interminables. Densidad manejable, no aplastante.

## Design Principles

1. **Densidad con claridad** — mucha información cabe en pantalla cuando está bien organizada. Las tablas, los números y los estados deben leerse de un vistazo sin necesidad de expandir o hacer hover para entender.

2. **Roles primero** — el cajero y el dueño no tienen la misma pantalla porque no tienen el mismo trabajo. La interfaz se adapta al contexto del rol activo, no los fuerza a ignorar lo que no necesitan.

3. **Confiable antes de bonito** — los números deben ser precisos, legibles y fáciles de verificar. Un quetzal de diferencia en el reporte importa. El diseño nunca sacrifica legibilidad por estética.

4. **Contexto guatemalteco** — Q antes del número, fechas DD/MM/YYYY, terminología local (farmacia no pharmacy, carwash no car wash). El sistema habla como hablan sus usuarios, no como una traducción del inglés.

5. **Escritorio para operar, móvil para supervisar** — responsive, pero no idéntico. El dueño en el celular necesita ver métricas clave y alertas. El cajero en PC necesita flujos de venta rápidos con teclado y scanner. Distintas prioridades de layout por dispositivo.

## Accessibility & Inclusion

- WCAG AA mínimo. Contraste de texto ≥ 4.5:1 sobre fondo claro.
- Flujos de cajero compatibles con teclado + lector de código de barras USB (que actúa como teclado). Sin dependencia de mouse para el flujo de venta.
- Texto legible sin zoom en pantallas de 13" a 27". Tamaño mínimo de fuente 14px en UI operativa.
- Responsive real para móvil: el dueño revisa desde celular en entorno de poca luz o con una mano. Targets táctiles mínimo 44px.
- Sin animaciones esenciales — todo contenido visible sin necesidad de hover o transición.
