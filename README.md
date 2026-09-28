# Mapa de sistemas EcoBici

Aplicación web en Next.js para explorar el mapa de actores de EcoBici CDMX: nodos negros, líneas curvas dirigidas y agrupación suave por capa, sin cajas de subgrafo.

Tres capas:

- **Actores primarios** (interacción directa y núcleo del viaje): UF, BIC, CE, APP, TMI
- **Actores secundarios** (operación, soporte y logística): SC, PO, VR, TM, PAS
- **Actores terciarios** (regulación, entorno y soporte institucional): SEM, EMP, PAT, INF, C5, ASE

Tres flujos dirigidos: usuario, logístico-operativo e institucional. Las flechas conservan el sentido del catálogo (`→` dirigido, `↔` bidireccional, `/` alternativa, `+` coparticipación).

Puedes buscar un actor, mostrar u ocultar capas y flujos, acercar el dibujo y abrir la ficha de cada nodo con su rol y relaciones.

Sitio en GitHub Pages: [https://evrythingRETH.github.io/MapadeSistemas_App/](https://evrythingRETH.github.io/MapadeSistemas_App/)
