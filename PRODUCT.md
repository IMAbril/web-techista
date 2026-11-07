# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Propietarios de viviendas unifamiliares, inquilinos, administradores de consorcios/PHs y dueños de locales comerciales o galpones en Argentina que enfrentan goteras, filtraciones recurrentes tras tormentas o que planifican un recambio o construcción de techo nuevo (chapa, tejas o losa).

## Product Purpose

Página web de alta conversión orientada a captar clientes calificados y generar consultas directas por WhatsApp y llamadas telefónicas para un profesional techista / zinguería. Su propósito es transformar la urgencia o inquietud del vecino en un contacto concreto, resolviendo la desconfianza habitual del rubro mediante demostración de oficio, materiales de primera línea y garantía escrita.

## Positioning

Techista especializado y zinguería de raíz sin parches improvisados. Frente a soluciones provisorias que vuelven a lloverse en la siguiente tormenta, la propuesta se basa en solucionar el origen real del agua: babetas amuradas y selladas, pendientes y canaletas calculadas, materiales oficiales (Ternium Cincalum calibre 25, selladores poliuretánicos Sika y membranas Weber) con visita de diagnóstico sin cargo y garantía escrita por contrato.

## Operating Context

- **Situación del usuario:** Consulta frecuentemente desde el teléfono celular durante o después de un día de lluvia, con urgencia por evitar mayores daños en cielorrasos, pintura o instalaciones eléctricas, o evaluando presupuestos para encarar una obra planificada.
- **Situación del techista:** Trabaja en obra, arriba de techos o manejando con herramientas y escaleras. Necesita recibir consultas filtradas y ordenadas (qué problema hay, tipo de techo/propiedad, nivel de apuro y localidad exacta) para responder rápido sin perder tiempo en mensajes ambiguos.

## Capabilities and Constraints

- **Formulario multipaso interactivo (3 pasos):** Flujo guiado táctil en JavaScript nativo que clasifica el trabajo, la propiedad y la urgencia, armando el mensaje listo para enviar al WhatsApp del techista.
- **Botón de llamada rápida siempre visible:** Acceso telefónico directo para urgencias en días de temporal.
- **Configuración centralizada (`DATOS_NEGOCIO`):** Permite adaptar nombre del negocio, número de teléfono, WhatsApp, localidades de cobertura y años de garantía en un solo bloque sin tocar la estructura HTML.
- **Arquitectura estática pura:** HTML5 semántico y Tailwind CSS sin dependencias de backend, base de datos ni servidores dinámicos, garantizando máxima velocidad de carga en redes móviles 4G/5G.

## Brand Commitments

- **Tono de voz:** Directo, transparente, serio y de oficio calificado; sin tecnicismos vacíos ni promesas engañosas.
- **Identidad visual:** Estilo industrial y de construcción noble (azul naval profundo, acentos en naranja de seguridad y tonos acero/zinc) con tipografía legible y sobria.
- **Flexibilidad geográfica:** Estructura modular adaptable para personalizar con el nombre y localidad de cualquier techista de Argentina.

## Evidence on Hand

- **Fotografías reales documentales en `public/img/`:**
  - `hero-techista.jpg`: Techista profesional en altura instalando chapa cincalum con herramientas de trabajo.
  - `obra1-antes.jpg` y `obra1-despues.jpg`: Recambio de cubierta de chapa oxidada por Ternium Cincalum nueva.
  - `obra2-antes.jpg` y `obra2-despues.jpg`: Impermeabilización de terraza/losa con membrana asfáltica termosellada.
  - `obra3-antes.jpg` y `obra3-despues.jpg`: Restauración de desagües con zinguería y canaletas a medida.
- **Documentación de acompañamiento en `docs/`:** Guías de funcionamiento, checklist de datos y fotos del techista, y manual para cierre de presupuestos.

## Product Principles

1. **Fricción cero hacia el contacto:** Cada sección y llamado a la acción debe conducir de manera natural a WhatsApp o a una llamada directa con un solo toque.
2. **Confianza demostrada, no prometida:** La credibilidad se construye mostrando obras reales de antes y después, explicando por qué fallan los parches y respaldando con garantía escrita.
3. **Calificación mutua de la consulta:** El calculador de 3 pasos ahorra tiempo tanto al cliente como al techista al ordenar los datos antes de iniciar la conversación.
4. **Resistencia técnica y liviandad:** La web debe ser liviana, veloz y completamente funcional bajo cualquier dispositivo móvil y conexión inestable.
