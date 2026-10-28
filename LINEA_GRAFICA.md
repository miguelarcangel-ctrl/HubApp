# Línea gráfica de las apps DP World Panamá

Todas las apps (Hub, Cotizador 3PL, Control de Horas, Control de Rampas, Last Mile, Alertas de Calidad y las que vengan) comparten el mismo cascarón, con **Last Mile** como molde:

- **Login** con la frase de la app en grande a la izquierda, una **escena animada propia de la app** al fondo y la tarjeta blanca a la derecha. La escena la elige el usuario para cada app.
- **Cinta superior blanca** con el botón de tres rayas, el logo, DP WORLD y el nombre de la app; a la derecha solo Instalar, Claro/Oscuro, el rol y Salir.
- **Menú desplegable lateral** con todas las secciones de la app (por ejemplo Turno, Insights y Vista TV en Control de Horas).
- **Tema claro y oscuro** en todas, con el botón de texto Claro/Oscuro (preferencia común `dpw_tema`).
- **Botón Instalar** en todas (cinta y login): cada app es instalable en PC, tableta y celular.
- **Sin íconos ni emojis**: solo texto en Barlow Condensed en mayúsculas.

La guía completa, el kit (`dpw-shell.css`, `dpw-shell.js`, escenas) y la plantilla están en el skill **`.claude/skills/linea-grafica/`** de este repo. Cada repo de app lleva una copia del skill y del kit; los cambios se hacen aquí y se vuelven a copiar.

## Tokens

| Token | Valor | Uso |
|---|---|---|
| Índigo | `#1A1060` | Botones, títulos, nav activo |
| Índigo hover | `#2A1F8F` | Hover del botón principal |
| Verde | `#00C389` | Acentos: éxito, fila activa del menú, antetítulos |
| Ámbar | `#f5a20b` | Advertencia, en desarrollo |
| Rojo | `#E8003D` | Errores y contadores |
| Fondo oscuro | `#0d0b28`, superficies `#16143d` / `#1e1c50` | Tema oscuro |
| Fondo claro | `#F2F3F8`, tarjetas blancas, bordes `#E2E8F0` | Tema claro |
| Texto | `#1B1B2F`, secundario `#64748B` | Tema claro |

Tipografía: **Barlow Condensed** 700–800 en mayúsculas para títulos, etiquetas y botones; **Barlow** para el cuerpo.

## Excepciones

- Las pantallas de TV o piso de operación pueden ser oscuras para leerse a distancia.
- Los manuales y mapas de procedimientos (`mapa-procedimientos/`) conservan su tema oscuro de documento.
