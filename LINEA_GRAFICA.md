# Línea gráfica de las apps DP World Panamá

Toda app nueva o existente de la plataforma (Hub, Cotizador 3PL, Control de Horas, Control de Rampas, Last Mile, Alertas de Calidad y las que vengan) sigue la línea gráfica del **Cotizador 3PL**. Si hay duda, se copia lo que hace el Cotizador.

## Tokens

| Token | Valor | Uso |
|---|---|---|
| `--blue` | `#1A1060` | Índigo principal: botones, títulos, nav activo |
| `--blue-mid` | `#2A1F8F` | Hover del botón principal |
| `--green` | `#00C389` | Acentos puntuales: éxito, indicadores, puntos de estado |
| `--orange` | `#F59E0B` | En desarrollo / advertencia |
| `--red` | `#E8003D` | Errores |
| `--ink` | `#1B1B2F` | Texto principal |
| `--mid` | `#64748B` | Texto secundario, etiquetas |
| `--border` | `#E2E8F0` | Bordes de campos y tarjetas |
| `--light` | `#F8F9FC` | Fondo de la app y de los campos |
| sombra | `0 8px 32px rgba(26,16,96,.14)` | Tarjetas destacadas |

Tipografía: **Barlow Condensed** 700–800 en mayúsculas para títulos, etiquetas y botones (`letter-spacing:.08em`); **Barlow** para el cuerpo.

## Pantalla de inicio (login o portada)
- Fondo: `linear-gradient(135deg,#1A1060 0%,#2D1B8E 50%,#1A1060 100%)`.
- Tarjeta blanca centrada: `border-radius:16px`, `padding:28px 24px`, `max-width:360px`, sombra de arriba, entra con un `slideUp` de 0.3 s.
- Logo a color sobre blanco (`logo_white.png` del repo `cotizador-dpworld`, que trae el texto en negro), 48 px de alto.
- Nombre de la app: Barlow Condensed 800, 1.1rem, `#1A1060`, mayúsculas. Debajo: "DAL · Colón Logistics Park · Panamá" en `.72rem` gris `#64748B`.
- Etiquetas: `.65rem`, 700, mayúsculas, `#64748B`.
- Campos: fondo `#F8F9FC`, borde 1.5px `#E2E8F0`, `border-radius:10px`, `padding:12px 14px`; al enfocar, borde `#1A1060`, fondo blanco y halo `0 0 0 3px rgba(26,16,96,.08)`.
- Botón principal: ancho completo, fondo `#1A1060`, `border-radius:10px`, `padding:13px`, Barlow Condensed 800 1rem en mayúsculas; hover `#2A1F8F`.
- Error: fondo `#FEE`, borde `#FCC`, texto `#E8003D`, `border-radius:8px`.
- Pie opcional: "🔒 Uso interno exclusivo · DP World Panamá" en `.65rem` gris.

## Dentro de la app
- Encabezado blanco fijo con borde inferior `#E2E8F0`, logo a la izquierda y navegación con botones Barlow Condensed en mayúsculas; el activo va en `#1A1060` con texto blanco.
- Fondo `#F8F9FC` y contenido en tarjetas blancas con borde `#E2E8F0` y `border-radius:10–16px`.
- Excepción: las pantallas de TV/piso de operación pueden ser oscuras para leerse a distancia.

Referencia viva: https://cotizador-dpworld-i7d3.vercel.app/ y el portal https://github.com/miguelarcangel-ctrl/HubApp
