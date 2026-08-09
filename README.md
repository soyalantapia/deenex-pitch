# Deenex · Pitch Deck

Deck de presentación de **Deenex Technologies SAS**. Un solo archivo HTML, sin dependencias ni build.

**Tus clientes son tuyos.** La infraestructura que convierte cada pedido en un cliente que vuelve.

---

## Cómo se usa

Abrí `index.html` en cualquier navegador, o entrá al link publicado.

| Tecla | Qué hace |
|---|---|
| `←` `→` `espacio` | Navegar |
| `M` | Índice de salto — útil en Q&A para ir directo a una slide |
| `T` | Cronómetro de escenario (el pitch son 3 minutos) |
| `E` | Editar cualquier texto en el navegador · `Ctrl+S` exporta el archivo |
| `Inicio` `Fin` | Primera y última slide |

## Estructura

Un solo flujo de **16 slides**, sin separación entre vivo y respaldo:

Portada · El problema · La cita · La prueba del problema · El insight · La solución · Los beneficios · Tracción · El camino · Modelo de ingresos · Casos de éxito · Mercado · Adquisición · Competencia · Equipo · La ronda

Cierra en La ronda a propósito: el pedido es construir la relación con el inversor, no levantar capital hoy. Para tres minutos en escenario, el recorrido corto es Portada → El problema → La cita → El insight → La solución → Tracción → La ronda; el resto se usa en Q&A saltando con `M`.

**Los beneficios** va pegada a **La solución** a propósito: la primera explica cómo funciona el sistema y la segunda qué se lleva el que lo contrata. Sus cuatro filas son las cuatro capas del loop leídas desde el lado del cliente, así que si cambia el loop hay que cambiarlas juntas.

## Notas para editar

- **Tipografía:** Panchang (títulos) y Bespoke Sans (cuerpo), servidas por Fontshare.
- **Paleta:** los tokens están en `:root`, arriba de todo. Regla dura: fondo blanco en todas las slides y **prohibido el naranja**, aunque figure en el manual de marca.
- **Datos:** las marcas de los gráficos van todas en un solo violeta. Los violetas claros quedan por debajo del piso de contraste de 3:1 contra blanco y desaparecen en un proyector con luz ambiente.
- **Proporciones:** el embudo, la escalera de ARPA y las barras de revenue están a escala real. Si cambiás un número, hay que recalcular el porcentaje de alto o ancho.
- **Media queries:** viven al final de la hoja de estilos. Una media query no suma especificidad, así que declarada antes la pisa la regla del componente.

## Pendientes

- Faltan 5 nombres de clientes para llegar a los 15 que dice Tracción.
- Logos oficiales de las 8 marcas: hoy la grilla usa lo que había a mano.
- Serie mensual de MRR para dibujar la curva de crecimiento.
- Confirmar el número real de pipeline que muestra Adquisición.
