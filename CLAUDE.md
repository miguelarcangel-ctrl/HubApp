# HubApp — Portal de Aplicaciones DP World Panamá

Toda app de la plataforma, incluida cualquiera nueva y este mismo portal, sigue el skill `.claude/skills/linea-grafica/` (resumen en `LINEA_GRAFICA.md`): molde Last Mile, login con escena animada propia de la app, cinta superior blanca, menú desplegable lateral y sin íconos ni emojis. Antes de crear el login de una app nueva, pregúntale al usuario qué animación quiere. El kit vive aquí; al cambiarlo, vuelve a copiarlo a cada repo de app. Al agregar una app al portal, súmala al arreglo `APPS` de `index.html` (también aparece sola en el menú).

## Publicar cambios
El dueño del repo autoriza de forma permanente, en cualquier sesión: al terminar un cambio, subirlo a una rama, abrir el pull request a `main` y fusionarlo sin pedir confirmación, siempre que las pruebas y el despliegue de vista previa de Vercel estén en verde. Si algo falla, se arregla antes de fusionar; si no se puede, se avisa sin fusionar.
