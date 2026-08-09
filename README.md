# Deenex · Pitch Deck

Deck de presentación de **Deenex Technologies SAS**. Un solo archivo HTML, sin dependencias ni build.

**Tus clientes son tuyos.** La infraestructura que convierte cada pedido en un cliente que vuelve.

---

## Cómo se usa

Abrí `index.html` en cualquier navegador, o entrá al link publicado.

| Tecla | Qué hace |
|---|---|
| `←` `→` `espacio` | Navegar |
| `M` | Índice de salto — útil en Q&A para ir directo a una slide de respaldo |
| `B` | Mostrar u ocultar las slides de respaldo |
| `T` | Cronómetro de escenario (el pitch son 3 minutos) |
| `E` | Editar cualquier texto en el navegador · `Ctrl+S` exporta el archivo |

## Estructura

**10 slides en vivo:** Portada · El problema · La cita · La prueba del problema · El insight · La solución · Tracción · Modelo de ingresos · Objetivo y camino · La ronda

**7 de respaldo (para Q&A):** Casos de éxito · Mercado · Proyección financiera · Adquisición · Equipo · La ronda en detalle · Competencia

## Notas para editar

- **Tipografía:** Panchang (títulos) y Bespoke Sans (cuerpo), servidas por Fontshare.
- **Paleta:** los tokens están en `:root`, arriba de todo. Regla dura: fondo blanco en todas las slides y **prohibido el naranja**, aunque figure en el manual de marca.
- **Datos:** las marcas de los gráficos van todas en un solo violeta. Los violetas claros quedan por debajo del piso de contraste de 3:1 contra blanco y desaparecen en un proyector con luz ambiente.
- **Proporciones:** el embudo, la escalera de ARPA y las barras de revenue están a escala real. Si cambiás un número, hay que recalcular el porcentaje de alto o ancho.
- **Media queries:** viven al final de la hoja de estilos. Una media query no suma especificidad, así que declarada antes la pisa la regla del componente.

## Pendientes

- Videos de testimonio de Palta y La Fábrica: poner la URL en `data-video` de cada tarjeta y se activan solas.
- Logos de las marcas en negociación.
- Serie mensual de MRR para dibujar la curva de crecimiento.
- Credenciales del equipo — la slide está hoy con contenido de ejemplo, marcado como maqueta.
