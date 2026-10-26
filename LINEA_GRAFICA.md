# Línea gráfica de las apps DP World Panamá

Hay dos estilos, cada uno con su uso:

- **Apps** (Cotizador 3PL, Control de Horas, Control de Rampas, Last Mile, Alertas de Calidad y las que vengan): línea gráfica del **Cotizador 3PL**, descrita abajo. Si hay duda, se copia lo que hace el Cotizador.
- **Hub y mapas de procedimientos / manuales**: tema oscuro del **Mapa de Procedimientos** (ver la última sección).

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

## Hub y mapas de procedimientos (tema oscuro)
- Fondo `#0d0b28`; superficies `#16143d`; tarjetas internas `#1e1c50`; resalte `#252368`. Bordes blancos al 5 %, 10 % y 18 %. Texto blanco, secundario al 68 % y terciario al 42 %.
- Barra superior fija `#16143d` con el logo para fondo oscuro (`assets/dpworld-logo-fondo-oscuro.png`), un separador vertical, título en Barlow Condensed 700 mayúsculas y subtítulo de 12 px; a la derecha, buscador en píldora.
- Portada con degradado `#16143d → #0d0b28`: antetítulo verde `#00C389` de 13 px con tracking `.14em`, título Barlow Condensed 800 de 28–44 px y párrafo al 68 %.
- Tarjetas `#16143d` con borde al 10 % y `border-radius:14px`; ícono en cuadro de 46 px con fondo de color al 15 % (verde, azul `#0099e6`, violeta `#b3b0ff`, ámbar `#f5a20b`).
- Botón principal en píldora verde `#00C389` con texto `#06291e`; secundarios en píldora `#1e1c50`.
- Referencias: `index.html` (el hub) y `mapa-procedimientos/index.html` de este repo.

Referencia viva: https://cotizador-dpworld-i7d3.vercel.app/ y el portal https://github.com/miguelarcangel-ctrl/HubApp
