# Automatización de Agentes de Inteligencia Artificial en WhatsApp para el Comercio Local de Sincelejo

**Taller #1 — Arquitectura Empresarial TI**
Corporación Universitaria del Caribe (CECAR) — Facultad de Ingeniería y Arquitectura — Ingeniería de Sistemas
Semestre 7° — Sincelejo, Sucre — 2026

**Autores:**
- Daniel Fuentes Estrada
- Tomas Alberto Arias Zabala
- Bryan Esteban Velilla Perez

---

## Índice

1. [Introducción](#introducción)
2. [Entorno](#entorno)
3. [Drivers](#drivers)
4. [Oportunidad](#oportunidad)
5. [Idea de negocio](#idea-de-negocio)
6. [Creación de la empresa](#creación-de-la-empresa)
7. [Estrategia](#estrategia)
8. [Capacidades empresariales iniciales](#capacidades-empresariales-iniciales)
9. [Organización](#organización)
10. [Modelo de negocio B2B2C](#modelo-de-negocio-b2b2c)
11. [Secuencia conceptual: Entorno, Drivers, Presión y Oportunidad](#secuencia-conceptual-entorno-drivers-presión-y-oportunidad)
12. [Cambio organizacional aplicado a H&S Tecnología y Marketing S.A.S.](#cambio-organizacional-aplicado-a-hs-tecnología-y-marketing-sas)
13. [Alineación entre estrategia y arquitectura empresarial](#alineación-entre-estrategia-y-arquitectura-empresarial)
14. [Ejemplo de desalineación entre negocio y tecnología](#ejemplo-de-desalineación-entre-negocio-y-tecnología)
15. [Relación integral de la propuesta](#relación-integral-de-la-propuesta)
16. [Respaldo cuantitativo de la propuesta](#respaldo-cuantitativo-de-la-propuesta)
17. [Conclusión](#conclusión)
18. [Referencias bibliográficas](#referencias-bibliográficas)
19. [Anexo visual](#anexo-visual)

---

## Introducción

El trabajo desarrolla el Taller #1 de la asignatura Arquitectura Empresarial TI, orientado al análisis de la transformación digital del comercio local de Sincelejo. Parte de una problemática real: una alta proporción de comerciantes informales e independientes que, aunque usan herramientas digitales (WhatsApp, redes sociales, pagos electrónicos), lo hacen de forma desarticulada, lo que dificulta la gestión de pedidos, pagos, inventarios y domicilios.

Con base en cifras del DANE y otras fuentes, se identifican los factores del entorno y los drivers que presionan a los pequeños negocios a digitalizarse. De ahí se plantea una oportunidad de negocio concreta: implementar agentes de inteligencia artificial en WhatsApp que permitan automatizar la atención al cliente, la toma de pedidos y la confirmación de pagos.

El documento cierra con la creación de la empresa encargada de desarrollar la solución, su estrategia, sus capacidades empresariales iniciales y la organización de sus roles fundadores, aplicando los conceptos de Arquitectura Empresarial para conectar negocio, procesos, información, aplicaciones y tecnología.

---

## Entorno

Se identifican cuatro tipos de entorno que influyen sobre el comercio local de Sincelejo:

| Tipo de entorno | Descripción | Impacto sobre el caso |
|---|---|---|
| **Tecnológico** | El comercio ya usa herramientas digitales (WhatsApp, redes sociales, pagos electrónicos como Nequi/Daviplata), pero cada una funciona por separado, sin ningún sistema que las conecte. | Genera desorden: no hay control de inventario en tiempo real, los pedidos se pierden entre chats y verificar pagos o coordinar domicilios depende enteramente del comerciante. Es la principal oportunidad de mejora tecnológica. |
| **Económico** | Según el DANE, Sincelejo es la ciudad con mayor informalidad laboral del país (65,7 % en el trimestre abril-junio de 2026, muy por encima de Bogotá con 33,3 %), mientras que a nivel nacional los ingresos de los micronegocios crecieron 9,8 % frente al primer trimestre de 2025 (EMICRON). | El sector mueve dinero real y está en expansión, pero al operar informalmente no accede a crédito, herramientas tecnológicas robustas ni formación empresarial, lo que limita su capacidad de escalar. |
| **Social** | Un porcentaje muy alto de los micronegocios son trabajadores por cuenta propia: negocios familiares o unipersonales donde el mismo dueño vende, atiende WhatsApp, cobra y entrega. | La falta de personal especializado hace que digitalizar procesos parezca un trabajo extra en vez de una solución, por lo que la adopción tecnológica ha sido parcial y desorganizada. |
| **Competitivo** | Aunque el comercio local no compite directamente con grandes plataformas (Rappi, marketplaces nacionales), estas marcan el estándar de lo que un cliente espera hoy: rapidez, seguimiento del pedido y pago fácil. | Los micronegocios que no ofrezcan una experiencia similar, aunque sea simplificada, corren el riesgo de perder clientes frente a negocios más grandes o digitalizados. |

---

## Drivers

Fuerzas del entorno que presionan a los pequeños comercios de Sincelejo a cambiar su forma de operar:

| Driver | Explicación | Impacto |
|---|---|---|
| **Crecimiento acelerado de los micronegocios sin digitalización** | Los ingresos de los micronegocios del país crecieron 9,8 % frente al primer trimestre de 2025 (DANE, EMICRON), pero siguen operando con WhatsApp y transferencias manuales, sin ningún sistema que ordene la información. | Obliga a buscar soluciones que ordenen pedidos, pagos e inventario antes de que el desorden limite ese crecimiento. |
| **Adopción acelerada de IA en las pymes colombianas** | El 66 % de las micro, pequeñas y medianas empresas de Colombia ya integraba IA en sus operaciones en 2025 (frente al 29 % de 2024), y se proyecta que en 2026 el 80 % de las pymes tendrá algún nivel de adopción. | Refuerza que el momento de mercado es propicio: los comerciantes de Sincelejo que aún no automatizan su atención quedarán rezagados frente a negocios similares que ya lo están haciendo. |
| **Persistencia de la informalidad empresarial** | Sincelejo tiene una de las tasas de informalidad empresarial más altas del país; la mayoría de los negocios no cuenta con sistemas, registros ni procesos formales. | Presiona a crear soluciones simples y de bajo costo, adaptadas a negocios informales, en lugar de sistemas empresariales complejos. |
| **Estándar de experiencia digital impuesto por plataformas grandes** | Apps como Rappi o los marketplaces acostumbraron a los clientes a pedidos rápidos, pago fácil y seguimiento en tiempo real. | Motiva a los pequeños comercios a ofrecer una experiencia similar, aunque simplificada, para no perder clientes frente a negocios más digitalizados. |

---

## Oportunidad

De la combinación del entorno tecnológico desarticulado, la informalidad persistente, el crecimiento de los micronegocios y el estándar de experiencia impuesto por las grandes plataformas, surge la oportunidad de crear un agente de inteligencia artificial en WhatsApp que ayude a automatizar la atención al cliente, la toma de pedidos y la confirmación de pagos para el comercio local de Sincelejo.

---

## Idea de negocio

Desarrollar un agente de inteligencia artificial capaz de responder de forma autónoma en WhatsApp, adaptado a la realidad de los micronegocios de Sincelejo:

| Elemento | Descripción |
|---|---|
| **Cliente objetivo** | Micronegocios y comerciantes independientes de Sincelejo (tiendas de barrio, ventas por WhatsApp, negocios del Nuevo Mercado) que atienden a sus clientes por WhatsApp sin personal dedicado a esa tarea. |
| **Problema** | El dueño del negocio atiende solo su WhatsApp: responde precios, toma pedidos, coordina pagos y domicilios de forma manual, perdiendo tiempo y clientes cuando no puede responder con rapidez. |
| **Propuesta de valor** | Un agente de IA que responde automáticamente en WhatsApp: brinda información de catálogo y precios, toma pedidos y confirma pagos, disponible las 24 horas, sin que el comerciante deba estar pendiente del chat todo el tiempo. |
| **Forma de ingresos** | Suscripción mensual de bajo costo por negocio, bajo un modelo tipo SaaS, con planes diferenciados según el volumen de mensajes o pedidos gestionados. |
| **Factor diferenciador** | La solución se adapta a la informalidad del comercio local: no requiere sistemas complejos, se implementa directamente sobre el WhatsApp que el comerciante ya usa, y tiene un precio accesible pensado para micronegocios. |

---

## Creación de la empresa

Se constituye **H&S Tecnología y Marketing S.A.S.**, que amplía su portafolio existente (marketing digital, desarrollo web y soluciones tecnológicas personalizadas) incorporando una línea especializada en automatización mediante agentes de inteligencia artificial.

| Ítem | Descripción |
|---|---|
| **Razón social** | H&S Tecnología y Marketing S.A.S. |
| **Misión** | Brindar soluciones tecnológicas y de marketing digital a pequeñas empresas, con enfoque especializado en automatización mediante agentes de IA en WhatsApp para el comercio local de Sincelejo. |
| **Visión** | Ser en el año 2030 la empresa referente en el departamento de Sucre en soluciones digitales para pequeños negocios, liderando la adopción de inteligencia artificial en el comercio local de la región Caribe. |
| **Propósito** | Democratizar el acceso a la tecnología, ofreciendo desde automatización con IA hasta desarrollo web y marketing digital, adaptado a la realidad de negocios pequeños e informales. |

---

## Estrategia

La estrategia inicial busca entrar al mercado de micronegocios de Sincelejo mediante una propuesta accesible y de fácil implementación:

| Ítem | Descripción |
|---|---|
| **Estrategia** | Penetrar el mercado de micronegocios de Sincelejo ofreciendo un agente de IA en WhatsApp fácil de implementar y de bajo costo, posicionándose como la opción accesible frente a soluciones tecnológicas complejas o costosas. |
| **Objetivo estratégico 1** | Vincular al menos 25 micronegocios de Sincelejo al servicio durante el primer año de operación. |
| **Objetivo estratégico 2** | Lograr que el 80 % de los clientes reduzcan su tiempo de respuesta a pedidos por WhatsApp en al menos un 50 %. |
| **Objetivo estratégico 3** | Consolidar alianzas con la Cámara de Comercio de Sincelejo y con la administración del Nuevo Mercado para facilitar la adopción del servicio entre comerciantes. |
| **Ventaja competitiva** | Precio accesible y adaptado a la realidad de negocios informales, combinado con una implementación simple sobre una herramienta que el comerciante ya usa (WhatsApp), sin curva de aprendizaje ni inversión en nuevos sistemas. |

---

## Capacidades empresariales iniciales

Capacidades que la organización debe ser capaz de ejecutar, independientemente de la tecnología específica que utilice:

| Capacidad empresarial | Descripción | Relación con la estrategia |
|---|---|---|
| **Desarrollo y mantenimiento de agentes de IA** | Diseñar, entrenar y ajustar agentes conversacionales según el negocio de cada cliente (catálogo, tono de respuesta, reglas del negocio). | Es la base del producto; sin esta capacidad no existe el servicio ofrecido al mercado. |
| **Onboarding e implementación simple** | Conectar rápidamente el agente de IA al WhatsApp del comerciante, minimizando la fricción técnica del proceso. | Soporta directamente la ventaja competitiva de ser una solución fácil de implementar. |
| **Soporte y atención al cliente** | Resolver de forma ágil las dudas, fallos o ajustes solicitados por los comerciantes que usan el servicio. | Genera confianza y retención de clientes, clave para alcanzar la meta de 25 micronegocios vinculados en el primer año. |
| **Gestión comercial y alianzas** | Vender el servicio y construir relaciones institucionales con gremios como la Cámara de Comercio y el Nuevo Mercado. | Está ligada directamente al objetivo estratégico de consolidar alianzas institucionales. |

---

## Organización

Al inicio, H&S Tecnología y Marketing contará con cuatro roles principales, cada uno alineado con una capacidad empresarial:

| Rol | Responsabilidad | Contribución a la organización |
|---|---|---|
| **CEO / Experto en Marketing (founder)** | Dirigir la empresa, definir la estrategia comercial, posicionar la marca y gestionar alianzas con gremios como la Cámara de Comercio y el Nuevo Mercado. | Lidera la visión del negocio y asegura que el producto llegue a los clientes correctos. |
| **CTO / Desarrollador Full Stack (founder)** | Diseñar, desarrollar y mantener los agentes de IA y la plataforma tecnológica que los soporta, incluyendo la integración con WhatsApp. | Sostiene la capacidad técnica central sobre la cual se construye todo el producto. |
| **Experto en Infraestructura TI (founder)** | Administrar servidores, APIs, seguridad de la información y disponibilidad del servicio (uptime y escalabilidad). | Garantiza que el servicio funcione de forma estable y segura para todos los clientes. |
| **Gestor / Asesor Comercial (founder)** | Buscar nuevos clientes, asesorar a los comerciantes sobre el uso del servicio y cerrar nuevas suscripciones. | Impulsa el crecimiento de la empresa hacia la meta de 25 micronegocios vinculados en el primer año. |

---

## Modelo de negocio B2B2C

La propuesta de H&S Tecnología y Marketing S.A.S. se maneja como un modelo **B2B2C** (Business to Business to Consumer), ya que la empresa ofrece la solución a los micronegocios y estos la utilizan para atender a sus propios clientes.

Primero está **H&S Tecnología y Marketing**, que desarrolla y mantiene el agente de IA. Después está el **comerciante o micronegocio**, que paga por el servicio y lo usa en su negocio. Finalmente está el **consumidor**, que interactúa con el agente por WhatsApp para consultar productos, hacer pedidos o recibir información.

**Relación:** H&S Tecnología y Marketing → Micronegocio / comerciante → Cliente final

---

## Secuencia conceptual: Entorno, Drivers, Presión y Oportunidad

El caso sigue una secuencia sencilla: primero se observa lo que pasa en el entorno, después se identifican los drivers que generan presión para cambiar y finalmente se plantea una oportunidad.

**Entorno → Drivers → Presión para actuar → Oportunidad**

El comercio local usa diferentes herramientas digitales, pero de forma separada. A esto se suman la informalidad, el crecimiento de los micronegocios y las expectativas de los clientes. Estas situaciones generan presión para mejorar la atención y organizar mejor los pedidos y pagos. De ahí surge la oportunidad de crear un agente de IA en WhatsApp que automatice parte de estas tareas.

---

## Cambio organizacional aplicado a H&S Tecnología y Marketing S.A.S.

La propuesta no consiste solamente en instalar una tecnología; también implica cambios en la forma de trabajar de la empresa y de los comerciantes que usen el servicio:

- **Cambio operativo o de procesos:** la atención manual pasa a un proceso organizado: cliente → WhatsApp → agente de IA → consulta de catálogo → pedido → confirmación → aviso al comerciante. Así el comerciante no responde personalmente todas las preguntas y puede concentrarse en los casos que sí requieren su intervención.
- **Cambio tecnológico:** se incorporan agentes de IA, integración con WhatsApp, APIs y una infraestructura que mantenga el servicio disponible, al servicio de los objetivos del negocio.
- **Cambio estructural:** las responsabilidades se distribuyen entre los roles de dirección y marketing, desarrollo, infraestructura y gestión comercial, para que el servicio no dependa de una sola persona.
- **Cambio cultural:** el comerciante pasa de creer que debe responder cada mensaje personalmente a entender que algunas tareas pueden atenderse automáticamente, dejando la atención humana para los casos que realmente la necesiten.
- **Cambio estratégico:** H&S Tecnología y Marketing amplía sus servicios y se especializa en automatización para micronegocios de Sincelejo, diferenciándose por ser sencilla, económica y funcionar sobre una herramienta que los comerciantes ya conocen: WhatsApp.

---

## Alineación entre estrategia y arquitectura empresarial

Para llevar la estrategia a la práctica, se relaciona con las capacidades, procesos, datos, aplicaciones y tecnología que necesita la empresa:

| Nivel | Aplicación en el caso |
|---|---|
| **Estrategia** | Entrar al mercado de micronegocios de Sincelejo con una solución de automatización accesible. |
| **Capacidades** | Desarrollo de agentes de IA, implementación, soporte y gestión comercial. |
| **Procesos** | Atención, catálogo, toma de pedidos, confirmación de pagos y soporte. |
| **Datos** | Clientes, productos, precios, disponibilidad, pedidos y configuración del agente. |
| **Aplicaciones** | Agente de IA, integración con WhatsApp y componentes para gestionar pedidos. |
| **Tecnología** | Servicios de IA, APIs, base de datos e infraestructura para mantener el servicio. |

---

## Ejemplo de desalineación entre negocio y tecnología

Una tecnología puede funcionar bien técnicamente y aun así no ayudar completamente al negocio. Por ejemplo, si el agente responde los mensajes de WhatsApp, pero después el comerciante tiene que copiar manualmente cada pedido a otro sistema, todavía queda bastante trabajo manual: la solución tecnológica funciona, pero no está totalmente alineada con el objetivo de reducir el tiempo de atención.

Una solución más alineada sería que el agente pudiera registrar el pedido, consultar la información disponible y dejar la información organizada para el comerciante. Esto muestra que no basta con implementar inteligencia artificial: la tecnología debe ayudar de verdad a cumplir los objetivos planteados para el negocio.

---

## Relación integral de la propuesta

De forma resumida, el caso puede verse así:

**Entorno → Drivers → Presión de cambio → Oportunidad → Idea de negocio → Estrategia → Capacidades → Procesos → Datos → Aplicaciones → Tecnología**

Esta relación permite ver que la inteligencia artificial no es el punto de partida del proyecto. Primero existe una necesidad del comercio local y, a partir de ella, se propone una solución tecnológica que busca apoyar la estrategia.

---

## Respaldo cuantitativo de la propuesta

Estudios de mercado de 2026 sobre IA y WhatsApp en pymes latinoamericanas ofrecen cifras que sustentan la propuesta de valor y los objetivos estratégicos planteados:

| Indicador | Dato | Relevancia para el caso |
|---|---|---|
| Velocidad de respuesta | Responder en menos de un minuto multiplica hasta por 8 la tasa de conversión frente a la competencia. | Respalda el objetivo estratégico de reducir en un 50 % el tiempo de respuesta a pedidos por WhatsApp. |
| Valor promedio del pedido | El uso de agentes de IA en WhatsApp Business incrementa el valor promedio del pedido (AOV) en un 19,2 % en retail. | Sustenta el argumento de que automatizar la atención no solo ahorra tiempo, sino que también puede aumentar los ingresos del comerciante. |
| Adopción de IA en pymes colombianas | El 66 % de las mipymes del país ya integraba IA en sus operaciones en 2025, con proyección de 80 % de adopción en 2026. | Confirma que el mercado objetivo (micronegocios de Sincelejo) está entrando a una etapa de adopción masiva, lo que valida el momento de entrada de H&S Tecnología y Marketing. |

---

## Conclusión

El análisis del comercio local de Sincelejo evidencia una paradoja: un sector económicamente dinámico, con crecimiento sostenido en ingresos, pero que opera bajo altos niveles de informalidad y con herramientas digitales desarticuladas entre sí. Esta situación limita la capacidad de los micronegocios para escalar, atender bien a sus clientes y aprovechar los datos que generan día a día.

Frente a este panorama, la propuesta de H&S Tecnología y Marketing —un agente de inteligencia artificial en WhatsApp orientado a micronegocios— responde directamente a los drivers identificados: ofrece una solución simple y económica, compatible con la informalidad del sector, y capaz de igualar parte del estándar de servicio que hoy imponen las grandes plataformas digitales.

El ejercicio también permitió aplicar de forma práctica los conceptos propios de la Arquitectura Empresarial, conectando el entorno y los drivers con una oportunidad concreta, y esta a su vez con una idea de negocio, una estructura organizacional y unas capacidades empresariales coherentes entre sí. Esta conexión entre negocio, procesos, información, aplicaciones y tecnología es precisamente el aporte central que la Arquitectura Empresarial ofrece a la transformación digital del comercio local.

---

## Referencias bibliográficas

- El Tiempo. (2026, 6 de julio). *DANE publicará las nuevas cifras de informalidad laboral de marzo-mayo de 2026: Sincelejo mantiene la tasa más alta del país*. https://www.eltiempo.com/economia/sectores/dane-publicara-las-nuevas-cifras-de-informalidad-laboral-de-marzo-mayo-de-2026-sincelejo-mantiene-la-tasa-mas-alta-del-pais-desde-el-ultimo-reporte-3569404
- El Nuevo Siglo. (2025, 1 de octubre). *Informalidad de micronegocios quedó estancada en 90,2 % en 2024*. https://www.elnuevosiglo.com.co/economia/informalidad-de-micronegocios-quedo-estancada-en-902-en-2024
- La República. (2026). *Más de 90 % de los micronegocios pertenecen a trabajadores por cuenta propia*. https://www.larepublica.co/economia/mas-de-90-de-los-micronegocios-pertenecen-a-trabajadores-por-cuenta-propia-4449020
- Banco de la República. (2026). *Nueva evidencia sobre la informalidad laboral y empresarial en Colombia*. Reportes del Emisor / ESPE. https://investiga.banrep.gov.co/es/espe/espe108
- Universidad del Norte. (s.f.). *Nuevo mercado público de Sincelejo* [Repositorio Manglar]. https://manglar.uninorte.edu.co/handle/10584/7821
- Departamento Administrativo Nacional de Estadística [DANE]. (2025). *Encuesta de Micronegocios (EMICRON) — IV trimestre de 2025*. https://www.dane.gov.co/files/operaciones/EMICRON/pres-EMICRON-IVtrim2025.pdf
- Infobae. (2026, 14 de agosto). *Más de la mitad de los trabajadores de Colombia no tiene garantizada una pensión: el Dane midió 54,5 % de informalidad*. https://www.infobae.com/colombia/2026/08/14/mas-de-la-mitad-de-los-trabajadores-de-colombia-no-tiene-garantizada-una-pension-el-dane-midio-545-de-informalidad/
- El Espectador. (2026, 30 de mayo). *Así va la economía de los pequeños: ¿cuántos micronegocios tiene el país y cuánto facturan?*. https://www.elespectador.com/economia/asi-va-la-economia-de-los-pequenos-cuantos-micronegocios-tiene-el-pais-y-cuanto-facturan-noticias-colombia/
- Sense Digital. (2026, 14 de abril). *Automatización con IA para PYMES Colombianas: La Guía Definitiva 2026*. https://sense-digital.co/blog/posts/2026-04-14-automatizacion-ia-pymes-colombia.html
- TecnoChat Blog. (2026). *WhatsApp + IA en 2026: Pymes LATAM venden 8x más respondiendo en 1 minuto*. https://tecnochat.com/blog/ia/whatsapp-ia-en-2026-pymes-latam-venden-8x-mas-respondiendo-en-1-minuto

---

## Anexo visual

Imágenes de referencia sugeridas para ilustrar el documento (por ejemplo, en una versión de presentación o en Word), organizadas por sección:

- **Entorno / Idea de negocio:** fotografías de tiendas de barrio colombianas atendiendo pedidos por WhatsApp, mostrando la coexistencia de la venta tradicional con herramientas digitales.
- **Idea de negocio / Capacidades empresariales:** ilustraciones o fotografías conceptuales de un chatbot o agente de inteligencia artificial conversando con un cliente, representando la automatización de la atención.
- **Introducción / Alianzas comerciales:** fotografías del Mercado Público de Sincelejo, como referencia directa al espacio comercial mencionado como aliado estratégico de la empresa.

*Nota: estas imágenes se mostraron como referencia visual en la conversación, pero no quedan incrustadas como archivo dentro de este README; para incluirlas físicamente en el documento (por ejemplo, al pasarlo a Word o PowerPoint) se recomienda descargarlas de un banco de imágenes libres de derechos (Unsplash, Pexels) o usar fotografías propias del Mercado Público y del comercio local de Sincelejo.*
