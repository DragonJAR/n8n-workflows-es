[🌐 Versión en español](https://github.com/DragonJAR/n8n-workflows-es/blob/main/README.md) | [🌐 English Version](https://github.com/DragonJAR/n8n-workflows-es/blob/main/README-ENGLISH.md) | [🖥️ Mejor hosting n8n](https://djar.co/hostingn8n)

[📲 Noticias Diarias de Inteligencia Artificial gratis en tu WhatsApp](https://djar.co/iawz)


# 🧠 Colección de Flujos de Trabajo de n8n

Este repositorio es un **fork** de la iniciativa original de [@Zie619](https://github.com/Zie619/n8n-workflows), quien recopiló flujos de trabajo (workflows) de n8n procedentes de diversas fuentes, tales como:

- El sitio oficial de [n8n.io](https://n8n.io/) y su foro comunitario.  
- Ejemplos compartidos públicamente en GitHub, blogs y otros sitios web.

El propósito de este repositorio es ofrecer un recurso consolidado para inspirarte, facilitar tu aprendizaje y permitir la reutilización de workflows en tus propios proyectos de n8n.


## 📂 Mejoras Implementadas

- **Descripciones en español**: Cada archivo `.json` fue analizado y se le asignó una descripción clara en español, basada en las acciones que realiza.  
- **Eliminación de duplicados**: Se verificó y validó el hash único de cada archivo para detectar y eliminar workflows duplicados, garantizando que cada flujo de trabajo sea único en contenido.  
- **Renombrado de archivos**: Se actualizaron los nombres de los archivos para que describan con mayor precisión su funcionalidad principal, facilitando su búsqueda y selección.


## 🛠 Instrucciones de Uso

Para importar cualquier flujo de trabajo en tu instancia de n8n, sigue estos pasos:

1. Abre tu instancia de n8n.  
2. Pulsa el menú “Importar” (☰ → Importar workflow).  
3. Selecciona el archivo `.json` deseado desde la carpeta `workflows`.  
4. Revisa y ajusta las credenciales o URLs de los webhooks según sea necesario.  
5. Guarda y ejecuta el flujo de trabajo.
6. [Si no encuentras el flujo que necesitas, puedes usar este Custom GPT para que te ayude a encontrarlo o a resolver cualquier problema que tengas con N8N.](https://chatgpt.com/g/g-6840a79abd348191966dd06abd7236c8-asistente-de-flujos-n8n).
7. También puedes chatear con este repositorio usando [https://gitmcp.io/DragonJAR/n8n-workflows-es/chat](https://gitmcp.io/DragonJAR/n8n-workflows-es/chat)

## 🖥️ Servidor MCP (Model Context Protocol)

El servidor MCP de este repositorio, para que puedas interactuar con esta gran base de datos de conocimiento con flujos de n8n documentados, es:

`https://gitmcp.io/DragonJAR/n8n-workflows-es`

[Aquí encontrarás las instrucciones para usarlo en Cursor, Claude Desktop, Windsurf, VSCode, Cline o Highlight AI](https://gitmcp.io/DragonJAR/n8n-workflows-es).

## 🤝 Contribución

Si descubriste un workflow interesante o desarrollaste uno propio, ¡anímate a contribuir a esta colección! Solo ten en cuenta:

- **Nombre descriptivo**: Elige un nombre de archivo que refleje claramente la función principal del workflow.  
- **Mención de la fuente**: Si el flujo de trabajo proviene de otra fuente, incluye un comentario breve al inicio del archivo indicando su origen.

Para proponer contribuciones, abre un pull request con tu nuevo workflow o mejora.

## ⏯️ Manel aporta esta excelente explicación en video sobre el repositorio.

[![Agradecimiento a Manelautomatic](https://i.imgur.com/fq4Ef0N.png)](https://www.youtube.com/watch?v=9haKti-edOE "Gracias a Manelautomatic por explicar en video el repositorio")

## ⚠️ Aviso

Todos los workflows aquí compartidos se proporcionan tal cual. **Antes de emplearlos en un entorno de producción, inspecciónalos y pruébalos en un entorno controlado**. Asegúrate de entender completamente cada nodo, credencial y enlace para evitar posibles errores o brechas de seguridad.


## 📋 Listado de Workflows

### Integración y Automatización de CRM y Ventas

- **[3115-hdw-lead-management.json](workflows/3115-hdw-lead-management.json)**
  - **Descripción:** Flujo automático para la gestión de leads en LinkedIn que incluye búsqueda, enriquecimiento de datos, análisis y scoring de contactos utilizando APIs como HDW y OpenAI, con integración con Google Sheets para mantener un registro y seguimiento.
  - **Complejidad:** Alta (92 nodos)

- **[2931-linkedin-leads-enrichment.json](workflows/2931-linkedin-leads-enrichment.json)**
  - **Descripción:** Flujo automatizado para extraer y enriquecer datos de leads de LinkedIn usando Apollo.io y RapidAPI, con manejo de bases de datos en Google Sheets. Incluye la obtención de perfiles, correo electrónico, validación, resumen de posts y actualización del estado.
  - **Complejidad:** Alta (66 nodos)

- **[3157-test-webhooks-n8n-postbin-example.json](workflows/3157-test-webhooks-n8n-postbin-example.json)**
  - **Descripción:** Este flujo permite probar webhooks en n8n utilizando PostBin y BambooHR sin necesidad de modificar la variable WEBHOOK_URL. Crea una bin en PostBin, registra un webhook en BambooHR, prueba su funcionalidad y notifica a Slack sobre nuevos empleados.
  - **Complejidad:** Alta (58 nodos)

- **[0865-bamboo-hr-ai-chatbot.json](workflows/0865-bamboo-hr-ai-chatbot.json)**
  - **Descripción:** Este flujo es un chatbot potenciado por IA para responder preguntas sobre políticas corporativas, beneficios y procedimientos laborales utilizando documentos cargados desde BambooHR como fuente de información. Implementa búsqueda vectorial con OpenAI, memoria contextual (window buffer memory), y herramientas de empleado lookup que permiten a la IA buscar contactos internos o departamentos para facilitar las respuestas.
  - **Complejidad:** Alta (50 nodos)

- **[0954-bamboo-hr-ai-chatbot.json](workflows/0954-bamboo-hr-ai-chatbot.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de HR acceder e interpretar información sobre políticas y beneficios corporativos mediante la integración con el almacenamiento vectorial en Supabase. También facilita búsquedas de empleados específicos o departamentos para contactos relevantes.
  - **Complejidad:** Alta (50 nodos)

- **[1444-bamboohr-ai-powered-company-policies.json](workflows/1444-bamboohr-ai-powered-company-policies.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos, gestión de leads utilizando OpenAI/GPT, Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (50 nodos)

- **[2889-linkedin-monitor.json](workflows/2889-linkedin-monitor.json)**
  - **Descripción:** Este flujo automatiza la monitoreo de perfiles en LinkedIn y actualiza una hoja de cálculo Google Sheets con información de clientes. Obtiene listas de propietarios de HubSpot, busca perfiles en LinkedIn, compara datos y envía notificaciones por correo electrónico si hay cambios.
  - **Complejidad:** Alta (46 nodos)

- **[1511-ai-agent-for-n8n-creators.json](workflows/1511-ai-agent-for-n8n-creators.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, extracción de datos, generación de contenido, monitoreo, reportes, gestión de leads utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (43 nodos)

- **[3274-procesador-llamadas-venta.json](workflows/3274-procesador-llamadas-venta.json)**
  - **Descripción:** Este flujo procesa datos de competidores, integraciones y objeciones extraídos de un análisis de llamadas de ventas. Actualiza bases de datos en Notion con información estructurada y crea entradas específicas para cada categoría.
  - **Complejidad:** Alta (37 nodos)

- **[1440-auto-categorise-outlook-emails-with-ai.json](workflows/1440-auto-categorise-outlook-emails-with-ai.json)**
  - **Descripción:** Este flujo permite chatbot, gestión de leads utilizando Email/Gmail, YouTube, Supabase con inteligencia artificial.
  - **Complejidad:** Alta (36 nodos)

- **[2877-import-hubspot.json](workflows/2877-import-hubspot.json)**
  - **Descripción:** Este flujo importa datos desde un archivo CSV a HubSpot. Primero, valida los campos del archivo contra una lista de propiedades existentes en HubSpot. Si hay discrepancias, muestra un formulario para asignar campos correspondientes. Luego procesa los datos y los exporta a Google Sheets.
  - **Complejidad:** Alta (36 nodos)

- **[2986-appointment-leads-follow-up.json](workflows/2986-appointment-leads-follow-up.json)**
  - **Descripción:** Este flujo automático gestiona citas y seguimientos de leads utilizando Twilio para SMS, Cal.com para programación de citas y OpenAI para interacciones con el cliente. Detecta comandos como STOP para detener mensajes, actualiza Airtable con datos de seguimiento y envía recordatorios.
  - **Complejidad:** Alta (36 nodos)

- **[0882-hubspot-chatgpt-integration.json](workflows/0882-hubspot-chatgpt-integration.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de HubSpot integrar conversaciones con la API de OpenAI Assistant para mantener contexto y generar respuestas.
  - **Complejidad:** Alta (34 nodos)

- **[2535-hubspot-chat-ai-integration.json](workflows/2535-hubspot-chat-ai-integration.json)**
  - **Descripción:** Este flujo automatizado permite a un chatbot de HubSpot integrar la función Assistant con OpenAI y almacenar referencias en Airtable para mantener conversaciones contextualesizadas.
  - **Complejidad:** Alta (34 nodos)

- **[2854-finanzas-sync.json](workflows/2854-finanzas-sync.json)**
  - **Descripción:** Este flujo automático genera informes financieros mensuales que comparan los datos presupuestales con los resultados reales para una unidad de negocio específica. Incluye el análisis detallado de las ventas, costos, márgenes, y un informe de empleados, utilizando inteligencia artificial para la interpretación.
  - **Complejidad:** Alta (30 nodos)

- **[1012-crm-coupon-assignment.json](workflows/1012-crm-coupon-assignment.json)**
  - **Descripción:** Este flujo automático gestiona la asignación y validación de cupones únicos a través de código QR para generación de leads, manteniendo una relación bidireccional con Google Sheets.
  - **Complejidad:** Alta (29 nodos)

- **[3021-automatizacion-pipedrive-tokens.json](workflows/3021-automatizacion-pipedrive-tokens.json)**
  - **Descripción:** Este flujo automatiza el proceso de actualización de tokens de acceso y refresco en Pipedrive. Utiliza Supabase para almacenar y recuperar credenciales, maneja errores y valida los accesos토큰 mediante webhooks.
  - **Complejidad:** Alta (29 nodos)

- **[0879-whatsapp-sales-agent.json](workflows/0879-whatsapp-sales-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de WhatsApp actuar como asistente de ventas para los parlantes Yamaha Powered. El bot responde a mensajes de texto consultando una base de datos vectorial con el catálogo, mantiene memoria conversacional por cliente y rechaza automáticamente la procesión de no-texto.
  - **Complejidad:** Alta (28 nodos)

- **[1481-microsoft-outlook-ai-email-assistant-airtable.json](workflows/1481-microsoft-outlook-ai-email-assistant-airtable.json)**
  - **Descripción:** Este flujo permite chatbot, gestión de leads utilizando OpenAI/GPT, Email/Gmail, Airtable con inteligencia artificial y APIs de forma programada.
  - **Complejidad:** Alta (28 nodos)

- **[3026-shopify-mautic-sync.json](workflows/3026-shopify-mautic-sync.json)**
  - **Descripción:** Este flujo sincroniza y gestiona los estados de marketing entre Shopify y Mautic. Detecta cambios en la suscripción de correo electrónico de los clientes en Shopify, verifica su existencia en Mautic y actualiza automáticamente su segmentación o crea una nueva entrada si es necesario.
  - **Complejidad:** Alta (26 nodos)

- **[2864-mcp-paycaptain-employees.json](workflows/2864-mcp-paycaptain-employees.json)**
  - **Descripción:** Este flujo configura un servidor MCP que interactúa con la API de PayCaptain para permitir operaciones de búsqueda y actualización de empleados, protegiendo datos sensibles y logueando actividades en Google Sheets.
  - **Complejidad:** Alta (25 nodos)

- **[3272-call_processing_ai.json](workflows/3272-call_processing_ai.json)**
  - **Descripción:** Este flujo automatiza la procesamiento de llamadas de ventas usando AI para extraer información y almacenarla en Notion. Incluye alertas en Slack y maneja errores para garantizar la integridad de los datos.
  - **Complejidad:** Alta (25 nodos)

- **[1457-deduplicate-scraping-ai-grants-for-ai.json](workflows/1457-deduplicate-scraping-ai-grants-for-ai.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, extracción de datos, generación de contenido, monitoreo, gestión de leads utilizando OpenAI/GPT, Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs de forma programada.
  - **Complejidad:** Alta (24 nodos)

- **[2675-stripe-hubspot-sync.json](workflows/2675-stripe-hubspot-sync.json)**
  - **Descripción:** Este flujo sincroniza cargos de Stripe con contactos de HubSpot. Busca y suma los montos capturados por cliente, creando o actualizando una propiedad personalizada en HubSpot para mostrar el total gastado.
  - **Complejidad:** Alta (24 nodos)

- **[3275-automarketing-insights.json](workflows/3275-automarketing-insights.json)**
  - **Descripción:** Este flujo automatiza la creación de insights marketing y temas recurrentes en Notion a partir de datos de llamadas de ventas. Analiza y organiza información clave en bases de datos específas.
  - **Complejidad:** Alta (24 nodos)

- **[1266-smartlead-processing.json](workflows/1266-smartlead-processing.json)**
  - **Descripción:** Procesa leads de Smartlead y actualiza la base de datos.
  - **Complejidad:** Alta (23 nodos)

- **[3271-gong-call-processor.json](workflows/3271-gong-call-processor.json)**
  - **Descripción:** Este flujo extrae y procesa datos de llamadas de ventas de Gong para generar un transcript enriquecido con metadatos como compañías, asistentes internos/externos y formato unificado.
  - **Complejidad:** Alta (23 nodos)

- **[2722-asignacion-deal-hubspot.json](workflows/2722-asignacion-deal-hubspot.json)**
  - **Descripción:** Este flujo automático programa tareas diarias para obtener deals de HubSpot y asignarlos a diferentes vendedores basado en regiones y tamaño de empresa.
  - **Complejidad:** Alta (22 nodos)

- **[2751-crm-verification-form.json](workflows/2751-crm-verification-form.json)**
  - **Descripción:** Flujo que utiliza Tally Forms para capturar datos de formulario, verifica correo electrónico con CaptainVerify, gestiona créditos y crea Leads en SuiteCRM y contactos en Brevo. Notifica en NextCloudDiscussions si hay malformación o bajo crédito.
  - **Complejidad:** Alta (22 nodos)

- **[1125-zendesk-pipedrive-sync.json](workflows/1125-zendesk-pipedrive-sync.json)**
  - **Descripción:** Este flujo automatizado sincroniza comentarios de tickets de Zendesk con notas en personas de Pipedrive basándose en el correo electrónico del remitente y utiliza la última marca de tiempo para filtrar actualizaciones.
  - **Complejidad:** Alta (21 nodos)

- **[1477-intelligent-web-query-and-semantic-google.json](workflows/1477-intelligent-web-query-and-semantic-google.json)**
  - **Descripción:** Este flujo permite chatbot, resumen, extracción de datos, generación de contenido, reportes, gestión de leads utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (20 nodos)

- **[2728-automatizacion-leads-pipedrive.json](workflows/2728-automatizacion-leads-pipedrive.json)**
  - **Descripción:** Este flujo automatiza la gestión de leads en Pipedrive mediante Clearbit y Slack. Busca leads no archivados con tags B2B y más de 10 empleados, los enriquece con datos empresariales de Clearbit, marca como enriched y notifica a Slack.
  - **Complejidad:** Alta (20 nodos)

- **[3038-personal_assistant_mcp_server.json](workflows/3038-personal_assistant_mcp_server.json)**
  - **Descripción:** Este flujo configura un asistente personal que utiliza Google Gemini para procesar mensajes de chat, mantiene una memoria contextual y interactúa con MCP Server para realizar tareas como programar citas en Google Calendar, manejar correos electrónicos, actualizar hojas de cálculo de Google Sheets y buscar/actualizar filas en CRM.
  - **Complejidad:** Alta (20 nodos)

- **[1496-social-media-analysis-and-automated-email.json](workflows/1496-social-media-analysis-and-automated-email.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, web scraping, extracción de datos, generación de contenido, gestión de leads utilizando OpenAI/GPT, Email/Gmail, Google Sheets con inteligencia artificial y APIs.
  - **Complejidad:** Alta (19 nodos)

- **[3172-automated-social-media-email.json](workflows/3172-automated-social-media-email.json)**
  - **Descripción:** Este flujo automático permite analizar publicaciones en LinkedIn y Twitter de leads, generar un correo electrónico personalizado usando OpenAI y enviarlo automáticamente.
  - **Complejidad:** Alta (19 nodos)

- **[3251-automated-social-media-email.json](workflows/3251-automated-social-media-email.json)**
  - **Descripción:** Este flujo automático extrae publicaciones de LinkedIn y Twitter de leads, las procesa para generar mensajes personalizados con OpenAI y envía emails automatizados.
  - **Complejidad:** Alta (19 nodos)

- **[2676-workflow-hubspot-lead.json](workflows/2676-workflow-hubspot-lead.json)**
  - **Descripción:** Este flujo automático gestiona la integración de Leads en Lemlist y actualiza información en HubSpot, notificando a los equipos relevantes sobre oportunidades de venta. Incluye pasos para buscar o crear cuentas de empresas, actualizar perfiles de contactos, y enviar notificaciones a Slack.
  - **Complejidad:** Alta (18 nodos)

- **[2750-email_classifier.json](workflows/2750-email_classifier.json)**
  - **Descripción:** Este flujo monitorea las respuestas de correo electrónico en Lemlist y utiliza OpenAI para categorizarlas, posteriormente envía notificaciones personalizadas a Slack. Si la respuesta está clasificada como 'Unsubscribe', el lead es dado de baja; si es 'Interested', se marca como interesado.
  - **Complejidad:** Alta (18 nodos)

- **[2978-linkedin-empresa-score.json](workflows/2978-linkedin-empresa-score.json)**
  - **Descripción:** Este flujo automatiza la búsqueda de empresas en LinkedIn mediante la API de Ghost Genius, procesa sus datos, evalúa su fitness con un modelo de IA y los registra en una hoja de cálculo de Google Sheets. Primero, obtiene información detallada de cada empresa, filtra aquellas con más de 200 seguidores y una.website, luego verifica si ya existen en el CRM. Si son nuevas, las puntuación con IA y finalmente las agrega al CRM con su score y detalles relevantes.
  - **Complejidad:** Alta (18 nodos)

- **[3133-phone-agent-lead-qualification.json](workflows/3133-phone-agent-lead-qualification.json)**
  - **Descripción:** Este flujo automático gestiona llamadas salientes y entrantes, cualificando leads y programando citas mediante RetellAI, Google Sheets, Twilio y Gmail. Detecta nuevas oportunidades en Google Sheets, envía recordatorios SMS, programa llamadas automáticas con RetellAI, maneja citas por teléfono, registra interacciones, envía correos de confirmación y análisis con OpenAI.
  - **Complejidad:** Alta (18 nodos)

- **[0010-crm-lead-batchdata-calification.json](workflows/0010-crm-lead-batchdata-calification.json)**
  - **Descripción:** Este flujo verifica y califica leads utilizando BatchData para consultar detalles de propiedades como valor estimado, tamaño o antigüedad, y luego actualiza automáticamente el registro del lead en el CRM con esta información.
  - **Complejidad:** Alta (17 nodos)

- **[1124-zendesk-pipedrive-ticket.json](workflows/1124-zendesk-pipedrive-ticket.json)**
  - **Descripción:** Este flujo automático procesa tickets de Zendesk cada 5 minutos para buscar y actualizar información del solicitante utilizando datos de Pipedrive.
  - **Complejidad:** Alta (17 nodos)

- **[1183-mautic-student-automation.json](workflows/1183-mautic-student-automation.json)**
  - **Descripción:** Este flujo automatizado procesa solicitudes webhooks de estudiantes, busca usuarios en Mautic, actualiza sus datos e información relacionada con boletines.
  - **Complejidad:** Alta (17 nodos)

- **[2822-automated-sales-email-generator.json](workflows/2822-automated-sales-email-generator.json)**
  - **Descripción:** Este flujo automatiza la creación de emails personalizados para ventas utilizando Google Gemini y Gmail. Recupera correos electrónicos de clientes, construye perfiles personalizados con un análisis de comunicación y estilo de compra, genera pitches adaptados y crea borradores para revisión humana.
  - **Complejidad:** Alta (17 nodos)

- **[0085-n8n_LinkedIn_Interactions_Automation.json](workflows/0085-n8n_LinkedIn_Interactions_Automation.json)**
  - **Descripción:** Este flujo automático procesa interacciones de LinkedIn (comentarios y me gusta) para obtener datos de contactos y actualizarlos o crear nuevos registros en Airtable, además de agregarlos a Lemlist y Hubspot.
  - **Complejidad:** Alta (16 nodos)

- **[0376-unsubscribe-mautic.json](workflows/0376-unsubscribe-mautic.json)**
  - **Descripción:** Este flujo automático permite a los usuarios desuscribirse de correos marketing al responder un mensaje específico en Gmail, integrando con Mautic CRM para gestionar sus datos.
  - **Complejidad:** Alta (16 nodos)

- **[2726-crm-enrichment-flow.json](workflows/2726-crm-enrichment-flow.json)**
  - **Descripción:** Este flujo automatiza el proceso de enriquecimiento y gestión de datos de contactos y empresas a través de Clearbit y Hubspot. Detecta si una empresa existe en CRM; en caso contrario, la crea o actualiza con información detallada. También valida y filtra correos electrónicos para evitar direcciones personales.
  - **Complejidad:** Alta (16 nodos)

- **[2727-crm-enrich-flow.json](workflows/2727-crm-enrich-flow.json)**
  - **Descripción:** Este flujo automático en n8n utiliza Clearbit y Hubspot para enriquecer datos de empresas y contactos. Detecta si una empresa existe en el CRM, crea o actualiza registros en consecuencia, y gestiona Leads en ConvertKit. Filtra correos no personales y administra contactos con inteligencia.
  - **Complejidad:** Alta (16 nodos)

- **[3086-linkedin-to-airtable.json](workflows/3086-linkedin-to-airtable.json)**
  - **Descripción:** Este flujo automatiza la búsqueda de empresas en LinkedIn y las agrega a una base de datos de Airtable CRM. Busca compañías según criterios como industria, tamaño y ubicación, luego verifica si ya existen en el CRM y las ingresa si no están duplicadas.
  - **Complejidad:** Alta (16 nodos)

- **[3152-property_leads_enrichment.json](workflows/3152-property_leads_enrichment.json)**
  - **Descripción:** Este flujo automatiza la obtención de datos de propiedades inmuebles mediante BatchData, realiza un filtrado avanzado y enriquecimiento con información del dueño, formatea los resultados y los exporta a CRM y Excel.
  - **Complejidad:** Alta (16 nodos)

- **[3258-automate-lead-generation-suitecrm.json](workflows/3258-automate-lead-generation-suitecrm.json)**
  - **Descripción:** Flujo para automatizar la generación de leads en SuiteCRM usando formularios web y Google Sheets. Permite crear Leads con cupones exclusivos verificando si son duplicados y actualizando una hoja de cálculo.
  - **Complejidad:** Alta (16 nodos)

- **[2579-escaneo-propiedades.json](workflows/2579-escaneo-propiedades.json)**
  - **Descripción:** Este flujo automático escanea regularmente el mercado inmobiliario, identifica propiedades nuevas o modificadas y filtra aquellas con alta rentabilidad potencial (alta plusvalía) para enviar alertas al equipo de ventas mediante email y Slack.
  - **Complejidad:** Media (15 nodos)

- **[2720-leadfeeder-to-googlesheets.json](workflows/2720-leadfeeder-to-googlesheets.json)**
  - **Descripción:** Este flujo automático extrae y enriquece datos de Leads desde Leadfeeder, filtra por empresa y engagement, y los exporta a Google Sheets.
  - **Complejidad:** Media (15 nodos)

- **[2723-lead-generation-flow.json](workflows/2723-lead-generation-flow.json)**
  - **Descripción:** Este flujo automático recolecta Leads a través de un formulario web, verifica la validez del correo electrónico utilizando Hunter, evalúa el perfil del cliente con MadKudu y, en caso de ser interesante (puntuación >60), envía un correo de outreach a través de Gmail y registra la interacción en HubSpot.
  - **Complejidad:** Media (15 nodos)

- **[2729-form-to-pipedrive.json](workflows/2729-form-to-pipedrive.json)**
  - **Descripción:** Este flujo utiliza formularios para recolectar emails, verifica su validez con Hunter.io, obtiene información de Clearbit y crea o actualiza registros en Pipedrive.
  - **Complejidad:** Media (15 nodos)

- **[0235-salesforce-carga-hoja-calculo.json](workflows/0235-salesforce-carga-hoja-calculo.json)**
  - **Descripción:** Este flujo procesa datos de una hoja de cálculo para crear registros en Salesforce: primero busca cuentas existentes, luego crea nuevas cuentas si no se encuentran y finalmente agrega contactos vinculados a las mismas.
  - **Complejidad:** Media (14 nodos)

- **[0653-bidirectional-sync.json](workflows/0653-bidirectional-sync.json)**
  - **Descripción:** Este flujo sincroniza bidireccionalmente datos entre la base de datos MySQL y el CRM Pipedrive.
  - **Complejidad:** Media (14 nodos)

- **[0961-lead-presentaciones-auto.json](workflows/0961-lead-presentaciones-auto.json)**
  - **Descripción:** Este flujo automático crea presentaciones personalizadas basadas en datos de leads al monitorear archivos nuevos en Google Drive y procesarlos mediante operaciones de Google Sheets e Slides para integrar las informaciones.
  - **Complejidad:** Media (14 nodos)

- **[1014-INSEE_AgileCRM_Enrichment.json](workflows/1014-INSEE_AgileCRM_Enrichment.json)**
  - **Descripción:** Este flujo automático enriquece datos de empresas en Agile CRM usando la API abierta de INSEE.
  - **Complejidad:** Media (14 nodos)

- **[2872-flujo_conversaciones.json](workflows/2872-flujo_conversaciones.json)**
  - **Descripción:** Este flujo automatiza la gestión de conversaciones con clientes mediante HubSpot y LangChain. Permite buscar IDs de clientes, resumir conversaciones, enrutar feedback a departamentos específicos y enviar correos electrónicos usando Gmail.
  - **Complejidad:** Media (14 nodos)

- **[2995-lead-automaton-v4.json](workflows/2995-lead-automaton-v4.json)**
  - **Descripción:** Este flujo automático monitorea entradas en Google Sheets y envía notificaciones a Slack y Gmail al recibir una nueva Lead. Si el interés es caliente y no ha sido seguido up, programa un recordatorio después de 3 minutos.
  - **Complejidad:** Media (14 nodos)

- **[0254-hubspot-zendesk-sync.json](workflows/0254-hubspot-zendesk-sync.json)**
  - **Descripción:** Este flujo automatizado sincroniza datos entre los sistemas HubSpot y Zendesk, verificando si existe el ticket antes de realizar acciones como crear o actualizar contactos y tickets.
  - **Complejidad:** Media (13 nodos)

- **[2875-email-process-hubspot.json](workflows/2875-email-process-hubspot.json)**
  - **Descripción:** Este flujo automático procesa un correo electrónico recibido, extrae información relevante con IA, verifica si existe un contacto en HubSpot y crea una nueva entrada o actualiza el registro existente.
  - **Complejidad:** Media (13 nodos)

- **[0227-pipedrive-organization-sync.json](workflows/0227-pipedrive-organization-sync.json)**
  - **Descripción:** Este flujo monitoriza un archivo Excel en Google Drive y crea organizaciones e información de contacto en Pipedrive basada en su contenido.
  - **Complejidad:** Media (12 nodos)

- **[0233-salesforce-sync.json](workflows/0233-salesforce-sync.json)**
  - **Descripción:** Este flujo automatizado permite mantener la relación entre empresas de Google Sheets y sus datos correspondientes en Salesforce al crear registros tanto de cuenta como contacto.
  - **Complejidad:** Media (12 nodos)

- **[0234-excel-to-salesforce.json](workflows/0234-excel-to-salesforce.json)**
  - **Descripción:** Este flujo automático extrae datos de Microsoft Excel para buscar y crear registros tanto en cuenta como contacto en Salesforce.
  - **Complejidad:** Media (12 nodos)

- **[0252-flujo-captura-emails.json](workflows/0252-flujo-captura-emails.json)**
  - **Descripción:** Este flujo automático procesa respuestas por correo electrónico categorizándolas y ejecutando acciones como crear leads en HubSpot o marcarlas en Lemlist, además de enviar notificaciones vía Slack.
  - **Complejidad:** Media (12 nodos)

- **[0338-hubspot-exact-enrichment.json](workflows/0338-hubspot-exact-enrichment.json)**
  - **Descripción:** Este flujo automático permite a n8n enriquecer automáticamente perfiles de contacto en HubSpot con información adicional obtenida desde la API de ExactBuyer.
  - **Complejidad:** Media (12 nodos)

- **[0341-hubspot-seguimiento-email.json](workflows/0341-hubspot-seguimiento-email.json)**
  - **Descripción:** Este flujo automático busca contactos en HubSpot que hayan sido contactados anteriormente y solo hayan tenido un engagement, para enviarles un email educado de seguimiento.
  - **Complejidad:** Media (12 nodos)

- **[0343-validacion-email-madkudu-n8n.json](workflows/0343-validacion-email-madkudu-n8n.json)**
  - **Descripción:** Este flujo automatizado valida emails con Hunter y puntúa leads con MadKudu mediante un formulario webhook, enviando alertas por email solo si la puntuación es mayor a 60.
  - **Complejidad:** Media (12 nodos)

- **[0223-stripe-organization-sync.json](workflows/0223-stripe-organization-sync.json)**
  - **Descripción:** Este flujo automático busca procesar cargas exitosas de Stripe que ocurrieron antes del último tiempo de ejecución, buscando en Pipedrive la organización correspondiente a cada cliente y creando una nota con los detalles de la carga.
  - **Complejidad:** Media (11 nodos)

- **[0225-pipedrive-datagma-enrichment.json](workflows/0225-pipedrive-datagma-enrichment.json)**
  - **Descripción:** Este flujo automatizado utiliza Pipedrive para rastrear organizaciones y personal, enriqueciendo sus datos con información de Datorama como Fondo de Inversión y tráfico web.
  - **Complejidad:** Media (11 nodos)

- **[0294-twentycrm-eventos-canales.json](workflows/0294-twentycrm-eventos-canales.json)**
  - **Descripción:** Este flujo automatizado obtiene notificaciones/eventos de TwentyCRM y las distribuye por los canales preferidos según el tipo de evento.
  - **Complejidad:** Media (11 nodos)

- **[0323-crm_lead_automation.json](workflows/0323-crm_lead_automation.json)**
  - **Descripción:** Este flujo automático detecta respuestas por email a campañas de marketing, evalúa el interés del prospecto mediante inteligencia artificial y, en caso de estar interesado, crea un nuevo trato en Pipedrive.
  - **Complejidad:** Media (11 nodos)

- **[0342-lead-verification-madkudu-slack.json](workflows/0342-lead-verification-madkudu-slack.json)**
  - **Descripción:** Este flujo automático verifica y califica leads usando Hunter e integra con MadKudu para enviar notificaciones por Slack cuando el ajuste del cliente supera un umbral.
  - **Complejidad:** Media (11 nodos)

- **[1141-hubspot-product-replication.json](workflows/1141-hubspot-product-replication.json)**
  - **Descripción:** Este flujo automático permite replicar automáticamente los line items de un deal ganado a otro recién creado en HubSpot, integrando Workflows y n8n mediante webhooks.
  - **Complejidad:** Media (11 nodos)

- **[2721-email-verification-flow.json](workflows/2721-email-verification-flow.json)**
  - **Descripción:** Este flujo verifica la valididad de un correo electrónico, obtiene información de empresa y persona a partir de Clearbit, y agrega una lead a Hubspot si el correo es válido.
  - **Complejidad:** Media (11 nodos)

- **[3138-qualify-leads-pipedrive.json](workflows/3138-qualify-leads-pipedrive.json)**
  - **Descripción:** Este flujo automático cualifica respuestas de leads en Pipedrive utilizando inteligencia artificial para determinar su interés y crea una oportunidad si el lead muestra interés.
  - **Complejidad:** Media (11 nodos)

- **[3269-gong-call-processing.json](workflows/3269-gong-call-processing.json)**
  - **Descripción:** Este flujo automatiza la extracción de información relevante de las llamadas comerciales grabadas en Gong y Salesforce. Busca oportunidades primarias con valores y etapas específicas, formatea los datos de las llamadas y envía la información procesada a un preprocesador para su análisis posterior.
  - **Complejidad:** Media (11 nodos)

- **[0089-hubspot-deals-processing.json](workflows/0089-hubspot-deals-processing.json)**
  - **Descripción:** Este flujo automatizado procesa las propiedades de una negociación (deal) en HubSpot, determinando si es de alta prioridad o no. Luego envía notificaciones a Slack y guarda información en Airtable, además de generar presentaciones en Google Slides.
  - **Complejidad:** Media (10 nodos)

- **[0116-typeform_lead_workflow.json](workflows/0116-typeform_lead_workflow.json)**
  - **Descripción:** Este flujo automático permite a un chatbot procesar leads de Typeform y realizar operaciones en Airtable: si el contacto no existe, lo crea; si ya existe, actualiza sus campos. Además envía notificaciones por Slack cuando se añade o actualiza un lead.
  - **Complejidad:** Media (10 nodos)

- **[0374-crm-address-verification.json](workflows/0374-crm-address-verification.json)**
  - **Descripción:** Este flujo verifica la validez del domicilio postal de los contactos nuevos importados desde Groundhogg CRM utilizando la API de Lob. Si el resultado indica que es entregable, agrega una etiqueta y actualiza el contacto; si no, agrega otra etiqueta y desencadena acciones manuales o automatizadas.
  - **Complejidad:** Media (10 nodos)

- **[0379-Keap-Lob-Address-Verification.json](workflows/0379-Keap-Lob-Address-Verification.json)**
  - **Descripción:** Este flujo automático verifica la dirección postal de un contacto en Keap usando Lob a través de una API, y actualiza automáticamente los campos o aplica etiquetas según si es entregable o no.
  - **Complejidad:** Media (10 nodos)

- **[3029-wordpress-to-mautic-form.json](workflows/3029-wordpress-to-mautic-form.json)**
  - **Descripción:** Flujo que recibe datos de un formulario de WordPress, normaliza y valida los campos como el correo electrónico, y crea o actualiza una entrada en Mautic si la dirección es válida.
  - **Complejidad:** Media (10 nodos)

- **[0076-google-calendar-status-hue.json](workflows/0076-google-calendar-status-hue.json)**
  - **Descripción:** Este flujo verifica automáticamente eventos comenzados en Google Calendar cada 5 minutos. Luego, asigna colores o estados específicos (como '4dw_leading' o 'Lavendar') a una variable llamada calColor y utiliza esta información para controlar luces inteligentes Philips Hue mediante webhooks HTTP POST según el estado determinado. Finalmente, actualiza el perfil de usuario en Slack con texto e emoji relacionados.
  - **Complejidad:** Media (9 nodos)

- **[0081-shopify-pedidos-trigger.json](workflows/0081-shopify-pedidos-trigger.json)**
  - **Descripción:** Este flujo automático procesa la creación de nuevos pedidos en Shopify para sincronizar datos con Zoho CRM, crear tareas en Trello y enviar comunicaciones por correo electrónico si el pedido supera un valor mínimo.
  - **Complejidad:** Media (9 nodos)

- **[0253-hubspot-zendesk-company-sync.json](workflows/0253-hubspot-zendesk-company-sync.json)**
  - **Descripción:** Este flujo sincroniza datos de compañías de HubSpot con la API de Zendesk para mantener organizaciones actualizadas.
  - **Complejidad:** Media (9 nodos)

- **[1487-qualify-new-leads-in-google-sheets-gpt.json](workflows/1487-qualify-new-leads-in-google-sheets-gpt.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos, gestión de leads utilizando OpenAI/GPT, Email/Gmail, Google Sheets con inteligencia artificial y APIs.
  - **Complejidad:** Media (9 nodos)

- **[3137-calificacion-leads-gpt.json](workflows/3137-calificacion-leads-gpt.json)**
  - **Descripción:** Este flujo automatiza la calificación de leads usando Google Sheets y GPT-4. Detecta entradas nuevas en una hoja de cálculo, las envía a OpenAI para evaluar su calidad y actualiza el status en la misma hoja con una calificación y explicación.
  - **Complejidad:** Media (9 nodos)

- **[0017-stripe-hubspot-slack.json](workflows/0017-stripe-hubspot-slack.json)**
  - **Descripción:** Este flujo automático actualiza un deal en HubSpot a pagado cuando una factura de Stripe se paga exitosamente e informa sobre el pago y detalles del mismo mediante mensajes en Slack.
  - **Complejidad:** Media (8 nodos)

- **[0073-hubspot-pagination.json](workflows/0073-hubspot-pagination.json)**
  - **Descripción:** Este flujo automático obtiene múltiples páginas de resultados desde la API HubSpot para contactos.
  - **Complejidad:** Media (8 nodos)

- **[0216-typeform-pipedrive-mapeo.json](workflows/0216-typeform-pipedrive-mapeo.json)**
  - **Descripción:** Este flujo automático recoge datos de un formulario de Typeform y los integra en Pipedrive para crear automáticamente registros de organización, persona y lead, manteniendo la lógica de mapeo entre el formato original y las propiedades personalizadas.
  - **Complejidad:** Media (8 nodos)

- **[0228-github-fork-to-pipedrive-lead.json](workflows/0228-github-fork-to-pipedrive-lead.json)**
  - **Descripción:** Este flujo detecta forks en GitHub y crea leads en Pipedrive si no existe la persona.
  - **Complejidad:** Media (8 nodos)

- **[0339-hubspot-engagement-automation.json](workflows/0339-hubspot-engagement-automation.json)**
  - **Descripción:** Este flujo automático envía correos de seguimiento a contactos no contactados en HubSpot usando Gmail y registra el engagement.
  - **Complejidad:** Media (8 nodos)

- **[0346-lead-alertas-n8n.json](workflows/0346-lead-alertas-n8n.json)**
  - **Descripción:** Este flujo automático monitoriza nuevas empresas calientes en HubSpot y envía alertas a un usuario específico en Slack cada 5 minutos.
  - **Complejidad:** Media (8 nodos)

- **[0974-pipedrive-enrichment.json](workflows/0974-pipedrive-enrichment.json)**
  - **Descripción:** Este flujo de trabajo enriquece automáticamente los datos organizacionales de Pipedrive con información extraída por GPT-4o y envía una notificación a Slack.
  - **Complejidad:** Media (8 nodos)

- **[1123-shopify-deal-sync.json](workflows/1123-shopify-deal-sync.json)**
  - **Descripción:** Este flujo automatizado verifica si un pedido actualizado en Shopify ya existe como una oportunidad (deal) en HubSpot y, de no ser así, crea una nueva deal utilizando datos del pedido.
  - **Complejidad:** Media (8 nodos)

- **[2656-pipedrive-enrichment-flow.json](workflows/2656-pipedrive-enrichment-flow.json)**
  - **Descripción:** Este flujo automático escanea el sitio web de una organización recién creada en Pipedrive para generar un resumen detallado usando GPT-4o, lo que permite mantener datos actualizados e integrados directamente en el sistema CRM.
  - **Complejidad:** Media (8 nodos)

- **[0088-typeform-hubspot-email.json](workflows/0088-typeform-hubspot-email.json)**
  - **Descripción:** Este flujo automatizado captura datos desde un formulario Typeform, crea o actualiza contactos en HubSpot y envía información personalizada por email cuando el prospecto demuestra interés.
  - **Complejidad:** Media (7 nodos)

- **[0121-crm-sync.json](workflows/0121-crm-sync.json)**
  - **Descripción:** Este flujo sincroniza contactos entre Pipedrive y HubSpot mediante la obtención de todos los registros de ambos sistemas, luego utiliza 'Merge' para combinar datos cuando coinciden en email o nombre.
  - **Complejidad:** Media (7 nodos)

- **[0222-pipedrive-stripe-deal.json](workflows/0222-pipedrive-stripe-deal.json)**
  - **Descripción:** Este flujo verifica si un deal en Pipedrive ha sido ganado recientemente y, si no existe el cliente asociado en Stripe, lo crea utilizando los datos proporcionados.
  - **Complejidad:** Media (7 nodos)

- **[0224-pipedrive-stripe-product-sync.json](workflows/0224-pipedrive-stripe-product-sync.json)**
  - **Descripción:** Este flujo automático sincroniza productos nuevos de Pipedrive con Stripe mediante una API y luego crea sus registros de precios correspondientes.
  - **Complejidad:** Media (7 nodos)

- **[0980-lead-generation.json](workflows/0980-lead-generation.json)**
  - **Descripción:** Este flujo automatizado permite extraer y guardar en Airtable miles de leads con datos completos.
  - **Complejidad:** Media (7 nodos)

- **[2929-support-sales-flow.json](workflows/2929-support-sales-flow.json)**
  - **Descripción:** Este flujo implementa un sistema de soporte al cliente y ventas que utiliza inteligencia artificial para gestionar pedidos, actualizar stock y mantener conversaciones con los usuarios. El chatbot puede verificar el stock, realizar pedidos y actualizar la disponibilidad en Google Sheets.
  - **Complejidad:** Media (7 nodos)

- **[0229-github-pullrequest-pipedrive.json](workflows/0229-github-pullrequest-pipedrive.json)**
  - **Descripción:** Este flujo automático busca en Pipedrive un usuario existente basado en el correo electrónico de un creador de PR (Pull Request) detectado por una webhook de GitHub, y si existe añade una nota a su cuenta.
  - **Complejidad:** Media (6 nodos)

- **[0507-whatsapp-crm-automation.json](workflows/0507-whatsapp-crm-automation.json)**
  - **Descripción:** Este flujo automático recoge datos de WhatsApp mediante un webhook, los guarda en una hoja de Google y añade el contacto a la CRM con etiqueta 'Nuevo Lead'. Posteriormente envía un correo y un mensaje en WhatsApp para dar la bienvenida al cliente.
  - **Complejidad:** Media (6 nodos)

- **[0685-coffee-bot-mattermost.json](workflows/0685-coffee-bot-mattermost.json)**
  - **Descripción:** Este flujo automático organiza a los empleados en grupos aleatorios para sesiones de café virtual cada lunes y envía invitaciones a su calendario, además de anunciar los grupos formados.
  - **Complejidad:** Media (6 nodos)

- **[0706-mautic-email-validation-alert.json](workflows/0706-mautic-email-validation-alert.json)**
  - **Descripción:** Este flujo verifica si un contacto de Mautic tiene una dirección de correo electrónico inválida o con baja calidad, y en caso afirmativo envía una alerta a Slack.
  - **Complejidad:** Media (6 nodos)

- **[0086-calendly-pipedrive-slack.json](workflows/0086-calendly-pipedrive-slack.json)**
  - **Descripción:** Este flujo automático se activa cuando un invitado se crea en Calendly. Crea una actividad en Pipedrive con los detalles de la reunión y envía a Slack un recordatorio al equipo de ventas sobre el encuentro, pidiéndoles que redacten sus notas.
  - **Complejidad:** Media (5 nodos)

- **[0122-sync-hubspot-pipedrive.json](workflows/0122-sync-hubspot-pipedrive.json)**
  - **Descripción:** Este flujo sincroniza contactos entre HubSpot y Pipedrive mediante un desencadenador de cron cada minuto, utilizando coincidencias por email para fusionar los registros.
  - **Complejidad:** Media (5 nodos)

- **[0154-hubspot-company-alerts.json](workflows/0154-hubspot-company-alerts.json)**
  - **Descripción:** Este flujo se activa al crear una nueva empresa en HubSpot y verifica si tiene problemas de entregabilidad o si su dominio no es válido/¿email desechable?, enviando alertas por Slack.
  - **Complejidad:** Media (5 nodos)

- **[0221-line-mailchimp-sync.json](workflows/0221-line-mailchimp-sync.json)**
  - **Descripción:** Este flujo sincroniza contactos entre LINE y Mailchimp utilizando el HubSpot API.
  - **Complejidad:** Media (5 nodos)

- **[0700-mautic-woocommerce-sync.json](workflows/0700-mautic-woocommerce-sync.json)**
  - **Descripción:** Este flujo verifica si existe un cliente de WooCommerce en Mautic mediante una búsqueda en Mautic y crea o actualiza automáticamente contactos en Mautic.
  - **Complejidad:** Media (5 nodos)

- **[0774-coffee-groups-organization.json](workflows/0774-coffee-groups-organization.json)**
  - **Descripción:** Este flujo automatizado organiza virtualmente a los empleados en grupos para coffee chats cada lunes a las 10:00
  - **Complejidad:** Media (5 nodos)

- **[1195-hubspot-email-validation.json](workflows/1195-hubspot-email-validation.json)**
  - **Descripción:** Este flujo verifica automáticamente si un contacto recién creado en HubSpot tiene una dirección electrónica válida, confiable o no sospechosa.
  - **Complejidad:** Media (5 nodos)

- **[1212-save-sales-emails-odoo-opportunity.json](workflows/1212-save-sales-emails-odoo-opportunity.json)**
  - **Descripción:** Este flujo automático captura correos electrónicos con etiquetas específicas en Gmail y los utiliza para crear nuevas oportunidades de ventas en Odoo resumiendo su contenido mediante OpenAI.
  - **Complejidad:** Media (5 nodos)

- **[0021-mock-contacts-to-sheet.json](workflows/0021-mock-contacts-to-sheet.json)**
  - **Descripción:** Este flujo carga datos de ejemplo de contacto del servicio HubSpot en un conjunto (Set) para luego simular una operación de 'agregar fila' o similar hacia Google Sheets/Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[0022-copper-person-flow.json](workflows/0022-copper-person-flow.json)**
  - **Descripción:** Este flujo automatizado crea un registro en Copper con el nombre Harshil y su correo electrónico, luego actualiza ese registro agregando un número telefónico específico e finalmente obtiene los detalles actualizados de la persona.
  - **Complejidad:** Baja (4 nodos)

- **[0108-hubspot-trigger-para-chatbot.json](workflows/0108-hubspot-trigger-para-chatbot.json)**
  - **Descripción:** Este flujo automático utiliza el desencadenador de HubSpot para iniciar y actualizar datos de contacto con información obtenida de Clearbit mediante la dirección de correo electrónico.
  - **Complejidad:** Baja (4 nodos)

- **[0112-lem-list-carga.json](workflows/0112-lem-list-carga.json)**
  - **Descripción:** Este flujo permite cargar datos de contacto desde Dropcontact en una hoja de Google y luego transferirlos como leads a Lemlist.
  - **Complejidad:** Baja (4 nodos)

- **[0644-hoja-mautic-sync.json](workflows/0644-hoja-mautic-sync.json)**
  - **Descripción:** Este flujo automático lee datos de una hoja de Google Sheets cada 5 minutos y los envía como campos personalizados al CRM Mautic.
  - **Complejidad:** Baja (4 nodos)

- **[0655-salesforce-update-and-note.json](workflows/0655-salesforce-update-and-note.json)**
  - **Descripción:** Este flujo automatizado permite actualizar campos específicos de un registro en Salesforce y añadir una nota al mismo, utilizando el ID del registro precedente.
  - **Complejidad:** Baja (4 nodos)

- **[0220-mailchimp-nueva-cita.json](workflows/0220-mailchimp-nueva-cita.json)**
  - **Descripción:** Este flujo automático busca contactos nuevos creados hoy en HubSpot, extrae sus propiedades principales y los agrega como miembros a una lista específica de Mailchimp cada día a las 07:00.
  - **Complejidad:** Baja (3 nodos)

- **[0246-monday-mautic-automation.json](workflows/0246-monday-mautic-automation.json)**
  - **Descripción:** Este flujo automático crea un elemento en Monday.com con el nombre y email de contacto cuando se guarda uno nuevo en Mautic.
  - **Complejidad:** Baja (3 nodos)

- **[0247-calendly-mautic-sync.json](workflows/0247-calendly-mautic-sync.json)**
  - **Descripción:** Este flujo automático sincroniza datos de Calendly con Mautic para crear o actualizar contactos cuando se genera un nuevo evento.
  - **Complejidad:** Baja (3 nodos)

- **[0248-shopify-mautic-contact.json](workflows/0248-shopify-mautic-contact.json)**
  - **Descripción:** Este flujo automático permite crear un contacto en Mautic cada vez que se crea un nuevo cliente en Shopify.
  - **Complejidad:** Baja (3 nodos)

- **[0506-facebook-lead-to-klicktipp.json](workflows/0506-facebook-lead-to-klicktipp.json)**
  - **Descripción:** Este flujo automático importa datos de formularios de Facebook Lead Ads y los sincroniza en KlickTipp para iniciar campañas de email.
  - **Complejidad:** Baja (3 nodos)

- **[0755-airtable-lemlist-sync.json](workflows/0755-airtable-lemlist-sync.json)**
  - **Descripción:** Este flujo importa registros de Airtable y los convierte en leads en Lemlist, utilizando credenciales específicas para ambas conexiones.
  - **Complejidad:** Baja (3 nodos)

- **[0066-pipedrive-crear-deal.json](workflows/0066-pipedrive-crear-deal.json)**
  - **Descripción:** Este flujo automático crea un nuevo deal en Pipedrive cuando se hace clic en el manualTrigger.
  - **Complejidad:** Baja (2 nodos)

- **[0107-salesmate-company-creator.json](workflows/0107-salesmate-company-creator.json)**
  - **Descripción:** Este flujo permite crear una entrada de empresa en el sistema Salesmate mediante un desencadenador manual cuando se hace clic.
  - **Complejidad:** Baja (2 nodos)

- **[0110-info-uplead-company.json](workflows/0110-info-uplead-company.json)**
  - **Descripción:** Este flujo automático permite obtener información detallada sobre una empresa específica utilizando el servicio UpLead.
  - **Complejidad:** Baja (2 nodos)

- **[0141-twilio-mautic-form-sms.json](workflows/0141-twilio-mautic-form-sms.json)**
  - **Descripción:** Este flujo automático recibe notificaciones cuando se envía un formulario en Mautic y envía un SMS de confirmación.
  - **Complejidad:** Baja (2 nodos)

- **[0589-zoho-crm-get-all.json](workflows/0589-zoho-crm-get-all.json)**
  - **Descripción:** Este flujo manual inicia la ejecución para obtener todos los registros de Zoho CRM mediante autenticación OAuth2.
  - **Complejidad:** Baja (2 nodos)

- **[0590-keap-contact-all.json](workflows/0590-keap-contact-all.json)**
  - **Descripción:** Este flujo activa manualmente una ejecución que obtiene todos los contactos de Keap.
  - **Complejidad:** Baja (2 nodos)

- **[0684-hubspot-contactos-getall.json](workflows/0684-hubspot-contactos-getall.json)**
  - **Descripción:** Este flujo automático inicia manualmente la obtención de todos los contactos de HubSpot mediante el nodo 'getAll' del recurso 'contact'.
  - **Complejidad:** Baja (2 nodos)

- **[0745-crear-organizacion-affinity.json](workflows/0745-crear-organizacion-affinity.json)**
  - **Descripción:** Este flujo automático permite crear una organización en Affinity mediante un trigger manual.
  - **Complejidad:** Baja (2 nodos)

- **[0754-agile-crm-contact-creation.json](workflows/0754-agile-crm-contact-creation.json)**
  - **Descripción:** Este flujo automático permite crear un nuevo contacto en Agile CRM mediante la activación del botón 'execute' manual.
  - **Complejidad:** Baja (2 nodos)

- **[1186-mautic-get-all-registros.json](workflows/1186-mautic-get-all-registros.json)**
  - **Descripción:** Este flujo permite iniciar manualmente la ejecución de una tarea en el sistema n8n que se conecta a Mautic mediante autenticación OAuth2 para obtener todos los registros.
  - **Complejidad:** Baja (2 nodos)

- **[0071-pipedrive-change-monitor.json](workflows/0071-pipedrive-change-monitor.json)**
  - **Descripción:** Este flujo monitoriza todos los cambios en Pipedrive mediante su webhook y ejecuta acciones automatizadas.
  - **Complejidad:** Baja (1 nodos)

- **[0575-copper-project-trigger.json](workflows/0575-copper-project-trigger.json)**
  - **Descripción:** Este flujo automático se activa mediante un webhook de Copper cuando ocurren eventos 'new' en recursos de tipo 'project'.
  - **Complejidad:** Baja (1 nodos)

- **[0591-line-keap-integracion-automatica.json](workflows/0591-line-keap-integracion-automatica.json)**
  - **Descripción:** Este flujo automático inicia procesos en n8n cuando un nuevo contacto se agrega en Keap.
  - **Complejidad:** Baja (1 nodos)

- **[0642-hubspot-trigger-dghert3.json](workflows/0642-hubspot-trigger-dghert3.json)**
  - **Descripción:** Este flujo automático es un trigger para procesar eventos específicos en HubSpot con appId dghert3.
  - **Complejidad:** Baja (1 nodos)

- **[0646-nuevo-triage-afinidad-lista.json](workflows/0646-nuevo-triage-afinidad-lista.json)**
  - **Descripción:** Este flujo se activa cuando se crea una nueva lista en la API de Affinity.
  - **Complejidad:** Baja (1 nodos)


### Notificaciones y Alertas

- **[1262-thehive-slack-integration.json](workflows/1262-thehive-slack-integration.json)**
  - **Descripción:** Envía notificaciones de casos de TheHive a un canal de Slack.
  - **Complejidad:** Alta (63 nodos)

- **[1443-automate-sales-meeting-prep-with-ai-whatsapp.json](workflows/1443-automate-sales-meeting-prep-with-ai-whatsapp.json)**
  - **Descripción:** Este flujo permite chatbot, web scraping, resumen, extracción de datos, generación de contenido utilizando OpenAI/GPT, Telegram, Slack con inteligencia artificial mediante webhooks y APIs de forma programada.
  - **Complejidad:** Alta (61 nodos)

- **[2949-automate-sales-meeting-prep.json](workflows/2949-automate-sales-meeting-prep.json)**
  - **Descripción:** Este flujo automático programa reuniones y envía notificaciones con información relevante a través de WhatsApp utilizando inteligencia artificial para resumir correos electrónicos y perfiles de LinkedIn.
  - **Complejidad:** Alta (61 nodos)

- **[3039-documento_procesamiento_ai.json](workflows/3039-documento_procesamiento_ai.json)**
  - **Descripción:** Este flujo automático procesa documentos adjuntos en correo electrónico usando LlamaParse para extraer información y almacenarla en Google Sheets y Drive, además de enviar resúmenes por Telegram.
  - **Complejidad:** Alta (54 nodos)

- **[2900-inventario-materiales.json](workflows/2900-inventario-materiales.json)**
  - **Descripción:** Este flujo automático gestiona la solicitud de materiales, desde la recepción hasta su aprobación y actualización en库存, incluyendo notificaciones de stock bajo. Integra Google Sheets y Supabase para mantener el seguimiento preciso del inventario.
  - **Complejidad:** Alta (51 nodos)

- **[2673-n8n-leaderboard-ai-agente.json](workflows/2673-n8n-leaderboard-ai-agente.json)**
  - **Descripción:** Este flujo automático recopila estadísticas de los creadores y flujos n8n desde GitHub, procesa la información con inteligencia artificial para generar un informe detallado en formato Markdown, lo convierte a HTML si es necesario, y lo comparte vía email o Telegram.
  - **Complejidad:** Alta (49 nodos)

- **[2922-n8n_creator_leaderboard_report.json](workflows/2922-n8n_creator_leaderboard_report.json)**
  - **Descripción:** Este flujo automático genera informes detallados sobre los creadores y flujos de trabajo en n8n. Utiliza herramientas como OpenAI GPT-4 y Google Gemini para analizar y sintetizar datos, y luego envía los resultados a Google Drive o Telegram.
  - **Complejidad:** Alta (49 nodos)

- **[0933-telegram_baserow_ai_assistant.json](workflows/0933-telegram_baserow_ai_assistant.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con Telegram mediante la recepción de mensajes (voz, texto o imagen), gestionarlos con herramientas como OpenAI para transcribir voz e analizar imágenes, mantener una memoria contextua utilizando Baserow y luego responder adecuadamente en cada modalidad.
  - **Complejidad:** Alta (48 nodos)

- **[1405-team_weekly_report_slack.json](workflows/1405-team_weekly_report_slack.json)**
  - **Descripción:** Envía informes semanales del equipo en Slack.
  - **Complejidad:** Alta (47 nodos)

- **[2988-line-bot-flow.json](workflows/2988-line-bot-flow.json)**
  - **Descripción:** Este flujo procesa mensajes de LINE, incluyendo textos, imágenes y namecards, para almacenar en Microsoft To Do y Teams, utilizando OpenRouter para extracciones y agentes de imagen.
  - **Complejidad:** Alta (45 nodos)

- **[1469-generate-instagram-content-from-top-ai.json](workflows/1469-generate-instagram-content-from-top-ai.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, web scraping, resumen, generación de contenido, monitoreo utilizando OpenAI/GPT, Telegram, Instagram con inteligencia artificial y APIs de forma programada.
  - **Complejidad:** Alta (44 nodos)

- **[2981-instagram_content_generator.json](workflows/2981-instagram_content_generator.json)**
  - **Descripción:** Este flujo automatiza la creación de contenido para Instagram basado en las tendencias más populares, utilizando IA para generar imágenes y publicarlas. Realiza scraping de tendencias específicas como #blender3d e isometric, filtra el contenido por imágenes, analiza las imágenes con GPT-4 y OpenAI, genera captions atractivas, crea imágenes nuevas con Flux AI, y verifica si el contenido ya existe en una base de datos para evitar duplicaciones. Publica en Instagram y envía notificaciones al canal de Telegram.
  - **Complejidad:** Alta (44 nodos)

- **[0983-telegram-resume-processing.json](workflows/0983-telegram-resume-processing.json)**
  - **Descripción:** Este flujo automático permite extraer información de un currículum en PDF mediante el chatbot de Telegram y genera una copia en formato PDF con Gotenberg.
  - **Complejidad:** Alta (43 nodos)

- **[1464-extract-data-from-resume-and-pdf.json](workflows/1464-extract-data-from-resume-and-pdf.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, extracción de datos, generación de contenido utilizando OpenAI/GPT, Telegram, Email/Gmail con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (43 nodos)

- **[2734-cv-extractor-telegram.json](workflows/2734-cv-extractor-telegram.json)**
  - **Descripción:** Este flujo automatiza la extracción y formateo de información de currículum vitae en formato HTML y PDF para Telegram. Recibe un archivo PDF de CV, extrae el texto, lo procesa con OpenAI para estructurar los datos y genera un documento HTML/convertedo en PDF.
  - **Complejidad:** Alta (43 nodos)

- **[2991-auto_create_publish_videos.json](workflows/2991-auto_create_publish_videos.json)**
  - **Descripción:** Este flujo automático crea y publica videos sociales con AI utilizando Telegram, GPT-4 y Blotato. Incluye desde la creación del video hasta su distribución en múltiples plataformas como Instagram, YouTube, TikTok, Facebook, entre otras.
  - **Complejidad:** Alta (42 nodos)

- **[1419-youtube-rss-notifications.json](workflows/1419-youtube-rss-notifications.json)**
  - **Descripción:** Envía notificaciones de nuevos videos de YouTube vía RSS.
  - **Complejidad:** Alta (41 nodos)

- **[1400-telegram_survey_bot.json](workflows/1400-telegram_survey_bot.json)**
  - **Descripción:** Bot de Telegram para encuestas.
  - **Complejidad:** Alta (40 nodos)

- **[0714-telegram-bot-ai-integration.json](workflows/0714-telegram-bot-ai-integration.json)**
  - **Descripción:** Este flujo automático procesa mensajes de texto, audio e imágenes de un bot de Telegram usando webhooks y la API de OpenAI para análisis.
  - **Complejidad:** Alta (39 nodos)

- **[1433-ai-powered-candidate-shortlisting-automation.json](workflows/1433-ai-powered-candidate-shortlisting-automation.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, extracción de datos, reclutamiento utilizando OpenAI/GPT, Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (39 nodos)

- **[1437-advanced-ai-demo-presented-at-ai.json](workflows/1437-advanced-ai-demo-presented-at-ai.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen utilizando OpenAI/GPT, Slack, Email/Gmail con inteligencia artificial mediante webhooks y APIs de forma programada.
  - **Complejidad:** Alta (39 nodos)

- **[2672-telegram-multimedia-ai.json](workflows/2672-telegram-multimedia-ai.json)**
  - **Descripción:** Este flujo automático permite procesar mensajes de Telegram (texto, voz y fotos) utilizando modelos de lenguaje para clasificación o análisis.
  - **Complejidad:** Alta (39 nodos)

- **[3107-ai-chatbot-memory-router.json](workflows/3107-ai-chatbot-memory-router.json)**
  - **Descripción:** Este flujo implementa un chatbot con memoria a largo plazo que utiliza herramientas de enrutamiento dinámico para almacenar y recuperar información usando Google Docs, además de enviar notificaciones por Telegram o Gmail.
  - **Complejidad:** Alta (39 nodos)

- **[0782-telegram-chatbot-sessions.json](workflows/0782-telegram-chatbot-sessions.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Telegram gestionar múltiples conversaciones manteniendo memoria e historial por sesión mediante Google Sheets.
  - **Complejidad:** Alta (38 nodos)

- **[1232-email-to-notion-tasks.json](workflows/1232-email-to-notion-tasks.json)**
  - **Descripción:** Este flujo automático analiza correos electrónicos entrantes con IA para crear tareas organizadas y detalladas en Notion. Integra Gmail (para recibir correos), Airtable (para gestionar rutas activas) y Notion API (para generar las páginas). También incluye mecanismos de error, como enviar notificaciones a correos específicos cuando ocurren problemas.
  - **Complejidad:** Alta (38 nodos)

- **[1509-venafi-cloud-slack-cert-bot.json](workflows/1509-venafi-cloud-slack-cert-bot.json)**
  - **Descripción:** Este flujo permite automatización, resumen, extracción de datos, generación de contenido, reportes utilizando OpenAI/GPT, Slack, Email/Gmail con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (38 nodos)

- **[2542-venafi_slack_certbot.json](workflows/2542-venafi_slack_certbot.json)**
  - **Descripción:** Este flujo automático integra Slack y Venafi para gestionar solicitudes de certificados basándose en análisis de riesgo mediante VirusTotal.
  - **Complejidad:** Alta (38 nodos)

- **[2796-slack-csr-approval.json](workflows/2796-slack-csr-approval.json)**
  - **Descripción:** Este flujo automático gestiona la solicitud de certificados digitales a través de Slack. Analiza las amenazas usando VirusTotal y genera una confirmación automática o un informe para aprobación manual.
  - **Complejidad:** Alta (38 nodos)

- **[2919-gestor_consultas_medicas.json](workflows/2919-gestor_consultas_medicas.json)**
  - **Descripción:** Este flujo gestiona tareas de reagendamiento de consultas médicas y envía recordatorios a través de WhatsApp y Telegram utilizando Google Calendar y Tasks, integrando herramientas como OpenAI para procesar texto y mensajes.
  - **Complejidad:** Alta (38 nodos)

- **[1401-logistica-telegram-flow.json](workflows/1401-logistica-telegram-flow.json)**
  - **Descripción:** Automatiza notificaciones logísticas por Telegram.
  - **Complejidad:** Alta (37 nodos)

- **[1473-hr-job-posting-and-evaluation-with-ai.json](workflows/1473-hr-job-posting-and-evaluation-with-ai.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, extracción de datos, generación de contenido, monitoreo utilizando OpenAI/GPT, Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs de forma programada.
  - **Complejidad:** Alta (36 nodos)

- **[2699-telegram-support-flow.json](workflows/2699-telegram-support-flow.json)**
  - **Descripción:** Este flujo automático gestiona mensajes en Telegram mediante un bot, creando tópicos personalizados para cada usuario y转发ing mensajes al grupo de soporte o canal Broadcast. Utiliza Redis para almacenar datos y asegurar la integridad de los mensajes.
  - **Complejidad:** Alta (36 nodos)

- **[2772-pc_repair_booking.json](workflows/2772-pc_repair_booking.json)**
  - **Descripción:** Este flujo automático gestiona la agenda de citas y seguimientos para un servicio de reparación de PC y laptops. Utiliza Twilio para recibir mensajes SMS, Airtable para manejar sesiones y conversaciones, y OpenAI con agentes de lenguaje para interactuar con los clientes, además de Cal.com para programar citas.
  - **Complejidad:** Alta (36 nodos)

- **[2947-automate-support-issues.json](workflows/2947-automate-support-issues.json)**
  - **Descripción:** Este flujo automático gestiona la resolución de problemas de soporte utilizando IA para clasificar y resolver incidencias en Jira. Analiza los comentarios, utiliza agentes de conocimiento, y notifica por Slack si es necesario.
  - **Complejidad:** Alta (36 nodos)

- **[2882-contact_discovery.json](workflows/2882-contact_discovery.json)**
  - **Descripción:** Este flujo automatiza la descubierta de tomadores de decisiones en empresas utilizando Google Sheets y Apollo.io. Extrae información de empresas, encuentra contactos clave, realiza una verificación humana a través de Slack y enrriquece los datos con APIs para luego actualizar una base de contactos verificados.
  - **Complejidad:** Alta (35 nodos)

- **[3213-import-productboard-to-snowflake.json](workflows/3213-import-productboard-to-snowflake.json)**
  - **Descripción:** Este flujo importa datos de Productboard (notas, empresas y características) a Snowflake. Utiliza solicitudes HTTP para recuperar información de Productboard, realiza mapeos manuales y actualiza tablas en Snowflake. Incluye unavisador en Slack con resúmenes semanales.
  - **Complejidad:** Alta (35 nodos)

- **[3280-trading-agent-analysis.json](workflows/3280-trading-agent-analysis.json)**
  - **Descripción:** Este flujo automático permite a un usuario realizar un análisis técnico de acciones mediante un agente de inteligencia artificial en Telegram. Recibe mensajes, procesa texto o voz, genera gráficos personalizados y envía el análisis al usuario.
  - **Complejidad:** Alta (35 nodos)

- **[1510-vassistant-for-hubspot-chat-using-openai-airtable.json](workflows/1510-vassistant-for-hubspot-chat-using-openai-airtable.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (34 nodos)

- **[2730-slack-command-flow.json](workflows/2730-slack-command-flow.json)**
  - **Descripción:** Este flujo maneja comandos en Slack, valida tokens, crea hilos y ejecuta workflows según configuración. Responde a usuarios con ayuda o comandos desconocidos.
  - **Complejidad:** Alta (34 nodos)

- **[2761-slack-calendar-event.json](workflows/2761-slack-calendar-event.json)**
  - **Descripción:** Este flujo automático monitorea un canal de Slack para mensajes etiquetados con emoji de calendario (📅) y gestiona la creación y actualización de eventos en Google Calendar. Utiliza inteligencia artificial para extraer detalles del evento, crea uno nuevo si es necesario o agrega asistentes a un evento existente basado en las reacciones de los usuarios.
  - **Complejidad:** Alta (33 nodos)

- **[1130-auto-email-campaign-followup.json](workflows/1130-auto-email-campaign-followup.json)**
  - **Descripción:** Este flujo automatizado gestiona campañas de email con seguimiento posterior. Obtiene información de una hoja de Google, clasifica hilos de conversación y envía mensajes automatizados según un cronograma predefinido.
  - **Complejidad:** Alta (32 nodos)

- **[1435-ai-powered-information-monitoring-with-openai-google-sheets-ai-slack.json](workflows/1435-ai-powered-information-monitoring-with-openai-google-sheets-ai-slack.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, web scraping, resumen, extracción de datos, generación de contenido, monitoreo utilizando OpenAI/GPT, Slack, Webhook con inteligencia artificial mediante webhooks y APIs de forma programada.
  - **Complejidad:** Alta (31 nodos)

- **[2597-monitor-ia-articulos-slack.json](workflows/2597-monitor-ia-articulos-slack.json)**
  - **Descripción:** Este flujo automatizado monitorea artículos relevantes en tiempo real utilizando RSS feeds, clasifica su contenido con IA y genera resúmenes formateados para Slack.
  - **Complejidad:** Alta (31 nodos)

- **[3080-email-ai-management.json](workflows/3080-email-ai-management.json)**
  - **Descripción:** Este flujo automático gestiona emails de manera eficiente utilizando inteligencia artificial para resumir, clasificar y responder automáticamente. Utiliza Qdrant para almacenar vectores de documentos, OpenAI para embeddings y LLMs para generar respuestas, además de integrar con Gmail y Outlook.
  - **Complejidad:** Alta (31 nodos)

- **[3092-woocommerce-chatbot-posventa.json](workflows/3092-woocommerce-chatbot-posventa.json)**
  - **Descripción:** Este flujo automático implementa un chatbot de soporte pos-venta integrado con WooCommerce que utiliza inteligencia artificial para manejar consultas de clientes, recuperar información de órdenes, verificar identidad y proporcionar asistencia mediante OpenAI y Qdrant. Incluye escalado a operadores humanos vía Telegram si es necesario.
  - **Complejidad:** Alta (31 nodos)

- **[3301-antispam_discord.json](workflows/3301-antispam_discord.json)**
  - **Descripción:** Este flujo automático detecta y modera mensajes spam en Discord usando IA para clasificar textos, notifica a los moderadores y realiza acciones según la decisión humana.
  - **Complejidad:** Alta (30 nodos)

- **[1096-mattermost-standup-bot.json](workflows/1096-mattermost-standup-bot.json)**
  - **Descripción:** Este flujo automático permite al bot de reuniones en Mattermost gestionar configuraciones y enviar alertas programadas.
  - **Complejidad:** Alta (29 nodos)

- **[1264-slack-image-uploader.json](workflows/1264-slack-image-uploader.json)**
  - **Descripción:** Sube imágenes automáticamente a un canal de Slack.
  - **Complejidad:** Alta (29 nodos)

- **[2684-threat-intelligence-scan.json](workflows/2684-threat-intelligence-scan.json)**
  - **Descripción:** Este flujo automatiza la inspección de amenazas cibernéticas realizando análisis en VirusTotal y Greynoise. Recibe URLs o IPs mediante un formulario o Webhook, realiza DNS Lookup para obtener IPs, envía a VirusTotal para escaneo y consulta a Greynoise, combinando resultados para enviar reportes detallados por correo electrónico y Slack.
  - **Complejidad:** Alta (29 nodos)

- **[2786-telegram_bot_workflow.json](workflows/2786-telegram_bot_workflow.json)**
  - **Descripción:** Este flujo utiliza Telegram para manejar diferentes tipos de mensajes y comandos, como texto, fotos, archivos, voz y botones. Detecta el tipo de mensaje y actúa en consecuencia, mostrando un menú contextual o manejando pagos.
  - **Complejidad:** Alta (29 nodos)

- **[3155-telegram-neuroai-integration.json](workflows/3155-telegram-neuroai-integration.json)**
  - **Descripción:** Este flujo utiliza la API de NeurochainAI para procesar mensajes y generar respuestas o imágenes en Telegram. Detecta comandos con /flux, envía prompts y gestiona errores.
  - **Complejidad:** Alta (29 nodos)

- **[3327-telegram-ai-bot.json](workflows/3327-telegram-ai-bot.json)**
  - **Descripción:** Este flujo Telegram implementa un bot que procesa comandos /flux para generar imágenes y respuestas textuales con NeurochainAI. Incluye manejo de errores y enlaces de reintentar.
  - **Complejidad:** Alta (29 nodos)

- **[1152-qualys-scan-workflow.json](workflows/1152-qualys-scan-workflow.json)**
  - **Descripción:** Este flujo automático inicia un escaneo en Qualys a través de Slack y verifica su estado cada 5 minutos hasta completarse.
  - **Complejidad:** Alta (28 nodos)

- **[2902-financial-tracker-bot.json](workflows/2902-financial-tracker-bot.json)**
  - **Descripción:** Este flujo automatiza el seguimiento financiero al recibir facturas por Telegram, extraer datos con Google Gemini, estructurarlos en Notion y generar reportes visuales.
  - **Complejidad:** Alta (28 nodos)

- **[3050-telegram-ai-document-assistant.json](workflows/3050-telegram-ai-document-assistant.json)**
  - **Descripción:** Este flujo crea un asistente de chatbot en Telegram que procesa documentos PDF y utiliza Google Gemini para generar respuestas basadas en el contenido almacenado en Supabase.
  - **Complejidad:** Alta (28 nodos)

- **[3149-outlook-ai-email-assistant.json](workflows/3149-outlook-ai-email-assistant.json)**
  - **Descripción:** Este flujo automatiza la gestión de correos electrónicos en Microsoft Outlook usando inteligencia artificial para categorizar y priorizar emails. Extrae información relevante, procesa el cuerpo del correo para eliminar formato HTML, consulta bases de datos externas como Airtable y Monday.com para contexto adicional y utiliza el modelo OpenAI para asignar categorías. Actualiza la importancia y categorías en Outlook según las reglas definidas.
  - **Complejidad:** Alta (28 nodos)

- **[0957-noco-kanban-ai-monitoring.json](workflows/0957-noco-kanban-ai-monitoring.json)**
  - **Descripción:** Este flujo automático analiza incidentes mediante IA para asignar categorías y parámetros, los cuales se insertan en una tabla de NocoDB. Luego verifica periódicamente el estado de las tareas sin notificaciones excesivas.
  - **Complejidad:** Alta (27 nodos)

- **[1472-hr-it-helpdesk-chatbot-with-audio-transcription.json](workflows/1472-hr-it-helpdesk-chatbot-with-audio-transcription.json)**
  - **Descripción:** Este flujo permite chatbot, transcripción, extracción de datos, generación de contenido utilizando OpenAI/GPT, Telegram, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (27 nodos)

- **[2646-telegram-helpdesk-chatbot.json](workflows/2646-telegram-helpdesk-chatbot.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Telegram mantener una conversación contextualizada con los usuarios utilizando almacenamiento vectorial en PostgreSQL y memoria de chat para respuestas personalizadas.
  - **Complejidad:** Alta (27 nodos)

- **[2789-notion-task-reminder.json](workflows/2789-notion-task-reminder.json)**
  - **Descripción:** Este flujo automatiza la creación de un correo semanal con recordatorios y notificaciones push sobre tareas pendientes en Notion. Recupera las tareas desde una base de datos de Notion, filtra y ordena por fecha límite, genera un HTML con los detalles de cada tarea y envía un correo electrónico o una notificación Pushover si hay tareas vencidas.
  - **Complejidad:** Alta (27 nodos)

- **[2999-hr-it-chatbot-transcription.json](workflows/2999-hr-it-chatbot-transcription.json)**
  - **Descripción:** Este flujo configura un chatbot para asistencia HR e IT que procesa mensajes de texto y audio en Telegram, utiliza embeddings OpenAI para transcripciones y almacenamiento vectorial PostgreSQL, respondiendo preguntas basadas en políticas internas.
  - **Complejidad:** Alta (27 nodos)

- **[3109-parents-bot-memory.json](workflows/3109-parents-bot-memory.json)**
  - **Descripción:** Este flujo utiliza un chatbot para manejar mensajes de Telegram, transcribe voz a texto, consulta información y almacena datos en vectores para mejorar la memoria contextual.
  - **Complejidad:** Alta (27 nodos)

- **[3124-actualizar_n8n.json](workflows/3124-actualizar_n8n.json)**
  - **Descripción:** Este flujo automatiza la actualización de n8n verificando versiones en GitHub, notificando por Telegram si hay una nueva versión y pidiendo confirmación antes de actualizar.
  - **Complejidad:** Alta (27 nodos)

- **[0976-research-report-gen.json](workflows/0976-research-report-gen.json)**
  - **Descripción:** Este flujo automático permite generar informes de investigación utilizando OpenAI, Wikipedia, Google Search y enviarlos por correo electrónico o Telegram.
  - **Complejidad:** Alta (26 nodos)

- **[1478-invoice-data-extraction-with-llamaparse-and-openai.json](workflows/1478-invoice-data-extraction-with-llamaparse-and-openai.json)**
  - **Descripción:** Este flujo permite extracción de datos, procesamiento de facturas utilizando OpenAI/GPT, Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (26 nodos)

- **[2638-telegram-github-agent.json](workflows/2638-telegram-github-agent.json)**
  - **Descripción:** Automatiza la curación y publicación en Telegram de discusiones destacadas sobre proyectos GitHub desde Hacker News.
  - **Complejidad:** Alta (26 nodos)

- **[2950-automate-siem-enrichment-mitre.json](workflows/2950-automate-siem-enrichment-mitre.json)**
  - **Descripción:** Este flujo automatiza la enriquecimiento de alertas de SIEM mediante el marco MITRE ATT&CK, usando Qdrant como vector store y Zendesk para actualizar incidentes con información contextualizada.
  - **Complejidad:** Alta (26 nodos)

- **[3253-cyber-attack-vector-store.json](workflows/3253-cyber-attack-vector-store.json)**
  - **Descripción:** Este flujo automatiza la gestión de incidentes cibernéticos usando MITRE ATT&CK. Analiza alertas SIEM con LLM, consulta bases vectoriales Qdrant y actualiza Zendesk.
  - **Complejidad:** Alta (26 nodos)

- **[0836-email-phishing-analysis.json](workflows/0836-email-phishing-analysis.json)**
  - **Descripción:** Este flujo automático analiza y clasifica correos electrónicos sospechosos mediante ChatGPT para determinar si son fraudulentos o no. Las alertas de Gmail y Outlook capturan mensajes entrantes, que luego se procesan con IA para evaluar su naturaleza.
  - **Complejidad:** Alta (25 nodos)

- **[1488-qualifying-appointment-requests-with-ai-n8n-forms.json](workflows/1488-qualifying-appointment-requests-with-ai-n8n-forms.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, transcripción, resumen utilizando OpenAI/GPT, Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs de forma programada.
  - **Complejidad:** Alta (25 nodos)

- **[2933-monitoreo_precios.json](workflows/2933-monitoreo_precios.json)**
  - **Descripción:** Este flujo automatiza la monitoreo de precios en diferentes sitios web. Extrae los precios de productos específicos utilizando selección por CSS, actualiza los datos guardados y envía notificaciones si hay una disminución de precio.
  - **Complejidad:** Alta (25 nodos)

- **[0001-nostr-damus-ai-report.json](workflows/0001-nostr-damus-ai-report.json)**
  - **Descripción:** Este flujo automatizado analiza contenido Nostr con el hashtag #damus usando modelos de lenguaje para generar informes y luego envía los resultados por correo electrónico y Telegram.
  - **Complejidad:** Alta (24 nodos)

- **[1147-notion-tareas-slack-automatizado.json](workflows/1147-notion-tareas-slack-automatizado.json)**
  - **Descripción:** Este flujo automático envía recordatorios de tareas pendientes almacenadas en una base de datos de Notion mediante mensajes directos en Slack, filtrando por usuarios específicos cada día entre lunes y viernes a las 9:00 AM.
  - **Complejidad:** Alta (24 nodos)

- **[1254-_damus-report.json](workflows/1254-_damus-report.json)**
  - **Descripción:** Genera reportes de Damus y envía notificaciones por Gmail y Telegram.
  - **Complejidad:** Alta (24 nodos)

- **[2890-email_bot_transcripciones.json](workflows/2890-email_bot_transcripciones.json)**
  - **Descripción:** Este flujo automático procesa emails nuevos, utiliza OpenAI para determinar si necesitan respuesta y transcribe audios de Telegram para generar respuestas formateadas en Gmail.
  - **Complejidad:** Alta (24 nodos)

- **[3078-ai_tech_newsletter.json](workflows/3078-ai_tech_newsletter.json)**
  - **Descripción:** Este flujo automatiza la creación de un newsletter tecnológico personalizado utilizando RSS feeds, OpenAI y Gmail. Cada día, recoge artículos de noticias desde fuentes como Wired y TechCrunch, los procesa y almacena en un vector store. Semanalmente, utiliza OpenAI para resumir los artículos más relevantes según tus intereses y envía la recapByEmail.
  - **Complejidad:** Alta (24 nodos)

- **[3079-extract-spend-details.json](workflows/3079-extract-spend-details.json)**
  - **Descripción:** Este flujo extrae y procesa detalles de gastos a partir de correos electrónicos relacionados con pagos e invoices utilizando Gmail como origen de datos. Analiza emails etiquetados específicamente para detectar transacciones, invoice y pagos, utiliza LLMs (Google Gemini y Groq) para estructurar la información y finalmente inserta los datos en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Alta (24 nodos)

- **[3292-breach-monitor.json](workflows/3292-breach-monitor.json)**
  - **Descripción:** Este flujo automático monitorea continuamente por nuevos brechas en haveibeenpwned.com y envía alertas cuando se detectan. Almacena la información de los últimos breaches en un archivo cache.json para evitar notificaciones duplicadas.
  - **Complejidad:** Alta (24 nodos)

- **[3335-github-releases-tracker.json](workflows/3335-github-releases-tracker.json)**
  - **Descripción:** Este flujo rastrea los lanzamientos de proyectos en GitHub y extrae información relevante para enviar mensajes formatizados a Slack. Configura repositorios seguidos, verifica releases periódicamente con un temporizador y utiliza Redis para cachear IDs.
  - **Complejidad:** Alta (24 nodos)

- **[0880-telegram-schedule-ai.json](workflows/0880-telegram-schedule-ai.json)**
  - **Descripción:** Este flujo permite que un chatbot de Telegram interactúe con IA utilizando memoria conversacional y datos de agenda extraídos de una hoja de Google, enviando respuestas tanto a la aplicación n8n como al usuario de Telegram.
  - **Complejidad:** Alta (23 nodos)

- **[0897-telegram-schedule-bot.json](workflows/0897-telegram-schedule-bot.json)**
  - **Descripción:** Este flujo permite a un chatbot interactuar con la agenda de eventos desde una hoja de cálculo Google usandoTelegram.
  - **Complejidad:** Alta (23 nodos)

- **[0972-slack-qualys-shortcut.json](workflows/0972-slack-qualys-shortcut.json)**
  - **Descripción:** Este flujo automático permite a un bot de Slack integrar la creación de informes e iniciativas de escaneo con el sistema Qualys, procesando interacciones del usuario mediante webhooks.
  - **Complejidad:** Alta (23 nodos)

- **[1151-qualys-slack-integration.json](workflows/1151-qualys-slack-integration.json)**
  - **Descripción:** Este flujo automático permite interactuar con la API de Qualys desde Slack mediante modales, generando informes y ejecutando escaneos de vulnerabilidades basados en entradas del usuario.
  - **Complejidad:** Alta (23 nodos)

- **[1461-enhance-security-operations-with-the-slack-bot.json](workflows/1461-enhance-security-operations-with-the-slack-bot.json)**
  - **Descripción:** Este flujo permite automatización, resumen, extracción de datos, generación de contenido, reportes utilizando Slack, Webhook, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (23 nodos)

- **[2665-telegram-deepseek-bot.json](workflows/2665-telegram-deepseek-bot.json)**
  - **Descripción:** Este flujo automatizado permite a un chatbot interactuar con los usuarios de Telegram mediante la integración del modelo de IA DeepSeek-V3/Chat. Analiza los mensajes, verifica datos de usuario, mantiene memoria a largo plazo en Google Docs y responde de manera personalizada.
  - **Complejidad:** Alta (23 nodos)

- **[2850-nutrientes_dieta.json](workflows/2850-nutrientes_dieta.json)**
  - **Descripción:** Este flujo procesa mensajes de Telegram para extraer nutrientes y macros de la dieta diaria. Si es un mensaje de voz, lo transcribe; luego estructura los datos y los almacena en Google Sheets.
  - **Complejidad:** Alta (23 nodos)

- **[2951-automate-rfp-openai.json](workflows/2951-automate-rfp-openai.json)**
  - **Descripción:** Automatiza el proceso de RFP mediante la integración con OpenAI para extraer preguntas, generar respuestas y notificar vía Slack y correo electrónico.
  - **Complejidad:** Alta (23 nodos)

- **[3156-deepseek-telegram-agent.json](workflows/3156-deepseek-telegram-agent.json)**
  - **Descripción:** Este flujo utiliza un agente de inteligencia artificial DeepSeek integrado con Telegram para manejar conversaciones, validando usuarios y chats, procesando mensajes de texto, audio e imágenes, recuperando记忆es长期 desde Google Docs y respondiendo a través de la API de Telegram.
  - **Complejidad:** Alta (23 nodos)

- **[3298-pomodoro-bot.json](workflows/3298-pomodoro-bot.json)**
  - **Descripción:** Este flujo gestiona sesiones de trabajo Pomodoro con Telegram y registra actividades en Google Sheets. Detecta comandos como /start y /stop, maneja intervalos de trabajo y descanso, y registra estadísticas.
  - **Complejidad:** Alta (23 nodos)

- **[0943-Telegram-Buffered-Messages.json](workflows/0943-Telegram-Buffered-Messages.json)**
  - **Descripción:** Este flujo automatizado permite al chatbot de Telegram combinar mensajes recibidos en intervalos cortos usando una base de datos Supabase y mantener memoria contextualizada para generar respuestas cohesivas.
  - **Complejidad:** Alta (22 nodos)

- **[0996-speech_assistant_telegram.json](workflows/0996-speech_assistant_telegram.json)**
  - **Descripción:** Este flujo utiliza la API de Google Gemini y OpenAI junto con n8n para procesar mensajes en Telegram, ya sean textuales o de voz. Analiza el contenido, proporciona retroalimentación sobre claridad, estructura y contenido, y permite refinar discursos colaborativamente.
  - **Complejidad:** Alta (22 nodos)

- **[1153-qualys-report-automation.json](workflows/1153-qualys-report-automation.json)**
  - **Descripción:** Este flujo automático integra la API de Qualys con Slack para generar informes periódicos y enviarlos como adjuntos en el canal especificado.
  - **Complejidad:** Alta (22 nodos)

- **[1449-chat-with-pdf-docs-using-ai-quoting-sources.json](workflows/1449-chat-with-pdf-docs-using-ai-quoting-sources.json)**
  - **Descripción:** Este flujo permite chatbot, generación de contenido utilizando OpenAI/GPT, Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (22 nodos)

- **[3037-youtube-summarizer-gpt.json](workflows/3037-youtube-summarizer-gpt.json)**
  - **Descripción:** Este flujo extrae y procesa transcripciones de videos de YouTube para resumirlas y mantener una conversación sobre su contenido utilizando GPT-4o-mini e interactúa a través de Telegram.
  - **Complejidad:** Alta (22 nodos)

- **[3089-automated-backups-google-drive.json](workflows/3089-automated-backups-google-drive.json)**
  - **Descripción:** Este flujo automático programa backups diarios de los workflows guardando archivos JSON en Google Drive con una marca de fecha y hora. Maneja la retención de archivos manteniendo solo las copias más recientes de siete días, eliminando las antiguas, y envía notificaciones vía Telegram al completar el proceso.
  - **Complejidad:** Alta (22 nodos)

- **[1118-telegram-weather-bot.json](workflows/1118-telegram-weather-bot.json)**
  - **Descripción:** Este flujo automático permite a un bot de Telegram ofrecer datos meteorológicos mediante gráficos generados en R, siguiendo un protocolo definido por los comandos /start y /getweather.
  - **Complejidad:** Alta (21 nodos)

- **[2674-ai-chatbot-memory.json](workflows/2674-ai-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite a un chatbot almacenar y recuperar memoria de largo plazo e información puntual en Google Docs para mantener conversaciones contextualizadas vía Telegram.
  - **Complejidad:** Alta (21 nodos)

- **[2867-telegram-voz-tareas.json](workflows/2867-telegram-voz-tareas.json)**
  - **Descripción:** Este flujo utiliza Telegram para recibir mensajes de voz, descargar y transcribir audios con OpenAI, y gestionar tareas en Google Tasks a través de MCP Server.
  - **Complejidad:** Alta (21 nodos)

- **[3024-ssl-expiry-alert.json](workflows/3024-ssl-expiry-alert.json)**
  - **Descripción:** Este flujo automático monitorea la expiración de certificados SSL de sitios web y envía alertas vía correo electrónico o Telegram cuando los certificados están por vencerse.
  - **Complejidad:** Alta (21 nodos)

- **[3132-ai-agent-chatbot-memory.json](workflows/3132-ai-agent-chatbot-memory.json)**
  - **Descripción:** Este flujo implementa un agente de chatbot con memoria a largo plazo y almacenamiento de notas integrados, utilizando Google Docs para guardar memorias y notas, y Telegram para las respuestas. El sistema utiliza diferentes modelos de lenguaje como GPT-4o-mini y DeepSeek-V3 para procesar mensajes y mantener una conversación contextualizada.
  - **Complejidad:** Alta (21 nodos)

- **[3167-slack-ai-chatbot-rag.json](workflows/3167-slack-ai-chatbot-rag.json)**
  - **Descripción:** Flujo de un chatbot en Slack integrado con RAG que utiliza embeddings y vectores de Qdrant para responder preguntas basadas en documentos internos.
  - **Complejidad:** Alta (21 nodos)

- **[3277-water-drink-reminder.json](workflows/3277-water-drink-reminder.json)**
  - **Descripción:** Este flujo automatiza la gestión de un sistema de recordatorio de beber agua. Recoge datos desde Google Sheets, utiliza OpenAI para generar mensajes motivacionales personalizados y envía notificaciones a Slack con botones interactivos.
  - **Complejidad:** Alta (21 nodos)

- **[1475-it-ops-ai-slackbot-workflow-chat.json](workflows/1475-it-ops-ai-slackbot-workflow-chat.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, generación de contenido utilizando OpenAI/GPT, Slack, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (20 nodos)

- **[2785-it-slack-ai-agent.json](workflows/2785-it-slack-ai-agent.json)**
  - **Descripción:** Este flujo utiliza n8n para manejar mensajes de Slack, respondiendo a los usuarios con respuestas generadas por OpenAI y consultando Confluence. Incluye verificación de webhooks, memoria contextual y eliminación de mensajes iniciales.
  - **Complejidad:** Alta (20 nodos)

- **[2916-telegram-rag-pdf.json](workflows/2916-telegram-rag-pdf.json)**
  - **Descripción:** Este flujo automático procesa un documento PDF enviado por Telegram, lo carga en Pinecone para realizar búsquedas de preguntas y respuestas con inteligencia artificial.
  - **Complejidad:** Alta (20 nodos)

- **[2940-dmarc-processing-flow.json](workflows/2940-dmarc-processing-flow.json)**
  - **Descripción:** Este flujo automático procesa informes DMARC recibidos por correo electrónico, extrae y formatea los datos relevantes, y los inserta en una base de datos MySQL. Si hay fallos en DKIM o SPF, envía notificaciones a Slack y correo electrónico.
  - **Complejidad:** Alta (20 nodos)

- **[3016-it-slack-ai-bot.json](workflows/3016-it-slack-ai-bot.json)**
  - **Descripción:** Este flujo automático gestiona las consultas IT en Slack mediante un chatbot integrado con OpenAI y Confluence. Analiza mensajes, verifica webhooks, evita bots y proporciona respuestas basadas en el conocimiento de la empresa.
  - **Complejidad:** Alta (20 nodos)

- **[3052-email-chatbot-telegram-vector.json](workflows/3052-email-chatbot-telegram-vector.json)**
  - **Descripción:** Este flujo implementa un chatbot que utiliza Telegram y PostgreSQL con vectores para realizar búsquedas semánticas y estructuradas en bases de datos de correo electrónico, permitiendo una interacción avanzada y contextualizada.
  - **Complejidad:** Alta (20 nodos)

- **[3264-zoom-stripe-payments.json](workflows/3264-zoom-stripe-payments.json)**
  - **Descripción:** Este flujo automático crea reuniones en Zoom y enlaza pagos seguros con Stripe para eventos. Automatiza la creación de citas, facturaclientes y envía notificaciones por correo electrónico con los detalles necesarios.
  - **Complejidad:** Alta (20 nodos)

- **[3303-email-pdf-classifier.json](workflows/3303-email-pdf-classifier.json)**
  - **Descripción:** Este flujo automático utiliza n8n para analizar emails con adjuntos PDF y clasificarlos usando OpenAI. Crea carpetas en Google Drive según fechas, verifica si los archivos son facturas/receipts y los almacena allí o los envía por correo electrónico.
  - **Complejidad:** Alta (20 nodos)

- **[3330-telegram-pdf-integration.json](workflows/3330-telegram-pdf-integration.json)**
  - **Descripción:** Este flujo procesa un archivo PDF enviado por Telegram, lo carga en Pinecone para permitir búsquedas y contestaciones basadas en el contenido.
  - **Complejidad:** Alta (20 nodos)

- **[0923-customer-support-ticketing.json](workflows/0923-customer-support-ticketing.json)**
  - **Descripción:** Este flujo automático monitorea un canal de Slack específico (n8n-tickets) en busca de mensajes con el ticket emoji. Cuando detecta uno nuevo, consulta Linear para ver si ya existe un ticket correspondiente y, si no lo encuentra, utiliza ChatGPT para generar un título descriptivo, una descripción resumida, sugerencias para resolver la incidencia y determinar su prioridad basándose en el mensaje del usuario.
  - **Complejidad:** Alta (19 nodos)

- **[1456-customer-support-channel-and-ticketing-slack.json](workflows/1456-customer-support-channel-and-ticketing-slack.json)**
  - **Descripción:** Este flujo permite chatbot, resumen, generación de contenido, monitoreo utilizando OpenAI/GPT, Slack, Linear con inteligencia artificial y APIs de forma programada.
  - **Complejidad:** Alta (19 nodos)

- **[1494-sentiment-analysis-tracking-on-support-slack.json](workflows/1494-sentiment-analysis-tracking-on-support-slack.json)**
  - **Descripción:** Este flujo permite chatbot, análisis de sentimientos, resumen, extracción de datos, monitoreo, reportes utilizando OpenAI/GPT, Slack, Webhook con inteligencia artificial mediante webhooks y APIs de forma programada.
  - **Complejidad:** Alta (19 nodos)

- **[2724-social-activity-email.json](workflows/2724-social-activity-email.json)**
  - **Descripción:** Este flujo automático recopila tweets recientes de Twitter e publicaciones de LinkedIn de empresas y envía un correo electrónico con la actividad social a las direcciones email configuradas.
  - **Complejidad:** Alta (19 nodos)

- **[2800-monitor-github.json](workflows/2800-monitor-github.json)**
  - **Descripción:** Este flujo monitorea múltiples repositorios de GitHub sin polling, registrando y manejando webhooks para recibir notificaciones de eventos como empujes y solicitudes de pull.
  - **Complejidad:** Alta (19 nodos)

- **[3165-sentiment-linear-slack.json](workflows/3165-sentiment-linear-slack.json)**
  - **Descripción:** Este flujo monitorea continuamente las conversaciones en los problemas de soporte de Linear, realiza un análisis de sentimiento en los comentarios y notifica vía Slack si el sentimiento pasa a ser negativo.
  - **Complejidad:** Alta (19 nodos)

- **[3197-slack-to-linear-tickets.json](workflows/3197-slack-to-linear-tickets.json)**
  - **Descripción:** Este flujo automático monitorea un canal de Slack para mensajes con la emoji de ticket, utiliza OpenAI para generar el título y descripción de los tickets, y crea incidentes en Linear si no existen duplicados.
  - **Complejidad:** Alta (19 nodos)

- **[3228-linear-sentiment-monitor.json](workflows/3228-linear-sentiment-monitor.json)**
  - **Descripción:** Este flujo automatiza la monitorización de los problemas activos en Linear, realiza un análisis de sentimiento en los comentarios de las issues utilizando OpenAI y actualiza una tabla en Airtable con el estado emocional. Detecta transiciones de sentimiento negativo para enviar notificaciones a Slack.
  - **Complejidad:** Alta (19 nodos)

- **[0794-fireflies-ai-agent-tasks-notification.json](workflows/0794-fireflies-ai-agent-tasks-notification.json)**
  - **Descripción:** Este flujo automático captura transcripciones de reuniones en Fireflies.ai y utiliza un agente AI basado en OpenAI para generar tareas en Airtable según puntos clave del encuentro. Además, envía notificaciones específicas a clientes sobre sus pendientes mediante Gmail si son relevantes y programa eventos de Google Calendar si se requieren llamadas posteriores.
  - **Complejidad:** Alta (18 nodos)

- **[0900-n8n-lemlist-reply-classification.json](workflows/0900-n8n-lemlist-reply-classification.json)**
  - **Descripción:** Clasifica respuestas de Lemplist con OpenAI y automatiza la gestión, enviando alertas a Slack o desuscibriendo interesados.
  - **Complejidad:** Alta (18 nodos)

- **[0949-dsp_telegram_tutor.json](workflows/0949-dsp_telegram_tutor.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Telegram mantener una conversación contextualizada sobre temas de procesamiento de señales, utilizando herramientas como Wikipedia y calculadora para resolver problemas.
  - **Complejidad:** Alta (18 nodos)

- **[0970-buffer-chat-twilio-redis.json](workflows/0970-buffer-chat-twilio-redis.json)**
  - **Descripción:** Este flujo utiliza Redis para almacenar mensajes de usuario y Twilio para recibir entradas por SMS, permitiendo a la AI agent procesar múltiples mensajes enlazados como si fueran uno solo después de verificar que no hay nuevos mensajes pendientes.
  - **Complejidad:** Alta (18 nodos)

- **[1117-telegram-multilang-bot.json](workflows/1117-telegram-multilang-bot.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Telegram mantener registros en una base de datos y enviar respuestas multilingües según el idioma del usuario.
  - **Complejidad:** Alta (18 nodos)

- **[1180-rss-telegram-monitor.json](workflows/1180-rss-telegram-monitor.json)**
  - **Descripción:** Este flujo automatizado analiza RSS de Instagram y Weibo para enviar actualizaciones por Telegram.
  - **Complejidad:** Alta (18 nodos)

- **[2774-chat-flow-buffer.json](workflows/2774-chat-flow-buffer.json)**
  - **Descripción:** Este flujo utiliza Redis y Twilio para manejar mensajes de chat, pausando la ejecución por 5 segundos y verificando si el último mensaje coincide con el ingresado. Si coincide, envía una respuesta única basada en todos los mensajes bufferizados usando OpenAI.
  - **Complejidad:** Alta (18 nodos)

- **[2839-automaton-ics-calendario.json](workflows/2839-automaton-ics-calendario.json)**
  - **Descripción:** Este flujo automatiza la extracción de fechas y eventos de un archivo Excel usando Cloudflare para convertirlo a formato legible, luego utiliza el modelo Gemini para extraer información estructurada y crea un calendario ICS para compartir via email.
  - **Complejidad:** Alta (18 nodos)

- **[3011-flujo-analisis-crowdstrike-detecciones.json](workflows/3011-flujo-analisis-crowdstrike-detecciones.json)**
  - **Descripción:** Este flujo automático analiza las detecciones de CrowdStrike, busca indicadores de compromiso (IOCs) en VirusTotal y crea un ticket en Jira, además de enviar una notificación a Slack.
  - **Complejidad:** Alta (18 nodos)

- **[3293-youtube-notificacion-videos.json](workflows/3293-youtube-notificacion-videos.json)**
  - **Descripción:** Este flujo utiliza la API de YouTube para buscar y filtrar videos de canales subscriptos, detectando aquellos con duración mayor a 61 segundos y enviando notificaciones por correo electrónico.
  - **Complejidad:** Alta (18 nodos)

- **[0939-gmail-gemini-email-management.json](workflows/0939-gmail-gemini-email-management.json)**
  - **Descripción:** Este flujo automático utiliza Google Gemini AI junto con Gmail OAuth2 para clasificar correos electrónicos mediante un modelo de machine learning. Los correos se evalúan basándose en confidencias numéricas (0-1) donde valores por encima de 0.5 indican que el correo es inaceptable, marketing o spam, y son eliminados automáticamente a través de la API de Gmail. Se envía notificación por Telegram cuando un correo se elimina, no lo hace en caso contrario o si ocurren errores.
  - **Complejidad:** Alta (17 nodos)

- **[1418-telegram-bot-integration.json](workflows/1418-telegram-bot-integration.json)**
  - **Descripción:** Integra un bot de Telegram con servicios externos.
  - **Complejidad:** Alta (17 nodos)

- **[2714-ai-agent-slack-transfer.json](workflows/2714-ai-agent-slack-transfer.json)**
  - **Descripción:** Flujo que implementa un agente de chat con inteligencia artificial capaz de transferir conversaciones a Slack si el usuario no proporciona una dirección de correo electrónico.
  - **Complejidad:** Alta (17 nodos)

- **[2769-bank_statement_reconciliation.json](workflows/2769-bank_statement_reconciliation.json)**
  - **Descripción:** Este flujo monitorea archivos CSV de estado bancario, los procesa con un modelo de inteligencia artificial para detectar discrepancias en pagos de alquileres y notificaciones específicas.
  - **Complejidad:** Alta (17 nodos)

- **[2806-telegram-bot-memory.json](workflows/2806-telegram-bot-memory.json)**
  - **Descripción:** Este flujo automático gestiona conversaciones en Telegram usando OpenAI y Supabase para mantener el contexto. Crea una nueva hilera de discusión en OpenAI si es la primera vez que un usuario habla con el bot, guarda la información del usuario en Supabase y envía respuestas personalizadas.
  - **Complejidad:** Alta (17 nodos)

- **[2869-automail_manager.json](workflows/2869-automail_manager.json)**
  - **Descripción:** Este flujo automatiza la gestión de correo electrónico utilizando OpenRouter y Telegram. Recupera mensajes no leídos de Gmail, los categoriza con ayuda de Chat Model, y envía notificaciones por Telegram.
  - **Complejidad:** Alta (17 nodos)

- **[2897-team-weekly-report.json](workflows/2897-team-weekly-report.json)**
  - **Descripción:** Este flujo automático recopila los mensajes de un canal de Microsoft Teams, Agrupa y resume la actividad de cada miembro del equipo utilizando OpenAI para generar informes personalizados, y publica un resumen semanal en el canal.
  - **Complejidad:** Alta (17 nodos)

- **[3103-email-autoresponder-approval.json](workflows/3103-email-autoresponder-approval.json)**
  - **Descripción:** Este flujo automático procesa emails entrantes, los resume y genera respuestas con RAG usando DeepSeek R1 y Qdrant. Permite una aprobación por correo electrónico antes de enviar la respuesta final.
  - **Complejidad:** Alta (17 nodos)

- **[3215-linear_productboard_sync.json](workflows/3215-linear_productboard_sync.json)**
  - **Descripción:** Este flujo sincroniza el estado y fecha final de proyectos en Linear con una función en Productboard. Actualiza automáticamente los estados y las fechas en Productboard basado en los datos de Linear y notifica cambios mediante Slack.
  - **Complejidad:** Alta (17 nodos)

- **[0152-gdpr-data-deletion.json](workflows/0152-gdpr-data-deletion.json)**
  - **Descripción:** Este flujo automatizado maneja comandos de barra en Slack para solicitar la eliminación de datos según GDPR. Valida que el token y el correo electrónico estén presentes, procesa las eliminaciones de diferentes servicios (Paddle, Customer.io y Zendesk) y luego registra estos eventos en una base de Airtable.
  - **Complejidad:** Alta (16 nodos)

- **[0771-google-trends-resumen.json](workflows/0771-google-trends-resumen.json)**
  - **Descripción:** Este flujo automatizado extrae datos de Google Trends utilizando Bright Data Web Unlocker y los procesa con cadenas LLM (Google Gemini Flash) para generar un resumen estructurado que luego se escribe en un archivo JSON o envía por email.
  - **Complejidad:** Alta (16 nodos)

- **[1424-a-very-simple-_human-in-email-ai.json](workflows/1424-a-very-simple-_human-in-email-ai.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, generación de contenido utilizando OpenAI/GPT, Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (16 nodos)

- **[1467-extract-text-from-pdf-and-ai.json](workflows/1467-extract-text-from-pdf-and-ai.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos utilizando Email/Gmail, PDF con inteligencia artificial y APIs.
  - **Complejidad:** Alta (16 nodos)

- **[1500-telegram-ai-chatbot.json](workflows/1500-telegram-ai-chatbot.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Telegram, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (16 nodos)

- **[2577-ClockifySlackCopilotWorkflow.json](workflows/2577-ClockifySlackCopilotWorkflow.json)**
  - **Descripción:** Este flujo automatiza la gestión conversacional de entradas de tiempo en Clockify a través de Slack, integrando herramientas para crear, actualizar y eliminar registros sin superposición.
  - **Complejidad:** Alta (16 nodos)

- **[2628-error-limitacion.json](workflows/2628-error-limitacion.json)**
  - **Descripción:** Este flujo automático permite registrar errores en una base de datos PostgreSQL pero limita las notificaciones a un máximo de una por cada cinco minutos.
  - **Complejidad:** Alta (16 nodos)

- **[2715-discord-to-sheets-sync.json](workflows/2715-discord-to-sheets-sync.json)**
  - **Descripción:** Este flujo automatiza la sincronización de miembros activos de Discord con Google Sheets. Extrae información de Discord, filtra por roles y mantiene un registro en una hoja de cálculo.
  - **Complejidad:** Alta (16 nodos)

- **[2758-evento-banner-generator.json](workflows/2758-evento-banner-generator.json)**
  - **Descripción:** Este flujo automatiza la creación de banners promocionales para eventos usando n8n. Permite capturar información a través de un formulario, generar una imagen con IA y crear banners personalizados en BannerBear para compartir en Discord.
  - **Complejidad:** Alta (16 nodos)

- **[3055-discord-server-flow.json](workflows/3055-discord-server-flow.json)**
  - **Descripción:** Este flujo configura una integración con Discord que permite realizar diversas acciones como enviar mensajes, obtener información de servidores y usuarios, manejar roles y esperar respuestas.
  - **Complejidad:** Alta (16 nodos)

- **[3068-confluence-chatbot-ai.json](workflows/3068-confluence-chatbot-ai.json)**
  - **Descripción:** Este flujo utiliza la API de Confluence para buscar y recuperar contenido específico de páginas, convierte HTML a Markdown, y utiliza el agente AI de GPT-4 para responder preguntas basadas en el contexto proporcionado. Además, envía las respuestas mediante Telegram.
  - **Complejidad:** Alta (16 nodos)

- **[3087-email-automatizado-con-HITL.json](workflows/3087-email-automatizado-con-HITL.json)**
  - **Descripción:** Este flujo automático procesa emails entrantes mediante un sistema de correo IMAP, los resume con IA y genera respuestas automáticas. El usuario humano valida la respuesta antes de enviarla.
  - **Complejidad:** Alta (16 nodos)

- **[3113-training_feedback_automat.json](workflows/3113-training_feedback_automat.json)**
  - **Descripción:** Este flujo automático gestiona retroalimentación de capacitación enviando notificaciones y creando tareas según la calificación dada. Detecta retroalimentación negativa para acción inmediata, crea tareas en UserTask y envía correo electrónico a los encargados.
  - **Complejidad:** Alta (16 nodos)

- **[3281-telegram-voice-to-social.json](workflows/3281-telegram-voice-to-social.json)**
  - **Descripción:** Este flujo recibe mensajes de Telegram, los analiza para ver si son voz o texto, y en caso de ser voz los transcribe. Luego utiliza OpenAI y SerpAPI para generar contenido optimizado para redes sociales con un prompt detallado para crear imágenes.
  - **Complejidad:** Alta (16 nodos)

- **[3295-email-processing-flow.json](workflows/3295-email-processing-flow.json)**
  - **Descripción:** Este flujo automático procesa correos electrónicos de Gmail usando un clasificador de texto para asignar mensajes a categorías específicas como Guest Post, Youtube o Cursos. Luego, envía respuestas predefinidas utilizando plantillas HTML y marca los emails como leídos además de agregar etiquetas y contactos en Brevo.
  - **Complejidad:** Alta (16 nodos)

- **[3328-telegram-ai-bot.json](workflows/3328-telegram-ai-bot.json)**
  - **Descripción:** Este flujo Telegram AI Chatbot gestiona comandos específicos y utiliza OpenAI para responder mensajes en diferentes modos como conversación, bienvenida y generación de imágenes.
  - **Complejidad:** Alta (16 nodos)

- **[3339-amazon_price_tracker.json](workflows/3339-amazon_price_tracker.json)**
  - **Descripción:** Este flujo monitorea los precios de productos en Amazon utilizando la API de ScrapeOps, registra cambios y envía alertas por correo electrónico cuando hay alteraciones significativas.
  - **Complejidad:** Alta (16 nodos)

- **[0829-news-monitor-trello.json](workflows/0829-news-monitor-trello.json)**
  - **Descripción:** Este flujo automático monitoriza múltiples fuentes de RSS (Artificial Intelligence Blog, Testing Catalog y MarkTechPost), filtra artículos basados en la fecha, transforma los resultados a formato Markdown y publica comentarios en Trello mientras envía notificaciones por correo.
  - **Complejidad:** Media (15 nodos)

- **[0842-telegram-ai-assistant.json](workflows/0842-telegram-ai-assistant.json)**
  - **Descripción:** Este flujo automático permite a Angie mantener un contexto conversacional en tiempo real mientras interactúa con los usuarios mediante Telegram (tanto mensajes de texto como archivos de audio) y accede a sus correos electrónicos, agenda y datos basados en Baserow.
  - **Complejidad:** Media (15 nodos)

- **[1224-telegram-recipe-daily.json](workflows/1224-telegram-recipe-daily.json)**
  - **Descripción:** Este flujo automático envía un receta vegana aleatoria por Telegram cada día mediante el desencadenante cron, y también añade a los chats nuevos usuarios para gestionarlos adecuadamente.
  - **Complejidad:** Media (15 nodos)

- **[1243-assistant-tool.json](workflows/1243-assistant-tool.json)**
  - **Descripción:** Este flujo automatizado funciona como asistente personal, utilizando herramientas específicas para manejar tareas de email, calendario, contactos y búsqueda web según la consulta del usuario.
  - **Complejidad:** Media (15 nodos)

- **[1434-ai-powered-children_s-arabic-storytelling-telegram.json](workflows/1434-ai-powered-children_s-arabic-storytelling-telegram.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, generación de contenido utilizando OpenAI/GPT, Telegram con inteligencia artificial y APIs de forma programada.
  - **Complejidad:** Media (15 nodos)

- **[1438-angie-personal-ai-assistant-with-telegram.json](workflows/1438-angie-personal-ai-assistant-with-telegram.json)**
  - **Descripción:** Este flujo permite chatbot, transcripción, resumen utilizando OpenAI/GPT, Telegram, Email/Gmail con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (15 nodos)

- **[1490-reddit-ai-digest.json](workflows/1490-reddit-ai-digest.json)**
  - **Descripción:** Este flujo permite automatización, resumen, extracción de datos, monitoreo utilizando OpenAI/GPT, Slack, Twitter/X con inteligencia artificial y APIs.
  - **Complejidad:** Media (15 nodos)

- **[2697-shopify-inventory-alert.json](workflows/2697-shopify-inventory-alert.json)**
  - **Descripción:** Flujo para monitorear y notificar cuando los productos de Shopify tienen bajo stock o agotan existencias enviando mensajes a Discord con detalles del producto.
  - **Complejidad:** Media (15 nodos)

- **[2701-songkick-event-email.json](workflows/2701-songkick-event-email.json)**
  - **Descripción:** Este flujo automático extrae y procesa información de eventos musicales de Songkick, PagerDuty-style, enviando un correo electrónico con los detalles formateados al usuario cada mes.
  - **Complejidad:** Media (15 nodos)

- **[2745-kids-story-generator.json](workflows/2745-kids-story-generator.json)**
  - **Descripción:** Flujo automatizado para crear y compartir historias infantiles en árabe con OpenAI y Telegram.
  - **Complejidad:** Media (15 nodos)

- **[2762-sitios-monitor.json](workflows/2762-sitios-monitor.json)**
  - **Descripción:** Este flujo automatiza la monitorización de sitios web mediante un temporizador que verifica el estado de cada sitio y envía alertas por correo electrónico o Slack si hay cambios en el estado.
  - **Complejidad:** Media (15 nodos)

- **[2808-telegram-ai-agent.json](workflows/2808-telegram-ai-agent.json)**
  - **Descripción:** Este flujo utiliza Telegram para recibir mensajes, procesa voz o texto, transcribe voz a texto, y usa OpenAI como agente de inteligencia artificial para responder basándose en correo electrónico, calendario y contactos.
  - **Complejidad:** Media (15 nodos)

- **[2962-telegram-links-sync.json](workflows/2962-telegram-links-sync.json)**
  - **Descripción:** Este flujo automatiza la sincronización de enlaces entre un canal de Telegram y dos servicios: Readeck y Hoarder. Primero, utiliza una API de Telegram para recuperar los mensajes del canal especificado. Luego, filtra y procesa los enlaces no guardados en cada servicio, realizando peticiones POST para almacenar aquellos que aún no han sido agregados.
  - **Complejidad:** Media (15 nodos)

- **[2992-telegram-chatbot-multi-format.json](workflows/2992-telegram-chatbot-multi-format.json)**
  - **Descripción:** Este flujo automático gestiona mensajes y voz en Telegram, transcribe audio a texto con OpenAI, procesa inputs y envía respuestas formatadas.
  - **Complejidad:** Media (15 nodos)

- **[3003-extract-summarize-indeed.json](workflows/3003-extract-summarize-indeed.json)**
  - **Descripción:** Este flujo extrae y resume información de empresas de Indeed utilizando Bright Data y Google Gemini. Incluye web scraping, análisis con LLM y notificaciones por webhook.
  - **Complejidad:** Media (15 nodos)

- **[3056-email-classifier.json](workflows/3056-email-classifier.json)**
  - **Descripción:** Este flujo automático clasifica y organiza emails en Gmail utilizando IA para etiquetarlos como Prioritarios, Relacionados con el trabajo o Promociones.
  - **Complejidad:** Media (15 nodos)

- **[3088-whatsapp_medical_appointments_bot.json](workflows/3088-whatsapp_medical_appointments_bot.json)**
  - **Descripción:** Este flujo automático envía notificaciones de citas médicas por WhatsApp a usuarios que han dado su consentimiento,registra mensajes en una hoja de cálculo de Google Sheets y permite responder a los usuarios a través de un sistema escalable.
  - **Complejidad:** Media (15 nodos)

- **[3308-historias-infantiles-arabic.json](workflows/3308-historias-infantiles-arabic.json)**
  - **Descripción:** Flujo que automatiza la creación y envío de historias en árabe para niños a través de Telegram, utilizando OpenAI para generar contenido, traducir, crear imágenes y audio.
  - **Complejidad:** Media (15 nodos)

- **[3326-telegram-ai-bot.json](workflows/3326-telegram-ai-bot.json)**
  - **Descripción:** Este flujo procesa mensajes de voz y texto en Telegram, transcribe audio a texto y utiliza OpenAI para responder inteligentemente.
  - **Complejidad:** Media (15 nodos)

- **[0286-slack-gilfoyle-chatbot.json](workflows/0286-slack-gilfoyle-chatbot.json)**
  - **Descripción:** Este flujo n8n procesa mensajes en Slack a través de una Webhook, utilizando al agente Gilfoyle para generar respuestas sarcásticas e irritable sobre temas definidos. El sistema verifica si el mensaje es humano y no generado por bot, usa herramientas como búsqueda web (SerpAPI) e información de Wikipedia según sea necesario y mantiene en memoria la conversación usando el ID del canal como clave.
  - **Complejidad:** Media (14 nodos)

- **[0497-incident-integracion.json](workflows/0497-incident-integracion.json)**
  - **Descripción:** Este flujo automatizado integra el monitoreo de incidentes con seguimiento en Jira, notificando al equipo a través de canales Mattermost.
  - **Complejidad:** Media (14 nodos)

- **[0820-historias-para-ninos.json](workflows/0820-historias-para-ninos.json)**
  - **Descripción:** Este flujo automático crea historias en inglés para niños, las ilustra visualmente y las envía como texto e imágenes de audio vía Telegram.
  - **Complejidad:** Media (14 nodos)

- **[0843-spy-intelligence-tool.json](workflows/0843-spy-intelligence-tool.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE realizar una inteligencia espionaje automatizada. Escanea periódicamente (cada día) información de una URL extraída por IA y compara el contenido antiguo con el actual para enviar alertas por email si hay diferencias significativas.
  - **Complejidad:** Media (14 nodos)

- **[0915-google_analytics_report_workflow.json](workflows/0915-google_analytics_report_workflow.json)**
  - **Descripción:** Este flujo analiza datos de Google Analytics para las últimas 7 días y los compara con el mismo período del año anterior, luego utiliza la IA para formatearlos en un informe HTML detallado que se envía por correo electrónico. Además, transforma estos datos en texto plano para Telegram y lo comparte opcionalmente.
  - **Complejidad:** Media (14 nodos)

- **[0994-spotify_telegram_integration.json](workflows/0994-spotify_telegram_integration.json)**
  - **Descripción:** Este flujo automático permite a un usuario enviar mensajes a Telegram sobre canciones o artistas, que son analizados por OpenAI para obtener información detallada y luego se busca y controla esa música en Spotify.
  - **Complejidad:** Media (14 nodos)

- **[1185-mcp-brave-telegram-search.json](workflows/1185-mcp-brave-telegram-search.json)**
  - **Descripción:** Este flujo MCP utiliza la API de Brave y Telegram para realizar búsquedas web automáticamente cuando el usuario envía un comando /brave seguido de una consulta.
  - **Complejidad:** Media (14 nodos)

- **[1505-utm-link-creator-qr-code-google.json](workflows/1505-utm-link-creator-qr-code-google.json)**
  - **Descripción:** Este flujo permite chatbot, resumen, generación de contenido, reportes utilizando OpenAI/GPT, Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs de forma programada.
  - **Complejidad:** Media (14 nodos)

- **[2681-notion-gmail-sinc.json](workflows/2681-notion-gmail-sinc.json)**
  - **Descripción:** Este flujo automatiza la sincronización de correos electrónicos etiquetados a una base de datos en Notion. Busca emails específicos cada minuto, crea páginas nuevas si no existen y elimina los etiquetos una vez procesados.
  - **Complejidad:** Media (14 nodos)

- **[2742-email_to_podcast.json](workflows/2742-email_to_podcast.json)**
  - **Descripción:** Este flujo automatiza la conversión de correos electrónicos en podcasts. Utiliza Gmail para detectar mensajes con la etiqueta 'CATEGORY_PROMOTIONS', los procesa, genera un resumen y convierte el texto en audio que se envía a Telegram.
  - **Complejidad:** Media (14 nodos)

- **[2744-ai-storyteller-telegram.json](workflows/2744-ai-storyteller-telegram.json)**
  - **Descripción:** Este flujo automatiza la creación y envío de historias infantiles al canal Telegram, generando textos, audios e imágenes con inteligencia artificial.
  - **Complejidad:** Media (14 nodos)

- **[2911-manejador_comentarios_ig.json](workflows/2911-manejador_comentarios_ig.json)**
  - **Descripción:** Este flujo automático gestiona los comentarios en Instagram de manera autónoma. Recibe notificaciones de webhooks, valida el origen, extrae datos y utiliza un agente de IA para responder adecuadamente.
  - **Complejidad:** Media (14 nodos)

- **[3129-discord_cleaner.json](workflows/3129-discord_cleaner.json)**
  - **Descripción:** Este flujo automático elimina mensajes de Discord que sean antiguos de más de 7 días, ejecutándose diariamente a las 21:00 horas. Utiliza nodos para descargar canales, filtrar mensajes por fecha y eliminar los viejos, con pausas para respetar los límites de la API.
  - **Complejidad:** Media (14 nodos)

- **[3182-spotify_telegram_bot.json](workflows/3182-spotify_telegram_bot.json)**
  - **Descripción:** Este flujo utiliza Telegram para recibir mensajes musicales, consulta a OpenAI para obtener información de canciones y reproduce música en Spotify.
  - **Complejidad:** Media (14 nodos)

- **[3243-service-now-slack-notifications.json](workflows/3243-service-now-slack-notifications.json)**
  - **Descripción:** Este flujo automatiza la notificación de incidentes recientes de ServiceNow a un canal de Slack cada 5 minutos. Utiliza un timestamp para buscar incidentes creados en los últimos 5 minutos y, si hay nuevos, los ordena por número y envía detalles formateados al Slack. Si ocurre un error con ServiceNow, notifica el problema.
  - **Complejidad:** Media (14 nodos)

- **[0060-notion-sigalerts.json](workflows/0060-notion-sigalerts.json)**
  - **Descripción:** Este flujo automático utiliza el desencadenador de Notion para recibir eventos relacionados con cambios en la base de datos, procesa estos eventos mediante funciones y luego actualiza registros en Notion según los estados detectados (Abierto, Resuelto, Anotado o No hay alguien al tanto). Además, integra con SIGNL4 para enviar alertas.
  - **Complejidad:** Media (13 nodos)

- **[0439-hn-lookback-bot.json](workflows/0439-hn-lookback-bot.json)**
  - **Descripción:** Este flujo automático permite revisar las principales historias de Hacker News del día actual y los días anteriores en múltiples años, analizarlas con un modelo LLM para categorizarlas en temas usando Google Gemini y enviar el resumen formateado en Markdown a través de Telegram.
  - **Complejidad:** Media (13 nodos)

- **[0778-discord-ai-agent.json](workflows/0778-discord-ai-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Discord mantener conversaciones contextualizadas entre diferentes canales utilizando memoria avanzada y herramientas integradas.
  - **Complejidad:** Media (13 nodos)

- **[0888-webflow-discord-form.json](workflows/0888-webflow-discord-form.json)**
  - **Descripción:** Este flujo automático crea un canal de Discord para cada formulario web de Webflow y envía las respuestas formuladas a ese canal.
  - **Complejidad:** Media (13 nodos)

- **[1204-telegram-ai-multitranslator.json](workflows/1204-telegram-ai-multitranslator.json)**
  - **Descripción:** Este flujo permite a un bot de Telegram detectar y traducir mensajes de voz en 55 idiomas, conversando con usuarios en el idioma nativo.
  - **Complejidad:** Media (13 nodos)

- **[1247-auto-subir-multimedia.json](workflows/1247-auto-subir-multimedia.json)**
  - **Descripción:** Este flujo automatizado permite descargar videos de Google Drive y luego extraer su audio para generar descripciones que se utilizan en la subida simultanea a Instagram y TikTok. Además, cuenta con un mecanismo para notificar errores por Telegram.
  - **Complejidad:** Media (13 nodos)

- **[1397-telegram-tareas.json](workflows/1397-telegram-tareas.json)**
  - **Descripción:** Gestiona tareas mediante un bot de Telegram.
  - **Complejidad:** Media (13 nodos)

- **[1447-cv-resume-pdf-parsing-with-multimodal-vision-ai.json](workflows/1447-cv-resume-pdf-parsing-with-multimodal-vision-ai.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, extracción de datos utilizando Email/Gmail, PDF con inteligencia artificial y APIs.
  - **Complejidad:** Media (13 nodos)

- **[1466-extract-personal-data-with-self.json](workflows/1466-extract-personal-data-with-self.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos utilizando Email/Gmail, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (13 nodos)

- **[2571-OpenSea-Insights-Telegram.json](workflows/2571-OpenSea-Insights-Telegram.json)**
  - **Descripción:** Este flujo n8n automatizado analiza el mercado de NFTs en tiempo real usando OpenAI GPT y conecta con agentes especializados para responder consultas via Telegram.
  - **Complejidad:** Media (13 nodos)

- **[2695-g2_reviews_monitor.json](workflows/2695-g2_reviews_monitor.json)**
  - **Descripción:** Este flujo automático extrae y monitorea reseñas recientes de G2 para competidores como Zendesk, Intercom y Dixa utilizando ScrapingBee. Notifica nuevas reseñas en Slack y las registra en Google Sheets.
  - **Complejidad:** Media (13 nodos)

- **[2718-intercom-enrich-user-flow.json](workflows/2718-intercom-enrich-user-flow.json)**
  - **Descripción:** Este flujo automatiza la enriquecimiento de datos de usuarios recién creados en Intercom mediante API. Recibe notificaciones de Intercom, verifica el evento 'contact.user.created', extrae información y consulta ExactBuyer para actualizar detalles como correo electrónico, teléfono, ubicación y perfiles sociales.
  - **Complejidad:** Media (13 nodos)

- **[2901-error_alert_summarizer.json](workflows/2901-error_alert_summarizer.json)**
  - **Descripción:** Este flujo automático detecta errores en ejecuciones n8n y genera alertas de correo electrónico con diagnóstico y resolución.
  - **Complejidad:** Media (13 nodos)

- **[2984-hn-throwback-analyzer.json](workflows/2984-hn-throwback-analyzer.json)**
  - **Descripción:** Este flujo recopila y analiza los titulares de la portada de Hacker News para una fecha específica en años pasados, utilizando un modelo LLM para categorizarlos temáticamente y enviar el resultado a Telegram.
  - **Complejidad:** Media (13 nodos)

- **[3053-Notify_user_quarantined_email.json](workflows/3053-Notify_user_quarantined_email.json)**
  - **Descripción:** Este flujo notifica a un usuario de Slack cuando un correo electrónico es quarantinizado y crea una tarjeta en Jira si el correo fue abierto antes de la cuarentena.
  - **Complejidad:** Media (13 nodos)

- **[3116-webflow-slack-submissions.json](workflows/3116-webflow-slack-submissions.json)**
  - **Descripción:** Este flujo automático envía las submissions de formularios de Webflow a Slack. Primero, verifica si existe un canal correspondiente al nombre del formulario; si no existe, crea uno nuevo y notifica en el canal #general. Luego, compone y envía el mensaje con los datos del formulario al canal apropiado.
  - **Complejidad:** Media (13 nodos)

- **[3187-traductor_telegram_audio.json](workflows/3187-traductor_telegram_audio.json)**
  - **Descripción:** Este flujo traduce mensajes de voz en Telegram utilizando IA. Detecta automáticamente el idioma y los traduce al idioma configurado.
  - **Complejidad:** Media (13 nodos)

- **[0102-google-calendar-meetings-slack.json](workflows/0102-google-calendar-meetings-slack.json)**
  - **Descripción:** Este flujo automático consulta eventos de la agenda Gmail y los compara con hoy para enviar por Slack una lista de reuniones programadas.
  - **Complejidad:** Media (12 nodos)

- **[0291-telegram-n8n-control.json](workflows/0291-telegram-n8n-control.json)**
  - **Descripción:** Este flujo permite activar o desactivar workflows de n8n mediante comandos de Telegram. Los mensajes deben comenzar con '/start' o '/stop' seguidos del nombre del workflow para realizar la acción correspondiente.
  - **Complejidad:** Media (12 nodos)

- **[0337-empresa-noticias-automatizacion.json](workflows/0337-empresa-noticias-automatizacion.json)**
  - **Descripción:** Este flujo automático busca mantener informados sobre las noticias más recientes de empresas relacionadas con cada reunión programada en el calendario diario, enviando un resumen por email a la hora convenida.
  - **Complejidad:** Media (12 nodos)

- **[0344-form-contacto-telegram.json](workflows/0344-form-contacto-telegram.json)**
  - **Descripción:** Este flujo automático recopila correos electrónicos mediante un formulario de contacto, verifica su validez usando Hunter API y, si es válido, calcula el score de ajuste del cliente a través de MadKudu. Los resultados se envían a Telegram para seguimiento rápido.
  - **Complejidad:** Media (12 nodos)

- **[0371-telegram-chatbot-ai.json](workflows/0371-telegram-chatbot-ai.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Telegram generar respuestas inteligentes basadas en mensajes recibidos y enviar esas respuestas junto con imágenes generadas por IA.
  - **Complejidad:** Media (12 nodos)

- **[0437-youtube-transcript-summary.json](workflows/0437-youtube-transcript-summary.json)**
  - **Descripción:** Este flujo permite extraer la ID de un video de YouTube desde su URL mediante expresión regular, obtener sus datos principales como título y descripción, concatenar las transcripciones si están disponibles, y enviar un mensaje formateado con el resumen a través de Telegram.
  - **Complejidad:** Media (12 nodos)

- **[1030-telegram-ai-image-generation.json](workflows/1030-telegram-ai-image-generation.json)**
  - **Descripción:** Este flujo automático convierte el texto de mensajes de Telegram en imágenes generadas por OpenAI y las envía de vuelta al usuario mediante la aplicación de Telegram.
  - **Complejidad:** Media (12 nodos)

- **[1194-slack-webhook-verify.json](workflows/1194-slack-webhook-verify.json)**
  - **Descripción:** Este flujo verifica la firma de una solicitud web de Slack utilizando HMAC SHA256 para asegurar que el mensaje proviene realmente del webhook oficial de Slack y no es un falso.
  - **Complejidad:** Media (12 nodos)

- **[1451-classify-new-bugs-in-linear-gpt.json](workflows/1451-classify-new-bugs-in-linear-gpt.json)**
  - **Descripción:** Este flujo automatiza procesos utilizando OpenAI/GPT, Slack, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (12 nodos)

- **[1499-summarize-the-new-documents-from-google-drive-google.json](workflows/1499-summarize-the-new-documents-from-google-drive-google.json)**
  - **Descripción:** Este flujo permite automatización, resumen, generación de contenido utilizando OpenAI/GPT, Email/Gmail, Google Sheets con inteligencia artificial y APIs.
  - **Complejidad:** Media (12 nodos)

- **[2629-flujo_verificacion_lead.json](workflows/2629-flujo_verificacion_lead.json)**
  - **Descripción:** Este flujo automatizado verifica la validez de correos electrónicos en formularios y, si son válidos, los envía a Gmail, actualiza una hoja de cálculo en Google Sheets y notifica por Discord.
  - **Complejidad:** Media (12 nodos)

- **[2712-automated-email-flow.json](workflows/2712-automated-email-flow.json)**
  - **Descripción:** Este flujo automatiza la gestión de mensajes pendientes para enviar correos electrónicos. Recupera datos desde una hoja de cálculo de Google Sheets, filtra las entradas según el estado 'Esperando para ser enviado' y fecha actual, configura los datos necesarios, envía emails mediante Gmail y actualiza el estatus en la hoja de cálculo.
  - **Complejidad:** Media (12 nodos)

- **[2719-discourse-slack-notifications.json](workflows/2719-discourse-slack-notifications.json)**
  - **Descripción:** Este flujo automatiza la notificación en Slack de nuevos usuarios altamente valorados en Discourse, filtrando emails personales y verificando datos empresariales mediante Clearbit.
  - **Complejidad:** Media (12 nodos)

- **[2836-sms-course-assistant.json](workflows/2836-sms-course-assistant.json)**
  - **Descripción:** Este flujo automatiza una asistente de SMS para Northvale Institute of Technology que utiliza OpenAI y Airtable para responder preguntas sobre cursos. Recibe mensajes vía Twilio, consulta la base de datos de cursos y envía respuestas mediante SMS.
  - **Complejidad:** Media (12 nodos)

- **[3062-coinmarketcap-analyst.json](workflows/3062-coinmarketcap-analyst.json)**
  - **Descripción:** Este flujo automático utiliza un agente de inteligencia artificial para analizar y enviar información en tiempo real sobre criptomonedas a través de Telegram, usando tres sub-agentes especializados: Crypto, Exchange & Community y DEXScan. El sistema procesa consultas de usuarios, gestiona memoria de sesión y utiliza API de CoinMarketCap para proporcionar insights detallados.
  - **Complejidad:** Media (12 nodos)

- **[3181-telegram-ai-bot.json](workflows/3181-telegram-ai-bot.json)**
  - **Descripción:** Este flujo automatiza un chatbot de Telegram que utiliza OpenAI y LangChain para procesar mensajes, mantener memoria contextual y generar imágenes con Dall-E 3.
  - **Complejidad:** Media (12 nodos)

- **[3218-newsletter-survey.json](workflows/3218-newsletter-survey.json)**
  - **Descripción:** Este flujo recoge información del usuario a través de un formulario multi-página: correo electrónico inicialmente y posteriormente datos adicionales como nombre, país, nivel laboral, funciones laborales, experiencia en sin-código y aficiones al producto. Los datos se guardan en Google Sheets y se envía una notificación a Slack.
  - **Complejidad:** Media (12 nodos)

- **[0145-readwise_telegram_sync.json](workflows/0145-readwise_telegram_sync.json)**
  - **Descripción:** Este flujo automático sincroniza libros y artículos de Readwise con Telegram, enviando resúmenes y detalles.
  - **Complejidad:** Media (11 nodos)

- **[0170-rss-security-monitor.json](workflows/0170-rss-security-monitor.json)**
  - **Descripción:** Este flujo automático monitoriza múltiples fuentes RSS en busca de contenido nuevo, utilizando un mecanismo para evitar envíos duplicados. Cuando se detecta nueva información, envía notificaciones a distintas cuentas de Telegram según su categoría (seguridad, IT o Microsoft 365).
  - **Complejidad:** Media (11 nodos)

- **[1071-slack-chatbot-slash.json](workflows/1071-slack-chatbot-slash.json)**
  - **Descripción:** Este flujo automático configura un chatbot de Slack usando comandos slash para interactuar con usuarios. Responde a diferentes comandos como /ask y /another, utilizando modelos de OpenAI.
  - **Complejidad:** Media (11 nodos)

- **[1129-telegram-facebook-interest.json](workflows/1129-telegram-facebook-interest.json)**
  - **Descripción:** Este flujo automático procesa mensajes en Telegram que comienzan con '#interest' para buscar intereses en la API de Facebook Graph y luego genera un archivo CSV con los resultados.
  - **Complejidad:** Media (11 nodos)

- **[1228-slack-ai-chatbot.json](workflows/1228-slack-ai-chatbot.json)**
  - **Descripción:** Este flujo configura un chatbot en Slack usando n8n, donde diferentes comandos de barra (/ask y /another) activan respuestas generadas por modelos de OpenAI como gpt-4o-mini. Luego se envía el mensaje a la canal especificado.
  - **Complejidad:** Media (11 nodos)

- **[1240-splunk-jira-ticket-automation.json](workflows/1240-splunk-jira-ticket-automation.json)**
  - **Descripción:** Este flujo automático procesa alertas de Splunk para crear tickets únicos en Jira cuando no existe un ticket correspondiente. Si ya existe, añade comentarios con los detalles del alertado.
  - **Complejidad:** Media (11 nodos)

- **[1448-cv-screening-with-openai.json](workflows/1448-cv-screening-with-openai.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, extracción de datos, generación de contenido, reclutamiento utilizando OpenAI/GPT, Slack, Airtable con inteligencia artificial y APIs.
  - **Complejidad:** Media (11 nodos)

- **[1486-prepare-csv-files-with-gpt-gpt.json](workflows/1486-prepare-csv-files-with-gpt-gpt.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Email/Gmail con inteligencia artificial y APIs.
  - **Complejidad:** Media (11 nodos)

- **[1495-slack-slash-commands-ai-chat-bot.json](workflows/1495-slack-slash-commands-ai-chat-bot.json)**
  - **Descripción:** Este flujo permite chatbot, automatización utilizando OpenAI/GPT, Slack, Webhook con inteligencia artificial mediante webhooks.
  - **Complejidad:** Media (11 nodos)

- **[2680-reporte-notion-slack.json](workflows/2680-reporte-notion-slack.json)**
  - **Descripción:** Este flujo automatiza la creación de reportes semanales resumiendo entradas de una base de datos de Notion que contienen ideas de producto. Cada domingo a las 8:00 AM,consulta los últimos 7 días y envía un mensaje al canal #nik-wf-testing en Slack con el conteo único de ideas UX.
  - **Complejidad:** Media (11 nodos)

- **[0040-screenshot-automation.json](workflows/0040-screenshot-automation.json)**
  - **Descripción:** Este flujo automatizado genera capturas de pantalla de la página web https://uproc.io en modo completo y normal, las sube a Dropbox con rutas específicas y envía un email con ambos archivos adjuntos.
  - **Complejidad:** Media (10 nodos)

- **[0271-linear-alert-slack.json](workflows/0271-linear-alert-slack.json)**
  - **Descripción:** Este flujo automático detecta eventos de incidencias urgentes en Linear y envía una alerta a un canal específico de Slack para notificar al equipo.
  - **Complejidad:** Media (10 nodos)

- **[0365-reporte-fallas-telegram.json](workflows/0365-reporte-fallas-telegram.json)**
  - **Descripción:** Este flujo revisa las ejecuciones falladas de una tarea en la última semana y envía un resumen por Telegram.
  - **Complejidad:** Media (10 nodos)

- **[0457-vps-resource-monitor.json](workflows/0457-vps-resource-monitor.json)**
  - **Descripción:** Este flujo verifica el uso de CPU, RAM y disco en una VPS cada 15 minutos mediante tres nodos SSH ejecutados en intervalo. Si algún recurso excede el umbral del 80%, envía un email con la información detallada.
  - **Complejidad:** Media (10 nodos)

- **[0486-telegram-chinese-tutor.json](workflows/0486-telegram-chinese-tutor.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Telegram practicar eficientemente el idioma chino mediante ejercicios de opción múltiple, utilizando memoria para mantener el contexto de la conversación.
  - **Complejidad:** Media (10 nodos)

- **[0523-orlen-factura-automatizada.json](workflows/0523-orlen-factura-automatizada.json)**
  - **Descripción:** Este flujo automático descarga y procesa facturas electrónicas diarias del correo Gmail de Orlen, las sube a una carpeta en Google Drive organizada por año y mes, marca como leídas y notifica mediante Slack el directorio donde se han cargado.
  - **Complejidad:** Media (10 nodos)

- **[0919-slack-ai-bot.json](workflows/0919-slack-ai-bot.json)**
  - **Descripción:** Este flujo automático procesa mensajes de Slack mediante un agente AI basado en Google Gemini, manteniendo conversaciones contextualesizadas con memoria por ventana.
  - **Complejidad:** Media (10 nodos)

- **[1135-linear-bug-report.json](workflows/1135-linear-bug-report.json)**
  - **Descripción:** Este flujo n8n procesa reportes de bugs recibidos por webhook en Slack y los convierte en tareas dentro de Linear, utilizando credenciales OAuth para autenticación.
  - **Complejidad:** Media (10 nodos)

- **[1205-dst-automation.json](workflows/1205-dst-automation.json)**
  - **Descripción:** Este flujo automático verifica cambios de horario de verano en diferentes zonas horarias y notifica por Slack y correo sobre los cambios próximos.
  - **Complejidad:** Media (10 nodos)

- **[1206-hacker-news-recomendaciones.json](workflows/1206-hacker-news-recomendaciones.json)**
  - **Descripción:** Este flujo analiza los comentarios de las publicaciones 'ask_hn' relacionadas con un tema específico en Hacker News para recomendar recursos. Utiliza Google Gemini (PaLM) como modelo de lenguaje, procesa el texto y lo categoriza por tipo y nivel de dificultad antes de enviarlo vía email.
  - **Complejidad:** Media (10 nodos)

- **[1455-creating-a-ai-slack-bot-with-google-gemini.json](workflows/1455-creating-a-ai-slack-bot-with-google-gemini.json)**
  - **Descripción:** Este flujo permite chatbot, automatización utilizando Slack, Webhook con inteligencia artificial mediante webhooks.
  - **Complejidad:** Media (10 nodos)

- **[1479-learn-anything-from-hn-get.json](workflows/1479-learn-anything-from-hn-get.json)**
  - **Descripción:** Este flujo permite chatbot, web scraping, análisis de sentimientos utilizando Email/Gmail, Webhook, YouTube con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (10 nodos)

- **[2810-incident-service-now.json](workflows/2810-incident-service-now.json)**
  - **Descripción:** Este flujo recibe una solicitud de Slack mediante un comando slash, extrae el ID de incidente y consulta ServiceNow para obtener detalles. Si el incidente existe, envía la información a Slack; si no, notifica al usuario.
  - **Complejidad:** Media (10 nodos)

- **[2990-optimizar-prompt.json](workflows/2990-optimizar-prompt.json)**
  - **Descripción:** Flujo que optimiza prompts usando un agente de AI para mejorar la claridad y especificación, enviando el resultado via Telegram.
  - **Complejidad:** Media (10 nodos)

- **[0082-shopify-reportes-semanal.json](workflows/0082-shopify-reportes-semanal.json)**
  - **Descripción:** Este flujo automático ejecuta cada semana a las 10:00 un informe que recoge todos los pedidos de Shopify, calcula el número total y su suma, añade estos datos a una hoja de Google Sheets y envía un mensaje en Slack con esta información.
  - **Complejidad:** Media (9 nodos)

- **[0091-steam-cloudflare-phishing-monitor.json](workflows/0091-steam-cloudflare-phishing-monitor.json)**
  - **Descripción:** Este flujo verifica dominios en Steam para detectar si están alojados en Cloudflare mediante comandos dig y envía alertas por correo cuando se identifican posibles sitios de phishing.
  - **Complejidad:** Media (9 nodos)

- **[0226-tradegate-investment-report.json](workflows/0226-tradegate-investment-report.json)**
  - **Descripción:** Este flujo automático recoge datos de inversiones almacenados en una tabla de Baserow y consulta cotizaciones actuales en la plataforma Tradegate para generar un informe detallado que se envía vía email utilizando SendGrid.
  - **Complejidad:** Media (9 nodos)

- **[0244-zendesk-slack-sync.json](workflows/0244-zendesk-slack-sync.json)**
  - **Descripción:** Este flujo automático sincroniza eventos de Zendesk con mensajes en Slack mediante webhooks.
  - **Complejidad:** Media (9 nodos)

- **[0274-discord-calendar-sync.json](workflows/0274-discord-calendar-sync.json)**
  - **Descripción:** Este flujo sincroniza automáticamente los eventos programados en Discord a Google Calendar. Detecta si un evento ya existe o es nuevo y procede a actualizarlo o crearlo respectivamente.
  - **Complejidad:** Media (9 nodos)

- **[0467-signl4-event-processing.json](workflows/0467-signl4-event-processing.json)**
  - **Descripción:** Este flujo automático procesa eventos pendientes del sistema SIG SIGNL4 cada hora, leyendo datos previos almacenados en un archivo binario y verificando si ya han sido resueltos para enviar las alertas correspondientes.
  - **Complejidad:** Media (9 nodos)

- **[0643-email-excuse-notification.json](workflows/0643-email-excuse-notification.json)**
  - **Descripción:** Este flujo automático analiza el remitente de un correo electrónico, lee datos de una hoja de cálculo para generar excusas aleatorias y envía ambos resultados (el correo original modificado y notificaciones en Slack) cuando el remitente es Louis Litt.
  - **Complejidad:** Media (9 nodos)

- **[0665-pipeline-etl-twitter-sentiment.json](workflows/0665-pipeline-etl-twitter-sentiment.json)**
  - **Descripción:** Este flujo automatizado busca tweets con el hashtag #OnThisDay, inserta los textos en una base de datos MongoDB y realiza un análisis de sentimiento utilizando Google Cloud Natural Language para almacenar las métricas score y magnitude en PostgreSQL. Si la puntuación es alta, envía un mensaje a Slack.
  - **Complejidad:** Media (9 nodos)

- **[0931-calendar-gemini-slack-summarization.json](workflows/0931-calendar-gemini-slack-summarization.json)**
  - **Descripción:** Este flujo automatizado extrae eventos del Google Calendar para generar resúmenes diarios utilizando el modelo Gemini AI y los comparte en un canal de Slack.
  - **Complejidad:** Media (9 nodos)

- **[0940-n8n_discord_ai_categorizer.json](workflows/0940-n8n_discord_ai_categorizer.json)**
  - **Descripción:** Este flujo automático categoriza solicitudes de usuario utilizando OpenAI GPT-4, generando una estructura JSON para enviarlas por Webhook a distintos departamentos en Discord según su clasificación.
  - **Complejidad:** Media (9 nodos)

- **[1036-daily-calendar-summarization-slack.json](workflows/1036-daily-calendar-summarization-slack.json)**
  - **Descripción:** Este flujo automático permite al usuario obtener todos los eventos de Google Calendar diarios y enviar un resumen generado por IA a su canal de Slack.
  - **Complejidad:** Media (9 nodos)

- **[1060-slack-gmeet-automator.json](workflows/1060-slack-gmeet-automator.json)**
  - **Descripción:** Este flujo automático permite generar enlaces de Google Meet a partir de solicitudes en Slack y enviarlos a los participantes del canal.
  - **Complejidad:** Media (9 nodos)

- **[1063-github-issues-monitor.json](workflows/1063-github-issues-monitor.json)**
  - **Descripción:** Este flujo automático consulta cada 10 minutos las issues abiertas de un repositorio GitHub específico (con parámetros como state y labels) y envía por Telegram solo aquellas con menos de 5 comentarios.
  - **Complejidad:** Media (9 nodos)

- **[1460-etl-pipeline-for-text-processing.json](workflows/1460-etl-pipeline-for-text-processing.json)**
  - **Descripción:** Este flujo permite análisis de sentimientos utilizando Slack, Twitter/X, MongoDB con inteligencia artificial y APIs.
  - **Complejidad:** Media (9 nodos)

- **[2590-cal-booking-distribution.json](workflows/2590-cal-booking-distribution.json)**
  - **Descripción:** Este flujo automático se dispara al crear una nueva cita en Cal.com y añade automáticamente a cada asistente en Google Sheets y Beehiiv, además de notificando por Telegram.
  - **Complejidad:** Media (9 nodos)

- **[2855-cripto-market-summary.json](workflows/2855-cripto-market-summary.json)**
  - **Descripción:** Este flujo automático obtiene los datos de precios de mercado de Binance para BTC, ETH y SOLUSDC a través de su API, analiza las fluctuaciones y envía un resumen detallado al canal de Telegram.
  - **Complejidad:** Media (9 nodos)

- **[3179-google-reminder-bot.json](workflows/3179-google-reminder-bot.json)**
  - **Descripción:** Este flujo automático envía una notificación amable y personalizada a través de Telegram recordando eventos de Google Calendar con hasta 1 hora de anticipación, evitando duplicados.
  - **Complejidad:** Media (9 nodos)

- **[0004-connectwise-ticket-alerts-to-teams.json](workflows/0004-connectwise-ticket-alerts-to-teams.json)**
  - **Descripción:** Este flujo automático se activa cada día entre las 8 y las 4 de la tarde para consultar tickets nuevos en Connectwise con ciertas condiciones, filtrar aquellos ya notificados usando Redis, combinarlos por empresa o sitio en mensajes HTML y enviar alertas a Microsoft Teams.
  - **Complejidad:** Media (8 nodos)

- **[0350-slack-idea-capture.json](workflows/0350-slack-idea-capture.json)**
  - **Descripción:** Este flujo automatizado permite a un usuario enviar una solicitud viajera (comando slash) '/idea' en Slack para crear automáticamente una página de base de datos en Notion y solicitar detalles adicionales.
  - **Complejidad:** Media (8 nodos)

- **[0351-slack-feature-ideas.json](workflows/0351-slack-feature-ideas.json)**
  - **Descripción:** Este flujo automatizado permite recibir ideas a través de comandos Slack y agregarlas en una hoja Google con un enlace para añadir detalles.
  - **Complejidad:** Media (8 nodos)

- **[0430-calvin-hobbes-discord-daily-comic.json](workflows/0430-calvin-hobbes-discord-daily-comic.json)**
  - **Descripción:** Este flujo automático publica las tiras del cómic Calvin y Hobbes en Discord, con traducciones al coreano junto a los diálogues originales.
  - **Complejidad:** Media (8 nodos)

- **[0433-github-release-monitor.json](workflows/0433-github-release-monitor.json)**
  - **Descripción:** Este flujo automático verifica cada día los lanzamientos más recientes de n8n en GitHub, convierte cualquier contenido en formato markdown a HTML y envía un email notificando si hay una nueva versión disponible.
  - **Complejidad:** Media (8 nodos)

- **[0440-jira_telegram_webhook.json](workflows/0440-jira_telegram_webhook.json)**
  - **Descripción:** Este flujo envía actualizaciones por Telegram según el tipo de evento en Jira (creación, cambio o asignación).
  - **Complejidad:** Media (8 nodos)

- **[0686-language-learning-words.json](workflows/0686-language-learning-words.json)**
  - **Descripción:** Este flujo automatizado extrae palabras de los títulos de las tres noticias principales de Hacker News, las traduce al alemán y guarda el resultado. Luego envía un SMS con una selección de cinco palabras alemanas junto con su correspondiente término en inglés.
  - **Complejidad:** Media (8 nodos)

- **[0786-telegram-groq-llava.json](workflows/0786-telegram-groq-llava.json)**
  - **Descripción:** Este flujo automático permite recibir una imagen a través de Telegram, convertirla en base64 y enviarla al modelo GROQ LLAVA V1.5-7B para obtener su descripción.
  - **Complejidad:** Media (8 nodos)

- **[0789-telegram-ai-chat.json](workflows/0789-telegram-ai-chat.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Telegram mantener conversaciones contextualesizadas, responder preguntas y generar imágenes cuando los usuarios lo solicitan.
  - **Complejidad:** Media (8 nodos)

- **[0831-monitor-usdt-balance.json](workflows/0831-monitor-usdt-balance.json)**
  - **Descripción:** Este flujo monitoriza automáticamente el balance ERC-20 USDT almacenado en una cartera, notificando cada 5 minutos a Telegram si ha cambiado o no.
  - **Complejidad:** Media (8 nodos)

- **[1042-youtube-ai-summary-discord.json](workflows/1042-youtube-ai-summary-discord.json)**
  - **Descripción:** Este flujo automático monitoriza nuevos videos de YouTube a través de una URL RSS, obtiene sus subtítulos en inglés, los procesa y resume con la API de ChatGPT para luego publicar el resumen junto con el enlace del video en un canal de Discord.
  - **Complejidad:** Media (8 nodos)

- **[1059-automatic-meetings-telegram.json](workflows/1059-automatic-meetings-telegram.json)**
  - **Descripción:** Este flujo automático envía una lista de tus reuniones programadas para el día actual en Telegram cada mañana a las seis, con fechas y horarios formateados en persiano.
  - **Complejidad:** Media (8 nodos)

- **[1064-okMME97B70fXzK5U_telegram_to_kindle.json](workflows/1064-okMME97B70fXzK5U_telegram_to_kindle.json)**
  - **Descripción:** Este flujo automático permite recibir archivos adjuntos por Telegram, verificar su existencia, renombrarlos para enviarlos como adjuntos de email a una dirección Kindle y notificar tanto al usuario en Telegram como mediante un correo si el proceso es exitoso o falla.
  - **Complejidad:** Media (8 nodos)

- **[1094-trello-sync.json](workflows/1094-trello-sync.json)**
  - **Descripción:** Este flujo automático obtiene los eventos del calendario de Google cada día a las 8:00 AM, verifica si son tareas recurrentes (como 'Check email', etc.) y las elimina si es necesario. Luego crea tarjetas en Trello para cada evento con sus detalles.
  - **Complejidad:** Media (8 nodos)

- **[1139-telegram-image-analysis.json](workflows/1139-telegram-image-analysis.json)**
  - **Descripción:** Este flujo automático detecta si un mensaje recibe una imagen y la analiza con OpenAI para enviar una respuesta procesada a través de Telegram.
  - **Complejidad:** Media (8 nodos)

- **[1145-congratulations-automator.json](workflows/1145-congratulations-automator.json)**
  - **Descripción:** Este flujo automático verifica si hay eventos programados hoy en la hoja de cálculo, y si es así, personaliza un mensaje con deseos felices para cada contacto y envía SMS usando Twilio.
  - **Complejidad:** Media (8 nodos)

- **[1179-telegram-freshdesk-integration.json](workflows/1179-telegram-freshdesk-integration.json)**
  - **Descripción:** Este flujo automatizado procesa mensajes de Telegram para crear tickets en Freshdesk o elementos en Monday.com dependiendo si contienen la palabra clave 'refund'.
  - **Complejidad:** Media (8 nodos)

- **[1200-telegram-image-analysis.json](workflows/1200-telegram-image-analysis.json)**
  - **Descripción:** Este flujo automático analiza imágenes de Telegram utilizando la API de OpenAI.
  - **Complejidad:** Media (8 nodos)

- **[1225-calvin-hobbes-discord.json](workflows/1225-calvin-hobbes-discord.json)**
  - **Descripción:** Este flujo automatizado obtiene diariamente las viñetas de Calvin y Hobbes desde GoComics, extrae el URL de la imagen y utiliza GPT-4o-mini para traducir los diálogos originales al inglés al coreano. Finalmente, publica ambos textos junto con la imagen en un canal de Discord.
  - **Complejidad:** Media (8 nodos)

- **[1226-youtube-discord-ai-summary.json](workflows/1226-youtube-discord-ai-summary.json)**
  - **Descripción:** Este flujo automático monitoriza nuevos videos de YouTube y genera resúmenes con inteligencia artificial que se comparten en Discord.
  - **Complejidad:** Media (8 nodos)

- **[1238-telegram-agente-multimedia.json](workflows/1238-telegram-agente-multimedia.json)**
  - **Descripción:** Este flujo automático permite a un bot de Telegram generar respuestas textuales utilizando GPT-4o e imágenes mediante DALL-E, manteniendo memoria contextual y dirigiéndose al usuario por su nombre.
  - **Complejidad:** Media (8 nodos)

- **[1462-enrich-pipedrive_s-organization-data-with-openai-gpt-slack.json](workflows/1462-enrich-pipedrive_s-organization-data-with-openai-gpt-slack.json)**
  - **Descripción:** Este flujo permite web scraping, resumen, extracción de datos, generación de contenido utilizando OpenAI/GPT, Slack, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (8 nodos)

- **[2609-monitor-precios-competicion.json](workflows/2609-monitor-precios-competicion.json)**
  - **Descripción:** Este flujo automático monitorea los precios de competidores mediante Google Sheets, consulta y procesa la respuesta con Airtop para detectar cambios significativos en los precios o planificaciones, actualiza el registro solo cuando hay diferencias sustanciales, y envía notificaciones por Slack si se detectan cambios.
  - **Complejidad:** Media (8 nodos)

- **[0075-syncro-opsgenie-integration.json](workflows/0075-syncro-opsgenie-integration.json)**
  - **Descripción:** Este flujo automático permite integrar incidentes de la herramienta Syncro con OpsGenie, creando y cerrando alertas automáticamente basadas en eventos recibidos por un webhook.
  - **Complejidad:** Media (7 nodos)

- **[0156-news-ycombinator-telegram.json](workflows/0156-news-ycombinator-telegram.json)**
  - **Descripción:** Este flujo verifica periódicamente si la respuesta del servidor de noticias cambió usando dos peticiones HTTP iguales y un bot de Telegram para notificar cuando ocurren cambios.
  - **Complejidad:** Media (7 nodos)

- **[0325-binance_telegram_price_alert.json](workflows/0325-binance_telegram_price_alert.json)**
  - **Descripción:** Este flujo automático vigila los cambios de precio en Binance y envía alertas por mensajes formateados vía Telegram cuando una criptomoneda experimenta un cambio mayor o igual al 15% (diferente a la menciona inicial) en las últimas 24 horas.
  - **Complejidad:** Media (7 nodos)

- **[0402-github-release-monitor.json](workflows/0402-github-release-monitor.json)**
  - **Descripción:** Este flujo verifica las últimas publicaciones (releases) de repositorios GitHub seleccionados cada día y envía una notificación a Slack si hay una nueva versión disponible.
  - **Complejidad:** Media (7 nodos)

- **[0475-nocodebot-multilang.json](workflows/0475-nocodebot-multilang.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Telegram mantener una conversación contextualizada sobre herramientas de código abierto (No-Code) mediante la integración con una base de datos Strapi.
  - **Complejidad:** Media (7 nodos)

- **[0498-resume-screener.json](workflows/0498-resume-screener.json)**
  - **Descripción:** Este flujo n8n escucha nuevos correos electrónicos en Gmail con adjuntos, extrae el texto del PDF, lo evalúa usando un agente de IA basado en LangChain y OpenAI, y registra los resultados estructurados (nombre, email, LinkedIn y puntuación) en una hoja de Google.
  - **Complejidad:** Media (7 nodos)

- **[0525-the-hive-alerts.json](workflows/0525-the-hive-alerts.json)**
  - **Descripción:** Este flujo automático verifica cuando se crea una nueva alerta en TheHive que no esté cerrada. Si la condición se cumple, envía una notificación a SIGNL4 (probablemente para enviar alarma por LINE) con los detalles de la alerta y también inicia un proceso adicional si es necesario.
  - **Complejidad:** Media (7 nodos)

- **[0747-twitter-monitor-n8n-mentions.json](workflows/0747-twitter-monitor-n8n-mentions.json)**
  - **Descripción:** Este flujo automático busca los últimos tweets que mencionan a una empresa en Twitter y los comparte en un canal de Slack si son más recientes que la ejecución anterior.
  - **Complejidad:** Media (7 nodos)

- **[0773-slack-birthday-contacts.json](workflows/0773-slack-birthday-contacts.json)**
  - **Descripción:** Este flujo automático permite a un usuario obtener de Google Contacts todas las personas con cumpleaños el día actual y enviar en automático mensajes de recordatorio de cumpleaños a un canal específico de Slack.
  - **Complejidad:** Media (7 nodos)

- **[0978-ai-cv-screening.json](workflows/0978-ai-cv-screening.json)**
  - **Descripción:** Este flujo automático recopila información de formularios y analiza CVs subidos en PDF para calificar a candidatos. Integra la evaluación con IA, envía notificaciones a HR y confirma el envío por email.
  - **Complejidad:** Media (7 nodos)

- **[1005-telegram-crypto-price-agent.json](workflows/1005-telegram-crypto-price-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot en Telegram mantener conversaciones sobre precios de criptomonedas utilizando memoria contextualizada y herramientas para consultar la API de CoinMarketCap.
  - **Complejidad:** Media (7 nodos)

- **[1174-github_n8n_releases.json](workflows/1174-github_n8n_releases.json)**
  - **Descripción:** Este flujo automático verifica cada día a las 10:00, 14:00 y 18:00 si hay nuevas versiones de n8n publicadas en GitHub, filtrando por releases del mismo día que incluyan 'n8n@' y un número con extensión decimal como '.0'. Si se detecta una nueva versión, envía notificaciones a través de Telegram y AWS SES.
  - **Complejidad:** Media (7 nodos)

- **[1215-telegram-tron-blacklist-checker.json](workflows/1215-telegram-tron-blacklist-checker.json)**
  - **Descripción:** Este flujo automático permite a un bot de Telegram verificar si una dirección de wallet TRON está en la lista negra consultando la API de Tronscan, y enviar el resultado al usuario.
  - **Complejidad:** Media (7 nodos)

- **[2574-maia-health-check.json](workflows/2574-maia-health-check.json)**
  - **Descripción:** Este flujo automático verifica las URLs listadas en un documento de Google Sheets periódicamente, mediante el nodo Schedule Trigger, y luego envía los resultados de estas verificaciones a través del bot de Telegram.
  - **Complejidad:** Media (7 nodos)

- **[2604-discord-chat-agent.json](workflows/2604-discord-chat-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con Discord manteniendo el contexto de la conversación mediante memoria.
  - **Complejidad:** Media (7 nodos)

- **[2709-email-to-telegram.json](workflows/2709-email-to-telegram.json)**
  - **Descripción:** Este flujo automatiza la lectura de correos electrónicos desde una cuenta IMAP y los convierte en páginas HTML hospedadas en GitHub Gist, enviando notificaciones al Telegram con un enlace accedo. Tras 3 horas, elimina el archivo Gist.
  - **Complejidad:** Media (7 nodos)

- **[2816-rss-telegram-updates.json](workflows/2816-rss-telegram-updates.json)**
  - **Descripción:** Este flujo automatiza la publicación de actualizaciones desde un feed RSS a Telegram. Lee entradas RSS, verifica si son nuevas usando fecha, y las envía al canal si son recientes.
  - **Complejidad:** Media (7 nodos)

- **[0186-164_Crear-canal-invitar-y-subir-archivo.json](workflows/0186-164_Crear-canal-invitar-y-subir-archivo.json)**
  - **Descripción:** Este flujo automatizado crea un canal en Slack usando un bot, invita a los usuarios especificados y luego envía un mensaje de bienvenida junto con el logo de n8n.
  - **Complejidad:** Media (6 nodos)

- **[0298-cheems-discord.json](workflows/0298-cheems-discord.json)**
  - **Descripción:** Este flujo automático envía recordatorios humorísticos en Discord todos los viernes y jueves por la mañana a las 9 AM, además de mensajes cada 30 minutos también utilizando el mismo webhook.
  - **Complejidad:** Media (6 nodos)

- **[0314-bill-bot.json](workflows/0314-bill-bot.json)**
  - **Descripción:** Este flujo automático procesa facturas recibidas por WhatsApp o Telegram, analiza los detalles con la API de Mindee, almacena la información en Google Sheets y envía una notificación por SMS.
  - **Complejidad:** Media (6 nodos)

- **[0466-mattermost-rss-monitor.json](workflows/0466-mattermost-rss-monitor.json)**
  - **Descripción:** Este flujo automático publica cada nuevo artículo de un feed RSS en el canal correspondiente de Mattermost, utilizando Mastodon como intermediario para la verificación.
  - **Complejidad:** Media (6 nodos)

- **[0492-notion-tasks-slack.json](workflows/0492-notion-tasks-slack.json)**
  - **Descripción:** Este flujo verifica cada hora a las 8 am los To Do de Notion, busca tareas asignadas al usuario 'NAME' y si hay alguna pendiente, envía una notificación directa en Slack a un usuario específico.
  - **Complejidad:** Media (6 nodos)

- **[0541-github-notifications-monitor.json](workflows/0541-github-notifications-monitor.json)**
  - **Descripción:** Este flujo automático consulta periódicamente (cada minuto) las notificaciones del usuario en GitHub y si existen, envía un resumen formateado a una aplicación de Discord.
  - **Complejidad:** Media (6 nodos)

- **[0729-gmail-invoice-alert.json](workflows/0729-gmail-invoice-alert.json)**
  - **Descripción:** Este flujo verifica nuevas facturas en Gmail usando Mindee y envía notificaciones por Slack o correo si el monto total es superior a 1000.
  - **Complejidad:** Media (6 nodos)

- **[0785-typeform-feedback.json](workflows/0785-typeform-feedback.json)**
  - **Descripción:** Este flujo procesa respuestas positivas de un formulario en Typeform y las agrega automáticamente a una tabla en Notion mientras crea una tarjeta en Trello y notifica en Slack.
  - **Complejidad:** Media (6 nodos)

- **[0935-uber_eats_expense_tracker.json](workflows/0935-uber_eats_expense_tracker.json)**
  - **Descripción:** Este flujo automático busca correos electrónicos en Gmail con el asunto específico '透過 Uber Eats 系统送出的订单', extrae información como precio, tienda, fecha y hora del contenido del email utilizando expresiones regulares, y luego envía esta información formateada a Slack mediante blocks. Además, proporciona un enlace directo para integrar con Moze expense tracker.
  - **Complejidad:** Media (6 nodos)

- **[1067-discord-gemini-response.json](workflows/1067-discord-gemini-response.json)**
  - **Descripción:** Este flujo automático permite a un bot de Discord utilizar Google Gemini para generar respuestas conversacionales basadas en una ventana de contexto, manteniendo la historia de la conversación mediante un buffer de memoria.
  - **Complejidad:** Media (6 nodos)

- **[1138-email-verificacion-google-sheets.json](workflows/1138-email-verificacion-google-sheets.json)**
  - **Descripción:** Este flujo automático verifica si el email no duplicado (basado en una función removeDuplicates) y verifica su existencia mediante API para verificar su existencia. Si existe, realiza una actualización en Google Sheets.
  - **Complejidad:** Media (6 nodos)

- **[1197-slack-rss-publicacion.json](workflows/1197-slack-rss-publicacion.json)**
  - **Descripción:** Este flujo automático publica en el canal de Slack 'news' todos los artículos del RSS feed de n8n.io/blog publicados la víspera.
  - **Complejidad:** Media (6 nodos)

- **[2547-todoist_weekly_review.json](workflows/2547-todoist_weekly_review.json)**
  - **Descripción:** Este flujo automatizado realiza una revisión semanal de tareas completadas en Todoist, agrupándolas por fecha para generar un informe diario que se envía como email.
  - **Complejidad:** Media (6 nodos)

- **[2633-icypeas-email-search.json](workflows/2633-icypeas-email-search.json)**
  - **Descripción:** Este flujo automático permite a un usuario desencadenar una búsqueda específica de email utilizando el servicio Icypeas. Los pasos incluyen autenticación mediante API key, API secret y User ID en un nodo personalizado que requiere activar el módulo crypto en n8n self-hosted.
  - **Complejidad:** Media (6 nodos)

- **[3028-telegram-woocommerce-notifications.json](workflows/3028-telegram-woocommerce-notifications.json)**
  - **Descripción:** Este flujo envía notificaciones de Telegram cuando un pedido de WooCommerce cambia su estado a 'Processing', incluyendo detalles como ID, nombre del cliente, monto total y productos ordenados.
  - **Complejidad:** Media (6 nodos)

- **[0053-ssl-expiry-checker.json](workflows/0053-ssl-expiry-checker.json)**
  - **Descripción:** Este flujo automático verifica si el certificado SSL de n8n.io ha caducado y envía una notificación por Telegram en caso afirmativo.
  - **Complejidad:** Media (5 nodos)

- **[0065-telegram-deploy-automation.json](workflows/0065-telegram-deploy-automation.json)**
  - **Descripción:** Este flujo automático escucha mensajes de Telegram, verifica si contienen '/deploy', y si es así extrae el primer argumento como etiqueta de versión. Luego desencadena una acción en GitHub para crear un release.
  - **Complejidad:** Media (5 nodos)

- **[0084-telegram-profanity-detector.json](workflows/0084-telegram-profanity-detector.json)**
  - **Descripción:** Este flujo automático detecta y responde con un mensaje de advertencia cuando se identifica lenguaje inapropiado (profanidad) en mensajes recibidos por el bot de Telegram.
  - **Complejidad:** Media (5 nodos)

- **[0109-ph-discord-rank.json](workflows/0109-ph-discord-rank.json)**
  - **Descripción:** Este flujo automático consulta cada hora la API de Product Hunt para obtener los proyectos más votados y envía los detalles formateados en un mensaje a Discord.
  - **Complejidad:** Media (5 nodos)

- **[0177-youtube-telegram-monitor.json](workflows/0177-youtube-telegram-monitor.json)**
  - **Descripción:** Este flujo automático verifica cada 30 minutos si hay nuevos videos de YouTube en un canal específico, los compara con los IDs ya procesados para evitar duplicados y envía por Telegram una notificación cuando se detecta contenido nuevo.
  - **Complejidad:** Media (5 nodos)

- **[0304-email-xml-to-http-post.json](workflows/0304-email-xml-to-http-post.json)**
  - **Descripción:** Este flujo automatizado extrae un email de IMAP, procesa el XML contenido en la primera adjunción y envía los datos mediante una solicitud HTTP POST a una API.
  - **Complejidad:** Media (5 nodos)

- **[0310-twitter-monitor.json](workflows/0310-twitter-monitor.json)**
  - **Descripción:** Este flujo monitoriza las menciones recientes de 'n8n_io' en Twitter y las publica en un canal de Mattermost.
  - **Complejidad:** Media (5 nodos)

- **[0311-website-stock-alert.json](workflows/0311-website-stock-alert.json)**
  - **Descripción:** Este flujo verifica periódicamente el contenido de una respuesta HTTP para determinar si contiene 'Out Of Stock', enviando notificaciones en Discord según los resultados.
  - **Complejidad:** Media (5 nodos)

- **[0316-icypeas-email-search.json](workflows/0316-icypeas-email-search.json)**
  - **Descripción:** Este flujo procesa resultados de búsqueda en tiempo real desde Icypeas y almacena el email, nombre y apellido.
  - **Complejidad:** Media (5 nodos)

- **[0355-slack-error-notification.json](workflows/0355-slack-error-notification.json)**
  - **Descripción:** Este flujo automático envía una notificación por Slack cuando un workflow falla, informando del nombre del workflow y la URL de ejecución.
  - **Complejidad:** Media (5 nodos)

- **[0358-telegram-error-notification.json](workflows/0358-telegram-error-notification.json)**
  - **Descripción:** Este flujo automatizado envía una notificación por Telegram cuando ocurre un error en otro workflow o proceso.
  - **Complejidad:** Media (5 nodos)

- **[0412-zendesk-unassigned-tickets-to-slack.json](workflows/0412-zendesk-unassigned-tickets-to-slack.json)**
  - **Descripción:** Este flujo automatizado consulta los tickets no asignados y pendientes de Zendesk, formatea su información y envía un mensaje resumen a un canal específico de Slack.
  - **Complejidad:** Media (5 nodos)

- **[0421-alertas-azure-task.json](workflows/0421-alertas-azure-task.json)**
  - **Descripción:** Este flujo automático verifica periódicamente en Elasticsearch la cantidad de alertas, y si supera un umbral específico (probablemente 0), crea automáticamente una incidencia en Azure DevOps.
  - **Complejidad:** Media (5 nodos)

- **[0446-telegram-welcome-bidirectional.json](workflows/0446-telegram-welcome-bidirectional.json)**
  - **Descripción:** Este flujo automático permite a un bot de Telegram enviar saludos personalizados en español cuando alguien se une o abandona un chat, utilizando webhooks.
  - **Complejidad:** Media (5 nodos)

- **[0494-monitor-alertas-postgres.json](workflows/0494-monitor-alertas-postgres.json)**
  - **Descripción:** Este flujo automático verifica periódicamente registros en la base de datos PostgreSQL donde el valor es mayor a 70 y no ha sido notificado, luego actualiza el estado de dichos registros para marcarlos como notificados e informa por SMS mediante Twilio.
  - **Complejidad:** Media (5 nodos)

- **[0501-pager-duty-jira-integracion.json](workflows/0501-pager-duty-jira-integracion.json)**
  - **Descripción:** Este flujo automático actualiza el estado de un incidente en PagerDuty y su correspondiente incidencia en Jira, notificando luego a canales Mattermost.
  - **Complejidad:** Media (5 nodos)

- **[0550-zammad-tickets-summary.json](workflows/0550-zammad-tickets-summary.json)**
  - **Descripción:** Este flujo automático permite consultar el número de tickets abiertos y nuevos en Zammad, filtrándolos por estado, y enviar un resumen a la sala de soporte de Zulip.
  - **Complejidad:** Media (5 nodos)

- **[0672-webhook-weather-sync.json](workflows/0672-webhook-weather-sync.json)**
  - **Descripción:** Este flujo automatizado recibe datos via webhook, extrae información clave y la almacena en Airtable para su posterior uso. Posteriormente, consulta el clima de la ciudad proporcionada utilizando OpenWeatherMap API y envía un mensaje por SMS a un número específico con los detalles del pronóstico mediante Twilio.
  - **Complejidad:** Media (5 nodos)

- **[0676-google-sheets-telegram-batch.json](workflows/0676-google-sheets-telegram-batch.json)**
  - **Descripción:** Este flujo procesa entradas de Google Sheets por lotes y envía cada lote a Telegram.
  - **Complejidad:** Media (5 nodos)

- **[0679-bitcoin-monitor-sms.json](workflows/0679-bitcoin-monitor-sms.json)**
  - **Descripción:** Este flujo verifica cada minuto el precio de Bitcoin en euros desde CoinGecko y envía un SMS si supera los 9000 EUR.
  - **Complejidad:** Media (5 nodos)

- **[0692-disco-alerta-cron.json](workflows/0692-disco-alerta-cron.json)**
  - **Descripción:** Este flujo verifica automáticamente cada día las 9:00 AM y 4:00 PM el espacio en disco de la raíz del sistema (host). Si detecta que está superior al 80%, envía una alerta por SMS a Twilio, notificando el porcentaje exacto de uso. En caso contrario, no realiza ninguna acción.
  - **Complejidad:** Media (5 nodos)

- **[0695-automizy-list-management.json](workflows/0695-automizy-list-management.json)**
  - **Descripción:** Este flujo automatiza la creación de una nueva lista en Automizy, añade un contacto con email predeterminado y actualizado, luego obtiene todos los contactos almacenados.
  - **Complejidad:** Media (5 nodos)

- **[0751-weather-alert-schedule.json](workflows/0751-weather-alert-schedule.json)**
  - **Descripción:** Este workflow verifica el tiempo actual de Berlin cada vez que se inicia manualmente o en horario programado (06:15), comparando la temperatura con un umbral y enviando una alerta por signl4 si es menor a 25°C.
  - **Complejidad:** Media (5 nodos)

- **[0837-analisis-retroalimentacion-mattermost.json](workflows/0837-analisis-retroalimentacion-mattermost.json)**
  - **Descripción:** Este flujo analiza el sentimiento de un comentario de retroalimentación utilizando la API de Google Cloud Natural Language y, si es positivo (score > 0), envía una notificación al canal especificado en Mattermost.
  - **Complejidad:** Media (5 nodos)

- **[0838-typeform-mattermost-sentimiento-negativo.json](workflows/0838-typeform-mattermost-sentimiento-negativo.json)**
  - **Descripción:** Este flujo analiza el sentimiento de comentarios en formularios de Typeform y envía a un canal de Mattermost solo aquellos que tienen una valoración negativa.
  - **Complejidad:** Media (5 nodos)

- **[0859-telegram-gmail-alertas.json](workflows/0859-telegram-gmail-alertas.json)**
  - **Descripción:** Este flujo automatiza el envío de correos electrónicos filtrados de Gmail a un chat de Telegram, notificando solo aquellos con asuntos que contengan palabras clave específicas como 'Urgente' o 'Server Down'.
  - **Complejidad:** Media (5 nodos)

- **[0863-weather-slack-integration.json](workflows/0863-weather-slack-integration.json)**
  - **Descripción:** Este flujo automático permite recibir ubicaciones en mensajes de Slack, buscar sus coordenadas usando OpenStreetMap y luego obtener el pronóstico meteorológico local a través del National Weather Service API para enviar la información formateada como texto en el mismo canal de Slack.
  - **Complejidad:** Media (5 nodos)

- **[1011-producthunt-monitor-ai-agents.json](workflows/1011-producthunt-monitor-ai-agents.json)**
  - **Descripción:** Este flujo automático busca los últimos lanzamientos de productos relacionados con 'AI Agents' en ProductHunt, verifica si hay resultados válidos y envía una actualización a un canal de Slack diariamente.
  - **Complejidad:** Media (5 nodos)

- **[1085-send-sms-clicksend.json](workflows/1085-send-sms-clicksend.json)**
  - **Descripción:** Este flujo permite enviar un mensaje de texto (SMS) mediante la API de ClickSend cuando se activa manualmente.
  - **Complejidad:** Media (5 nodos)

- **[1181-typeform-problems-monitor.json](workflows/1181-typeform-problems-monitor.json)**
  - **Descripción:** Este flujo automático captura envíos de formulario Typeform y los almacena en Google Sheets. Si la severidad es mayor a 7, envía un email y actualiza el canal de Slack con detalles del problema.
  - **Complejidad:** Media (5 nodos)

- **[1203-line-error-alerts.json](workflows/1203-line-error-alerts.json)**
  - **Descripción:** Este flujo automático permite configurar un workflow de n8n para recibir notificaciones inmediatas por LINE cuando ocurre un error en otro workflow. Detecta errores automáticamente y envía una alerta al usuario especificado mediante el botón 'Enviar cuerpo como JSON' a la API de LINE.
  - **Complejidad:** Media (5 nodos)

- **[0035-airtable-mailcheck-validacion.json](workflows/0035-airtable-mailcheck-validacion.json)**
  - **Descripción:** Este flujo verifica automáticamente el correo electrónico de un contacto en la base de datos y actualiza el campo 'Valid' en una tabla de Airtable con el resultado. Primero lista registros de Airtable, luego toma el email para hacer la verificación mediante Mailcheck API.
  - **Complejidad:** Baja (4 nodos)

- **[0037-mattermost-trigger.json](workflows/0037-mattermost-trigger.json)**
  - **Descripción:** Este flujo inverso utiliza una actualización de Mattermost como entrada para disparar un evento y enviar el mensaje configurado.
  - **Complejidad:** Baja (4 nodos)

- **[0048-notion-mattermost-marketing.json](workflows/0048-notion-mattermost-marketing.json)**
  - **Descripción:** Este flujo automático verifica si una página nueva en la base de datos Notion específica es del equipo Marketing y, en ese caso, envía un mensaje a Mattermost con detalles sobre la nueva página.
  - **Complejidad:** Baja (4 nodos)

- **[0059-mattermost-bot-config.json](workflows/0059-mattermost-bot-config.json)**
  - **Descripción:** Este flujo de trabajo inicializa y guarda en un archivo binario las configuraciones necesarias para el funcionamiento del bot de Mattermost.
  - **Complejidad:** Baja (4 nodos)

- **[0138-telegram-receipts-textract.json](workflows/0138-telegram-receipts-textract.json)**
  - **Descripción:** Este flujo automático permite recibir un documento (probablemente una factura) a través del bot de Telegram, descargarlo y subirlo al almacenamiento en la nube S3. Posteriormente, utiliza AWS Textract para analizar el texto contenido en ese archivo y finalmente guarda los resultados extraídos en una tabla específica de Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[0175-pagerduty-incident-flow.json](workflows/0175-pagerduty-incident-flow.json)**
  - **Descripción:** Este flujo automático permite crear una incidencia en PagerDuty, actualizarla y luego obtener sus detalles.
  - **Complejidad:** Baja (4 nodos)

- **[0188-kafka-temp-alert.json](workflows/0188-kafka-temp-alert.json)**
  - **Descripción:** Este flujo recibe mensajes de Kafka desde el tópico topic_test y envía un SMS cuando la temperatura supera los 50 grados.
  - **Complejidad:** Baja (4 nodos)

- **[0230-mattermost-channel-onboarding.json](workflows/0230-mattermost-channel-onboarding.json)**
  - **Descripción:** Este flujo automático crea un canal de Mattermost, agrega miembros a él y luego publica un mensaje en ese mismo canal.
  - **Complejidad:** Baja (4 nodos)

- **[0258-rabbitmq-sms-alert.json](workflows/0258-rabbitmq-sms-alert.json)**
  - **Descripción:** Este flujo recibe mensajes de una cola RabbitMQ que contienen un campo 'temp', y si este excede los 50 grados Celsius, envía un SMS de alerta usando Vonage.
  - **Complejidad:** Baja (4 nodos)

- **[0264-mattermost-language-inclusion.json](workflows/0264-mattermost-language-inclusion.json)**
  - **Descripción:** Este flujo automatizado detecta términos de género excluyente (como 'guys', 'bros') en los mensajes entrantes y sugiere el uso de lenguaje inclusivo mediante un mensaje predefinido en Mattermost.
  - **Complejidad:** Baja (4 nodos)

- **[0275-sheets-discord-table.json](workflows/0275-sheets-discord-table.json)**
  - **Descripción:** Este flujo automatizado envía un mensaje formateado en tabla ASCII de Google Sheets al canal Discord cuando hay cambios (nueva fila o actualización) en la hoja de cálculo especificada.
  - **Complejidad:** Baja (4 nodos)

- **[0340-telegram-ai-bot.json](workflows/0340-telegram-ai-bot.json)**
  - **Descripción:** Este flujo automático permite a un bot de Telegram mantener una conversación utilizando el modelo OpenAI GPT-4o-mini, enviando respuestas con emojis.
  - **Complejidad:** Baja (4 nodos)

- **[0476-mailerlite-airtable-sync.json](workflows/0476-mailerlite-airtable-sync.json)**
  - **Descripción:** Este flujo detecta cuando un suscriptor es añadido a un grupo en MailerLite y guarda automáticamente su nombre y email en una tabla de Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[0520-daily-english-poems.json](workflows/0520-daily-english-poems.json)**
  - **Descripción:** Este flujo automático envía un poema aleatorio diario de forma traducida al inglés británico, utilizando la API de Poemist y Telegram.
  - **Complejidad:** Baja (4 nodos)

- **[0539-banner-cocktail.json](workflows/0539-banner-cocktail.json)**
  - **Descripción:** Este flujo automático muestra una receta aleatoria de cóctel cada viernes a las 18:00 mediante un mensaje con imagen en Rocket.Chat.
  - **Complejidad:** Baja (4 nodos)

- **[0549-github-stars-slack.json](workflows/0549-github-stars-slack.json)**
  - **Descripción:** Este flujo automático monitorea cambios en estrellas del repositorio de GitHub 'n8n' y envía mensajes en tiempo real a un canal de Slack.
  - **Complejidad:** Baja (4 nodos)

- **[0632-slack-github-email-query.json](workflows/0632-slack-github-email-query.json)**
  - **Descripción:** Este flujo automático consulta información de usuario y sus últimas contribuciones en GitHub mediante GraphQL, procesa los correos electrónicos encontrados (filtrando aquellos que no corresponden a un usuario real) y envía un mensaje formateado con estos datos al canal Slack especificado.
  - **Complejidad:** Baja (4 nodos)

- **[0656-teams-automation.json](workflows/0656-teams-automation.json)**
  - **Descripción:** Este flujo automático permite ejecutar manualmente una secuencia de acciones en Microsoft Teams, donde primero se inicia la conexión con un equipo predefinido, luego se actualiza su nombre y finalmente se envía un mensaje a un canal específico.
  - **Complejidad:** Baja (4 nodos)

- **[0726-typeform-airtable-slack.json](workflows/0726-typeform-airtable-slack.json)**
  - **Descripción:** Este flujo automático recoge respuestas de un formulario Typeform, extrae el nombre y correo electrónico del usuario, los agrega en Airtable y envía una notificación a Slack.
  - **Complejidad:** Baja (4 nodos)

- **[0894-telegram-gpt-ai-agent.json](workflows/0894-telegram-gpt-ai-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Telegram procesar mensajes entrantes del usuario utilizando el modelo GPT de OpenAI y enviar una respuesta enriquecida con emojis.
  - **Complejidad:** Baja (4 nodos)

- **[0911-google-calendar-telegram-eventos.json](workflows/0911-google-calendar-telegram-eventos.json)**
  - **Descripción:** Este flujo automático envía a un chat de Telegram una notificación cuando se crea un nuevo evento en Google Calendar. Extrae detalles clave como el nombre del evento, descripción, ubicación, fecha y hora de inicio y fin, y lo envía al chat especificado.
  - **Complejidad:** Baja (4 nodos)

- **[1069-telegram-error-handler.json](workflows/1069-telegram-error-handler.json)**
  - **Descripción:** Este flujo automático envía notificaciones de error a un chat de Telegram específico cuando ocurre un fallo en cualquier ejecución del workflow.
  - **Complejidad:** Baja (4 nodos)

- **[1077-twilio-http-monitor.json](workflows/1077-twilio-http-monitor.json)**
  - **Descripción:** Este flujo automático verifica periódicamente el estado de una URL mediante una solicitud HTTP y envía un SMS a través de Twilio si la respuesta es exitosa (código 200).
  - **Complejidad:** Baja (4 nodos)

- **[1084-form-to-airtable.json](workflows/1084-form-to-airtable.json)**
  - **Descripción:** Este flujo automatizado captura automáticamente los datos de un formulario y los almacena en una tabla de Airtable sin intervención manual. Cada envío del formulario crea un nuevo registro con campos personalizados para 'Name', 'Age', 'Email', 'Address' y 'Subscription'.
  - **Complejidad:** Baja (4 nodos)

- **[1165-telegram-sticker-checker.json](workflows/1165-telegram-sticker-checker.json)**
  - **Descripción:** Este workflow analiza si el mensaje recibido en Telegram contiene un sticker. Si es así, responde con información sobre el remitente y los detalles del sticker (ID y set_name). En caso contrario, envía un mensaje indicando que no se encontró ningún sticker.
  - **Complejidad:** Baja (4 nodos)

- **[0015-berlin-clima-plivo.json](workflows/0015-berlin-clima-plivo.json)**
  - **Descripción:** Este flujo automático envía cada día a las 9:00 el pronóstico del tiempo actual de Berlín mediante un mensaje usando Plivo.
  - **Complejidad:** Baja (3 nodos)

- **[0046-email-invite-calendar.json](workflows/0046-email-invite-calendar.json)**
  - **Descripción:** Este flujo automático envía un email de invitación al encuentro concreto cuando se hace clic en el botón 'execute', adjuntando la iCal correspondiente.
  - **Complejidad:** Baja (3 nodos)

- **[0080-shopify-product-alerts.json](workflows/0080-shopify-product-alerts.json)**
  - **Descripción:** Este flujo automático envía un mensaje cuando se crea un nuevo producto en Shopify, tanto a Twitter como al chat de Telegram.
  - **Complejidad:** Baja (3 nodos)

- **[0155-mattermost-financial-metrics-cron.json](workflows/0155-mattermost-financial-metrics-cron.json)**
  - **Descripción:** Este flujo automático envía métricas financieras mensuales de ProfitWell a Mattermost cada día en horario programado.
  - **Complejidad:** Baja (3 nodos)

- **[0172-slack-file-downloader.json](workflows/0172-slack-file-downloader.json)**
  - **Descripción:** Este flujo manual descarga un archivo de la URL especificada y lo envía al canal de Slack usando autenticación OAuth2.
  - **Complejidad:** Baja (3 nodos)

- **[0208-apod-telegram-daily.json](workflows/0208-apod-telegram-daily.json)**
  - **Descripción:** Este flujo automático envía la Astronomy Picture of The Day (APOD) de NASA cada día a las 8:00 PM en un mensaje con su título como subtítulo mediante el bot de Telegram.
  - **Complejidad:** Baja (3 nodos)

- **[0268-uProc_telegram_screenshot.json](workflows/0268-uProc_telegram_screenshot.json)**
  - **Descripción:** Este flujo automático permite crear capturas de pantalla de sitios web y enviarlas automáticamente a un canal de Telegram.
  - **Complejidad:** Baja (3 nodos)

- **[0299-airtable-mailchimp-sync.json](workflows/0299-airtable-mailchimp-sync.json)**
  - **Descripción:** Este flujo automático sincroniza entradas de la tabla Users en Airtable con una lista específica de Mailchimp, convirtiendo el campo Email en suscriptor y usando Name como valor para el campo FNAME.
  - **Complejidad:** Baja (3 nodos)

- **[0301-telegram-journal-reminder.json](workflows/0301-telegram-journal-reminder.json)**
  - **Descripción:** Este flujo automático envía cada mañana un recordatorio por Telegram para reflexionar sobre las actividades realizadas el día anterior.
  - **Complejidad:** Baja (3 nodos)

- **[0307-send-sms-from-airtable.json](workflows/0307-send-sms-from-airtable.json)**
  - **Descripción:** Este flujo automático permite enviar SMS utilizando Twilio a números y nombres almacenados en Airtable.
  - **Complejidad:** Baja (3 nodos)

- **[0308-typeform-whatsapp-message.json](workflows/0308-typeform-whatsapp-message.json)**
  - **Descripción:** Este flujo automático permite recibir nuevas respuestas de Typeform y enviarlas formateadas a WhatsApp usando Twilio.
  - **Complejidad:** Baja (3 nodos)

- **[0469-telegram-meteogram.json](workflows/0469-telegram-meteogram.json)**
  - **Descripción:** Este flujo automático permite recibir mensajes en Telegram sobre el clima y enviar de vuelta un informe con la descripción del tiempo actual, temperatura real y sensación térmica para la ciudad especificada.
  - **Complejidad:** Baja (3 nodos)

- **[0500-pagerduty-mattermost-update.json](workflows/0500-pagerduty-mattermost-update.json)**
  - **Descripción:** Este flujo automático permite a un sistema recibir una notificación vía webhook que contiene el ID de un incidente en PagerDuty. Una vez recibida la información, actualiza automáticamente el estado del incidente a 'acknowledged' y envía una confirmación al canal correspondiente de Mattermost.
  - **Complejidad:** Baja (3 nodos)

- **[0503-error-alertas.json](workflows/0503-error-alertas.json)**
  - **Descripción:** Este flujo automático detecta errores en trabajos y envía notificaciones tanto por SMS como por Mattermost.
  - **Complejidad:** Baja (3 nodos)

- **[0548-telegram-journal-saver.json](workflows/0548-telegram-journal-saver.json)**
  - **Descripción:** Este flujo automático captura respuestas de usuario en Telegram para guardar entradas diarias en una hoja de cálculo.
  - **Complejidad:** Baja (3 nodos)

- **[0620-58_telegram_coktai_random.json](workflows/0620-58_telegram_coktai_random.json)**
  - **Descripción:** Este flujo automático captura mensajes de Telegram usando el webhook. Luego realiza una solicitud GET a la API de TheCocktailDB para obtener un cóctel aleatorio y extrae su imagen y nombre.
  - **Complejidad:** Baja (3 nodos)

- **[0630-telegram-bash-automated-response.json](workflows/0630-telegram-bash-automated-response.json)**
  - **Descripción:** Este flujo automatizado permite que cuando se recibe un mensaje en el bot de Telegram (bash-dash), se envíe automáticamente una respuesta.
  - **Complejidad:** Baja (3 nodos)

- **[0638-mattermost-chatbot-response.json](workflows/0638-mattermost-chatbot-response.json)**
  - **Descripción:** Este flujo automatizado utiliza una webhook de Mattermost para procesar mensajes y enviar notificaciones con información almacenada mediante el nodo Set.
  - **Complejidad:** Baja (3 nodos)

- **[0670-n8n-cron-google-sheets-mattermost.json](workflows/0670-n8n-cron-google-sheets-mattermost.json)**
  - **Descripción:** Este flujo automático ejecuta una tarea en Mattermost cada año el 17 de diciembre a las 00:00 (UTC), utilizando valores dinámicos extraídos de Google Sheets.
  - **Complejidad:** Baja (3 nodos)

- **[0693-woocommerce-order-notification.json](workflows/0693-woocommerce-order-notification.json)**
  - **Descripción:** Este flujo automático envía una notificación a Slack cuando se crea un nuevo pedido en WooCommerce, siempre que el total de la orden sea igual o superior a 100.
  - **Complejidad:** Baja (3 nodos)

- **[0696-woocommerce-refund-notification.json](workflows/0696-woocommerce-refund-notification.json)**
  - **Descripción:** Este flujo verifica cuando un pedido WooCommerce se actualiza a estado refundado y si el total supera o iguala los 100, enviando automáticamente una notificación al canal Slack 'woo-commerce' con detalles específicos.
  - **Complejidad:** Baja (3 nodos)

- **[0697-weather-daily-update.json](workflows/0697-weather-daily-update.json)**
  - **Descripción:** Este flujo programado envía cada día una notificación Pushcut con el pronóstico meteorológico de Berlin.
  - **Complejidad:** Baja (3 nodos)

- **[0702-daily-weather-alert.json](workflows/0702-daily-weather-alert.json)**
  - **Descripción:** Este flujo automático envía cada día un mensaje SMS con la temperatura actual del usuario especificado en OpenWeatherMap.
  - **Complejidad:** Baja (3 nodos)

- **[0703-new-product-twitter-telegram.json](workflows/0703-new-product-twitter-telegram.json)**
  - **Descripción:** Este flujo automático anuncia la creación de nuevos productos en WooCommerce en Twitter y Telegram.
  - **Complejidad:** Baja (3 nodos)

- **[0730-diaria-temperatura-push.json](workflows/0730-diaria-temperatura-push.json)**
  - **Descripción:** Este flujo programado ejecuta un chequeo diario a las 9 AM para obtener la temperatura actual de Berlin y envía una notificación Pushover con esta información.
  - **Complejidad:** Baja (3 nodos)

- **[0777-telegram-file-downloader.json](workflows/0777-telegram-file-downloader.json)**
  - **Descripción:** Este flujo automático descarga y guarda en Google Drive los archivos nuevos recibidos por mensaje de Telegram.
  - **Complejidad:** Baja (3 nodos)

- **[1061-telegram-echo-bot.json](workflows/1061-telegram-echo-bot.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de Telegram mostrar el contenido JSON de cualquier mensaje o evento recibido en tiempo real.
  - **Complejidad:** Baja (3 nodos)

- **[1111-mattermost-bebida.json](workflows/1111-mattermost-bebida.json)**
  - **Descripción:** Este flujo permite recibir una solicitud POST vía webhook, obtener datos aleatorios de una API (como receta de cóctel), y enviar un mensaje formateado a Mattermost con detalles específicos.
  - **Complejidad:** Baja (3 nodos)

- **[2626-stripe-payment-auto.json](workflows/2626-stripe-payment-auto.json)**
  - **Descripción:** Este flujo automático permite recibir notificaciones de pagos a través del webhook 'checkout.session.completed' y extraer automáticamente información sobre el cliente (nombre, email) y el producto adquirido mediante una llamada HTTP posterior a la API de Stripe.
  - **Complejidad:** Baja (3 nodos)

- **[0029-mattermost-emelia-trigger.json](workflows/0029-mattermost-emelia-trigger.json)**
  - **Descripción:** Este flujo automático envía notificaciones a Mattermost cuando alguien responde en una campaña específica de Emelia.
  - **Complejidad:** Baja (2 nodos)

- **[0036-mattermost-notificacion-iniciado.json](workflows/0036-mattermost-notificacion-iniciado.json)**
  - **Descripción:** Este flujo de trabajo utiliza el inicio automático de n8n para enviar un mensaje en el canal especificado de Mattermost con la hora exacta del momento de activación.
  - **Complejidad:** Baja (2 nodos)

- **[0100-zulip-send-private-message.json](workflows/0100-zulip-send-private-message.json)**
  - **Descripción:** Este flujo permite enviar un mensaje privado en Zulip mediante un desencadenador manual.
  - **Complejidad:** Baja (2 nodos)

- **[0106-google-drive-email-alert.json](workflows/0106-google-drive-email-alert.json)**
  - **Descripción:** Este flujo automático envía un email cuando se crea un archivo en una carpeta específica de Google Drive.
  - **Complejidad:** Baja (2 nodos)

- **[0115-facebook-profile-changes-mattermost.json](workflows/0115-facebook-profile-changes-mattermost.json)**
  - **Descripción:** Este flujo automatizado envía una notificación por Mattermost cuando un usuario actualiza su perfil en Facebook.
  - **Complejidad:** Baja (2 nodos)

- **[0118-slack-error-alert.json](workflows/0118-slack-error-alert.json)**
  - **Descripción:** Este flujo automático envía una notificación por mensaje al nodo Slack cuando ocurre un error en el workflow 'Error Trigger'.
  - **Complejidad:** Baja (2 nodos)

- **[0161-onfleet-driver-signup-alert.json](workflows/0161-onfleet-driver-signup-alert.json)**
  - **Descripción:** Este flujo automático envía un mensaje a Slack cuando se crea un nuevo conductor en Onfleet.
  - **Complejidad:** Baja (2 nodos)

- **[0164-mattermost-airtable-trigger.json](workflows/0164-mattermost-airtable-trigger.json)**
  - **Descripción:** Este flujo monitoriza un registro en Airtable llamado 'Data' y envía una notificación al canal de Mattermost especificado cuando se añade nueva información.
  - **Complejidad:** Baja (2 nodos)

- **[0261-mattermost-woocommerce-pedido.json](workflows/0261-mattermost-woocommerce-pedido.json)**
  - **Descripción:** Este flujo automático envía un mensaje en el canal especificado de Mattermost cuando se crea un nuevo pedido en WooCommerce, incluyendo el nombre del comprador y el primer producto adquirido.
  - **Complejidad:** Baja (2 nodos)

- **[0465-discord-webhook-message.json](workflows/0465-discord-webhook-message.json)**
  - **Descripción:** Este flujo automático permite enviar un mensaje 'Hello World!' a una canal de Discord mediante el uso de webhooks.
  - **Complejidad:** Baja (2 nodos)

- **[0528-twilio_trigger.json](workflows/0528-twilio_trigger.json)**
  - **Descripción:** Este flujo automático permite ejecutar manualmente acciones en Twilio a través de una API utilizando el trigger manual.
  - **Complejidad:** Baja (2 nodos)

- **[0536-signl4-test-alert.json](workflows/0536-signl4-test-alert.json)**
  - **Descripción:** Este flujo manual permite desencadenar una alerta predefinida en SIGNL4 al hacer clic en el botón 'execute', enviando un mensaje y título de ejemplo.
  - **Complejidad:** Baja (2 nodos)

- **[0556-msg91-sms-flow.json](workflows/0556-msg91-sms-flow.json)**
  - **Descripción:** Este flujo automático permite enviar SMS utilizando el servicio MSG91 a través de una activación manual.
  - **Complejidad:** Baja (2 nodos)

- **[0565-mailgun-email-sender-test.json](workflows/0565-mailgun-email-sender-test.json)**
  - **Descripción:** Este flujo manual permite enviar un mensaje de email predefinido cuando se hace clic en el botón 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[0604-sms-alert-error-notification.json](workflows/0604-sms-alert-error-notification.json)**
  - **Descripción:** Este flujo de trabajo envía una alerta por SMS cuando un workflow específico falla en su ejecución.
  - **Complejidad:** Baja (2 nodos)

- **[0605-mandrill-email.json](workflows/0605-mandrill-email.json)**
  - **Descripción:** Este flujo permite enviar un correo utilizando la plantilla 'welcomeemailv2' desde el nodo Mandrill al hacer clic en 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[0624-mocean-sms.json](workflows/0624-mocean-sms.json)**
  - **Descripción:** Este flujo automático permite enviar un mensaje de texto (SMS) a través del servicio Mocean mediante una activación manual.
  - **Complejidad:** Baja (2 nodos)

- **[0626-github-release-slack-notification.json](workflows/0626-github-release-slack-notification.json)**
  - **Descripción:** Este flujo automático monitoriza nuevas publicaciones (releases) en el repositorio 'Mesdocteurs/mda-admin-partner-api' de GitHub y envía una notificación por mensaje en Slack al canal 'extranet-md'.
  - **Complejidad:** Baja (2 nodos)

- **[0689-nuevo-producto-slack.json](workflows/0689-nuevo-producto-slack.json)**
  - **Descripción:** Este flujo automático detecta la creación de nuevos productos en WooCommerce y envía una notificación al canal Slack.
  - **Complejidad:** Baja (2 nodos)

- **[0704-messagebird-sms-trigger.json](workflows/0704-messagebird-sms-trigger.json)**
  - **Descripción:** Este flujo automático permite enviar un SMS utilizando MessageBird mediante una activación manual.
  - **Complejidad:** Baja (2 nodos)

- **[0721-error-trigger-mailgun.json](workflows/0721-error-trigger-mailgun.json)**
  - **Descripción:** Este flujo utiliza un trigger de error para enviar notificaciones por correo cuando ocurre un error en la ejecución del workflow.
  - **Complejidad:** Baja (2 nodos)

- **[0733-automatic-sms-trigger.json](workflows/0733-automatic-sms-trigger.json)**
  - **Descripción:** Este flujo automático permite enviar un SMS predefinido al hacer clic en el botón 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[0734-pushcut-sms-trigger.json](workflows/0734-pushcut-sms-trigger.json)**
  - **Descripción:** Este flujo automático envía un SMS cuando se activa la acción 'Leaving Home' mediante Pushcut.
  - **Complejidad:** Baja (2 nodos)

- **[0756-lemplist-mattermost-email-reply.json](workflows/0756-lemplist-mattermost-email-reply.json)**
  - **Descripción:** Este flujo automático envía notificaciones de respuestas recibidas en una campaña específica de Lemplist a un canal designado en Mattermost.
  - **Complejidad:** Baja (2 nodos)

- **[1105-netlify-deploy-alert.json](workflows/1105-netlify-deploy-alert.json)**
  - **Descripción:** Este flujo automático detecta fallos en despliegues de Netlify y envía una alerta a un canal de Slack.
  - **Complejidad:** Baja (2 nodos)

- **[0540-paypal-billing-plan-activated-trigger.json](workflows/0540-paypal-billing-plan-activated-trigger.json)**
  - **Descripción:** Este flujo automático permite a n8n recibir notificaciones cuando PayPal activa un plan de facturación.
  - **Complejidad:** Baja (1 nodos)

- **[0554-aws-sns-trigger.json](workflows/0554-aws-sns-trigger.json)**
  - **Descripción:** Este flujo utiliza una suscripción de AWS SNS para recibir notificaciones y potencialmente iniciar procesos o workflows en respuesta.
  - **Complejidad:** Baja (1 nodos)

- **[0564-line-chatbot-memory.json](workflows/0564-line-chatbot-memory.json)**
  - **Descripción:** Este flujo se activa cuando un email es enviado mediante la API de Mailjet.
  - **Complejidad:** Baja (1 nodos)

- **[0578-calendly-eventos-monitor.json](workflows/0578-calendly-eventos-monitor.json)**
  - **Descripción:** Este flujo monitoriza eventos de Calendly para recibir notificaciones cuando se crea o cancela un participante en una cita.
  - **Complejidad:** Baja (1 nodos)


### Sincronización de Datos y Archivos

- **[2887-ai-language-tools.json](workflows/2887-ai-language-tools.json)**
  - **Descripción:** Este flujo incluye una variedad de nodos relacionados con agentes de lenguaje y herramientas de IA, como transformadores de lenguaje, cadenas de encadenamiento, extraedores de información, analizadores de sentimiento, herramientas de vectores y memoria. También contiene conexiones con servicios externos como Google Sheets, Dropbox, Gmail, Twitter y más.
  - **Complejidad:** Media (13 nodos)

- **[2825-gestion_citas_vapi.json](workflows/2825-gestion_citas_vapi.json)**
  - **Descripción:** Este flujo automático gestiona la reserva y gestión de citas mediante Vapi, Google Calendar y Airtable. Permite verificar disponibilidad, crear, actualizar y eliminar eventos, así como registrar información de llamadas telefónicas.
  - **Complejidad:** Media (9 nodos)

- **[0204-clientes-condicion.json](workflows/0204-clientes-condicion.json)**
  - **Descripción:** Este flujo procesa datos de clientes mediante filtros y bifurcaciones condicionales para segmentarlos por país.
  - **Complejidad:** Media (9 nodos)

- **[0276-notion-outlook-sync.json](workflows/0276-notion-outlook-sync.json)**
  - **Descripción:** Este flujo automático sincroniza eventos del calendario Outlook con páginas de base de datos en Notion mediante la verificación y creación/actualización basada en el ID del evento.
  - **Complejidad:** Media (9 nodos)

- **[0290-feedback-openai-google.json](workflows/0290-feedback-openai-google.json)**
  - **Descripción:** Este flujo automático permite recoger comentarios de clientes a través de un formulario y utilizar OpenAI para analizar su sentimiento. Los resultados junto con los datos del formulario se combinan y guardan automáticamente en una hoja de Google.
  - **Complejidad:** Media (9 nodos)

- **[0324-google-drive-file-share.json](workflows/0324-google-drive-file-share.json)**
  - **Descripción:** Este flujo n8n permite obtener y compartir archivos de Google Drive en modo público mediante una ejecución manual.
  - **Complejidad:** Media (9 nodos)

- **[0384-api-flutterflow-data.json](workflows/0384-api-flutterflow-data.json)**
  - **Descripción:** Este flujo n8n se utiliza para crear una API en FlutterFlow que recibe datos desde un almacén de datos (como 'Customer Datastore') y los inserta en una variable antes de devolverlos como JSON a la aplicación.
  - **Complejidad:** Media (9 nodos)

- **[0426-token-management.json](workflows/0426-token-management.json)**
  - **Descripción:** Este flujo utiliza variables estáticas persistentes para gestionar un token de acceso que caduca después de 1 minuto. Cuando el token expira (por la verificación en 'if token is valid'), se solicita uno nuevo mediante HTTP y actualiza los datos estáticos.
  - **Complejidad:** Media (9 nodos)

- **[0448-upwork-jobs-sync.json](workflows/0448-upwork-jobs-sync.json)**
  - **Descripción:** Este flujo consulta trabajos recientes de Upwork usando Apify y MongoDB. Si las horas son entre 2-15, verifica si ya existen entradas similares por título y presupuesto antes de insertarlas.
  - **Complejidad:** Media (9 nodos)

- **[0504-sharepoint-upload.json](workflows/0504-sharepoint-upload.json)**
  - **Descripción:** Este flujo automático sube archivos a Microsoft SharePoint utilizando Graph API.
  - **Complejidad:** Media (9 nodos)

- **[0807-analisis-sentimiento-feedback.json](workflows/0807-analisis-sentimiento-feedback.json)**
  - **Descripción:** Este flujo automatizado permite recopilar comentarios de clientes en una hoja de Google, analizarlos con IA para detectar el sentimiento y luego integrarlo junto con otros datos del formulario en la misma hoja.
  - **Complejidad:** Media (9 nodos)

- **[0853-fine-tuning-openai-with-drive.json](workflows/0853-fine-tuning-openai-with-drive.json)**
  - **Descripción:** Este flujo automático permite realizar un proceso completo de fine-tuning en modelos de OpenAI usando archivos JSONL alojados en Google Drive.
  - **Complejidad:** Media (9 nodos)

- **[0902-baserow-markdown-sync.json](workflows/0902-baserow-markdown-sync.json)**
  - **Descripción:** Este flujo automático permite sincronizar y actualizar registros en Baserow donde la descripción del video esté en formato Markdown. Primero verifica si hay un solo registro o múltiples, convierte cada descripción a HTML manteniendo la estructura original de datos e inicia sesión mediante un webhook.
  - **Complejidad:** Media (9 nodos)

- **[0953-notion-supabase-vector.json](workflows/0953-notion-supabase-vector.json)**
  - **Descripción:** Este flujo automatiza el almacenamiento de páginas de Notion como documentos vectorizados en un proyecto de Supabase utilizando columnas de vectores y embeddings generados por OpenAI.
  - **Complejidad:** Media (9 nodos)

- **[0979-pipeline-etl-twitter-sentiment.json](workflows/0979-pipeline-etl-twitter-sentiment.json)**
  - **Descripción:** Esta automatización diaria busca tweets con el hashtag #OnThisDay mediante ETL, analiza su sentimiento usando Google NLP y almacena los resultados en tablas de Postgres y MongoDB.
  - **Complejidad:** Media (9 nodos)

- **[1015-modelo_openai_fine_tuning.json](workflows/1015-modelo_openai_fine_tuning.json)**
  - **Descripción:** Este flujo automático permite la creación y uso de modelos personalizados de OpenAI a través del fine-tuning basado en archivos JSONL descargados desde Google Drive.
  - **Complejidad:** Media (9 nodos)

- **[1097-n8n-workflows-guardar.json](workflows/1097-n8n-workflows-guardar.json)**
  - **Descripción:** Este flujo automático permite guardar workflows de n8n en archivos JSON en Google Drive.
  - **Complejidad:** Media (9 nodos)

- **[1119-smart-factory-alert.json](workflows/1119-smart-factory-alert.json)**
  - **Descripción:** Este flujo monitorea sensores de fábrica para detectar temperaturas superiores a 50°C y almacena tanto los datos del sensor como incidentes en CrateDB.
  - **Complejidad:** Media (9 nodos)

- **[1188-n8n-backup-cron.json](workflows/1188-n8n-backup-cron.json)**
  - **Descripción:** Este flujo programa una tarea cada 6 horas para ejecutar un workflow y guardar su resultado como archivo binario en Nextcloud.
  - **Complejidad:** Media (9 nodos)

- **[1229-notion-document-embedding.json](workflows/1229-notion-document-embedding.json)**
  - **Descripción:** Este flujo automatiza el procesamiento de documentos Notion para generar sus embeddings y almacenarlos en Supabase.
  - **Complejidad:** Media (9 nodos)

- **[1498-store-notion_s-pages-as-vector-openai.json](workflows/1498-store-notion_s-pages-as-vector-openai.json)**
  - **Descripción:** Este flujo permite automatización, resumen, generación de contenido, monitoreo utilizando OpenAI/GPT, Notion, Supabase con inteligencia artificial y APIs.
  - **Complejidad:** Media (9 nodos)

- **[2565-ai-screenshot-analysis.json](workflows/2565-ai-screenshot-analysis.json)**
  - **Descripción:** Este flujo automatiza el análisis de capturas de pantalla mediante inteligencia artificial. Primero recoge la URL del sitio web a analizar, luego genera un screenshot utilizando la API de URLbox y finalmente lo procesa con OpenAI para obtener una descripción textual concisa en un solo párrafo.
  - **Complejidad:** Media (9 nodos)

- **[2586-shopify-campaign-sync.json](workflows/2586-shopify-campaign-sync.json)**
  - **Descripción:** Este flujo n8n permite guardar archivos .liquid en el tema de Shopify después de subir imágenes usando GraphQL, optimizando la creación de campañas publicitarias.
  - **Complejidad:** Media (9 nodos)

- **[2588-image-meta-tagging-automation.json](workflows/2588-image-meta-tagging-automation.json)**
  - **Descripción:** Este flujo automático analiza el contenido de imágenes subidas en una carpeta específica de Google Drive y escribe directamente la descripción como etiquetas (tags) en los metadatos XMP del archivo.
  - **Complejidad:** Media (9 nodos)

- **[2612-zammad-roles-excel.json](workflows/2612-zammad-roles-excel.json)**
  - **Descripción:** Este flujo automático permite descargar un archivo Excel desde una URL configurada previamente y actualizar el rol de los usuarios en Zammad a partir de los datos contenidos en él.
  - **Complejidad:** Media (9 nodos)

- **[2618-gemini-image-data-extractor.json](workflows/2618-gemini-image-data-extractor.json)**
  - **Descripción:** Este flujo crea una API para extraer datos de imágenes utilizando Gemini AI, requiere enviar una URL de imagen y un conjunto de instrucciones que definen qué información debe ser extraída.
  - **Complejidad:** Media (9 nodos)

- **[2641-csv-google-sheets-import.json](workflows/2641-csv-google-sheets-import.json)**
  - **Descripción:** Este flujo permite importar múltiples archivos CSV de una carpeta local a Google Sheets, eliminando duplicados y manteniendo solo suscriptores.
  - **Complejidad:** Media (9 nodos)

- **[3051-airtable-markdown-to-html.json](workflows/3051-airtable-markdown-to-html.json)**
  - **Descripción:** Este flujo procesa descripciones en formato markdown de un Airtable y las convierte a HTML. Si hay un solo registro, actualiza esa entrada; si hay múltiples registros, actualiza todas con el HTML convertido.
  - **Complejidad:** Media (9 nodos)

- **[3057-email_summary_dailly.json](workflows/3057-email_summary_dailly.json)**
  - **Descripción:** Este flujo automatiza la creación de resúmenes diarios de correo electrónico. Cada mañana a las 7 AM, recupera los correos electrónicos recibidos en las últimas 24 horas, organiza los datos, utiliza OpenAI para sintetizar el contenido y luego envía un informe estructurado con formato HTML.
  - **Complejidad:** Media (9 nodos)

- **[1436-api-schema-extractor.json](workflows/1436-api-schema-extractor.json)**
  - **Descripción:** Este flujo permite chatbot, web scraping, extracción de datos, generación de contenido utilizando Webhook, Google Sheets, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (8 nodos)

- **[0096-news-hacker.json](workflows/0096-news-hacker.json)**
  - **Descripción:** Este flujo automático recoge títulos y URLs de noticias de Hacker News, las exporta como un archivo en formato CSV o Excel y envía una notificación por correo electrónico.
  - **Complejidad:** Media (8 nodos)

- **[0162-crypto-portfolio-updater.json](workflows/0162-crypto-portfolio-updater.json)**
  - **Descripción:** Este flujo automático actualiza los valores de activos cripto en una base Airtable cada hora con datos actuales desde CoinGecko.
  - **Complejidad:** Media (8 nodos)

- **[0231-line-chatbot-context.json](workflows/0231-line-chatbot-context.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada al utilizar datos del usuario en mensajes personalizados.
  - **Complejidad:** Media (8 nodos)

- **[0272-datos-aleatorios.json](workflows/0272-datos-aleatorios.json)**
  - **Descripción:** Este workflow realiza una solicitud HTTP a un servicio de API para obtener datos y los guarda en Google Sheets.
  - **Complejidad:** Media (8 nodos)

- **[0389-chat-movie-recommendations.json](workflows/0389-chat-movie-recommendations.json)**
  - **Descripción:** Este flujo permite a una IA conversacional interactuar con datos de MongoDB mediante agregaciones, mantener contexto en memoria buffer y registrar preferencias del usuario.
  - **Complejidad:** Media (8 nodos)

- **[0462-n8n-blueprint-backoff.json](workflows/0462-n8n-blueprint-backoff.json)**
  - **Descripción:** Este flujo implementa un mecanismo de backoff exponencial para manejar limitaciones de tasa (rate limiting) en la API de Google Sheets, reintentando una acción con incrementos exponenciales del tiempo entre intentos hasta alcanzar un máximo de 5 reintentos.
  - **Complejidad:** Media (8 nodos)

- **[0478-formulario-google-docs.json](workflows/0478-formulario-google-docs.json)**
  - **Descripción:** Este flujo automático permite al usuario enviar datos a través de un formulario y que estos se utilicen para rellenar texto en un documento de Google Docs utilizando la API.
  - **Complejidad:** Media (8 nodos)

- **[0920-squarespace-orders-to-sheets.json](workflows/0920-squarespace-orders-to-sheets.json)**
  - **Descripción:** Este flujo automático recoge todos los pedidos de una tienda en Squarespace y actualiza automáticamente un archivo Google Sheets.
  - **Complejidad:** Media (8 nodos)

- **[1053-movie-recommendations-agent.json](workflows/1053-movie-recommendations-agent.json)**
  - **Descripción:** Este flujo permite a un asistente de chat obtener recomendaciones de películas mediante el uso de la API de OpenAI y consulta en tiempo real a una base de datos MongoDB.
  - **Complejidad:** Media (8 nodos)

- **[1109-transcripcion-drive-sheets.json](workflows/1109-transcripcion-drive-sheets.json)**
  - **Descripción:** Este flujo automatizado transcribe archivos de voz subidos en Google Drive y guarda el resultado en una hoja de cálculo.
  - **Complejidad:** Media (8 nodos)

- **[1169-gmail-file-monitor.json](workflows/1169-gmail-file-monitor.json)**
  - **Descripción:** Este flujo automático monitoriza correos electrónicos en Gmail y clasifica los archivos adjuntos por tamaño para su posterior manejo, filtrando grandes archivos (mayor a 300MB) o archivos intermedios (entre 10-300MB).
  - **Complejidad:** Media (8 nodos)

- **[1213-youtube-sync.json](workflows/1213-youtube-sync.json)**
  - **Descripción:** Este flujo sincroniza las URLs de videos de YouTube desde canales especificados en Google Sheets hacia otra hoja utilizando la API de YouTube.
  - **Complejidad:** Media (8 nodos)

- **[1217-luma-ai-webhook-process.json](workflows/1217-luma-ai-webhook-process.json)**
  - **Descripción:** Este flujo automatizado recibe una respuesta web de Luma AI a través de un webhook, verifica que contenga un video no vacío y guarda información sobre el mismo (URL del vídeo, miniatura) en Airtable.
  - **Complejidad:** Media (8 nodos)

- **[1233-audio-transcription-process.json](workflows/1233-audio-transcription-process.json)**
  - **Descripción:** Este flujo automático descarga archivos de audio nuevos en Google Drive y los envía para transcribirlos e interpretar sentimientos mediante OpenAI, generando un resumen estructurado que incluye título, contenido principal y análisis.
  - **Complejidad:** Media (8 nodos)

- **[1241-google-drive-sync.json](workflows/1241-google-drive-sync.json)**
  - **Descripción:** Este flujo automático sincroniza los archivos nuevos de una carpeta específica de Google Drive, comparte sus detalles con un destinatario por correo y registra la metadata completa en Airtable para su seguimiento.
  - **Complejidad:** Media (8 nodos)

- **[1482-mongodb-ai-agent-intelligent-movie-recommendations.json](workflows/1482-mongodb-ai-agent-intelligent-movie-recommendations.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Webhook, MongoDB con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (8 nodos)

- **[2694-dominio_icypeas.json](workflows/2694-dominio_icypeas.json)**
  - **Descripción:** Este flujo automatiza la ejecución de un análisis大批量 de dominios utilizando Icypeas. Lee datos desde una hoja de cálculo de Google, autentica en la cuenta de Icypeas y envía una solicitud POST para realizar las búsquedas masivas.
  - **Complejidad:** Media (8 nodos)

- **[2815-luma-video-generator.json](workflows/2815-luma-video-generator.json)**
  - **Descripción:** Este flujo crea videos personalizados utilizando la API de Luma AI Dream Machine. Genera un video basado en un prompt definido globalmente con diferentes opciones de aspecto, duración y movimiento aleatorio. Registra los datos del video en Airtable.
  - **Complejidad:** Media (8 nodos)

- **[2927-convert-squarespace-to-shopify.json](workflows/2927-convert-squarespace-to-shopify.json)**
  - **Descripción:** Este flujo automático convierte perfiles de Squarespace a clientes en Shopify utilizando Google Sheets. Extrae datos desde una hoja de cálculo de Squarespace, procesa y actualiza información en Shopify.
  - **Complejidad:** Media (8 nodos)

- **[2982-amazon-best-seller-electronic-extractor.json](workflows/2982-amazon-best-seller-electronic-extractor.json)**
  - **Descripción:** Este flujo extrae información de los mejores vendedores de Amazon en la categoría de electrónica utilizando Bright Data y Google Gemini para una extracción estructurada de datos.
  - **Complejidad:** Media (8 nodos)

- **[3184-audio-transcription-notion.json](workflows/3184-audio-transcription-notion.json)**
  - **Descripción:** Este flujo automatiza la transcripción de archivos de audio desde Google Drive, utiliza GPT-4 para resumir el contenido y almacena el resumen en Notion.
  - **Complejidad:** Media (8 nodos)

- **[0014-monitor-verstappen-tweets.json](workflows/0014-monitor-verstappen-tweets.json)**
  - **Descripción:** Este flujo busca los últimos tweets públicos y privados con la palabra clave 'Verstappen', luego compara esos resultados con una lista existente en Airtable para identificar y guardar solo las nuevas entradas, eliminando duplicados.
  - **Complejidad:** Media (7 nodos)

- **[0131-limpia_pacotes_telegram.json](workflows/0131-limpia_pacotes_telegram.json)**
  - **Descripción:** Este flujo automático ejecuta consultas SQL diarias para limpiar pacotes de transporte en la base de datos 'PPM' y luego actualiza registros antiguos a 'DELETE'. Después, envía un mensaje predefinido al chatId especificado.
  - **Complejidad:** Media (7 nodos)

- **[0392-proteccion-pdf-google.json](workflows/0392-proteccion-pdf-google.json)**
  - **Descripción:** Este flujo descarga automáticamente un PDF demo y lo escribe en disco o sube a Google Drive.
  - **Complejidad:** Media (7 nodos)

- **[0428-libros-historicos-extractor.json](workflows/0428-libros-historicos-extractor.json)**
  - **Descripción:** Este flujo extrae información sobre libros históricos de Toscrape usando Jina.ai y se utiliza el modelo OpenAI ChatGPT para analizar los datos, guardando finalmente los resultados en una hoja de Google.
  - **Complejidad:** Media (7 nodos)

- **[0429-webflow-to-gsheets.json](workflows/0429-webflow-to-gsheets.json)**
  - **Descripción:** Este flujo automatizado recoge datos de envíos de formulario en Webflow y los añade automáticamente como nuevas filas a una hoja de cálculo Google.
  - **Complejidad:** Media (7 nodos)

- **[0452-wordpress-posts-csv.json](workflows/0452-wordpress-posts-csv.json)**
  - **Descripción:** Este flujo automático permite obtener posts publicados de WordPress en formato JSON y convertirlos posteriormente en archivo CSV para subirlo automáticamente al Google Drive.
  - **Complejidad:** Media (7 nodos)

- **[0518-google-drive-pdf-to-html.json](workflows/0518-google-drive-pdf-to-html.json)**
  - **Descripción:** Este flujo automático convierte archivos PDF nuevos guardados en Google Drive a HTML y los guarda automáticamente en la misma carpeta.
  - **Complejidad:** Media (7 nodos)

- **[0658-demo-n8n-flujo.json](workflows/0658-demo-n8n-flujo.json)**
  - **Descripción:** Este flujo demuestra cómo n8n puede usar nodos 'function' para generar datos y nodos 'switch' para crear rutas de respuesta basadas en comparaciones.
  - **Complejidad:** Media (7 nodos)

- **[0725-file-list-processing.json](workflows/0725-file-list-processing.json)**
  - **Descripción:** Este flujo automático se activa manualmente, lee contenido desde el archivo '/home/n8n/filelist.txt', lo divide en líneas usando el carácter de nueva línea y almacena cada elemento en un array llamado 'arrData', luego utiliza la variable $runIndex para ejecutar comandos que imprimen los nombres de archivos basados en este array.
  - **Complejidad:** Media (7 nodos)

- **[0811-jina-scraper-book-extractor.json](workflows/0811-jina-scraper-book-extractor.json)**
  - **Descripción:** Este flujo utiliza Jina.ai para acceder y extraer datos de libros desde webscraping, los procesa con OpenAI y guarda el resultado en Google Sheets.
  - **Complejidad:** Media (7 nodos)

- **[0827-workflow-retriever-qa.json](workflows/0827-workflow-retriever-qa.json)**
  - **Descripción:** Este flujo automático permite hacer consultas sobre cualquier fuente de datos mediante la recuperación de workflows existentes.
  - **Complejidad:** Media (7 nodos)

- **[0993-airtable-telli-ia.json](workflows/0993-airtable-telli-ia.json)**
  - **Descripción:** Este flujo automático conecta Airtable con telli, permitiendo añadir contactos automáticamente desde la base y programar llamadas de voz con IA.
  - **Complejidad:** Media (7 nodos)

- **[1019-obsidian-airtable-agent.json](workflows/1019-obsidian-airtable-agent.json)**
  - **Descripción:** Este flujo permite obtener datos de Airtable y generar notas en Obsidian utilizando un modelo de chat de OpenAI.
  - **Complejidad:** Media (7 nodos)

- **[1037-gsc-weekly-report.json](workflows/1037-gsc-weekly-report.json)**
  - **Descripción:** Este flujo automático ejecuta un informe de SEO semanal basado en datos del Google Search Console y lo envía por correo electrónico.
  - **Complejidad:** Media (7 nodos)

- **[1056-test_pdf.json](workflows/1056-test_pdf.json)**
  - **Descripción:** Este flujo permite combinar múltiples PDFs en un solo documento y escribirlo en el sistema de archivos.
  - **Complejidad:** Media (7 nodos)

- **[1173-retell-webhook-response.json](workflows/1173-retell-webhook-response.json)**
  - **Descripción:** Este flujo automático utiliza una webhook para recibir datos de llamadas entrantes en Retell y buscar al usuario correspondiente en un archivo Google Sheets, respondiendo con los datos necesarios.
  - **Complejidad:** Media (7 nodos)

- **[1184-google-drive-image-tagging.json](workflows/1184-google-drive-image-tagging.json)**
  - **Descripción:** Este flujo n8n analiza automáticamente el contenido de imágenes en Google Drive usando una API AI y escribe los resultados como etiquetas (Subject/Keywords) en la metadata EXIF.
  - **Complejidad:** Media (7 nodos)

- **[1189-sheets-automation.json](workflows/1189-sheets-automation.json)**
  - **Descripción:** Este flujo automatizado permite leer datos de una hoja de Google Sheets utilizando búsqueda, luego modificar el valor de 'Rent' en los registros encontrados y actualizarlos.
  - **Complejidad:** Media (7 nodos)

- **[1211-covid_automated_import.json](workflows/1211-covid_automated_import.json)**
  - **Descripción:** Este flujo automatiza la importación puntual de datos COVID-19 específicos (DACH: Alemania, Austria, Suiza) del año 2023 desde una fuente externa a Google Sheets.
  - **Complejidad:** Media (7 nodos)

- **[1220-ai-cv-screening-process.json](workflows/1220-ai-cv-screening-process.json)**
  - **Descripción:** Este flujo automático permite al formulario de solicitud capturar información sobre candidatos para la posición de Software Engineer, procesar el CV subido y enviar un análisis detallado con IA a los usuarios. Luego envía confirmaciones por correo al candidato y notifica a HR sobre nuevas solicitudes. Finalmente, guarda todos estos datos en una hoja de Google Sheets.
  - **Complejidad:** Media (7 nodos)

- **[1230-squarespace-sync.json](workflows/1230-squarespace-sync.json)**
  - **Descripción:** Automatiza la extracción y actualización en tiempo real del contenido de blogs y eventos de Squarespace a Google Sheets.
  - **Complejidad:** Media (7 nodos)

- **[1428-ai-powered-web-scraping-with-google-sheets-openai.json](workflows/1428-ai-powered-web-scraping-with-google-sheets-openai.json)**
  - **Descripción:** Este flujo permite chatbot, web scraping, extracción de datos utilizando OpenAI/GPT, Google Sheets, YouTube con inteligencia artificial y APIs.
  - **Complejidad:** Media (7 nodos)

- **[1471-get-airtable-data-via-ai-and-obsidian-notes.json](workflows/1471-get-airtable-data-via-ai-and-obsidian-notes.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Webhook, Airtable con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (7 nodos)

- **[2554-x-influencers-list.json](workflows/2554-x-influencers-list.json)**
  - **Descripción:** Este flujo automatizado permite buscar influencers en X utilizando Airtop, extraer sus datos de forma estructurada, deduplicar los resultados e incorporarlos a un documento de Google mediante la hoja de cálculo.
  - **Complejidad:** Media (7 nodos)

- **[2583-prospectlens_company_research.json](workflows/2583-prospectlens_company_research.json)**
  - **Descripción:** Este flujo automático utiliza la API de ProspectLens para obtener datos de empresas y actualizar una hoja de cálculo en Google Sheets manteniendo un registro del momento de procesamiento.
  - **Complejidad:** Media (7 nodos)

- **[2658-agente-contact-ai.json](workflows/2658-agente-contact-ai.json)**
  - **Descripción:** Este flujo permite al agente de IA interactuar con Airtable usando búsqueda o actualización de contactos.
  - **Complejidad:** Media (7 nodos)

- **[2713-chat-agent-postgres.json](workflows/2713-chat-agent-postgres.json)**
  - **Descripción:** Este flujo utiliza un agente de lenguaje para procesar mensajes en chat, empleando memoria simple y una base de datos PostgreSQL para respaldar consultas SQL generadas por el sistema.
  - **Complejidad:** Media (7 nodos)

- **[2737-stripe-payment-link.json](workflows/2737-stripe-payment-link.json)**
  - **Descripción:** Este flujo crea un producto en Stripe y genera un enlace de pago basado en los datos del formulario enviado. Configura la moneda y el precio, luego crea el producto y finalmente redirige al usuario.
  - **Complejidad:** Media (7 nodos)

- **[0969-ats-ai-assessment.json](workflows/0969-ats-ai-assessment.json)**
  - **Descripción:** Este flujo automático procesa solicitudes de candidatos extraídos de formularios, analiza sus datos personales y calificaciones mediante modelos de Google Gemini, asigna experiencias por funciones usando un extractor LLM, evalúa su alineación con descripciones de roles específicos en Notion ATS, genera evaluaciones estructuradas y actualiza registros tanto en Notion como en Google Sheets.
  - **Complejidad:** Media (6 nodos)

- **[1242-ultimate-scraper-workflow.json](workflows/1242-ultimate-scraper-workflow.json)**
  - **Descripción:** Este flujo automático permite extraer información de cualquier página web, ya sea pública o privada, utilizando técnicas avanzadas como la automatización del navegador.Selenium y análisis con modelos de lenguaje de OpenAI. Ideal para proyectos que requieren recopilar datos detras de WAFs.
  - **Complejidad:** Media (6 nodos)

- **[2555-workflow-docs.json](workflows/2555-workflow-docs.json)**
  - **Descripción:** Este flujo automático permite a n8n generar y mantener documentación de workflows mediante Docsify, creando archivos Markdown basados en los datos del workflow.
  - **Complejidad:** Media (6 nodos)

- **[2998-notion-clockify-sync.json](workflows/2998-notion-clockify-sync.json)**
  - **Descripción:** Este flujo sincroniza datos entre Notion y Clockify, manejando clientes, proyectos y tareas. Actualiza estados y IDs de manera bidireccional.
  - **Complejidad:** Media (6 nodos)

- **[3045-selenium_scraping_automatizado.json](workflows/3045-selenium_scraping_automatizado.json)**
  - **Descripción:** Este flujo automatiza la extracción de datos web utilizando Selenium y OpenAI. Busca URLs relevantes en una página dada, extrae información con IA, maneja cookies y sesiones para logueo opcional, toma capturas de pantalla y detecta posibles bloqueos por WAF.
  - **Complejidad:** Media (6 nodos)

- **[0095-sequential-http-post.json](workflows/0095-sequential-http-post.json)**
  - **Descripción:** Este flujo permite iniciar manualmente la ejecución, obtener todos los datos de clientes desde un almacenamiento, dividirlos en lotes individuales y enviar cada uno mediante una solicitud HTTP POST a la API de JSONPlaceholder.
  - **Complejidad:** Media (6 nodos)

- **[0185-datos-binarios-descomprimidos.json](workflows/0185-datos-binarios-descomprimidos.json)**
  - **Descripción:** Este flujo automático descarga un archivo ZIP que contiene datos binarios y los divide en elementos individuales, cada uno con una única secuencia de datos binarios bajo la clave 'data'.
  - **Complejidad:** Media (6 nodos)

- **[0194-customer-data-processing.json](workflows/0194-customer-data-processing.json)**
  - **Descripción:** Este flujo de trabajo utiliza un desencadenador manual para obtener datos de clientes desde el 'Customer Datastore' y luego los edita en una variable mediante el nodo Set.
  - **Complejidad:** Media (6 nodos)

- **[0196-airtable-insert-update.json](workflows/0196-airtable-insert-update.json)**
  - **Descripción:** Este flujo automático inserta un registro inicial en la tabla Table 1 de Airtable, luego lista registros filtrados por el campo 'Name' igual a 'n8n', y finalmente actualiza el primer registro encontrado con los valores definidos en el paso Set.
  - **Complejidad:** Media (6 nodos)

- **[0197-snowflake-table-management.json](workflows/0197-snowflake-table-management.json)**
  - **Descripción:** Este flujo automático permite crear una tabla en Snowflake y realizar inserciones e actualizaciones de datos utilizando operaciones definidas previamente.
  - **Complejidad:** Media (6 nodos)

- **[0200-users-api-spreadsheet.json](workflows/0200-users-api-spreadsheet.json)**
  - **Descripción:** Este flujo utiliza la API de randomuser.me para obtener datos y luego los extrae en formato JSON. Posteriormente, actualiza una hoja de cálculo Google con estos valores y también genera un archivo CSV.
  - **Complejidad:** Media (6 nodos)

- **[0210-google-sheets-data-preparation.json](workflows/0210-google-sheets-data-preparation.json)**
  - **Descripción:** Este flujo procesa datos provenientes del nodo 'Customer Datastore' para prepararlos antes de realizar una operación UPSERT en Google Sheets. El formato de los campos se ajusta: el campo 'name' del input se renombra a 'Full name', y se añade un nuevo campo 'Created time' con la fecha actual.
  - **Complejidad:** Media (6 nodos)

- **[0237-firestore-document-management.json](workflows/0237-firestore-document-management.json)**
  - **Descripción:** Este flujo automatizado permite crear y actualizar documentos en Google Cloud Firestore.
  - **Complejidad:** Media (6 nodos)

- **[0238-nextcloud-spreadsheet.json](workflows/0238-nextcloud-spreadsheet.json)**
  - **Descripción:** Este flujo automático permite descargar un archivo de Excel desde NextCloud, procesarlo y subirlo nuevamente a la misma ubicación después de integrar datos.
  - **Complejidad:** Media (6 nodos)

- **[0267-imagenes-line-merge.json](workflows/0267-imagenes-line-merge.json)**
  - **Descripción:** Este flujo automático descarga múltiples imágenes de ejemplo mediante solicitudes HTTP y las fusiona en un único resultado que contiene todos los datos binarios concatenados.
  - **Complejidad:** Media (6 nodos)

- **[0287-google-drive-summarizer.json](workflows/0287-google-drive-summarizer.json)**
  - **Descripción:** Este flujo permite descargar y procesar un archivo de Google Drive para generar resúmenes utilizando cadenas de sumarización.
  - **Complejidad:** Media (6 nodos)

- **[0361-workflow-error-config.json](workflows/0361-workflow-error-config.json)**
  - **Descripción:** Este flujo actualiza la configuración de manejo de errores en workflows mediante Postgres y utiliza variables predefinidas para excluir ciertos casos.
  - **Complejidad:** Media (6 nodos)

- **[0381-airtable-seo-metatags.json](workflows/0381-airtable-seo-metatags.json)**
  - **Descripción:** Este flujo automatizado busca en Airtable los registros que no tienen URL ni título/metadata de descripción definidos y actualiza esos campos con valores reales extraídos desde el contenido web.
  - **Complejidad:** Media (6 nodos)

- **[0387-convertir-docx-a-pdf.json](workflows/0387-convertir-docx-a-pdf.json)**
  - **Descripción:** Este flujo automático permite convertir archivos DOCX enlazados de una URL remota al formato PDF utilizando ConvertAPI.
  - **Complejidad:** Media (6 nodos)

- **[0406-zigbee-backups-schedule.json](workflows/0406-zigbee-backups-schedule.json)**
  - **Descripción:** Este flujo automático realiza copias de seguridad semanalmente (todos los lunes a las 2:45 am) mediante mensajes MQTT, descodifica la respuesta JSON para obtener el archivo ZIP y lo sube automáticamente a un servidor SFTP.
  - **Complejidad:** Media (6 nodos)

- **[0477-n8n-workflow-backup-schedule.json](workflows/0477-n8n-workflow-backup-schedule.json)**
  - **Descripción:** Este flujo automatizado realiza copias de seguridad diarias a las 1:30 AM de todos los workflows de n8n en un archivo JSON y lo guarda en una carpeta especificada de Google Drive.
  - **Complejidad:** Media (6 nodos)

- **[0483-mailchimp-google-sheets-newsletter.json](workflows/0483-mailchimp-google-sheets-newsletter.json)**
  - **Descripción:** Este flujo automatizado procesa nuevas suscripciones a la newsletter en Google Sheets y las añade como contactos activos en Mailchimp.
  - **Complejidad:** Media (6 nodos)

- **[0545-google-page-entity-extraction.json](workflows/0545-google-page-entity-extraction.json)**
  - **Descripción:** Este flujo analiza el contenido HTML de cualquier página web para extraer datos estructurados sobre entidades reconocidas por Google.
  - **Complejidad:** Media (6 nodos)

- **[0652-product-feedback-workflow.json](workflows/0652-product-feedback-workflow.json)**
  - **Descripción:** Este flujo automatizado recoge comentarios y valoraciones sobre un producto a través de Typeform, los almacena en Airtable y, cuando el puntaje es igual a 7, crea una tarjeta en Trello con la información proporcionada.
  - **Complejidad:** Media (6 nodos)

- **[0663-iot-mqtt-influxdb-monitoring.json](workflows/0663-iot-mqtt-influxdb-monitoring.json)**
  - **Descripción:** Este flujo automatizado recibe datos de sensores IoT remotos a través de un tema MQTT 'wokwi-weather', procesa y validan las lecturas de temperatura y humedad, luego escribe estos valores en formato JSON en una base de datos InfluxDB.
  - **Complejidad:** Media (6 nodos)

- **[0694-orbit-import-from-sheets.json](workflows/0694-orbit-import-from-sheets.json)**
  - **Descripción:** Este flujo automatizado importa datos de miembros y actividades desde Google Sheets a la plataforma Orbit utilizando credenciales OAuth2.
  - **Complejidad:** Media (6 nodos)

- **[0723-gmail-expenses-mindee.json](workflows/0723-gmail-expenses-mindee.json)**
  - **Descripción:** Este flujo verifica correos electrónicos en Gmail que contienen palabras clave como 'expenses' o 'recibo', extrae datos de facturas usando la API Mindee y agrega automáticamente los detalles a una hoja de Google.
  - **Complejidad:** Media (6 nodos)

- **[1110-nicepng-text-analysis.json](workflows/1110-nicepng-text-analysis.json)**
  - **Descripción:** Este flujo analiza un archivo PNG de motivational quotes con AWS Rekognition para detectar texto, luego extrae el nombre y enlace de la imagen a través de una solicitud HTTP e incorpora todo junto los textos detectados (convertidos a minúsculas) en Google Sheets mediante OAuth2.
  - **Complejidad:** Media (6 nodos)

- **[1142-s3-lista-archivos.json](workflows/1142-s3-lista-archivos.json)**
  - **Descripción:** Este flujo automatizado permite descargar todos los archivos de una carpeta específica de Amazon S3 y comprimirlos en un archivo ZIP para facilitar su descarga o procesamiento posterior.
  - **Complejidad:** Media (6 nodos)

- **[0717-rag-chatbot-docs.json](workflows/0717-rag-chatbot-docs.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de IA mantener una conversación contextualizada usando documentos almacenados en Google Drive y Qdrant. Extrae metadatos relevantes como temas principales, puntos dolorosos e información clave para mejorar la búsqueda semántica y las respuestas del asistente.
  - **Complejidad:** Media (5 nodos)

- **[0808-airtable-dynamic-prompts-llm.json](workflows/0808-airtable-dynamic-prompts-llm.json)**
  - **Descripción:** Este flujo automático permite al usuario generar y mantener un esquema dinámico de campos en una tabla de Airtable mediante webhooks, optimizando la actualización con LLM solo cuando son necesarios.
  - **Complejidad:** Media (5 nodos)

- **[0941-techradar-ai-agent.json](workflows/0941-techradar-ai-agent.json)**
  - **Descripción:** Este flujo automático maneja la tecnología corporativa para tres empresas, manteniendo actualizados los registros en base de datos SQL y almacenamiento vectorial Pinecone. Se ejecuta cada mes un cron job que sincroniza los datos desde Google Sheets eliminando registros antiguos.
  - **Complejidad:** Media (5 nodos)

- **[1258-pdf-to-vector-store.json](workflows/1258-pdf-to-vector-store.json)**
  - **Descripción:** Convierte un PDF en datos vectoriales para búsquedas posteriores.
  - **Complejidad:** Media (5 nodos)

- **[1276-airtable-pdf-llm-update.json](workflows/1276-airtable-pdf-llm-update.json)**
  - **Descripción:** Actualiza registros de Airtable con datos extraídos de PDFs mediante LLM.
  - **Complejidad:** Media (5 nodos)

- **[2575-wordpress-ai-chatbot.json](workflows/2575-wordpress-ai-chatbot.json)**
  - **Descripción:** Este flujo automático permite crear y mantener embeddings de contenido de WordPress en Supabase, utilizando modelos OpenAI para responder preguntas con información contextualizada.
  - **Complejidad:** Media (5 nodos)

- **[2704-switchy-url-shortener.json](workflows/2704-switchy-url-shortener.json)**
  - **Descripción:** Este flujo procesa URLs para generar y acortarlas utilizando Switchy.io. Analiza metadatos, verifica seguridad con Norton y Bitdefender, y maneja diferentes modos de imagen OpenGraph.
  - **Complejidad:** Media (5 nodos)

- **[3041-online-marketing-report.json](workflows/3041-online-marketing-report.json)**
  - **Descripción:** Este flujo automático genera un informe semanal de marketing digital que recopila y analiza datos de Google Analytics, Google Ads y Meta Ads. Utiliza sub-flujos para obtener métricas actuales y del año pasado, procesa la información con OpenAI y envía el reporte por correo electrónico.
  - **Complejidad:** Media (5 nodos)

- **[3090-app-wordpress-genai.json](workflows/3090-app-wordpress-genai.json)**
  - **Descripción:** Este flujo implementa una aplicación que utiliza tecnologías de RAG (Retrieval-Augmented Generation) y GenAI para interactuar con contenido de WordPress. Extrae embeddings de texto, gestiona documentos en Supabase y mantiene memoria del chat usando PostgreSQL.
  - **Complejidad:** Media (5 nodos)

- **[0018-entrevistas-y-participantes.json](workflows/0018-entrevistas-y-participantes.json)**
  - **Descripción:** Este flujo procesa dos conjuntos de datos separados que contienen información sobre entrevistas y sus participantes, convirtiendo cada entrada individual en un objeto independiente para luego fusionarlos basándose en claves específicas.
  - **Complejidad:** Media (5 nodos)

- **[0142-xml-to-json-dropbox.json](workflows/0142-xml-to-json-dropbox.json)**
  - **Descripción:** Este flujo toma datos XML desde una URL, los convierte a formato JSON utilizando el nodo 'To JSON', luego actualiza el título del mensaje con el parámetro 'Change title' y finalmente sube el contenido JSON al Dropbox usando la ruta especificada.
  - **Complejidad:** Media (5 nodos)

- **[0165-hashtag-tweet-generator.json](workflows/0165-hashtag-tweet-generator.json)**
  - **Descripción:** Este flujo selecciona aleatoriamente un hashtag de una lista predefinida, genera un tweet utilizando la API de OpenAI y lo guarda en una tabla de Airtable.
  - **Complejidad:** Media (5 nodos)

- **[0174-adobesign-webhook-data.json](workflows/0174-adobesign-webhook-data.json)**
  - **Descripción:** Este flujo automatizado configura una respuesta webhook que incluye la variable clientID y extrae datos específicos del cuerpo JSON sobre acuerdos y participantes.
  - **Complejidad:** Media (5 nodos)

- **[0209-google-search-url-generator.json](workflows/0209-google-search-url-generator.json)**
  - **Descripción:** Este flujo utiliza el nodo Webhook para recibir datos de entrada, luego crea una URL concatenando esos valores (primera y última letra) para generar una búsqueda en Google, y finalmente responde al webhook mostrando la URL generada.
  - **Complejidad:** Media (5 nodos)

- **[0219-company-data-airtable.json](workflows/0219-company-data-airtable.json)**
  - **Descripción:** Este flujo extrae el logo, icon y datos de una empresa usando Brandfetch, y los almacena automáticamente en una tabla de Airtable.
  - **Complejidad:** Media (5 nodos)

- **[0259-mysql-export-spreadsheet.json](workflows/0259-mysql-export-spreadsheet.json)**
  - **Descripción:** Este flujo automatiza la descarga de datos de una tabla MySQL específica en formato Excel, permitiendo así almacenar el contenido del catálogo.
  - **Complejidad:** Media (5 nodos)

- **[0292-snowflake-csv-insert.json](workflows/0292-snowflake-csv-insert.json)**
  - **Descripción:** Este flujo carga datos desde un archivo CSV alojado en Azure Blob Storage, los procesa y luego inserta las columnas especificadas en la tabla 'users' de Snowflake.
  - **Complejidad:** Media (5 nodos)

- **[0320-dingtalk-tfs-automation.json](workflows/0320-dingtalk-tfs-automation.json)**
  - **Descripción:** Este flujo automatizado envía una notificación por DingTalk cuando se crea un nuevo Pull Request en Azure DevOps, utilizando mapas de base de datos MySQL para traducir cuentas de usuario.
  - **Complejidad:** Media (5 nodos)

- **[0385-convertapi-docx2pdf.json](workflows/0385-convertapi-docx2pdf.json)**
  - **Descripción:** Este flujo automático descarga un archivo DOCX desde una URL y lo convierte a PDF usando las credenciales de ConvertAPI para luego escribirlo en el sistema de archivos.
  - **Complejidad:** Media (5 nodos)

- **[0388-scrappey-test-schedule.json](workflows/0388-scrappey-test-schedule.json)**
  - **Descripción:** Este flujo automatizado programa un proceso de prueba cada cierto tiempo para extraer datos mediante la API de Scrappey.
  - **Complejidad:** Media (5 nodos)

- **[0390-convertapi-xlsx-to-pdf-test.json](workflows/0390-convertapi-xlsx-to-pdf-test.json)**
  - **Descripción:** Este flujo automático permite probar la conversión de archivos XLSX a PDF utilizando una API pública.
  - **Complejidad:** Media (5 nodos)

- **[0502-chart-upload.json](workflows/0502-chart-upload.json)**
  - **Descripción:** Este flujo crea dinámicamente un gráfico de línea a partir de datos JSON y lo sube al Google Drive.
  - **Complejidad:** Media (5 nodos)

- **[0524-mattermost-instagram-stats.json](workflows/0524-mattermost-instagram-stats.json)**
  - **Descripción:** Este flujo automático verifica las estadísticas de un perfil Instagram (como seguidores y posts) cada día a las 8:00 AM y envía los datos actualizados en un mensaje formateado con fecha y hora actuales.
  - **Complejidad:** Media (5 nodos)

- **[0537-shopify-odoo-product-sync.json](workflows/0537-shopify-odoo-product-sync.json)**
  - **Descripción:** Este flujo sincroniza automáticamente productos nuevos de Shopify con Odoo. Se activa cuando se crea un producto en Shopify (evento 'products/create') y busca si ya existe en Odoo mediante el código por defecto. Si no existe, lo crea; si ya existe, verifica los datos del producto para realizar una actualización.
  - **Complejidad:** Media (5 nodos)

- **[0598-expense-receipt-automation.json](workflows/0598-expense-receipt-automation.json)**
  - **Descripción:** Este flujo automático recoge recibos a través de Typeform, extrae información relevante usando Mindee y almacena los datos en Airtable.
  - **Complejidad:** Media (5 nodos)

- **[0612-workflow-n8n-581.json](workflows/0612-workflow-n8n-581.json)**
  - **Descripción:** Este flujo inicia con un trigger manual, procesa datos a través de una función que devuelve dos objetos (con IDs 0 y 1), y luego utiliza un nodo condicional para evaluar si el valor 'value1' coincide con los resultados esperados.
  - **Complejidad:** Media (5 nodos)

- **[0639-dropbox-http-image.json](workflows/0639-dropbox-http-image.json)**
  - **Descripción:** Este flujo n8n permite la interacción con Dropbox mediante una solicitud HTTP, primero listando archivos de un directorio y luego subiendo un archivo específico.
  - **Complejidad:** Media (5 nodos)

- **[0641-nextcloud-http-image-upload.json](workflows/0641-nextcloud-http-image-upload.json)**
  - **Descripción:** Este flujo permite descargar una imagen desde un servidor HTTP y luego subirla a la carpeta 'n8n' en NextCloud, así como guardarla directamente con el nombre especificado.
  - **Complejidad:** Media (5 nodos)

- **[0722-compression-to-dropbox.json](workflows/0722-compression-to-dropbox.json)**
  - **Descripción:** Este flujo automatizado descarga dos imágenes de URLs HTTP, las comprime en un archivo ZIP y luego sube el resultado a Dropbox.
  - **Complejidad:** Media (5 nodos)

- **[0857-calendar-event-automation.json](workflows/0857-calendar-event-automation.json)**
  - **Descripción:** Este flujo automático crea eventos en Google Calendar a partir de datos insertados en una hoja de cálculo Google Sheets.
  - **Complejidad:** Media (5 nodos)

- **[0963-copiar-documentos-escaneados-json.json](workflows/0963-copiar-documentos-escaneados-json.json)**
  - **Descripción:** Este flujo automático copia documentos escaneados de un servidor vía HTTP a la cuenta de Nextcloud.
  - **Complejidad:** Media (5 nodos)

- **[0967-comparador-sql.json](workflows/0967-comparador-sql.json)**
  - **Descripción:** Este flujo compara dos conjuntos de datos SQL basados en el número de cliente y año, utilizando una opción para manejar múltiples coincidencias.
  - **Complejidad:** Media (5 nodos)

- **[1049-pdf-to-text-converter.json](workflows/1049-pdf-to-text-converter.json)**
  - **Descripción:** Convierte archivos PDF en texto utilizando un plugin personalizado y una entrada HTML.
  - **Complejidad:** Media (5 nodos)

- **[1066-openai-tweet-generator.json](workflows/1066-openai-tweet-generator.json)**
  - **Descripción:** Este flujo utiliza OpenAI para generar tweets basados en hashtags seleccionados aleatoriamente y luego los guarda automáticamente en una base de Airtable.
  - **Complejidad:** Media (5 nodos)

- **[1072-openweathermap-airtable-weather.json](workflows/1072-openweathermap-airtable-weather.json)**
  - **Descripción:** Este flujo automático obtiene datos meteorológicos diarios de la API de OpenWeatherMap y los almacena en una tabla de Airtable.
  - **Complejidad:** Media (5 nodos)

- **[1088-zip-multiple-files.json](workflows/1088-zip-multiple-files.json)**
  - **Descripción:** Este flujo comprime múltiples archivos en un archivo ZIP dinámico con n8n.
  - **Complejidad:** Media (5 nodos)

- **[1155-sharepoint-token-fetch.json](workflows/1155-sharepoint-token-fetch.json)**
  - **Descripción:** Este flujo automático obtiene tokens de autenticación para acceder a una lista SharePoint y permite ejecutar operaciones programadas con ellos.
  - **Complejidad:** Media (5 nodos)

- **[1253-notion-clickup-sync.json](workflows/1253-notion-clickup-sync.json)**
  - **Descripción:** Este flujo sincroniza tareas entre Notion y ClickUp. Cuando una página de la base de datos en Notion se actualiza, el estado de la tarea correspondiente en ClickUp es actualizado, y viceversa.
  - **Complejidad:** Media (5 nodos)

- **[1465-extract-license-plate-number-from.json](workflows/1465-extract-license-plate-number-from.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (5 nodos)

- **[1483-openai-powered-tweet-generator.json](workflows/1483-openai-powered-tweet-generator.json)**
  - **Descripción:** Este flujo permite generación de contenido utilizando OpenAI/GPT, Airtable, Twitter/X con inteligencia artificial y APIs.
  - **Complejidad:** Media (5 nodos)

- **[2610-icp_linkedin_scoring.json](workflows/2610-icp_linkedin_scoring.json)**
  - **Descripción:** Este flujo n8n calcula automáticamente la puntuación de Ideal Customer Profile (ICP) para empresas basada en sus páginas de LinkedIn, utilizando Airtop para el análisis y Google Sheets para almacenar e integrar los datos.
  - **Complejidad:** Media (5 nodos)

- **[2833-icp_scoring_workflow.json](workflows/2833-icp_scoring_workflow.json)**
  - **Descripción:** Este flujo automatiza la puntuación de ICP recolectando y procesando datos de perfiles de LinkedIn. Primero, utiliza Google Sheets para obtener información personal, luego extrae detalles del perfil de LinkedIn y calcula una puntuación ICP basada en intereses en AI, nivel técnico y seniority.
  - **Complejidad:** Media (5 nodos)

- **[3031-google-drive-summarizer.json](workflows/3031-google-drive-summarizer.json)**
  - **Descripción:** Este flujo descarga un archivo de Google Drive, lo sumaiza utilizando Mistral AI y envía el resumen por correo electrónico.
  - **Complejidad:** Media (5 nodos)

- **[0809-baserow-pdf-extractor.json](workflows/0809-baserow-pdf-extractor.json)**
  - **Descripción:** Este flujo automático permite a un usuario extraer datos de PDF utilizando prompts dinámicos en una tabla Baserow.
  - **Complejidad:** Baja (4 nodos)

- **[0872-estudio-descomposicion-documents-n8n.json](workflows/0872-estudio-descomposicion-documents-n8n.json)**
  - **Descripción:** Este flujo automatizado permite al sistema procesar documentos subidos en un directorio especificado, dividirlos en bloques de texto, vectorizar su contenido y luego generar diferentes tipos de materiales de estudio como guías o cronologías utilizando modelos de lenguaje AI. Finalmente exporta estos archivos generados junto con el original.
  - **Complejidad:** Baja (4 nodos)

- **[0908-ai-interviews-n8n.json](workflows/0908-ai-interviews-n8n.json)**
  - **Descripción:** Este flujo automático con n8n permite realizar entrevistas conversacionales con un agente de IA que dinámicamente pregunta y registra respuestas en Redis, usando formularios para capturar información. Las respuestas se guardan en Google Sheets.
  - **Complejidad:** Baja (4 nodos)

- **[0913-google-maps-leads-generator.json](workflows/0913-google-maps-leads-generator.json)**
  - **Descripción:** Este flujo automático utiliza la API de Google Maps para buscar lugares basados en categorías y códigos postales específicos, extrayendo datos relevantes e insertándolos en una hoja de Google Sheets con mecanismos de control anti-duplicado y manejo exponencial de errores.
  - **Complejidad:** Baja (4 nodos)

- **[0934-ai-logo-sheet-extractor.json](workflows/0934-ai-logo-sheet-extractor.json)**
  - **Descripción:** Este flujo automático permite extraer información de imágenes que muestran tablas de logotipos, identificando herramientas y sus atributos para guardarlos en Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[0984-ai-logo-extractor.json](workflows/0984-ai-logo-extractor.json)**
  - **Descripción:** Este flujo automático permite extraer información de una imagen con múltiples logotipos utilizando IA, y guardarla en tablas estructuradas de Airtable para categorizar herramientas.
  - **Complejidad:** Baja (4 nodos)

- **[1122-wordpress-auto-generation.json](workflows/1122-wordpress-auto-generation.json)**
  - **Descripción:** Este flujo automático selecciona la categoría menos utilizada de WordPress desde una base de datos PostgreSQL para generar artículos únicos y estructurados mediante modelos GPT. Después de crear el contenido completo en formato HTML específico, genera un título optimizado y descarga/adjunta una imagen destacada antes de publicar todo junto.
  - **Complejidad:** Baja (4 nodos)

- **[1270-email-header-analyzer.json](workflows/1270-email-header-analyzer.json)**
  - **Descripción:** Analiza los encabezados de un correo para obtener metadatos.
  - **Complejidad:** Baja (4 nodos)

- **[1271-email-header-analyzer.json](workflows/1271-email-header-analyzer.json)**
  - **Descripción:** Analiza los encabezados de un correo para obtener metadatos.
  - **Complejidad:** Baja (4 nodos)

- **[1272-ai_airtable_agent.json](workflows/1272-ai_airtable_agent.json)**
  - **Descripción:** Agente de IA que gestiona registros en Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[1445-breakdown-documents-into-study-notes.json](workflows/1445-breakdown-documents-into-study-notes.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, extracción de datos, generación de contenido utilizando Webhook, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (4 nodos)

- **[2603-suspicious-login-detection.json](workflows/2603-suspicious-login-detection.json)**
  - **Descripción:** Este flujo n8n detecta logins sospechosos de cuentas mediante la integración de datos de IP-API, UserParser y GreyNoise. Analiza ubicaciones nuevas o dispositivos/browser diferentes para determinar si es un intento fraudulento.
  - **Complejidad:** Baja (4 nodos)

- **[2670-n8n_creators_leaderboard_stats.json](workflows/2670-n8n_creators_leaderboard_stats.json)**
  - **Descripción:** Este flujo automatiza la obtención y procesamiento de datos estadísticos del tablero de n8n creadores para generar informes detallados en formato Markdown sobre las contribuciones específicas de un usuario.
  - **Complejidad:** Baja (4 nodos)

- **[2679-chatgpt-email-sheets.json](workflows/2679-chatgpt-email-sheets.json)**
  - **Descripción:** Este flujo automático gestiona las respuestas de ChatGPT a correos electrónicos específicos y registra interacciones en Google Sheets.
  - **Complejidad:** Baja (4 nodos)

- **[2731-woocommerce-chatbot.json](workflows/2731-woocommerce-chatbot.json)**
  - **Descripción:** Este flujo automático permite a un chatbot recuperar y mostrar información de pedidos de WooCommerce basada en la dirección de correo electrónico del usuario. Utiliza herramientas de encriptación para proteger los datos sensibles y servicios como DHL para el seguimiento de envíos.
  - **Complejidad:** Baja (4 nodos)

- **[2770-automated-notes-generator.json](workflows/2770-automated-notes-generator.json)**
  - **Descripción:** Este flujo automático monitorea un directorio para detectar nuevos archivos, procesa su contenido y utiliza agentes de IA para generar documentos estructurados en formato Markdown como guías de estudio, timeline y documentación informativa.
  - **Complejidad:** Baja (4 nodos)

- **[2862-mcp-qdrant-reviews.json](workflows/2862-mcp-qdrant-reviews.json)**
  - **Descripción:** Este flujo configura y administra una base de datos vectorial con Qdrant para realizar operaciones como insertar, buscar, comparar y recomendar revisiones de empresas. Utiliza MCP Server Trigger para manejar diferentes herramientas personalizadas y extiende la funcionalidad del servidor Qdrant con capacidades avanzadas.
  - **Complejidad:** Baja (4 nodos)

- **[2876-workflow_mcp_manager.json](workflows/2876-workflow_mcp_manager.json)**
  - **Descripción:** Este flujo gestiona dinámicamente una lista de workflows disponibles mediante Redis y n8n, permitiendo operaciones como agregar, eliminar y listar workflows. Utiliza un agente de lenguaje para ejecutar tareas basadas en estos workflows.
  - **Complejidad:** Baja (4 nodos)

- **[2879-stock-analysis-bot.json](workflows/2879-stock-analysis-bot.json)**
  - **Descripción:** Este flujo automático realiza un análisis detallado de acciones combinando análisis técnico y sentimiento de noticias. Utiliza varias APIs para obtener datos técnicos (gráficos, indicadores) y analítica de sentimiento, luego los procesa con GPT-4 para generar un informe estructurado en formato HTML en hebreo, que se envía por correo electrónico.
  - **Complejidad:** Baja (4 nodos)

- **[2899-prevent-concurrent-workflows.json](workflows/2899-prevent-concurrent-workflows.json)**
  - **Descripción:** Este flujo utiliza Redis para prevenir la ejecución concurrente de workflows. Almacena estados en Redis y verifica si un proceso ya está en curso antes de continuar.
  - **Complejidad:** Baja (4 nodos)

- **[2937-tiktok-youtube-generator.json](workflows/2937-tiktok-youtube-generator.json)**
  - **Descripción:** Este flujo automático genera contenido multimedia para TikTok y YouTube Shorts/Reels de manera automatizada utilizando APIs como PiAPI para imágenes y videos, ElevenLabs para voces, Google Drive para almacenamiento y OpenAI para texto. Incluye capturas de ideas, generación de imágenes, conversión a video, adición de audio, mezcla de elementos y notificación al final.
  - **Complejidad:** Baja (4 nodos)

- **[2956-nextcloud-docker-flow.json](workflows/2956-nextcloud-docker-flow.json)**
  - **Descripción:** Este flujo configura y gestiona entornos Docker para NextCloud utilizando n8n, incluyendo acciones como iniciar, detener, suspender, desususpender, montar/desmontar discos, actualizar paquetes y más. También administra conexiones DNS y verifica la validez del dominio.
  - **Complejidad:** Baja (4 nodos)

- **[3058-set_medoids_cultivos.json](workflows/3058-set_medoids_cultivos.json)**
  - **Descripción:** Este flujo configura los medoides (centros) de dos tipos para la detección de anomalías en un conjunto de datos de cultivos usando Qdrant y el modelo Voyage. Calcula representantes de clusters mediante matrices de distancia y vectores embedding de texto.
  - **Complejidad:** Baja (4 nodos)

- **[3126-multi-ai-chatbot-postgres-chart.json](workflows/3126-multi-ai-chatbot-postgres-chart.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con una base de datos PostgreSQL o Supabase mediante consultas SQL y generar gráficos visualizados en QuickChart usando agentes de inteligencia artificial. El sistema utiliza OpenAI para procesar las preguntas del usuario, ejecutar consultas SQL, obtener definiciones de tablas y crear gráficos basados en los resultados obtenidos.
  - **Complejidad:** Baja (4 nodos)

- **[3160-chatgpt-email-responses.json](workflows/3160-chatgpt-email-responses.json)**
  - **Descripción:** Este flujo automático envía una respuesta de ChatGPT a través de correo electrónico cuando se recibe un correo electrónico y registra las respuestas en Google Sheets. También registra retroalimentación para mejorar el modelo.
  - **Complejidad:** Baja (4 nodos)

- **[0024-iss-position-updates.json](workflows/0024-iss-position-updates.json)**
  - **Descripción:** Este flujo automático obtiene cada minuto la posición actual de la Estación Espacial Internacional (ISS) desde una API externa y envía los datos a un topic en ActiveMQ.
  - **Complejidad:** Baja (4 nodos)

- **[0030-iss-monitoring-sqs.json](workflows/0030-iss-monitoring-sqs.json)**
  - **Descripción:** Este flujo automático verifica cada minuto la posición del satélite ISS mediante una API y almacena los datos en variables para su uso posterior.
  - **Complejidad:** Baja (4 nodos)

- **[0032-iss-satellite-monitoring.json](workflows/0032-iss-satellite-monitoring.json)**
  - **Descripción:** Este flujo automatizado consulta periódicamente la posición del satélite ISS mediante una API y carga los datos en Google BigQuery.
  - **Complejidad:** Baja (4 nodos)

- **[0042-iss-mqtt-flow.json](workflows/0042-iss-mqtt-flow.json)**
  - **Descripción:** Este flujo automático ejecuta una llamada HTTP cada minuto para obtener la posición actual de la Estación Espacial Internacional desde api.wheretheiss.at, procesa los datos y los envía a través de MQTT al tópico 'iss-position'.
  - **Complejidad:** Baja (4 nodos)

- **[0050-calendly-humantic-personality-analysis.json](workflows/0050-calendly-humantic-personality-analysis.json)**
  - **Descripción:** Este flujo automatizado responde a eventos de Calendly (como la creación de un invitado) para ejecutar análisis de personalidad con Humantic AI y almacenar posteriormente los resultados en una página de base de datos de Notion.
  - **Complejidad:** Baja (4 nodos)
  - [Ver lista completa](https://github.com/DragonJAR/n8n-workflows-es/blob/main/README.md)

- **[0058-microsoft-todo-blueprint.json](workflows/0058-microsoft-todo-blueprint.json)**
  - **Descripción:** Este flujo permite crear y actualizar tareas en Microsoft To Do mediante un trigger manual. Comienza con la activación del trigger que inicializa el proceso. Luego crea una nueva tarea (create) especificando detalles como lista de tareas, importancia alta y contenido. Posteriormente, actualiza esa misma tarea usando los datos retornados por la creación para identificarla.
  - **Complejidad:** Baja (4 nodos)

- **[0070-114_validar_telefono.json](workflows/0070-114_validar_telefono.json)**
  - **Descripción:** Este flujo automático verifica si el número telefónico +34605281220 es válido utilizando un proceso de validación mediante uProc. Comienza con un trigger manual que inicia el flujo, luego configura una variable 'phone' en los datos del flujo y la envía a una validación por parte de un servicio de verificación.
  - **Complejidad:** Baja (4 nodos)

- **[0077-conversor-json-a-xml.json](workflows/0077-conversor-json-a-xml.json)**
  - **Descripción:** Este flujo convierte datos JSON en XML utilizando el nodo 'Set' para definir valores específicos y los responde mediante un webhook.
  - **Complejidad:** Baja (4 nodos)

- **[0079-sheets-to-dropbox.json](workflows/0079-sheets-to-dropbox.json)**
  - **Descripción:** Este flujo automático lee una hoja de cálculo cada 15 minutos y la convierte en archivo XLS para subirlo a Dropbox.
  - **Complejidad:** Baja (4 nodos)

- **[0120-customer-data-post.json](workflows/0120-customer-data-post.json)**
  - **Descripción:** Este flujo automatizado inicia manualmente con un clic, establece una clave API y luego obtiene todos los datos de personas del dataStore para enviarlos mediante POST a webhook.site.
  - **Complejidad:** Baja (4 nodos)

- **[0128-iss-position-firebase.json](workflows/0128-iss-position-firebase.json)**
  - **Descripción:** Este flujo automatizado recoge cada minuto la posición actual del ISS desde una API y almacena los datos en tiempo real en una base de datos Firebase.
  - **Complejidad:** Baja (4 nodos)

- **[0139-gdrive-aws-s3-sync.json](workflows/0139-gdrive-aws-s3-sync.json)**
  - **Descripción:** Este flujo monitoriza cambios en un archivo de Google Drive específico y sincroniza archivos con el bucket 'mybucket' en AWS S3 mediante operaciones de obtención y subida, utilizando un nodo 'merge' para combinar datos.
  - **Complejidad:** Baja (4 nodos)

- **[0143-rekognition-google-images.json](workflows/0143-rekognition-google-images.json)**
  - **Descripción:** Este flujo automatizado busca imágenes de calles desde Google y utiliza AWS Rekognition para analizarlas y extraer etiquetas. Luego combina estos resultados junto con los datos originales y guarda todo en una hoja de cálculo de Google.
  - **Complejidad:** Baja (4 nodos)

- **[0150-workflow-spreadsheet-export.json](workflows/0150-workflow-spreadsheet-export.json)**
  - **Descripción:** Este flujo n8n procesa una entrada de webhook que contiene listas de elementos, convierte estos en un archivo de Excel (.xlsx) y responde al webhook con la hoja de cálculo como archivo adjunto.
  - **Complejidad:** Baja (4 nodos)

- **[0183-questdb-tabla-datos.json](workflows/0183-questdb-tabla-datos.json)**
  - **Descripción:** Este flujo automático crea una tabla 'test' con columnas id y name en QuestDB al ejecutarse manualmente.
  - **Complejidad:** Baja (4 nodos)

- **[0215-html-sheet.json](workflows/0215-html-sheet.json)**
  - **Descripción:** Este flujo automatizado lee datos de una hoja de Google Sheets y los convierte en un HTML con formato tabla para responder a través de webhook.
  - **Complejidad:** Baja (4 nodos)

- **[0303-google-sheets-sync.json](workflows/0303-google-sheets-sync.json)**
  - **Descripción:** Este flujo automático lee datos de una hoja de cálculo Google y los sincroniza periódicamente en el listado de suscriptores de Mailchimp.
  - **Complejidad:** Baja (4 nodos)

- **[0317-phantom-airtable-store.json](workflows/0317-phantom-airtable-store.json)**
  - **Descripción:** Este flujo permite ejecutar una operación Phantom Buster y almacenar el resultado estructurado en Airtable mediante la opción 'append'.
  - **Complejidad:** Baja (4 nodos)

- **[0321-airtable-image-automation.json](workflows/0321-airtable-image-automation.json)**
  - **Descripción:** Este flujo automático busca y actualiza registros en Airtable para agregar imágenes mediante URL.
  - **Complejidad:** Baja (4 nodos)

- **[0322-notion-bookmark-tracker.json](workflows/0322-notion-bookmark-tracker.json)**
  - **Descripción:** Este flujo automatizado recibe URLs a través de un webhook POST y las crea como nuevas páginas en una base de datos Notion especificada.
  - **Complejidad:** Baja (4 nodos)

- **[0328-analytics-airtable.json](workflows/0328-analytics-airtable.json)**
  - **Descripción:** Este flujo automatizado obtiene datos de análisis web históricos y los almacena en una tabla de Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[0336-google-contacts-test.json](workflows/0336-google-contacts-test.json)**
  - **Descripción:** Este flujo automatizado permite crear un contacto en Google Contacts con los datos de n8n y luego actualizar e inmediatamente obtener ese mismo contacto.
  - **Complejidad:** Baja (4 nodos)

- **[0362-country-query-formatter.json](workflows/0362-country-query-formatter.json)**
  - **Descripción:** Este flujo automático consulta datos de país mediante GraphQL usando un código como parámetro, luego extrae el objeto del país y lo convierte en texto formateado para ser enviado a través de una URL.
  - **Complejidad:** Baja (4 nodos)

- **[0499-tts-generation.json](workflows/0499-tts-generation.json)**
  - **Descripción:** Este flujo automático permite ejecutar un script de Python para generar archivos de audio MP3 basados en texto y voz predefinidos.
  - **Complejidad:** Baja (4 nodos)

- **[0517-postgres-csv-export.json](workflows/0517-postgres-csv-export.json)**
  - **Descripción:** Este flujo automático consulta datos de una tabla específica (booksRead) en PostgreSQL mediante un trigger manual y exporta el resultado a un archivo CSV.
  - **Complejidad:** Baja (4 nodos)

- **[0596-cfp-trello-cards.json](workflows/0596-cfp-trello-cards.json)**
  - **Descripción:** Este flujo selecciona solicitantes de un evento CFP con puntuación mayor que 15 en Airtable y crea tarjetas en Trello a partir de la información del formulario usando Bannerbear para generar imágenes publicitarias.
  - **Complejidad:** Baja (4 nodos)

- **[0621-crear-tabla-y-insertar.json](workflows/0621-crear-tabla-y-insertar.json)**
  - **Descripción:** Este flujo manual crea una tabla en CrateDB si no existe y luego inserta un registro con valores predefinidos.
  - **Complejidad:** Baja (4 nodos)

- **[0622-crear-tabla-json.json](workflows/0622-crear-tabla-json.json)**
  - **Descripción:** Este flujo ejecuta una consulta SQL para crear una tabla denominada 'test' con columnas id e name, luego configura un conjunto de valores que incluye esos datos.
  - **Complejidad:** Baja (4 nodos)

- **[0623-postgres-create-set-insert.json](workflows/0623-postgres-create-set-insert.json)**
  - **Descripción:** Este flujo automatizado inicia con un clic manual que ejecuta una consulta SQL para crear una tabla llamada 'test' en PostgreSQL. Luego, toma la salida de esa creación y la utiliza como entrada para establecer valores en el nodo Set (específicamente, espera establecer un valor numérico para 'id' y una cadena fija para 'name'). Finalmente, estos valores se envían a otra operación PostgreSQL.
  - **Complejidad:** Baja (4 nodos)

- **[0634-dos_pasos_google_sheets.json](workflows/0634-dos_pasos_google_sheets.json)**
  - **Descripción:** Este flujo automático permite al usuario iniciar la ejecución manual y luego anexar datos en Google Sheets.
  - **Complejidad:** Baja (4 nodos)

- **[0649-amazon-s3-upload-list-json.json](workflows/0649-amazon-s3-upload-list-json.json)**
  - **Descripción:** Descarga un archivo desde una URL, lo sube a Amazon S3 y muestra todos los archivos en el bucket.
  - **Complejidad:** Baja (4 nodos)

- **[0650-cocktail-storage.json](workflows/0650-cocktail-storage.json)**
  - **Descripción:** Este flujo automático permite almacenar de forma persistente los datos en bruto de un trago aleatorio obtenido de la API de CocktailDB mediante el guardado como archivo JSON.
  - **Complejidad:** Baja (4 nodos)

- **[0651-ejemplo-merge.json](workflows/0651-ejemplo-merge.json)**
  - **Descripción:** Este flujo analiza datos de ejemplo para fusionar información sobre nombre y saludo en función del idioma común.
  - **Complejidad:** Baja (4 nodos)

- **[0654-descargar-y-subir-imagen.json](workflows/0654-descargar-y-subir-imagen.json)**
  - **Descripción:** Este flujo automático permite descargar una imagen de n8n.io y subirla directamente a un servidor FTP mediante el botón 'execute'.
  - **Complejidad:** Baja (4 nodos)

- **[0666-sheets-sync-every-2min.json](workflows/0666-sheets-sync-every-2min.json)**
  - **Descripción:** Este flujo automatizado ejecuta una actualización en dos hojas de Google cada dos minutos, utilizando datos leídos previamente.
  - **Complejidad:** Baja (4 nodos)

- **[0673-expense-tracker-mindee-airtable.json](workflows/0673-expense-tracker-mindee-airtable.json)**
  - **Descripción:** Este flujo permite recibir un webhook con datos de factura que Mindee procesa y almacena en una tabla de Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[0705-google-sheets-mattermost-notification.json](workflows/0705-google-sheets-mattermost-notification.json)**
  - **Descripción:** Este flujo automático verifica cada 45 minutos datos nuevos de una hoja Google Sheets y envía al chatbot un mensaje formateado indicando la adición.
  - **Complejidad:** Baja (4 nodos)

- **[0727-iss-tracking-timescaledb.json](workflows/0727-iss-tracking-timescaledb.json)**
  - **Descripción:** Este flujo de trabajo automatizado consulta periódicamente la posición actual del satélite ISS y la almacena en una tabla de TimescaleDB para análisis temporal.
  - **Complejidad:** Baja (4 nodos)

- **[0732-reddit-automated-posting.json](workflows/0732-reddit-automated-posting.json)**
  - **Descripción:** Este flujo automático publica un mensaje inicial en Reddit, luego obtiene datos de ese post y finalmente añade un comentario con información procesada.
  - **Complejidad:** Baja (4 nodos)

- **[0738-n8n-flujo-set-stackby.json](workflows/0738-n8n-flujo-set-stackby.json)**
  - **Descripción:** Este flujo utiliza un trigger manual para establecer valores estáticos en un nodo 'set', luego pasa estos datos a otro nodo Stackby que los muestra en una tabla. El segundo Stackby utiliza la configuración de ID y nombre del primer nodo, manteniendo coherencia con esos campos.
  - **Complejidad:** Baja (4 nodos)

- **[0740-tapfiliate-crear-cuenta.json](workflows/0740-tapfiliate-crear-cuenta.json)**
  - **Descripción:** Este flujo automático crea una cuenta de afiliado en Tapfiliate con datos predefinidos y añade un tag personalizado.
  - **Complejidad:** Baja (4 nodos)

- **[0757-weather-query-response.json](workflows/0757-weather-query-response.json)**
  - **Descripción:** Este flujo automatizado consulta un servicio web para obtener datos meteorológicos de una ciudad especificada, los formatea y los devuelve como respuesta.
  - **Complejidad:** Baja (4 nodos)

- **[0761-iss-kafka-positions.json](workflows/0761-iss-kafka-positions.json)**
  - **Descripción:** Este flujo automático consulta cada minuto la posición actual del satélite ISS a través de la API WhereTheIss y envía los datos en tiempo real al topic Kafka 'iss-position'.
  - **Complejidad:** Baja (4 nodos)

- **[0765-wise-transfer-handler.json](workflows/0765-wise-transfer-handler.json)**
  - **Descripción:** Este flujo automático permite registrar en Airtable detalles de transferencias cuando cambia su estado utilizando la API de Wise.
  - **Complejidad:** Baja (4 nodos)

- **[1048-notion-clockify-client-sync.json](workflows/1048-notion-clockify-client-sync.json)**
  - **Descripción:** Este flujo automático detecta nuevos clientes en una base de datos de Notion y añade cada uno automáticamente al sistema de gestión de tiempo de Clockify.
  - **Complejidad:** Baja (4 nodos)

- **[1079-automatizar-carga-csv-postgres.json](workflows/1079-automatizar-carga-csv-postgres.json)**
  - **Descripción:** Este flujo automático lee un archivo CSV desde /tmp, lo convierte a formato de spreadsheet y carga los datos directamente en la tabla t1 de PostgreSQL.
  - **Complejidad:** Baja (4 nodos)

- **[1128-csv-insert-json.json](workflows/1128-csv-insert-json.json)**
  - **Descripción:** Este flujo automático lee un archivo CSV desde una ubicación específica y lo convierte a formato de hoja de cálculo para luego insertarlo en la tabla MySQL concerts_2023_csv.
  - **Complejidad:** Baja (4 nodos)

- **[2553-parquet-conversion-flujos.json](workflows/2553-parquet-conversion-flujos.json)**
  - **Descripción:** Este flujo permite convertir archivos Parquet, Avro, ORC y Feather a JSON utilizando la API de ParquetReader. Se inicia con un envío vía webhook que recibe el archivo en formato binario, lo procesa y devuelve los datos estructurados.
  - **Complejidad:** Baja (4 nodos)

- **[2643-api-moa-googleSheets.json](workflows/2643-api-moa-googleSheets.json)**
  - **Descripción:** Este flujo automático recopila datos de cotización ovina desde la API del Ministerio de Agricultura a través de una solicitud HTTP, los divide y luego los añade como nuevas filas en un archivo Google Sheets específico.
  - **Complejidad:** Baja (4 nodos)

- **[3123-sync-todoist-notion.json](workflows/3123-sync-todoist-notion.json)**
  - **Descripción:** Este flujo sincroniza tareas etiquetadas en Todoist con Notion y marca las tareas como enviadas una vez completada la sincronización.
  - **Complejidad:** Baja (4 nodos)

- **[0716-blotato-social-publishing.json](workflows/0716-blotato-social-publishing.json)**
  - **Descripción:** Este flujo automático publica videos e imágenes en múltiples redes sociales como Instagram, Facebook, LinkedIn, TikTok y más utilizando la plataforma Blotato. La automatización extrae contenido de Airtable, genera títulos virales para YouTube con OpenAI y gestiona el estado de publicación.
  - **Complejidad:** Baja (3 nodos)

- **[0791-ai-wordpress-summary.json](workflows/0791-ai-wordpress-summary.json)**
  - **Descripción:** Este flujo automático genera y añade un resumen AI al principio de artículos de WordPress usando OpenAI, verifica si ya existe uno para evitar duplicados, actualiza la página y guarda los datos en Google Sheets.
  - **Complejidad:** Baja (3 nodos)

- **[0798-ai-chat-with-supabase-documents.json](workflows/0798-ai-chat-with-supabase-documents.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de IA procesar documentos PDF y texto almacenados en Supabase, generar embeddings vectoriales con OpenAI y crear una base de conocimiento interactiva para consultas sobre archivos.
  - **Complejidad:** Baja (3 nodos)

- **[0800-search-console-ai-agent.json](workflows/0800-search-console-ai-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con datos del motor de búsqueda utilizando herramientas de la API de Google Search Console, OpenAI y almacenar el historial de conversaciones en una base de datos PostgreSQL.
  - **Complejidad:** Baja (3 nodos)

- **[0819-erpnext-candidate-automation.json](workflows/0819-erpnext-candidate-automation.json)**
  - **Descripción:** Este flujo automático permite integrar webhooks de ERPNext para gestionar solicitudes de candidatos mediante análisis AI (como Google Gemini) y actualizar sus estados en función del resultado.
  - **Complejidad:** Baja (3 nodos)

- **[0832-wordpress-ai-content-generator.json](workflows/0832-wordpress-ai-content-generator.json)**
  - **Descripción:** Este flujo automático crea artículos en WordPress a diferentes niveles de lectura utilizando modelos de lenguaje. Procesa el contenido reescrito, valida que tengan título e introducción, genera imágenes relacionadas y guarda borradores en Google Drive.
  - **Complejidad:** Baja (3 nodos)

- **[0874-tax-code-assistant-qdrant-mistral-openai.json](workflows/0874-tax-code-assistant-qdrant-mistral-openai.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de IA responder preguntas sobre el código fiscal del estado de Texas utilizando embeddings de Mistral.ai para generar vectores y Qdrant para almacenar y recuperar documentos con eficiencia, optimizando la gestión de grandes archivos mediante descompresión estratégica.
  - **Complejidad:** Baja (3 nodos)

- **[0886-workflow-doc-analyzer.json](workflows/0886-workflow-doc-analyzer.json)**
  - **Descripción:** Este flujo automático analiza documentos subidos mediante formulario, convierte el markdown en HTML y guarda los resultados en una base de datos vectorial para alimentar un chatbot.
  - **Complejidad:** Baja (3 nodos)

- **[0965-factoid_subscription_service.json](workflows/0965-factoid_subscription_service.json)**
  - **Descripción:** Este flujo automático utiliza n8n formularios para gestionar suscripciones a correos educativos diarios, semanales o sorprendentes con modelos de IA generativa y almacenamiento en Airtable.
  - **Complejidad:** Baja (3 nodos)

- **[0968-HR_CV_Evaluation_AI.json](workflows/0968-HR_CV_Evaluation_AI.json)**
  - **Descripción:** Este flujo automático permite evaluar automáticamente solicitudes de candidatos mediante análisis AI para determinar su calificación y aptitud para la vacante, actualizando luego en Airtable según el resultado.
  - **Complejidad:** Baja (3 nodos)

- **[0973-ai-faq-generator.json](workflows/0973-ai-faq-generator.json)**
  - **Descripción:** Este flujo utiliza n8n y modelos de lenguaje como ChatGPT para generar automáticamente contenido completo en FAQ basado en datos proporcionados.
  - **Complejidad:** Baja (3 nodos)

- **[0995-agent-access-control.json](workflows/0995-agent-access-control.json)**
  - **Descripción:** Este flujo verifica las credenciales del usuario en Airtable para establecer permisos y control de acceso a diferentes agentes y herramientas.
  - **Complejidad:** Baja (3 nodos)

- **[1091-spotify-maintenance.json](workflows/1091-spotify-maintenance.json)**
  - **Descripción:** Este flujo automático verifica si las canciones de las últimas reproducciones en Spotify ya están guardadas en la base de datos NocoDB. Si no lo están, crea nuevos registros para cada una con el URI de la canción y la fecha en que fue añadida (usando currentDate). También busca en la base de datos existente si hay una playlist mensual con el nombre correspondiente a la fecha actual. Si existe, obtiene sus pistas; si no existe en Spotify pero sí está en NocoDb, la crea y sincroniza.
  - **Complejidad:** Baja (3 nodos)

- **[1104-airtable-batch-processing-with-rates.json](workflows/1104-airtable-batch-processing-with-rates.json)**
  - **Descripción:** Este flujo procesa registros en lote en Airtable con tres modos: insert, update y upsert. Para evitar límites de tasa en la API de Airtable, incluye pausas después de cada error 429.
  - **Complejidad:** Baja (3 nodos)

- **[1154-content-generation-automated.json](workflows/1154-content-generation-automated.json)**
  - **Descripción:** Este flujo automático permite generar contenido estructurado a partir de entradas formulario utilizando modelos OpenAI y almacenar los resultados en Google Drive.
  - **Complejidad:** Baja (3 nodos)

- **[1164-zendesk-gcal-airtable-customer-flow.json](workflows/1164-zendesk-gcal-airtable-customer-flow.json)**
  - **Descripción:** Este flujo automático permite a un chatbot integrar múltiples sistemas como Zendesk para crear tickets y gestionar datos de clientes, Gcal (Google Calendar) para programar citas, Airtable para compartir transcripciones con el equipo de producto, y n8n para ejecutar todas las operaciones.
  - **Complejidad:** Baja (3 nodos)

- **[1265-airtable-baserow-form-connector.json](workflows/1265-airtable-baserow-form-connector.json)**
  - **Descripción:** Conecta formularios de Airtable con bases en Baserow.
  - **Complejidad:** Baja (3 nodos)

- **[1275-flujo-seleccion-candidatos-ai.json](workflows/1275-flujo-seleccion-candidatos-ai.json)**
  - **Descripción:** Flujo de selección de candidatos asistido por IA.
  - **Complejidad:** Baja (3 nodos)

- **[1425-ai-agent-to-chat-with-files-in-supabase-storage.json](workflows/1425-ai-agent-to-chat-with-files-in-supabase-storage.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, extracción de datos, generación de contenido utilizando OpenAI/GPT, Webhook, Airtable con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (3 nodos)

- **[1426-ai-agent-to-chat-with-openai.json](workflows/1426-ai-agent-to-chat-with-openai.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, generación de contenido utilizando OpenAI/GPT, Webhook, Supabase con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (3 nodos)

- **[1492-respond-to-whatsapp-messages-with-ai-like-a-pro.json](workflows/1492-respond-to-whatsapp-messages-with-ai-like-a-pro.json)**
  - **Descripción:** Este flujo permite chatbot, transcripción, resumen, extracción de datos, generación de contenido utilizando OpenAI/GPT, Webhook, WhatsApp con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (3 nodos)

- **[2536-billbee-address-validation.json](workflows/2536-billbee-address-validation.json)**
  - **Descripción:** Este flujo automático valida y corrige direcciones de envío de pedidos utilizando la API Endereco para verificar datos en Alemania.
  - **Complejidad:** Baja (3 nodos)

- **[2556-glassdoor-discrimination-analysis.json](workflows/2556-glassdoor-discrimination-analysis.json)**
  - **Descripción:** Este flujo automático utiliza ScrapingBee para extraer reseñas y datos demográficos de Glassdoor, junto con modelos de OpenAI para analizar patrones discriminatorios mediante cálculos estadísticos como puntuaciones z y tamaños de efecto.
  - **Complejidad:** Baja (3 nodos)

- **[2600-news-pipeline.json](workflows/2600-news-pipeline.json)**
  - **Descripción:** Este flujo automatizado extrae artículos de prensa, los filtra por antigüedad (7 días), genera resúmenes y palabras clave usando ChatGPT, y almacena todo en una base de datos SQL.
  - **Complejidad:** Baja (3 nodos)

- **[2686-nextcloud_folder_migration.json](workflows/2686-nextcloud_folder_migration.json)**
  - **Descripción:** Este flujo automático搬迁文件夹及其子文件和子文件夹到Nextcloud的指定位置，确保结构完整并避免超过速率限制。
  - **Complejidad:** Baja (3 nodos)

- **[2736-wordpress-article-generator.json](workflows/2736-wordpress-article-generator.json)**
  - **Descripción:** Flujo que automatiza la creación de artículos en WordPress utilizando OpenAI para generar contenido estructurado y DALL·E para imágenes, con validación de datos.
  - **Complejidad:** Baja (3 nodos)

- **[2766-hellofresh-recomendador.json](workflows/2766-hellofresh-recomendador.json)**
  - **Descripción:** Este flujo automatiza la recomendación de recetas semanales de HelloFresh mediante un motor de búsqueda vectorial y una base de datos. Extrae información de menús semanales, procesa datos de recetas, genera embeddings con Mistral Cloud y utiliza Qdrant para推荐pciones basadas en preferencias.
  - **Complejidad:** Baja (3 nodos)

- **[2775-competitor-research-automator.json](workflows/2775-competitor-research-automator.json)**
  - **Descripción:** Este flujo automatiza la investigación competitiva usando Exa.ai para encontrar competidores y luego recopila información detallada sobre cada competidor mediante agentes de inteligencia artificial que extraen datos de sitios como Crunchbase, LinkedIn y bienvenidos. Los datos se estructuran y se insertan en Notion.
  - **Complejidad:** Baja (3 nodos)

- **[2778-trustpilot-insights.json](workflows/2778-trustpilot-insights.json)**
  - **Descripción:** Este flujo extrae, procesa y analiza reseñas de Trustpilot para una empresa específica. Utiliza Qdrant como base vectorial para almacenar datos estructurados, aplica clustering con K-means para identificar patrones, genera insights usando un modelo LLM y exporta los resultados a Google Sheets.
  - **Complejidad:** Baja (3 nodos)

- **[2779-hn_comments_analyzer.json](workflows/2779-hn_comments_analyzer.json)**
  - **Descripción:** Este flujo automático extrae y analiza comentarios de un artículo de Hacker News, los organiza en clusters utilizando algoritmos de agrupamiento (K-means) y genera insights con un modelo de lenguaje grande. Los datos se almacenan en Qdrant para su posterior análisis.
  - **Complejidad:** Baja (3 nodos)

- **[2799-faq-generator-n8n.json](workflows/2799-faq-generator-n8n.json)**
  - **Descripción:** Este flujo automatiza la creación de FAQ para integraciones de n8n usando OpenAI y Google Sheets. Extrae datos de una hoja de cálculo, genera pares de preguntas y respuestas, completa algunas respuestas con AI y guarda los resultados en Google Drive.
  - **Complejidad:** Baja (3 nodos)

- **[2820-auto-assign-jira.json](workflows/2820-auto-assign-jira.json)**
  - **Descripción:** Este flujo automatiza la asignación de tareas estancadas en JIRA mediante un sistema de coincidencias con issues resueltos pasados usando IA y bases de datos vectoriales. Busca tareas sin asignar durante más de 5 días, encuentra las más similares en la base de conocimientos y asigna a los miembros del equipo con menos cargas actuales.
  - **Complejidad:** Baja (3 nodos)

- **[2829-digest-novedades-plantillas.json](workflows/2829-digest-novedades-plantillas.json)**
  - **Descripción:** Este flujo automático genera un resumen diario de las plantillas más recientes de n8n filtradas por categorías seleccionadas por los subscriptores almacenados en una hoja de cálculo de Excel. Utiliza OpenAI para resumir las descripciones y Outlook para enviar el correo electrónico.
  - **Complejidad:** Baja (3 nodos)

- **[2883-chatbot-interactivo.json](workflows/2883-chatbot-interactivo.json)**
  - **Descripción:** Este flujo gestiona la interacción de un chatbot, almacenando mensajes en Redis y usando OpenAI para extraer información. Espera una cantidad de tiempo variable basada en el conteo de palabras antes de procesar los mensajes.
  - **Complejidad:** Baja (3 nodos)

- **[2908-llm_chaining.json](workflows/2908-llm_chaining.json)**
  - **Descripción:** Este flujo utiliza cadenas de LLM para realizar tareas secuenciales y paralelas con diferentes modelos de inteligencia artificial, incluyendo la obtención de datos de una página web, el análisis con prompts específicos y la combinación de resultados.
  - **Complejidad:** Baja (3 nodos)

- **[2941-blog-automation.json](workflows/2941-blog-automation.json)**
  - **Descripción:** Este flujo automatiza la creación y publicación de artículos en un blog usando Google Sheets como origen de datos. Configura parámetros, recupera información de hojas de cálculo, procesa prompts personalizados con OpenAI, genera contenido, valida fechas y statuses, y actualiza el estado en tiempo real.
  - **Complejidad:** Baja (3 nodos)

- **[2953-influxdb-docker-deploy.json](workflows/2953-influxdb-docker-deploy.json)**
  - **Descripción:** Este flujo automático implementa y gestiona un contenedor de InfluxDB en Docker para una aplicación relacionada con WHMCS/WISECP, admitiendo operaciones como despliegue, arranque, parada, suspensión, montaje y control de disco.
  - **Complejidad:** Baja (3 nodos)

- **[3000-automatizacion_rrhh.json](workflows/3000-automatizacion_rrhh.json)**
  - **Descripción:** Este flujo automatiza la publicación de ofertas laborales y evalúa candidatos utilizando inteligencia artificial. Incluye formularios para postulaciones, análisis de CV con ChatGPT, generación de cuestionarios personalizados y seguimiento en Airtable.
  - **Complejidad:** Baja (3 nodos)

- **[3030-n8n-rag-living-data.json](workflows/3030-n8n-rag-living-data.json)**
  - **Descripción:** Este flujo automatiza la integración de datos en tiempo real desde Notion hacia un sistema de recuperación de información basado en vectores (RAG) usando OpenAI y Supabase. Procesa documentos, los divide en fragmentos, genera embeddings con OpenAI y almacena los resultados en Supabase para permitir búsquedas semánticas.
  - **Complejidad:** Baja (3 nodos)

- **[3117-ai-search-console-chat.json](workflows/3117-ai-search-console-chat.json)**
  - **Descripción:** Este flujo utiliza OpenAI y Postgres para permitir a un agente de chat interactuar con datos de Google Search Console, recuperando información mediante una conversación natural.
  - **Complejidad:** Baja (3 nodos)

- **[3158-scrape-news-with-ai-to-nocodb.json](workflows/3158-scrape-news-with-ai-to-nocodb.json)**
  - **Descripción:** Este flujo extrae HTML de una página web específicamente con CSS, luego suma los enlaces y fechas de las publicaciones, filtra por fecha reciente, obtiene el contenido individual de cada post, genera resúmenes y palabras clave usando OpenAI, y almacena los datos en NocoDB.
  - **Complejidad:** Baja (3 nodos)

- **[3166-buscar_palabras_clave.json](workflows/3166-buscar_palabras_clave.json)**
  - **Descripción:** Este flujo automatiza la búsqueda de palabras clave principales usando NocoDB y DataforSEO para analizar volumen de búsquedas en Google y YouTube. Genera y actualiza datos en_batches en una base de datos.
  - **Complejidad:** Baja (3 nodos)

- **[3205-backup-n8n.json](workflows/3205-backup-n8n.json)**
  - **Descripción:** Este flujo automático realiza una copia de seguridad diaria de los workflows de n8n en Google Drive. Crea y verifica las carpetas 'n8n_backups' y 'n8n_old', mueve las copias antiguas a la carpeta 'n8n_old' y elimina aquellas que excedan 30 días.
  - **Complejidad:** Baja (3 nodos)

- **[3278-google-sheets-analysis.json](workflows/3278-google-sheets-analysis.json)**
  - **Descripción:** Este flujo utiliza un agente de inteligencia artificial para analizar y manipular datos desde Google Sheets, permitiendo realizar consultas avanzadas filtrando por fechas y estados, transformar formatos complicados en JSON, y obtener estadísticas a través de herramientas como el cálculo y la agregación.
  - **Complejidad:** Baja (3 nodos)

- **[3312-chatbot-curriculos.json](workflows/3312-chatbot-curriculos.json)**
  - **Descripción:** Este flujo permite crear un chatbot personalizado que gestiona currículos y envía reportes diarios con información de conversaciones mediante Google Drive, Gemini, Pinecone y NocoDB.
  - **Complejidad:** Baja (3 nodos)

- **[0019-EscrituraJSONBinario.json](workflows/0019-EscrituraJSONBinario.json)**
  - **Descripción:** Este flujo automatizado crea datos JSON de ejemplo, los convierte a formato binario (Base64) y escribe este contenido en un archivo.
  - **Complejidad:** Baja (3 nodos)

- **[0023-coda-insert-data.json](workflows/0023-coda-insert-data.json)**
  - **Descripción:** Este flujo n8n inserta datos nuevos en una tabla específica de un documento Coda cuando se activa manualmente mediante un clic.
  - **Complejidad:** Baja (3 nodos)

- **[0044-gmail-drive-adjunto.json](workflows/0044-gmail-drive-adjunto.json)**
  - **Descripción:** Este flujo automático extrae mensajes de Gmail, guarda adjuntos en Google Drive y luego obtiene el enlace directo para facilitar su acceso.
  - **Complejidad:** Baja (3 nodos)

- **[0056-aws-transcribe-s3.json](workflows/0056-aws-transcribe-s3.json)**
  - **Descripción:** Este flujo ejecuta AWS Transcribe con todos los archivos encontrados en el bucket 'n8n-docs' de S3.
  - **Complejidad:** Baja (3 nodos)

- **[0097-netlify-to-airtable.json](workflows/0097-netlify-to-airtable.json)**
  - **Descripción:** Este flujo automático captura envíos formularios de Netlify y los agrega automáticamente a una tabla específica en Airtable.
  - **Complejidad:** Baja (3 nodos)

- **[0105-invoicing-textract-s3.json](workflows/0105-invoicing-textract-s3.json)**
  - **Descripción:** Al hacer clic en el botón, se sube un archivo 'Rechnung.jpg' a la carpeta S3 y luego Amazon Textract lo procesa.
  - **Complejidad:** Baja (3 nodos)

- **[0111-onfleet-tasks-from-spreadsheet.json](workflows/0111-onfleet-tasks-from-spreadsheet.json)**
  - **Descripción:** Este flujo carga un archivo Excel desde una ruta local y lo utiliza para crear tareas en Onfleet.
  - **Complejidad:** Baja (3 nodos)

- **[0117-calendly-dropcontact-notion-integracion.json](workflows/0117-calendly-dropcontact-notion-integracion.json)**
  - **Descripción:** Este flujo automatizado permite integrar eventos de Calendly con el sistema DropContact y almacenar los datos en una base de datos de Notion.
  - **Complejidad:** Baja (3 nodos)

- **[0126-sanitized-invoices-upload.json](workflows/0126-sanitized-invoices-upload.json)**
  - **Descripción:** Este flujo lee correos electrónicos de la bandeja 'Invoices' en un servidor IMAP y procesa cada archivo adjunto, sanitizando el nombre del archivo para eliminar caracteres especiales, antes de subirlo a Nextcloud.
  - **Complejidad:** Baja (3 nodos)

- **[0133-gitlab-release-outline.json](workflows/0133-gitlab-release-outline.json)**
  - **Descripción:** Este flujo detecta automáticamente la creación de un nuevo tag en el repositorio GitLab 'ci-test' y, si es una etiqueta de lanzamiento (release), crea un documento Outline basado en los datos proporcionados.
  - **Complejidad:** Baja (3 nodos)

- **[0163-mock-transactions-sum.json](workflows/0163-mock-transactions-sum.json)**
  - **Descripción:** Este flujo utiliza nodos de función para generar datos mockados con montos en USD y calcular la suma total.
  - **Complejidad:** Baja (3 nodos)

- **[0176-weather-api.json](workflows/0176-weather-api.json)**
  - **Descripción:** Este flujo automático permite obtener información meteorológica (temperatura y descripción) de cualquier ciudad que se especifique mediante una solicitud HTTP. Recolecta los datos desde la API de OpenWeatherMap y crea dos variables: 'temp' para la temperatura y 'description' para el estado del tiempo.
  - **Complejidad:** Baja (3 nodos)

- **[0182-logo-download-script.json](workflows/0182-logo-download-script.json)**
  - **Descripción:** Este flujo automatizado descarga una imagen de un URL y la escribe en el sistema de archivos local.
  - **Complejidad:** Baja (3 nodos)

- **[0190-smart-factory-data-generator.json](workflows/0190-smart-factory-data-generator.json)**
  - **Descripción:** Este flujo automatizado genera datos aleatorios de temperatura y tiempo de actividad de una máquina industrial, utilizando un nombre fijo 'n8n_cr8' como identificador, y los envía periódicamente a través de AMQP.
  - **Complejidad:** Baja (3 nodos)

- **[0211-etl-weekly-google-sheets-mysql.json](workflows/0211-etl-weekly-google-sheets-mysql.json)**
  - **Descripción:** Este flujo automático ejecuta una inserción en MySQL cada semana usando datos de Google Sheets.
  - **Complejidad:** Baja (3 nodos)

- **[0214-hoja-html-flujo.json](workflows/0214-hoja-html-flujo.json)**
  - **Descripción:** Este flujo automático lee datos de una hoja de cálculo específica y los convierte en un archivo HTML cuando se recibe una solicitud a través de Webhook.
  - **Complejidad:** Baja (3 nodos)

- **[0251-notion-clockify-invoices.json](workflows/0251-notion-clockify-invoices.json)**
  - **Descripción:** Este flujo automático crea automáticamente un registro en una base de datos de Notion cada vez que se genera una nueva factura en Clockify.
  - **Complejidad:** Baja (3 nodos)

- **[0265-customer-data-count-set.json](workflows/0265-customer-data-count-set.json)**
  - **Descripción:** Este flujo manual cuenta el número de registros de clientes en la base de datos de n8n Training.
  - **Complejidad:** Baja (3 nodos)

- **[0300-nextcloud-deck-email.json](workflows/0300-nextcloud-deck-email.json)**
  - **Descripción:** Este flujo automático lee correos electrónicos por IMAP, limpia su contenido y crea tarjetas en Nextcloud Deck.
  - **Complejidad:** Baja (3 nodos)

- **[0313-insertar-productos-desde-excel.json](workflows/0313-insertar-productos-desde-excel.json)**
  - **Descripción:** Este flujo lee un archivo Excel (.xls), lo interpreta y luego inserta cada fila de este archivo en la tabla 'product' de una base de datos PostgreSQL.
  - **Complejidad:** Baja (3 nodos)

- **[0400-gmail-attachment-upload.json](workflows/0400-gmail-attachment-upload.json)**
  - **Descripción:** Este flujo detecta nuevos correos electrónicos en Gmail con archivos adjuntos, extrae cada archivo individualmente y lo sube a la carpeta raíz de Google Drive.
  - **Complejidad:** Baja (3 nodos)

- **[0401-line-chatbot-memory-automation.json](workflows/0401-line-chatbot-memory-automation.json)**
  - **Descripción:** Este flujo automático extrae datos de nodos Webhook específicos en una ejecución y los pasa al nodo de procesamiento.
  - **Complejidad:** Baja (3 nodos)

- **[0449-rankmath-update-product.json](workflows/0449-rankmath-update-product.json)**
  - **Descripción:** Este flujo automatizado se ejecuta cuando el usuario hace clic en 'Probar flujo' y actualiza los metadatos SEO de un producto específico utilizando la API del plugin Rank Math.
  - **Complejidad:** Baja (3 nodos)

- **[0470-postgres-excel-generator.json](workflows/0470-postgres-excel-generator.json)**
  - **Descripción:** Este flujo ejecuta una consulta en PostgreSQL para obtener los nombres y códigos EAN de los productos, convierte el resultado en un archivo Excel y lo escribe.
  - **Complejidad:** Baja (3 nodos)

- **[0526-webhook-analisis-datos.json](workflows/0526-webhook-analisis-datos.json)**
  - **Descripción:** Este flujo analiza un webhook para extraer datos y generar una respuesta.
  - **Complejidad:** Baja (3 nodos)

- **[0527-3-xml-transform.json](workflows/0527-3-xml-transform.json)**
  - **Descripción:** Este flujo procesa y transforma datos en formato XML mediante la conversión de una cadena XML en un objeto estructurado.
  - **Complejidad:** Baja (3 nodos)

- **[0552-insertar-valor-mongodb.json](workflows/0552-insertar-valor-mongodb.json)**
  - **Descripción:** Este flujo manual inserta un valor específico en la base de datos MongoDB cuando se ejecuta.
  - **Complejidad:** Baja (3 nodos)

- **[0558-google-drive-download.json](workflows/0558-google-drive-download.json)**
  - **Descripción:** Este flujo automático permite descargar un archivo de Google Drive y guardarlo localmente con un nombre específico.
  - **Complejidad:** Baja (3 nodos)

- **[0597-cocktaildb-json-xml-conversion.json](workflows/0597-cocktaildb-json-xml-conversion.json)**
  - **Descripción:** Este flujo automático convierte los datos de respuesta en JSON de la API CocktailDB a XML.
  - **Complejidad:** Baja (3 nodos)

- **[0637-60_n8n_mysql_purge_older_records.json](workflows/0637-60_n8n_mysql_purge_older_records.json)**
  - **Descripción:** Este flujo elimina automáticamente registros de ejecución en la base de datos MySQL que sean antiguos (más de un mes) para optimizar el almacenamiento.
  - **Complejidad:** Baja (3 nodos)

- **[0671-weather-processing.json](workflows/0671-weather-processing.json)**
  - **Descripción:** Este flujo automático procesa datos meteorológicos utilizando la API de OpenWeatherMap para obtener información sobre temperatura, humedad, velocidad del viento y descripción.
  - **Complejidad:** Baja (3 nodos)

- **[0737-getresponse-trigger-airtable.json](workflows/0737-getresponse-trigger-airtable.json)**
  - **Descripción:** Este flujo automático es desencadenado por un suscriptor en GetResponse para la lista 'qtPk7'. Cuando se produce este evento, n8n recoge los datos del contacto y añade una entrada en Airtable a la tabla especificada.
  - **Complejidad:** Baja (3 nodos)

- **[0763-autopilot-to-airtable-contact.json](workflows/0763-autopilot-to-airtable-contact.json)**
  - **Descripción:** Este flujo automatizado importa automáticamente los contactos nuevos de Autopilot a una tabla específica en Airtable.
  - **Complejidad:** Baja (3 nodos)

- **[0927-digital-ocean-upload-form.json](workflows/0927-digital-ocean-upload-form.json)**
  - **Descripción:** Este flujo permite subir archivos a Digital Ocean Spaces mediante un formulario y mostrar el enlace después de la carga.
  - **Complejidad:** Baja (3 nodos)

- **[1115-filemaker-pagination.json](workflows/1115-filemaker-pagination.json)**
  - **Descripción:** Este flujo procesa una respuesta paginada del Data API de FileMaker para extraer datos específicos de los contactos.
  - **Complejidad:** Baja (3 nodos)

- **[1171-sheets-screenshot-storage.json](workflows/1171-sheets-screenshot-storage.json)**
  - **Descripción:** Este flujo automático captura una pantalla de un sitio web cada vez que se añade una nueva fila en Google Sheets y guarda la imagen en Google Drive.
  - **Complejidad:** Baja (3 nodos)

- **[1175-postgres-data-ingestion.json](workflows/1175-postgres-data-ingestion.json)**
  - **Descripción:** Este flujo automático ejecuta cada minuto una función que genera valores aleatorios y los inserta en una tabla de PostgreSQL.
  - **Complejidad:** Baja (3 nodos)

- **[2570-drive-video-upload.json](workflows/2570-drive-video-upload.json)**
  - **Descripción:** Este flujo automático permite subir videos a Google Drive mediante una Google Apps Script. Comienza con un trigger manual que inicia la ejecución, luego envía los datos de la URL del video (y un secreto) a la web app de Google Script para procesar la subida, y finalmente renombra el archivo recién cargado.
  - **Complejidad:** Baja (3 nodos)

- **[0783-sql-email-query-generator.json](workflows/0783-sql-email-query-generator.json)**
  - **Descripción:** Este flujo traduce preguntas sobre correos electrónicos en consultas SQL y las ejecuta contra la base de datos.
  - **Complejidad:** Baja (2 nodos)

- **[0790-amazon-ads-optimization-flow.json](workflows/0790-amazon-ads-optimization-flow.json)**
  - **Descripción:** Este flujo automatizado analiza reportes de Amazon Ads almacenados en Google Drive, utilizando IA para generar recomendaciones detalladas sobre estrategias de licitación, optimización táctica y escalado presupuestario.
  - **Complejidad:** Baja (2 nodos)

- **[0815-ai-company-researcher-sales.json](workflows/0815-ai-company-researcher-sales.json)**
  - **Descripción:** Este flujo automático utiliza IA junto con herramientas web como SERPAPI o ScrapingBee para investigar propiedades de empresas como dominio, URL de LinkedIn, tipo de mercado (B2B/B2C), planes más económicos, API y ensayos gratuitos, actualizando luego los datos en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[0856-youtube-x-automation.json](workflows/0856-youtube-x-automation.json)**
  - **Descripción:** Este flujo automático busca promover los videos más recientes de una canaleta YouTube específica en X, verificando que cumplan con las limitaciones de caracteres y manteniendo un registro en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[0868-n8n-deployer.json](workflows/0868-n8n-deployer.json)**
  - **Descripción:** Este flujo permite la importación y configuración de un workflow en n8n mediante archivos JSON alojados en una carpeta específica de Google Drive.
  - **Complejidad:** Baja (2 nodos)

- **[0930-linkedin-data-processing.json](workflows/0930-linkedin-data-processing.json)**
  - **Descripción:** Este flujo automatizado utiliza el MCP de Bright Data para extraer información en Markdown desde perfiles o empresas de LinkedIn, procesa esos datos con Google Gemini (modelo PaLM) que los convierte en JSON e incorpora contexto profundo para generar historias detalladas, y finalmente escribe la salida en archivos locales.
  - **Complejidad:** Baja (2 nodos)

- **[0975-airtable-image-analysis.json](workflows/0975-airtable-image-analysis.json)**
  - **Descripción:** Este flujo automatiza el análisis de imágenes capturadas en Airtable para identificar atributos de productos e integra información web, optimizando la gestión de inventario.
  - **Complejidad:** Baja (2 nodos)

- **[0985-youtube-ai-agent-comment-analysis.json](workflows/0985-youtube-ai-agent-comment-analysis.json)**
  - **Descripción:** Este flujo automatizado permite a un agente conversacional de IA interactuar y analizar datos de YouTube, incluyendo la transcripción de videos, recopilación de comentarios, obtención de detalles del canal, evaluación de thumbnails e implementación de gestión con memoria PostgreSQL.
  - **Complejidad:** Baja (2 nodos)

- **[0988-finance-email-parser.json](workflows/0988-finance-email-parser.json)**
  - **Descripción:** Este flujo automático extrae datos de transacciones financieras de correos electrónicos utilizando Gmail como fuente, Google Gemini AI para análisis e interpretación del contenido, y finalmente estructura la información en un formato específico que se envía a una hoja de cálculo de Google. El workflow utiliza etiquetas personalizadas para identificar diferentes tipos de transacciones (facturas, pagos múltiples, etc.) y aplica procesamiento inteligente basado en el remitente del correo.
  - **Complejidad:** Baja (2 nodos)

- **[1092-url-shortener-management.json](workflows/1092-url-shortener-management.json)**
  - **Descripción:** Este flujo automático gestiona URLs cortas mediante la generación de hashes SHA-256 que se almacenan en Airtable, permitiendo crear y verificar referencias únicas para controlar accesos o registros.
  - **Complejidad:** Baja (2 nodos)

- **[1108-notion-project-user-management.json](workflows/1108-notion-project-user-management.json)**
  - **Descripción:** Este flujo permite gestionar la creación de proyectos y usuarios en Notion mediante funciones que procesan datos e integra con webhooks.
  - **Complejidad:** Baja (2 nodos)

- **[1113-swift_codes_extractor.json](workflows/1113-swift_codes_extractor.json)**
  - **Descripción:** Este flujo automático extrae códigos SWIFT de múltiples páginas web en diferentes países, procesa la información normalizada y la guarda en una base de datos MongoDB.
  - **Complejidad:** Baja (2 nodos)

- **[1114-backup-n8n-workflows.json](workflows/1114-backup-n8n-workflows.json)**
  - **Descripción:** Este flujo automático de n8n guarda todas las configuraciones del servidor en archivos JSON almacenados en una repositorio GitHub.
  - **Complejidad:** Baja (2 nodos)

- **[1127-procesamiento_excel.json](workflows/1127-procesamiento_excel.json)**
  - **Descripción:** Este flujo procesa archivos de Excel mediante diversas fuentes y destinos, permite manipular los datos y opcionalmente guardar o subir el archivo modificado.
  - **Complejidad:** Baja (2 nodos)

- **[1156-qualys-thehive-integration.json](workflows/1156-qualys-thehive-integration.json)**
  - **Descripción:** Este flujo automático busca reportes finalizados en Qualys, descarta los ya procesados según un timestamp previo y crea casos en TheHive con sus respectivos archivos adjuntos de reporte.
  - **Complejidad:** Baja (2 nodos)

- **[1166-threads-notion-integration.json](workflows/1166-threads-notion-integration.json)**
  - **Descripción:** Este flujo automático permite obtener publicaciones de la API de Threads, filtrarlas y guardarlas en una base de datos de Notion después de un análisis detallado.
  - **Complejidad:** Baja (2 nodos)

- **[1446-building-your-first-whatsapp-chatbot.json](workflows/1446-building-your-first-whatsapp-chatbot.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos utilizando OpenAI/GPT, Webhook, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (2 nodos)

- **[1480-manipulate-pdf-with-adobe-developer-api.json](workflows/1480-manipulate-pdf-with-adobe-developer-api.json)**
  - **Descripción:** Este flujo permite extracción de datos utilizando OpenAI/GPT, Webhook, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (2 nodos)

- **[1493-scrape-trustpilot-reviews-with-deepseek-openai.json](workflows/1493-scrape-trustpilot-reviews-with-deepseek-openai.json)**
  - **Descripción:** Este flujo permite chatbot, web scraping, análisis de sentimientos, extracción de datos, reportes utilizando OpenAI/GPT, Google Sheets con inteligencia artificial y APIs.
  - **Complejidad:** Baja (2 nodos)

- **[1503-transcribing-bank-statements-to-markdown-ai.json](workflows/1503-transcribing-bank-statements-to-markdown-ai.json)**
  - **Descripción:** Este flujo permite chatbot, transcripción, extracción de datos, generación de contenido utilizando OpenAI/GPT, Webhook, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (2 nodos)

- **[1512-local-multi-llm-testing-performance-tracker.json](workflows/1512-local-multi-llm-testing-performance-tracker.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos, generación de contenido utilizando OpenAI/GPT, Webhook, Google Sheets con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (2 nodos)

- **[2537-agricultural-crops-vector-db.json](workflows/2537-agricultural-crops-vector-db.json)**
  - **Descripción:** Este flujo automatizado carga conjuntamente imágenes de cultivos agrícolas y datos relacionados (como nombres de las plantas) desde Google Cloud Storage, genera embeddings utilizando el modelo Voyage Multimodal de AI y los almacena en una colección vectorial de Qdrant. Además, verifica si la colección ya existe para evitar duplicaciones e incluye un índice en memoria sobre el nombre de la planta (crop_name). La carga se realiza por lotes con un tamaño configurable, permitiendo así la creación eficiente y rápida de índices.
  - **Complejidad:** Baja (2 nodos)

- **[2560-linkedin-profile-collector.json](workflows/2560-linkedin-profile-collector.json)**
  - **Descripción:** Este flujo automatizado utiliza Google Search a través de SerpAPI para encontrar perfiles de LinkedIn relevantes, limpia y estructura la información usando OpenAI, y guarda los resultados en Excel o NocoDB.
  - **Complejidad:** Baja (2 nodos)

- **[2562-shopify_google_sync.json](workflows/2562-shopify_google_sync.json)**
  - **Descripción:** Este flujo sincroniza automáticamente productos de un almacén Shopify a una hoja de cálculo de Google, utilizando GraphQL para extraer datos como título, descripción, etiquetas y precio. Implementa paginación eficiente mediante el uso del cursor.
  - **Complejidad:** Baja (2 nodos)

- **[2605-Colombian-Invoices-Processor.json](workflows/2605-Colombian-Invoices-Processor.json)**
  - **Descripción:** Este flujo automático procesa facturas electrónicas colombianas recibidas por correo electrónico, verificando datos clave como impuestos y subtotales, y los almacena en Google Sheets usando la normativa tributaria del país.
  - **Complejidad:** Baja (2 nodos)

- **[2636-monday-boarditem-hierarchy.json](workflows/2636-monday-boarditem-hierarchy.json)**
  - **Descripción:** Este flujo automático obtiene todos los campos de un elemento de tablero junto con sus relaciones y subelementos para procesar datos completos.
  - **Complejidad:** Baja (2 nodos)

- **[2642-gmail_vector_embeddings_import.json](workflows/2642-gmail_vector_embeddings_import.json)**
  - **Descripción:** Este flujo automatizado importa correos electrónicos de Gmail y los almacena como embeddings vectoriales en PostgreSQL usando PGVector y el modelo Ollama para facilitar búsquedas similares.
  - **Complejidad:** Baja (2 nodos)

- **[2652-youtube-performance-searcher.json](workflows/2652-youtube-performance-searcher.json)**
  - **Descripción:** Este flujo busca los mejores videos de YouTube en el último dos semanas y los almacena en una base de datos PostgreSQL.
  - **Complejidad:** Baja (2 nodos)

- **[2662-vision-based-scraping.json](workflows/2662-vision-based-scraping.json)**
  - **Descripción:** Este flujo utiliza la IA Gemini para extraer datos de capturas de pantalla web e integra los resultados en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2685-email_campaign_generator.json](workflows/2685-email_campaign_generator.json)**
  - **Descripción:** Este flujo automatiza la creación de campañas de correo electrónico personalizadas usando datos de compra y feedback de clientes. Utiliza OpenAI para generar contenido atractivo y decide si enviar un cupón promocional.
  - **Complejidad:** Baja (2 nodos)

- **[2689-printify-update-product.json](workflows/2689-printify-update-product.json)**
  - **Descripción:** Automatiza la actualización de títulos y descripciones de productos en Printify mediante Google Sheets. El workflow utiliza API de Printify para obtener datos de tiendas y productos, procesa cada producto para generar opciones personalizadas de título y descripción usando OpenAI, y las actualiza en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2691-dialpad_syncro.json](workflows/2691-dialpad_syncro.json)**
  - **Descripción:** Este flujo automatiza la sincronización de datos entre Dialpad y Syncro. Recibe una notificación de llamada inbound, busca al cliente en Syncro, crea un ticket si el cliente no existe o actualiza su estado, y registra la información en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2702-meraki-network-monitor.json](workflows/2702-meraki-network-monitor.json)**
  - **Descripción:** Este flujo automático monitorea y analiza los datos de latencia y pérdida de paquetes en redes Meraki para detectar problemas, notificando solo aquellos que superen umbralsthrough Redis.
  - **Complejidad:** Baja (2 nodos)

- **[2703-google_maps_scraper.json](workflows/2703-google_maps_scraper.json)**
  - **Descripción:** Este flujo extrae y procesa datos de Google Maps usando SerpAPI, elimina duplicados, los formatea y actualiza el estado en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2711-google-sheet-ai-agent.json](workflows/2711-google-sheet-ai-agent.json)**
  - **Descripción:** Este flujo utiliza un agente de inteligencia artificial para interactuar con una hoja de cálculo de Google Sheets, permitiendo listar columnas, obtener valores específicos y recuperar información de clientes basado en operaciones definidas.
  - **Complejidad:** Baja (2 nodos)

- **[2725-flujo-automatico-diario.json](workflows/2725-flujo-automatico-diario.json)**
  - **Descripción:** Este flujo automático programa tareas diarias para extraer y procesar información de calendario, LinkedIn y Twitter, enriquecer datos con Clearbit, y enviar un correo electrónico con un resumen personalizado.
  - **Complejidad:** Baja (2 nodos)

- **[2732-vector-chatbot-pinecone.json](workflows/2732-vector-chatbot-pinecone.json)**
  - **Descripción:** Este flujo configura un sistema de recuperación vectorial para responder preguntas basadas en contenido descargado de Google Drive. Utiliza Pinecone como base de datos vectorial y OpenAI para embeddings y respuesta al chat.
  - **Complejidad:** Baja (2 nodos)

- **[2740-automate_ga_reporting.json](workflows/2740-automate_ga_reporting.json)**
  - **Descripción:** Este flujo automático extrae y procesa datos de Google Analytics para generar reportes detallados sobre estadísticas de páginas, resultados de búsquedas y vistas por país, comparando datos semanales. Los resultados se formatean en HTML y se envían por correo electrónico.
  - **Complejidad:** Baja (2 nodos)

- **[2756-automatizacion-facturas-pdf.json](workflows/2756-automatizacion-facturas-pdf.json)**
  - **Descripción:** Este flujo automatiza la extracción de datos desde facturas PDF enviadas por correo electrónico. Utiliza LlamaParse para analizar los documentos y luego extrae información estructurada con OpenAI, finalmente insertando los datos en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2760-empresa_research.json](workflows/2760-empresa_research.json)**
  - **Descripción:** Este flujo automatiza la investigación de empresas mediante el uso de OpenAI y Google Sheets. Recopila información estructurada de sitios web y bases de datos, y actualiza una hoja de cálculo con los resultados.
  - **Complejidad:** Baja (2 nodos)

- **[2763-google-meet-scheduler.json](workflows/2763-google-meet-scheduler.json)**
  - **Descripción:** Este flujo automatiza la gestión de reuniones mediante Google Calendar y Drive. Recupera los registros de reunión, procesa transcripciones con OpenAI, crea eventos calendarísticos y asigna asistentes.
  - **Complejidad:** Baja (2 nodos)

- **[2764-inventory-enricher.json](workflows/2764-inventory-enricher.json)**
  - **Descripción:** Este flujo automático utiliza Airtable para capturar fotos de un inventario, OpenAI para analizar imágenes y agentes de inteligencia artificial para enriquecer datos. Primero, obtiene las filas aplicables de Airtable con fotos no procesadas. Luego, usa el modelo OpenAI para identificar atributos del objeto en la imagen. Un agente de AI utiliza herramientas personalizadas (búsqueda inversa de imágenes y web scraping) para buscar información adicional. Finalmente, sobreescribe los datos en Airtable con los resultados enriquecidos.
  - **Complejidad:** Baja (2 nodos)

- **[2768-file_sync_qdrant.json](workflows/2768-file_sync_qdrant.json)**
  - **Descripción:** Este flujo monitorea un directorio local y sincroniza cambios en los archivos con Qdrant para crear una base de conocimientos usando Mistral AI.
  - **Complejidad:** Baja (2 nodos)

- **[2773-image-embedding_workflow.json](workflows/2773-image-embedding_workflow.json)**
  - **Descripción:** Este flujo descarga una imagen de Google Drive, extrae información de color y genera palabras clave semánticas usando OpenAI para crear un documento embedding, el cual se almacena en un vector store en memoria.
  - **Complejidad:** Baja (2 nodos)

- **[2782-sync-workflows.json](workflows/2782-sync-workflows.json)**
  - **Descripción:** Este flujo automatiza la sincronización de workflows entre n8n y GitLab. Recupera los workflows de n8n, verifica su estado en GitLab y actualiza o crea nuevos archivos JSON según las diferencias detectadas.
  - **Complejidad:** Baja (2 nodos)

- **[2784-supabase-vector-store.json](workflows/2784-supabase-vector-store.json)**
  - **Descripción:** Este flujo configura una base de datos vectorial en Supabase para almacenar y recuperar documentos con embeddings de OpenAI, permitiendo realizar búsquedas semánticas y contestar preguntas basadas en el contenido.
  - **Complejidad:** Baja (2 nodos)

- **[2791-notion-workflow-generator.json](workflows/2791-notion-workflow-generator.json)**
  - **Descripción:** Este flujo genera un workflow personalizado de n8n para bases de datos de Notion a partir de una URL proporcionada por el usuario. Utiliza agentes de lenguaje y validación para asegurar la correcta estructura del JSON.
  - **Complejidad:** Baja (2 nodos)

- **[2797-adobe-pdf-processing.json](workflows/2797-adobe-pdf-processing.json)**
  - **Descripción:** Este flujo automático implementa una integración con la API de Adobe para procesar archivos PDF, realizando tareas como subir un archivo, enviar una query de procesamiento y descargar el resultado. Utiliza credenciales personalizadas para autenticación y gestiona diferentes estados del proceso.
  - **Complejidad:** Baja (2 nodos)

- **[2821-automatizacion-facturas-outlook.json](workflows/2821-automatizacion-facturas-outlook.json)**
  - **Descripción:** Este flujo automatiza la gestión de facturas desde una cuenta de Outlook, clasificando mensajes para detectar y descargar attachments que sean facturas emitidas a la empresa. Utiliza Google Gemini para verificar si los archivos adjuntos son facturas relevantes y extraer información clave, posteriormente registra estos datos en una hoja de cálculo de Excel.
  - **Complejidad:** Baja (2 nodos)

- **[2826-client-usage-tracker.json](workflows/2826-client-usage-tracker.json)**
  - **Descripción:** Este flujo registra el uso de tokens y costos de clientes al utilizar un servicio de extracción de datos de CV con OpenAI, almacenando los datos en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2831-rss_to_gsheet_cleaner.json](workflows/2831-rss_to_gsheet_cleaner.json)**
  - **Descripción:** Este flujo automatiza la actualización y manejo de entradas RSS en Google Sheets. Primero, utiliza un temporizador para leer los enlaces desde una hoja de cálculo, luego extrae las noticias correspondientes y las procesa. Filtros eliminan entradas antiguas (más de 3 días) y las nuevas se guardan con un tiempo de espera para evitar bloqueos. Entradas viejas son eliminadas después de cierto tiempo.
  - **Complejidad:** Baja (2 nodos)

- **[2840-google-drive-deduplicate.json](workflows/2840-google-drive-deduplicate.json)**
  - **Descripción:** Este flujo automatiza la deduplicación de archivos en Google Drive. Identifica duplicados basándose en el checksum md5 y gestiona su eliminación o renombrado según las configuraciones de Keep (first/last) y Action (trash/flag).
  - **Complejidad:** Baja (2 nodos)

- **[2842-automated-purchase-order-processing.json](workflows/2842-automated-purchase-order-processing.json)**
  - **Descripción:** Este flujo automatiza la importación y procesamiento de órdenes de compra desde Outlook. Convierte archivos XLSX a formato legible por LLMs, extrae detalles usando IA y realiza validaciones.
  - **Complejidad:** Baja (2 nodos)

- **[2845-linkedin-enrichment-icebreaker.json](workflows/2845-linkedin-enrichment-icebreaker.json)**
  - **Descripción:** Este flujo automático en n8n permite extraer y enriquecer datos de perfiles de LinkedIn usando Bright Data, generar icebreakers personalizados con el modelo Claude de Anthropic y actualizar una hoja de Google Sheets con la información resultante.
  - **Complejidad:** Baja (2 nodos)

- **[2878-n8n-backup-workflows.json](workflows/2878-n8n-backup-workflows.json)**
  - **Descripción:** Este flujo automatiza la copia de seguridad diaria de los workflows de n8n en Google Drive. Busca y procesa todos los workflows, y si no hay un archivo existente, crea uno nuevo; si ya existe, lo actualiza con la nueva información.
  - **Complejidad:** Baja (2 nodos)

- **[2884-instagram-post-automation.json](workflows/2884-instagram-post-automation.json)**
  - **Descripción:** Automatiza la creación de publicaciones en Instagram mediante Google Sheets y herramientas AI. Incluye desde la generación de conceptos de contenido hasta la publicación final.
  - **Complejidad:** Baja (2 nodos)

- **[2904-ai-ready-vector-datasets.json](workflows/2904-ai-ready-vector-datasets.json)**
  - **Descripción:** Este flujo crea conjuntos de datos vectoriales listos para LLMs usando Bright Data, Gemini y Pinecone. Realiza extracción de información, formateo estructurado y persistencia en una base de vectores.
  - **Complejidad:** Baja (2 nodos)

- **[2923-dashboard-metricas.json](workflows/2923-dashboard-metricas.json)**
  - **Descripción:** Este flujo automatiza la actualización de un dashboard que recopila y muestra estadísticas y métricas desde diversas fuentes como Docker, npm, GitHub y Product Hunt. Utiliza Cron para programar ejecuciones periódicas, extrae datos mediante HTTP requests, procesa y formatea los resultados, y actualiza_WIDGETS en un host dashboard con autenticación.
  - **Complejidad:** Baja (2 nodos)

- **[2926-google-sheets-to-postgres.json](workflows/2926-google-sheets-to-postgres.json)**
  - **Descripción:** Este flujo automatiza la importación de datos desde Google Sheets a PostgreSQL. Analiza dinámicamente los datos para detectar tipos y generar esquemas SQL, crea tablas si no existen y realiza inserciones con formato adecuado.
  - **Complejidad:** Baja (2 nodos)

- **[2928-sitemap-index-automatizado.json](workflows/2928-sitemap-index-automatizado.json)**
  - **Descripción:** Este flujo automatiza la indexación de URLs en Google Search Console usando sitemap.xml. Extrae URLs de los archivos sitemap, verifica su estado y actualiza las que han sido modificadas o no están indexadas.
  - **Complejidad:** Baja (2 nodos)

- **[2955-auto-content-generator.json](workflows/2955-auto-content-generator.json)**
  - **Descripción:** Este flujo automatiza la creación de contenido multimedia basado en datos de Google Sheets. Genera imágenes y videos cinemáticos con textos promocionales, agrega sonidos ambientales, y publica el resultado en YouTube.
  - **Complejidad:** Baja (2 nodos)

- **[2967-sql-agent-scheme.json](workflows/2967-sql-agent-scheme.json)**
  - **Descripción:** Flujo que utiliza un agente de IA para generar consultas SQL basadas en esquema de base de datos guardando la estructura localmente y usando OpenAI para formular sentencias SQL.
  - **Complejidad:** Baja (2 nodos)

- **[2968-image-embedder.json](workflows/2968-image-embedder.json)**
  - **Descripción:** Este flujo automatiza la creación de embeddings de imágenes mediante resumen textual. Descarga una imagen desde Google Drive, extrae información de colores y genera palabras clave usando OpenAI, luego combina estos datos para crear un documento que se almacena en un vector store.
  - **Complejidad:** Baja (2 nodos)

- **[2970-autoclip-video-generator.json](workflows/2970-autoclip-video-generator.json)**
  - **Descripción:** Este flujo automático genera clips de video seleccionando aleatoriamente entre vídeos y música de Google Drive, yuxtapone citas y luego los sube a YouTube.
  - **Complejidad:** Baja (2 nodos)

- **[2983-hacker-news-jobs-scraper.json](workflows/2983-hacker-news-jobs-scraper.json)**
  - **Descripción:** Este flujo extrae y procesa información de ofertas laborales publicadas en Hacker News utilizando su API y_algolia, estructura los datos con OpenAI y los exporta a Airtable.
  - **Complejidad:** Baja (2 nodos)

- **[2987-gestion-solicitudes-AI.json](workflows/2987-gestion-solicitudes-AI.json)**
  - **Descripción:** Flujo que automatiza la gestión de solicitudes de empleo usando formularios y herramientas de inteligencia artificial para extraer información, clasificar documentos y almacenar datos en Airtable.
  - **Complejidad:** Baja (2 nodos)

- **[3004-voice-chatbot-rag-qdrant.json](workflows/3004-voice-chatbot-rag-qdrant.json)**
  - **Descripción:** Este flujo implementa un chatbot de voz que utiliza RAG (Retrieval-Augmented Generation) con ElevenLabs y OpenAI para responder preguntas usando una base de datos vectorial en Qdrant.
  - **Complejidad:** Baja (2 nodos)

- **[3014-factura-extraccion-llamaparse.json](workflows/3014-factura-extraccion-llamaparse.json)**
  - **Descripción:** Este flujo automático extrae información de facturas en formato PDF usando LlamaParse y OpenAI. Detecta correos con adjuntos PDF, procesa los documentos para obtener datos estructurados y los almacena en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[3034-google-analytics-seo-analysis.json](workflows/3034-google-analytics-seo-analysis.json)**
  - **Descripción:** Este flujo automático recopila y analiza datos de Google Analytics para una página web, comparando estadísticas semanales como páginas vistas, usuarios activos y tasas de participación. Luego, envía esta información a un modelo de lenguaje A.I. para obtener recomendaciones SEO y guarda los resultados en Baserow.
  - **Complejidad:** Baja (2 nodos)

- **[3060-manipula-pdf-adobe.json](workflows/3060-manipula-pdf-adobe.json)**
  - **Descripción:** Este flujo maneja la manipulación de archivos PDF utilizando la API de Adobe Services. Realiza autenticación, carga un archivo PDF, procesa solicitudes específicas (como extracción) y espera la finalización del proceso antes de descargar los resultados.
  - **Complejidad:** Baja (2 nodos)

- **[3064-outlook-email-ai-assistant.json](workflows/3064-outlook-email-ai-assistant.json)**
  - **Descripción:** Este flujo utiliza Microsoft Outlook para leer correos electrónicos no marcados yWithout categorías, procesa su contenido con OpenAI para categorizarlos, actualiza su importancia y asigna categorías. También integra contactos de Monday.com y Airtable para mejorar la contextualización.
  - **Complejidad:** Baja (2 nodos)

- **[3071-line-file-save-to-google-drive.json](workflows/3071-line-file-save-to-google-drive.json)**
  - **Descripción:** Este flujo automatiza la descarga de archivos desde LINE, los organiza en Google Drive según configuración y registra detalles en una hoja de cálculo.
  - **Complejidad:** Baja (2 nodos)

- **[3081-whatsapp-ai-chatbot.json](workflows/3081-whatsapp-ai-chatbot.json)**
  - **Descripción:** Este flujo implementa un chatbot de WhatsApp que utiliza tecnología RAG (Retrieval-Augmented Generation) para responder consultas usando OpenAI y Qdrant. Recoge documentos desde Google Drive, los vectoriza con OpenAI, almacena en Qdrant y usa el agente AI para contestar preguntas basadas en ellos.
  - **Complejidad:** Baja (2 nodos)

- **[3084-notion-chatbot-generator.json](workflows/3084-notion-chatbot-generator.json)**
  - **Descripción:** Este flujo genera un asistente de chatbot personalizado para bases de datos de Notion, creando una workflow adaptada al esquema proporcionado. Analiza la URL de la base de datos, simplifica los objetos y utiliza agentes de lenguaje para modificar el JSON del workflow según las necesidades específicas.
  - **Complejidad:** Baja (2 nodos)

- **[3091-obsidian-podcast-flow.json](workflows/3091-obsidian-podcast-flow.json)**
  - **Descripción:** Flujo que convierte notas de Obsidian en audios para podcasts usando OpenAI y almacena datos en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[3097-mcp-supabase-agent.json](workflows/3097-mcp-supabase-agent.json)**
  - **Descripción:** Este flujo implementa un agente de LangChain con capacidades de recuperación de vectores y embeddings de OpenAI, usando Supabase para almacenar y gestionar datos como mensajes, tareas y estado.
  - **Complejidad:** Baja (2 nodos)

- **[3101-update-printify-products.json](workflows/3101-update-printify-products.json)**
  - **Descripción:** Este flujo actualiza títulos y descripciones de productos en Printify usando OpenAI para optimizar contenido y Google Sheets para la gestión.
  - **Complejidad:** Baja (2 nodos)

- **[3105-generate-sql-from-schema.json](workflows/3105-generate-sql-from-schema.json)**
  - **Descripción:** Este flujo genera consultas SQL basadas en un esquema de base de datos usando inteligencia artificial. Extrae información de la estructura de las tablas y utiliza el modelo OpenAI para crear sentencias SQL sin necesidad de acceder a los datos reales.
  - **Complejidad:** Baja (2 nodos)

- **[3114-chatbot_personal_shopper.json](workflows/3114-chatbot_personal_shopper.json)**
  - **Descripción:** Este flujo implementa un chatbot personal shopper para WooCommerce que utiliza RAG con Google Drive y openAI. Analiza mensajes de chat para buscar productos o responder preguntas generales usando vectores almacenados en Qdrant.
  - **Complejidad:** Baja (2 nodos)

- **[3118-Vision-Scraping-Agent.json](workflows/3118-Vision-Scraping-Agent.json)**
  - **Descripción:** Este flujo automatiza la extracción de datos web utilizando vision artificial con Google Sheets, ScrapingBee y Gemini. Realiza capturas de pantalla completas de páginas web, utiliza el modelo Gemini para extraer información visualmente, y en caso de falla, recurre a herramientas HTML para asegurar datos precisos.
  - **Complejidad:** Baja (2 nodos)

- **[3119-batch_crops_qdrant.json](workflows/3119-batch_crops_qdrant.json)**
  - **Descripción:** Este flujo carga un conjunto de datos de imágenes agrícolas en Qdrant usando embeddings de Voyage AI y Google Cloud Storage. Primero verifica si la colección existe, crea una nueva si es necesario, luego procesa las imágenes en tandas y las sube al vectorstore.
  - **Complejidad:** Baja (2 nodos)

- **[3162-google-analytics-to-ai-seo-analysis.json](workflows/3162-google-analytics-to-ai-seo-analysis.json)**
  - **Descripción:** Este flujo recopila datos de analítica web, procesa y envía información a un modelo de IA para análisis SEO comparativo semanal, guardando los resultados en Baserow.
  - **Complejidad:** Baja (2 nodos)

- **[3216-aplicacion_cv_automatizada.json](workflows/3216-aplicacion_cv_automatizada.json)**
  - **Descripción:** Flujo de aplicación para la gestión de CV y formulario de solicitud optimizado con IA, que incluye validación de documentos, extracción de información, y almacenamiento en Airtable.
  - **Complejidad:** Baja (2 nodos)

- **[3232-automated-backup.json](workflows/3232-automated-backup.json)**
  - **Descripción:** Este flujo automatiza la copia de seguridad de trabajos en GitHub usando n8n. Almacena los workflows como archivos JSON en un repositorio designado.
  - **Complejidad:** Baja (2 nodos)

- **[3256-github-backup-workflow.json](workflows/3256-github-backup-workflow.json)**
  - **Descripción:** Este flujo automatiza la copia de seguridad de trabajos en GitHub al comparar y actualizar archivos JSON. Utiliza un bucle para procesar cada instancia, verifica diferencias entre versiones y gestiona operaciones de creación o edición según el estado.
  - **Complejidad:** Baja (2 nodos)

- **[3263-ai-resume-screening.json](workflows/3263-ai-resume-screening.json)**
  - **Descripción:** Flujo automático para evaluar currículos en base a una descripción de empleo utilizando inteligencia artificial. Analiza, clasifica y organiza candidatos en carpetas según su perfil.
  - **Complejidad:** Baja (2 nodos)

- **[3270-call-processing-flow.json](workflows/3270-call-processing-flow.json)**
  - **Descripción:** Este flujo automatiza la extracción y procesamiento de datos de llamadas de venta, integrando información complementaria como competidores y listas de integraciones para enriquecer los transcritos antes de enviarlos a un sistema de inteligencia artificial.
  - **Complejidad:** Baja (2 nodos)

- **[3285-mistral-ocr-parsing.json](workflows/3285-mistral-ocr-parsing.json)**
  - **Descripción:** Flujo que utiliza Mistral OCR para analizar documentos y imágenes subidas a Google Drive. Primero carga archivos desde Google Drive, luego los envía a Mistral Cloud para obtener URLs firmadas, procesa el OCR con esas URLs y finalmente realiza análisis de documento o imagen utilizando diferentes modelos (chat completions).
  - **Complejidad:** Baja (2 nodos)

- **[3290-aprendizaje_idiomas.json](workflows/3290-aprendizaje_idiomas.json)**
  - **Descripción:** Este flujo automatiza la creación de tarjetas flash para aprendizaje de idiomas. Utiliza Google Sheets para almacenar palabras, traduce al chino usando Google Translate, genera fonética y oraciones con un agente AI, busca imágenes en Pexels y las sube a Google Drive.
  - **Complejidad:** Baja (2 nodos)

- **[3297-dropbox-watch-files.json](workflows/3297-dropbox-watch-files.json)**
  - **Descripción:** Este flujo monitorea cambios en dos carpetas de Dropbox (/z_Apps/a_iphone/RecUp Memos/ y /z_Apps/auphonic/whisper) para detectar nuevos archivos o carpetas. Utiliza NocoDB para almacenar los metadatos de los archivos, filtra aquellos que no han sido procesados antes y ejecuta flujos específicos para cada tipo de archivo detectado.
  - **Complejidad:** Baja (2 nodos)

- **[3305-seo-wordpress-generator.json](workflows/3305-seo-wordpress-generator.json)**
  - **Descripción:** Este flujo automático genera contenido optimizado para SEO para WordPress utilizando investigación de Perplexity y OpenAI. Incluye creación de títulos, slug y metadatos, desarrollo de HTML estructurado, y publicación en el blog.
  - **Complejidad:** Baja (2 nodos)

- **[3320-supabase-vector-flow.json](workflows/3320-supabase-vector-flow.json)**
  - **Descripción:** Este flujo integra Supabase con n8n para realizar inserciones, actualizaciones y recuperaciones en una base de datos vectoriales, utilizando embeddings de OpenAI y un motor de vectores optimizado para búsquedas eficientes.
  - **Complejidad:** Baja (2 nodos)

- **[3340-transcribe-bank-statements.json](workflows/3340-transcribe-bank-statements.json)**
  - **Descripción:** Este flujo transforma un estado de cuenta bancario en formato PDF a markdown utilizando el modelo Gemini Vision AI para una fácil extracción de datos.
  - **Complejidad:** Baja (2 nodos)

- **[3344-scrape-trustpilot-sentiment.json](workflows/3344-scrape-trustpilot-sentiment.json)**
  - **Descripción:** Este flujo extrae reseñas de Trustpilot usando DeepSeek, analiza su sentimiento con OpenAI y las registra en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[0047-calendly-notion-auto.json](workflows/0047-calendly-notion-auto.json)**
  - **Descripción:** Este flujo automatizado crea un nuevo registro en una base de datos Notion cada vez que se crea un 'invitee' (invitado) en Calendly.
  - **Complejidad:** Baja (2 nodos)

- **[0098-line-chatbot-memory.json](workflows/0098-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite que un mensaje recibido en el webhook se utilice para crear un recurso en Netlify usando datos dinámicos.
  - **Complejidad:** Baja (2 nodos)

- **[0169-onfleet-task-from-google-drive.json](workflows/0169-onfleet-task-from-google-drive.json)**
  - **Descripción:** Este flujo automático crea una tarea en Onfleet cuando un archivo específico en Google Drive es actualizado.
  - **Complejidad:** Baja (2 nodos)

- **[0179-bubble-data-access.json](workflows/0179-bubble-data-access.json)**
  - **Descripción:** Este flujo permite realizar una solicitud HTTP autenticada para acceder datos de usuarios desde la API de Bubble.
  - **Complejidad:** Baja (2 nodos)

- **[0243-google-drive-notion.json](workflows/0243-google-drive-notion.json)**
  - **Descripción:** Este flujo automático crea una página en la base de datos de Notion cuando se sube un nuevo archivo a una carpeta específica de Google Drive.
  - **Complejidad:** Baja (2 nodos)

- **[0332-strava-beeminder-datapoint-flow.json](workflows/0332-strava-beeminder-datapoint-flow.json)**
  - **Descripción:** Este flujo agrega un punto de datos en Beeminder cuando se crea una nueva actividad en Strava.
  - **Complejidad:** Baja (2 nodos)

- **[0382-webhook-google-sheets.json](workflows/0382-webhook-google-sheets.json)**
  - **Descripción:** Este flujo lee datos de una hoja específica de Google Sheets cuando se recibe una solicitud a través del webhook.
  - **Complejidad:** Baja (2 nodos)

- **[0468-syncro-clockify-tasks.json](workflows/0468-syncro-clockify-tasks.json)**
  - **Descripción:** Este flujo automático recibe datos vía webhook y los usa para crear tareas en Clockify.
  - **Complejidad:** Baja (2 nodos)

- **[0538-postgres-query.json](workflows/0538-postgres-query.json)**
  - **Descripción:** Este flujo automático permite ejecutar un comando SQL de selección en una base de datos PostgreSQL mediante una activación manual.
  - **Complejidad:** Baja (2 nodos)

- **[0557-facebook_datos_basicos.json](workflows/0557-facebook_datos_basicos.json)**
  - **Descripción:** Este flujo obtiene manualmente los datos personales básicos (nombre y apellido) del usuario actual en Facebook mediante una llamada a la API.
  - **Complejidad:** Baja (2 nodos)

- **[0560-trigger-cockpit-sample.json](workflows/0560-trigger-cockpit-sample.json)**
  - **Descripción:** Este flujo automático permite iniciar un proceso manual y conectarlo inmediatamente con el nodo de Cockpit para visualizar datos de la colección 'samplecollection'.
  - **Complejidad:** Baja (2 nodos)

- **[0566-hacker-news-trigger.json](workflows/0566-hacker-news-trigger.json)**
  - **Descripción:** Este flujo automático permite ejecutar una acción manuala para obtener datos de todas las categorías de Hacker News.
  - **Complejidad:** Baja (2 nodos)

- **[0586-typeform-seleccion-automatizada.json](workflows/0586-typeform-seleccion-automatizada.json)**
  - **Descripción:** Este flujo automatizado permite registrar selecciones de formulario Typeform en Airtable.
  - **Complejidad:** Baja (2 nodos)

- **[0592-monday-board-data.json](workflows/0592-monday-board-data.json)**
  - **Descripción:** Este flujo ejecuta una acción manual en n8n para obtener datos de un tablero específico en Monday.com.
  - **Complejidad:** Baja (2 nodos)

- **[0593-line-chatbot-memory.json](workflows/0593-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada mediante la persistencia en Redis.
  - **Complejidad:** Baja (2 nodos)

- **[0594-spacex-graphql-query.json](workflows/0594-spacex-graphql-query.json)**
  - **Descripción:** Este flujo manual consulta la API de SpaceX mediante GraphQL para obtener detalles sobre los últimos lanzamientos y datos de las naves espaciales.
  - **Complejidad:** Baja (2 nodos)

- **[0595-box-folder-execution.json](workflows/0595-box-folder-execution.json)**
  - **Descripción:** Este flujo ejecuta automáticamente una acción sobre una carpeta específica de Box cuando se hace clic en el botón 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[0600-one-drive-folder-creation.json](workflows/0600-one-drive-folder-creation.json)**
  - **Descripción:** Este flujo manual permite crear una carpeta en OneDrive al hacer clic en el botón 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[0601-excel-trigger.json](workflows/0601-excel-trigger.json)**
  - **Descripción:** Este flujo ejecuta un proceso manual al hacer clic en el botón de inicio, que luego consulta todos los datos disponibles a través del conector Microsoft Excel.
  - **Complejidad:** Baja (2 nodos)

- **[0609-trigger-leer-imagen-binaria.json](workflows/0609-trigger-leer-imagen-binaria.json)**
  - **Descripción:** Este flujo permite cargar archivos binarios como imágenes al hacer clic en el desencadenador.
  - **Complejidad:** Baja (2 nodos)

- **[0610-read-images-trigger.json](workflows/0610-read-images-trigger.json)**
  - **Descripción:** Este flujo automático permite a un usuario iniciar manualmente una ejecución, la cual lee archivos binarios (específicamente imágenes jpg) desde el directorio /data/lol.
  - **Complejidad:** Baja (2 nodos)

- **[0674-transformador-array.json](workflows/0674-transformador-array.json)**
  - **Descripción:** Este flujo automatizado inicia con un nodo que genera datos estáticos en forma de array y luego utiliza una función personalizada para transformar cada elemento del array en un objeto individual JSON.
  - **Complejidad:** Baja (2 nodos)

- **[0709-openweathermap-weather.json](workflows/0709-openweathermap-weather.json)**
  - **Descripción:** Este flujo automático permite al usuario ejecutar un proceso manual que consulta los datos meteorológicos actuales de la ciudad especificada (en este caso, Berlin) mediante el servicio OpenWeatherMap.
  - **Complejidad:** Baja (2 nodos)

- **[0742-typeform-demio-registration.json](workflows/0742-typeform-demio-registration.json)**
  - **Descripción:** Este flujo automatizado activa el registro en Demio con datos proporcionados por un formulario de Typeform.
  - **Complejidad:** Baja (2 nodos)

- **[0769-sql-query-execution.json](workflows/0769-sql-query-execution.json)**
  - **Descripción:** Este flujo automático permite ejecutar una consulta SQL en base de datos Microsoft SQL mediante un desencadenador manual.
  - **Complejidad:** Baja (2 nodos)

- **[1193-line-chatbot-memory.json](workflows/1193-line-chatbot-memory.json)**
  - **Descripción:** Este flujo procesa datos de usuario para mantener el contexto en conversaciones.
  - **Complejidad:** Baja (2 nodos)

- **[0003-line-chatgpt-image-flow.json](workflows/0003-line-chatgpt-image-flow.json)**
  - **Descripción:** Este flujo automático procesa solicitudes de generación de imágenes a través del chatbot LINE y los almacena en Google Drive como archivos binarios y en una hoja de cálculo con detalles incluyendo prompts, costos estimados e información relevante.
  - **Complejidad:** Baja (1 nodos)

- **[0205-workflow-merge-demo.json](workflows/0205-workflow-merge-demo.json)**
  - **Descripción:** Este flujo demuestra cómo el nodo Merge de n8n combina datos de diferentes fuentes usando diferentes modos de unión, mostrando ejemplos desde ingredientes hasta la formación de bandas.
  - **Complejidad:** Baja (1 nodos)

- **[0383-workflow-estado.json](workflows/0383-workflow-estado.json)**
  - **Descripción:** Este flujo automático ejecuta un workflow principal con intervalos de disparo y verifica en Redis si el workflow está actualmente en ejecución para evitar múltiples instancias concurrentes.
  - **Complejidad:** Baja (1 nodos)

- **[0425-n8n-flujos-backup-github.json](workflows/0425-n8n-flujos-backup-github.json)**
  - **Descripción:** Este flujo automático respalda workflows de n8n en un repositorio git verificando cambios y actualizando archivos.
  - **Complejidad:** Baja (1 nodos)

- **[0803-n8n-hr-cv-automation.json](workflows/0803-n8n-hr-cv-automation.json)**
  - **Descripción:** Este flujo automático analiza currículums de candidatos mediante la extracción y resumen de datos clave usando modelos de IA.
  - **Complejidad:** Baja (1 nodos)

- **[0806-stock-fundamental-ai-analyzer.json](workflows/0806-stock-fundamental-ai-analyzer.json)**
  - **Descripción:** Este flujo automático analiza datos de fondos utilizando embeddings de OpenAI, procesamiento con LangChain y almacenamiento vectorial en Qdrant para responder preguntas sobre análisis fundamental de acciones.
  - **Complejidad:** Baja (1 nodos)

- **[0824-rag-financial-report-gen.json](workflows/0824-rag-financial-report-gen.json)**
  - **Descripción:** Este flujo utiliza el sistema RAG para analizar informes de rentabilidad corporativa basados en documentos históricos almacenados como embeddings en Pinecone. Procesa información mediante modelos de Google Gemini y OpenAI, sintetiza los datos con un agente especializado e integra todo en un informe markdown que se guarda automáticamente en Google Docs.
  - **Complejidad:** Baja (1 nodos)

- **[0841-bright-data-gemini-hotel-summarizer.json](workflows/0841-bright-data-gemini-hotel-summarizer.json)**
  - **Descripción:** Este flujo automático extrae datos de hoteles desde Bing Copilot usando la API de Bright Data y utiliza Google Gemini AI para formatearlos en estructura JSON y generar resúmenes concisos.
  - **Complejidad:** Baja (1 nodos)

- **[0846-workflow-pinecone-openai.json](workflows/0846-workflow-pinecone-openai.json)**
  - **Descripción:** Este flujo carga documentos desde Google Drive en un vector store de Pinecone utilizando embeddings de OpenAI para luego permitir la recuperación de información mediante cadenas de pregunta-respuesta.
  - **Complejidad:** Baja (1 nodos)

- **[0855-eliminar-fondos-google-drive.json](workflows/0855-eliminar-fondos-google-drive.json)**
  - **Descripción:** Este flujo elimina automáticamente los fondos de imágenes en Google Drive usando la API de Photroom.
  - **Complejidad:** Baja (1 nodos)

- **[0871-line-chatbot-memory.json](workflows/0871-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada con los usuarios al procesar mensajes tanto en texto como imágenes, extrayendo información relevante sobre estados de cuenta y datos personales para luego insertarla en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[0890-Google_Sheet_AI_Interface.json](workflows/0890-Google_Sheet_AI_Interface.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con una hoja de Google mediante funciones personalizadas, optimizando la consulta y gestión de datos.
  - **Complejidad:** Baja (1 nodos)

- **[0944-obsidian-email-sender.json](workflows/0944-obsidian-email-sender.json)**
  - **Descripción:** Este flujo automático permite enviar correos electrónicos desde Obsidian utilizando webhooks, procesando correctamente los archivos adjuntos mediante codificación base64 y añadiendo la información del remitente.
  - **Complejidad:** Baja (1 nodos)

- **[0959-squarespace-backup.json](workflows/0959-squarespace-backup.json)**
  - **Descripción:** Este flujo automático permite guardar las personalizaciones de Squarespace (código de inyecciones) en archivos HTML dentro de un repositorio de GitHub, manteniendo el contexto por dominio y realizando respaldos cada hora.
  - **Complejidad:** Baja (1 nodos)

- **[0989-vertex-ai-pdf-image-extractor.json](workflows/0989-vertex-ai-pdf-image-extractor.json)**
  - **Descripción:** Este flujo automático permite extraer texto de archivos PDF e imágenes usando Vertex AI (Gemini) y convertirlos en CSV para almacenar la información.
  - **Complejidad:** Baja (1 nodos)

- **[0991-umami-analytics-ai.json](workflows/0991-umami-analytics-ai.json)**
  - **Descripción:** Este flujo analítico procesa datos de tráfico web desde Umami utilizando múltiples API calls y transformaciones JavaScript para extraer métricas clave como visitas e impresiones. Luego envía estos resultados junto con solicitudes a un modelo AI de OpenRouter para generar análisis detallado, que finalmente se almacena en Baserow.
  - **Complejidad:** Baja (1 nodos)

- **[1001-flux-image-generator.json](workflows/1001-flux-image-generator.json)**
  - **Descripción:** Este flujo automatizado permite generar imágenes con estilos predefinidos (como AI Dystopia, Hyper-Surreal Escape, etc.) mediante la API de huggingface. Después de que un usuario completa un formulario proporcionando un prompt y selecciona un estilo, el sistema llama al modelo correspondiente, sube la imagen generada a S3 y muestra el resultado en una página web.
  - **Complejidad:** Baja (1 nodos)

- **[1237-bright-data-gemini-scraping-agent.json](workflows/1237-bright-data-gemini-scraping-agent.json)**
  - **Descripción:** Este flujo automático utiliza un asistente de IA basado en Google Gemini para analizar consultas sobre scraping web. Luego delega la tarea a herramientas del MCP Client (Bright Data) que extraen datos desde URLs especificadas mediante webhooks, manteniendo el contexto con una memoria buffer y almacenando resultados en archivos.
  - **Complejidad:** Baja (1 nodos)

- **[1396-ai-product-data-processor.json](workflows/1396-ai-product-data-processor.json)**
  - **Descripción:** Procesa datos de productos con ayuda de IA.
  - **Complejidad:** Baja (1 nodos)

- **[1402-edi-processor.json](workflows/1402-edi-processor.json)**
  - **Descripción:** Procesa archivos EDI de intercambio electrónico de datos.
  - **Complejidad:** Baja (1 nodos)

- **[1453-convert-url-html-to-markdown.json](workflows/1453-convert-url-html-to-markdown.json)**
  - **Descripción:** Este flujo permite automatización, web scraping, extracción de datos utilizando Webhook, Airtable con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (1 nodos)

- **[1468-fetch-dynamic-prompts-from-github.json](workflows/1468-fetch-dynamic-prompts-from-github.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos con inteligencia artificial y APIs.
  - **Complejidad:** Baja (1 nodos)

- **[1489-reconcile-rent-payments-with-local-excel-openai.json](workflows/1489-reconcile-rent-payments-with-local-excel-openai.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos, generación de contenido, reportes utilizando OpenAI/GPT, Excel con inteligencia artificial y APIs.
  - **Complejidad:** Baja (1 nodos)

- **[2541-agricultural-anomaly-detector.json](workflows/2541-agricultural-anomaly-detector.json)**
  - **Descripción:** Este flujo analiza imágenes de cultivos para detectar si contienen ejemplares no conocidos, utilizando embeddings multimodales y una base de datos vectorial Qdrant.
  - **Complejidad:** Baja (1 nodos)

- **[2546-sql-agent-visualizacion.json](workflows/2546-sql-agent-visualizacion.json)**
  - **Descripción:** Este flujo automatizado permite a un AI Agent interactuar con bases de datos mediante consultas SQL y generar visualizaciones usando Chart.js y Quickchart.io basadas en la necesidad del usuario. El clasificador textual decide si se requiere una representación gráfica para mejorar la comprensión de los resultados.
  - **Complejidad:** Baja (1 nodos)

- **[2587-youtube-sentiment-analyzer.json](workflows/2587-youtube-sentiment-analyzer.json)**
  - **Descripción:** Este flujo analiza automáticamente los comentarios de videos de YouTube a partir de una lista en Google Sheets utilizando la API de YouTube y la IA de OpenAI para categorizarlos como positivos, neutros o negativos.
  - **Complejidad:** Baja (1 nodos)

- **[2592-multipage-scraper.json](workflows/2592-multipage-scraper.json)**
  - **Descripción:** Este flujo automático permite extraer y almacenar en Google Drive el contenido de múltiples páginas web a partir del archivo sitemap.xml usando la API de Jina.ai para realizar búsquedas inteligentes.
  - **Complejidad:** Baja (1 nodos)

- **[2596-image-to-3d-conversion.json](workflows/2596-image-to-3d-conversion.json)**
  - **Descripción:** Este flujo automático permite convertir una imagen en un modelo 3D (.glb) utilizando la API de Fal.ai y luego guardar el resultado en Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[2601-facturacion-automatizada.json](workflows/2601-facturacion-automatizada.json)**
  - **Descripción:** Este flujo automatizado descarga archivos adjuntos de correos electrónicos no leídos en Gmail y los guarda en Google Drive. Luego utiliza OpenAI para extraer datos clave de las facturas (fecha, descripción, precio total), que se almacenan en un esquema estructurado y finalmente se incorporan a una hoja de cálculo.
  - **Complejidad:** Baja (1 nodos)

- **[2617-woocommerce-ai-product-importer.json](workflows/2617-woocommerce-ai-product-importer.json)**
  - **Descripción:** Este flujo de trabajo automatiza la importación de productos en WooCommerce a través de Google Sheets. Analiza los detalles del producto para generar metatítulos y meta-descripciones SEO optimizadas, las crea inmediatamente en el catálogo WordPress e inserta esta información directamente en una hoja de cálculo.
  - **Complejidad:** Baja (1 nodos)

- **[2634-opensea-nft-agent.json](workflows/2634-opensea-nft-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de n8n interactuar con la API de OpenSea para recuperar y procesar datos específicos sobre NFTs.
  - **Complejidad:** Baja (1 nodos)

- **[2635-bright_data_gemini_search.json](workflows/2635-bright_data_gemini_search.json)**
  - **Descripción:** Este flujo automatizado busca datos web utilizando Perplexity, extrae información relevante con LangChain y utiliza Gemini AI para generar resúmenes.
  - **Complejidad:** Baja (1 nodos)

- **[2653-line-chatbot-memory.json](workflows/2653-line-chatbot-memory.json)**
  - **Descripción:** Este flujo permite a un chatbot de LINE mantener una conversación contextualizada utilizando la memoria histórica almacenada en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2678-gmail-to-drive-pdfs.json](workflows/2678-gmail-to-drive-pdfs.json)**
  - **Descripción:** Este flujo automático envía attachments PDF específicos de un correo electrónico a Google Drive usando OpenAI para filtrar y subir solo aquellos que coinciden con un término determinado.
  - **Complejidad:** Baja (1 nodos)

- **[2688-data_extraction_bright_google.json](workflows/2688-data_extraction_bright_google.json)**
  - **Descripción:** Este flujo extrae y analiza datos estructurados de una página web utilizando Bright Data Web Unlocker y Google Gemini para realizar tareas de minería de datos, incluyendo análisis temático y extracción de sentimientos.
  - **Complejidad:** Baja (1 nodos)

- **[2706-airtable-csv-uploader.json](workflows/2706-airtable-csv-uploader.json)**
  - **Descripción:** Este flujo automático procesa y carga datos desde un archivo CSV a Airtable. Detecta si la campaña no está vacía, marca el estado de proceso, descarga el archivo, crea registros en Airtable y actualiza el estado a 'Uploaded' o 'Failed'.
  - **Complejidad:** Baja (1 nodos)

- **[2707-dropbox-backup-cleanup.json](workflows/2707-dropbox-backup-cleanup.json)**
  - **Descripción:** Este flujo automático programa tareas periódicas para Backup y limpieza de Workflows en Dropbox. Cada día, copia los Workflows actuales a una carpeta 'OLD' y elimina aquellos backups que superen los 30 días.
  - **Complejidad:** Baja (1 nodos)

- **[2767-file-organizer-mistral.json](workflows/2767-file-organizer-mistral.json)**
  - **Descripción:** Este flujo utiliza un desencadenador local para monitorear un directorio, utiliza comandos para obtener una lista de archivos y carpetas, luego emplea el modelo Mistral AI para organizar los archivos moviéndolos a subcarpetas apropiadas basándose en sugerencias del AI.
  - **Complejidad:** Baja (1 nodos)

- **[2780-gitlab-backup-n8n.json](workflows/2780-gitlab-backup-n8n.json)**
  - **Descripción:** Este flujo automático configura un backup periódico y manual de los workflows de n8n en GitLab. Utiliza triggers programados y manuales para guardar la configuración actualizada en archivos separados dentro de una repositorio gitlab.
  - **Complejidad:** Baja (1 nodos)

- **[2805-sincronizacion-stripe-s3.json](workflows/2805-sincronizacion-stripe-s3.json)**
  - **Descripción:** Este flujo automatiza la sincronización de facturas PDF desde Stripe hacia un.bucket de AWS S3 organizando los archivos en subcarpetas según el año y mes. Configura intervalos mensuales para descargar solo las facturas emitidas a partir del primer día del mes.
  - **Complejidad:** Baja (1 nodos)

- **[2827-redis_lock_workflow.json](workflows/2827-redis_lock_workflow.json)**
  - **Descripción:** Este flujo utiliza Redis para bloquear la ejecución de un workflow hasta que expire una clave TTL, evitando así la ejecución concurrente.
  - **Complejidad:** Baja (1 nodos)

- **[2832-gmail-to-drive-organizer.json](workflows/2832-gmail-to-drive-organizer.json)**
  - **Descripción:** Este flujo automatiza la descarga de archivos adjuntos de Gmail, los organiza en carpetas específicas en Google Drive según el correo electrónico receptor y fecha, creando las carpetas necesarias si no existen.
  - **Complejidad:** Baja (1 nodos)

- **[2841-export_google_keep_to_sheet.json](workflows/2841-export_google_keep_to_sheet.json)**
  - **Descripción:** Este flujo automatiza la exportación de notas desde Google Keep alinear con un sistema de procesamiento y almacenamiento en Google Sheets. Busca archivos JSON en una carpeta específica de Google Drive, filtra aquellos que no estén archivados y contengan palabras clave como 'dépensé' o 'depense', descarga los archivos seleccionados, extrae su contenido y utiliza OpenAI para tratar la información antes de insertarla en una hoja de cálculo.
  - **Complejidad:** Baja (1 nodos)

- **[2843-gdrive-audit.json](workflows/2843-gdrive-audit.json)**
  - **Descripción:** Este flujo automatiza la auditoría de permisos en Google Drive, identificando archivos compartidos públicamente o con usuarios externos y generando un informe diario que se envía por correo electrónico.
  - **Complejidad:** Baja (1 nodos)

- **[2851-job_scraping_openai.json](workflows/2851-job_scraping_openai.json)**
  - **Descripción:** Este flujo automatiza la búsqueda de ofertas laborales en Indeed usando Bright Data y OpenAI para evaluar si cada cargo es adecuado. Inicia con un formulario que recoge ubicación, palabra clave y país, luego envía una solicitud a Bright Data, espera a que se procese el.snapshot, extrae los datos, y finalmente utiliza OpenAI para determinar si eres un buen candidato.
  - **Complejidad:** Baja (1 nodos)

- **[2852-glassdoor-jobs-scraper.json](workflows/2852-glassdoor-jobs-scraper.json)**
  - **Descripción:** Este flujo utiliza Bright Data para extraer ofertas laborales de Glassdoor basadas en ubicación, palabra clave y país, espera a que estén listas, las guarda en Google Sheets y luego genera pitches personalizados usando un LLM.
  - **Complejidad:** Baja (1 nodos)

- **[2853-trustpilot-analysis.json](workflows/2853-trustpilot-analysis.json)**
  - **Descripción:** Este flujo automatiza la extracción y análisis de reseñas negativas de competidores en Trustpilot usando Bright Data. El usuario ingresa una URL de Trustpilot y selecciona un período, luego el workflow envía una solicitud a Bright Data, espera hasta que los datos estén listos, filtra las reseñas negativas (1 o 2 estrellas), agrupa los comentarios y utiliza OpenAI para generar texto persuasivo basado en esas quejas. Finalmente, envía un resumen por correo electrónico.
  - **Complejidad:** Baja (1 nodos)

- **[2856-amazon_reviews_analysis.json](workflows/2856-amazon_reviews_analysis.json)**
  - **Descripción:** Este flujo utiliza Bright Data para extraer y analizar opiniones de productos en Amazon. Configura un formulario para introducir URLs de productos, envía una solicitud HTTP para iniciar el análisis, espera a que se procese la información y luego almacena los datos en Google Sheets. Después, utiliza OpenAI para resumir las reseñas, genera imágenes creativas basadas en los resultados y envía estos creativos por correo electrónico.
  - **Complejidad:** Baja (1 nodos)

- **[2859-sqlite-mcp-server.json](workflows/2859-sqlite-mcp-server.json)**
  - **Descripción:** Flujo que implementa un servidor MCP de SQLite para realizar operaciones básicas en una base de datos local como lectura, inserción y actualización de registros, usando nodos personalizados para manejar las operaciones seguras.
  - **Complejidad:** Baja (1 nodos)

- **[2860-gdrive-mcp-server.json](workflows/2860-gdrive-mcp-server.json)**
  - **Descripción:** Este flujo configura un servidor MCP que interactúa con Google Drive para buscar y leer archivos, convirtiendo formatos binarios a texto. Utiliza OpenAI para analizar imágenes y transcribir audio.
  - **Complejidad:** Baja (1 nodos)

- **[2866-legis-sostenibilidad.json](workflows/2866-legis-sostenibilidad.json)**
  - **Descripción:** Este flujo automático extrae información de procedimientos legislativos relacionados con sostenibilidad de la página web del Parlamento Europeo, clasificando cada documento utilizando un agente de lenguaje OpenAI y almacenándolos en una hoja de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2871-image-processing.json](workflows/2871-image-processing.json)**
  - **Descripción:** Este flujo automático descarga imágenes de URLs, las analiza para crear un prompt de fotografía de producto y genera una nueva imagen con OpenAI antes de almacenarla en Google Drive y actualizar una tabla.
  - **Complejidad:** Baja (1 nodos)

- **[2873-google-drive-folder-creator.json](workflows/2873-google-drive-folder-creator.json)**
  - **Descripción:** Este flujo crea una estructura jerárquica en Google Drive a partir de un path dado y devuelve el ID del último folder creado.
  - **Complejidad:** Baja (1 nodos)

- **[2892-resto-order-processor.json](workflows/2892-resto-order-processor.json)**
  - **Descripción:** Flujo automatizado para procesar pedidos en restaurantes. Extrae información de los pedidos mediante un agente de chat y herramientas de IA, separa los items, cantidad y número de mesa, confirma la orden y registra en una hoja de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2909-workflow_management.json](workflows/2909-workflow_management.json)**
  - **Descripción:** Este flujo automático gestiona y sincroniza Workflows de n8n con Airtable y Dropbox. Recupera detalles de Workflows, prepara datos, maneja cron jobs y actualiza o agrega nuevos registros en Airtable.
  - **Complejidad:** Baja (1 nodos)

- **[2910-import_odoo_product_images.json](workflows/2910-import_odoo_product_images.json)**
  - **Descripción:** Este flujo importa imágenes de productos desde Google Drive a Odoo, filtrando y actualizando las mismas en base al modelo y SKU. Mantiene un sistema para mover archivos procesados y notificar el total descargado.
  - **Complejidad:** Baja (1 nodos)

- **[2914-openai-file-citation.json](workflows/2914-openai-file-citation.json)**
  - **Descripción:** Este flujo extrae y formatea citas de archivos almacenados en OpenAI a partir de un hilo de conversación, asegurando que las referencias se muestren correctamente con nombres de archivo.
  - **Complejidad:** Baja (1 nodos)

- **[2946-automate-content-generator-wordpress.json](workflows/2946-automate-content-generator-wordpress.json)**
  - **Descripción:** Este flujo automático genera contenido para WordPress usando DeepSeek R1, incluyendo artículos y títulos SEO-friendlys, crea imágenes con DALL-E, las sube y actualiza una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2979-multi_methods_airtable.json](workflows/2979-multi_methods_airtable.json)**
  - **Descripción:** Este flujo maneja diferentes métodos HTTP para interactuar con una API de Airtable, realizando operaciones como crear, obtener todo, obtener un registro por ID, actualizar y eliminar registros.
  - **Complejidad:** Baja (1 nodos)

- **[3015-automated-resume-review-system.json](workflows/3015-automated-resume-review-system.json)**
  - **Descripción:** Este flujo automático permite analizar y evaluar currículos de manera automatizada utilizando OpenAI y Google Sheets. Incluye la subida al Drive, extracción de información, resumen profesional y almacenamiento en hojas de cálculo.
  - **Complejidad:** Baja (1 nodos)

- **[3018-webflow-airtable-tables-creator.json](workflows/3018-webflow-airtable-tables-creator.json)**
  - **Descripción:** Este flujo crea tablas dinámicas en Airtable para las submisiones de formularios de Webflow. Automatiza la creación de tableros y registros basados en los formulario, usando credenciales de API y manejando errores.
  - **Complejidad:** Baja (1 nodos)

- **[3019-export_zammad_to_excel.json](workflows/3019-export_zammad_to_excel.json)**
  - **Descripción:** Este flujo exporta objetos de Zammad como Usuarios, Roles, Grupos y Organizaciones a archivos Excel.
  - **Complejidad:** Baja (1 nodos)

- **[3036-procesador-imagenes-ollama.json](workflows/3036-procesador-imagenes-ollama.json)**
  - **Descripción:** Este flujo automatiza el análisis detallado de imágenes utilizando modelos visuales locales de Ollama. Descarga una imagen desde Google Drive, la procesa con múltiples modelos (como granita3.2-vision y llama3.2-vision), genera descripciones exhaustivas en markdown y las guarda en Google Docs.
  - **Complejidad:** Baja (1 nodos)

- **[3040-enra_zammad_sync.json](workflows/3040-enra_zammad_sync.json)**
  - **Descripción:** Este flujo sincroniza usuarios de Entra con Zammad. Recupera grupos y miembros de Entra, crea objetos de usuario universales, compara datos para actualizar o desactivar usuarios en Zammad.
  - **Complejidad:** Baja (1 nodos)

- **[3059-openai-file-retrieval-rg.json](workflows/3059-openai-file-retrieval-rg.json)**
  - **Descripción:** Este flujo utiliza OpenAI para recuperar y citar contenido de archivos almacenados en un vector store, formateando la salida con Markdown o HTML.
  - **Complejidad:** Baja (1 nodos)

- **[3093-bright_data_extractor.json](workflows/3093-bright_data_extractor.json)**
  - **Descripción:** Este flujo utiliza Bright Data Web Scraper para extraer datos estructurados en masa. Inicia una captura, espera a que esté lista y luego descarga los datos. Maneja errores y notifica por webhook.
  - **Complejidad:** Baja (1 nodos)

- **[3095-remove-background-google-drive.json](workflows/3095-remove-background-google-drive.json)**
  - **Descripción:** Este flujo elimina el fondo de las imágenes almacenadas en Google Drive utilizando la API de Photoroom, añadiendo un color de fondo configurable y guardando las nuevas imágenes en una ubicación específica.
  - **Complejidad:** Baja (1 nodos)

- **[3102-organizar-archivos-con-AI.json](workflows/3102-organizar-archivos-con-AI.json)**
  - **Descripción:** Este flujo automatiza la organización de archivos en directorios locales utilizando IA. Monitorea un folder específico, lista los archivos y carpetas, utiliza Mistral AI para clasificar los archivos sugiriendo subdirectorios existentes o nuevos, y luego mueve los archivos según las indicaciones de la IA.
  - **Complejidad:** Baja (1 nodos)

- **[3106-automate-content-generator-wordpress.json](workflows/3106-automate-content-generator-wordpress.json)**
  - **Descripción:** Este flujo automatiza la creación de contenido para WordPress utilizando DeepSeek. Genera artículos, títulos y imágenes basadas en ideas proporcionadas en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3125-linkedin-stories-generator.json](workflows/3125-linkedin-stories-generator.json)**
  - **Descripción:** Este flujo extrae información de LinkedIn usando la API de Bright Data y genera historias empresariales con Google Gemini. Incluye el procesamiento de datos, extracción de información y resumen mediante LLM.
  - **Complejidad:** Baja (1 nodos)

- **[3130-extract-google-maps.json](workflows/3130-extract-google-maps.json)**
  - **Descripción:** Este flujo utiliza Google Maps y herramientas de scrappeo para extraer datos empresariales como nombre, dirección, teléfono, correo electrónico y website. Utiliza OpenAI para procesar las peticiones yGuardar en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3144-chatbot_companyIdocs.json](workflows/3144-chatbot_companyIdocs.json)**
  - **Descripción:** Este flujo automatiza la creación de un chatbot que utiliza documentos de la empresa almacenados en Google Drive y Gemini para responder preguntas.
  - **Complejidad:** Baja (1 nodos)

- **[3145-rag_context_chunking.json](workflows/3145-rag_context_chunking.json)**
  - **Descripción:** Este flujo automatiza la creación de vectores contextuales a partir de documentos en Google Drive usando RAG (Retrieval-Augmented Generation) con división en secciones y almacenamiento en Pinecone.
  - **Complejidad:** Baja (1 nodos)

- **[3146-reconcile-rent-payments.json](workflows/3146-reconcile-rent-payments.json)**
  - **Descripción:** Este flujo automatiza la reconciliación de pagos de alquileres utilizando un modelo OpenAI para detectar y flaggear discrepancias en los pagos contra una base de datos local en Excel. Identifica misses, pagos incorrectos, vencimientos y alerta acciones necesarias.
  - **Complejidad:** Baja (1 nodos)

- **[3154-dynamic_form_dropdown.json](workflows/3154-dynamic_form_dropdown.json)**
  - **Descripción:** Este flujo configura un formulario con un campo desplegable dinámico que se actualiza con valores obtenidos de una fuente de datos externa, como una hoja de cálculo de Google Sheets. La estructura incluye nodos para capturar la submisión del formulario, recuperar los datos de la fuente, transformarlos y actualizar el formulario con las nuevas opciones.
  - **Complejidad:** Baja (1 nodos)

- **[3163-gmail-to-drive-pdfs.json](workflows/3163-gmail-to-drive-pdfs.json)**
  - **Descripción:** Este flujo automatiza la transferencia de archivos PDF específicos desde Gmail a Google Drive usando OpenAI para filtrar y subir solo aquellos que coinciden con un término determinado.
  - **Complejidad:** Baja (1 nodos)

- **[3173-social-banner-generator.json](workflows/3173-social-banner-generator.json)**
  - **Descripción:** Este flujo automatiza la creación de banners sociales usando n8n Forms para capturar datos del evento, OpenAI para generar imágenes y BannerBear para crear el banner final.
  - **Complejidad:** Baja (1 nodos)

- **[3207-waitlist-verification.json](workflows/3207-waitlist-verification.json)**
  - **Descripción:** Flujo para manejar una lista de espera que incluye registro de usuarios, generación de código de verificación, envío de correo electrónico y validación. Si el código es incorrecto, se le pide al usuario reintentar. Una vez validado, se guarda en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3208-sql-agent-chart-generator.json](workflows/3208-sql-agent-chart-generator.json)**
  - **Descripción:** Este flujo utiliza un agente de SQL y OpenAI para generar respuestas con visualizaciones en tiempo real. El usuario puede hacer preguntas sobre los datos y el sistema determinará si incluir una gráfica usando Chart.js, accionando un subflujo para crear una imagen compatible con Quickchart.io.
  - **Complejidad:** Baja (1 nodos)

- **[3211-blueSky-welcome-bot.json](workflows/3211-blueSky-welcome-bot.json)**
  - **Descripción:** Este flujo programa un mensaje de bienvenida automático a nuevos seguidores en BlueSky. Primero inicia sesión, luego lista los seguidores y compara con una base de datos guardada para detectar新人. Los nuevos seguidores reciben un mensaje privado con un texto definido. Se actualiza la lista de seguidores en un archivo JSON.
  - **Complejidad:** Baja (1 nodos)

- **[3223-search-console-report.json](workflows/3223-search-console-report.json)**
  - **Descripción:** Este flujo extrae datos de Search Console mediante tres reportes diferentes (palabras clave, páginas y fechas) usando la API de Google. Los datos se procesan para separarlos y luego actualizar una hoja de cálculo de Google con información detallada sobre clics, impresiones, CTR y posiciones.
  - **Complejidad:** Baja (1 nodos)

- **[3227-calendly-klicktipp-sync.json](workflows/3227-calendly-klicktipp-sync.json)**
  - **Descripción:** Este flujo automático sincroniza eventos de Calendly con KlickTipp, manejando reservas y.Cancelaciones, transformando datos para asegurar que los invitados sean agregados o eliminados correctamente en la lista de subscriptores.
  - **Complejidad:** Baja (1 nodos)

- **[3231-transcription-ai-flow.json](workflows/3231-transcription-ai-flow.json)**
  - **Descripción:** Este flujo automatiza la transcripción en tiempo real de reuniones, estructura los datos y genera resúmenes usando OpenAI y bases de datos PostgreSQL.
  - **Complejidad:** Baja (1 nodos)

- **[3234-invoice-parser-flow.json](workflows/3234-invoice-parser-flow.json)**
  - **Descripción:** Este flujo automático detecta nuevos archivos en Google Drive, los envía a LlamaParse para análisis y extrae información de facturas. Los datos procesados se almacenan en Airtable como registros de invoices y sus respectivos ítems detallados.
  - **Complejidad:** Baja (1 nodos)

- **[3241-ai-meeting-automator.json](workflows/3241-ai-meeting-automator.json)**
  - **Descripción:** Este flujo automático utiliza un agente de inteligencia artificial para procesar transcripciones de reuniones, extraer tareas y notificar al cliente. Para ello, utiliza Airtable para crear tareas y Google Calendar para programar citas.
  - **Complejidad:** Baja (1 nodos)

- **[3245-csvToJsonParser.json](workflows/3245-csvToJsonParser.json)**
  - **Descripción:** Este flujo procesa una solicitud POST con datos en formato CSV o JSON. Primero, verifica el tipo de contenido y extrae los datos utilizando ExtractFromFile. Luego, convierte los datos_RAW a CSV si es necesario. Si hay errores, devuelve un código 500 con un mensaje de error. Si la conversión es exitosa, agrega los datos al cuerpo JSON y responde con un código 200.
  - **Complejidad:** Baja (1 nodos)

- **[3267-certificado-automatico.json](workflows/3267-certificado-automatico.json)**
  - **Descripción:** Este flujo automatiza la generación y envío de certificados basados en un cuestionario de Google Forms. Recoge datos de las respuestas, verifica la puntuación, crea una presentación personalizada con el nombre del usuario, convierte la presentación a PDF y envía un correo electrónico con el certificado al usuario si supera la calificación.
  - **Complejidad:** Baja (1 nodos)

- **[3318-extract_text_from_pdf_image_to_csv.json](workflows/3318-extract_text_from_pdf_image_to_csv.json)**
  - **Descripción:** Este flujo automático extrae texto de archivos PDF y imágenes usando Vertex AI (Gemini) y los convierte en CSV para su almacenamiento en Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[3319-umami-ai-analytics.json](workflows/3319-umami-ai-analytics.json)**
  - **Descripción:** Este flujo extrae datos de analítica web de Umami, procesa y envía información a un modelo de IA para obtener resúmenes y comparativas semanales, guardando los resultados en Baserow.
  - **Complejidad:** Baja (1 nodos)

- **[3325-split-test-ab.json](workflows/3325-split-test-ab.json)**
  - **Descripción:** Este flujo implementa un test de división A/B para evaluar diferentes mensajes en un chatbot. Al recibir un mensaje, verifica si la sesión existe y asigna aleatoriamente un.prompt entre dos opciones guardadas en Supabase, luego utiliza el agente AI con el prompt seleccionado.
  - **Complejidad:** Baja (1 nodos)

- **[3343-Indeed_Data_Scraper_Gemini.json](workflows/3343-Indeed_Data_Scraper_Gemini.json)**
  - **Descripción:** Este flujo extrae y resume datos de compañías de Indeed usando Bright Data y Google Gemini. Utiliza Airtable para almacenar los enlaces y procesa la información con agentes y cadenas de pensamiento AI.
  - **Complejidad:** Baja (1 nodos)

- **[0008-notion_linkedin_pub.json](workflows/0008-notion_linkedin_pub.json)**
  - **Descripción:** Este flujo automático publica cada día en LinkedIn un post seleccionado desde una base de datos de Notion, basándose en la fecha y hora programadas.
  - **Complejidad:** Baja (1 nodos)

- **[0087-github-backup-flujos.json](workflows/0087-github-backup-flujos.json)**
  - **Descripción:** Este flujo automático ejecuta trabajos todos los días a las 23:59 y guarda el contenido editado en archivos JSON en un repositorio de GitHub.
  - **Complejidad:** Baja (1 nodos)

- **[0093-pokemon-rate-limiter.json](workflows/0093-pokemon-rate-limiter.json)**
  - **Descripción:** Este flujo verifica límites de uso por minuto y hora mediante Redis, consulta datos de Airtable sobre Pokémon y utiliza webhooks para procesar respuestas.
  - **Complejidad:** Baja (1 nodos)

- **[0201-users-data-flow.json](workflows/0201-users-data-flow.json)**
  - **Descripción:** Este flujo obtiene datos aleatorios de usuarios de la API de randomuser.me, los procesa y almacena en una hoja de Google. También crea un archivo CSV con esos datos y prepara un correo electrónico para adjuntar el JSON.
  - **Complejidad:** Baja (1 nodos)

- **[0206-n8n_paginacion_ejemplo.json](workflows/0206-n8n_paginacion_ejemplo.json)**
  - **Descripción:** Este flujo automático utiliza nodos HTTP para obtener datos de manera estructurada (como listas de álbumes o páginas web) y manejar respuestas mediante la creación de elementos.
  - **Complejidad:** Baja (1 nodos)

- **[0207-workflow-automatico-mensajes-clientes.json](workflows/0207-workflow-automatico-mensajes-clientes.json)**
  - **Descripción:** Este flujo automático envía mensajes personalizados a cada cliente obtenido desde un almacenamiento de datos, esperando brevemente entre cada mensaje para evitar exceder límites de solicitud y luego les proporciona una URL específica para su interacción.
  - **Complejidad:** Baja (1 nodos)

- **[0218-asana-notion-sync.json](workflows/0218-asana-notion-sync.json)**
  - **Descripción:** Este flujo n8n sincroniza tareas entre Asana y Notion mediante webhooks, creando o actualizando entradas en la base de datos de Notion según los cambios detectados en las tareas de Asana.
  - **Complejidad:** Baja (1 nodos)

- **[0239-github-issue-notion-sync.json](workflows/0239-github-issue-notion-sync.json)**
  - **Descripción:** Este flujo sincroniza eventos de GitHub Issues con acciones en una base de datos de Notion, permitiendo la actualización automática de propiedades como título y estado.
  - **Complejidad:** Baja (1 nodos)

- **[0257-analisis-domini.json](workflows/0257-analisis-domini.json)**
  - **Descripción:** Este flujo automatizado toma una lista de dominios web (dividida en lotes), consulta su contenido mediante solicitudes HTTP, pide a OpenAI que analice el texto para obtener propiedades clave sobre valor proposicional, audiencia y sector, y luego guarda estos datos clasificados en un hoja de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[0277-products-to-xml.json](workflows/0277-products-to-xml.json)**
  - **Descripción:** Este flujo consulta aleatoriamente 16 productos de una base de datos MySQL y los transforma en dos archivos XML diferentes, manteniendo la estructura con etiquetas mediante funciones set.
  - **Complejidad:** Baja (1 nodos)

- **[0285-bitcoin-chat-flow-pinecone.json](workflows/0285-bitcoin-chat-flow-pinecone.json)**
  - **Descripción:** Este flujo permite cargar datos del Bitcoin White Paper desde Google Drive en Pinecone usando embeddings de GPT-4o-mini y responder preguntas mediante herramientas vectoriales.
  - **Complejidad:** Baja (1 nodos)

- **[0372-xml-to-json-converter.json](workflows/0372-xml-to-json-converter.json)**
  - **Descripción:** Este flujo permite convertir archivos XML a JSON, tiene múltiples conexiones y maneja errores con respuestas HTTP personalizadas.
  - **Complejidad:** Baja (1 nodos)

- **[0399-workflow-credentials-agent.json](workflows/0399-workflow-credentials-agent.json)**
  - **Descripción:** Este flujo permite almacenar configuraciones de n8n en una base de datos SQLite y consultarlas mediante un agente conversacional.
  - **Complejidad:** Baja (1 nodos)

- **[0413-analisis-multimodal-cv.json](workflows/0413-analisis-multimodal-cv.json)**
  - **Descripción:** Este flujo analiza currículums en PDF utilizando modelos visuales para detectar 'bypass' con prompts ocultos, evitando así que los candidatos intenten engañar al sistema.
  - **Complejidad:** Baja (1 nodos)

- **[0419-google-ads-keyword-data.json](workflows/0419-google-ads-keyword-data.json)**
  - **Descripción:** Este flujo de trabajo utiliza la API de Google Ads para obtener datos históricos y volúmenes de búsqueda de hasta 20 palabras clave.
  - **Complejidad:** Baja (1 nodos)

- **[0435-openai-supabase-sql-chat.json](workflows/0435-openai-supabase-sql-chat.json)**
  - **Descripción:** Este flujo permite a un usuario interactuar conversacionalmente con una base de datos PostgreSQL en Supabase mediante el uso de funciones de OpenAI para ejecutar consultas y generar respuestas.
  - **Complejidad:** Baja (1 nodos)

- **[0444-google-drive-pii-detector.json](workflows/0444-google-drive-pii-detector.json)**
  - **Descripción:** Este flujo automático detecta la creación de nuevos archivos CSV en Google Drive, identifica columnas que contienen datos personales (PII) mediante OpenAI, elimina esas columnas y vuelve a subir el archivo procesado.
  - **Complejidad:** Baja (1 nodos)

- **[0451-backups-workflow-google.json](workflows/0451-backups-workflow-google.json)**
  - **Descripción:** Este flujo automático ejecuta backups periódicos de workflows en Google Drive cada 4 horas y elimina los archivos originales para mantener el almacenamiento optimizado.
  - **Complejidad:** Baja (1 nodos)

- **[0458-google-drive-batch-upload.json](workflows/0458-google-drive-batch-upload.json)**
  - **Descripción:** Este flujo automático permite subir múltiples archivos a Google Drive de forma organizada mediante un formulario que verifica y crea automáticamente la carpeta destino.
  - **Complejidad:** Baja (1 nodos)

- **[0481-shopify-orders-sync.json](workflows/0481-shopify-orders-sync.json)**
  - **Descripción:** Este flujo automático obtiene pedidos de Shopify mediante API y los almacena en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[0482-invitaciones-google-sheets-n8n.json](workflows/0482-invitaciones-google-sheets-n8n.json)**
  - **Descripción:** Este flujo automatizado compara usuarios en n8n con datos de una hoja de Google Sheets para enviar invitaciones a los que no existen en la plataforma.
  - **Complejidad:** Baja (1 nodos)

- **[0491-ai-chat-agent-memory.json](workflows/0491-ai-chat-agent-memory.json)**
  - **Descripción:** Este flujo utiliza un agente de IA con memoria para mantener el contexto durante la interacción y realizar consultas a BigQuery sobre datos de envíos.
  - **Complejidad:** Baja (1 nodos)

- **[0511-outlook-jira-ai-tickets.json](workflows/0511-outlook-jira-ai-tickets.json)**
  - **Descripción:** Este flujo automático monitoriza el correo electrónico en la bandeja de Outlook para tickets de soporte, los clasifica y prioriza con inteligencia artificial, luego crea un ticket en Jira utilizando esos datos estructurados. Las notas adhesivas proporcionan instrucciones y contexto sobre cómo funciona el flujo.
  - **Complejidad:** Baja (1 nodos)

- **[0512-web-scraper-structured.json](workflows/0512-web-scraper-structured.json)**
  - **Descripción:** Este flujo automático permite extraer información estructurada sobre productos web (nombre, descripción, precio, valoración y número de reseñas) a partir de páginas HTML limpiadas. Utiliza Google Sheets para obtener listas de URLs a procesar, limpia el contenido con un script Node.js antes de enviarlo al modelo GPT-4 via OpenRouter, y finalmente anexa los resultados estructurados en JSON a otra hoja del documento.
  - **Complejidad:** Baja (1 nodos)

- **[0519-clockify-syncro-timer-sync.json](workflows/0519-clockify-syncro-timer-sync.json)**
  - **Descripción:** Este flujo sincroniza entradas de tiempo entre Clockify y Syncro mediante Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[0681-notion-ai-blog-update.json](workflows/0681-notion-ai-blog-update.json)**
  - **Descripción:** Este flujo automático reacciona a actualizaciones en una base de datos de Notion usando DeepSeek para crear artículos SEO y publicarlos tanto en WordPress como actualizar el registro original.
  - **Complejidad:** Baja (1 nodos)

- **[0770-google-drive-video-upload.json](workflows/0770-google-drive-video-upload.json)**
  - **Descripción:** Este flujo automático permite cargar videos en Google Drive y, de forma inmediata, los subirá a Instagram, TikTok e YouTube con un título o descripción generado por la IA (OpenAI). El proceso incluye descargar el video desde Google Drive, extraer su audio para análisis con OpenAI y finalmente realizar las peticiones HTTP necesarias para publicar en las tres plataformas de redes sociales.
  - **Complejidad:** Baja (1 nodos)

- **[0799-supabase-chat-ai.json](workflows/0799-supabase-chat-ai.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar de forma conversacional con una base de datos PostgreSQL alojada en Supabase, ejecutando consultas SQL basadas en solicitudes del usuario.
  - **Complejidad:** Baja (1 nodos)

- **[0801-ai-agent-weather-wiki.json](workflows/0801-ai-agent-weather-wiki.json)**
  - **Descripción:** Este flujo automatizado permite a un chatbot de IA responder preguntas sobre el clima actual y datos generales utilizando herramientas de Wikipedia, almacenando la conversación en memoria para mantener contexto.
  - **Complejidad:** Baja (1 nodos)

- **[0802-google-calendar-ai-agent.json](workflows/0802-google-calendar-ai-agent.json)**
  - **Descripción:** Este flujo automático permite a un asistente de Google Calendar interactuar con los usuarios mediante chat para crear eventos o recuperar datos, utilizando la API de OpenAI y manteniendo el contexto conversacional.
  - **Complejidad:** Baja (1 nodos)

- **[0804-ai-agent-hacker-news.json](workflows/0804-ai-agent-hacker-news.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de IA mantener una conversación contextualizada mediante herramientas personalizadas. En este caso específico, el agente utiliza un workflow para obtener y procesar datos sobre los artículos más populares en Hacker News.
  - **Complejidad:** Baja (1 nodos)

- **[0810-strava-coaching.json](workflows/0810-strava-coaching.json)**
  - **Descripción:** Este flujo analiza datos de Strava para ofrecer coaching deportivo personalizado en triatlón.
  - **Complejidad:** Baja (1 nodos)

- **[0812-social_media_caption_generator.json](workflows/0812-social_media_caption_generator.json)**
  - **Descripción:** Este flujo automático crea títulos para redes sociales en función de una breve presentación y datos sobre el público objetivo, almacenando todo directamente en un registro de Airtable.
  - **Complejidad:** Baja (1 nodos)

- **[0816-youtube-trend-finder-n8n.json](workflows/0816-youtube-trend-finder-n8n.json)**
  - **Descripción:** Este flujo automático utiliza la IA para analizar datos de videos tendenciales de YouTube en función de un nicho específico.
  - **Complejidad:** Baja (1 nodos)

- **[0830-assistant-travel-agency.json](workflows/0830-assistant-travel-agency.json)**
  - **Descripción:** Este flujo automatizado permite crear un asistente de OpenAI a partir del contenido de documentos almacenados en Google Drive y mantener una conversación contextualizada para la agencia de viajes.
  - **Complejidad:** Baja (1 nodos)

- **[0875-assistente_viajes_actualizado.json](workflows/0875-assistente_viajes_actualizado.json)**
  - **Descripción:** Este flujo automático permite crear un asistente de OpenAI a partir de un documento PDF almacenado en Google Drive, manteniendo una conversación contextualizada mediante memoria buffer y permitiendo su interacción vía chat.
  - **Complejidad:** Baja (1 nodos)

- **[0889-openai-chatbot-memory-api.json](workflows/0889-openai-chatbot-memory-api.json)**
  - **Descripción:** Este flujo permite a un chatbot de OpenAI mantener conversaciones con memoria persistente en PostgreSQL y acceder a información externa mediante APIs.
  - **Complejidad:** Baja (1 nodos)

- **[0896-postgres-chat-ai.json](workflows/0896-postgres-chat-ai.json)**
  - **Descripción:** Este flujo permite a un chatbot de IA interactuar con una base de datos PostgreSQL mediante herramientas para ejecutar consultas SQL y mantener contexto.
  - **Complejidad:** Baja (1 nodos)

- **[0899-yelp-summary.json](workflows/0899-yelp-summary.json)**
  - **Descripción:** Este flujo automático permite extraer y resumir reseñas de negocios en Yelp usando los servicios web de Bright Data para la recopilación de datos, seguido de análisis estructurado con Google Gemini.
  - **Complejidad:** Baja (1 nodos)

- **[0924-cv-multimodal-ai.json](workflows/0924-cv-multimodal-ai.json)**
  - **Descripción:** Este flujo de trabajo utiliza visión multimodal con AI para analizar currículums PDF y evaluar si los candidatos son aptos para una entrevista.
  - **Complejidad:** Baja (1 nodos)

- **[0942-pdf2blog-automatizado.json](workflows/0942-pdf2blog-automatizado.json)**
  - **Descripción:** Este flujo automático permite convertir archivos PDF en blogs mediante la extracción de texto, procesamiento con una API de OpenAI y publicación en Ghost si los resultados son válidos.
  - **Complejidad:** Baja (1 nodos)

- **[0947-trustpilot_reviews_google_sheets.json](workflows/0947-trustpilot_reviews_google_sheets.json)**
  - **Descripción:** Este flujo n8n automatiza la extracción de reseñas de Trustpilot a Google Sheets mediante scraping paginado y transformación de datos.
  - **Complejidad:** Baja (1 nodos)

- **[0948-glassdoor-resume-empresa.json](workflows/0948-glassdoor-resume-empresa.json)**
  - **Descripción:** Este flujo automatiza la extracción de datos sobre una empresa en Glassdoor usando Bright Data Web Scraper, los divide para su procesamiento con Gemini y genera un resumen.
  - **Complejidad:** Baja (1 nodos)

- **[0951-book-scraping-automation.json](workflows/0951-book-scraping-automation.json)**
  - **Descripción:** Este flujo automatizado extrae datos de libros desde URLs utilizando Dumpling AI, limpia el HTML y guarda la información en un CSV.
  - **Complejidad:** Baja (1 nodos)

- **[0952-facturas-ocr-google-drive.json](workflows/0952-facturas-ocr-google-drive.json)**
  - **Descripción:** Este flujo automático permite reconocer automáticamente facturas e invoices almacenadas en una carpeta de Google Drive (formatos PDF, PNG o JPG) usando la API OakPDF. El workflow se activa cuando hay archivos nuevos y extrae datos clave como el nombre del emisor, dirección, total pagado y detalles específicos para guardarlos estructurados en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[0977-postgresql-chat-automaton.json](workflows/0977-postgresql-chat-automaton.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con una base de datos PostgreSQL, generando respuestas basadas en consultas SQL que analizan los datos solicitados.
  - **Complejidad:** Baja (1 nodos)

- **[0982-comparativa-ia-pdf.json](workflows/0982-comparativa-ia-pdf.json)**
  - **Descripción:** Este flujo automatiza la extracción de datos directamente desde archivos PDF utilizando modelos de IA como Claude o Gemini para una comparación eficiente.
  - **Complejidad:** Baja (1 nodos)

- **[1002-flux-dev-image-generation.json](workflows/1002-flux-dev-image-generation.json)**
  - **Descripción:** Este flujo automático genera una imagen usando la API de Fal.ai con parámetros predefinidos y la descarga para almacenarla automáticamente en Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[1004-imagen-optimizada-gdrive.json](workflows/1004-imagen-optimizada-gdrive.json)**
  - **Descripción:** Este flujo automático optimiza imágenes subidas a una carpeta de Google Drive y las reenvía al mismo servicio.
  - **Complejidad:** Baja (1 nodos)

- **[1009-huggingface-notion-ai-database.json](workflows/1009-huggingface-notion-ai-database.json)**
  - **Descripción:** Este flujo automático ejecuta una consulta diaria a la API de Hugging Face cada semana para obtener datos sobre publicaciones relacionadas con inteligencia artificial y los almacena en un formato estructurado como base de datos en Notion.
  - **Complejidad:** Baja (1 nodos)

- **[1016-bright-data-serp-extractor.json](workflows/1016-bright-data-serp-extractor.json)**
  - **Descripción:** Este flujo utiliza la API de Bright Data para extraer datos de páginas de resultados de búsqueda (SERP) en Google y los procesa con cadenas de modelos LLM como Gemini Flash Exp para generar una respuesta estructurada.
  - **Complejidad:** Baja (1 nodos)

- **[1025-chatbot-extraccion-datos-personales.json](workflows/1025-chatbot-extraccion-datos-personales.json)**
  - **Descripción:** Este flujo automático analiza mensajes de chat para extraer datos personales (nombre, apellido, tipo de comunicación) y contactos en formato JSON.
  - **Complejidad:** Baja (1 nodos)

- **[1039-amazon-keywords-automation.json](workflows/1039-amazon-keywords-automation.json)**
  - **Descripción:** Este flujo automático obtiene sugerencias de palabras clave desde la API Completion de Amazon basadas en una entrada por webhook, limpia los datos y luego los almacena en Airtable.
  - **Complejidad:** Baja (1 nodos)

- **[1041-google-drive-rag-automation.json](workflows/1041-google-drive-rag-automation.json)**
  - **Descripción:** Este flujo automático permite descargar documentos de Google Drive, extraer y normalizar su texto, generar embeddings con Gemini, insertarlos en un índice Pinecone para búsqueda semántica, y cuando se recibe un mensaje por chat, recuperar información relevante del vector store.
  - **Complejidad:** Baja (1 nodos)

- **[1052-monday-com-column-split.json](workflows/1052-monday-com-column-split.json)**
  - **Descripción:** Este flujo procesa datos de columnas específicas en una tarjeta de Monday.com y las divide para manejar subelementos por separado.
  - **Complejidad:** Baja (1 nodos)

- **[1065-assistant-creator.json](workflows/1065-assistant-creator.json)**
  - **Descripción:** Este flujo automático permite descargar documentos de Google Drive y crear un asistente OpenAI con esas fichas, seguido de una conversación con el asistente.
  - **Complejidad:** Baja (1 nodos)

- **[1073-namesilo-domain-checker.json](workflows/1073-namesilo-domain-checker.json)**
  - **Descripción:** Este flujo automático verifica la disponibilidad de múltiples dominios a través de la API de Namesilo y exporta los resultados en formato Excel.
  - **Complejidad:** Baja (1 nodos)

- **[1078-matomo-seo-ai-report.json](workflows/1078-matomo-seo-ai-report.json)**
  - **Descripción:** Este flujo automático analiza datos de visitantes recurrentes (más de 3 visitas) en Matomo mediante integración con LLaMA-3 y guarda los resultados en Baserow para análisis SEO.
  - **Complejidad:** Baja (1 nodos)

- **[1082-serp-bear-ai-analysis.json](workflows/1082-serp-bear-ai-analysis.json)**
  - **Descripción:** Este flujo automático analiza los datos de rango de palabras clave de SERP Bear utilizando una inteligencia artificial, y guarda el análisis en Baserow.
  - **Complejidad:** Baja (1 nodos)

- **[1099-notion-page-archiver.json](workflows/1099-notion-page-archiver.json)**
  - **Descripción:** Este flujo automático busca y arhiva automáticamente las páginas vacías de una base de datos en Notion.
  - **Complejidad:** Baja (1 nodos)

- **[1106-openlibrary-recommendation.json](workflows/1106-openlibrary-recommendation.json)**
  - **Descripción:** Este flujo automático busca y recomienda un libro al azar de Open Library basado en el tema 'juvenile_literature' cada día viernes a las 11:00 AM o mediante ejecución manual, utilizando HTTP requests para obtener datos y enviar correos electrónicos con recomendaciones.
  - **Complejidad:** Baja (1 nodos)

- **[1126-xml-to-sheets.json](workflows/1126-xml-to-sheets.json)**
  - **Descripción:** Este flujo automatizado descarga un archivo XML de ejemplo, lo parsea para extraer elementos y crear un nuevo archivo en Google Sheets con las columnas definidas a partir del contenido.
  - **Complejidad:** Baja (1 nodos)

- **[1159-webinar-registration-klicktipp.json](workflows/1159-webinar-registration-klicktipp.json)**
  - **Descripción:** Este flujo automatiza la integración de registros webinars desde JotForm con KlickTipp. Valida y transforma datos como nombres, fechas, experiencias laborales y URLs para crear suscriptores en KlickTipp y aplicar etiquetas dinámicas basadas en las respuestas del formulario.
  - **Complejidad:** Baja (1 nodos)

- **[1167-stripe-quickbooks-integration.json](workflows/1167-stripe-quickbooks-integration.json)**
  - **Descripción:** Este blueprint implementa un flujo automatizado que integra n8n con Stripe y QuickBooks Online. Cuando se recibe una notificación de webhook 'payment_intent.succeeded' (éxito en el pago), busca si el cliente asociado ya existe en QuickBooks mediante una consulta HTTP a la API de QuickBooks. Si no existe, crea un nuevo cliente en QuickBooks usando los datos del pago y de Stripe, y luego crea un registro de venta (sales receipt) con esos detalles. El flujo utiliza n8n para manejar el workflow.
  - **Complejidad:** Baja (1 nodos)

- **[1168-linkedin-enrichment.json](workflows/1168-linkedin-enrichment.json)**
  - **Descripción:** Este flujo automático lee URLs de LinkedIn desde Google Sheets, las codifica y filtra para verificar si ya están enriquecidas. Luego llama a la API de RapidAPI (Fresh LinkedIn Profile Data) para obtener datos completos sobre los perfiles y finalmente actualiza un archivo CSV con esta información detallada.
  - **Complejidad:** Baja (1 nodos)

- **[1198-notion-duplicates-removal.json](workflows/1198-notion-duplicates-removal.json)**
  - **Descripción:** Este flujo elimina automáticamente duplicados de páginas en una base de datos Notion.
  - **Complejidad:** Baja (1 nodos)

- **[1199-google-drive-doc-summarizer.json](workflows/1199-google-drive-doc-summarizer.json)**
  - **Descripción:** Este flujo automático identifica el documento de Google Drive más recientemente creado, extrae su contenido y lo resume utilizando inteligencia artificial antes de almacenarlo en una hoja de cálculo.
  - **Complejidad:** Baja (1 nodos)

- **[1210-fal-ai-image-generation.json](workflows/1210-fal-ai-image-generation.json)**
  - **Descripción:** Este flujo automático permite generar imágenes mediante la API de Fal.ai, descargarlas y guardarlas en una carpeta específica de Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[1216-github-multiple-file-push.json](workflows/1216-github-multiple-file-push.json)**
  - **Descripción:** Este flujo permite subir múltiples archivos a un repositorio de GitHub mediante suscripciones, utilizando el token y la información proporcionada para autenticación e interacción con la API.
  - **Complejidad:** Baja (1 nodos)

- **[1227-tracker-gastos-ia-descripcion.json](workflows/1227-tracker-gastos-ia-descripcion.json)**
  - **Descripción:** Este flujo permite a un agente de IA procesar mensajes sobre gastos, convertirlos en datos estructurados JSON y guardarlos automáticamente en una hoja de Google. Incluye memoria para mantener conversaciones contextuales.
  - **Complejidad:** Baja (1 nodos)

- **[1231-feedback-resumen.json](workflows/1231-feedback-resumen.json)**
  - **Descripción:** Este workflow automatizado analiza respuestas de encuestas Google Form mediante Google Sheets y OpenAI GPT-4 para generar un resumen estructurado que incluye una visión general del sentimiento sobre un evento, junto con ideas para mejorar.
  - **Complejidad:** Baja (1 nodos)

- **[1252-ausencias_procesamiento.json](workflows/1252-ausencias_procesamiento.json)**
  - **Descripción:** Este flujo automático recopila y procesa los datos de ausencias (vacaciones y enfermedades) de los últimos meses desde Google Calendar. Utiliza expresiones regulares para filtrar eventos relacionados con vacaciones o enfermedades, calcula las horas de cada evento y genera un informe detallado que se envía por correo electrónico a la dirección payroll-team@mydomain.tld.
  - **Complejidad:** Baja (1 nodos)

- **[1463-extract-and-process-information-directly-pdf.json](workflows/1463-extract-and-process-information-directly-pdf.json)**
  - **Descripción:** Este flujo permite extracción de datos, generación de contenido, procesamiento de facturas utilizando PDF con inteligencia artificial y APIs.
  - **Complejidad:** Baja (1 nodos)

- **[1491-remove-personally-identifiable-information-pii-openai.json](workflows/1491-remove-personally-identifiable-information-pii-openai.json)**
  - **Descripción:** Este flujo permite extracción de datos, generación de contenido, monitoreo utilizando OpenAI/GPT con inteligencia artificial y APIs.
  - **Complejidad:** Baja (1 nodos)

- **[2530-analytics-utm-generator.json](workflows/2530-analytics-utm-generator.json)**
  - **Descripción:** Este flujo automático crea enlaces con parámetros UTM personalizados a partir de inputs específicos, genera códigos QR para ellos y luego utiliza un agente analítico basado en OpenAI para evaluar datos de Google Analytics.
  - **Complejidad:** Baja (1 nodos)

- **[2533-redaktionsplan_caption_generator.json](workflows/2533-redaktionsplan_caption_generator.json)**
  - **Descripción:** Este flujo automático crea títulos para redes sociales, utilizando la base de datos Airtable y un modelo de chat IA para generar textos creativos e informativos.
  - **Complejidad:** Baja (1 nodos)

- **[2551-traductor-srt.json](workflows/2551-traductor-srt.json)**
  - **Descripción:** Este flujo automático permite procesar archivos SRT subiendo un formulario que contiene el archivo y seleccionando el idioma destino. El sistema extrae texto del archivo binario, lo divide en partes, traduce cada fragmento manteniendo la estructura de subtítulos y finalmente genera un nuevo archivo con las traducciones completadas.
  - **Complejidad:** Baja (1 nodos)

- **[2552-google-sheets-mysql-sync.json](workflows/2552-google-sheets-mysql-sync.json)**
  - **Descripción:** Este flujo automatizado sincroniza datos entre Google Sheets y MySQL mediante comparaciones, actualizaciones y condiciones específicas.
  - **Complejidad:** Baja (1 nodos)

- **[2563-vector-db-loader.json](workflows/2563-vector-db-loader.json)**
  - **Descripción:** Este flujo automático permite cargar documentos de Google Drive en una base de datos vectorial usando embeddings de OpenAI y PostgreSQL.
  - **Complejidad:** Baja (1 nodos)

- **[2567-postgres-sync.json](workflows/2567-postgres-sync.json)**
  - **Descripción:** Este flujo sincroniza automáticamente datos de Google Sheets hacia una tabla PostgreSQL, insertando nuevos registros o actualizando los existentes basándose en campos clave.
  - **Complejidad:** Baja (1 nodos)

- **[2569-dataforseo-backlink-checker.json](workflows/2569-dataforseo-backlink-checker.json)**
  - **Descripción:** Este flujo verifica los estados (vivo o muerto) de un conjunto de URLs, analizándolas a través del API de DataForSEO y registrando el resultado en una hoja de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2594-bluesky-post-automation.json](workflows/2594-bluesky-post-automation.json)**
  - **Descripción:** Este flujo automático permite publicar posts con imágenes en Bluesky, manejando la autenticación de sesión y el envío de archivos.
  - **Complejidad:** Baja (1 nodos)

- **[2598-shopware-multi-manufacturer-import.json](workflows/2598-shopware-multi-manufacturer-import.json)**
  - **Descripción:** Este flujo automático permite importar múltiples fabricantes desde una hoja de Google hacia Shopware 6 mediante el procesamiento por lotes. Configura los parámetros necesarios y crea solicitudes HTTP con datos encriptados para logotipos e información multilingüe.
  - **Complejidad:** Baja (1 nodos)

- **[2606-youtube-trend-analysis-memory.json](workflows/2606-youtube-trend-analysis-memory.json)**
  - **Descripción:** Este flujo automático analiza datos de videos de YouTube utilizando herramientas como búsqueda y procesamiento del motor LangChain, luego los almacena en memoria para su uso posterior. Además, integra una verificación inicial mediante chatTrigger que determina si el usuario proporcionó un nicho antes de proceder.
  - **Complejidad:** Baja (1 nodos)

- **[2615-jira-notion-sync.json](workflows/2615-jira-notion-sync.json)**
  - **Descripción:** Este flujo automatizado sincroniza las creación, modificación y eliminación de problemas en Jira con entradas en una base de datos específica de Notion.
  - **Complejidad:** Baja (1 nodos)

- **[2616-medium_linkedin_automation.json](workflows/2616-medium_linkedin_automation.json)**
  - **Descripción:** Este flujo automático busca artículos aleatorios de Medium usando etiquetas predefinidas, verifica si ya no han sido utilizados mediante un registro en Airtable, crea publicaciones en LinkedIn con sus imágenes y envía una alerta por cada post exitoso.
  - **Complejidad:** Baja (1 nodos)

- **[2621-vector-paquete.json](workflows/2621-vector-paquete.json)**
  - **Descripción:** Este flujo automático extrae textos de archivos JSON en FTP, los divide en fragmentos y los almacena como embeddings en una base de datos vectorial Qdrant para facilitar búsquedas semánticas.
  - **Complejidad:** Baja (1 nodos)

- **[2624-OpenSeaAnalyticsAgent.json](workflows/2624-OpenSeaAnalyticsAgent.json)**
  - **Descripción:** Este flujo automático implementa un agente conversacional con memoria que analiza datos de NFTs utilizando API de OpenSea.
  - **Complejidad:** Baja (1 nodos)

- **[2639-oidc-client-auth-flow.json](workflows/2639-oidc-client-auth-flow.json)**
  - **Descripción:** Este flujo automático de n8n implementa el protocolo OIDC (OpenID Connect) para autenticar usuarios y obtener información sobre ellos. Comienza con un webhook que captura peticiones entrantes, luego procesa cookies de autenticación. Después, verifica si hay token presente o se recibe código en la URL para continuar obteniendo datos del usuario.
  - **Complejidad:** Baja (1 nodos)

- **[2648-travel-planner-mongodb.json](workflows/2648-travel-planner-mongodb.json)**
  - **Descripción:** Este flujo actúa como un asistente de planificación viajera que utiliza la memoria conversacional MongoDB y el vector store Atlas para buscar puntos de interés.
  - **Complejidad:** Baja (1 nodos)

- **[2651-ai_tshirt_redesign.json](workflows/2651-ai_tshirt_redesign.json)**
  - **Descripción:** Este flujo analiza una imagen de diseño de camiseta mediante un modelo de IA, como GPT-4o, y genera un prompt mejorado para crear un rediseño visual artístico usando modelos generativos.
  - **Complejidad:** Baja (1 nodos)

- **[2705-automated-tasks-creator.json](workflows/2705-automated-tasks-creator.json)**
  - **Descripción:** Este flujo automático crea tareas en Airtable basadas en plantillas y actualiza registros con fechas calculadas.
  - **Complejidad:** Baja (1 nodos)

- **[2708-piloterr-fundraising-scraping.json](workflows/2708-piloterr-fundraising-scraping.json)**
  - **Descripción:** Este flujo automático extrae información de financiación reciente de Crunchbase para Series A, B y Seed, la enriquece con datos adicionales de LinkedIn y Semrush, y la exporta a Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2716-form-to-email-notificacion.json](workflows/2716-form-to-email-notificacion.json)**
  - **Descripción:** Este flujo recoge datos de un formulario donde los usuarios ingresan su rol y correo electrónico. Luego verifica si el correo no es personal usando Clearbit para enriquecer la información. Si cumple con ciertos criterios, envía un correo electrónico.
  - **Complejidad:** Baja (1 nodos)

- **[2717-linkedin-email-finder.json](workflows/2717-linkedin-email-finder.json)**
  - **Descripción:** Este flujo automatiza la actualización de información de contactos en Google Sheets usando la API de Prospeo.io para encontrar correos electrónicos a través de URLS de LinkedIn.
  - **Complejidad:** Baja (1 nodos)

- **[2735-traductor-deepL-GDrive.json](workflows/2735-traductor-deepL-GDrive.json)**
  - **Descripción:** Este flujo automatiza la traducción de documentos PDF usando DeepL y Google Drive. Configura una ruta, selecciona el idioma origen y destino, y los archivos se traducirán automáticamente.
  - **Complejidad:** Baja (1 nodos)

- **[2746-dropcontact-batch.json](workflows/2746-dropcontact-batch.json)**
  - **Descripción:** Este flujo automatiza la eliminación masiva de contactos en Dropcontact mediante consultas PostgreSQL y maneja hasta 1500 solicitudes por hora.
  - **Complejidad:** Baja (1 nodos)

- **[2748-wordpress_blog_poster.json](workflows/2748-wordpress_blog_poster.json)**
  - **Descripción:** Este flujo automatiza la publicación de contenido en WordPress y Airtable. Busca entradas marcadas como 'To Post', convierte el markdown a HTML, sube una imagen, crea una entrada en WordPress con ella y actualiza Airtable para marcarla como 'Posted'.
  - **Complejidad:** Baja (1 nodos)

- **[2783-paddle-invoice-processor.json](workflows/2783-paddle-invoice-processor.json)**
  - **Descripción:** Este flujo automático detecta y procesa invoices de Paddle desde Gmail, extrae el enlace PDF, lo descarga y almacena en Google Drive organizándolo en carpetas específicas.
  - **Complejidad:** Baja (1 nodos)

- **[2788-daily-order-summary.json](workflows/2788-daily-order-summary.json)**
  - **Descripción:** Este flujo automatiza la creación de un resumen diario de órdenes y su envío por correo electrónico. Cada vez que se recibe una nueva orden a través de un webhook, los datos se almacenan en Airtable. A las 7 PM se genera un informe con todas las órdenes del día y se adjunta un HTML formateado.
  - **Complejidad:** Baja (1 nodos)

- **[2790-notion-kb-agent.json](workflows/2790-notion-kb-agent.json)**
  - **Descripción:** Este flujo utiliza OpenAI y Notion para actuar como un asistente de conocimiento base que busca información en una base de datos de Notion basándose en preguntas del usuario.
  - **Complejidad:** Baja (1 nodos)

- **[2812-youtube-metagen.json](workflows/2812-youtube-metagen.json)**
  - **Descripción:** Este flujo automatiza la generación de metadatos para videos de YouTube, incluyendo títulos, descripciones y tags optimizados para SEO, utilizando un formulario de entrada que procesa enlaces de video y transcripciones.
  - **Complejidad:** Baja (1 nodos)

- **[2819-procesar_Ordenes_Gmail.json](workflows/2819-procesar_Ordenes_Gmail.json)**
  - **Descripción:** Flujo automático que procesa órdenes de compra recibidas por correo electrónico, extrae información relevante y la almacena en una hoja de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2834-automated-instagram-posts.json](workflows/2834-automated-instagram-posts.json)**
  - **Descripción:** Este flujo automático publica contenido en Instagram usando Google Drive para detectar subidas de archivo, OpenAI para generar captions y Facebook Graph API para publicación.
  - **Complejidad:** Baja (1 nodos)

- **[2838-retell-call-storage.json](workflows/2838-retell-call-storage.json)**
  - **Descripción:** Este flujo procesa y almacena en diferentes herramientas como Airtable, Google Sheets y Notion los datos de las llamadas analizadas por Retell AI. Recibe un webhook cuando una llamada termina, filtra solo los eventos 'call_analyzed', extrae información relevante como el ID de la llamada, duración, costo y transcripción, y la guarda en Airtable, Google Sheets y Notion.
  - **Complejidad:** Baja (1 nodos)

- **[2844-actualizar_Tasas.json](workflows/2844-actualizar_Tasas.json)**
  - **Descripción:** Este flujo automatiza la actualización diaria de tasas de cambio desde USD a múltiples divisas utilizando una API. Registra los datos en Google Sheets y mantiene un historial archivado.
  - **Complejidad:** Baja (1 nodos)

- **[2848-linkedin-jobs-to-sheets.json](workflows/2848-linkedin-jobs-to-sheets.json)**
  - **Descripción:** Este flujo automatiza la extracción de ofertas laborales de LinkedIn utilizando Bright Data, las limpia y las envía a una hoja de cálculo de Google Sheets. Incluye un formulario para definir filtros como ubicación, palabra clave y país, espera a que se procese la solicitud, luego envía los datos limpios a la planilla.
  - **Complejidad:** Baja (1 nodos)

- **[2849-producthunt-to-sheets.json](workflows/2849-producthunt-to-sheets.json)**
  - **Descripción:** Este flujo recoge y procesa información de Product Hunt cada día para actualizar una hoja de cálculo de Google Sheets con los datos básicos de los productos publicados.
  - **Complejidad:** Baja (1 nodos)

- **[2857-filesystem-mcp-server.json](workflows/2857-filesystem-mcp-server.json)**
  - **Descripción:** Flujo que implementa un servidor MCP para manejar operaciones de archivo como listar directorios, leer y crear archivos en un sistema de archivos a través de comandos controlados.
  - **Complejidad:** Baja (1 nodos)

- **[2858-postgre-mcp-server.json](workflows/2858-postgre-mcp-server.json)**
  - **Descripción:** Flujo que implementa una interfaz MCP para interactuar con PostgreSQL permitiendo operaciones CRUD seguras usando herramientas personalizadas.
  - **Complejidad:** Baja (1 nodos)

- **[2870-paypal-payment-email.json](workflows/2870-paypal-payment-email.json)**
  - **Descripción:** Este flujo recoge datos de un webhook de PayPal, filtra eventos de pago completados, extrae detalles del orden, captura información del comprador y del producto, genera un correo electrónico con los datos formateados y adjunta un archivo JSON.
  - **Complejidad:** Baja (1 nodos)

- **[2898-whatsapp-flow-encrypt.json](workflows/2898-whatsapp-flow-encrypt.json)**
  - **Descripción:** Flujo que maneja la decodificación y encriptación híbrida de datos mediante RSA y AES-GCM para procesar interacciones seguras con usuarios a través de Whatsapp Flow.
  - **Complejidad:** Baja (1 nodos)

- **[2906-workflow-obsidian-markdown.json](workflows/2906-workflow-obsidian-markdown.json)**
  - **Descripción:** Este flujo automatiza la creación de notas en formato Markdown en tu Obsidian Vault mediante Google Drive. Recibe resultados de workflows, procesa información para generar contenido estructurado con YAML frontmatter y almacena los archivos en Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[2917-youtube-to-airtable.json](workflows/2917-youtube-to-airtable.json)**
  - **Descripción:** Este flujo automatiza la extracción de transcripciones de vídeos de YouTube y genera resúmenes detallados que se guardan en Airtable.
  - **Complejidad:** Baja (1 nodos)

- **[2920-flujo-extraccion-apuestas.json](workflows/2920-flujo-extraccion-apuestas.json)**
  - **Descripción:** Este flujo automático programa la extracción de datos de apuestas deportivas utilizando TheOddsAPI y Airtable. Realiza capturas diarias al inicio y fin del día para eventos futuros y resultados, respectivamente, y actualiza los registros en Airtable con información detallada.
  - **Complejidad:** Baja (1 nodos)

- **[2948-pinterest-analysis-ai.json](workflows/2948-pinterest-analysis-ai.json)**
  - **Descripción:** Este flujo automático extrae y analiza datos de Pinterest usando su API, almacena la información en Airtable, luego utiliza OpenAI para generar recomendaciones de contenido y envía un resumen a Gmail.
  - **Complejidad:** Baja (1 nodos)

- **[2958-formulario-datos.json](workflows/2958-formulario-datos.json)**
  - **Descripción:** Este flujo automático registra los datos de un formulario en Google Sheets y Airtable, extrae la fecha y hora de la submission, y envía correos electrónicos personalizados.
  - **Complejidad:** Baja (1 nodos)

- **[2973-pinterest-analysis-ai-suggestions.json](workflows/2973-pinterest-analysis-ai-suggestions.json)**
  - **Descripción:** Este flujo automático extrae y analiza datos de Pinterest Organic utilizando la API, almacena los resultados en Airtable y genera recomendaciones de contenido con inteligencia artificial para marketing.
  - **Complejidad:** Baja (1 nodos)

- **[3006-linkedin-to-airtable.json](workflows/3006-linkedin-to-airtable.json)**
  - **Descripción:** Este flujo automatiza la extracción de me gusta en LinkedIn, filtra las publicaciones más recientes y relevantes, y las registra en Airtable para organizarlas como ideas de contenido.
  - **Complejidad:** Baja (1 nodos)

- **[3010-coinmarketcap_dex_agent.json](workflows/3010-coinmarketcap_dex_agent.json)**
  - **Descripción:** Este flujo automático actúa como una herramienta de agente inteligente para interactuar con la API de CoinMarketCap DEXScan, permitiendo recuperar y analizar datos en tiempo real sobre exchanges descentralizados, pares de trading, volumen, liquidez y actividad comercial mediante un sistema multiagente integrado.
  - **Complejidad:** Baja (1 nodos)

- **[3020-convertir_imagenes_webp.json](workflows/3020-convertir_imagenes_webp.json)**
  - **Descripción:** Este flujo automático convierte imágenes JPG y PNG a formato WEBP usando la API de APYHub. Recupera URLs de imágenes desde una hoja de cálculo de Google Sheets, determina el tipo de archivo, realiza la conversión correspondiente y actualiza la hoja con los nuevos enlaces. Finalmente, sube las imágenes convertidas a Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[3035-cripto-market-agent.json](workflows/3035-cripto-market-agent.json)**
  - **Descripción:** Este flujo utiliza agentes de lenguaje y herramientas de HTTP para consultar datos de mercado criptográfico mediante la API de CoinMarketCap, proporcionando información sobre exchanges, activos, índices y sentimiento del mercado.
  - **Complejidad:** Baja (1 nodos)

- **[3042-airtable-mcp-server.json](workflows/3042-airtable-mcp-server.json)**
  - **Descripción:** Este flujo crea un servidor MCP usando Airtable para interactuar con una base de datos, permitiendo operaciones como obtener, buscar, actualizar y eliminar registros.
  - **Complejidad:** Baja (1 nodos)

- **[3073-reservation_medica.json](workflows/3073-reservation_medica.json)**
  - **Descripción:** Este flujo utiliza un agente de inteligencia artificial para gestionar citas médicas, integrando OpenAI y Google Calendar/Sheets. El agente recibe mensajes, verifica disponibilidad en el calendario, sugiere horarios o crea citas.
  - **Complejidad:** Baja (1 nodos)

- **[3082-pge-energy-cost-tracker.json](workflows/3082-pge-energy-cost-tracker.json)**
  - **Descripción:** Este flujo automatiza la extracción diaria de los costos de energía de PG&E, incluyendo electricidad y gas, desde su sitio web. Utiliza un navegador para iniciar sesión, navegar a las páginas relevantes, extraer los datos y enviar un correo electrónico con un informe formateado.
  - **Complejidad:** Baja (1 nodos)

- **[3085-notion-ai-assistant.json](workflows/3085-notion-ai-assistant.json)**
  - **Descripción:** Este flujo actúa como un asistente de conocimiento que utiliza Notion para buscar información y OpenAI para responder preguntas, organizando datos de bases de datos de manera eficiente.
  - **Complejidad:** Baja (1 nodos)

- **[3096-ahrefs-keyword-research.json](workflows/3096-ahrefs-keyword-research.json)**
  - **Descripción:** Flujo de investigación de palabras clave que utiliza Ahrefs para extraer y formatear datos SEO, pasando por un agente de limpieza de consultas y luego procesando la información con el modelo Gemini para una respuesta estructurada.
  - **Complejidad:** Baja (1 nodos)

- **[3111-air-quality-scheduler.json](workflows/3111-air-quality-scheduler.json)**
  - **Descripción:** Este flujo recolecta y procesa datos de calidad del aire y polen utilizando la API de Ambee, luego utiliza un agente de inteligencia artificial para generar recomendaciones personalizadas basadas en el perfil del usuario, y finalmente envía estas recomendaciones por correo electrónico.
  - **Complejidad:** Baja (1 nodos)

- **[3120-usuarios_ficticios.json](workflows/3120-usuarios_ficticios.json)**
  - **Descripción:** Este flujo genera y procesa datos JSON para crear archivos CSV con nombres y correos electrónicos aleatorios, usando GPT-4. Los usuarios pueden estar suscritos o no, con fechas de suscripción opcionales.
  - **Complejidad:** Baja (1 nodos)

- **[3121-deteccion_objetos_gemini.json](workflows/3121-deteccion_objetos_gemini.json)**
  - **Descripción:** Este flujo utiliza la API de Gemini 2.0 para detectar objetos en una imagen basada en un prompt. Descarga una imagen, usa el modelo de Gemini para obtener coordenadas normalizadas de los bounding boxes y luego las ajusta al tamaño original de la imagen para dibujarlas sobre ella.
  - **Complejidad:** Baja (1 nodos)

- **[3134-line-bot-ocr-to-sheets.json](workflows/3134-line-bot-ocr-to-sheets.json)**
  - **Descripción:** Este flujo automático recoge datos de una imagen enviada a un bot de LINE, la procesa para extraer información relevante usando OCR y luego almacena los datos en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3140-n8n-credentials-agent.json](workflows/3140-n8n-credentials-agent.json)**
  - **Descripción:** Este flujo automatiza la gestión de credenciales de workflows en n8n almacenándolas en una base de datos SQLite y utiliza un agente de IA para realizar búsquedas avanzadas mediante SQL.
  - **Complejidad:** Baja (1 nodos)

- **[3148-remove_pii_from_csv.json](workflows/3148-remove_pii_from_csv.json)**
  - **Descripción:** Este flujo automatiza la eliminación de datos personales (PII) de archivos CSV alojados en Google Drive. Utiliza OpenAI para identificar las columnas con información sensible y genera un nuevo archivo sin dichos datos.
  - **Complejidad:** Baja (1 nodos)

- **[3174-analisis-seo-serp.json](workflows/3174-analisis-seo-serp.json)**
  - **Descripción:** Automatiza el análisis de datos SEO de SERPBear enviando información a OpenRouter para obtener una sumailla y guardando los resultados en Baserow.
  - **Complejidad:** Baja (1 nodos)

- **[3175-google-doc-summarizer.json](workflows/3175-google-doc-summarizer.json)**
  - **Descripción:** Este flujo automático monitorea un folder específico en Google Drive, obtiene los nuevos documentos .doc, extrae su contenido y lo sumaiza utilizando un modelo de IA, luego almacena el resumen junto con metadatos en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3180-sqlite-ai-agent.json](workflows/3180-sqlite-ai-agent.json)**
  - **Descripción:** Este flujo permite interactuar con una base de datos SQLite usando un agente de inteligencia artificial. Descarga, extrae y carga la base de datos localmente, luego utiliza el agente de SQL para responder preguntas basadas en los datos.
  - **Complejidad:** Baja (1 nodos)

- **[3189-ubicacion-trabajo.json](workflows/3189-ubicacion-trabajo.json)**
  - **Descripción:** Este flujo automático registra automáticamente los tiempos de entrada y salida basados en ubicación usando Webhooks, Google Sheets y Drive. Detecta si la hoja de trabajo existe, crea una nueva si no está presente y registra los datos de hora con fecha y dirección.
  - **Complejidad:** Baja (1 nodos)

- **[3240-strava-to-sheets.json](workflows/3240-strava-to-sheets.json)**
  - **Descripción:** Este flujo programa un horario que cada dos horas extrae actividades de Strava, filtra aquellas no guardadas en Google Sheets y las procesa para actualizar una hoja de cálculo con detalles como distancia, fecha, tiempo y desnivel.
  - **Complejidad:** Baja (1 nodos)

- **[3259-notion-md-sincro.json](workflows/3259-notion-md-sincro.json)**
  - **Descripción:** Este flujo automatiza la sincronización de bloques de Notion convirtiendo texto enriquecido a formato Markdown y viceversa, permitiendo actualizar contenido con formato.
  - **Complejidad:** Baja (1 nodos)

- **[3268-prompt-generator.json](workflows/3268-prompt-generator.json)**
  - **Descripción:** Flujo para generar y organizar prompts optimizados en Airtable usando Google Gemini. Permite categorizar y estructurar prompts de chatbot para un mejor manejo en n8n.
  - **Complejidad:** Baja (1 nodos)

- **[3296-shopify-to-google-spreadsheet.json](workflows/3296-shopify-to-google-spreadsheet.json)**
  - **Descripción:** Este flujo extrae información de clientes de Shopify y la exporta a una hoja de cálculo de Google Sheets. Utiliza un bucle para recuperar datos paginados hasta que no haya más páginas, procesando la información y actualizando continuamente.
  - **Complejidad:** Baja (1 nodos)

- **[3302-webpage-change-monitor.json](workflows/3302-webpage-change-monitor.json)**
  - **Descripción:** Flujo automatizado para detectar cambios en una página web y notificar via correo electrónico cuando hay modificación. Utiliza un hash de contenido para comparación y registra actividades en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3333-Enrich_Company_Data.json](workflows/3333-Enrich_Company_Data.json)**
  - **Descripción:** Este flujo automatiza la enriquecimiento de datos empresariales usando Google Sheets, OpenAI y una herramienta de extracción web. Recupera información de una hoja de cálculo, utiliza un agente de inteligencia artificial para analizar sitios web mediante ScrapingBee y actualiza los datos en tiempo real.
  - **Complejidad:** Baja (1 nodos)

- **[0531-webflow-form-trigger.json](workflows/0531-webflow-form-trigger.json)**
  - **Descripción:** Este flujo automático se activa cuando un formulario es enviado en una página web de Webflow y recoge los datos para su procesamiento.
  - **Complejidad:** Baja (1 nodos)

- **[0599-box-folder-file-events.json](workflows/0599-box-folder-file-events.json)**
  - **Descripción:** Este flujo automático se activa cuando archivos o carpetas son movidas o descargadas en una carpeta específica de Box.
  - **Complejidad:** Baja (1 nodos)


### Herramientas de Productividad y Colaboración

- **[1398-mails2notion.json](workflows/1398-mails2notion.json)**
  - **Descripción:** Convierte correos electrónicos en páginas de Notion.
  - **Complejidad:** Alta (38 nodos)

- **[1259-jira-ticket-autoresolver.json](workflows/1259-jira-ticket-autoresolver.json)**
  - **Descripción:** Resuelve tickets de Jira de forma automática según reglas predefinidas.
  - **Complejidad:** Alta (36 nodos)

- **[1507-upsert-huge-documents-in-a-notion.json](workflows/1507-upsert-huge-documents-in-a-notion.json)**
  - **Descripción:** Este flujo permite chatbot, resumen utilizando OpenAI/GPT, Webhook, Notion con inteligencia artificial mediante webhooks y APIs de forma programada.
  - **Complejidad:** Alta (34 nodos)

- **[3112-track-time-pausas.json](workflows/3112-track-time-pausas.json)**
  - **Descripción:** Este flujo rastrea el tiempo de trabajo y las pausas en Notion. Crea una nueva página al inicio, actualiza el final del tiempo, maneja las interrupciones y envía mensajes al webhook.
  - **Complejidad:** Alta (30 nodos)

- **[2752-notion-webflow-sync.json](workflows/2752-notion-webflow-sync.json)**
  - **Descripción:** Este flujo sincroniza entradas de un blog desde Notion a Webflow comparando por slug y actualizando o creando posts según corresponda.
  - **Complejidad:** Alta (29 nodos)

- **[2803-workflow_calendar_task.json](workflows/2803-workflow_calendar_task.json)**
  - **Descripción:** Flujo que gestiona tareas y citas en Google Calendar y Notion mediante agentes especializados para calendar y tasks, usando OpenAI y Chat Models para la inteligencia artificial.
  - **Complejidad:** Alta (28 nodos)

- **[2886-jira-ticket-automatizacion.json](workflows/2886-jira-ticket-automatizacion.json)**
  - **Descripción:** Este flujo automático utiliza JIRA y OpenAI para triage, priorizar y resolver incidentes de soporte. Busca tiquetes abiertos, los procesa con AI para etiquetar y reescribir, luego busca resoluciones similares en la historia para sugerir comentarios basados en ellos.
  - **Complejidad:** Alta (27 nodos)

- **[0825-ai-social-media-amplifier.json](workflows/0825-ai-social-media-amplifier.json)**
  - **Descripción:** Este flujo automatizado permite compartir discusiones destacadas de GitHub que aparecen en Hacker News, generando y enviando publicaciones formateadas para Twitter e LinkedIn.
  - **Complejidad:** Alta (26 nodos)

- **[2581-email-todoist-ai-integration.json](workflows/2581-email-todoist-ai-integration.json)**
  - **Descripción:** Este flujo automatiza la conversión de correos electrónicos en tareas de Todoist mediante el uso del modelo GPT-4o-mini para resúmenes y propuestas de acciones.
  - **Complejidad:** Alta (25 nodos)

- **[3025-zoom-meeting-assistant.json](workflows/3025-zoom-meeting-assistant.json)**
  - **Descripción:** Este flujo automatiza la asistencia a reuniones de Zoom mediante la extracción y análisis de transcripciones para enviar resúmenes por correo electrónico, crear tareas en ClickUp y programar citas futuras.
  - **Complejidad:** Alta (25 nodos)

- **[3236-email-threat-detection.json](workflows/3236-email-threat-detection.json)**
  - **Descripción:** Este flujo automatiza la detección de amenazas en correo electrónico mediante integración con Gmail y Outlook, análisis con ChatGPT y creación de tickets en Jira.
  - **Complejidad:** Alta (25 nodos)

- **[1131-notion-linear-issue-sync.json](workflows/1131-notion-linear-issue-sync.json)**
  - **Descripción:** Este flujo automatizado extrae información de bloques To-Do en Notion con formato específico y la usa para crear tareas automáticamente en Linear.
  - **Complejidad:** Alta (24 nodos)

- **[2649-zoom-ai-meeting-auto.json](workflows/2649-zoom-ai-meeting-auto.json)**
  - **Descripción:** Este flujo automático procesa transcripciones de reuniones de Zoom con IA para generar resúmenes por correo, crear tareas en ClickUp y programar llamadas de seguimiento.
  - **Complejidad:** Alta (24 nodos)

- **[2754-backup-github.json](workflows/2754-backup-github.json)**
  - **Descripción:** Este flujo automatiza la copia de seguridad de credenciales en GitHub. Utiliza un comando para exportar credenciales, las formatea y luego compara con versiones existentes o crea nuevas si no existe.
  - **Complejidad:** Alta (24 nodos)

- **[3032-gitlab-merge-request-review.json](workflows/3032-gitlab-merge-request-review.json)**
  - **Descripción:** Este flujo automático analiza los cambios en una solicitud de integración (MR) de GitLab, utiliza Claude AI para evaluar el riesgo y genera un informe estructurado con recomendaciones, casos de prueba y correcciones.
  - **Complejidad:** Alta (23 nodos)

- **[3033-clockify-backup.json](workflows/3033-clockify-backup.json)**
  - **Descripción:** Este flujo automático extrae y almacena reportes detallados de Clockify en GitHub. Para cada mes configurado, verifica si el archivo existe y lo actualiza o crea uno nuevo.
  - **Complejidad:** Alta (21 nodos)

- **[1132-todoist-task-management.json](workflows/1132-todoist-task-management.json)**
  - **Descripción:** Este flujo automático gestiona tareas en Todoist moviéndolas entre proyectos según fechas límite y condiciones horarias.
  - **Complejidad:** Alta (19 nodos)

- **[2861-github-mcp-server.json](workflows/2861-github-mcp-server.json)**
  - **Descripción:** Este flujo configura un servidor MCP personalizado en n8n para interactuar con GitHub, permitiendo visualizar y comentar issues. Utiliza nodos personalizados para obtener los últimos problemas, comentarios de issues y agregar nuevos comentarios.
  - **Complejidad:** Alta (19 nodos)

- **[0839-email-phishing-analysis.json](workflows/0839-email-phishing-analysis.json)**
  - **Descripción:** Este flujo automático analiza mensajes de correo electrónico sospechosos detectados en Gmail y Outlook, utilizando ChatGPT Vision para evaluar su apariencia visual e indicar si pueden ser intentos de phishing. Los resultados son formateados y almacenados en Jira.
  - **Complejidad:** Alta (18 nodos)

- **[3235-phishing-email-monitor.json](workflows/3235-phishing-email-monitor.json)**
  - **Descripción:** Este flujo automático monitorea correo electrónico de Gmail y Outlook, genera capturas de pantalla HTML, analiza amenazas con ChatGPT-4 y crea tickets en Jira para phishing.
  - **Complejidad:** Alta (18 nodos)

- **[0891-rag-github-api-chatbot.json](workflows/0891-rag-github-api-chatbot.json)**
  - **Descripción:** Este flujo utiliza el patrón RAG (Retrieval-Augmented Generation) con OpenAI y Pinecone para crear un chatbot que responda consultas sobre la documentación de la API de GitHub.
  - **Complejidad:** Alta (17 nodos)

- **[0999-github-prompts-dynamic.json](workflows/0999-github-prompts-dynamic.json)**
  - **Descripción:** Este flujo automatiza la carga de prompts dinámicos desde un repositorio GitHub y su auto-populación con expresiones n8n para uso en modelos de lenguaje.
  - **Complejidad:** Alta (17 nodos)

- **[1245-github-n8n-workflow_restore.json](workflows/1245-github-n8n-workflow_restore.json)**
  - **Descripción:** Este flujo automático permite restaurar workflows de un repositorio GitHub a una instancia n8n solo si no existen previamente en el workspace.
  - **Complejidad:** Alta (17 nodos)

- **[2625-monitor-advisories-paloalto.json](workflows/2625-monitor-advisories-paloalto.json)**
  - **Descripción:** Este flujo monitoriza advisories de seguridad de Palo Alto, los filtra por palabras clave como GlobalProtect o Traps, verifica si fueron publicados en el último día y crea incidencias en Jira o envía correos electrónicos a los clientes relevantes.
  - **Complejidad:** Alta (17 nodos)

- **[3141-load_prompts_github.json](workflows/3141-load_prompts_github.json)**
  - **Descripción:** Este flujo carga prompts desde un repositorio de GitHub y los procesa para reemplazar variables dinámicamente.
  - **Complejidad:** Alta (17 nodos)

- **[0690-github-sync-n8n.json](workflows/0690-github-sync-n8n.json)**
  - **Descripción:** Este flujo sincroniza automáticamente los workflows de N8N con un archivo en GitHub mediante comparación y edición diferida.
  - **Complejidad:** Alta (16 nodos)

- **[0898-gitlab-chatgpt-review.json](workflows/0898-gitlab-chatgpt-review.json)**
  - **Descripción:** Este flujo automatizado utiliza ChatGPT para revisar cambios de código detectados en una solicitud de integración (MR) de GitLab, analizando las diferencias entre el código original y modificado. Luego, integra estas revisiones con la API de GitLab para comentar directamente en los cambios.
  - **Complejidad:** Media (14 nodos)

- **[2733-gitlab-code-review.json](workflows/2733-gitlab-code-review.json)**
  - **Descripción:** Este flujo utiliza la API de GitLab para obtener los cambios realizados en una solicitud de fusión y utiliza un modelo LLM para revisar esos cambios. Si hay problemas, publica comentarios en el repositorio.
  - **Complejidad:** Media (14 nodos)

- **[3009-enra-zammad-sync.json](workflows/3009-enra-zammad-sync.json)**
  - **Descripción:** Este flujo sincroniza contactos de Entra con usuarios en Zammad. Recupera contactos de Microsoft Graph, los compara con usuarios existentes y actualiza o crea nuevos usuarios en Zammad.
  - **Complejidad:** Media (14 nodos)

- **[2887-ai-language-tools.json](workflows/2887-ai-language-tools.json)**
  - **Descripción:** Este flujo incluye una variedad de nodos relacionados con agentes de lenguaje y herramientas de IA, como transformadores de lenguaje, cadenas de encadenamiento, extraedores de información, analizadores de sentimiento, herramientas de vectores y memoria. También contiene conexiones con servicios externos como Google Sheets, Dropbox, Gmail, Twitter y más.
  - **Complejidad:** Media (13 nodos)

- **[0354-todoist-recurring-tasks.json](workflows/0354-todoist-recurring-tasks.json)**
  - **Descripción:** Este flujo n8n procesa tareas de un proyecto Todoist para crear nuevas tareas en la bandeja de entrada cada día, basadas en parámetros como días y horas específicas. Analiza las descripciones de las tareas, verifica si coinciden con el día actual, genera tareas nuevas y elimina aquellas que ya existen.
  - **Complejidad:** Media (13 nodos)

- **[1236-jira-retrospective-flow.json](workflows/1236-jira-retrospective-flow.json)**
  - **Descripción:** Este flujo automático se activa cuando un epic en Jira se marca como completado. Recopila todos los detalles de las tareas (títulos, descripciones, comentarios) que pertenecen a ese epic y utiliza un modelo de lenguaje para generar un documento estructurado con lecciones aprendidas y recomendaciones.
  - **Complejidad:** Media (13 nodos)

- **[0020-todoist-ai-categorization.json](workflows/0020-todoist-ai-categorization.json)**
  - **Descripción:** Este flujo organiza automáticamente tareas de Todoist en proyectos específicos usando inteligencia artificial para categorizarlas.
  - **Complejidad:** Media (12 nodos)

- **[0409-todoist-categorizador.json](workflows/0409-todoist-categorizador.json)**
  - **Descripción:** Este flujo automático toma tareas de la bandeja de entrada de Todoist, descarta subtareas y utiliza IA para asignarlas a proyectos específicos basados en prioridades predefinidas o etiquetarlas como 'other'.
  - **Complejidad:** Media (12 nodos)

- **[0101-github-issue-auto-assignment.json](workflows/0101-github-issue-auto-assignment.json)**
  - **Descripción:** Este flujo automático asigna automáticamente los issues de GitHub a la persona que lo creó o comentó, cuando no tienen asignado nadie.
  - **Complejidad:** Media (11 nodos)

- **[0683-github-credentials-restore.json](workflows/0683-github-credentials-restore.json)**
  - **Descripción:** Este flujo automático permite restaurar todas las credenciales de la instancia desde un repositorio de GitHub.
  - **Complejidad:** Media (11 nodos)

- **[0835-analisis-papers-hf.json](workflows/0835-analisis-papers-hf.json)**
  - **Descripción:** Este flujo automatizado extrae y analiza artículos académicos de la plataforma Hugging Face utilizando inteligencia artificial (OpenAI) y almacena el resultado en un formato estructurado en Notion.
  - **Complejidad:** Media (11 nodos)

- **[1047-linkedin-ai-post.json](workflows/1047-linkedin-ai-post.json)**
  - **Descripción:** Este flujo automatiza la publicación en LinkedIn. Extrae el contenido del día desde Notion, lo reformatea con IA, adjunta la imagen correspondiente y publica el resultado en tu perfil.
  - **Complejidad:** Media (11 nodos)

- **[1430-ai-agent-for-instagram-dm_inbox-ai.json](workflows/1430-ai-agent-for-instagram-dm_inbox-ai.json)**
  - **Descripción:** Este flujo permite chatbot, generación de contenido utilizando OpenAI/GPT, Webhook, Notion con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (11 nodos)

- **[0356-sync-n8n-notion.json](workflows/0356-sync-n8n-notion.json)**
  - **Descripción:** Este flujo sincroniza automáticamente los workflows de n8n con el sistema Notion cada 15 minutos.
  - **Complejidad:** Media (10 nodos)

- **[0885-zammad-roles-sync.json](workflows/0885-zammad-roles-sync.json)**
  - **Descripción:** Este flujo automático actualiza todos los roles de usuario en Zammad para usuarios activos con base a una lista predefinida de roles por defecto.
  - **Complejidad:** Media (10 nodos)

- **[3153-reschedule-overdue-asana.json](workflows/3153-reschedule-overdue-asana.json)**
  - **Descripción:** Este flujo automático programado para ejecutarse每日7点，recupera las tareas asignadas desde Asana y gestiona el estado de los trabajos. Se encarga de reprogramar tareas vencidas al día actual si están abiertas y eliminar aquellas que ya han sido finalizadas.
  - **Complejidad:** Media (10 nodos)

- **[2825-gestion_citas_vapi.json](workflows/2825-gestion_citas_vapi.json)**
  - **Descripción:** Este flujo automático gestiona la reserva y gestión de citas mediante Vapi, Google Calendar y Airtable. Permite verificar disponibilidad, crear, actualizar y eliminar eventos, así como registrar información de llamadas telefónicas.
  - **Complejidad:** Media (9 nodos)

- **[0204-clientes-condicion.json](workflows/0204-clientes-condicion.json)**
  - **Descripción:** Este flujo procesa datos de clientes mediante filtros y bifurcaciones condicionales para segmentarlos por país.
  - **Complejidad:** Media (9 nodos)

- **[0276-notion-outlook-sync.json](workflows/0276-notion-outlook-sync.json)**
  - **Descripción:** Este flujo automático sincroniza eventos del calendario Outlook con páginas de base de datos en Notion mediante la verificación y creación/actualización basada en el ID del evento.
  - **Complejidad:** Media (9 nodos)

- **[0290-feedback-openai-google.json](workflows/0290-feedback-openai-google.json)**
  - **Descripción:** Este flujo automático permite recoger comentarios de clientes a través de un formulario y utilizar OpenAI para analizar su sentimiento. Los resultados junto con los datos del formulario se combinan y guardan automáticamente en una hoja de Google.
  - **Complejidad:** Media (9 nodos)

- **[0324-google-drive-file-share.json](workflows/0324-google-drive-file-share.json)**
  - **Descripción:** Este flujo n8n permite obtener y compartir archivos de Google Drive en modo público mediante una ejecución manual.
  - **Complejidad:** Media (9 nodos)

- **[0384-api-flutterflow-data.json](workflows/0384-api-flutterflow-data.json)**
  - **Descripción:** Este flujo n8n se utiliza para crear una API en FlutterFlow que recibe datos desde un almacén de datos (como 'Customer Datastore') y los inserta en una variable antes de devolverlos como JSON a la aplicación.
  - **Complejidad:** Media (9 nodos)

- **[0426-token-management.json](workflows/0426-token-management.json)**
  - **Descripción:** Este flujo utiliza variables estáticas persistentes para gestionar un token de acceso que caduca después de 1 minuto. Cuando el token expira (por la verificación en 'if token is valid'), se solicita uno nuevo mediante HTTP y actualiza los datos estáticos.
  - **Complejidad:** Media (9 nodos)

- **[0448-upwork-jobs-sync.json](workflows/0448-upwork-jobs-sync.json)**
  - **Descripción:** Este flujo consulta trabajos recientes de Upwork usando Apify y MongoDB. Si las horas son entre 2-15, verifica si ya existen entradas similares por título y presupuesto antes de insertarlas.
  - **Complejidad:** Media (9 nodos)

- **[0504-sharepoint-upload.json](workflows/0504-sharepoint-upload.json)**
  - **Descripción:** Este flujo automático sube archivos a Microsoft SharePoint utilizando Graph API.
  - **Complejidad:** Media (9 nodos)

- **[0807-analisis-sentimiento-feedback.json](workflows/0807-analisis-sentimiento-feedback.json)**
  - **Descripción:** Este flujo automatizado permite recopilar comentarios de clientes en una hoja de Google, analizarlos con IA para detectar el sentimiento y luego integrarlo junto con otros datos del formulario en la misma hoja.
  - **Complejidad:** Media (9 nodos)

- **[0853-fine-tuning-openai-with-drive.json](workflows/0853-fine-tuning-openai-with-drive.json)**
  - **Descripción:** Este flujo automático permite realizar un proceso completo de fine-tuning en modelos de OpenAI usando archivos JSONL alojados en Google Drive.
  - **Complejidad:** Media (9 nodos)

- **[0902-baserow-markdown-sync.json](workflows/0902-baserow-markdown-sync.json)**
  - **Descripción:** Este flujo automático permite sincronizar y actualizar registros en Baserow donde la descripción del video esté en formato Markdown. Primero verifica si hay un solo registro o múltiples, convierte cada descripción a HTML manteniendo la estructura original de datos e inicia sesión mediante un webhook.
  - **Complejidad:** Media (9 nodos)

- **[0953-notion-supabase-vector.json](workflows/0953-notion-supabase-vector.json)**
  - **Descripción:** Este flujo automatiza el almacenamiento de páginas de Notion como documentos vectorizados en un proyecto de Supabase utilizando columnas de vectores y embeddings generados por OpenAI.
  - **Complejidad:** Media (9 nodos)

- **[0979-pipeline-etl-twitter-sentiment.json](workflows/0979-pipeline-etl-twitter-sentiment.json)**
  - **Descripción:** Esta automatización diaria busca tweets con el hashtag #OnThisDay mediante ETL, analiza su sentimiento usando Google NLP y almacena los resultados en tablas de Postgres y MongoDB.
  - **Complejidad:** Media (9 nodos)

- **[1015-modelo_openai_fine_tuning.json](workflows/1015-modelo_openai_fine_tuning.json)**
  - **Descripción:** Este flujo automático permite la creación y uso de modelos personalizados de OpenAI a través del fine-tuning basado en archivos JSONL descargados desde Google Drive.
  - **Complejidad:** Media (9 nodos)

- **[1097-n8n-workflows-guardar.json](workflows/1097-n8n-workflows-guardar.json)**
  - **Descripción:** Este flujo automático permite guardar workflows de n8n en archivos JSON en Google Drive.
  - **Complejidad:** Media (9 nodos)

- **[1119-smart-factory-alert.json](workflows/1119-smart-factory-alert.json)**
  - **Descripción:** Este flujo monitorea sensores de fábrica para detectar temperaturas superiores a 50°C y almacena tanto los datos del sensor como incidentes en CrateDB.
  - **Complejidad:** Media (9 nodos)

- **[1188-n8n-backup-cron.json](workflows/1188-n8n-backup-cron.json)**
  - **Descripción:** Este flujo programa una tarea cada 6 horas para ejecutar un workflow y guardar su resultado como archivo binario en Nextcloud.
  - **Complejidad:** Media (9 nodos)

- **[1229-notion-document-embedding.json](workflows/1229-notion-document-embedding.json)**
  - **Descripción:** Este flujo automatiza el procesamiento de documentos Notion para generar sus embeddings y almacenarlos en Supabase.
  - **Complejidad:** Media (9 nodos)

- **[1498-store-notion_s-pages-as-vector-openai.json](workflows/1498-store-notion_s-pages-as-vector-openai.json)**
  - **Descripción:** Este flujo permite automatización, resumen, generación de contenido, monitoreo utilizando OpenAI/GPT, Notion, Supabase con inteligencia artificial y APIs.
  - **Complejidad:** Media (9 nodos)

- **[2565-ai-screenshot-analysis.json](workflows/2565-ai-screenshot-analysis.json)**
  - **Descripción:** Este flujo automatiza el análisis de capturas de pantalla mediante inteligencia artificial. Primero recoge la URL del sitio web a analizar, luego genera un screenshot utilizando la API de URLbox y finalmente lo procesa con OpenAI para obtener una descripción textual concisa en un solo párrafo.
  - **Complejidad:** Media (9 nodos)

- **[2586-shopify-campaign-sync.json](workflows/2586-shopify-campaign-sync.json)**
  - **Descripción:** Este flujo n8n permite guardar archivos .liquid en el tema de Shopify después de subir imágenes usando GraphQL, optimizando la creación de campañas publicitarias.
  - **Complejidad:** Media (9 nodos)

- **[2588-image-meta-tagging-automation.json](workflows/2588-image-meta-tagging-automation.json)**
  - **Descripción:** Este flujo automático analiza el contenido de imágenes subidas en una carpeta específica de Google Drive y escribe directamente la descripción como etiquetas (tags) en los metadatos XMP del archivo.
  - **Complejidad:** Media (9 nodos)

- **[2612-zammad-roles-excel.json](workflows/2612-zammad-roles-excel.json)**
  - **Descripción:** Este flujo automático permite descargar un archivo Excel desde una URL configurada previamente y actualizar el rol de los usuarios en Zammad a partir de los datos contenidos en él.
  - **Complejidad:** Media (9 nodos)

- **[2618-gemini-image-data-extractor.json](workflows/2618-gemini-image-data-extractor.json)**
  - **Descripción:** Este flujo crea una API para extraer datos de imágenes utilizando Gemini AI, requiere enviar una URL de imagen y un conjunto de instrucciones que definen qué información debe ser extraída.
  - **Complejidad:** Media (9 nodos)

- **[2641-csv-google-sheets-import.json](workflows/2641-csv-google-sheets-import.json)**
  - **Descripción:** Este flujo permite importar múltiples archivos CSV de una carpeta local a Google Sheets, eliminando duplicados y manteniendo solo suscriptores.
  - **Complejidad:** Media (9 nodos)

- **[3051-airtable-markdown-to-html.json](workflows/3051-airtable-markdown-to-html.json)**
  - **Descripción:** Este flujo procesa descripciones en formato markdown de un Airtable y las convierte a HTML. Si hay un solo registro, actualiza esa entrada; si hay múltiples registros, actualiza todas con el HTML convertido.
  - **Complejidad:** Media (9 nodos)

- **[3057-email_summary_dailly.json](workflows/3057-email_summary_dailly.json)**
  - **Descripción:** Este flujo automatiza la creación de resúmenes diarios de correo electrónico. Cada mañana a las 7 AM, recupera los correos electrónicos recibidos en las últimas 24 horas, organiza los datos, utiliza OpenAI para sintetizar el contenido y luego envía un informe estructurado con formato HTML.
  - **Complejidad:** Media (9 nodos)

- **[0240-shopify-zendesk-sync.json](workflows/0240-shopify-zendesk-sync.json)**
  - **Descripción:** Este flujo automático sincroniza la información de clientes entre Shopify y Zendesk al actualizar un contacto en Shopify.
  - **Complejidad:** Media (9 nodos)

- **[0411-backup-n8n-workflows.json](workflows/0411-backup-n8n-workflows.json)**
  - **Descripción:** Este flujo automático realiza el respaldo de los workflows de n8n a un repositorio Bitbucket, evitando así la exceder de límites de rate.
  - **Complejidad:** Media (9 nodos)

- **[2611-github-workflow-restore.json](workflows/2611-github-workflow-restore.json)**
  - **Descripción:** Este flujo automático permite restaurar workflows de n8n desde un repositorio de GitHub.
  - **Complejidad:** Media (9 nodos)

- **[1436-api-schema-extractor.json](workflows/1436-api-schema-extractor.json)**
  - **Descripción:** Este flujo permite chatbot, web scraping, extracción de datos, generación de contenido utilizando Webhook, Google Sheets, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (8 nodos)

- **[0096-news-hacker.json](workflows/0096-news-hacker.json)**
  - **Descripción:** Este flujo automático recoge títulos y URLs de noticias de Hacker News, las exporta como un archivo en formato CSV o Excel y envía una notificación por correo electrónico.
  - **Complejidad:** Media (8 nodos)

- **[0162-crypto-portfolio-updater.json](workflows/0162-crypto-portfolio-updater.json)**
  - **Descripción:** Este flujo automático actualiza los valores de activos cripto en una base Airtable cada hora con datos actuales desde CoinGecko.
  - **Complejidad:** Media (8 nodos)

- **[0231-line-chatbot-context.json](workflows/0231-line-chatbot-context.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada al utilizar datos del usuario en mensajes personalizados.
  - **Complejidad:** Media (8 nodos)

- **[0272-datos-aleatorios.json](workflows/0272-datos-aleatorios.json)**
  - **Descripción:** Este workflow realiza una solicitud HTTP a un servicio de API para obtener datos y los guarda en Google Sheets.
  - **Complejidad:** Media (8 nodos)

- **[0389-chat-movie-recommendations.json](workflows/0389-chat-movie-recommendations.json)**
  - **Descripción:** Este flujo permite a una IA conversacional interactuar con datos de MongoDB mediante agregaciones, mantener contexto en memoria buffer y registrar preferencias del usuario.
  - **Complejidad:** Media (8 nodos)

- **[0462-n8n-blueprint-backoff.json](workflows/0462-n8n-blueprint-backoff.json)**
  - **Descripción:** Este flujo implementa un mecanismo de backoff exponencial para manejar limitaciones de tasa (rate limiting) en la API de Google Sheets, reintentando una acción con incrementos exponenciales del tiempo entre intentos hasta alcanzar un máximo de 5 reintentos.
  - **Complejidad:** Media (8 nodos)

- **[0478-formulario-google-docs.json](workflows/0478-formulario-google-docs.json)**
  - **Descripción:** Este flujo automático permite al usuario enviar datos a través de un formulario y que estos se utilicen para rellenar texto en un documento de Google Docs utilizando la API.
  - **Complejidad:** Media (8 nodos)

- **[0920-squarespace-orders-to-sheets.json](workflows/0920-squarespace-orders-to-sheets.json)**
  - **Descripción:** Este flujo automático recoge todos los pedidos de una tienda en Squarespace y actualiza automáticamente un archivo Google Sheets.
  - **Complejidad:** Media (8 nodos)

- **[1053-movie-recommendations-agent.json](workflows/1053-movie-recommendations-agent.json)**
  - **Descripción:** Este flujo permite a un asistente de chat obtener recomendaciones de películas mediante el uso de la API de OpenAI y consulta en tiempo real a una base de datos MongoDB.
  - **Complejidad:** Media (8 nodos)

- **[1109-transcripcion-drive-sheets.json](workflows/1109-transcripcion-drive-sheets.json)**
  - **Descripción:** Este flujo automatizado transcribe archivos de voz subidos en Google Drive y guarda el resultado en una hoja de cálculo.
  - **Complejidad:** Media (8 nodos)

- **[1169-gmail-file-monitor.json](workflows/1169-gmail-file-monitor.json)**
  - **Descripción:** Este flujo automático monitoriza correos electrónicos en Gmail y clasifica los archivos adjuntos por tamaño para su posterior manejo, filtrando grandes archivos (mayor a 300MB) o archivos intermedios (entre 10-300MB).
  - **Complejidad:** Media (8 nodos)

- **[1213-youtube-sync.json](workflows/1213-youtube-sync.json)**
  - **Descripción:** Este flujo sincroniza las URLs de videos de YouTube desde canales especificados en Google Sheets hacia otra hoja utilizando la API de YouTube.
  - **Complejidad:** Media (8 nodos)

- **[1217-luma-ai-webhook-process.json](workflows/1217-luma-ai-webhook-process.json)**
  - **Descripción:** Este flujo automatizado recibe una respuesta web de Luma AI a través de un webhook, verifica que contenga un video no vacío y guarda información sobre el mismo (URL del vídeo, miniatura) en Airtable.
  - **Complejidad:** Media (8 nodos)

- **[1233-audio-transcription-process.json](workflows/1233-audio-transcription-process.json)**
  - **Descripción:** Este flujo automático descarga archivos de audio nuevos en Google Drive y los envía para transcribirlos e interpretar sentimientos mediante OpenAI, generando un resumen estructurado que incluye título, contenido principal y análisis.
  - **Complejidad:** Media (8 nodos)

- **[1241-google-drive-sync.json](workflows/1241-google-drive-sync.json)**
  - **Descripción:** Este flujo automático sincroniza los archivos nuevos de una carpeta específica de Google Drive, comparte sus detalles con un destinatario por correo y registra la metadata completa en Airtable para su seguimiento.
  - **Complejidad:** Media (8 nodos)

- **[1482-mongodb-ai-agent-intelligent-movie-recommendations.json](workflows/1482-mongodb-ai-agent-intelligent-movie-recommendations.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Webhook, MongoDB con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (8 nodos)

- **[2694-dominio_icypeas.json](workflows/2694-dominio_icypeas.json)**
  - **Descripción:** Este flujo automatiza la ejecución de un análisis大批量 de dominios utilizando Icypeas. Lee datos desde una hoja de cálculo de Google, autentica en la cuenta de Icypeas y envía una solicitud POST para realizar las búsquedas masivas.
  - **Complejidad:** Media (8 nodos)

- **[2815-luma-video-generator.json](workflows/2815-luma-video-generator.json)**
  - **Descripción:** Este flujo crea videos personalizados utilizando la API de Luma AI Dream Machine. Genera un video basado en un prompt definido globalmente con diferentes opciones de aspecto, duración y movimiento aleatorio. Registra los datos del video en Airtable.
  - **Complejidad:** Media (8 nodos)

- **[2927-convert-squarespace-to-shopify.json](workflows/2927-convert-squarespace-to-shopify.json)**
  - **Descripción:** Este flujo automático convierte perfiles de Squarespace a clientes en Shopify utilizando Google Sheets. Extrae datos desde una hoja de cálculo de Squarespace, procesa y actualiza información en Shopify.
  - **Complejidad:** Media (8 nodos)

- **[2982-amazon-best-seller-electronic-extractor.json](workflows/2982-amazon-best-seller-electronic-extractor.json)**
  - **Descripción:** Este flujo extrae información de los mejores vendedores de Amazon en la categoría de electrónica utilizando Bright Data y Google Gemini para una extracción estructurada de datos.
  - **Complejidad:** Media (8 nodos)

- **[3184-audio-transcription-notion.json](workflows/3184-audio-transcription-notion.json)**
  - **Descripción:** Este flujo automatiza la transcripción de archivos de audio desde Google Drive, utiliza GPT-4 para resumir el contenido y almacena el resumen en Notion.
  - **Complejidad:** Media (8 nodos)

- **[1058-notion-pinecone-embeddings.json](workflows/1058-notion-pinecone-embeddings.json)**
  - **Descripción:** Este flujo supervisa nuevas páginas en Notion, resume el contenido, genera embeddings con dimensión 768 mediante Google Gemini y los inserta en un índice de Pinecone.
  - **Complejidad:** Media (8 nodos)

- **[1502-transcribe-audio-files-summarize-with-gpt-notion.json](workflows/1502-transcribe-audio-files-summarize-with-gpt-notion.json)**
  - **Descripción:** Este flujo permite análisis de sentimientos, transcripción, resumen utilizando OpenAI/GPT, Notion con inteligencia artificial y APIs.
  - **Complejidad:** Media (8 nodos)

- **[0014-monitor-verstappen-tweets.json](workflows/0014-monitor-verstappen-tweets.json)**
  - **Descripción:** Este flujo busca los últimos tweets públicos y privados con la palabra clave 'Verstappen', luego compara esos resultados con una lista existente en Airtable para identificar y guardar solo las nuevas entradas, eliminando duplicados.
  - **Complejidad:** Media (7 nodos)

- **[0131-limpia_pacotes_telegram.json](workflows/0131-limpia_pacotes_telegram.json)**
  - **Descripción:** Este flujo automático ejecuta consultas SQL diarias para limpiar pacotes de transporte en la base de datos 'PPM' y luego actualiza registros antiguos a 'DELETE'. Después, envía un mensaje predefinido al chatId especificado.
  - **Complejidad:** Media (7 nodos)

- **[0392-proteccion-pdf-google.json](workflows/0392-proteccion-pdf-google.json)**
  - **Descripción:** Este flujo descarga automáticamente un PDF demo y lo escribe en disco o sube a Google Drive.
  - **Complejidad:** Media (7 nodos)

- **[0428-libros-historicos-extractor.json](workflows/0428-libros-historicos-extractor.json)**
  - **Descripción:** Este flujo extrae información sobre libros históricos de Toscrape usando Jina.ai y se utiliza el modelo OpenAI ChatGPT para analizar los datos, guardando finalmente los resultados en una hoja de Google.
  - **Complejidad:** Media (7 nodos)

- **[0429-webflow-to-gsheets.json](workflows/0429-webflow-to-gsheets.json)**
  - **Descripción:** Este flujo automatizado recoge datos de envíos de formulario en Webflow y los añade automáticamente como nuevas filas a una hoja de cálculo Google.
  - **Complejidad:** Media (7 nodos)

- **[0452-wordpress-posts-csv.json](workflows/0452-wordpress-posts-csv.json)**
  - **Descripción:** Este flujo automático permite obtener posts publicados de WordPress en formato JSON y convertirlos posteriormente en archivo CSV para subirlo automáticamente al Google Drive.
  - **Complejidad:** Media (7 nodos)

- **[0518-google-drive-pdf-to-html.json](workflows/0518-google-drive-pdf-to-html.json)**
  - **Descripción:** Este flujo automático convierte archivos PDF nuevos guardados en Google Drive a HTML y los guarda automáticamente en la misma carpeta.
  - **Complejidad:** Media (7 nodos)

- **[0658-demo-n8n-flujo.json](workflows/0658-demo-n8n-flujo.json)**
  - **Descripción:** Este flujo demuestra cómo n8n puede usar nodos 'function' para generar datos y nodos 'switch' para crear rutas de respuesta basadas en comparaciones.
  - **Complejidad:** Media (7 nodos)

- **[0725-file-list-processing.json](workflows/0725-file-list-processing.json)**
  - **Descripción:** Este flujo automático se activa manualmente, lee contenido desde el archivo '/home/n8n/filelist.txt', lo divide en líneas usando el carácter de nueva línea y almacena cada elemento en un array llamado 'arrData', luego utiliza la variable $runIndex para ejecutar comandos que imprimen los nombres de archivos basados en este array.
  - **Complejidad:** Media (7 nodos)

- **[0811-jina-scraper-book-extractor.json](workflows/0811-jina-scraper-book-extractor.json)**
  - **Descripción:** Este flujo utiliza Jina.ai para acceder y extraer datos de libros desde webscraping, los procesa con OpenAI y guarda el resultado en Google Sheets.
  - **Complejidad:** Media (7 nodos)

- **[0827-workflow-retriever-qa.json](workflows/0827-workflow-retriever-qa.json)**
  - **Descripción:** Este flujo automático permite hacer consultas sobre cualquier fuente de datos mediante la recuperación de workflows existentes.
  - **Complejidad:** Media (7 nodos)

- **[0993-airtable-telli-ia.json](workflows/0993-airtable-telli-ia.json)**
  - **Descripción:** Este flujo automático conecta Airtable con telli, permitiendo añadir contactos automáticamente desde la base y programar llamadas de voz con IA.
  - **Complejidad:** Media (7 nodos)

- **[1019-obsidian-airtable-agent.json](workflows/1019-obsidian-airtable-agent.json)**
  - **Descripción:** Este flujo permite obtener datos de Airtable y generar notas en Obsidian utilizando un modelo de chat de OpenAI.
  - **Complejidad:** Media (7 nodos)

- **[1037-gsc-weekly-report.json](workflows/1037-gsc-weekly-report.json)**
  - **Descripción:** Este flujo automático ejecuta un informe de SEO semanal basado en datos del Google Search Console y lo envía por correo electrónico.
  - **Complejidad:** Media (7 nodos)

- **[1056-test_pdf.json](workflows/1056-test_pdf.json)**
  - **Descripción:** Este flujo permite combinar múltiples PDFs en un solo documento y escribirlo en el sistema de archivos.
  - **Complejidad:** Media (7 nodos)

- **[1173-retell-webhook-response.json](workflows/1173-retell-webhook-response.json)**
  - **Descripción:** Este flujo automático utiliza una webhook para recibir datos de llamadas entrantes en Retell y buscar al usuario correspondiente en un archivo Google Sheets, respondiendo con los datos necesarios.
  - **Complejidad:** Media (7 nodos)

- **[1184-google-drive-image-tagging.json](workflows/1184-google-drive-image-tagging.json)**
  - **Descripción:** Este flujo n8n analiza automáticamente el contenido de imágenes en Google Drive usando una API AI y escribe los resultados como etiquetas (Subject/Keywords) en la metadata EXIF.
  - **Complejidad:** Media (7 nodos)

- **[1189-sheets-automation.json](workflows/1189-sheets-automation.json)**
  - **Descripción:** Este flujo automatizado permite leer datos de una hoja de Google Sheets utilizando búsqueda, luego modificar el valor de 'Rent' en los registros encontrados y actualizarlos.
  - **Complejidad:** Media (7 nodos)

- **[1211-covid_automated_import.json](workflows/1211-covid_automated_import.json)**
  - **Descripción:** Este flujo automatiza la importación puntual de datos COVID-19 específicos (DACH: Alemania, Austria, Suiza) del año 2023 desde una fuente externa a Google Sheets.
  - **Complejidad:** Media (7 nodos)

- **[1220-ai-cv-screening-process.json](workflows/1220-ai-cv-screening-process.json)**
  - **Descripción:** Este flujo automático permite al formulario de solicitud capturar información sobre candidatos para la posición de Software Engineer, procesar el CV subido y enviar un análisis detallado con IA a los usuarios. Luego envía confirmaciones por correo al candidato y notifica a HR sobre nuevas solicitudes. Finalmente, guarda todos estos datos en una hoja de Google Sheets.
  - **Complejidad:** Media (7 nodos)

- **[1230-squarespace-sync.json](workflows/1230-squarespace-sync.json)**
  - **Descripción:** Automatiza la extracción y actualización en tiempo real del contenido de blogs y eventos de Squarespace a Google Sheets.
  - **Complejidad:** Media (7 nodos)

- **[1428-ai-powered-web-scraping-with-google-sheets-openai.json](workflows/1428-ai-powered-web-scraping-with-google-sheets-openai.json)**
  - **Descripción:** Este flujo permite chatbot, web scraping, extracción de datos utilizando OpenAI/GPT, Google Sheets, YouTube con inteligencia artificial y APIs.
  - **Complejidad:** Media (7 nodos)

- **[1471-get-airtable-data-via-ai-and-obsidian-notes.json](workflows/1471-get-airtable-data-via-ai-and-obsidian-notes.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Webhook, Airtable con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (7 nodos)

- **[2554-x-influencers-list.json](workflows/2554-x-influencers-list.json)**
  - **Descripción:** Este flujo automatizado permite buscar influencers en X utilizando Airtop, extraer sus datos de forma estructurada, deduplicar los resultados e incorporarlos a un documento de Google mediante la hoja de cálculo.
  - **Complejidad:** Media (7 nodos)

- **[2583-prospectlens_company_research.json](workflows/2583-prospectlens_company_research.json)**
  - **Descripción:** Este flujo automático utiliza la API de ProspectLens para obtener datos de empresas y actualizar una hoja de cálculo en Google Sheets manteniendo un registro del momento de procesamiento.
  - **Complejidad:** Media (7 nodos)

- **[2658-agente-contact-ai.json](workflows/2658-agente-contact-ai.json)**
  - **Descripción:** Este flujo permite al agente de IA interactuar con Airtable usando búsqueda o actualización de contactos.
  - **Complejidad:** Media (7 nodos)

- **[2713-chat-agent-postgres.json](workflows/2713-chat-agent-postgres.json)**
  - **Descripción:** Este flujo utiliza un agente de lenguaje para procesar mensajes en chat, empleando memoria simple y una base de datos PostgreSQL para respaldar consultas SQL generadas por el sistema.
  - **Complejidad:** Media (7 nodos)

- **[2737-stripe-payment-link.json](workflows/2737-stripe-payment-link.json)**
  - **Descripción:** Este flujo crea un producto en Stripe y genera un enlace de pago basado en los datos del formulario enviado. Configura la moneda y el precio, luego crea el producto y finalmente redirige al usuario.
  - **Complejidad:** Media (7 nodos)

- **[0193-user-request-management.json](workflows/0193-user-request-management.json)**
  - **Descripción:** Este flujo automatizado maneja solicitudes de usuario provenientes de un formulario Typeform y las clasifica en diferentes tipos (Documentación, Presentación, etc.) para procesarlas adecuadamente en ClickUp.
  - **Complejidad:** Media (7 nodos)

- **[0241-shopify-zendesk-sync.json](workflows/0241-shopify-zendesk-sync.json)**
  - **Descripción:** Este flujo verifica si un pedido de Shopify ya existe en Zendesk. Si no se encuentra, crea un nuevo ticket con la información del pedido y actualiza el flujo.
  - **Complejidad:** Media (7 nodos)

- **[0245-workflow-zendesk-asana.json](workflows/0245-workflow-zendesk-asana.json)**
  - **Descripción:** Este flujo automático verifica si una tarea Asana ya existe en base a un campo personalizado de Zendesk, y actualiza el ticket con la información correspondiente.
  - **Complejidad:** Media (7 nodos)

- **[0249-zendesk-github-integration.json](workflows/0249-zendesk-github-integration.json)**
  - **Descripción:** Este flujo automatizado sincroniza tickets de Zendesk con problemas y comentarios en GitHub.
  - **Complejidad:** Media (7 nodos)

- **[0250-zendesk-jira-integracion.json](workflows/0250-zendesk-jira-integracion.json)**
  - **Descripción:** Este flujo automático integra Zendesk y Jira: si un ticket en Zendesk ya tiene asociado un Jira Issue Key, se añade un comentario a esa issue existente; si no existe, se crea automáticamente una nueva issue en Jira basada en el ticket de Zendesk.
  - **Complejidad:** Media (7 nodos)

- **[0881-github-trending-scraping.json](workflows/0881-github-trending-scraping.json)**
  - **Descripción:** Este flujo permite extraer los 13 repositorios más populares de GitHub Trend, almacenando información como autor, título, lenguaje y descripción para su uso en monitorización o análisis.
  - **Complejidad:** Media (7 nodos)

- **[1044-line-customer-service-whatsapp-asana.json](workflows/1044-line-customer-service-whatsapp-asana.json)**
  - **Descripción:** Este flujo automático permite integrar respuestas de formularios WhatsApp con la creación de tareas en Asana para el seguimiento de incidencias.
  - **Complejidad:** Media (7 nodos)

- **[2747-correo_n8n_version.json](workflows/2747-correo_n8n_version.json)**
  - **Descripción:** Este flujo programa un correo electrónico diario con la versión más estable de n8n obtenida de GitHub.
  - **Complejidad:** Media (7 nodos)

- **[0969-ats-ai-assessment.json](workflows/0969-ats-ai-assessment.json)**
  - **Descripción:** Este flujo automático procesa solicitudes de candidatos extraídos de formularios, analiza sus datos personales y calificaciones mediante modelos de Google Gemini, asigna experiencias por funciones usando un extractor LLM, evalúa su alineación con descripciones de roles específicos en Notion ATS, genera evaluaciones estructuradas y actualiza registros tanto en Notion como en Google Sheets.
  - **Complejidad:** Media (6 nodos)

- **[1242-ultimate-scraper-workflow.json](workflows/1242-ultimate-scraper-workflow.json)**
  - **Descripción:** Este flujo automático permite extraer información de cualquier página web, ya sea pública o privada, utilizando técnicas avanzadas como la automatización del navegador.Selenium y análisis con modelos de lenguaje de OpenAI. Ideal para proyectos que requieren recopilar datos detras de WAFs.
  - **Complejidad:** Media (6 nodos)

- **[2555-workflow-docs.json](workflows/2555-workflow-docs.json)**
  - **Descripción:** Este flujo automático permite a n8n generar y mantener documentación de workflows mediante Docsify, creando archivos Markdown basados en los datos del workflow.
  - **Complejidad:** Media (6 nodos)

- **[2998-notion-clockify-sync.json](workflows/2998-notion-clockify-sync.json)**
  - **Descripción:** Este flujo sincroniza datos entre Notion y Clockify, manejando clientes, proyectos y tareas. Actualiza estados y IDs de manera bidireccional.
  - **Complejidad:** Media (6 nodos)

- **[3045-selenium_scraping_automatizado.json](workflows/3045-selenium_scraping_automatizado.json)**
  - **Descripción:** Este flujo automatiza la extracción de datos web utilizando Selenium y OpenAI. Busca URLs relevantes en una página dada, extrae información con IA, maneja cookies y sesiones para logueo opcional, toma capturas de pantalla y detecta posibles bloqueos por WAF.
  - **Complejidad:** Media (6 nodos)

- **[0095-sequential-http-post.json](workflows/0095-sequential-http-post.json)**
  - **Descripción:** Este flujo permite iniciar manualmente la ejecución, obtener todos los datos de clientes desde un almacenamiento, dividirlos en lotes individuales y enviar cada uno mediante una solicitud HTTP POST a la API de JSONPlaceholder.
  - **Complejidad:** Media (6 nodos)

- **[0185-datos-binarios-descomprimidos.json](workflows/0185-datos-binarios-descomprimidos.json)**
  - **Descripción:** Este flujo automático descarga un archivo ZIP que contiene datos binarios y los divide en elementos individuales, cada uno con una única secuencia de datos binarios bajo la clave 'data'.
  - **Complejidad:** Media (6 nodos)

- **[0194-customer-data-processing.json](workflows/0194-customer-data-processing.json)**
  - **Descripción:** Este flujo de trabajo utiliza un desencadenador manual para obtener datos de clientes desde el 'Customer Datastore' y luego los edita en una variable mediante el nodo Set.
  - **Complejidad:** Media (6 nodos)

- **[0196-airtable-insert-update.json](workflows/0196-airtable-insert-update.json)**
  - **Descripción:** Este flujo automático inserta un registro inicial en la tabla Table 1 de Airtable, luego lista registros filtrados por el campo 'Name' igual a 'n8n', y finalmente actualiza el primer registro encontrado con los valores definidos en el paso Set.
  - **Complejidad:** Media (6 nodos)

- **[0197-snowflake-table-management.json](workflows/0197-snowflake-table-management.json)**
  - **Descripción:** Este flujo automático permite crear una tabla en Snowflake y realizar inserciones e actualizaciones de datos utilizando operaciones definidas previamente.
  - **Complejidad:** Media (6 nodos)

- **[0200-users-api-spreadsheet.json](workflows/0200-users-api-spreadsheet.json)**
  - **Descripción:** Este flujo utiliza la API de randomuser.me para obtener datos y luego los extrae en formato JSON. Posteriormente, actualiza una hoja de cálculo Google con estos valores y también genera un archivo CSV.
  - **Complejidad:** Media (6 nodos)

- **[0210-google-sheets-data-preparation.json](workflows/0210-google-sheets-data-preparation.json)**
  - **Descripción:** Este flujo procesa datos provenientes del nodo 'Customer Datastore' para prepararlos antes de realizar una operación UPSERT en Google Sheets. El formato de los campos se ajusta: el campo 'name' del input se renombra a 'Full name', y se añade un nuevo campo 'Created time' con la fecha actual.
  - **Complejidad:** Media (6 nodos)

- **[0237-firestore-document-management.json](workflows/0237-firestore-document-management.json)**
  - **Descripción:** Este flujo automatizado permite crear y actualizar documentos en Google Cloud Firestore.
  - **Complejidad:** Media (6 nodos)

- **[0238-nextcloud-spreadsheet.json](workflows/0238-nextcloud-spreadsheet.json)**
  - **Descripción:** Este flujo automático permite descargar un archivo de Excel desde NextCloud, procesarlo y subirlo nuevamente a la misma ubicación después de integrar datos.
  - **Complejidad:** Media (6 nodos)

- **[0267-imagenes-line-merge.json](workflows/0267-imagenes-line-merge.json)**
  - **Descripción:** Este flujo automático descarga múltiples imágenes de ejemplo mediante solicitudes HTTP y las fusiona en un único resultado que contiene todos los datos binarios concatenados.
  - **Complejidad:** Media (6 nodos)

- **[0287-google-drive-summarizer.json](workflows/0287-google-drive-summarizer.json)**
  - **Descripción:** Este flujo permite descargar y procesar un archivo de Google Drive para generar resúmenes utilizando cadenas de sumarización.
  - **Complejidad:** Media (6 nodos)

- **[0361-workflow-error-config.json](workflows/0361-workflow-error-config.json)**
  - **Descripción:** Este flujo actualiza la configuración de manejo de errores en workflows mediante Postgres y utiliza variables predefinidas para excluir ciertos casos.
  - **Complejidad:** Media (6 nodos)

- **[0381-airtable-seo-metatags.json](workflows/0381-airtable-seo-metatags.json)**
  - **Descripción:** Este flujo automatizado busca en Airtable los registros que no tienen URL ni título/metadata de descripción definidos y actualiza esos campos con valores reales extraídos desde el contenido web.
  - **Complejidad:** Media (6 nodos)

- **[0387-convertir-docx-a-pdf.json](workflows/0387-convertir-docx-a-pdf.json)**
  - **Descripción:** Este flujo automático permite convertir archivos DOCX enlazados de una URL remota al formato PDF utilizando ConvertAPI.
  - **Complejidad:** Media (6 nodos)

- **[0406-zigbee-backups-schedule.json](workflows/0406-zigbee-backups-schedule.json)**
  - **Descripción:** Este flujo automático realiza copias de seguridad semanalmente (todos los lunes a las 2:45 am) mediante mensajes MQTT, descodifica la respuesta JSON para obtener el archivo ZIP y lo sube automáticamente a un servidor SFTP.
  - **Complejidad:** Media (6 nodos)

- **[0477-n8n-workflow-backup-schedule.json](workflows/0477-n8n-workflow-backup-schedule.json)**
  - **Descripción:** Este flujo automatizado realiza copias de seguridad diarias a las 1:30 AM de todos los workflows de n8n en un archivo JSON y lo guarda en una carpeta especificada de Google Drive.
  - **Complejidad:** Media (6 nodos)

- **[0483-mailchimp-google-sheets-newsletter.json](workflows/0483-mailchimp-google-sheets-newsletter.json)**
  - **Descripción:** Este flujo automatizado procesa nuevas suscripciones a la newsletter en Google Sheets y las añade como contactos activos en Mailchimp.
  - **Complejidad:** Media (6 nodos)

- **[0545-google-page-entity-extraction.json](workflows/0545-google-page-entity-extraction.json)**
  - **Descripción:** Este flujo analiza el contenido HTML de cualquier página web para extraer datos estructurados sobre entidades reconocidas por Google.
  - **Complejidad:** Media (6 nodos)

- **[0652-product-feedback-workflow.json](workflows/0652-product-feedback-workflow.json)**
  - **Descripción:** Este flujo automatizado recoge comentarios y valoraciones sobre un producto a través de Typeform, los almacena en Airtable y, cuando el puntaje es igual a 7, crea una tarjeta en Trello con la información proporcionada.
  - **Complejidad:** Media (6 nodos)

- **[0663-iot-mqtt-influxdb-monitoring.json](workflows/0663-iot-mqtt-influxdb-monitoring.json)**
  - **Descripción:** Este flujo automatizado recibe datos de sensores IoT remotos a través de un tema MQTT 'wokwi-weather', procesa y validan las lecturas de temperatura y humedad, luego escribe estos valores en formato JSON en una base de datos InfluxDB.
  - **Complejidad:** Media (6 nodos)

- **[0694-orbit-import-from-sheets.json](workflows/0694-orbit-import-from-sheets.json)**
  - **Descripción:** Este flujo automatizado importa datos de miembros y actividades desde Google Sheets a la plataforma Orbit utilizando credenciales OAuth2.
  - **Complejidad:** Media (6 nodos)

- **[0723-gmail-expenses-mindee.json](workflows/0723-gmail-expenses-mindee.json)**
  - **Descripción:** Este flujo verifica correos electrónicos en Gmail que contienen palabras clave como 'expenses' o 'recibo', extrae datos de facturas usando la API Mindee y agrega automáticamente los detalles a una hoja de Google.
  - **Complejidad:** Media (6 nodos)

- **[1110-nicepng-text-analysis.json](workflows/1110-nicepng-text-analysis.json)**
  - **Descripción:** Este flujo analiza un archivo PNG de motivational quotes con AWS Rekognition para detectar texto, luego extrae el nombre y enlace de la imagen a través de una solicitud HTTP e incorpora todo junto los textos detectados (convertidos a minúsculas) en Google Sheets mediante OAuth2.
  - **Complejidad:** Media (6 nodos)

- **[1142-s3-lista-archivos.json](workflows/1142-s3-lista-archivos.json)**
  - **Descripción:** Este flujo automatizado permite descargar todos los archivos de una carpeta específica de Amazon S3 y comprimirlos en un archivo ZIP para facilitar su descarga o procesamiento posterior.
  - **Complejidad:** Media (6 nodos)

- **[0127-github-release-to-gitlab-issue.json](workflows/0127-github-release-to-gitlab-issue.json)**
  - **Descripción:** Este flujo monitoriza las últimas publicaciones de un repositorio de GitHub semanalmente y verifica si existe una incidencia correspondiente en el repositorio GitLab adjunto. Si no hay coincidencia, crea automáticamente una nueva incidencia.
  - **Complejidad:** Media (6 nodos)

- **[0668-wekan-board-creation.json](workflows/0668-wekan-board-creation.json)**
  - **Descripción:** Este flujo automático permite a un usuario ejecutar manualmente el proceso de creación de tableros Wekan, listas y tarjetas.
  - **Complejidad:** Media (6 nodos)

- **[0717-rag-chatbot-docs.json](workflows/0717-rag-chatbot-docs.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de IA mantener una conversación contextualizada usando documentos almacenados en Google Drive y Qdrant. Extrae metadatos relevantes como temas principales, puntos dolorosos e información clave para mejorar la búsqueda semántica y las respuestas del asistente.
  - **Complejidad:** Media (5 nodos)

- **[0808-airtable-dynamic-prompts-llm.json](workflows/0808-airtable-dynamic-prompts-llm.json)**
  - **Descripción:** Este flujo automático permite al usuario generar y mantener un esquema dinámico de campos en una tabla de Airtable mediante webhooks, optimizando la actualización con LLM solo cuando son necesarios.
  - **Complejidad:** Media (5 nodos)

- **[0941-techradar-ai-agent.json](workflows/0941-techradar-ai-agent.json)**
  - **Descripción:** Este flujo automático maneja la tecnología corporativa para tres empresas, manteniendo actualizados los registros en base de datos SQL y almacenamiento vectorial Pinecone. Se ejecuta cada mes un cron job que sincroniza los datos desde Google Sheets eliminando registros antiguos.
  - **Complejidad:** Media (5 nodos)

- **[1258-pdf-to-vector-store.json](workflows/1258-pdf-to-vector-store.json)**
  - **Descripción:** Convierte un PDF en datos vectoriales para búsquedas posteriores.
  - **Complejidad:** Media (5 nodos)

- **[1276-airtable-pdf-llm-update.json](workflows/1276-airtable-pdf-llm-update.json)**
  - **Descripción:** Actualiza registros de Airtable con datos extraídos de PDFs mediante LLM.
  - **Complejidad:** Media (5 nodos)

- **[2575-wordpress-ai-chatbot.json](workflows/2575-wordpress-ai-chatbot.json)**
  - **Descripción:** Este flujo automático permite crear y mantener embeddings de contenido de WordPress en Supabase, utilizando modelos OpenAI para responder preguntas con información contextualizada.
  - **Complejidad:** Media (5 nodos)

- **[2704-switchy-url-shortener.json](workflows/2704-switchy-url-shortener.json)**
  - **Descripción:** Este flujo procesa URLs para generar y acortarlas utilizando Switchy.io. Analiza metadatos, verifica seguridad con Norton y Bitdefender, y maneja diferentes modos de imagen OpenGraph.
  - **Complejidad:** Media (5 nodos)

- **[3041-online-marketing-report.json](workflows/3041-online-marketing-report.json)**
  - **Descripción:** Este flujo automático genera un informe semanal de marketing digital que recopila y analiza datos de Google Analytics, Google Ads y Meta Ads. Utiliza sub-flujos para obtener métricas actuales y del año pasado, procesa la información con OpenAI y envía el reporte por correo electrónico.
  - **Complejidad:** Media (5 nodos)

- **[3090-app-wordpress-genai.json](workflows/3090-app-wordpress-genai.json)**
  - **Descripción:** Este flujo implementa una aplicación que utiliza tecnologías de RAG (Retrieval-Augmented Generation) y GenAI para interactuar con contenido de WordPress. Extrae embeddings de texto, gestiona documentos en Supabase y mantiene memoria del chat usando PostgreSQL.
  - **Complejidad:** Media (5 nodos)

- **[0018-entrevistas-y-participantes.json](workflows/0018-entrevistas-y-participantes.json)**
  - **Descripción:** Este flujo procesa dos conjuntos de datos separados que contienen información sobre entrevistas y sus participantes, convirtiendo cada entrada individual en un objeto independiente para luego fusionarlos basándose en claves específicas.
  - **Complejidad:** Media (5 nodos)

- **[0142-xml-to-json-dropbox.json](workflows/0142-xml-to-json-dropbox.json)**
  - **Descripción:** Este flujo toma datos XML desde una URL, los convierte a formato JSON utilizando el nodo 'To JSON', luego actualiza el título del mensaje con el parámetro 'Change title' y finalmente sube el contenido JSON al Dropbox usando la ruta especificada.
  - **Complejidad:** Media (5 nodos)

- **[0165-hashtag-tweet-generator.json](workflows/0165-hashtag-tweet-generator.json)**
  - **Descripción:** Este flujo selecciona aleatoriamente un hashtag de una lista predefinida, genera un tweet utilizando la API de OpenAI y lo guarda en una tabla de Airtable.
  - **Complejidad:** Media (5 nodos)

- **[0174-adobesign-webhook-data.json](workflows/0174-adobesign-webhook-data.json)**
  - **Descripción:** Este flujo automatizado configura una respuesta webhook que incluye la variable clientID y extrae datos específicos del cuerpo JSON sobre acuerdos y participantes.
  - **Complejidad:** Media (5 nodos)

- **[0209-google-search-url-generator.json](workflows/0209-google-search-url-generator.json)**
  - **Descripción:** Este flujo utiliza el nodo Webhook para recibir datos de entrada, luego crea una URL concatenando esos valores (primera y última letra) para generar una búsqueda en Google, y finalmente responde al webhook mostrando la URL generada.
  - **Complejidad:** Media (5 nodos)

- **[0219-company-data-airtable.json](workflows/0219-company-data-airtable.json)**
  - **Descripción:** Este flujo extrae el logo, icon y datos de una empresa usando Brandfetch, y los almacena automáticamente en una tabla de Airtable.
  - **Complejidad:** Media (5 nodos)

- **[0259-mysql-export-spreadsheet.json](workflows/0259-mysql-export-spreadsheet.json)**
  - **Descripción:** Este flujo automatiza la descarga de datos de una tabla MySQL específica en formato Excel, permitiendo así almacenar el contenido del catálogo.
  - **Complejidad:** Media (5 nodos)

- **[0292-snowflake-csv-insert.json](workflows/0292-snowflake-csv-insert.json)**
  - **Descripción:** Este flujo carga datos desde un archivo CSV alojado en Azure Blob Storage, los procesa y luego inserta las columnas especificadas en la tabla 'users' de Snowflake.
  - **Complejidad:** Media (5 nodos)

- **[0320-dingtalk-tfs-automation.json](workflows/0320-dingtalk-tfs-automation.json)**
  - **Descripción:** Este flujo automatizado envía una notificación por DingTalk cuando se crea un nuevo Pull Request en Azure DevOps, utilizando mapas de base de datos MySQL para traducir cuentas de usuario.
  - **Complejidad:** Media (5 nodos)

- **[0385-convertapi-docx2pdf.json](workflows/0385-convertapi-docx2pdf.json)**
  - **Descripción:** Este flujo automático descarga un archivo DOCX desde una URL y lo convierte a PDF usando las credenciales de ConvertAPI para luego escribirlo en el sistema de archivos.
  - **Complejidad:** Media (5 nodos)

- **[0388-scrappey-test-schedule.json](workflows/0388-scrappey-test-schedule.json)**
  - **Descripción:** Este flujo automatizado programa un proceso de prueba cada cierto tiempo para extraer datos mediante la API de Scrappey.
  - **Complejidad:** Media (5 nodos)

- **[0390-convertapi-xlsx-to-pdf-test.json](workflows/0390-convertapi-xlsx-to-pdf-test.json)**
  - **Descripción:** Este flujo automático permite probar la conversión de archivos XLSX a PDF utilizando una API pública.
  - **Complejidad:** Media (5 nodos)

- **[0502-chart-upload.json](workflows/0502-chart-upload.json)**
  - **Descripción:** Este flujo crea dinámicamente un gráfico de línea a partir de datos JSON y lo sube al Google Drive.
  - **Complejidad:** Media (5 nodos)

- **[0524-mattermost-instagram-stats.json](workflows/0524-mattermost-instagram-stats.json)**
  - **Descripción:** Este flujo automático verifica las estadísticas de un perfil Instagram (como seguidores y posts) cada día a las 8:00 AM y envía los datos actualizados en un mensaje formateado con fecha y hora actuales.
  - **Complejidad:** Media (5 nodos)

- **[0537-shopify-odoo-product-sync.json](workflows/0537-shopify-odoo-product-sync.json)**
  - **Descripción:** Este flujo sincroniza automáticamente productos nuevos de Shopify con Odoo. Se activa cuando se crea un producto en Shopify (evento 'products/create') y busca si ya existe en Odoo mediante el código por defecto. Si no existe, lo crea; si ya existe, verifica los datos del producto para realizar una actualización.
  - **Complejidad:** Media (5 nodos)

- **[0598-expense-receipt-automation.json](workflows/0598-expense-receipt-automation.json)**
  - **Descripción:** Este flujo automático recoge recibos a través de Typeform, extrae información relevante usando Mindee y almacena los datos en Airtable.
  - **Complejidad:** Media (5 nodos)

- **[0612-workflow-n8n-581.json](workflows/0612-workflow-n8n-581.json)**
  - **Descripción:** Este flujo inicia con un trigger manual, procesa datos a través de una función que devuelve dos objetos (con IDs 0 y 1), y luego utiliza un nodo condicional para evaluar si el valor 'value1' coincide con los resultados esperados.
  - **Complejidad:** Media (5 nodos)

- **[0639-dropbox-http-image.json](workflows/0639-dropbox-http-image.json)**
  - **Descripción:** Este flujo n8n permite la interacción con Dropbox mediante una solicitud HTTP, primero listando archivos de un directorio y luego subiendo un archivo específico.
  - **Complejidad:** Media (5 nodos)

- **[0641-nextcloud-http-image-upload.json](workflows/0641-nextcloud-http-image-upload.json)**
  - **Descripción:** Este flujo permite descargar una imagen desde un servidor HTTP y luego subirla a la carpeta 'n8n' en NextCloud, así como guardarla directamente con el nombre especificado.
  - **Complejidad:** Media (5 nodos)

- **[0722-compression-to-dropbox.json](workflows/0722-compression-to-dropbox.json)**
  - **Descripción:** Este flujo automatizado descarga dos imágenes de URLs HTTP, las comprime en un archivo ZIP y luego sube el resultado a Dropbox.
  - **Complejidad:** Media (5 nodos)

- **[0857-calendar-event-automation.json](workflows/0857-calendar-event-automation.json)**
  - **Descripción:** Este flujo automático crea eventos en Google Calendar a partir de datos insertados en una hoja de cálculo Google Sheets.
  - **Complejidad:** Media (5 nodos)

- **[0963-copiar-documentos-escaneados-json.json](workflows/0963-copiar-documentos-escaneados-json.json)**
  - **Descripción:** Este flujo automático copia documentos escaneados de un servidor vía HTTP a la cuenta de Nextcloud.
  - **Complejidad:** Media (5 nodos)

- **[0967-comparador-sql.json](workflows/0967-comparador-sql.json)**
  - **Descripción:** Este flujo compara dos conjuntos de datos SQL basados en el número de cliente y año, utilizando una opción para manejar múltiples coincidencias.
  - **Complejidad:** Media (5 nodos)

- **[1049-pdf-to-text-converter.json](workflows/1049-pdf-to-text-converter.json)**
  - **Descripción:** Convierte archivos PDF en texto utilizando un plugin personalizado y una entrada HTML.
  - **Complejidad:** Media (5 nodos)

- **[1066-openai-tweet-generator.json](workflows/1066-openai-tweet-generator.json)**
  - **Descripción:** Este flujo utiliza OpenAI para generar tweets basados en hashtags seleccionados aleatoriamente y luego los guarda automáticamente en una base de Airtable.
  - **Complejidad:** Media (5 nodos)

- **[1072-openweathermap-airtable-weather.json](workflows/1072-openweathermap-airtable-weather.json)**
  - **Descripción:** Este flujo automático obtiene datos meteorológicos diarios de la API de OpenWeatherMap y los almacena en una tabla de Airtable.
  - **Complejidad:** Media (5 nodos)

- **[1088-zip-multiple-files.json](workflows/1088-zip-multiple-files.json)**
  - **Descripción:** Este flujo comprime múltiples archivos en un archivo ZIP dinámico con n8n.
  - **Complejidad:** Media (5 nodos)

- **[1155-sharepoint-token-fetch.json](workflows/1155-sharepoint-token-fetch.json)**
  - **Descripción:** Este flujo automático obtiene tokens de autenticación para acceder a una lista SharePoint y permite ejecutar operaciones programadas con ellos.
  - **Complejidad:** Media (5 nodos)

- **[1253-notion-clickup-sync.json](workflows/1253-notion-clickup-sync.json)**
  - **Descripción:** Este flujo sincroniza tareas entre Notion y ClickUp. Cuando una página de la base de datos en Notion se actualiza, el estado de la tarea correspondiente en ClickUp es actualizado, y viceversa.
  - **Complejidad:** Media (5 nodos)

- **[1465-extract-license-plate-number-from.json](workflows/1465-extract-license-plate-number-from.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (5 nodos)

- **[1483-openai-powered-tweet-generator.json](workflows/1483-openai-powered-tweet-generator.json)**
  - **Descripción:** Este flujo permite generación de contenido utilizando OpenAI/GPT, Airtable, Twitter/X con inteligencia artificial y APIs.
  - **Complejidad:** Media (5 nodos)

- **[2610-icp_linkedin_scoring.json](workflows/2610-icp_linkedin_scoring.json)**
  - **Descripción:** Este flujo n8n calcula automáticamente la puntuación de Ideal Customer Profile (ICP) para empresas basada en sus páginas de LinkedIn, utilizando Airtop para el análisis y Google Sheets para almacenar e integrar los datos.
  - **Complejidad:** Media (5 nodos)

- **[2833-icp_scoring_workflow.json](workflows/2833-icp_scoring_workflow.json)**
  - **Descripción:** Este flujo automatiza la puntuación de ICP recolectando y procesando datos de perfiles de LinkedIn. Primero, utiliza Google Sheets para obtener información personal, luego extrae detalles del perfil de LinkedIn y calcula una puntuación ICP basada en intereses en AI, nivel técnico y seniority.
  - **Complejidad:** Media (5 nodos)

- **[3031-google-drive-summarizer.json](workflows/3031-google-drive-summarizer.json)**
  - **Descripción:** Este flujo descarga un archivo de Google Drive, lo sumaiza utilizando Mistral AI y envía el resumen por correo electrónico.
  - **Complejidad:** Media (5 nodos)

- **[0330-monday-error-tracking.json](workflows/0330-monday-error-tracking.json)**
  - **Descripción:** Este flujo automático detecta cuando ocurre un error durante el procesamiento de ejecuciones, captura su stack trace y mensaje, y luego actualiza automáticamente un ítem en Monday.com con esta información.
  - **Complejidad:** Media (5 nodos)

- **[1093-n8n-git-automation.json](workflows/1093-n8n-git-automation.json)**
  - **Descripción:** Este flujo automático permite añadir un archivo README.md y realizar el primer commit seguido de un push en GitHub cuando se ejecuta manualmente.
  - **Complejidad:** Media (5 nodos)

- **[0809-baserow-pdf-extractor.json](workflows/0809-baserow-pdf-extractor.json)**
  - **Descripción:** Este flujo automático permite a un usuario extraer datos de PDF utilizando prompts dinámicos en una tabla Baserow.
  - **Complejidad:** Baja (4 nodos)

- **[0872-estudio-descomposicion-documents-n8n.json](workflows/0872-estudio-descomposicion-documents-n8n.json)**
  - **Descripción:** Este flujo automatizado permite al sistema procesar documentos subidos en un directorio especificado, dividirlos en bloques de texto, vectorizar su contenido y luego generar diferentes tipos de materiales de estudio como guías o cronologías utilizando modelos de lenguaje AI. Finalmente exporta estos archivos generados junto con el original.
  - **Complejidad:** Baja (4 nodos)

- **[0908-ai-interviews-n8n.json](workflows/0908-ai-interviews-n8n.json)**
  - **Descripción:** Este flujo automático con n8n permite realizar entrevistas conversacionales con un agente de IA que dinámicamente pregunta y registra respuestas en Redis, usando formularios para capturar información. Las respuestas se guardan en Google Sheets.
  - **Complejidad:** Baja (4 nodos)

- **[0913-google-maps-leads-generator.json](workflows/0913-google-maps-leads-generator.json)**
  - **Descripción:** Este flujo automático utiliza la API de Google Maps para buscar lugares basados en categorías y códigos postales específicos, extrayendo datos relevantes e insertándolos en una hoja de Google Sheets con mecanismos de control anti-duplicado y manejo exponencial de errores.
  - **Complejidad:** Baja (4 nodos)

- **[0934-ai-logo-sheet-extractor.json](workflows/0934-ai-logo-sheet-extractor.json)**
  - **Descripción:** Este flujo automático permite extraer información de imágenes que muestran tablas de logotipos, identificando herramientas y sus atributos para guardarlos en Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[0984-ai-logo-extractor.json](workflows/0984-ai-logo-extractor.json)**
  - **Descripción:** Este flujo automático permite extraer información de una imagen con múltiples logotipos utilizando IA, y guardarla en tablas estructuradas de Airtable para categorizar herramientas.
  - **Complejidad:** Baja (4 nodos)

- **[1122-wordpress-auto-generation.json](workflows/1122-wordpress-auto-generation.json)**
  - **Descripción:** Este flujo automático selecciona la categoría menos utilizada de WordPress desde una base de datos PostgreSQL para generar artículos únicos y estructurados mediante modelos GPT. Después de crear el contenido completo en formato HTML específico, genera un título optimizado y descarga/adjunta una imagen destacada antes de publicar todo junto.
  - **Complejidad:** Baja (4 nodos)

- **[1270-email-header-analyzer.json](workflows/1270-email-header-analyzer.json)**
  - **Descripción:** Analiza los encabezados de un correo para obtener metadatos.
  - **Complejidad:** Baja (4 nodos)

- **[1271-email-header-analyzer.json](workflows/1271-email-header-analyzer.json)**
  - **Descripción:** Analiza los encabezados de un correo para obtener metadatos.
  - **Complejidad:** Baja (4 nodos)

- **[1272-ai_airtable_agent.json](workflows/1272-ai_airtable_agent.json)**
  - **Descripción:** Agente de IA que gestiona registros en Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[1445-breakdown-documents-into-study-notes.json](workflows/1445-breakdown-documents-into-study-notes.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, extracción de datos, generación de contenido utilizando Webhook, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (4 nodos)

- **[2603-suspicious-login-detection.json](workflows/2603-suspicious-login-detection.json)**
  - **Descripción:** Este flujo n8n detecta logins sospechosos de cuentas mediante la integración de datos de IP-API, UserParser y GreyNoise. Analiza ubicaciones nuevas o dispositivos/browser diferentes para determinar si es un intento fraudulento.
  - **Complejidad:** Baja (4 nodos)

- **[2670-n8n_creators_leaderboard_stats.json](workflows/2670-n8n_creators_leaderboard_stats.json)**
  - **Descripción:** Este flujo automatiza la obtención y procesamiento de datos estadísticos del tablero de n8n creadores para generar informes detallados en formato Markdown sobre las contribuciones específicas de un usuario.
  - **Complejidad:** Baja (4 nodos)

- **[2679-chatgpt-email-sheets.json](workflows/2679-chatgpt-email-sheets.json)**
  - **Descripción:** Este flujo automático gestiona las respuestas de ChatGPT a correos electrónicos específicos y registra interacciones en Google Sheets.
  - **Complejidad:** Baja (4 nodos)

- **[2731-woocommerce-chatbot.json](workflows/2731-woocommerce-chatbot.json)**
  - **Descripción:** Este flujo automático permite a un chatbot recuperar y mostrar información de pedidos de WooCommerce basada en la dirección de correo electrónico del usuario. Utiliza herramientas de encriptación para proteger los datos sensibles y servicios como DHL para el seguimiento de envíos.
  - **Complejidad:** Baja (4 nodos)

- **[2770-automated-notes-generator.json](workflows/2770-automated-notes-generator.json)**
  - **Descripción:** Este flujo automático monitorea un directorio para detectar nuevos archivos, procesa su contenido y utiliza agentes de IA para generar documentos estructurados en formato Markdown como guías de estudio, timeline y documentación informativa.
  - **Complejidad:** Baja (4 nodos)

- **[2862-mcp-qdrant-reviews.json](workflows/2862-mcp-qdrant-reviews.json)**
  - **Descripción:** Este flujo configura y administra una base de datos vectorial con Qdrant para realizar operaciones como insertar, buscar, comparar y recomendar revisiones de empresas. Utiliza MCP Server Trigger para manejar diferentes herramientas personalizadas y extiende la funcionalidad del servidor Qdrant con capacidades avanzadas.
  - **Complejidad:** Baja (4 nodos)

- **[2876-workflow_mcp_manager.json](workflows/2876-workflow_mcp_manager.json)**
  - **Descripción:** Este flujo gestiona dinámicamente una lista de workflows disponibles mediante Redis y n8n, permitiendo operaciones como agregar, eliminar y listar workflows. Utiliza un agente de lenguaje para ejecutar tareas basadas en estos workflows.
  - **Complejidad:** Baja (4 nodos)

- **[2879-stock-analysis-bot.json](workflows/2879-stock-analysis-bot.json)**
  - **Descripción:** Este flujo automático realiza un análisis detallado de acciones combinando análisis técnico y sentimiento de noticias. Utiliza varias APIs para obtener datos técnicos (gráficos, indicadores) y analítica de sentimiento, luego los procesa con GPT-4 para generar un informe estructurado en formato HTML en hebreo, que se envía por correo electrónico.
  - **Complejidad:** Baja (4 nodos)

- **[2899-prevent-concurrent-workflows.json](workflows/2899-prevent-concurrent-workflows.json)**
  - **Descripción:** Este flujo utiliza Redis para prevenir la ejecución concurrente de workflows. Almacena estados en Redis y verifica si un proceso ya está en curso antes de continuar.
  - **Complejidad:** Baja (4 nodos)

- **[2937-tiktok-youtube-generator.json](workflows/2937-tiktok-youtube-generator.json)**
  - **Descripción:** Este flujo automático genera contenido multimedia para TikTok y YouTube Shorts/Reels de manera automatizada utilizando APIs como PiAPI para imágenes y videos, ElevenLabs para voces, Google Drive para almacenamiento y OpenAI para texto. Incluye capturas de ideas, generación de imágenes, conversión a video, adición de audio, mezcla de elementos y notificación al final.
  - **Complejidad:** Baja (4 nodos)

- **[2956-nextcloud-docker-flow.json](workflows/2956-nextcloud-docker-flow.json)**
  - **Descripción:** Este flujo configura y gestiona entornos Docker para NextCloud utilizando n8n, incluyendo acciones como iniciar, detener, suspender, desususpender, montar/desmontar discos, actualizar paquetes y más. También administra conexiones DNS y verifica la validez del dominio.
  - **Complejidad:** Baja (4 nodos)

- **[3058-set_medoids_cultivos.json](workflows/3058-set_medoids_cultivos.json)**
  - **Descripción:** Este flujo configura los medoides (centros) de dos tipos para la detección de anomalías en un conjunto de datos de cultivos usando Qdrant y el modelo Voyage. Calcula representantes de clusters mediante matrices de distancia y vectores embedding de texto.
  - **Complejidad:** Baja (4 nodos)

- **[3126-multi-ai-chatbot-postgres-chart.json](workflows/3126-multi-ai-chatbot-postgres-chart.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con una base de datos PostgreSQL o Supabase mediante consultas SQL y generar gráficos visualizados en QuickChart usando agentes de inteligencia artificial. El sistema utiliza OpenAI para procesar las preguntas del usuario, ejecutar consultas SQL, obtener definiciones de tablas y crear gráficos basados en los resultados obtenidos.
  - **Complejidad:** Baja (4 nodos)

- **[3160-chatgpt-email-responses.json](workflows/3160-chatgpt-email-responses.json)**
  - **Descripción:** Este flujo automático envía una respuesta de ChatGPT a través de correo electrónico cuando se recibe un correo electrónico y registra las respuestas en Google Sheets. También registra retroalimentación para mejorar el modelo.
  - **Complejidad:** Baja (4 nodos)

- **[0024-iss-position-updates.json](workflows/0024-iss-position-updates.json)**
  - **Descripción:** Este flujo automático obtiene cada minuto la posición actual de la Estación Espacial Internacional (ISS) desde una API externa y envía los datos a un topic en ActiveMQ.
  - **Complejidad:** Baja (4 nodos)

- **[0030-iss-monitoring-sqs.json](workflows/0030-iss-monitoring-sqs.json)**
  - **Descripción:** Este flujo automático verifica cada minuto la posición del satélite ISS mediante una API y almacena los datos en variables para su uso posterior.
  - **Complejidad:** Baja (4 nodos)

- **[0032-iss-satellite-monitoring.json](workflows/0032-iss-satellite-monitoring.json)**
  - **Descripción:** Este flujo automatizado consulta periódicamente la posición del satélite ISS mediante una API y carga los datos en Google BigQuery.
  - **Complejidad:** Baja (4 nodos)

- **[0042-iss-mqtt-flow.json](workflows/0042-iss-mqtt-flow.json)**
  - **Descripción:** Este flujo automático ejecuta una llamada HTTP cada minuto para obtener la posición actual de la Estación Espacial Internacional desde api.wheretheiss.at, procesa los datos y los envía a través de MQTT al tópico 'iss-position'.
  - **Complejidad:** Baja (4 nodos)

- **[0050-calendly-humantic-personality-analysis.json](workflows/0050-calendly-humantic-personality-analysis.json)**
  - **Descripción:** Este flujo automatizado responde a eventos de Calendly (como la creación de un invitado) para ejecutar análisis de personalidad con Humantic AI y almacenar posteriormente los resultados en una página de base de datos de Notion.
  - **Complejidad:** Baja (4 nodos)
  - [Ver lista completa](https://github.com/DragonJAR/n8n-workflows-es/blob/main/README.md)

- **[0058-microsoft-todo-blueprint.json](workflows/0058-microsoft-todo-blueprint.json)**
  - **Descripción:** Este flujo permite crear y actualizar tareas en Microsoft To Do mediante un trigger manual. Comienza con la activación del trigger que inicializa el proceso. Luego crea una nueva tarea (create) especificando detalles como lista de tareas, importancia alta y contenido. Posteriormente, actualiza esa misma tarea usando los datos retornados por la creación para identificarla.
  - **Complejidad:** Baja (4 nodos)

- **[0070-114_validar_telefono.json](workflows/0070-114_validar_telefono.json)**
  - **Descripción:** Este flujo automático verifica si el número telefónico +34605281220 es válido utilizando un proceso de validación mediante uProc. Comienza con un trigger manual que inicia el flujo, luego configura una variable 'phone' en los datos del flujo y la envía a una validación por parte de un servicio de verificación.
  - **Complejidad:** Baja (4 nodos)

- **[0077-conversor-json-a-xml.json](workflows/0077-conversor-json-a-xml.json)**
  - **Descripción:** Este flujo convierte datos JSON en XML utilizando el nodo 'Set' para definir valores específicos y los responde mediante un webhook.
  - **Complejidad:** Baja (4 nodos)

- **[0079-sheets-to-dropbox.json](workflows/0079-sheets-to-dropbox.json)**
  - **Descripción:** Este flujo automático lee una hoja de cálculo cada 15 minutos y la convierte en archivo XLS para subirlo a Dropbox.
  - **Complejidad:** Baja (4 nodos)

- **[0120-customer-data-post.json](workflows/0120-customer-data-post.json)**
  - **Descripción:** Este flujo automatizado inicia manualmente con un clic, establece una clave API y luego obtiene todos los datos de personas del dataStore para enviarlos mediante POST a webhook.site.
  - **Complejidad:** Baja (4 nodos)

- **[0128-iss-position-firebase.json](workflows/0128-iss-position-firebase.json)**
  - **Descripción:** Este flujo automatizado recoge cada minuto la posición actual del ISS desde una API y almacena los datos en tiempo real en una base de datos Firebase.
  - **Complejidad:** Baja (4 nodos)

- **[0139-gdrive-aws-s3-sync.json](workflows/0139-gdrive-aws-s3-sync.json)**
  - **Descripción:** Este flujo monitoriza cambios en un archivo de Google Drive específico y sincroniza archivos con el bucket 'mybucket' en AWS S3 mediante operaciones de obtención y subida, utilizando un nodo 'merge' para combinar datos.
  - **Complejidad:** Baja (4 nodos)

- **[0143-rekognition-google-images.json](workflows/0143-rekognition-google-images.json)**
  - **Descripción:** Este flujo automatizado busca imágenes de calles desde Google y utiliza AWS Rekognition para analizarlas y extraer etiquetas. Luego combina estos resultados junto con los datos originales y guarda todo en una hoja de cálculo de Google.
  - **Complejidad:** Baja (4 nodos)

- **[0150-workflow-spreadsheet-export.json](workflows/0150-workflow-spreadsheet-export.json)**
  - **Descripción:** Este flujo n8n procesa una entrada de webhook que contiene listas de elementos, convierte estos en un archivo de Excel (.xlsx) y responde al webhook con la hoja de cálculo como archivo adjunto.
  - **Complejidad:** Baja (4 nodos)

- **[0183-questdb-tabla-datos.json](workflows/0183-questdb-tabla-datos.json)**
  - **Descripción:** Este flujo automático crea una tabla 'test' con columnas id y name en QuestDB al ejecutarse manualmente.
  - **Complejidad:** Baja (4 nodos)

- **[0215-html-sheet.json](workflows/0215-html-sheet.json)**
  - **Descripción:** Este flujo automatizado lee datos de una hoja de Google Sheets y los convierte en un HTML con formato tabla para responder a través de webhook.
  - **Complejidad:** Baja (4 nodos)

- **[0303-google-sheets-sync.json](workflows/0303-google-sheets-sync.json)**
  - **Descripción:** Este flujo automático lee datos de una hoja de cálculo Google y los sincroniza periódicamente en el listado de suscriptores de Mailchimp.
  - **Complejidad:** Baja (4 nodos)

- **[0317-phantom-airtable-store.json](workflows/0317-phantom-airtable-store.json)**
  - **Descripción:** Este flujo permite ejecutar una operación Phantom Buster y almacenar el resultado estructurado en Airtable mediante la opción 'append'.
  - **Complejidad:** Baja (4 nodos)

- **[0321-airtable-image-automation.json](workflows/0321-airtable-image-automation.json)**
  - **Descripción:** Este flujo automático busca y actualiza registros en Airtable para agregar imágenes mediante URL.
  - **Complejidad:** Baja (4 nodos)

- **[0322-notion-bookmark-tracker.json](workflows/0322-notion-bookmark-tracker.json)**
  - **Descripción:** Este flujo automatizado recibe URLs a través de un webhook POST y las crea como nuevas páginas en una base de datos Notion especificada.
  - **Complejidad:** Baja (4 nodos)

- **[0328-analytics-airtable.json](workflows/0328-analytics-airtable.json)**
  - **Descripción:** Este flujo automatizado obtiene datos de análisis web históricos y los almacena en una tabla de Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[0336-google-contacts-test.json](workflows/0336-google-contacts-test.json)**
  - **Descripción:** Este flujo automatizado permite crear un contacto en Google Contacts con los datos de n8n y luego actualizar e inmediatamente obtener ese mismo contacto.
  - **Complejidad:** Baja (4 nodos)

- **[0362-country-query-formatter.json](workflows/0362-country-query-formatter.json)**
  - **Descripción:** Este flujo automático consulta datos de país mediante GraphQL usando un código como parámetro, luego extrae el objeto del país y lo convierte en texto formateado para ser enviado a través de una URL.
  - **Complejidad:** Baja (4 nodos)

- **[0499-tts-generation.json](workflows/0499-tts-generation.json)**
  - **Descripción:** Este flujo automático permite ejecutar un script de Python para generar archivos de audio MP3 basados en texto y voz predefinidos.
  - **Complejidad:** Baja (4 nodos)

- **[0517-postgres-csv-export.json](workflows/0517-postgres-csv-export.json)**
  - **Descripción:** Este flujo automático consulta datos de una tabla específica (booksRead) en PostgreSQL mediante un trigger manual y exporta el resultado a un archivo CSV.
  - **Complejidad:** Baja (4 nodos)

- **[0596-cfp-trello-cards.json](workflows/0596-cfp-trello-cards.json)**
  - **Descripción:** Este flujo selecciona solicitantes de un evento CFP con puntuación mayor que 15 en Airtable y crea tarjetas en Trello a partir de la información del formulario usando Bannerbear para generar imágenes publicitarias.
  - **Complejidad:** Baja (4 nodos)

- **[0621-crear-tabla-y-insertar.json](workflows/0621-crear-tabla-y-insertar.json)**
  - **Descripción:** Este flujo manual crea una tabla en CrateDB si no existe y luego inserta un registro con valores predefinidos.
  - **Complejidad:** Baja (4 nodos)

- **[0622-crear-tabla-json.json](workflows/0622-crear-tabla-json.json)**
  - **Descripción:** Este flujo ejecuta una consulta SQL para crear una tabla denominada 'test' con columnas id e name, luego configura un conjunto de valores que incluye esos datos.
  - **Complejidad:** Baja (4 nodos)

- **[0623-postgres-create-set-insert.json](workflows/0623-postgres-create-set-insert.json)**
  - **Descripción:** Este flujo automatizado inicia con un clic manual que ejecuta una consulta SQL para crear una tabla llamada 'test' en PostgreSQL. Luego, toma la salida de esa creación y la utiliza como entrada para establecer valores en el nodo Set (específicamente, espera establecer un valor numérico para 'id' y una cadena fija para 'name'). Finalmente, estos valores se envían a otra operación PostgreSQL.
  - **Complejidad:** Baja (4 nodos)

- **[0634-dos_pasos_google_sheets.json](workflows/0634-dos_pasos_google_sheets.json)**
  - **Descripción:** Este flujo automático permite al usuario iniciar la ejecución manual y luego anexar datos en Google Sheets.
  - **Complejidad:** Baja (4 nodos)

- **[0649-amazon-s3-upload-list-json.json](workflows/0649-amazon-s3-upload-list-json.json)**
  - **Descripción:** Descarga un archivo desde una URL, lo sube a Amazon S3 y muestra todos los archivos en el bucket.
  - **Complejidad:** Baja (4 nodos)

- **[0650-cocktail-storage.json](workflows/0650-cocktail-storage.json)**
  - **Descripción:** Este flujo automático permite almacenar de forma persistente los datos en bruto de un trago aleatorio obtenido de la API de CocktailDB mediante el guardado como archivo JSON.
  - **Complejidad:** Baja (4 nodos)

- **[0651-ejemplo-merge.json](workflows/0651-ejemplo-merge.json)**
  - **Descripción:** Este flujo analiza datos de ejemplo para fusionar información sobre nombre y saludo en función del idioma común.
  - **Complejidad:** Baja (4 nodos)

- **[0654-descargar-y-subir-imagen.json](workflows/0654-descargar-y-subir-imagen.json)**
  - **Descripción:** Este flujo automático permite descargar una imagen de n8n.io y subirla directamente a un servidor FTP mediante el botón 'execute'.
  - **Complejidad:** Baja (4 nodos)

- **[0666-sheets-sync-every-2min.json](workflows/0666-sheets-sync-every-2min.json)**
  - **Descripción:** Este flujo automatizado ejecuta una actualización en dos hojas de Google cada dos minutos, utilizando datos leídos previamente.
  - **Complejidad:** Baja (4 nodos)

- **[0673-expense-tracker-mindee-airtable.json](workflows/0673-expense-tracker-mindee-airtable.json)**
  - **Descripción:** Este flujo permite recibir un webhook con datos de factura que Mindee procesa y almacena en una tabla de Airtable.
  - **Complejidad:** Baja (4 nodos)

- **[0705-google-sheets-mattermost-notification.json](workflows/0705-google-sheets-mattermost-notification.json)**
  - **Descripción:** Este flujo automático verifica cada 45 minutos datos nuevos de una hoja Google Sheets y envía al chatbot un mensaje formateado indicando la adición.
  - **Complejidad:** Baja (4 nodos)

- **[0727-iss-tracking-timescaledb.json](workflows/0727-iss-tracking-timescaledb.json)**
  - **Descripción:** Este flujo de trabajo automatizado consulta periódicamente la posición actual del satélite ISS y la almacena en una tabla de TimescaleDB para análisis temporal.
  - **Complejidad:** Baja (4 nodos)

- **[0732-reddit-automated-posting.json](workflows/0732-reddit-automated-posting.json)**
  - **Descripción:** Este flujo automático publica un mensaje inicial en Reddit, luego obtiene datos de ese post y finalmente añade un comentario con información procesada.
  - **Complejidad:** Baja (4 nodos)

- **[0738-n8n-flujo-set-stackby.json](workflows/0738-n8n-flujo-set-stackby.json)**
  - **Descripción:** Este flujo utiliza un trigger manual para establecer valores estáticos en un nodo 'set', luego pasa estos datos a otro nodo Stackby que los muestra en una tabla. El segundo Stackby utiliza la configuración de ID y nombre del primer nodo, manteniendo coherencia con esos campos.
  - **Complejidad:** Baja (4 nodos)

- **[0740-tapfiliate-crear-cuenta.json](workflows/0740-tapfiliate-crear-cuenta.json)**
  - **Descripción:** Este flujo automático crea una cuenta de afiliado en Tapfiliate con datos predefinidos y añade un tag personalizado.
  - **Complejidad:** Baja (4 nodos)

- **[0757-weather-query-response.json](workflows/0757-weather-query-response.json)**
  - **Descripción:** Este flujo automatizado consulta un servicio web para obtener datos meteorológicos de una ciudad especificada, los formatea y los devuelve como respuesta.
  - **Complejidad:** Baja (4 nodos)

- **[0761-iss-kafka-positions.json](workflows/0761-iss-kafka-positions.json)**
  - **Descripción:** Este flujo automático consulta cada minuto la posición actual del satélite ISS a través de la API WhereTheIss y envía los datos en tiempo real al topic Kafka 'iss-position'.
  - **Complejidad:** Baja (4 nodos)

- **[0765-wise-transfer-handler.json](workflows/0765-wise-transfer-handler.json)**
  - **Descripción:** Este flujo automático permite registrar en Airtable detalles de transferencias cuando cambia su estado utilizando la API de Wise.
  - **Complejidad:** Baja (4 nodos)

- **[1048-notion-clockify-client-sync.json](workflows/1048-notion-clockify-client-sync.json)**
  - **Descripción:** Este flujo automático detecta nuevos clientes en una base de datos de Notion y añade cada uno automáticamente al sistema de gestión de tiempo de Clockify.
  - **Complejidad:** Baja (4 nodos)

- **[1079-automatizar-carga-csv-postgres.json](workflows/1079-automatizar-carga-csv-postgres.json)**
  - **Descripción:** Este flujo automático lee un archivo CSV desde /tmp, lo convierte a formato de spreadsheet y carga los datos directamente en la tabla t1 de PostgreSQL.
  - **Complejidad:** Baja (4 nodos)

- **[1128-csv-insert-json.json](workflows/1128-csv-insert-json.json)**
  - **Descripción:** Este flujo automático lee un archivo CSV desde una ubicación específica y lo convierte a formato de hoja de cálculo para luego insertarlo en la tabla MySQL concerts_2023_csv.
  - **Complejidad:** Baja (4 nodos)

- **[2553-parquet-conversion-flujos.json](workflows/2553-parquet-conversion-flujos.json)**
  - **Descripción:** Este flujo permite convertir archivos Parquet, Avro, ORC y Feather a JSON utilizando la API de ParquetReader. Se inicia con un envío vía webhook que recibe el archivo en formato binario, lo procesa y devuelve los datos estructurados.
  - **Complejidad:** Baja (4 nodos)

- **[2643-api-moa-googleSheets.json](workflows/2643-api-moa-googleSheets.json)**
  - **Descripción:** Este flujo automático recopila datos de cotización ovina desde la API del Ministerio de Agricultura a través de una solicitud HTTP, los divide y luego los añade como nuevas filas en un archivo Google Sheets específico.
  - **Complejidad:** Baja (4 nodos)

- **[3123-sync-todoist-notion.json](workflows/3123-sync-todoist-notion.json)**
  - **Descripción:** Este flujo sincroniza tareas etiquetadas en Todoist con Notion y marca las tareas como enviadas una vez completada la sincronización.
  - **Complejidad:** Baja (4 nodos)

- **[0256-github-light-alert.json](workflows/0256-github-light-alert.json)**
  - **Descripción:** Este flujo activa un interruptor en Home Assistant a color rojo cuando hay actualizaciones en el repositorio de GitHub.
  - **Complejidad:** Baja (4 nodos)

- **[0627-figma-jira-sync.json](workflows/0627-figma-jira-sync.json)**
  - **Descripción:** Este flujo detecta actualizaciones en versiones de Figma a través del webhook del plugin Commit y agrega un comentario al issue específico JAJ-368 en Jira con los detalles pertinentes.
  - **Complejidad:** Baja (4 nodos)

- **[0660-taiga-issue-management.json](workflows/0660-taiga-issue-management.json)**
  - **Descripción:** Este flujo automático permite crear, actualizar y obtener una incidencia en Taiga a partir de un desencadenador manual.
  - **Complejidad:** Baja (4 nodos)

- **[0716-blotato-social-publishing.json](workflows/0716-blotato-social-publishing.json)**
  - **Descripción:** Este flujo automático publica videos e imágenes en múltiples redes sociales como Instagram, Facebook, LinkedIn, TikTok y más utilizando la plataforma Blotato. La automatización extrae contenido de Airtable, genera títulos virales para YouTube con OpenAI y gestiona el estado de publicación.
  - **Complejidad:** Baja (3 nodos)

- **[0791-ai-wordpress-summary.json](workflows/0791-ai-wordpress-summary.json)**
  - **Descripción:** Este flujo automático genera y añade un resumen AI al principio de artículos de WordPress usando OpenAI, verifica si ya existe uno para evitar duplicados, actualiza la página y guarda los datos en Google Sheets.
  - **Complejidad:** Baja (3 nodos)

- **[0798-ai-chat-with-supabase-documents.json](workflows/0798-ai-chat-with-supabase-documents.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de IA procesar documentos PDF y texto almacenados en Supabase, generar embeddings vectoriales con OpenAI y crear una base de conocimiento interactiva para consultas sobre archivos.
  - **Complejidad:** Baja (3 nodos)

- **[0800-search-console-ai-agent.json](workflows/0800-search-console-ai-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con datos del motor de búsqueda utilizando herramientas de la API de Google Search Console, OpenAI y almacenar el historial de conversaciones en una base de datos PostgreSQL.
  - **Complejidad:** Baja (3 nodos)

- **[0819-erpnext-candidate-automation.json](workflows/0819-erpnext-candidate-automation.json)**
  - **Descripción:** Este flujo automático permite integrar webhooks de ERPNext para gestionar solicitudes de candidatos mediante análisis AI (como Google Gemini) y actualizar sus estados en función del resultado.
  - **Complejidad:** Baja (3 nodos)

- **[0832-wordpress-ai-content-generator.json](workflows/0832-wordpress-ai-content-generator.json)**
  - **Descripción:** Este flujo automático crea artículos en WordPress a diferentes niveles de lectura utilizando modelos de lenguaje. Procesa el contenido reescrito, valida que tengan título e introducción, genera imágenes relacionadas y guarda borradores en Google Drive.
  - **Complejidad:** Baja (3 nodos)

- **[0874-tax-code-assistant-qdrant-mistral-openai.json](workflows/0874-tax-code-assistant-qdrant-mistral-openai.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de IA responder preguntas sobre el código fiscal del estado de Texas utilizando embeddings de Mistral.ai para generar vectores y Qdrant para almacenar y recuperar documentos con eficiencia, optimizando la gestión de grandes archivos mediante descompresión estratégica.
  - **Complejidad:** Baja (3 nodos)

- **[0886-workflow-doc-analyzer.json](workflows/0886-workflow-doc-analyzer.json)**
  - **Descripción:** Este flujo automático analiza documentos subidos mediante formulario, convierte el markdown en HTML y guarda los resultados en una base de datos vectorial para alimentar un chatbot.
  - **Complejidad:** Baja (3 nodos)

- **[0965-factoid_subscription_service.json](workflows/0965-factoid_subscription_service.json)**
  - **Descripción:** Este flujo automático utiliza n8n formularios para gestionar suscripciones a correos educativos diarios, semanales o sorprendentes con modelos de IA generativa y almacenamiento en Airtable.
  - **Complejidad:** Baja (3 nodos)

- **[0968-HR_CV_Evaluation_AI.json](workflows/0968-HR_CV_Evaluation_AI.json)**
  - **Descripción:** Este flujo automático permite evaluar automáticamente solicitudes de candidatos mediante análisis AI para determinar su calificación y aptitud para la vacante, actualizando luego en Airtable según el resultado.
  - **Complejidad:** Baja (3 nodos)

- **[0973-ai-faq-generator.json](workflows/0973-ai-faq-generator.json)**
  - **Descripción:** Este flujo utiliza n8n y modelos de lenguaje como ChatGPT para generar automáticamente contenido completo en FAQ basado en datos proporcionados.
  - **Complejidad:** Baja (3 nodos)

- **[0995-agent-access-control.json](workflows/0995-agent-access-control.json)**
  - **Descripción:** Este flujo verifica las credenciales del usuario en Airtable para establecer permisos y control de acceso a diferentes agentes y herramientas.
  - **Complejidad:** Baja (3 nodos)

- **[1091-spotify-maintenance.json](workflows/1091-spotify-maintenance.json)**
  - **Descripción:** Este flujo automático verifica si las canciones de las últimas reproducciones en Spotify ya están guardadas en la base de datos NocoDB. Si no lo están, crea nuevos registros para cada una con el URI de la canción y la fecha en que fue añadida (usando currentDate). También busca en la base de datos existente si hay una playlist mensual con el nombre correspondiente a la fecha actual. Si existe, obtiene sus pistas; si no existe en Spotify pero sí está en NocoDb, la crea y sincroniza.
  - **Complejidad:** Baja (3 nodos)

- **[1104-airtable-batch-processing-with-rates.json](workflows/1104-airtable-batch-processing-with-rates.json)**
  - **Descripción:** Este flujo procesa registros en lote en Airtable con tres modos: insert, update y upsert. Para evitar límites de tasa en la API de Airtable, incluye pausas después de cada error 429.
  - **Complejidad:** Baja (3 nodos)

- **[1154-content-generation-automated.json](workflows/1154-content-generation-automated.json)**
  - **Descripción:** Este flujo automático permite generar contenido estructurado a partir de entradas formulario utilizando modelos OpenAI y almacenar los resultados en Google Drive.
  - **Complejidad:** Baja (3 nodos)

- **[1164-zendesk-gcal-airtable-customer-flow.json](workflows/1164-zendesk-gcal-airtable-customer-flow.json)**
  - **Descripción:** Este flujo automático permite a un chatbot integrar múltiples sistemas como Zendesk para crear tickets y gestionar datos de clientes, Gcal (Google Calendar) para programar citas, Airtable para compartir transcripciones con el equipo de producto, y n8n para ejecutar todas las operaciones.
  - **Complejidad:** Baja (3 nodos)

- **[1265-airtable-baserow-form-connector.json](workflows/1265-airtable-baserow-form-connector.json)**
  - **Descripción:** Conecta formularios de Airtable con bases en Baserow.
  - **Complejidad:** Baja (3 nodos)

- **[1275-flujo-seleccion-candidatos-ai.json](workflows/1275-flujo-seleccion-candidatos-ai.json)**
  - **Descripción:** Flujo de selección de candidatos asistido por IA.
  - **Complejidad:** Baja (3 nodos)

- **[1425-ai-agent-to-chat-with-files-in-supabase-storage.json](workflows/1425-ai-agent-to-chat-with-files-in-supabase-storage.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, extracción de datos, generación de contenido utilizando OpenAI/GPT, Webhook, Airtable con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (3 nodos)

- **[1426-ai-agent-to-chat-with-openai.json](workflows/1426-ai-agent-to-chat-with-openai.json)**
  - **Descripción:** Este flujo permite chatbot, automatización, resumen, generación de contenido utilizando OpenAI/GPT, Webhook, Supabase con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (3 nodos)

- **[1492-respond-to-whatsapp-messages-with-ai-like-a-pro.json](workflows/1492-respond-to-whatsapp-messages-with-ai-like-a-pro.json)**
  - **Descripción:** Este flujo permite chatbot, transcripción, resumen, extracción de datos, generación de contenido utilizando OpenAI/GPT, Webhook, WhatsApp con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (3 nodos)

- **[2536-billbee-address-validation.json](workflows/2536-billbee-address-validation.json)**
  - **Descripción:** Este flujo automático valida y corrige direcciones de envío de pedidos utilizando la API Endereco para verificar datos en Alemania.
  - **Complejidad:** Baja (3 nodos)

- **[2556-glassdoor-discrimination-analysis.json](workflows/2556-glassdoor-discrimination-analysis.json)**
  - **Descripción:** Este flujo automático utiliza ScrapingBee para extraer reseñas y datos demográficos de Glassdoor, junto con modelos de OpenAI para analizar patrones discriminatorios mediante cálculos estadísticos como puntuaciones z y tamaños de efecto.
  - **Complejidad:** Baja (3 nodos)

- **[2600-news-pipeline.json](workflows/2600-news-pipeline.json)**
  - **Descripción:** Este flujo automatizado extrae artículos de prensa, los filtra por antigüedad (7 días), genera resúmenes y palabras clave usando ChatGPT, y almacena todo en una base de datos SQL.
  - **Complejidad:** Baja (3 nodos)

- **[2686-nextcloud_folder_migration.json](workflows/2686-nextcloud_folder_migration.json)**
  - **Descripción:** Este flujo automático搬迁文件夹及其子文件和子文件夹到Nextcloud的指定位置，确保结构完整并避免超过速率限制。
  - **Complejidad:** Baja (3 nodos)

- **[2736-wordpress-article-generator.json](workflows/2736-wordpress-article-generator.json)**
  - **Descripción:** Flujo que automatiza la creación de artículos en WordPress utilizando OpenAI para generar contenido estructurado y DALL·E para imágenes, con validación de datos.
  - **Complejidad:** Baja (3 nodos)

- **[2766-hellofresh-recomendador.json](workflows/2766-hellofresh-recomendador.json)**
  - **Descripción:** Este flujo automatiza la recomendación de recetas semanales de HelloFresh mediante un motor de búsqueda vectorial y una base de datos. Extrae información de menús semanales, procesa datos de recetas, genera embeddings con Mistral Cloud y utiliza Qdrant para推荐pciones basadas en preferencias.
  - **Complejidad:** Baja (3 nodos)

- **[2775-competitor-research-automator.json](workflows/2775-competitor-research-automator.json)**
  - **Descripción:** Este flujo automatiza la investigación competitiva usando Exa.ai para encontrar competidores y luego recopila información detallada sobre cada competidor mediante agentes de inteligencia artificial que extraen datos de sitios como Crunchbase, LinkedIn y bienvenidos. Los datos se estructuran y se insertan en Notion.
  - **Complejidad:** Baja (3 nodos)

- **[2778-trustpilot-insights.json](workflows/2778-trustpilot-insights.json)**
  - **Descripción:** Este flujo extrae, procesa y analiza reseñas de Trustpilot para una empresa específica. Utiliza Qdrant como base vectorial para almacenar datos estructurados, aplica clustering con K-means para identificar patrones, genera insights usando un modelo LLM y exporta los resultados a Google Sheets.
  - **Complejidad:** Baja (3 nodos)

- **[2779-hn_comments_analyzer.json](workflows/2779-hn_comments_analyzer.json)**
  - **Descripción:** Este flujo automático extrae y analiza comentarios de un artículo de Hacker News, los organiza en clusters utilizando algoritmos de agrupamiento (K-means) y genera insights con un modelo de lenguaje grande. Los datos se almacenan en Qdrant para su posterior análisis.
  - **Complejidad:** Baja (3 nodos)

- **[2799-faq-generator-n8n.json](workflows/2799-faq-generator-n8n.json)**
  - **Descripción:** Este flujo automatiza la creación de FAQ para integraciones de n8n usando OpenAI y Google Sheets. Extrae datos de una hoja de cálculo, genera pares de preguntas y respuestas, completa algunas respuestas con AI y guarda los resultados en Google Drive.
  - **Complejidad:** Baja (3 nodos)

- **[2820-auto-assign-jira.json](workflows/2820-auto-assign-jira.json)**
  - **Descripción:** Este flujo automatiza la asignación de tareas estancadas en JIRA mediante un sistema de coincidencias con issues resueltos pasados usando IA y bases de datos vectoriales. Busca tareas sin asignar durante más de 5 días, encuentra las más similares en la base de conocimientos y asigna a los miembros del equipo con menos cargas actuales.
  - **Complejidad:** Baja (3 nodos)

- **[2829-digest-novedades-plantillas.json](workflows/2829-digest-novedades-plantillas.json)**
  - **Descripción:** Este flujo automático genera un resumen diario de las plantillas más recientes de n8n filtradas por categorías seleccionadas por los subscriptores almacenados en una hoja de cálculo de Excel. Utiliza OpenAI para resumir las descripciones y Outlook para enviar el correo electrónico.
  - **Complejidad:** Baja (3 nodos)

- **[2883-chatbot-interactivo.json](workflows/2883-chatbot-interactivo.json)**
  - **Descripción:** Este flujo gestiona la interacción de un chatbot, almacenando mensajes en Redis y usando OpenAI para extraer información. Espera una cantidad de tiempo variable basada en el conteo de palabras antes de procesar los mensajes.
  - **Complejidad:** Baja (3 nodos)

- **[2908-llm_chaining.json](workflows/2908-llm_chaining.json)**
  - **Descripción:** Este flujo utiliza cadenas de LLM para realizar tareas secuenciales y paralelas con diferentes modelos de inteligencia artificial, incluyendo la obtención de datos de una página web, el análisis con prompts específicos y la combinación de resultados.
  - **Complejidad:** Baja (3 nodos)

- **[2941-blog-automation.json](workflows/2941-blog-automation.json)**
  - **Descripción:** Este flujo automatiza la creación y publicación de artículos en un blog usando Google Sheets como origen de datos. Configura parámetros, recupera información de hojas de cálculo, procesa prompts personalizados con OpenAI, genera contenido, valida fechas y statuses, y actualiza el estado en tiempo real.
  - **Complejidad:** Baja (3 nodos)

- **[2953-influxdb-docker-deploy.json](workflows/2953-influxdb-docker-deploy.json)**
  - **Descripción:** Este flujo automático implementa y gestiona un contenedor de InfluxDB en Docker para una aplicación relacionada con WHMCS/WISECP, admitiendo operaciones como despliegue, arranque, parada, suspensión, montaje y control de disco.
  - **Complejidad:** Baja (3 nodos)

- **[3000-automatizacion_rrhh.json](workflows/3000-automatizacion_rrhh.json)**
  - **Descripción:** Este flujo automatiza la publicación de ofertas laborales y evalúa candidatos utilizando inteligencia artificial. Incluye formularios para postulaciones, análisis de CV con ChatGPT, generación de cuestionarios personalizados y seguimiento en Airtable.
  - **Complejidad:** Baja (3 nodos)

- **[3030-n8n-rag-living-data.json](workflows/3030-n8n-rag-living-data.json)**
  - **Descripción:** Este flujo automatiza la integración de datos en tiempo real desde Notion hacia un sistema de recuperación de información basado en vectores (RAG) usando OpenAI y Supabase. Procesa documentos, los divide en fragmentos, genera embeddings con OpenAI y almacena los resultados en Supabase para permitir búsquedas semánticas.
  - **Complejidad:** Baja (3 nodos)

- **[3117-ai-search-console-chat.json](workflows/3117-ai-search-console-chat.json)**
  - **Descripción:** Este flujo utiliza OpenAI y Postgres para permitir a un agente de chat interactuar con datos de Google Search Console, recuperando información mediante una conversación natural.
  - **Complejidad:** Baja (3 nodos)

- **[3158-scrape-news-with-ai-to-nocodb.json](workflows/3158-scrape-news-with-ai-to-nocodb.json)**
  - **Descripción:** Este flujo extrae HTML de una página web específicamente con CSS, luego suma los enlaces y fechas de las publicaciones, filtra por fecha reciente, obtiene el contenido individual de cada post, genera resúmenes y palabras clave usando OpenAI, y almacena los datos en NocoDB.
  - **Complejidad:** Baja (3 nodos)

- **[3166-buscar_palabras_clave.json](workflows/3166-buscar_palabras_clave.json)**
  - **Descripción:** Este flujo automatiza la búsqueda de palabras clave principales usando NocoDB y DataforSEO para analizar volumen de búsquedas en Google y YouTube. Genera y actualiza datos en_batches en una base de datos.
  - **Complejidad:** Baja (3 nodos)

- **[3205-backup-n8n.json](workflows/3205-backup-n8n.json)**
  - **Descripción:** Este flujo automático realiza una copia de seguridad diaria de los workflows de n8n en Google Drive. Crea y verifica las carpetas 'n8n_backups' y 'n8n_old', mueve las copias antiguas a la carpeta 'n8n_old' y elimina aquellas que excedan 30 días.
  - **Complejidad:** Baja (3 nodos)

- **[3278-google-sheets-analysis.json](workflows/3278-google-sheets-analysis.json)**
  - **Descripción:** Este flujo utiliza un agente de inteligencia artificial para analizar y manipular datos desde Google Sheets, permitiendo realizar consultas avanzadas filtrando por fechas y estados, transformar formatos complicados en JSON, y obtener estadísticas a través de herramientas como el cálculo y la agregación.
  - **Complejidad:** Baja (3 nodos)

- **[3312-chatbot-curriculos.json](workflows/3312-chatbot-curriculos.json)**
  - **Descripción:** Este flujo permite crear un chatbot personalizado que gestiona currículos y envía reportes diarios con información de conversaciones mediante Google Drive, Gemini, Pinecone y NocoDB.
  - **Complejidad:** Baja (3 nodos)

- **[0019-EscrituraJSONBinario.json](workflows/0019-EscrituraJSONBinario.json)**
  - **Descripción:** Este flujo automatizado crea datos JSON de ejemplo, los convierte a formato binario (Base64) y escribe este contenido en un archivo.
  - **Complejidad:** Baja (3 nodos)

- **[0023-coda-insert-data.json](workflows/0023-coda-insert-data.json)**
  - **Descripción:** Este flujo n8n inserta datos nuevos en una tabla específica de un documento Coda cuando se activa manualmente mediante un clic.
  - **Complejidad:** Baja (3 nodos)

- **[0044-gmail-drive-adjunto.json](workflows/0044-gmail-drive-adjunto.json)**
  - **Descripción:** Este flujo automático extrae mensajes de Gmail, guarda adjuntos en Google Drive y luego obtiene el enlace directo para facilitar su acceso.
  - **Complejidad:** Baja (3 nodos)

- **[0056-aws-transcribe-s3.json](workflows/0056-aws-transcribe-s3.json)**
  - **Descripción:** Este flujo ejecuta AWS Transcribe con todos los archivos encontrados en el bucket 'n8n-docs' de S3.
  - **Complejidad:** Baja (3 nodos)

- **[0097-netlify-to-airtable.json](workflows/0097-netlify-to-airtable.json)**
  - **Descripción:** Este flujo automático captura envíos formularios de Netlify y los agrega automáticamente a una tabla específica en Airtable.
  - **Complejidad:** Baja (3 nodos)

- **[0105-invoicing-textract-s3.json](workflows/0105-invoicing-textract-s3.json)**
  - **Descripción:** Al hacer clic en el botón, se sube un archivo 'Rechnung.jpg' a la carpeta S3 y luego Amazon Textract lo procesa.
  - **Complejidad:** Baja (3 nodos)

- **[0111-onfleet-tasks-from-spreadsheet.json](workflows/0111-onfleet-tasks-from-spreadsheet.json)**
  - **Descripción:** Este flujo carga un archivo Excel desde una ruta local y lo utiliza para crear tareas en Onfleet.
  - **Complejidad:** Baja (3 nodos)

- **[0117-calendly-dropcontact-notion-integracion.json](workflows/0117-calendly-dropcontact-notion-integracion.json)**
  - **Descripción:** Este flujo automatizado permite integrar eventos de Calendly con el sistema DropContact y almacenar los datos en una base de datos de Notion.
  - **Complejidad:** Baja (3 nodos)

- **[0126-sanitized-invoices-upload.json](workflows/0126-sanitized-invoices-upload.json)**
  - **Descripción:** Este flujo lee correos electrónicos de la bandeja 'Invoices' en un servidor IMAP y procesa cada archivo adjunto, sanitizando el nombre del archivo para eliminar caracteres especiales, antes de subirlo a Nextcloud.
  - **Complejidad:** Baja (3 nodos)

- **[0133-gitlab-release-outline.json](workflows/0133-gitlab-release-outline.json)**
  - **Descripción:** Este flujo detecta automáticamente la creación de un nuevo tag en el repositorio GitLab 'ci-test' y, si es una etiqueta de lanzamiento (release), crea un documento Outline basado en los datos proporcionados.
  - **Complejidad:** Baja (3 nodos)

- **[0163-mock-transactions-sum.json](workflows/0163-mock-transactions-sum.json)**
  - **Descripción:** Este flujo utiliza nodos de función para generar datos mockados con montos en USD y calcular la suma total.
  - **Complejidad:** Baja (3 nodos)

- **[0176-weather-api.json](workflows/0176-weather-api.json)**
  - **Descripción:** Este flujo automático permite obtener información meteorológica (temperatura y descripción) de cualquier ciudad que se especifique mediante una solicitud HTTP. Recolecta los datos desde la API de OpenWeatherMap y crea dos variables: 'temp' para la temperatura y 'description' para el estado del tiempo.
  - **Complejidad:** Baja (3 nodos)

- **[0182-logo-download-script.json](workflows/0182-logo-download-script.json)**
  - **Descripción:** Este flujo automatizado descarga una imagen de un URL y la escribe en el sistema de archivos local.
  - **Complejidad:** Baja (3 nodos)

- **[0190-smart-factory-data-generator.json](workflows/0190-smart-factory-data-generator.json)**
  - **Descripción:** Este flujo automatizado genera datos aleatorios de temperatura y tiempo de actividad de una máquina industrial, utilizando un nombre fijo 'n8n_cr8' como identificador, y los envía periódicamente a través de AMQP.
  - **Complejidad:** Baja (3 nodos)

- **[0211-etl-weekly-google-sheets-mysql.json](workflows/0211-etl-weekly-google-sheets-mysql.json)**
  - **Descripción:** Este flujo automático ejecuta una inserción en MySQL cada semana usando datos de Google Sheets.
  - **Complejidad:** Baja (3 nodos)

- **[0214-hoja-html-flujo.json](workflows/0214-hoja-html-flujo.json)**
  - **Descripción:** Este flujo automático lee datos de una hoja de cálculo específica y los convierte en un archivo HTML cuando se recibe una solicitud a través de Webhook.
  - **Complejidad:** Baja (3 nodos)

- **[0251-notion-clockify-invoices.json](workflows/0251-notion-clockify-invoices.json)**
  - **Descripción:** Este flujo automático crea automáticamente un registro en una base de datos de Notion cada vez que se genera una nueva factura en Clockify.
  - **Complejidad:** Baja (3 nodos)

- **[0265-customer-data-count-set.json](workflows/0265-customer-data-count-set.json)**
  - **Descripción:** Este flujo manual cuenta el número de registros de clientes en la base de datos de n8n Training.
  - **Complejidad:** Baja (3 nodos)

- **[0300-nextcloud-deck-email.json](workflows/0300-nextcloud-deck-email.json)**
  - **Descripción:** Este flujo automático lee correos electrónicos por IMAP, limpia su contenido y crea tarjetas en Nextcloud Deck.
  - **Complejidad:** Baja (3 nodos)

- **[0313-insertar-productos-desde-excel.json](workflows/0313-insertar-productos-desde-excel.json)**
  - **Descripción:** Este flujo lee un archivo Excel (.xls), lo interpreta y luego inserta cada fila de este archivo en la tabla 'product' de una base de datos PostgreSQL.
  - **Complejidad:** Baja (3 nodos)

- **[0400-gmail-attachment-upload.json](workflows/0400-gmail-attachment-upload.json)**
  - **Descripción:** Este flujo detecta nuevos correos electrónicos en Gmail con archivos adjuntos, extrae cada archivo individualmente y lo sube a la carpeta raíz de Google Drive.
  - **Complejidad:** Baja (3 nodos)

- **[0401-line-chatbot-memory-automation.json](workflows/0401-line-chatbot-memory-automation.json)**
  - **Descripción:** Este flujo automático extrae datos de nodos Webhook específicos en una ejecución y los pasa al nodo de procesamiento.
  - **Complejidad:** Baja (3 nodos)

- **[0449-rankmath-update-product.json](workflows/0449-rankmath-update-product.json)**
  - **Descripción:** Este flujo automatizado se ejecuta cuando el usuario hace clic en 'Probar flujo' y actualiza los metadatos SEO de un producto específico utilizando la API del plugin Rank Math.
  - **Complejidad:** Baja (3 nodos)

- **[0470-postgres-excel-generator.json](workflows/0470-postgres-excel-generator.json)**
  - **Descripción:** Este flujo ejecuta una consulta en PostgreSQL para obtener los nombres y códigos EAN de los productos, convierte el resultado en un archivo Excel y lo escribe.
  - **Complejidad:** Baja (3 nodos)

- **[0526-webhook-analisis-datos.json](workflows/0526-webhook-analisis-datos.json)**
  - **Descripción:** Este flujo analiza un webhook para extraer datos y generar una respuesta.
  - **Complejidad:** Baja (3 nodos)

- **[0527-3-xml-transform.json](workflows/0527-3-xml-transform.json)**
  - **Descripción:** Este flujo procesa y transforma datos en formato XML mediante la conversión de una cadena XML en un objeto estructurado.
  - **Complejidad:** Baja (3 nodos)

- **[0552-insertar-valor-mongodb.json](workflows/0552-insertar-valor-mongodb.json)**
  - **Descripción:** Este flujo manual inserta un valor específico en la base de datos MongoDB cuando se ejecuta.
  - **Complejidad:** Baja (3 nodos)

- **[0558-google-drive-download.json](workflows/0558-google-drive-download.json)**
  - **Descripción:** Este flujo automático permite descargar un archivo de Google Drive y guardarlo localmente con un nombre específico.
  - **Complejidad:** Baja (3 nodos)

- **[0597-cocktaildb-json-xml-conversion.json](workflows/0597-cocktaildb-json-xml-conversion.json)**
  - **Descripción:** Este flujo automático convierte los datos de respuesta en JSON de la API CocktailDB a XML.
  - **Complejidad:** Baja (3 nodos)

- **[0637-60_n8n_mysql_purge_older_records.json](workflows/0637-60_n8n_mysql_purge_older_records.json)**
  - **Descripción:** Este flujo elimina automáticamente registros de ejecución en la base de datos MySQL que sean antiguos (más de un mes) para optimizar el almacenamiento.
  - **Complejidad:** Baja (3 nodos)

- **[0671-weather-processing.json](workflows/0671-weather-processing.json)**
  - **Descripción:** Este flujo automático procesa datos meteorológicos utilizando la API de OpenWeatherMap para obtener información sobre temperatura, humedad, velocidad del viento y descripción.
  - **Complejidad:** Baja (3 nodos)

- **[0737-getresponse-trigger-airtable.json](workflows/0737-getresponse-trigger-airtable.json)**
  - **Descripción:** Este flujo automático es desencadenado por un suscriptor en GetResponse para la lista 'qtPk7'. Cuando se produce este evento, n8n recoge los datos del contacto y añade una entrada en Airtable a la tabla especificada.
  - **Complejidad:** Baja (3 nodos)

- **[0763-autopilot-to-airtable-contact.json](workflows/0763-autopilot-to-airtable-contact.json)**
  - **Descripción:** Este flujo automatizado importa automáticamente los contactos nuevos de Autopilot a una tabla específica en Airtable.
  - **Complejidad:** Baja (3 nodos)

- **[0927-digital-ocean-upload-form.json](workflows/0927-digital-ocean-upload-form.json)**
  - **Descripción:** Este flujo permite subir archivos a Digital Ocean Spaces mediante un formulario y mostrar el enlace después de la carga.
  - **Complejidad:** Baja (3 nodos)

- **[1115-filemaker-pagination.json](workflows/1115-filemaker-pagination.json)**
  - **Descripción:** Este flujo procesa una respuesta paginada del Data API de FileMaker para extraer datos específicos de los contactos.
  - **Complejidad:** Baja (3 nodos)

- **[1171-sheets-screenshot-storage.json](workflows/1171-sheets-screenshot-storage.json)**
  - **Descripción:** Este flujo automático captura una pantalla de un sitio web cada vez que se añade una nueva fila en Google Sheets y guarda la imagen en Google Drive.
  - **Complejidad:** Baja (3 nodos)

- **[1175-postgres-data-ingestion.json](workflows/1175-postgres-data-ingestion.json)**
  - **Descripción:** Este flujo automático ejecuta cada minuto una función que genera valores aleatorios y los inserta en una tabla de PostgreSQL.
  - **Complejidad:** Baja (3 nodos)

- **[2570-drive-video-upload.json](workflows/2570-drive-video-upload.json)**
  - **Descripción:** Este flujo automático permite subir videos a Google Drive mediante una Google Apps Script. Comienza con un trigger manual que inicia la ejecución, luego envía los datos de la URL del video (y un secreto) a la web app de Google Script para procesar la subida, y finalmente renombra el archivo recién cargado.
  - **Complejidad:** Baja (3 nodos)

- **[0758-asana-task-creator.json](workflows/0758-asana-task-creator.json)**
  - **Descripción:** Este flujo automático consulta la API de Asana mediante OAuth2 y procesa el resultado para generar un mensaje que muestra el enlace permanente de una tarea creada.
  - **Complejidad:** Baja (3 nodos)

- **[0783-sql-email-query-generator.json](workflows/0783-sql-email-query-generator.json)**
  - **Descripción:** Este flujo traduce preguntas sobre correos electrónicos en consultas SQL y las ejecuta contra la base de datos.
  - **Complejidad:** Baja (2 nodos)

- **[0790-amazon-ads-optimization-flow.json](workflows/0790-amazon-ads-optimization-flow.json)**
  - **Descripción:** Este flujo automatizado analiza reportes de Amazon Ads almacenados en Google Drive, utilizando IA para generar recomendaciones detalladas sobre estrategias de licitación, optimización táctica y escalado presupuestario.
  - **Complejidad:** Baja (2 nodos)

- **[0815-ai-company-researcher-sales.json](workflows/0815-ai-company-researcher-sales.json)**
  - **Descripción:** Este flujo automático utiliza IA junto con herramientas web como SERPAPI o ScrapingBee para investigar propiedades de empresas como dominio, URL de LinkedIn, tipo de mercado (B2B/B2C), planes más económicos, API y ensayos gratuitos, actualizando luego los datos en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[0856-youtube-x-automation.json](workflows/0856-youtube-x-automation.json)**
  - **Descripción:** Este flujo automático busca promover los videos más recientes de una canaleta YouTube específica en X, verificando que cumplan con las limitaciones de caracteres y manteniendo un registro en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[0868-n8n-deployer.json](workflows/0868-n8n-deployer.json)**
  - **Descripción:** Este flujo permite la importación y configuración de un workflow en n8n mediante archivos JSON alojados en una carpeta específica de Google Drive.
  - **Complejidad:** Baja (2 nodos)

- **[0930-linkedin-data-processing.json](workflows/0930-linkedin-data-processing.json)**
  - **Descripción:** Este flujo automatizado utiliza el MCP de Bright Data para extraer información en Markdown desde perfiles o empresas de LinkedIn, procesa esos datos con Google Gemini (modelo PaLM) que los convierte en JSON e incorpora contexto profundo para generar historias detalladas, y finalmente escribe la salida en archivos locales.
  - **Complejidad:** Baja (2 nodos)

- **[0975-airtable-image-analysis.json](workflows/0975-airtable-image-analysis.json)**
  - **Descripción:** Este flujo automatiza el análisis de imágenes capturadas en Airtable para identificar atributos de productos e integra información web, optimizando la gestión de inventario.
  - **Complejidad:** Baja (2 nodos)

- **[0985-youtube-ai-agent-comment-analysis.json](workflows/0985-youtube-ai-agent-comment-analysis.json)**
  - **Descripción:** Este flujo automatizado permite a un agente conversacional de IA interactuar y analizar datos de YouTube, incluyendo la transcripción de videos, recopilación de comentarios, obtención de detalles del canal, evaluación de thumbnails e implementación de gestión con memoria PostgreSQL.
  - **Complejidad:** Baja (2 nodos)

- **[0988-finance-email-parser.json](workflows/0988-finance-email-parser.json)**
  - **Descripción:** Este flujo automático extrae datos de transacciones financieras de correos electrónicos utilizando Gmail como fuente, Google Gemini AI para análisis e interpretación del contenido, y finalmente estructura la información en un formato específico que se envía a una hoja de cálculo de Google. El workflow utiliza etiquetas personalizadas para identificar diferentes tipos de transacciones (facturas, pagos múltiples, etc.) y aplica procesamiento inteligente basado en el remitente del correo.
  - **Complejidad:** Baja (2 nodos)

- **[1092-url-shortener-management.json](workflows/1092-url-shortener-management.json)**
  - **Descripción:** Este flujo automático gestiona URLs cortas mediante la generación de hashes SHA-256 que se almacenan en Airtable, permitiendo crear y verificar referencias únicas para controlar accesos o registros.
  - **Complejidad:** Baja (2 nodos)

- **[1108-notion-project-user-management.json](workflows/1108-notion-project-user-management.json)**
  - **Descripción:** Este flujo permite gestionar la creación de proyectos y usuarios en Notion mediante funciones que procesan datos e integra con webhooks.
  - **Complejidad:** Baja (2 nodos)

- **[1113-swift_codes_extractor.json](workflows/1113-swift_codes_extractor.json)**
  - **Descripción:** Este flujo automático extrae códigos SWIFT de múltiples páginas web en diferentes países, procesa la información normalizada y la guarda en una base de datos MongoDB.
  - **Complejidad:** Baja (2 nodos)

- **[1114-backup-n8n-workflows.json](workflows/1114-backup-n8n-workflows.json)**
  - **Descripción:** Este flujo automático de n8n guarda todas las configuraciones del servidor en archivos JSON almacenados en una repositorio GitHub.
  - **Complejidad:** Baja (2 nodos)

- **[1127-procesamiento_excel.json](workflows/1127-procesamiento_excel.json)**
  - **Descripción:** Este flujo procesa archivos de Excel mediante diversas fuentes y destinos, permite manipular los datos y opcionalmente guardar o subir el archivo modificado.
  - **Complejidad:** Baja (2 nodos)

- **[1156-qualys-thehive-integration.json](workflows/1156-qualys-thehive-integration.json)**
  - **Descripción:** Este flujo automático busca reportes finalizados en Qualys, descarta los ya procesados según un timestamp previo y crea casos en TheHive con sus respectivos archivos adjuntos de reporte.
  - **Complejidad:** Baja (2 nodos)

- **[1166-threads-notion-integration.json](workflows/1166-threads-notion-integration.json)**
  - **Descripción:** Este flujo automático permite obtener publicaciones de la API de Threads, filtrarlas y guardarlas en una base de datos de Notion después de un análisis detallado.
  - **Complejidad:** Baja (2 nodos)

- **[1446-building-your-first-whatsapp-chatbot.json](workflows/1446-building-your-first-whatsapp-chatbot.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos utilizando OpenAI/GPT, Webhook, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (2 nodos)

- **[1480-manipulate-pdf-with-adobe-developer-api.json](workflows/1480-manipulate-pdf-with-adobe-developer-api.json)**
  - **Descripción:** Este flujo permite extracción de datos utilizando OpenAI/GPT, Webhook, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (2 nodos)

- **[1493-scrape-trustpilot-reviews-with-deepseek-openai.json](workflows/1493-scrape-trustpilot-reviews-with-deepseek-openai.json)**
  - **Descripción:** Este flujo permite chatbot, web scraping, análisis de sentimientos, extracción de datos, reportes utilizando OpenAI/GPT, Google Sheets con inteligencia artificial y APIs.
  - **Complejidad:** Baja (2 nodos)

- **[1503-transcribing-bank-statements-to-markdown-ai.json](workflows/1503-transcribing-bank-statements-to-markdown-ai.json)**
  - **Descripción:** Este flujo permite chatbot, transcripción, extracción de datos, generación de contenido utilizando OpenAI/GPT, Webhook, PDF con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (2 nodos)

- **[1512-local-multi-llm-testing-performance-tracker.json](workflows/1512-local-multi-llm-testing-performance-tracker.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos, generación de contenido utilizando OpenAI/GPT, Webhook, Google Sheets con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (2 nodos)

- **[2537-agricultural-crops-vector-db.json](workflows/2537-agricultural-crops-vector-db.json)**
  - **Descripción:** Este flujo automatizado carga conjuntamente imágenes de cultivos agrícolas y datos relacionados (como nombres de las plantas) desde Google Cloud Storage, genera embeddings utilizando el modelo Voyage Multimodal de AI y los almacena en una colección vectorial de Qdrant. Además, verifica si la colección ya existe para evitar duplicaciones e incluye un índice en memoria sobre el nombre de la planta (crop_name). La carga se realiza por lotes con un tamaño configurable, permitiendo así la creación eficiente y rápida de índices.
  - **Complejidad:** Baja (2 nodos)

- **[2560-linkedin-profile-collector.json](workflows/2560-linkedin-profile-collector.json)**
  - **Descripción:** Este flujo automatizado utiliza Google Search a través de SerpAPI para encontrar perfiles de LinkedIn relevantes, limpia y estructura la información usando OpenAI, y guarda los resultados en Excel o NocoDB.
  - **Complejidad:** Baja (2 nodos)

- **[2562-shopify_google_sync.json](workflows/2562-shopify_google_sync.json)**
  - **Descripción:** Este flujo sincroniza automáticamente productos de un almacén Shopify a una hoja de cálculo de Google, utilizando GraphQL para extraer datos como título, descripción, etiquetas y precio. Implementa paginación eficiente mediante el uso del cursor.
  - **Complejidad:** Baja (2 nodos)

- **[2605-Colombian-Invoices-Processor.json](workflows/2605-Colombian-Invoices-Processor.json)**
  - **Descripción:** Este flujo automático procesa facturas electrónicas colombianas recibidas por correo electrónico, verificando datos clave como impuestos y subtotales, y los almacena en Google Sheets usando la normativa tributaria del país.
  - **Complejidad:** Baja (2 nodos)

- **[2636-monday-boarditem-hierarchy.json](workflows/2636-monday-boarditem-hierarchy.json)**
  - **Descripción:** Este flujo automático obtiene todos los campos de un elemento de tablero junto con sus relaciones y subelementos para procesar datos completos.
  - **Complejidad:** Baja (2 nodos)

- **[2642-gmail_vector_embeddings_import.json](workflows/2642-gmail_vector_embeddings_import.json)**
  - **Descripción:** Este flujo automatizado importa correos electrónicos de Gmail y los almacena como embeddings vectoriales en PostgreSQL usando PGVector y el modelo Ollama para facilitar búsquedas similares.
  - **Complejidad:** Baja (2 nodos)

- **[2652-youtube-performance-searcher.json](workflows/2652-youtube-performance-searcher.json)**
  - **Descripción:** Este flujo busca los mejores videos de YouTube en el último dos semanas y los almacena en una base de datos PostgreSQL.
  - **Complejidad:** Baja (2 nodos)

- **[2662-vision-based-scraping.json](workflows/2662-vision-based-scraping.json)**
  - **Descripción:** Este flujo utiliza la IA Gemini para extraer datos de capturas de pantalla web e integra los resultados en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2685-email_campaign_generator.json](workflows/2685-email_campaign_generator.json)**
  - **Descripción:** Este flujo automatiza la creación de campañas de correo electrónico personalizadas usando datos de compra y feedback de clientes. Utiliza OpenAI para generar contenido atractivo y decide si enviar un cupón promocional.
  - **Complejidad:** Baja (2 nodos)

- **[2689-printify-update-product.json](workflows/2689-printify-update-product.json)**
  - **Descripción:** Automatiza la actualización de títulos y descripciones de productos en Printify mediante Google Sheets. El workflow utiliza API de Printify para obtener datos de tiendas y productos, procesa cada producto para generar opciones personalizadas de título y descripción usando OpenAI, y las actualiza en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2691-dialpad_syncro.json](workflows/2691-dialpad_syncro.json)**
  - **Descripción:** Este flujo automatiza la sincronización de datos entre Dialpad y Syncro. Recibe una notificación de llamada inbound, busca al cliente en Syncro, crea un ticket si el cliente no existe o actualiza su estado, y registra la información en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2702-meraki-network-monitor.json](workflows/2702-meraki-network-monitor.json)**
  - **Descripción:** Este flujo automático monitorea y analiza los datos de latencia y pérdida de paquetes en redes Meraki para detectar problemas, notificando solo aquellos que superen umbralsthrough Redis.
  - **Complejidad:** Baja (2 nodos)

- **[2703-google_maps_scraper.json](workflows/2703-google_maps_scraper.json)**
  - **Descripción:** Este flujo extrae y procesa datos de Google Maps usando SerpAPI, elimina duplicados, los formatea y actualiza el estado en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2711-google-sheet-ai-agent.json](workflows/2711-google-sheet-ai-agent.json)**
  - **Descripción:** Este flujo utiliza un agente de inteligencia artificial para interactuar con una hoja de cálculo de Google Sheets, permitiendo listar columnas, obtener valores específicos y recuperar información de clientes basado en operaciones definidas.
  - **Complejidad:** Baja (2 nodos)

- **[2725-flujo-automatico-diario.json](workflows/2725-flujo-automatico-diario.json)**
  - **Descripción:** Este flujo automático programa tareas diarias para extraer y procesar información de calendario, LinkedIn y Twitter, enriquecer datos con Clearbit, y enviar un correo electrónico con un resumen personalizado.
  - **Complejidad:** Baja (2 nodos)

- **[2732-vector-chatbot-pinecone.json](workflows/2732-vector-chatbot-pinecone.json)**
  - **Descripción:** Este flujo configura un sistema de recuperación vectorial para responder preguntas basadas en contenido descargado de Google Drive. Utiliza Pinecone como base de datos vectorial y OpenAI para embeddings y respuesta al chat.
  - **Complejidad:** Baja (2 nodos)

- **[2740-automate_ga_reporting.json](workflows/2740-automate_ga_reporting.json)**
  - **Descripción:** Este flujo automático extrae y procesa datos de Google Analytics para generar reportes detallados sobre estadísticas de páginas, resultados de búsquedas y vistas por país, comparando datos semanales. Los resultados se formatean en HTML y se envían por correo electrónico.
  - **Complejidad:** Baja (2 nodos)

- **[2756-automatizacion-facturas-pdf.json](workflows/2756-automatizacion-facturas-pdf.json)**
  - **Descripción:** Este flujo automatiza la extracción de datos desde facturas PDF enviadas por correo electrónico. Utiliza LlamaParse para analizar los documentos y luego extrae información estructurada con OpenAI, finalmente insertando los datos en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2760-empresa_research.json](workflows/2760-empresa_research.json)**
  - **Descripción:** Este flujo automatiza la investigación de empresas mediante el uso de OpenAI y Google Sheets. Recopila información estructurada de sitios web y bases de datos, y actualiza una hoja de cálculo con los resultados.
  - **Complejidad:** Baja (2 nodos)

- **[2763-google-meet-scheduler.json](workflows/2763-google-meet-scheduler.json)**
  - **Descripción:** Este flujo automatiza la gestión de reuniones mediante Google Calendar y Drive. Recupera los registros de reunión, procesa transcripciones con OpenAI, crea eventos calendarísticos y asigna asistentes.
  - **Complejidad:** Baja (2 nodos)

- **[2764-inventory-enricher.json](workflows/2764-inventory-enricher.json)**
  - **Descripción:** Este flujo automático utiliza Airtable para capturar fotos de un inventario, OpenAI para analizar imágenes y agentes de inteligencia artificial para enriquecer datos. Primero, obtiene las filas aplicables de Airtable con fotos no procesadas. Luego, usa el modelo OpenAI para identificar atributos del objeto en la imagen. Un agente de AI utiliza herramientas personalizadas (búsqueda inversa de imágenes y web scraping) para buscar información adicional. Finalmente, sobreescribe los datos en Airtable con los resultados enriquecidos.
  - **Complejidad:** Baja (2 nodos)

- **[2768-file_sync_qdrant.json](workflows/2768-file_sync_qdrant.json)**
  - **Descripción:** Este flujo monitorea un directorio local y sincroniza cambios en los archivos con Qdrant para crear una base de conocimientos usando Mistral AI.
  - **Complejidad:** Baja (2 nodos)

- **[2773-image-embedding_workflow.json](workflows/2773-image-embedding_workflow.json)**
  - **Descripción:** Este flujo descarga una imagen de Google Drive, extrae información de color y genera palabras clave semánticas usando OpenAI para crear un documento embedding, el cual se almacena en un vector store en memoria.
  - **Complejidad:** Baja (2 nodos)

- **[2782-sync-workflows.json](workflows/2782-sync-workflows.json)**
  - **Descripción:** Este flujo automatiza la sincronización de workflows entre n8n y GitLab. Recupera los workflows de n8n, verifica su estado en GitLab y actualiza o crea nuevos archivos JSON según las diferencias detectadas.
  - **Complejidad:** Baja (2 nodos)

- **[2784-supabase-vector-store.json](workflows/2784-supabase-vector-store.json)**
  - **Descripción:** Este flujo configura una base de datos vectorial en Supabase para almacenar y recuperar documentos con embeddings de OpenAI, permitiendo realizar búsquedas semánticas y contestar preguntas basadas en el contenido.
  - **Complejidad:** Baja (2 nodos)

- **[2791-notion-workflow-generator.json](workflows/2791-notion-workflow-generator.json)**
  - **Descripción:** Este flujo genera un workflow personalizado de n8n para bases de datos de Notion a partir de una URL proporcionada por el usuario. Utiliza agentes de lenguaje y validación para asegurar la correcta estructura del JSON.
  - **Complejidad:** Baja (2 nodos)

- **[2797-adobe-pdf-processing.json](workflows/2797-adobe-pdf-processing.json)**
  - **Descripción:** Este flujo automático implementa una integración con la API de Adobe para procesar archivos PDF, realizando tareas como subir un archivo, enviar una query de procesamiento y descargar el resultado. Utiliza credenciales personalizadas para autenticación y gestiona diferentes estados del proceso.
  - **Complejidad:** Baja (2 nodos)

- **[2821-automatizacion-facturas-outlook.json](workflows/2821-automatizacion-facturas-outlook.json)**
  - **Descripción:** Este flujo automatiza la gestión de facturas desde una cuenta de Outlook, clasificando mensajes para detectar y descargar attachments que sean facturas emitidas a la empresa. Utiliza Google Gemini para verificar si los archivos adjuntos son facturas relevantes y extraer información clave, posteriormente registra estos datos en una hoja de cálculo de Excel.
  - **Complejidad:** Baja (2 nodos)

- **[2826-client-usage-tracker.json](workflows/2826-client-usage-tracker.json)**
  - **Descripción:** Este flujo registra el uso de tokens y costos de clientes al utilizar un servicio de extracción de datos de CV con OpenAI, almacenando los datos en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[2831-rss_to_gsheet_cleaner.json](workflows/2831-rss_to_gsheet_cleaner.json)**
  - **Descripción:** Este flujo automatiza la actualización y manejo de entradas RSS en Google Sheets. Primero, utiliza un temporizador para leer los enlaces desde una hoja de cálculo, luego extrae las noticias correspondientes y las procesa. Filtros eliminan entradas antiguas (más de 3 días) y las nuevas se guardan con un tiempo de espera para evitar bloqueos. Entradas viejas son eliminadas después de cierto tiempo.
  - **Complejidad:** Baja (2 nodos)

- **[2840-google-drive-deduplicate.json](workflows/2840-google-drive-deduplicate.json)**
  - **Descripción:** Este flujo automatiza la deduplicación de archivos en Google Drive. Identifica duplicados basándose en el checksum md5 y gestiona su eliminación o renombrado según las configuraciones de Keep (first/last) y Action (trash/flag).
  - **Complejidad:** Baja (2 nodos)

- **[2842-automated-purchase-order-processing.json](workflows/2842-automated-purchase-order-processing.json)**
  - **Descripción:** Este flujo automatiza la importación y procesamiento de órdenes de compra desde Outlook. Convierte archivos XLSX a formato legible por LLMs, extrae detalles usando IA y realiza validaciones.
  - **Complejidad:** Baja (2 nodos)

- **[2845-linkedin-enrichment-icebreaker.json](workflows/2845-linkedin-enrichment-icebreaker.json)**
  - **Descripción:** Este flujo automático en n8n permite extraer y enriquecer datos de perfiles de LinkedIn usando Bright Data, generar icebreakers personalizados con el modelo Claude de Anthropic y actualizar una hoja de Google Sheets con la información resultante.
  - **Complejidad:** Baja (2 nodos)

- **[2878-n8n-backup-workflows.json](workflows/2878-n8n-backup-workflows.json)**
  - **Descripción:** Este flujo automatiza la copia de seguridad diaria de los workflows de n8n en Google Drive. Busca y procesa todos los workflows, y si no hay un archivo existente, crea uno nuevo; si ya existe, lo actualiza con la nueva información.
  - **Complejidad:** Baja (2 nodos)

- **[2884-instagram-post-automation.json](workflows/2884-instagram-post-automation.json)**
  - **Descripción:** Automatiza la creación de publicaciones en Instagram mediante Google Sheets y herramientas AI. Incluye desde la generación de conceptos de contenido hasta la publicación final.
  - **Complejidad:** Baja (2 nodos)

- **[2904-ai-ready-vector-datasets.json](workflows/2904-ai-ready-vector-datasets.json)**
  - **Descripción:** Este flujo crea conjuntos de datos vectoriales listos para LLMs usando Bright Data, Gemini y Pinecone. Realiza extracción de información, formateo estructurado y persistencia en una base de vectores.
  - **Complejidad:** Baja (2 nodos)

- **[2923-dashboard-metricas.json](workflows/2923-dashboard-metricas.json)**
  - **Descripción:** Este flujo automatiza la actualización de un dashboard que recopila y muestra estadísticas y métricas desde diversas fuentes como Docker, npm, GitHub y Product Hunt. Utiliza Cron para programar ejecuciones periódicas, extrae datos mediante HTTP requests, procesa y formatea los resultados, y actualiza_WIDGETS en un host dashboard con autenticación.
  - **Complejidad:** Baja (2 nodos)

- **[2926-google-sheets-to-postgres.json](workflows/2926-google-sheets-to-postgres.json)**
  - **Descripción:** Este flujo automatiza la importación de datos desde Google Sheets a PostgreSQL. Analiza dinámicamente los datos para detectar tipos y generar esquemas SQL, crea tablas si no existen y realiza inserciones con formato adecuado.
  - **Complejidad:** Baja (2 nodos)

- **[2928-sitemap-index-automatizado.json](workflows/2928-sitemap-index-automatizado.json)**
  - **Descripción:** Este flujo automatiza la indexación de URLs en Google Search Console usando sitemap.xml. Extrae URLs de los archivos sitemap, verifica su estado y actualiza las que han sido modificadas o no están indexadas.
  - **Complejidad:** Baja (2 nodos)

- **[2955-auto-content-generator.json](workflows/2955-auto-content-generator.json)**
  - **Descripción:** Este flujo automatiza la creación de contenido multimedia basado en datos de Google Sheets. Genera imágenes y videos cinemáticos con textos promocionales, agrega sonidos ambientales, y publica el resultado en YouTube.
  - **Complejidad:** Baja (2 nodos)

- **[2967-sql-agent-scheme.json](workflows/2967-sql-agent-scheme.json)**
  - **Descripción:** Flujo que utiliza un agente de IA para generar consultas SQL basadas en esquema de base de datos guardando la estructura localmente y usando OpenAI para formular sentencias SQL.
  - **Complejidad:** Baja (2 nodos)

- **[2968-image-embedder.json](workflows/2968-image-embedder.json)**
  - **Descripción:** Este flujo automatiza la creación de embeddings de imágenes mediante resumen textual. Descarga una imagen desde Google Drive, extrae información de colores y genera palabras clave usando OpenAI, luego combina estos datos para crear un documento que se almacena en un vector store.
  - **Complejidad:** Baja (2 nodos)

- **[2970-autoclip-video-generator.json](workflows/2970-autoclip-video-generator.json)**
  - **Descripción:** Este flujo automático genera clips de video seleccionando aleatoriamente entre vídeos y música de Google Drive, yuxtapone citas y luego los sube a YouTube.
  - **Complejidad:** Baja (2 nodos)

- **[2983-hacker-news-jobs-scraper.json](workflows/2983-hacker-news-jobs-scraper.json)**
  - **Descripción:** Este flujo extrae y procesa información de ofertas laborales publicadas en Hacker News utilizando su API y_algolia, estructura los datos con OpenAI y los exporta a Airtable.
  - **Complejidad:** Baja (2 nodos)

- **[2987-gestion-solicitudes-AI.json](workflows/2987-gestion-solicitudes-AI.json)**
  - **Descripción:** Flujo que automatiza la gestión de solicitudes de empleo usando formularios y herramientas de inteligencia artificial para extraer información, clasificar documentos y almacenar datos en Airtable.
  - **Complejidad:** Baja (2 nodos)

- **[3004-voice-chatbot-rag-qdrant.json](workflows/3004-voice-chatbot-rag-qdrant.json)**
  - **Descripción:** Este flujo implementa un chatbot de voz que utiliza RAG (Retrieval-Augmented Generation) con ElevenLabs y OpenAI para responder preguntas usando una base de datos vectorial en Qdrant.
  - **Complejidad:** Baja (2 nodos)

- **[3014-factura-extraccion-llamaparse.json](workflows/3014-factura-extraccion-llamaparse.json)**
  - **Descripción:** Este flujo automático extrae información de facturas en formato PDF usando LlamaParse y OpenAI. Detecta correos con adjuntos PDF, procesa los documentos para obtener datos estructurados y los almacena en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[3034-google-analytics-seo-analysis.json](workflows/3034-google-analytics-seo-analysis.json)**
  - **Descripción:** Este flujo automático recopila y analiza datos de Google Analytics para una página web, comparando estadísticas semanales como páginas vistas, usuarios activos y tasas de participación. Luego, envía esta información a un modelo de lenguaje A.I. para obtener recomendaciones SEO y guarda los resultados en Baserow.
  - **Complejidad:** Baja (2 nodos)

- **[3060-manipula-pdf-adobe.json](workflows/3060-manipula-pdf-adobe.json)**
  - **Descripción:** Este flujo maneja la manipulación de archivos PDF utilizando la API de Adobe Services. Realiza autenticación, carga un archivo PDF, procesa solicitudes específicas (como extracción) y espera la finalización del proceso antes de descargar los resultados.
  - **Complejidad:** Baja (2 nodos)

- **[3064-outlook-email-ai-assistant.json](workflows/3064-outlook-email-ai-assistant.json)**
  - **Descripción:** Este flujo utiliza Microsoft Outlook para leer correos electrónicos no marcados yWithout categorías, procesa su contenido con OpenAI para categorizarlos, actualiza su importancia y asigna categorías. También integra contactos de Monday.com y Airtable para mejorar la contextualización.
  - **Complejidad:** Baja (2 nodos)

- **[3071-line-file-save-to-google-drive.json](workflows/3071-line-file-save-to-google-drive.json)**
  - **Descripción:** Este flujo automatiza la descarga de archivos desde LINE, los organiza en Google Drive según configuración y registra detalles en una hoja de cálculo.
  - **Complejidad:** Baja (2 nodos)

- **[3081-whatsapp-ai-chatbot.json](workflows/3081-whatsapp-ai-chatbot.json)**
  - **Descripción:** Este flujo implementa un chatbot de WhatsApp que utiliza tecnología RAG (Retrieval-Augmented Generation) para responder consultas usando OpenAI y Qdrant. Recoge documentos desde Google Drive, los vectoriza con OpenAI, almacena en Qdrant y usa el agente AI para contestar preguntas basadas en ellos.
  - **Complejidad:** Baja (2 nodos)

- **[3084-notion-chatbot-generator.json](workflows/3084-notion-chatbot-generator.json)**
  - **Descripción:** Este flujo genera un asistente de chatbot personalizado para bases de datos de Notion, creando una workflow adaptada al esquema proporcionado. Analiza la URL de la base de datos, simplifica los objetos y utiliza agentes de lenguaje para modificar el JSON del workflow según las necesidades específicas.
  - **Complejidad:** Baja (2 nodos)

- **[3091-obsidian-podcast-flow.json](workflows/3091-obsidian-podcast-flow.json)**
  - **Descripción:** Flujo que convierte notas de Obsidian en audios para podcasts usando OpenAI y almacena datos en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[3097-mcp-supabase-agent.json](workflows/3097-mcp-supabase-agent.json)**
  - **Descripción:** Este flujo implementa un agente de LangChain con capacidades de recuperación de vectores y embeddings de OpenAI, usando Supabase para almacenar y gestionar datos como mensajes, tareas y estado.
  - **Complejidad:** Baja (2 nodos)

- **[3101-update-printify-products.json](workflows/3101-update-printify-products.json)**
  - **Descripción:** Este flujo actualiza títulos y descripciones de productos en Printify usando OpenAI para optimizar contenido y Google Sheets para la gestión.
  - **Complejidad:** Baja (2 nodos)

- **[3105-generate-sql-from-schema.json](workflows/3105-generate-sql-from-schema.json)**
  - **Descripción:** Este flujo genera consultas SQL basadas en un esquema de base de datos usando inteligencia artificial. Extrae información de la estructura de las tablas y utiliza el modelo OpenAI para crear sentencias SQL sin necesidad de acceder a los datos reales.
  - **Complejidad:** Baja (2 nodos)

- **[3114-chatbot_personal_shopper.json](workflows/3114-chatbot_personal_shopper.json)**
  - **Descripción:** Este flujo implementa un chatbot personal shopper para WooCommerce que utiliza RAG con Google Drive y openAI. Analiza mensajes de chat para buscar productos o responder preguntas generales usando vectores almacenados en Qdrant.
  - **Complejidad:** Baja (2 nodos)

- **[3118-Vision-Scraping-Agent.json](workflows/3118-Vision-Scraping-Agent.json)**
  - **Descripción:** Este flujo automatiza la extracción de datos web utilizando vision artificial con Google Sheets, ScrapingBee y Gemini. Realiza capturas de pantalla completas de páginas web, utiliza el modelo Gemini para extraer información visualmente, y en caso de falla, recurre a herramientas HTML para asegurar datos precisos.
  - **Complejidad:** Baja (2 nodos)

- **[3119-batch_crops_qdrant.json](workflows/3119-batch_crops_qdrant.json)**
  - **Descripción:** Este flujo carga un conjunto de datos de imágenes agrícolas en Qdrant usando embeddings de Voyage AI y Google Cloud Storage. Primero verifica si la colección existe, crea una nueva si es necesario, luego procesa las imágenes en tandas y las sube al vectorstore.
  - **Complejidad:** Baja (2 nodos)

- **[3162-google-analytics-to-ai-seo-analysis.json](workflows/3162-google-analytics-to-ai-seo-analysis.json)**
  - **Descripción:** Este flujo recopila datos de analítica web, procesa y envía información a un modelo de IA para análisis SEO comparativo semanal, guardando los resultados en Baserow.
  - **Complejidad:** Baja (2 nodos)

- **[3216-aplicacion_cv_automatizada.json](workflows/3216-aplicacion_cv_automatizada.json)**
  - **Descripción:** Flujo de aplicación para la gestión de CV y formulario de solicitud optimizado con IA, que incluye validación de documentos, extracción de información, y almacenamiento en Airtable.
  - **Complejidad:** Baja (2 nodos)

- **[3232-automated-backup.json](workflows/3232-automated-backup.json)**
  - **Descripción:** Este flujo automatiza la copia de seguridad de trabajos en GitHub usando n8n. Almacena los workflows como archivos JSON en un repositorio designado.
  - **Complejidad:** Baja (2 nodos)

- **[3256-github-backup-workflow.json](workflows/3256-github-backup-workflow.json)**
  - **Descripción:** Este flujo automatiza la copia de seguridad de trabajos en GitHub al comparar y actualizar archivos JSON. Utiliza un bucle para procesar cada instancia, verifica diferencias entre versiones y gestiona operaciones de creación o edición según el estado.
  - **Complejidad:** Baja (2 nodos)

- **[3263-ai-resume-screening.json](workflows/3263-ai-resume-screening.json)**
  - **Descripción:** Flujo automático para evaluar currículos en base a una descripción de empleo utilizando inteligencia artificial. Analiza, clasifica y organiza candidatos en carpetas según su perfil.
  - **Complejidad:** Baja (2 nodos)

- **[3270-call-processing-flow.json](workflows/3270-call-processing-flow.json)**
  - **Descripción:** Este flujo automatiza la extracción y procesamiento de datos de llamadas de venta, integrando información complementaria como competidores y listas de integraciones para enriquecer los transcritos antes de enviarlos a un sistema de inteligencia artificial.
  - **Complejidad:** Baja (2 nodos)

- **[3285-mistral-ocr-parsing.json](workflows/3285-mistral-ocr-parsing.json)**
  - **Descripción:** Flujo que utiliza Mistral OCR para analizar documentos y imágenes subidas a Google Drive. Primero carga archivos desde Google Drive, luego los envía a Mistral Cloud para obtener URLs firmadas, procesa el OCR con esas URLs y finalmente realiza análisis de documento o imagen utilizando diferentes modelos (chat completions).
  - **Complejidad:** Baja (2 nodos)

- **[3290-aprendizaje_idiomas.json](workflows/3290-aprendizaje_idiomas.json)**
  - **Descripción:** Este flujo automatiza la creación de tarjetas flash para aprendizaje de idiomas. Utiliza Google Sheets para almacenar palabras, traduce al chino usando Google Translate, genera fonética y oraciones con un agente AI, busca imágenes en Pexels y las sube a Google Drive.
  - **Complejidad:** Baja (2 nodos)

- **[3297-dropbox-watch-files.json](workflows/3297-dropbox-watch-files.json)**
  - **Descripción:** Este flujo monitorea cambios en dos carpetas de Dropbox (/z_Apps/a_iphone/RecUp Memos/ y /z_Apps/auphonic/whisper) para detectar nuevos archivos o carpetas. Utiliza NocoDB para almacenar los metadatos de los archivos, filtra aquellos que no han sido procesados antes y ejecuta flujos específicos para cada tipo de archivo detectado.
  - **Complejidad:** Baja (2 nodos)

- **[3305-seo-wordpress-generator.json](workflows/3305-seo-wordpress-generator.json)**
  - **Descripción:** Este flujo automático genera contenido optimizado para SEO para WordPress utilizando investigación de Perplexity y OpenAI. Incluye creación de títulos, slug y metadatos, desarrollo de HTML estructurado, y publicación en el blog.
  - **Complejidad:** Baja (2 nodos)

- **[3320-supabase-vector-flow.json](workflows/3320-supabase-vector-flow.json)**
  - **Descripción:** Este flujo integra Supabase con n8n para realizar inserciones, actualizaciones y recuperaciones en una base de datos vectoriales, utilizando embeddings de OpenAI y un motor de vectores optimizado para búsquedas eficientes.
  - **Complejidad:** Baja (2 nodos)

- **[3340-transcribe-bank-statements.json](workflows/3340-transcribe-bank-statements.json)**
  - **Descripción:** Este flujo transforma un estado de cuenta bancario en formato PDF a markdown utilizando el modelo Gemini Vision AI para una fácil extracción de datos.
  - **Complejidad:** Baja (2 nodos)

- **[3344-scrape-trustpilot-sentiment.json](workflows/3344-scrape-trustpilot-sentiment.json)**
  - **Descripción:** Este flujo extrae reseñas de Trustpilot usando DeepSeek, analiza su sentimiento con OpenAI y las registra en Google Sheets.
  - **Complejidad:** Baja (2 nodos)

- **[0047-calendly-notion-auto.json](workflows/0047-calendly-notion-auto.json)**
  - **Descripción:** Este flujo automatizado crea un nuevo registro en una base de datos Notion cada vez que se crea un 'invitee' (invitado) en Calendly.
  - **Complejidad:** Baja (2 nodos)

- **[0098-line-chatbot-memory.json](workflows/0098-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite que un mensaje recibido en el webhook se utilice para crear un recurso en Netlify usando datos dinámicos.
  - **Complejidad:** Baja (2 nodos)

- **[0169-onfleet-task-from-google-drive.json](workflows/0169-onfleet-task-from-google-drive.json)**
  - **Descripción:** Este flujo automático crea una tarea en Onfleet cuando un archivo específico en Google Drive es actualizado.
  - **Complejidad:** Baja (2 nodos)

- **[0179-bubble-data-access.json](workflows/0179-bubble-data-access.json)**
  - **Descripción:** Este flujo permite realizar una solicitud HTTP autenticada para acceder datos de usuarios desde la API de Bubble.
  - **Complejidad:** Baja (2 nodos)

- **[0243-google-drive-notion.json](workflows/0243-google-drive-notion.json)**
  - **Descripción:** Este flujo automático crea una página en la base de datos de Notion cuando se sube un nuevo archivo a una carpeta específica de Google Drive.
  - **Complejidad:** Baja (2 nodos)

- **[0332-strava-beeminder-datapoint-flow.json](workflows/0332-strava-beeminder-datapoint-flow.json)**
  - **Descripción:** Este flujo agrega un punto de datos en Beeminder cuando se crea una nueva actividad en Strava.
  - **Complejidad:** Baja (2 nodos)

- **[0382-webhook-google-sheets.json](workflows/0382-webhook-google-sheets.json)**
  - **Descripción:** Este flujo lee datos de una hoja específica de Google Sheets cuando se recibe una solicitud a través del webhook.
  - **Complejidad:** Baja (2 nodos)

- **[0468-syncro-clockify-tasks.json](workflows/0468-syncro-clockify-tasks.json)**
  - **Descripción:** Este flujo automático recibe datos vía webhook y los usa para crear tareas en Clockify.
  - **Complejidad:** Baja (2 nodos)

- **[0538-postgres-query.json](workflows/0538-postgres-query.json)**
  - **Descripción:** Este flujo automático permite ejecutar un comando SQL de selección en una base de datos PostgreSQL mediante una activación manual.
  - **Complejidad:** Baja (2 nodos)

- **[0557-facebook_datos_basicos.json](workflows/0557-facebook_datos_basicos.json)**
  - **Descripción:** Este flujo obtiene manualmente los datos personales básicos (nombre y apellido) del usuario actual en Facebook mediante una llamada a la API.
  - **Complejidad:** Baja (2 nodos)

- **[0560-trigger-cockpit-sample.json](workflows/0560-trigger-cockpit-sample.json)**
  - **Descripción:** Este flujo automático permite iniciar un proceso manual y conectarlo inmediatamente con el nodo de Cockpit para visualizar datos de la colección 'samplecollection'.
  - **Complejidad:** Baja (2 nodos)

- **[0566-hacker-news-trigger.json](workflows/0566-hacker-news-trigger.json)**
  - **Descripción:** Este flujo automático permite ejecutar una acción manuala para obtener datos de todas las categorías de Hacker News.
  - **Complejidad:** Baja (2 nodos)

- **[0586-typeform-seleccion-automatizada.json](workflows/0586-typeform-seleccion-automatizada.json)**
  - **Descripción:** Este flujo automatizado permite registrar selecciones de formulario Typeform en Airtable.
  - **Complejidad:** Baja (2 nodos)

- **[0592-monday-board-data.json](workflows/0592-monday-board-data.json)**
  - **Descripción:** Este flujo ejecuta una acción manual en n8n para obtener datos de un tablero específico en Monday.com.
  - **Complejidad:** Baja (2 nodos)

- **[0593-line-chatbot-memory.json](workflows/0593-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada mediante la persistencia en Redis.
  - **Complejidad:** Baja (2 nodos)

- **[0594-spacex-graphql-query.json](workflows/0594-spacex-graphql-query.json)**
  - **Descripción:** Este flujo manual consulta la API de SpaceX mediante GraphQL para obtener detalles sobre los últimos lanzamientos y datos de las naves espaciales.
  - **Complejidad:** Baja (2 nodos)

- **[0595-box-folder-execution.json](workflows/0595-box-folder-execution.json)**
  - **Descripción:** Este flujo ejecuta automáticamente una acción sobre una carpeta específica de Box cuando se hace clic en el botón 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[0600-one-drive-folder-creation.json](workflows/0600-one-drive-folder-creation.json)**
  - **Descripción:** Este flujo manual permite crear una carpeta en OneDrive al hacer clic en el botón 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[0601-excel-trigger.json](workflows/0601-excel-trigger.json)**
  - **Descripción:** Este flujo ejecuta un proceso manual al hacer clic en el botón de inicio, que luego consulta todos los datos disponibles a través del conector Microsoft Excel.
  - **Complejidad:** Baja (2 nodos)

- **[0609-trigger-leer-imagen-binaria.json](workflows/0609-trigger-leer-imagen-binaria.json)**
  - **Descripción:** Este flujo permite cargar archivos binarios como imágenes al hacer clic en el desencadenador.
  - **Complejidad:** Baja (2 nodos)

- **[0610-read-images-trigger.json](workflows/0610-read-images-trigger.json)**
  - **Descripción:** Este flujo automático permite a un usuario iniciar manualmente una ejecución, la cual lee archivos binarios (específicamente imágenes jpg) desde el directorio /data/lol.
  - **Complejidad:** Baja (2 nodos)

- **[0674-transformador-array.json](workflows/0674-transformador-array.json)**
  - **Descripción:** Este flujo automatizado inicia con un nodo que genera datos estáticos en forma de array y luego utiliza una función personalizada para transformar cada elemento del array en un objeto individual JSON.
  - **Complejidad:** Baja (2 nodos)

- **[0709-openweathermap-weather.json](workflows/0709-openweathermap-weather.json)**
  - **Descripción:** Este flujo automático permite al usuario ejecutar un proceso manual que consulta los datos meteorológicos actuales de la ciudad especificada (en este caso, Berlin) mediante el servicio OpenWeatherMap.
  - **Complejidad:** Baja (2 nodos)

- **[0742-typeform-demio-registration.json](workflows/0742-typeform-demio-registration.json)**
  - **Descripción:** Este flujo automatizado activa el registro en Demio con datos proporcionados por un formulario de Typeform.
  - **Complejidad:** Baja (2 nodos)

- **[0769-sql-query-execution.json](workflows/0769-sql-query-execution.json)**
  - **Descripción:** Este flujo automático permite ejecutar una consulta SQL en base de datos Microsoft SQL mediante un desencadenador manual.
  - **Complejidad:** Baja (2 nodos)

- **[1193-line-chatbot-memory.json](workflows/1193-line-chatbot-memory.json)**
  - **Descripción:** Este flujo procesa datos de usuario para mantener el contexto en conversaciones.
  - **Complejidad:** Baja (2 nodos)

- **[0016-todoist-task-creator.json](workflows/0016-todoist-task-creator.json)**
  - **Descripción:** Este flujo permite crear una nueva tarea en la aplicación Todoist a través de un trigger manual.
  - **Complejidad:** Baja (2 nodos)

- **[0039-clickup-task-creator.json](workflows/0039-clickup-task-creator.json)**
  - **Descripción:** Este flujo automático permite crear una tarea en ClickUp mediante un desencadenador manual.
  - **Complejidad:** Baja (2 nodos)

- **[0094-zendesk-ticket-flow.json](workflows/0094-zendesk-ticket-flow.json)**
  - **Descripción:** Este flujo automático permite crear un ticket en Zendesk mediante una activación manual.
  - **Complejidad:** Baja (2 nodos)

- **[0099-crear-contacto-drift.json](workflows/0099-crear-contacto-drift.json)**
  - **Descripción:** Este flujo permite crear un contacto en la plataforma Drift manualmente al hacer clic en el trigger.
  - **Complejidad:** Baja (2 nodos)

- **[0577-rundeck-job-trigger.json](workflows/0577-rundeck-job-trigger.json)**
  - **Descripción:** Este flujo permite iniciar manualmente la ejecución de una tarea específica en Rundeck al hacer clic en el botón 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[0602-helpscout-mailbox-fetcher.json](workflows/0602-helpscout-mailbox-fetcher.json)**
  - **Descripción:** Este flujo permite obtener todos los correos electrónicos almacenados en una caja específica mediante integración con HelpScout.
  - **Complejidad:** Baja (2 nodos)

- **[0631-manual-github-profile-request.json](workflows/0631-manual-github-profile-request.json)**
  - **Descripción:** Este flujo permite desencadenar manualmente una solicitud al API de GitHub para obtener el perfil de un repositorio.
  - **Complejidad:** Baja (2 nodos)

- **[0648-unleashed-ordenes-completadas.json](workflows/0648-unleashed-ordenes-completadas.json)**
  - **Descripción:** Este flujo manual ejecuta una consulta en el sistema Unleashed solo para órdenes completadas.
  - **Complejidad:** Baja (2 nodos)

- **[0701-circleci-api-trigger.json](workflows/0701-circleci-api-trigger.json)**
  - **Descripción:** Este flujo permite ejecutar una acción en la plataforma de CI/CD CircleCI a través de su API al activar manualmente el trigger.
  - **Complejidad:** Baja (2 nodos)

- **[0707-Crear-Issue-Jira.json](workflows/0707-Crear-Issue-Jira.json)**
  - **Descripción:** Este flujo automático permite crear rápidamente una nueva incidencia (issue) en Jira Software mediante la activación de un desencadenador manual.
  - **Complejidad:** Baja (2 nodos)

- **[0728-crear-usuario-intercom.json](workflows/0728-crear-usuario-intercom.json)**
  - **Descripción:** Este flujo automático permite crear un nuevo usuario en Intercom al hacer clic manualmente.
  - **Complejidad:** Baja (2 nodos)

- **[0760-asana-task-creator.json](workflows/0760-asana-task-creator.json)**
  - **Descripción:** Este flujo permite crear una nueva tarea en Asana manualmente mediante un clic en 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[1196-trello-crear-tarjeta-automatico.json](workflows/1196-trello-crear-tarjeta-automatico.json)**
  - **Descripción:** Este flujo permite crear automáticamente una tarjeta en Trello cuando se ejecuta manualmente.
  - **Complejidad:** Baja (2 nodos)

- **[0003-line-chatgpt-image-flow.json](workflows/0003-line-chatgpt-image-flow.json)**
  - **Descripción:** Este flujo automático procesa solicitudes de generación de imágenes a través del chatbot LINE y los almacena en Google Drive como archivos binarios y en una hoja de cálculo con detalles incluyendo prompts, costos estimados e información relevante.
  - **Complejidad:** Baja (1 nodos)

- **[0205-workflow-merge-demo.json](workflows/0205-workflow-merge-demo.json)**
  - **Descripción:** Este flujo demuestra cómo el nodo Merge de n8n combina datos de diferentes fuentes usando diferentes modos de unión, mostrando ejemplos desde ingredientes hasta la formación de bandas.
  - **Complejidad:** Baja (1 nodos)

- **[0383-workflow-estado.json](workflows/0383-workflow-estado.json)**
  - **Descripción:** Este flujo automático ejecuta un workflow principal con intervalos de disparo y verifica en Redis si el workflow está actualmente en ejecución para evitar múltiples instancias concurrentes.
  - **Complejidad:** Baja (1 nodos)

- **[0425-n8n-flujos-backup-github.json](workflows/0425-n8n-flujos-backup-github.json)**
  - **Descripción:** Este flujo automático respalda workflows de n8n en un repositorio git verificando cambios y actualizando archivos.
  - **Complejidad:** Baja (1 nodos)

- **[0803-n8n-hr-cv-automation.json](workflows/0803-n8n-hr-cv-automation.json)**
  - **Descripción:** Este flujo automático analiza currículums de candidatos mediante la extracción y resumen de datos clave usando modelos de IA.
  - **Complejidad:** Baja (1 nodos)

- **[0806-stock-fundamental-ai-analyzer.json](workflows/0806-stock-fundamental-ai-analyzer.json)**
  - **Descripción:** Este flujo automático analiza datos de fondos utilizando embeddings de OpenAI, procesamiento con LangChain y almacenamiento vectorial en Qdrant para responder preguntas sobre análisis fundamental de acciones.
  - **Complejidad:** Baja (1 nodos)

- **[0824-rag-financial-report-gen.json](workflows/0824-rag-financial-report-gen.json)**
  - **Descripción:** Este flujo utiliza el sistema RAG para analizar informes de rentabilidad corporativa basados en documentos históricos almacenados como embeddings en Pinecone. Procesa información mediante modelos de Google Gemini y OpenAI, sintetiza los datos con un agente especializado e integra todo en un informe markdown que se guarda automáticamente en Google Docs.
  - **Complejidad:** Baja (1 nodos)

- **[0841-bright-data-gemini-hotel-summarizer.json](workflows/0841-bright-data-gemini-hotel-summarizer.json)**
  - **Descripción:** Este flujo automático extrae datos de hoteles desde Bing Copilot usando la API de Bright Data y utiliza Google Gemini AI para formatearlos en estructura JSON y generar resúmenes concisos.
  - **Complejidad:** Baja (1 nodos)

- **[0846-workflow-pinecone-openai.json](workflows/0846-workflow-pinecone-openai.json)**
  - **Descripción:** Este flujo carga documentos desde Google Drive en un vector store de Pinecone utilizando embeddings de OpenAI para luego permitir la recuperación de información mediante cadenas de pregunta-respuesta.
  - **Complejidad:** Baja (1 nodos)

- **[0855-eliminar-fondos-google-drive.json](workflows/0855-eliminar-fondos-google-drive.json)**
  - **Descripción:** Este flujo elimina automáticamente los fondos de imágenes en Google Drive usando la API de Photroom.
  - **Complejidad:** Baja (1 nodos)

- **[0871-line-chatbot-memory.json](workflows/0871-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada con los usuarios al procesar mensajes tanto en texto como imágenes, extrayendo información relevante sobre estados de cuenta y datos personales para luego insertarla en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[0890-Google_Sheet_AI_Interface.json](workflows/0890-Google_Sheet_AI_Interface.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con una hoja de Google mediante funciones personalizadas, optimizando la consulta y gestión de datos.
  - **Complejidad:** Baja (1 nodos)

- **[0944-obsidian-email-sender.json](workflows/0944-obsidian-email-sender.json)**
  - **Descripción:** Este flujo automático permite enviar correos electrónicos desde Obsidian utilizando webhooks, procesando correctamente los archivos adjuntos mediante codificación base64 y añadiendo la información del remitente.
  - **Complejidad:** Baja (1 nodos)

- **[0959-squarespace-backup.json](workflows/0959-squarespace-backup.json)**
  - **Descripción:** Este flujo automático permite guardar las personalizaciones de Squarespace (código de inyecciones) en archivos HTML dentro de un repositorio de GitHub, manteniendo el contexto por dominio y realizando respaldos cada hora.
  - **Complejidad:** Baja (1 nodos)

- **[0989-vertex-ai-pdf-image-extractor.json](workflows/0989-vertex-ai-pdf-image-extractor.json)**
  - **Descripción:** Este flujo automático permite extraer texto de archivos PDF e imágenes usando Vertex AI (Gemini) y convertirlos en CSV para almacenar la información.
  - **Complejidad:** Baja (1 nodos)

- **[0991-umami-analytics-ai.json](workflows/0991-umami-analytics-ai.json)**
  - **Descripción:** Este flujo analítico procesa datos de tráfico web desde Umami utilizando múltiples API calls y transformaciones JavaScript para extraer métricas clave como visitas e impresiones. Luego envía estos resultados junto con solicitudes a un modelo AI de OpenRouter para generar análisis detallado, que finalmente se almacena en Baserow.
  - **Complejidad:** Baja (1 nodos)

- **[1001-flux-image-generator.json](workflows/1001-flux-image-generator.json)**
  - **Descripción:** Este flujo automatizado permite generar imágenes con estilos predefinidos (como AI Dystopia, Hyper-Surreal Escape, etc.) mediante la API de huggingface. Después de que un usuario completa un formulario proporcionando un prompt y selecciona un estilo, el sistema llama al modelo correspondiente, sube la imagen generada a S3 y muestra el resultado en una página web.
  - **Complejidad:** Baja (1 nodos)

- **[1237-bright-data-gemini-scraping-agent.json](workflows/1237-bright-data-gemini-scraping-agent.json)**
  - **Descripción:** Este flujo automático utiliza un asistente de IA basado en Google Gemini para analizar consultas sobre scraping web. Luego delega la tarea a herramientas del MCP Client (Bright Data) que extraen datos desde URLs especificadas mediante webhooks, manteniendo el contexto con una memoria buffer y almacenando resultados en archivos.
  - **Complejidad:** Baja (1 nodos)

- **[1396-ai-product-data-processor.json](workflows/1396-ai-product-data-processor.json)**
  - **Descripción:** Procesa datos de productos con ayuda de IA.
  - **Complejidad:** Baja (1 nodos)

- **[1402-edi-processor.json](workflows/1402-edi-processor.json)**
  - **Descripción:** Procesa archivos EDI de intercambio electrónico de datos.
  - **Complejidad:** Baja (1 nodos)

- **[1453-convert-url-html-to-markdown.json](workflows/1453-convert-url-html-to-markdown.json)**
  - **Descripción:** Este flujo permite automatización, web scraping, extracción de datos utilizando Webhook, Airtable con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Baja (1 nodos)

- **[1468-fetch-dynamic-prompts-from-github.json](workflows/1468-fetch-dynamic-prompts-from-github.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos con inteligencia artificial y APIs.
  - **Complejidad:** Baja (1 nodos)

- **[1489-reconcile-rent-payments-with-local-excel-openai.json](workflows/1489-reconcile-rent-payments-with-local-excel-openai.json)**
  - **Descripción:** Este flujo permite chatbot, extracción de datos, generación de contenido, reportes utilizando OpenAI/GPT, Excel con inteligencia artificial y APIs.
  - **Complejidad:** Baja (1 nodos)

- **[2541-agricultural-anomaly-detector.json](workflows/2541-agricultural-anomaly-detector.json)**
  - **Descripción:** Este flujo analiza imágenes de cultivos para detectar si contienen ejemplares no conocidos, utilizando embeddings multimodales y una base de datos vectorial Qdrant.
  - **Complejidad:** Baja (1 nodos)

- **[2546-sql-agent-visualizacion.json](workflows/2546-sql-agent-visualizacion.json)**
  - **Descripción:** Este flujo automatizado permite a un AI Agent interactuar con bases de datos mediante consultas SQL y generar visualizaciones usando Chart.js y Quickchart.io basadas en la necesidad del usuario. El clasificador textual decide si se requiere una representación gráfica para mejorar la comprensión de los resultados.
  - **Complejidad:** Baja (1 nodos)

- **[2587-youtube-sentiment-analyzer.json](workflows/2587-youtube-sentiment-analyzer.json)**
  - **Descripción:** Este flujo analiza automáticamente los comentarios de videos de YouTube a partir de una lista en Google Sheets utilizando la API de YouTube y la IA de OpenAI para categorizarlos como positivos, neutros o negativos.
  - **Complejidad:** Baja (1 nodos)

- **[2592-multipage-scraper.json](workflows/2592-multipage-scraper.json)**
  - **Descripción:** Este flujo automático permite extraer y almacenar en Google Drive el contenido de múltiples páginas web a partir del archivo sitemap.xml usando la API de Jina.ai para realizar búsquedas inteligentes.
  - **Complejidad:** Baja (1 nodos)

- **[2596-image-to-3d-conversion.json](workflows/2596-image-to-3d-conversion.json)**
  - **Descripción:** Este flujo automático permite convertir una imagen en un modelo 3D (.glb) utilizando la API de Fal.ai y luego guardar el resultado en Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[2601-facturacion-automatizada.json](workflows/2601-facturacion-automatizada.json)**
  - **Descripción:** Este flujo automatizado descarga archivos adjuntos de correos electrónicos no leídos en Gmail y los guarda en Google Drive. Luego utiliza OpenAI para extraer datos clave de las facturas (fecha, descripción, precio total), que se almacenan en un esquema estructurado y finalmente se incorporan a una hoja de cálculo.
  - **Complejidad:** Baja (1 nodos)

- **[2617-woocommerce-ai-product-importer.json](workflows/2617-woocommerce-ai-product-importer.json)**
  - **Descripción:** Este flujo de trabajo automatiza la importación de productos en WooCommerce a través de Google Sheets. Analiza los detalles del producto para generar metatítulos y meta-descripciones SEO optimizadas, las crea inmediatamente en el catálogo WordPress e inserta esta información directamente en una hoja de cálculo.
  - **Complejidad:** Baja (1 nodos)

- **[2634-opensea-nft-agent.json](workflows/2634-opensea-nft-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de n8n interactuar con la API de OpenSea para recuperar y procesar datos específicos sobre NFTs.
  - **Complejidad:** Baja (1 nodos)

- **[2635-bright_data_gemini_search.json](workflows/2635-bright_data_gemini_search.json)**
  - **Descripción:** Este flujo automatizado busca datos web utilizando Perplexity, extrae información relevante con LangChain y utiliza Gemini AI para generar resúmenes.
  - **Complejidad:** Baja (1 nodos)

- **[2653-line-chatbot-memory.json](workflows/2653-line-chatbot-memory.json)**
  - **Descripción:** Este flujo permite a un chatbot de LINE mantener una conversación contextualizada utilizando la memoria histórica almacenada en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2678-gmail-to-drive-pdfs.json](workflows/2678-gmail-to-drive-pdfs.json)**
  - **Descripción:** Este flujo automático envía attachments PDF específicos de un correo electrónico a Google Drive usando OpenAI para filtrar y subir solo aquellos que coinciden con un término determinado.
  - **Complejidad:** Baja (1 nodos)

- **[2688-data_extraction_bright_google.json](workflows/2688-data_extraction_bright_google.json)**
  - **Descripción:** Este flujo extrae y analiza datos estructurados de una página web utilizando Bright Data Web Unlocker y Google Gemini para realizar tareas de minería de datos, incluyendo análisis temático y extracción de sentimientos.
  - **Complejidad:** Baja (1 nodos)

- **[2706-airtable-csv-uploader.json](workflows/2706-airtable-csv-uploader.json)**
  - **Descripción:** Este flujo automático procesa y carga datos desde un archivo CSV a Airtable. Detecta si la campaña no está vacía, marca el estado de proceso, descarga el archivo, crea registros en Airtable y actualiza el estado a 'Uploaded' o 'Failed'.
  - **Complejidad:** Baja (1 nodos)

- **[2707-dropbox-backup-cleanup.json](workflows/2707-dropbox-backup-cleanup.json)**
  - **Descripción:** Este flujo automático programa tareas periódicas para Backup y limpieza de Workflows en Dropbox. Cada día, copia los Workflows actuales a una carpeta 'OLD' y elimina aquellos backups que superen los 30 días.
  - **Complejidad:** Baja (1 nodos)

- **[2767-file-organizer-mistral.json](workflows/2767-file-organizer-mistral.json)**
  - **Descripción:** Este flujo utiliza un desencadenador local para monitorear un directorio, utiliza comandos para obtener una lista de archivos y carpetas, luego emplea el modelo Mistral AI para organizar los archivos moviéndolos a subcarpetas apropiadas basándose en sugerencias del AI.
  - **Complejidad:** Baja (1 nodos)

- **[2780-gitlab-backup-n8n.json](workflows/2780-gitlab-backup-n8n.json)**
  - **Descripción:** Este flujo automático configura un backup periódico y manual de los workflows de n8n en GitLab. Utiliza triggers programados y manuales para guardar la configuración actualizada en archivos separados dentro de una repositorio gitlab.
  - **Complejidad:** Baja (1 nodos)

- **[2805-sincronizacion-stripe-s3.json](workflows/2805-sincronizacion-stripe-s3.json)**
  - **Descripción:** Este flujo automatiza la sincronización de facturas PDF desde Stripe hacia un.bucket de AWS S3 organizando los archivos en subcarpetas según el año y mes. Configura intervalos mensuales para descargar solo las facturas emitidas a partir del primer día del mes.
  - **Complejidad:** Baja (1 nodos)

- **[2827-redis_lock_workflow.json](workflows/2827-redis_lock_workflow.json)**
  - **Descripción:** Este flujo utiliza Redis para bloquear la ejecución de un workflow hasta que expire una clave TTL, evitando así la ejecución concurrente.
  - **Complejidad:** Baja (1 nodos)

- **[2832-gmail-to-drive-organizer.json](workflows/2832-gmail-to-drive-organizer.json)**
  - **Descripción:** Este flujo automatiza la descarga de archivos adjuntos de Gmail, los organiza en carpetas específicas en Google Drive según el correo electrónico receptor y fecha, creando las carpetas necesarias si no existen.
  - **Complejidad:** Baja (1 nodos)

- **[2841-export_google_keep_to_sheet.json](workflows/2841-export_google_keep_to_sheet.json)**
  - **Descripción:** Este flujo automatiza la exportación de notas desde Google Keep alinear con un sistema de procesamiento y almacenamiento en Google Sheets. Busca archivos JSON en una carpeta específica de Google Drive, filtra aquellos que no estén archivados y contengan palabras clave como 'dépensé' o 'depense', descarga los archivos seleccionados, extrae su contenido y utiliza OpenAI para tratar la información antes de insertarla en una hoja de cálculo.
  - **Complejidad:** Baja (1 nodos)

- **[2843-gdrive-audit.json](workflows/2843-gdrive-audit.json)**
  - **Descripción:** Este flujo automatiza la auditoría de permisos en Google Drive, identificando archivos compartidos públicamente o con usuarios externos y generando un informe diario que se envía por correo electrónico.
  - **Complejidad:** Baja (1 nodos)

- **[2851-job_scraping_openai.json](workflows/2851-job_scraping_openai.json)**
  - **Descripción:** Este flujo automatiza la búsqueda de ofertas laborales en Indeed usando Bright Data y OpenAI para evaluar si cada cargo es adecuado. Inicia con un formulario que recoge ubicación, palabra clave y país, luego envía una solicitud a Bright Data, espera a que se procese el.snapshot, extrae los datos, y finalmente utiliza OpenAI para determinar si eres un buen candidato.
  - **Complejidad:** Baja (1 nodos)

- **[2852-glassdoor-jobs-scraper.json](workflows/2852-glassdoor-jobs-scraper.json)**
  - **Descripción:** Este flujo utiliza Bright Data para extraer ofertas laborales de Glassdoor basadas en ubicación, palabra clave y país, espera a que estén listas, las guarda en Google Sheets y luego genera pitches personalizados usando un LLM.
  - **Complejidad:** Baja (1 nodos)

- **[2853-trustpilot-analysis.json](workflows/2853-trustpilot-analysis.json)**
  - **Descripción:** Este flujo automatiza la extracción y análisis de reseñas negativas de competidores en Trustpilot usando Bright Data. El usuario ingresa una URL de Trustpilot y selecciona un período, luego el workflow envía una solicitud a Bright Data, espera hasta que los datos estén listos, filtra las reseñas negativas (1 o 2 estrellas), agrupa los comentarios y utiliza OpenAI para generar texto persuasivo basado en esas quejas. Finalmente, envía un resumen por correo electrónico.
  - **Complejidad:** Baja (1 nodos)

- **[2856-amazon_reviews_analysis.json](workflows/2856-amazon_reviews_analysis.json)**
  - **Descripción:** Este flujo utiliza Bright Data para extraer y analizar opiniones de productos en Amazon. Configura un formulario para introducir URLs de productos, envía una solicitud HTTP para iniciar el análisis, espera a que se procese la información y luego almacena los datos en Google Sheets. Después, utiliza OpenAI para resumir las reseñas, genera imágenes creativas basadas en los resultados y envía estos creativos por correo electrónico.
  - **Complejidad:** Baja (1 nodos)

- **[2859-sqlite-mcp-server.json](workflows/2859-sqlite-mcp-server.json)**
  - **Descripción:** Flujo que implementa un servidor MCP de SQLite para realizar operaciones básicas en una base de datos local como lectura, inserción y actualización de registros, usando nodos personalizados para manejar las operaciones seguras.
  - **Complejidad:** Baja (1 nodos)

- **[2860-gdrive-mcp-server.json](workflows/2860-gdrive-mcp-server.json)**
  - **Descripción:** Este flujo configura un servidor MCP que interactúa con Google Drive para buscar y leer archivos, convirtiendo formatos binarios a texto. Utiliza OpenAI para analizar imágenes y transcribir audio.
  - **Complejidad:** Baja (1 nodos)

- **[2866-legis-sostenibilidad.json](workflows/2866-legis-sostenibilidad.json)**
  - **Descripción:** Este flujo automático extrae información de procedimientos legislativos relacionados con sostenibilidad de la página web del Parlamento Europeo, clasificando cada documento utilizando un agente de lenguaje OpenAI y almacenándolos en una hoja de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2871-image-processing.json](workflows/2871-image-processing.json)**
  - **Descripción:** Este flujo automático descarga imágenes de URLs, las analiza para crear un prompt de fotografía de producto y genera una nueva imagen con OpenAI antes de almacenarla en Google Drive y actualizar una tabla.
  - **Complejidad:** Baja (1 nodos)

- **[2873-google-drive-folder-creator.json](workflows/2873-google-drive-folder-creator.json)**
  - **Descripción:** Este flujo crea una estructura jerárquica en Google Drive a partir de un path dado y devuelve el ID del último folder creado.
  - **Complejidad:** Baja (1 nodos)

- **[2892-resto-order-processor.json](workflows/2892-resto-order-processor.json)**
  - **Descripción:** Flujo automatizado para procesar pedidos en restaurantes. Extrae información de los pedidos mediante un agente de chat y herramientas de IA, separa los items, cantidad y número de mesa, confirma la orden y registra en una hoja de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2909-workflow_management.json](workflows/2909-workflow_management.json)**
  - **Descripción:** Este flujo automático gestiona y sincroniza Workflows de n8n con Airtable y Dropbox. Recupera detalles de Workflows, prepara datos, maneja cron jobs y actualiza o agrega nuevos registros en Airtable.
  - **Complejidad:** Baja (1 nodos)

- **[2910-import_odoo_product_images.json](workflows/2910-import_odoo_product_images.json)**
  - **Descripción:** Este flujo importa imágenes de productos desde Google Drive a Odoo, filtrando y actualizando las mismas en base al modelo y SKU. Mantiene un sistema para mover archivos procesados y notificar el total descargado.
  - **Complejidad:** Baja (1 nodos)

- **[2914-openai-file-citation.json](workflows/2914-openai-file-citation.json)**
  - **Descripción:** Este flujo extrae y formatea citas de archivos almacenados en OpenAI a partir de un hilo de conversación, asegurando que las referencias se muestren correctamente con nombres de archivo.
  - **Complejidad:** Baja (1 nodos)

- **[2946-automate-content-generator-wordpress.json](workflows/2946-automate-content-generator-wordpress.json)**
  - **Descripción:** Este flujo automático genera contenido para WordPress usando DeepSeek R1, incluyendo artículos y títulos SEO-friendlys, crea imágenes con DALL-E, las sube y actualiza una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2979-multi_methods_airtable.json](workflows/2979-multi_methods_airtable.json)**
  - **Descripción:** Este flujo maneja diferentes métodos HTTP para interactuar con una API de Airtable, realizando operaciones como crear, obtener todo, obtener un registro por ID, actualizar y eliminar registros.
  - **Complejidad:** Baja (1 nodos)

- **[3015-automated-resume-review-system.json](workflows/3015-automated-resume-review-system.json)**
  - **Descripción:** Este flujo automático permite analizar y evaluar currículos de manera automatizada utilizando OpenAI y Google Sheets. Incluye la subida al Drive, extracción de información, resumen profesional y almacenamiento en hojas de cálculo.
  - **Complejidad:** Baja (1 nodos)

- **[3018-webflow-airtable-tables-creator.json](workflows/3018-webflow-airtable-tables-creator.json)**
  - **Descripción:** Este flujo crea tablas dinámicas en Airtable para las submisiones de formularios de Webflow. Automatiza la creación de tableros y registros basados en los formulario, usando credenciales de API y manejando errores.
  - **Complejidad:** Baja (1 nodos)

- **[3019-export_zammad_to_excel.json](workflows/3019-export_zammad_to_excel.json)**
  - **Descripción:** Este flujo exporta objetos de Zammad como Usuarios, Roles, Grupos y Organizaciones a archivos Excel.
  - **Complejidad:** Baja (1 nodos)

- **[3036-procesador-imagenes-ollama.json](workflows/3036-procesador-imagenes-ollama.json)**
  - **Descripción:** Este flujo automatiza el análisis detallado de imágenes utilizando modelos visuales locales de Ollama. Descarga una imagen desde Google Drive, la procesa con múltiples modelos (como granita3.2-vision y llama3.2-vision), genera descripciones exhaustivas en markdown y las guarda en Google Docs.
  - **Complejidad:** Baja (1 nodos)

- **[3040-enra_zammad_sync.json](workflows/3040-enra_zammad_sync.json)**
  - **Descripción:** Este flujo sincroniza usuarios de Entra con Zammad. Recupera grupos y miembros de Entra, crea objetos de usuario universales, compara datos para actualizar o desactivar usuarios en Zammad.
  - **Complejidad:** Baja (1 nodos)

- **[3059-openai-file-retrieval-rg.json](workflows/3059-openai-file-retrieval-rg.json)**
  - **Descripción:** Este flujo utiliza OpenAI para recuperar y citar contenido de archivos almacenados en un vector store, formateando la salida con Markdown o HTML.
  - **Complejidad:** Baja (1 nodos)

- **[3093-bright_data_extractor.json](workflows/3093-bright_data_extractor.json)**
  - **Descripción:** Este flujo utiliza Bright Data Web Scraper para extraer datos estructurados en masa. Inicia una captura, espera a que esté lista y luego descarga los datos. Maneja errores y notifica por webhook.
  - **Complejidad:** Baja (1 nodos)

- **[3095-remove-background-google-drive.json](workflows/3095-remove-background-google-drive.json)**
  - **Descripción:** Este flujo elimina el fondo de las imágenes almacenadas en Google Drive utilizando la API de Photoroom, añadiendo un color de fondo configurable y guardando las nuevas imágenes en una ubicación específica.
  - **Complejidad:** Baja (1 nodos)

- **[3102-organizar-archivos-con-AI.json](workflows/3102-organizar-archivos-con-AI.json)**
  - **Descripción:** Este flujo automatiza la organización de archivos en directorios locales utilizando IA. Monitorea un folder específico, lista los archivos y carpetas, utiliza Mistral AI para clasificar los archivos sugiriendo subdirectorios existentes o nuevos, y luego mueve los archivos según las indicaciones de la IA.
  - **Complejidad:** Baja (1 nodos)

- **[3106-automate-content-generator-wordpress.json](workflows/3106-automate-content-generator-wordpress.json)**
  - **Descripción:** Este flujo automatiza la creación de contenido para WordPress utilizando DeepSeek. Genera artículos, títulos y imágenes basadas en ideas proporcionadas en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3125-linkedin-stories-generator.json](workflows/3125-linkedin-stories-generator.json)**
  - **Descripción:** Este flujo extrae información de LinkedIn usando la API de Bright Data y genera historias empresariales con Google Gemini. Incluye el procesamiento de datos, extracción de información y resumen mediante LLM.
  - **Complejidad:** Baja (1 nodos)

- **[3130-extract-google-maps.json](workflows/3130-extract-google-maps.json)**
  - **Descripción:** Este flujo utiliza Google Maps y herramientas de scrappeo para extraer datos empresariales como nombre, dirección, teléfono, correo electrónico y website. Utiliza OpenAI para procesar las peticiones yGuardar en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3144-chatbot_companyIdocs.json](workflows/3144-chatbot_companyIdocs.json)**
  - **Descripción:** Este flujo automatiza la creación de un chatbot que utiliza documentos de la empresa almacenados en Google Drive y Gemini para responder preguntas.
  - **Complejidad:** Baja (1 nodos)

- **[3145-rag_context_chunking.json](workflows/3145-rag_context_chunking.json)**
  - **Descripción:** Este flujo automatiza la creación de vectores contextuales a partir de documentos en Google Drive usando RAG (Retrieval-Augmented Generation) con división en secciones y almacenamiento en Pinecone.
  - **Complejidad:** Baja (1 nodos)

- **[3146-reconcile-rent-payments.json](workflows/3146-reconcile-rent-payments.json)**
  - **Descripción:** Este flujo automatiza la reconciliación de pagos de alquileres utilizando un modelo OpenAI para detectar y flaggear discrepancias en los pagos contra una base de datos local en Excel. Identifica misses, pagos incorrectos, vencimientos y alerta acciones necesarias.
  - **Complejidad:** Baja (1 nodos)

- **[3154-dynamic_form_dropdown.json](workflows/3154-dynamic_form_dropdown.json)**
  - **Descripción:** Este flujo configura un formulario con un campo desplegable dinámico que se actualiza con valores obtenidos de una fuente de datos externa, como una hoja de cálculo de Google Sheets. La estructura incluye nodos para capturar la submisión del formulario, recuperar los datos de la fuente, transformarlos y actualizar el formulario con las nuevas opciones.
  - **Complejidad:** Baja (1 nodos)

- **[3163-gmail-to-drive-pdfs.json](workflows/3163-gmail-to-drive-pdfs.json)**
  - **Descripción:** Este flujo automatiza la transferencia de archivos PDF específicos desde Gmail a Google Drive usando OpenAI para filtrar y subir solo aquellos que coinciden con un término determinado.
  - **Complejidad:** Baja (1 nodos)

- **[3173-social-banner-generator.json](workflows/3173-social-banner-generator.json)**
  - **Descripción:** Este flujo automatiza la creación de banners sociales usando n8n Forms para capturar datos del evento, OpenAI para generar imágenes y BannerBear para crear el banner final.
  - **Complejidad:** Baja (1 nodos)

- **[3207-waitlist-verification.json](workflows/3207-waitlist-verification.json)**
  - **Descripción:** Flujo para manejar una lista de espera que incluye registro de usuarios, generación de código de verificación, envío de correo electrónico y validación. Si el código es incorrecto, se le pide al usuario reintentar. Una vez validado, se guarda en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3208-sql-agent-chart-generator.json](workflows/3208-sql-agent-chart-generator.json)**
  - **Descripción:** Este flujo utiliza un agente de SQL y OpenAI para generar respuestas con visualizaciones en tiempo real. El usuario puede hacer preguntas sobre los datos y el sistema determinará si incluir una gráfica usando Chart.js, accionando un subflujo para crear una imagen compatible con Quickchart.io.
  - **Complejidad:** Baja (1 nodos)

- **[3211-blueSky-welcome-bot.json](workflows/3211-blueSky-welcome-bot.json)**
  - **Descripción:** Este flujo programa un mensaje de bienvenida automático a nuevos seguidores en BlueSky. Primero inicia sesión, luego lista los seguidores y compara con una base de datos guardada para detectar新人. Los nuevos seguidores reciben un mensaje privado con un texto definido. Se actualiza la lista de seguidores en un archivo JSON.
  - **Complejidad:** Baja (1 nodos)

- **[3223-search-console-report.json](workflows/3223-search-console-report.json)**
  - **Descripción:** Este flujo extrae datos de Search Console mediante tres reportes diferentes (palabras clave, páginas y fechas) usando la API de Google. Los datos se procesan para separarlos y luego actualizar una hoja de cálculo de Google con información detallada sobre clics, impresiones, CTR y posiciones.
  - **Complejidad:** Baja (1 nodos)

- **[3227-calendly-klicktipp-sync.json](workflows/3227-calendly-klicktipp-sync.json)**
  - **Descripción:** Este flujo automático sincroniza eventos de Calendly con KlickTipp, manejando reservas y.Cancelaciones, transformando datos para asegurar que los invitados sean agregados o eliminados correctamente en la lista de subscriptores.
  - **Complejidad:** Baja (1 nodos)

- **[3231-transcription-ai-flow.json](workflows/3231-transcription-ai-flow.json)**
  - **Descripción:** Este flujo automatiza la transcripción en tiempo real de reuniones, estructura los datos y genera resúmenes usando OpenAI y bases de datos PostgreSQL.
  - **Complejidad:** Baja (1 nodos)

- **[3234-invoice-parser-flow.json](workflows/3234-invoice-parser-flow.json)**
  - **Descripción:** Este flujo automático detecta nuevos archivos en Google Drive, los envía a LlamaParse para análisis y extrae información de facturas. Los datos procesados se almacenan en Airtable como registros de invoices y sus respectivos ítems detallados.
  - **Complejidad:** Baja (1 nodos)

- **[3241-ai-meeting-automator.json](workflows/3241-ai-meeting-automator.json)**
  - **Descripción:** Este flujo automático utiliza un agente de inteligencia artificial para procesar transcripciones de reuniones, extraer tareas y notificar al cliente. Para ello, utiliza Airtable para crear tareas y Google Calendar para programar citas.
  - **Complejidad:** Baja (1 nodos)

- **[3245-csvToJsonParser.json](workflows/3245-csvToJsonParser.json)**
  - **Descripción:** Este flujo procesa una solicitud POST con datos en formato CSV o JSON. Primero, verifica el tipo de contenido y extrae los datos utilizando ExtractFromFile. Luego, convierte los datos_RAW a CSV si es necesario. Si hay errores, devuelve un código 500 con un mensaje de error. Si la conversión es exitosa, agrega los datos al cuerpo JSON y responde con un código 200.
  - **Complejidad:** Baja (1 nodos)

- **[3267-certificado-automatico.json](workflows/3267-certificado-automatico.json)**
  - **Descripción:** Este flujo automatiza la generación y envío de certificados basados en un cuestionario de Google Forms. Recoge datos de las respuestas, verifica la puntuación, crea una presentación personalizada con el nombre del usuario, convierte la presentación a PDF y envía un correo electrónico con el certificado al usuario si supera la calificación.
  - **Complejidad:** Baja (1 nodos)

- **[3318-extract_text_from_pdf_image_to_csv.json](workflows/3318-extract_text_from_pdf_image_to_csv.json)**
  - **Descripción:** Este flujo automático extrae texto de archivos PDF y imágenes usando Vertex AI (Gemini) y los convierte en CSV para su almacenamiento en Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[3319-umami-ai-analytics.json](workflows/3319-umami-ai-analytics.json)**
  - **Descripción:** Este flujo extrae datos de analítica web de Umami, procesa y envía información a un modelo de IA para obtener resúmenes y comparativas semanales, guardando los resultados en Baserow.
  - **Complejidad:** Baja (1 nodos)

- **[3325-split-test-ab.json](workflows/3325-split-test-ab.json)**
  - **Descripción:** Este flujo implementa un test de división A/B para evaluar diferentes mensajes en un chatbot. Al recibir un mensaje, verifica si la sesión existe y asigna aleatoriamente un.prompt entre dos opciones guardadas en Supabase, luego utiliza el agente AI con el prompt seleccionado.
  - **Complejidad:** Baja (1 nodos)

- **[3343-Indeed_Data_Scraper_Gemini.json](workflows/3343-Indeed_Data_Scraper_Gemini.json)**
  - **Descripción:** Este flujo extrae y resume datos de compañías de Indeed usando Bright Data y Google Gemini. Utiliza Airtable para almacenar los enlaces y procesa la información con agentes y cadenas de pensamiento AI.
  - **Complejidad:** Baja (1 nodos)

- **[0008-notion_linkedin_pub.json](workflows/0008-notion_linkedin_pub.json)**
  - **Descripción:** Este flujo automático publica cada día en LinkedIn un post seleccionado desde una base de datos de Notion, basándose en la fecha y hora programadas.
  - **Complejidad:** Baja (1 nodos)

- **[0087-github-backup-flujos.json](workflows/0087-github-backup-flujos.json)**
  - **Descripción:** Este flujo automático ejecuta trabajos todos los días a las 23:59 y guarda el contenido editado en archivos JSON en un repositorio de GitHub.
  - **Complejidad:** Baja (1 nodos)

- **[0093-pokemon-rate-limiter.json](workflows/0093-pokemon-rate-limiter.json)**
  - **Descripción:** Este flujo verifica límites de uso por minuto y hora mediante Redis, consulta datos de Airtable sobre Pokémon y utiliza webhooks para procesar respuestas.
  - **Complejidad:** Baja (1 nodos)

- **[0201-users-data-flow.json](workflows/0201-users-data-flow.json)**
  - **Descripción:** Este flujo obtiene datos aleatorios de usuarios de la API de randomuser.me, los procesa y almacena en una hoja de Google. También crea un archivo CSV con esos datos y prepara un correo electrónico para adjuntar el JSON.
  - **Complejidad:** Baja (1 nodos)

- **[0206-n8n_paginacion_ejemplo.json](workflows/0206-n8n_paginacion_ejemplo.json)**
  - **Descripción:** Este flujo automático utiliza nodos HTTP para obtener datos de manera estructurada (como listas de álbumes o páginas web) y manejar respuestas mediante la creación de elementos.
  - **Complejidad:** Baja (1 nodos)

- **[0207-workflow-automatico-mensajes-clientes.json](workflows/0207-workflow-automatico-mensajes-clientes.json)**
  - **Descripción:** Este flujo automático envía mensajes personalizados a cada cliente obtenido desde un almacenamiento de datos, esperando brevemente entre cada mensaje para evitar exceder límites de solicitud y luego les proporciona una URL específica para su interacción.
  - **Complejidad:** Baja (1 nodos)

- **[0218-asana-notion-sync.json](workflows/0218-asana-notion-sync.json)**
  - **Descripción:** Este flujo n8n sincroniza tareas entre Asana y Notion mediante webhooks, creando o actualizando entradas en la base de datos de Notion según los cambios detectados en las tareas de Asana.
  - **Complejidad:** Baja (1 nodos)

- **[0239-github-issue-notion-sync.json](workflows/0239-github-issue-notion-sync.json)**
  - **Descripción:** Este flujo sincroniza eventos de GitHub Issues con acciones en una base de datos de Notion, permitiendo la actualización automática de propiedades como título y estado.
  - **Complejidad:** Baja (1 nodos)

- **[0257-analisis-domini.json](workflows/0257-analisis-domini.json)**
  - **Descripción:** Este flujo automatizado toma una lista de dominios web (dividida en lotes), consulta su contenido mediante solicitudes HTTP, pide a OpenAI que analice el texto para obtener propiedades clave sobre valor proposicional, audiencia y sector, y luego guarda estos datos clasificados en un hoja de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[0277-products-to-xml.json](workflows/0277-products-to-xml.json)**
  - **Descripción:** Este flujo consulta aleatoriamente 16 productos de una base de datos MySQL y los transforma en dos archivos XML diferentes, manteniendo la estructura con etiquetas mediante funciones set.
  - **Complejidad:** Baja (1 nodos)

- **[0285-bitcoin-chat-flow-pinecone.json](workflows/0285-bitcoin-chat-flow-pinecone.json)**
  - **Descripción:** Este flujo permite cargar datos del Bitcoin White Paper desde Google Drive en Pinecone usando embeddings de GPT-4o-mini y responder preguntas mediante herramientas vectoriales.
  - **Complejidad:** Baja (1 nodos)

- **[0372-xml-to-json-converter.json](workflows/0372-xml-to-json-converter.json)**
  - **Descripción:** Este flujo permite convertir archivos XML a JSON, tiene múltiples conexiones y maneja errores con respuestas HTTP personalizadas.
  - **Complejidad:** Baja (1 nodos)

- **[0399-workflow-credentials-agent.json](workflows/0399-workflow-credentials-agent.json)**
  - **Descripción:** Este flujo permite almacenar configuraciones de n8n en una base de datos SQLite y consultarlas mediante un agente conversacional.
  - **Complejidad:** Baja (1 nodos)

- **[0413-analisis-multimodal-cv.json](workflows/0413-analisis-multimodal-cv.json)**
  - **Descripción:** Este flujo analiza currículums en PDF utilizando modelos visuales para detectar 'bypass' con prompts ocultos, evitando así que los candidatos intenten engañar al sistema.
  - **Complejidad:** Baja (1 nodos)

- **[0419-google-ads-keyword-data.json](workflows/0419-google-ads-keyword-data.json)**
  - **Descripción:** Este flujo de trabajo utiliza la API de Google Ads para obtener datos históricos y volúmenes de búsqueda de hasta 20 palabras clave.
  - **Complejidad:** Baja (1 nodos)

- **[0435-openai-supabase-sql-chat.json](workflows/0435-openai-supabase-sql-chat.json)**
  - **Descripción:** Este flujo permite a un usuario interactuar conversacionalmente con una base de datos PostgreSQL en Supabase mediante el uso de funciones de OpenAI para ejecutar consultas y generar respuestas.
  - **Complejidad:** Baja (1 nodos)

- **[0444-google-drive-pii-detector.json](workflows/0444-google-drive-pii-detector.json)**
  - **Descripción:** Este flujo automático detecta la creación de nuevos archivos CSV en Google Drive, identifica columnas que contienen datos personales (PII) mediante OpenAI, elimina esas columnas y vuelve a subir el archivo procesado.
  - **Complejidad:** Baja (1 nodos)

- **[0451-backups-workflow-google.json](workflows/0451-backups-workflow-google.json)**
  - **Descripción:** Este flujo automático ejecuta backups periódicos de workflows en Google Drive cada 4 horas y elimina los archivos originales para mantener el almacenamiento optimizado.
  - **Complejidad:** Baja (1 nodos)

- **[0458-google-drive-batch-upload.json](workflows/0458-google-drive-batch-upload.json)**
  - **Descripción:** Este flujo automático permite subir múltiples archivos a Google Drive de forma organizada mediante un formulario que verifica y crea automáticamente la carpeta destino.
  - **Complejidad:** Baja (1 nodos)

- **[0481-shopify-orders-sync.json](workflows/0481-shopify-orders-sync.json)**
  - **Descripción:** Este flujo automático obtiene pedidos de Shopify mediante API y los almacena en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[0482-invitaciones-google-sheets-n8n.json](workflows/0482-invitaciones-google-sheets-n8n.json)**
  - **Descripción:** Este flujo automatizado compara usuarios en n8n con datos de una hoja de Google Sheets para enviar invitaciones a los que no existen en la plataforma.
  - **Complejidad:** Baja (1 nodos)

- **[0491-ai-chat-agent-memory.json](workflows/0491-ai-chat-agent-memory.json)**
  - **Descripción:** Este flujo utiliza un agente de IA con memoria para mantener el contexto durante la interacción y realizar consultas a BigQuery sobre datos de envíos.
  - **Complejidad:** Baja (1 nodos)

- **[0511-outlook-jira-ai-tickets.json](workflows/0511-outlook-jira-ai-tickets.json)**
  - **Descripción:** Este flujo automático monitoriza el correo electrónico en la bandeja de Outlook para tickets de soporte, los clasifica y prioriza con inteligencia artificial, luego crea un ticket en Jira utilizando esos datos estructurados. Las notas adhesivas proporcionan instrucciones y contexto sobre cómo funciona el flujo.
  - **Complejidad:** Baja (1 nodos)

- **[0512-web-scraper-structured.json](workflows/0512-web-scraper-structured.json)**
  - **Descripción:** Este flujo automático permite extraer información estructurada sobre productos web (nombre, descripción, precio, valoración y número de reseñas) a partir de páginas HTML limpiadas. Utiliza Google Sheets para obtener listas de URLs a procesar, limpia el contenido con un script Node.js antes de enviarlo al modelo GPT-4 via OpenRouter, y finalmente anexa los resultados estructurados en JSON a otra hoja del documento.
  - **Complejidad:** Baja (1 nodos)

- **[0519-clockify-syncro-timer-sync.json](workflows/0519-clockify-syncro-timer-sync.json)**
  - **Descripción:** Este flujo sincroniza entradas de tiempo entre Clockify y Syncro mediante Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[0681-notion-ai-blog-update.json](workflows/0681-notion-ai-blog-update.json)**
  - **Descripción:** Este flujo automático reacciona a actualizaciones en una base de datos de Notion usando DeepSeek para crear artículos SEO y publicarlos tanto en WordPress como actualizar el registro original.
  - **Complejidad:** Baja (1 nodos)

- **[0770-google-drive-video-upload.json](workflows/0770-google-drive-video-upload.json)**
  - **Descripción:** Este flujo automático permite cargar videos en Google Drive y, de forma inmediata, los subirá a Instagram, TikTok e YouTube con un título o descripción generado por la IA (OpenAI). El proceso incluye descargar el video desde Google Drive, extraer su audio para análisis con OpenAI y finalmente realizar las peticiones HTTP necesarias para publicar en las tres plataformas de redes sociales.
  - **Complejidad:** Baja (1 nodos)

- **[0799-supabase-chat-ai.json](workflows/0799-supabase-chat-ai.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar de forma conversacional con una base de datos PostgreSQL alojada en Supabase, ejecutando consultas SQL basadas en solicitudes del usuario.
  - **Complejidad:** Baja (1 nodos)

- **[0801-ai-agent-weather-wiki.json](workflows/0801-ai-agent-weather-wiki.json)**
  - **Descripción:** Este flujo automatizado permite a un chatbot de IA responder preguntas sobre el clima actual y datos generales utilizando herramientas de Wikipedia, almacenando la conversación en memoria para mantener contexto.
  - **Complejidad:** Baja (1 nodos)

- **[0802-google-calendar-ai-agent.json](workflows/0802-google-calendar-ai-agent.json)**
  - **Descripción:** Este flujo automático permite a un asistente de Google Calendar interactuar con los usuarios mediante chat para crear eventos o recuperar datos, utilizando la API de OpenAI y manteniendo el contexto conversacional.
  - **Complejidad:** Baja (1 nodos)

- **[0804-ai-agent-hacker-news.json](workflows/0804-ai-agent-hacker-news.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de IA mantener una conversación contextualizada mediante herramientas personalizadas. En este caso específico, el agente utiliza un workflow para obtener y procesar datos sobre los artículos más populares en Hacker News.
  - **Complejidad:** Baja (1 nodos)

- **[0810-strava-coaching.json](workflows/0810-strava-coaching.json)**
  - **Descripción:** Este flujo analiza datos de Strava para ofrecer coaching deportivo personalizado en triatlón.
  - **Complejidad:** Baja (1 nodos)

- **[0812-social_media_caption_generator.json](workflows/0812-social_media_caption_generator.json)**
  - **Descripción:** Este flujo automático crea títulos para redes sociales en función de una breve presentación y datos sobre el público objetivo, almacenando todo directamente en un registro de Airtable.
  - **Complejidad:** Baja (1 nodos)

- **[0816-youtube-trend-finder-n8n.json](workflows/0816-youtube-trend-finder-n8n.json)**
  - **Descripción:** Este flujo automático utiliza la IA para analizar datos de videos tendenciales de YouTube en función de un nicho específico.
  - **Complejidad:** Baja (1 nodos)

- **[0830-assistant-travel-agency.json](workflows/0830-assistant-travel-agency.json)**
  - **Descripción:** Este flujo automatizado permite crear un asistente de OpenAI a partir del contenido de documentos almacenados en Google Drive y mantener una conversación contextualizada para la agencia de viajes.
  - **Complejidad:** Baja (1 nodos)

- **[0875-assistente_viajes_actualizado.json](workflows/0875-assistente_viajes_actualizado.json)**
  - **Descripción:** Este flujo automático permite crear un asistente de OpenAI a partir de un documento PDF almacenado en Google Drive, manteniendo una conversación contextualizada mediante memoria buffer y permitiendo su interacción vía chat.
  - **Complejidad:** Baja (1 nodos)

- **[0889-openai-chatbot-memory-api.json](workflows/0889-openai-chatbot-memory-api.json)**
  - **Descripción:** Este flujo permite a un chatbot de OpenAI mantener conversaciones con memoria persistente en PostgreSQL y acceder a información externa mediante APIs.
  - **Complejidad:** Baja (1 nodos)

- **[0896-postgres-chat-ai.json](workflows/0896-postgres-chat-ai.json)**
  - **Descripción:** Este flujo permite a un chatbot de IA interactuar con una base de datos PostgreSQL mediante herramientas para ejecutar consultas SQL y mantener contexto.
  - **Complejidad:** Baja (1 nodos)

- **[0899-yelp-summary.json](workflows/0899-yelp-summary.json)**
  - **Descripción:** Este flujo automático permite extraer y resumir reseñas de negocios en Yelp usando los servicios web de Bright Data para la recopilación de datos, seguido de análisis estructurado con Google Gemini.
  - **Complejidad:** Baja (1 nodos)

- **[0924-cv-multimodal-ai.json](workflows/0924-cv-multimodal-ai.json)**
  - **Descripción:** Este flujo de trabajo utiliza visión multimodal con AI para analizar currículums PDF y evaluar si los candidatos son aptos para una entrevista.
  - **Complejidad:** Baja (1 nodos)

- **[0942-pdf2blog-automatizado.json](workflows/0942-pdf2blog-automatizado.json)**
  - **Descripción:** Este flujo automático permite convertir archivos PDF en blogs mediante la extracción de texto, procesamiento con una API de OpenAI y publicación en Ghost si los resultados son válidos.
  - **Complejidad:** Baja (1 nodos)

- **[0947-trustpilot_reviews_google_sheets.json](workflows/0947-trustpilot_reviews_google_sheets.json)**
  - **Descripción:** Este flujo n8n automatiza la extracción de reseñas de Trustpilot a Google Sheets mediante scraping paginado y transformación de datos.
  - **Complejidad:** Baja (1 nodos)

- **[0948-glassdoor-resume-empresa.json](workflows/0948-glassdoor-resume-empresa.json)**
  - **Descripción:** Este flujo automatiza la extracción de datos sobre una empresa en Glassdoor usando Bright Data Web Scraper, los divide para su procesamiento con Gemini y genera un resumen.
  - **Complejidad:** Baja (1 nodos)

- **[0951-book-scraping-automation.json](workflows/0951-book-scraping-automation.json)**
  - **Descripción:** Este flujo automatizado extrae datos de libros desde URLs utilizando Dumpling AI, limpia el HTML y guarda la información en un CSV.
  - **Complejidad:** Baja (1 nodos)

- **[0952-facturas-ocr-google-drive.json](workflows/0952-facturas-ocr-google-drive.json)**
  - **Descripción:** Este flujo automático permite reconocer automáticamente facturas e invoices almacenadas en una carpeta de Google Drive (formatos PDF, PNG o JPG) usando la API OakPDF. El workflow se activa cuando hay archivos nuevos y extrae datos clave como el nombre del emisor, dirección, total pagado y detalles específicos para guardarlos estructurados en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[0977-postgresql-chat-automaton.json](workflows/0977-postgresql-chat-automaton.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con una base de datos PostgreSQL, generando respuestas basadas en consultas SQL que analizan los datos solicitados.
  - **Complejidad:** Baja (1 nodos)

- **[0982-comparativa-ia-pdf.json](workflows/0982-comparativa-ia-pdf.json)**
  - **Descripción:** Este flujo automatiza la extracción de datos directamente desde archivos PDF utilizando modelos de IA como Claude o Gemini para una comparación eficiente.
  - **Complejidad:** Baja (1 nodos)

- **[1002-flux-dev-image-generation.json](workflows/1002-flux-dev-image-generation.json)**
  - **Descripción:** Este flujo automático genera una imagen usando la API de Fal.ai con parámetros predefinidos y la descarga para almacenarla automáticamente en Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[1004-imagen-optimizada-gdrive.json](workflows/1004-imagen-optimizada-gdrive.json)**
  - **Descripción:** Este flujo automático optimiza imágenes subidas a una carpeta de Google Drive y las reenvía al mismo servicio.
  - **Complejidad:** Baja (1 nodos)

- **[1009-huggingface-notion-ai-database.json](workflows/1009-huggingface-notion-ai-database.json)**
  - **Descripción:** Este flujo automático ejecuta una consulta diaria a la API de Hugging Face cada semana para obtener datos sobre publicaciones relacionadas con inteligencia artificial y los almacena en un formato estructurado como base de datos en Notion.
  - **Complejidad:** Baja (1 nodos)

- **[1016-bright-data-serp-extractor.json](workflows/1016-bright-data-serp-extractor.json)**
  - **Descripción:** Este flujo utiliza la API de Bright Data para extraer datos de páginas de resultados de búsqueda (SERP) en Google y los procesa con cadenas de modelos LLM como Gemini Flash Exp para generar una respuesta estructurada.
  - **Complejidad:** Baja (1 nodos)

- **[1025-chatbot-extraccion-datos-personales.json](workflows/1025-chatbot-extraccion-datos-personales.json)**
  - **Descripción:** Este flujo automático analiza mensajes de chat para extraer datos personales (nombre, apellido, tipo de comunicación) y contactos en formato JSON.
  - **Complejidad:** Baja (1 nodos)

- **[1039-amazon-keywords-automation.json](workflows/1039-amazon-keywords-automation.json)**
  - **Descripción:** Este flujo automático obtiene sugerencias de palabras clave desde la API Completion de Amazon basadas en una entrada por webhook, limpia los datos y luego los almacena en Airtable.
  - **Complejidad:** Baja (1 nodos)

- **[1041-google-drive-rag-automation.json](workflows/1041-google-drive-rag-automation.json)**
  - **Descripción:** Este flujo automático permite descargar documentos de Google Drive, extraer y normalizar su texto, generar embeddings con Gemini, insertarlos en un índice Pinecone para búsqueda semántica, y cuando se recibe un mensaje por chat, recuperar información relevante del vector store.
  - **Complejidad:** Baja (1 nodos)

- **[1052-monday-com-column-split.json](workflows/1052-monday-com-column-split.json)**
  - **Descripción:** Este flujo procesa datos de columnas específicas en una tarjeta de Monday.com y las divide para manejar subelementos por separado.
  - **Complejidad:** Baja (1 nodos)

- **[1065-assistant-creator.json](workflows/1065-assistant-creator.json)**
  - **Descripción:** Este flujo automático permite descargar documentos de Google Drive y crear un asistente OpenAI con esas fichas, seguido de una conversación con el asistente.
  - **Complejidad:** Baja (1 nodos)

- **[1073-namesilo-domain-checker.json](workflows/1073-namesilo-domain-checker.json)**
  - **Descripción:** Este flujo automático verifica la disponibilidad de múltiples dominios a través de la API de Namesilo y exporta los resultados en formato Excel.
  - **Complejidad:** Baja (1 nodos)

- **[1078-matomo-seo-ai-report.json](workflows/1078-matomo-seo-ai-report.json)**
  - **Descripción:** Este flujo automático analiza datos de visitantes recurrentes (más de 3 visitas) en Matomo mediante integración con LLaMA-3 y guarda los resultados en Baserow para análisis SEO.
  - **Complejidad:** Baja (1 nodos)

- **[1082-serp-bear-ai-analysis.json](workflows/1082-serp-bear-ai-analysis.json)**
  - **Descripción:** Este flujo automático analiza los datos de rango de palabras clave de SERP Bear utilizando una inteligencia artificial, y guarda el análisis en Baserow.
  - **Complejidad:** Baja (1 nodos)

- **[1099-notion-page-archiver.json](workflows/1099-notion-page-archiver.json)**
  - **Descripción:** Este flujo automático busca y arhiva automáticamente las páginas vacías de una base de datos en Notion.
  - **Complejidad:** Baja (1 nodos)

- **[1106-openlibrary-recommendation.json](workflows/1106-openlibrary-recommendation.json)**
  - **Descripción:** Este flujo automático busca y recomienda un libro al azar de Open Library basado en el tema 'juvenile_literature' cada día viernes a las 11:00 AM o mediante ejecución manual, utilizando HTTP requests para obtener datos y enviar correos electrónicos con recomendaciones.
  - **Complejidad:** Baja (1 nodos)

- **[1126-xml-to-sheets.json](workflows/1126-xml-to-sheets.json)**
  - **Descripción:** Este flujo automatizado descarga un archivo XML de ejemplo, lo parsea para extraer elementos y crear un nuevo archivo en Google Sheets con las columnas definidas a partir del contenido.
  - **Complejidad:** Baja (1 nodos)

- **[1159-webinar-registration-klicktipp.json](workflows/1159-webinar-registration-klicktipp.json)**
  - **Descripción:** Este flujo automatiza la integración de registros webinars desde JotForm con KlickTipp. Valida y transforma datos como nombres, fechas, experiencias laborales y URLs para crear suscriptores en KlickTipp y aplicar etiquetas dinámicas basadas en las respuestas del formulario.
  - **Complejidad:** Baja (1 nodos)

- **[1167-stripe-quickbooks-integration.json](workflows/1167-stripe-quickbooks-integration.json)**
  - **Descripción:** Este blueprint implementa un flujo automatizado que integra n8n con Stripe y QuickBooks Online. Cuando se recibe una notificación de webhook 'payment_intent.succeeded' (éxito en el pago), busca si el cliente asociado ya existe en QuickBooks mediante una consulta HTTP a la API de QuickBooks. Si no existe, crea un nuevo cliente en QuickBooks usando los datos del pago y de Stripe, y luego crea un registro de venta (sales receipt) con esos detalles. El flujo utiliza n8n para manejar el workflow.
  - **Complejidad:** Baja (1 nodos)

- **[1168-linkedin-enrichment.json](workflows/1168-linkedin-enrichment.json)**
  - **Descripción:** Este flujo automático lee URLs de LinkedIn desde Google Sheets, las codifica y filtra para verificar si ya están enriquecidas. Luego llama a la API de RapidAPI (Fresh LinkedIn Profile Data) para obtener datos completos sobre los perfiles y finalmente actualiza un archivo CSV con esta información detallada.
  - **Complejidad:** Baja (1 nodos)

- **[1198-notion-duplicates-removal.json](workflows/1198-notion-duplicates-removal.json)**
  - **Descripción:** Este flujo elimina automáticamente duplicados de páginas en una base de datos Notion.
  - **Complejidad:** Baja (1 nodos)

- **[1199-google-drive-doc-summarizer.json](workflows/1199-google-drive-doc-summarizer.json)**
  - **Descripción:** Este flujo automático identifica el documento de Google Drive más recientemente creado, extrae su contenido y lo resume utilizando inteligencia artificial antes de almacenarlo en una hoja de cálculo.
  - **Complejidad:** Baja (1 nodos)

- **[1210-fal-ai-image-generation.json](workflows/1210-fal-ai-image-generation.json)**
  - **Descripción:** Este flujo automático permite generar imágenes mediante la API de Fal.ai, descargarlas y guardarlas en una carpeta específica de Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[1216-github-multiple-file-push.json](workflows/1216-github-multiple-file-push.json)**
  - **Descripción:** Este flujo permite subir múltiples archivos a un repositorio de GitHub mediante suscripciones, utilizando el token y la información proporcionada para autenticación e interacción con la API.
  - **Complejidad:** Baja (1 nodos)

- **[1227-tracker-gastos-ia-descripcion.json](workflows/1227-tracker-gastos-ia-descripcion.json)**
  - **Descripción:** Este flujo permite a un agente de IA procesar mensajes sobre gastos, convertirlos en datos estructurados JSON y guardarlos automáticamente en una hoja de Google. Incluye memoria para mantener conversaciones contextuales.
  - **Complejidad:** Baja (1 nodos)

- **[1231-feedback-resumen.json](workflows/1231-feedback-resumen.json)**
  - **Descripción:** Este workflow automatizado analiza respuestas de encuestas Google Form mediante Google Sheets y OpenAI GPT-4 para generar un resumen estructurado que incluye una visión general del sentimiento sobre un evento, junto con ideas para mejorar.
  - **Complejidad:** Baja (1 nodos)

- **[1252-ausencias_procesamiento.json](workflows/1252-ausencias_procesamiento.json)**
  - **Descripción:** Este flujo automático recopila y procesa los datos de ausencias (vacaciones y enfermedades) de los últimos meses desde Google Calendar. Utiliza expresiones regulares para filtrar eventos relacionados con vacaciones o enfermedades, calcula las horas de cada evento y genera un informe detallado que se envía por correo electrónico a la dirección payroll-team@mydomain.tld.
  - **Complejidad:** Baja (1 nodos)

- **[1463-extract-and-process-information-directly-pdf.json](workflows/1463-extract-and-process-information-directly-pdf.json)**
  - **Descripción:** Este flujo permite extracción de datos, generación de contenido, procesamiento de facturas utilizando PDF con inteligencia artificial y APIs.
  - **Complejidad:** Baja (1 nodos)

- **[1491-remove-personally-identifiable-information-pii-openai.json](workflows/1491-remove-personally-identifiable-information-pii-openai.json)**
  - **Descripción:** Este flujo permite extracción de datos, generación de contenido, monitoreo utilizando OpenAI/GPT con inteligencia artificial y APIs.
  - **Complejidad:** Baja (1 nodos)

- **[2530-analytics-utm-generator.json](workflows/2530-analytics-utm-generator.json)**
  - **Descripción:** Este flujo automático crea enlaces con parámetros UTM personalizados a partir de inputs específicos, genera códigos QR para ellos y luego utiliza un agente analítico basado en OpenAI para evaluar datos de Google Analytics.
  - **Complejidad:** Baja (1 nodos)

- **[2533-redaktionsplan_caption_generator.json](workflows/2533-redaktionsplan_caption_generator.json)**
  - **Descripción:** Este flujo automático crea títulos para redes sociales, utilizando la base de datos Airtable y un modelo de chat IA para generar textos creativos e informativos.
  - **Complejidad:** Baja (1 nodos)

- **[2551-traductor-srt.json](workflows/2551-traductor-srt.json)**
  - **Descripción:** Este flujo automático permite procesar archivos SRT subiendo un formulario que contiene el archivo y seleccionando el idioma destino. El sistema extrae texto del archivo binario, lo divide en partes, traduce cada fragmento manteniendo la estructura de subtítulos y finalmente genera un nuevo archivo con las traducciones completadas.
  - **Complejidad:** Baja (1 nodos)

- **[2552-google-sheets-mysql-sync.json](workflows/2552-google-sheets-mysql-sync.json)**
  - **Descripción:** Este flujo automatizado sincroniza datos entre Google Sheets y MySQL mediante comparaciones, actualizaciones y condiciones específicas.
  - **Complejidad:** Baja (1 nodos)

- **[2563-vector-db-loader.json](workflows/2563-vector-db-loader.json)**
  - **Descripción:** Este flujo automático permite cargar documentos de Google Drive en una base de datos vectorial usando embeddings de OpenAI y PostgreSQL.
  - **Complejidad:** Baja (1 nodos)

- **[2567-postgres-sync.json](workflows/2567-postgres-sync.json)**
  - **Descripción:** Este flujo sincroniza automáticamente datos de Google Sheets hacia una tabla PostgreSQL, insertando nuevos registros o actualizando los existentes basándose en campos clave.
  - **Complejidad:** Baja (1 nodos)

- **[2569-dataforseo-backlink-checker.json](workflows/2569-dataforseo-backlink-checker.json)**
  - **Descripción:** Este flujo verifica los estados (vivo o muerto) de un conjunto de URLs, analizándolas a través del API de DataForSEO y registrando el resultado en una hoja de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2594-bluesky-post-automation.json](workflows/2594-bluesky-post-automation.json)**
  - **Descripción:** Este flujo automático permite publicar posts con imágenes en Bluesky, manejando la autenticación de sesión y el envío de archivos.
  - **Complejidad:** Baja (1 nodos)

- **[2598-shopware-multi-manufacturer-import.json](workflows/2598-shopware-multi-manufacturer-import.json)**
  - **Descripción:** Este flujo automático permite importar múltiples fabricantes desde una hoja de Google hacia Shopware 6 mediante el procesamiento por lotes. Configura los parámetros necesarios y crea solicitudes HTTP con datos encriptados para logotipos e información multilingüe.
  - **Complejidad:** Baja (1 nodos)

- **[2606-youtube-trend-analysis-memory.json](workflows/2606-youtube-trend-analysis-memory.json)**
  - **Descripción:** Este flujo automático analiza datos de videos de YouTube utilizando herramientas como búsqueda y procesamiento del motor LangChain, luego los almacena en memoria para su uso posterior. Además, integra una verificación inicial mediante chatTrigger que determina si el usuario proporcionó un nicho antes de proceder.
  - **Complejidad:** Baja (1 nodos)

- **[2615-jira-notion-sync.json](workflows/2615-jira-notion-sync.json)**
  - **Descripción:** Este flujo automatizado sincroniza las creación, modificación y eliminación de problemas en Jira con entradas en una base de datos específica de Notion.
  - **Complejidad:** Baja (1 nodos)

- **[2616-medium_linkedin_automation.json](workflows/2616-medium_linkedin_automation.json)**
  - **Descripción:** Este flujo automático busca artículos aleatorios de Medium usando etiquetas predefinidas, verifica si ya no han sido utilizados mediante un registro en Airtable, crea publicaciones en LinkedIn con sus imágenes y envía una alerta por cada post exitoso.
  - **Complejidad:** Baja (1 nodos)

- **[2621-vector-paquete.json](workflows/2621-vector-paquete.json)**
  - **Descripción:** Este flujo automático extrae textos de archivos JSON en FTP, los divide en fragmentos y los almacena como embeddings en una base de datos vectorial Qdrant para facilitar búsquedas semánticas.
  - **Complejidad:** Baja (1 nodos)

- **[2624-OpenSeaAnalyticsAgent.json](workflows/2624-OpenSeaAnalyticsAgent.json)**
  - **Descripción:** Este flujo automático implementa un agente conversacional con memoria que analiza datos de NFTs utilizando API de OpenSea.
  - **Complejidad:** Baja (1 nodos)

- **[2639-oidc-client-auth-flow.json](workflows/2639-oidc-client-auth-flow.json)**
  - **Descripción:** Este flujo automático de n8n implementa el protocolo OIDC (OpenID Connect) para autenticar usuarios y obtener información sobre ellos. Comienza con un webhook que captura peticiones entrantes, luego procesa cookies de autenticación. Después, verifica si hay token presente o se recibe código en la URL para continuar obteniendo datos del usuario.
  - **Complejidad:** Baja (1 nodos)

- **[2648-travel-planner-mongodb.json](workflows/2648-travel-planner-mongodb.json)**
  - **Descripción:** Este flujo actúa como un asistente de planificación viajera que utiliza la memoria conversacional MongoDB y el vector store Atlas para buscar puntos de interés.
  - **Complejidad:** Baja (1 nodos)

- **[2651-ai_tshirt_redesign.json](workflows/2651-ai_tshirt_redesign.json)**
  - **Descripción:** Este flujo analiza una imagen de diseño de camiseta mediante un modelo de IA, como GPT-4o, y genera un prompt mejorado para crear un rediseño visual artístico usando modelos generativos.
  - **Complejidad:** Baja (1 nodos)

- **[2705-automated-tasks-creator.json](workflows/2705-automated-tasks-creator.json)**
  - **Descripción:** Este flujo automático crea tareas en Airtable basadas en plantillas y actualiza registros con fechas calculadas.
  - **Complejidad:** Baja (1 nodos)

- **[2708-piloterr-fundraising-scraping.json](workflows/2708-piloterr-fundraising-scraping.json)**
  - **Descripción:** Este flujo automático extrae información de financiación reciente de Crunchbase para Series A, B y Seed, la enriquece con datos adicionales de LinkedIn y Semrush, y la exporta a Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2716-form-to-email-notificacion.json](workflows/2716-form-to-email-notificacion.json)**
  - **Descripción:** Este flujo recoge datos de un formulario donde los usuarios ingresan su rol y correo electrónico. Luego verifica si el correo no es personal usando Clearbit para enriquecer la información. Si cumple con ciertos criterios, envía un correo electrónico.
  - **Complejidad:** Baja (1 nodos)

- **[2717-linkedin-email-finder.json](workflows/2717-linkedin-email-finder.json)**
  - **Descripción:** Este flujo automatiza la actualización de información de contactos en Google Sheets usando la API de Prospeo.io para encontrar correos electrónicos a través de URLS de LinkedIn.
  - **Complejidad:** Baja (1 nodos)

- **[2735-traductor-deepL-GDrive.json](workflows/2735-traductor-deepL-GDrive.json)**
  - **Descripción:** Este flujo automatiza la traducción de documentos PDF usando DeepL y Google Drive. Configura una ruta, selecciona el idioma origen y destino, y los archivos se traducirán automáticamente.
  - **Complejidad:** Baja (1 nodos)

- **[2746-dropcontact-batch.json](workflows/2746-dropcontact-batch.json)**
  - **Descripción:** Este flujo automatiza la eliminación masiva de contactos en Dropcontact mediante consultas PostgreSQL y maneja hasta 1500 solicitudes por hora.
  - **Complejidad:** Baja (1 nodos)

- **[2748-wordpress_blog_poster.json](workflows/2748-wordpress_blog_poster.json)**
  - **Descripción:** Este flujo automatiza la publicación de contenido en WordPress y Airtable. Busca entradas marcadas como 'To Post', convierte el markdown a HTML, sube una imagen, crea una entrada en WordPress con ella y actualiza Airtable para marcarla como 'Posted'.
  - **Complejidad:** Baja (1 nodos)

- **[2783-paddle-invoice-processor.json](workflows/2783-paddle-invoice-processor.json)**
  - **Descripción:** Este flujo automático detecta y procesa invoices de Paddle desde Gmail, extrae el enlace PDF, lo descarga y almacena en Google Drive organizándolo en carpetas específicas.
  - **Complejidad:** Baja (1 nodos)

- **[2788-daily-order-summary.json](workflows/2788-daily-order-summary.json)**
  - **Descripción:** Este flujo automatiza la creación de un resumen diario de órdenes y su envío por correo electrónico. Cada vez que se recibe una nueva orden a través de un webhook, los datos se almacenan en Airtable. A las 7 PM se genera un informe con todas las órdenes del día y se adjunta un HTML formateado.
  - **Complejidad:** Baja (1 nodos)

- **[2790-notion-kb-agent.json](workflows/2790-notion-kb-agent.json)**
  - **Descripción:** Este flujo utiliza OpenAI y Notion para actuar como un asistente de conocimiento base que busca información en una base de datos de Notion basándose en preguntas del usuario.
  - **Complejidad:** Baja (1 nodos)

- **[2812-youtube-metagen.json](workflows/2812-youtube-metagen.json)**
  - **Descripción:** Este flujo automatiza la generación de metadatos para videos de YouTube, incluyendo títulos, descripciones y tags optimizados para SEO, utilizando un formulario de entrada que procesa enlaces de video y transcripciones.
  - **Complejidad:** Baja (1 nodos)

- **[2819-procesar_Ordenes_Gmail.json](workflows/2819-procesar_Ordenes_Gmail.json)**
  - **Descripción:** Flujo automático que procesa órdenes de compra recibidas por correo electrónico, extrae información relevante y la almacena en una hoja de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[2834-automated-instagram-posts.json](workflows/2834-automated-instagram-posts.json)**
  - **Descripción:** Este flujo automático publica contenido en Instagram usando Google Drive para detectar subidas de archivo, OpenAI para generar captions y Facebook Graph API para publicación.
  - **Complejidad:** Baja (1 nodos)

- **[2838-retell-call-storage.json](workflows/2838-retell-call-storage.json)**
  - **Descripción:** Este flujo procesa y almacena en diferentes herramientas como Airtable, Google Sheets y Notion los datos de las llamadas analizadas por Retell AI. Recibe un webhook cuando una llamada termina, filtra solo los eventos 'call_analyzed', extrae información relevante como el ID de la llamada, duración, costo y transcripción, y la guarda en Airtable, Google Sheets y Notion.
  - **Complejidad:** Baja (1 nodos)

- **[2844-actualizar_Tasas.json](workflows/2844-actualizar_Tasas.json)**
  - **Descripción:** Este flujo automatiza la actualización diaria de tasas de cambio desde USD a múltiples divisas utilizando una API. Registra los datos en Google Sheets y mantiene un historial archivado.
  - **Complejidad:** Baja (1 nodos)

- **[2848-linkedin-jobs-to-sheets.json](workflows/2848-linkedin-jobs-to-sheets.json)**
  - **Descripción:** Este flujo automatiza la extracción de ofertas laborales de LinkedIn utilizando Bright Data, las limpia y las envía a una hoja de cálculo de Google Sheets. Incluye un formulario para definir filtros como ubicación, palabra clave y país, espera a que se procese la solicitud, luego envía los datos limpios a la planilla.
  - **Complejidad:** Baja (1 nodos)

- **[2849-producthunt-to-sheets.json](workflows/2849-producthunt-to-sheets.json)**
  - **Descripción:** Este flujo recoge y procesa información de Product Hunt cada día para actualizar una hoja de cálculo de Google Sheets con los datos básicos de los productos publicados.
  - **Complejidad:** Baja (1 nodos)

- **[2857-filesystem-mcp-server.json](workflows/2857-filesystem-mcp-server.json)**
  - **Descripción:** Flujo que implementa un servidor MCP para manejar operaciones de archivo como listar directorios, leer y crear archivos en un sistema de archivos a través de comandos controlados.
  - **Complejidad:** Baja (1 nodos)

- **[2858-postgre-mcp-server.json](workflows/2858-postgre-mcp-server.json)**
  - **Descripción:** Flujo que implementa una interfaz MCP para interactuar con PostgreSQL permitiendo operaciones CRUD seguras usando herramientas personalizadas.
  - **Complejidad:** Baja (1 nodos)

- **[2870-paypal-payment-email.json](workflows/2870-paypal-payment-email.json)**
  - **Descripción:** Este flujo recoge datos de un webhook de PayPal, filtra eventos de pago completados, extrae detalles del orden, captura información del comprador y del producto, genera un correo electrónico con los datos formateados y adjunta un archivo JSON.
  - **Complejidad:** Baja (1 nodos)

- **[2898-whatsapp-flow-encrypt.json](workflows/2898-whatsapp-flow-encrypt.json)**
  - **Descripción:** Flujo que maneja la decodificación y encriptación híbrida de datos mediante RSA y AES-GCM para procesar interacciones seguras con usuarios a través de Whatsapp Flow.
  - **Complejidad:** Baja (1 nodos)

- **[2906-workflow-obsidian-markdown.json](workflows/2906-workflow-obsidian-markdown.json)**
  - **Descripción:** Este flujo automatiza la creación de notas en formato Markdown en tu Obsidian Vault mediante Google Drive. Recibe resultados de workflows, procesa información para generar contenido estructurado con YAML frontmatter y almacena los archivos en Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[2917-youtube-to-airtable.json](workflows/2917-youtube-to-airtable.json)**
  - **Descripción:** Este flujo automatiza la extracción de transcripciones de vídeos de YouTube y genera resúmenes detallados que se guardan en Airtable.
  - **Complejidad:** Baja (1 nodos)

- **[2920-flujo-extraccion-apuestas.json](workflows/2920-flujo-extraccion-apuestas.json)**
  - **Descripción:** Este flujo automático programa la extracción de datos de apuestas deportivas utilizando TheOddsAPI y Airtable. Realiza capturas diarias al inicio y fin del día para eventos futuros y resultados, respectivamente, y actualiza los registros en Airtable con información detallada.
  - **Complejidad:** Baja (1 nodos)

- **[2948-pinterest-analysis-ai.json](workflows/2948-pinterest-analysis-ai.json)**
  - **Descripción:** Este flujo automático extrae y analiza datos de Pinterest usando su API, almacena la información en Airtable, luego utiliza OpenAI para generar recomendaciones de contenido y envía un resumen a Gmail.
  - **Complejidad:** Baja (1 nodos)

- **[2958-formulario-datos.json](workflows/2958-formulario-datos.json)**
  - **Descripción:** Este flujo automático registra los datos de un formulario en Google Sheets y Airtable, extrae la fecha y hora de la submission, y envía correos electrónicos personalizados.
  - **Complejidad:** Baja (1 nodos)

- **[2973-pinterest-analysis-ai-suggestions.json](workflows/2973-pinterest-analysis-ai-suggestions.json)**
  - **Descripción:** Este flujo automático extrae y analiza datos de Pinterest Organic utilizando la API, almacena los resultados en Airtable y genera recomendaciones de contenido con inteligencia artificial para marketing.
  - **Complejidad:** Baja (1 nodos)

- **[3006-linkedin-to-airtable.json](workflows/3006-linkedin-to-airtable.json)**
  - **Descripción:** Este flujo automatiza la extracción de me gusta en LinkedIn, filtra las publicaciones más recientes y relevantes, y las registra en Airtable para organizarlas como ideas de contenido.
  - **Complejidad:** Baja (1 nodos)

- **[3010-coinmarketcap_dex_agent.json](workflows/3010-coinmarketcap_dex_agent.json)**
  - **Descripción:** Este flujo automático actúa como una herramienta de agente inteligente para interactuar con la API de CoinMarketCap DEXScan, permitiendo recuperar y analizar datos en tiempo real sobre exchanges descentralizados, pares de trading, volumen, liquidez y actividad comercial mediante un sistema multiagente integrado.
  - **Complejidad:** Baja (1 nodos)

- **[3020-convertir_imagenes_webp.json](workflows/3020-convertir_imagenes_webp.json)**
  - **Descripción:** Este flujo automático convierte imágenes JPG y PNG a formato WEBP usando la API de APYHub. Recupera URLs de imágenes desde una hoja de cálculo de Google Sheets, determina el tipo de archivo, realiza la conversión correspondiente y actualiza la hoja con los nuevos enlaces. Finalmente, sube las imágenes convertidas a Google Drive.
  - **Complejidad:** Baja (1 nodos)

- **[3035-cripto-market-agent.json](workflows/3035-cripto-market-agent.json)**
  - **Descripción:** Este flujo utiliza agentes de lenguaje y herramientas de HTTP para consultar datos de mercado criptográfico mediante la API de CoinMarketCap, proporcionando información sobre exchanges, activos, índices y sentimiento del mercado.
  - **Complejidad:** Baja (1 nodos)

- **[3042-airtable-mcp-server.json](workflows/3042-airtable-mcp-server.json)**
  - **Descripción:** Este flujo crea un servidor MCP usando Airtable para interactuar con una base de datos, permitiendo operaciones como obtener, buscar, actualizar y eliminar registros.
  - **Complejidad:** Baja (1 nodos)

- **[3073-reservation_medica.json](workflows/3073-reservation_medica.json)**
  - **Descripción:** Este flujo utiliza un agente de inteligencia artificial para gestionar citas médicas, integrando OpenAI y Google Calendar/Sheets. El agente recibe mensajes, verifica disponibilidad en el calendario, sugiere horarios o crea citas.
  - **Complejidad:** Baja (1 nodos)

- **[3082-pge-energy-cost-tracker.json](workflows/3082-pge-energy-cost-tracker.json)**
  - **Descripción:** Este flujo automatiza la extracción diaria de los costos de energía de PG&E, incluyendo electricidad y gas, desde su sitio web. Utiliza un navegador para iniciar sesión, navegar a las páginas relevantes, extraer los datos y enviar un correo electrónico con un informe formateado.
  - **Complejidad:** Baja (1 nodos)

- **[3085-notion-ai-assistant.json](workflows/3085-notion-ai-assistant.json)**
  - **Descripción:** Este flujo actúa como un asistente de conocimiento que utiliza Notion para buscar información y OpenAI para responder preguntas, organizando datos de bases de datos de manera eficiente.
  - **Complejidad:** Baja (1 nodos)

- **[3096-ahrefs-keyword-research.json](workflows/3096-ahrefs-keyword-research.json)**
  - **Descripción:** Flujo de investigación de palabras clave que utiliza Ahrefs para extraer y formatear datos SEO, pasando por un agente de limpieza de consultas y luego procesando la información con el modelo Gemini para una respuesta estructurada.
  - **Complejidad:** Baja (1 nodos)

- **[3111-air-quality-scheduler.json](workflows/3111-air-quality-scheduler.json)**
  - **Descripción:** Este flujo recolecta y procesa datos de calidad del aire y polen utilizando la API de Ambee, luego utiliza un agente de inteligencia artificial para generar recomendaciones personalizadas basadas en el perfil del usuario, y finalmente envía estas recomendaciones por correo electrónico.
  - **Complejidad:** Baja (1 nodos)

- **[3120-usuarios_ficticios.json](workflows/3120-usuarios_ficticios.json)**
  - **Descripción:** Este flujo genera y procesa datos JSON para crear archivos CSV con nombres y correos electrónicos aleatorios, usando GPT-4. Los usuarios pueden estar suscritos o no, con fechas de suscripción opcionales.
  - **Complejidad:** Baja (1 nodos)

- **[3121-deteccion_objetos_gemini.json](workflows/3121-deteccion_objetos_gemini.json)**
  - **Descripción:** Este flujo utiliza la API de Gemini 2.0 para detectar objetos en una imagen basada en un prompt. Descarga una imagen, usa el modelo de Gemini para obtener coordenadas normalizadas de los bounding boxes y luego las ajusta al tamaño original de la imagen para dibujarlas sobre ella.
  - **Complejidad:** Baja (1 nodos)

- **[3134-line-bot-ocr-to-sheets.json](workflows/3134-line-bot-ocr-to-sheets.json)**
  - **Descripción:** Este flujo automático recoge datos de una imagen enviada a un bot de LINE, la procesa para extraer información relevante usando OCR y luego almacena los datos en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3140-n8n-credentials-agent.json](workflows/3140-n8n-credentials-agent.json)**
  - **Descripción:** Este flujo automatiza la gestión de credenciales de workflows en n8n almacenándolas en una base de datos SQLite y utiliza un agente de IA para realizar búsquedas avanzadas mediante SQL.
  - **Complejidad:** Baja (1 nodos)

- **[3148-remove_pii_from_csv.json](workflows/3148-remove_pii_from_csv.json)**
  - **Descripción:** Este flujo automatiza la eliminación de datos personales (PII) de archivos CSV alojados en Google Drive. Utiliza OpenAI para identificar las columnas con información sensible y genera un nuevo archivo sin dichos datos.
  - **Complejidad:** Baja (1 nodos)

- **[3174-analisis-seo-serp.json](workflows/3174-analisis-seo-serp.json)**
  - **Descripción:** Automatiza el análisis de datos SEO de SERPBear enviando información a OpenRouter para obtener una sumailla y guardando los resultados en Baserow.
  - **Complejidad:** Baja (1 nodos)

- **[3175-google-doc-summarizer.json](workflows/3175-google-doc-summarizer.json)**
  - **Descripción:** Este flujo automático monitorea un folder específico en Google Drive, obtiene los nuevos documentos .doc, extrae su contenido y lo sumaiza utilizando un modelo de IA, luego almacena el resumen junto con metadatos en una hoja de cálculo de Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3180-sqlite-ai-agent.json](workflows/3180-sqlite-ai-agent.json)**
  - **Descripción:** Este flujo permite interactuar con una base de datos SQLite usando un agente de inteligencia artificial. Descarga, extrae y carga la base de datos localmente, luego utiliza el agente de SQL para responder preguntas basadas en los datos.
  - **Complejidad:** Baja (1 nodos)

- **[3189-ubicacion-trabajo.json](workflows/3189-ubicacion-trabajo.json)**
  - **Descripción:** Este flujo automático registra automáticamente los tiempos de entrada y salida basados en ubicación usando Webhooks, Google Sheets y Drive. Detecta si la hoja de trabajo existe, crea una nueva si no está presente y registra los datos de hora con fecha y dirección.
  - **Complejidad:** Baja (1 nodos)

- **[3240-strava-to-sheets.json](workflows/3240-strava-to-sheets.json)**
  - **Descripción:** Este flujo programa un horario que cada dos horas extrae actividades de Strava, filtra aquellas no guardadas en Google Sheets y las procesa para actualizar una hoja de cálculo con detalles como distancia, fecha, tiempo y desnivel.
  - **Complejidad:** Baja (1 nodos)

- **[3259-notion-md-sincro.json](workflows/3259-notion-md-sincro.json)**
  - **Descripción:** Este flujo automatiza la sincronización de bloques de Notion convirtiendo texto enriquecido a formato Markdown y viceversa, permitiendo actualizar contenido con formato.
  - **Complejidad:** Baja (1 nodos)

- **[3268-prompt-generator.json](workflows/3268-prompt-generator.json)**
  - **Descripción:** Flujo para generar y organizar prompts optimizados en Airtable usando Google Gemini. Permite categorizar y estructurar prompts de chatbot para un mejor manejo en n8n.
  - **Complejidad:** Baja (1 nodos)

- **[3296-shopify-to-google-spreadsheet.json](workflows/3296-shopify-to-google-spreadsheet.json)**
  - **Descripción:** Este flujo extrae información de clientes de Shopify y la exporta a una hoja de cálculo de Google Sheets. Utiliza un bucle para recuperar datos paginados hasta que no haya más páginas, procesando la información y actualizando continuamente.
  - **Complejidad:** Baja (1 nodos)

- **[3302-webpage-change-monitor.json](workflows/3302-webpage-change-monitor.json)**
  - **Descripción:** Flujo automatizado para detectar cambios en una página web y notificar via correo electrónico cuando hay modificación. Utiliza un hash de contenido para comparación y registra actividades en Google Sheets.
  - **Complejidad:** Baja (1 nodos)

- **[3333-Enrich_Company_Data.json](workflows/3333-Enrich_Company_Data.json)**
  - **Descripción:** Este flujo automatiza la enriquecimiento de datos empresariales usando Google Sheets, OpenAI y una herramienta de extracción web. Recupera información de una hoja de cálculo, utiliza un agente de inteligencia artificial para analizar sitios web mediante ScrapingBee y actualiza los datos en tiempo real.
  - **Complejidad:** Baja (1 nodos)

- **[0531-webflow-form-trigger.json](workflows/0531-webflow-form-trigger.json)**
  - **Descripción:** Este flujo automático se activa cuando un formulario es enviado en una página web de Webflow y recoge los datos para su procesamiento.
  - **Complejidad:** Baja (1 nodos)

- **[0599-box-folder-file-events.json](workflows/0599-box-folder-file-events.json)**
  - **Descripción:** Este flujo automático se activa cuando archivos o carpetas son movidas o descargadas en una carpeta específica de Box.
  - **Complejidad:** Baja (1 nodos)

- **[0054-clickup-trigger.json](workflows/0054-clickup-trigger.json)**
  - **Descripción:** Este flujo automático se activa al recibir actualizaciones de cualquier evento en la herramienta ClickUp.
  - **Complejidad:** Baja (1 nodos)

- **[0542-asana-tweet-event-trigger.json](workflows/0542-asana-tweet-event-trigger.json)**
  - **Descripción:** Este flujo automático permite recibir actualizaciones cuando ocurre un evento en Asana relacionado con tweets.
  - **Complejidad:** Baja (1 nodos)

- **[0567-github-monitor-repo.json](workflows/0567-github-monitor-repo.json)**
  - **Descripción:** Este flujo monitoriza cualquier actividad en el repositorio de GitHub 'n8n-io/n827-docs' mediante una webhook, utilizando credenciales predefinidas para la API.
  - **Complejidad:** Baja (1 nodos)

- **[0568-gitlab-trigger-n8n-docs.json](workflows/0568-gitlab-trigger-n8n-docs.json)**
  - **Descripción:** Este flujo monitorea eventos en el repositorio GitLab n8n-io/n8n-docs mediante una webhook.
  - **Complejidad:** Baja (1 nodos)

- **[0569-bitbucket-push-monitor.json](workflows/0569-bitbucket-push-monitor.json)**
  - **Descripción:** Este flujo se activa automáticamente cuando hay un evento de push en el repositorio 'test' de Bitbucket.
  - **Complejidad:** Baja (1 nodos)

- **[0603-jira-trigger-any-event.json](workflows/0603-jira-trigger-any-event.json)**
  - **Descripción:** Este flujo monitoriza cualquier evento en Jira Software Cloud mediante una conexión web.
  - **Complejidad:** Baja (1 nodos)

- **[0640-helpscout-customer-created.json](workflows/0640-helpscout-customer-created.json)**
  - **Descripción:** Este flujo escucha específicamente el evento 'customer.created' en HelpScout utilizando un webhook OAuth.
  - **Complejidad:** Baja (1 nodos)

- **[0667-taiga-event-trigger.json](workflows/0667-taiga-event-trigger.json)**
  - **Descripción:** Este flujo escucha eventos en el proyecto específico de Taiga mediante un desencadenador webhooks.
  - **Complejidad:** Baja (1 nodos)

- **[1176-zendesk-ticket-updates.json](workflows/1176-zendesk-ticket-updates.json)**
  - **Descripción:** Este flujo automático está configurado para recibir actualizaciones de tickets en Zendesk a través de un webhook, aunque no está activo.
  - **Complejidad:** Baja (1 nodos)

- **[1251-trello-list-updates.json](workflows/1251-trello-list-updates.json)**
  - **Descripción:** Este flujo monitorea y recibe actualizaciones sobre cambios en una lista específica de Trello.
  - **Complejidad:** Baja (1 nodos)


### Gestión de Contenido y Redes Sociales

- **[0007-social-media-creator.json](workflows/0007-social-media-creator.json)**
  - **Descripción:** Este flujo automático permite a un chatbot crear contenido optimizado para múltiples redes sociales (X-Twitter, Instagram, Facebook, LinkedIn, Threads, YouTube Shorts) utilizando modelos LLM y herramientas de búsqueda web. Genera posts con estructuras JSON específicas y crea imágenes usando servicios externos como pollinations.ai.
  - **Complejidad:** Alta (100 nodos)

- **[2912-youtube-ai-summarizer.json](workflows/2912-youtube-ai-summarizer.json)**
  - **Descripción:** Este flujo automatiza la sumailla y análisis de playlists o vídeos de YouTube mediante IA. Detecta URLs, procesa transcripciones, genera resúmenes estructurados y almacena embeddings para respuestas contextualizadas.
  - **Complejidad:** Alta (72 nodos)

- **[1409-automated_social_media_factory.json](workflows/1409-automated_social_media_factory.json)**
  - **Descripción:** Genera contenidos para redes sociales de forma automatizada.
  - **Complejidad:** Alta (56 nodos)

- **[1279-spotify_to_youtube_sync.json](workflows/1279-spotify_to_youtube_sync.json)**
  - **Descripción:** Sincroniza listas de Spotify con YouTube.
  - **Complejidad:** Alta (54 nodos)

- **[3044-video_generator_short_form.json](workflows/3044-video_generator_short_form.json)**
  - **Descripción:** Este flujo automático genera vídeos cortos con IA, utilizando OpenAI para generar textos y prompts, Flux y Kling de PiAPI para crear imágenes y vídeos, ElevenLabs para la voz y Creatomate para renderizar el vídeo final. Luego los sube a todas las redes sociales.
  - **Complejidad:** Alta (51 nodos)

- **[2985-hacker_news_video_content.json](workflows/2985-hacker_news_video_content.json)**
  - **Descripción:** Este flujo automatiza la conversión de artículos de Hacker News a contenido en vídeo usando.RunwayML y LeonardoAI para generar imágenes y vídeos personalizados.
  - **Complejidad:** Alta (48 nodos)

- **[2965-instagram-content-generator.json](workflows/2965-instagram-content-generator.json)**
  - **Descripción:** Este flujo automatiza la creación de contenido para Instagram usando tendencias del momento y generación de imágenes con IA. Descarga contenido popular de Instagram a través de una API, analiza las imágenes con GPT-4, crea captions atractivas y genera nuevas imágenes con Flux AI. Publica el contenido en tu cuenta de Instagram empresarial y monitorea el estado de las publicaciones.
  - **Complejidad:** Alta (44 nodos)

- **[2964-image_generator_9_16.json](workflows/2964-image_generator_9_16.json)**
  - **Descripción:** Este flujo genera imágenes de aspecto 9:16 a partir de contenido y guías de marca utilizando OpenAI y Leonardo.ai para crear activos visuales optimizados.
  - **Complejidad:** Alta (39 nodos)

- **[1416-video-social-generator.json](workflows/1416-video-social-generator.json)**
  - **Descripción:** Genera videos cortos para redes sociales.
  - **Complejidad:** Alta (38 nodos)

- **[2952-crawler-ai-scraper.json](workflows/2952-crawler-ai-scraper.json)**
  - **Descripción:** Flujo que utiliza agentes de IA para extraer enlaces de redes sociales de sitios web autonomamente.
  - **Complejidad:** Alta (38 nodos)

- **[2576-AI-WordPress-Article-Creator.json](workflows/2576-AI-WordPress-Article-Creator.json)**
  - **Descripción:** Este flujo automático utiliza la inteligencia artificial para generar artículos SEO en WordPress basados en palabras clave proporcionadas por el usuario. Incluye creación de títulos, subtítulos, capítulos y verificación con Wikipedia.
  - **Complejidad:** Alta (37 nodos)

- **[2930-exam-question-generator.json](workflows/2930-exam-question-generator.json)**
  - **Descripción:** Flujo para generar preguntas de examen tanto abiertas como cerradas a partir de contenido en Google Docs usando vectores Qdrant y diferentes modelos de lenguaje.
  - **Complejidad:** Alta (37 nodos)

- **[2942-categorizador-ai-outlook.json](workflows/2942-categorizador-ai-outlook.json)**
  - **Descripción:** Este flujo categoriza automáticamente los correos electrónicos de Outlook usando IA para clasificarlos en diferentes carpetas basadas en su contenido.
  - **Complejidad:** Alta (36 nodos)

- **[1148-linkedin-automation.json](workflows/1148-linkedin-automation.json)**
  - **Descripción:** Este flujo automatizado busca obtener artículos recientes sobre LinkedIn mediante búsquedas programadas, extraer sus enlaces y luego generar contribuciones utilizando la tecnología AI.
  - **Complejidad:** Alta (33 nodos)

- **[2568-service-page-seo-blueprint.json](workflows/2568-service-page-seo-blueprint.json)**
  - **Descripción:** Este flujo analiza el rendimiento SEO de paginas de servicio, comparando estructuras y contenidos con competidores en tiempo real para crear estrategias optimizadas.
  - **Complejidad:** Alta (33 nodos)

- **[2572-youtube-automation-generative.json](workflows/2572-youtube-automation-generative.json)**
  - **Descripción:** Este flujo automático permite obtener videos de YouTube y generar títulos, descripciones e información SEO para automatizar las funciones necesarias.
  - **Complejidad:** Alta (33 nodos)

- **[3048-analyze_youtube_workflow.json](workflows/3048-analyze_youtube_workflow.json)**
  - **Descripción:** Este flujo analiza videos de YouTube para resumirlos, generar transcripciones y extraer contenido utilizando la API de Gemini AI de Google. Permite diferentes tipos de análisis como resúmenes concisos, transcripciones verbatim, subtítulos con marcas de tiempo y más.
  - **Complejidad:** Alta (33 nodos)

- **[0818-ai-summary-wordpress.json](workflows/0818-ai-summary-wordpress.json)**
  - **Descripción:** Este flujo automático analiza y clasifica contenido de WordPress para determinar si ya incluye un resumen generado por IA, generando nuevos resúmenes con GPT-4o-mini cuando es necesario.
  - **Complejidad:** Alta (32 nodos)

- **[3170-auto-tag-wordpress.json](workflows/3170-auto-tag-wordpress.json)**
  - **Descripción:** Este flujo automatiza la asignación de etiquetas en WordPress usando IA. Analiza entradas RSS, genera y estructura tags, crea nuevas si son necesarias y actualiza las existentes.
  - **Complejidad:** Alta (32 nodos)

- **[2972-youtube-ai-agent.json](workflows/2972-youtube-ai-agent.json)**
  - **Descripción:** Este flujo automatiza la extracción de detalles y transcripciones de videos de YouTube, los cuales son procesados por un agente de inteligencia artificial para permitir una conversación contextualizada y análisis detallado del contenido.
  - **Complejidad:** Alta (29 nodos)

- **[1008-workflow-pdf-wordpress-ai.json](workflows/1008-workflow-pdf-wordpress-ai.json)**
  - **Descripción:** Este flujo automático transforma documentos PDF en entradas de blog formateadas para WordPress, utilizando IA para generar contenido y títulos, creando imágenes con pollinations.ai e incorporando una revisión humana mediante Gmail.
  - **Complejidad:** Alta (27 nodos)

- **[2945-automate-blog-ai.json](workflows/2945-automate-blog-ai.json)**
  - **Descripción:** Este flujo automatiza la creación de artículos de blog en voz de marca usando AI. Analiza contenido existente para extraer características de estilo y tono, luego genera nuevos artículos consistentes con ellos.
  - **Complejidad:** Alta (27 nodos)

- **[3229-ai_content_generator.json](workflows/3229-ai_content_generator.json)**
  - **Descripción:** Este flujo utiliza IA para analizar artículos existentes y extraer características de voz y estilo, luego genera contenido nuevo siguiendo esas pautas y publica en WordPress.
  - **Complejidad:** Alta (27 nodos)

- **[2584-youtube-video-analysis.json](workflows/2584-youtube-video-analysis.json)**
  - **Descripción:** Este flujo analiza videos de YouTube para generar resúmenes, transcripciones y descripciones detalladas de escenas. Permite elegir el tipo de análisis mediante la variable 'promptType' (transcript, summary, scene) e incorpora un modelo Gemini para procesamiento.
  - **Complejidad:** Alta (26 nodos)

- **[0929-analisis_comentarios_youtube.json](workflows/0929-analisis_comentarios_youtube.json)**
  - **Descripción:** Este flujo analiza comentarios de videos de YouTube utilizando la API de Google y GPT-4o-mini para generar un informe detallado con insights sobre tendencias del público, temas destacados y recomendaciones prácticas.
  - **Complejidad:** Alta (25 nodos)

- **[1010-workflow-contact-form-automation.json](workflows/1010-workflow-contact-form-automation.json)**
  - **Descripción:** Este flujo automático clasifica respuestas de formularios WordPress (CF7) y genera borradores de correos electrónicos personalizados para responder eficientemente a los clientes.
  - **Complejidad:** Alta (24 nodos)

- **[0906-gmail-reply-drafts-openai-assistant.json](workflows/0906-gmail-reply-drafts-openai-assistant.json)**
  - **Descripción:** Este flujo automático permite a Gmail responder mensajes con la ayuda de OpenAI Assistant, creando borradores de respuestas basados en el contenido del correo y eliminando las etiquetas que desencadenan esta acción después de componer el mensaje.
  - **Complejidad:** Alta (23 nodos)

- **[2578-analisis-contenido-brand.json](workflows/2578-analisis-contenido-brand.json)**
  - **Descripción:** Este flujo automático permite a un usuario configurar una URL para extraer el contenido markdown, limpiarlo dejando solo texto, generar un resumen conciso y analizar su sentimiento con modelos de Google Gemini.
  - **Complejidad:** Alta (23 nodos)

- **[2582-auto-article-generation.json](workflows/2582-auto-article-generation.json)**
  - **Descripción:** Este flujo automático utiliza el modelo de Perplexity para generar contenido inicial y luego lo refina mediante iteraciones usando modelos generativos de OpenAI, finalmente publicándolo en una plataforma como Contentful.
  - **Complejidad:** Alta (23 nodos)

- **[2739-email-ai-reply.json](workflows/2739-email-ai-reply.json)**
  - **Descripción:** Este flujo automático procesa correos electrónicos con etiquetas específicas transfiriendo su contenido al Asistente de OpenAI para generar un borrador de respuesta. El workflow incluye desde la extracción del correo hasta su envío final y posterior eliminación de las etiquetas de disparo.
  - **Complejidad:** Alta (23 nodos)

- **[3266-yt-ai-playlist.json](workflows/3266-yt-ai-playlist.json)**
  - **Descripción:** Este flujo crea y actualiza una playlist de YouTube con noticias AI, eliminando la anterior y notificando su creación.
  - **Complejidad:** Alta (23 nodos)

- **[2593-seo-blog-generator-flujo-automatico.json](workflows/2593-seo-blog-generator-flujo-automatico.json)**
  - **Descripción:** Este flujo automático permite a un usuario enviar una consulta de investigación relacionada con temas de salud masculina para que sea procesada por múltiples nodos de IA, generando contenido estructurado como títulos, subtítulos y hashtags basados en la información proporcionada. Luego utiliza esta estructura junto con investigaciones recopiladas mediante Perplexity.ai para crear un artículo completo de blog.
  - **Complejidad:** Alta (22 nodos)

- **[2847-paulgraham-essays-milvus.json](workflows/2847-paulgraham-essays-milvus.json)**
  - **Descripción:** Este flujo extrae los títulos de ensayos de Paul Graham, obtiene su contenido, los procesa y almacena en Milvus para luego responder preguntas sobre ellos.
  - **Complejidad:** Alta (22 nodos)

- **[2798-podcast-summarizer.json](workflows/2798-podcast-summarizer.json)**
  - **Descripción:** Este flujo automatiza la creación de un resumen diario de podcasts específicos por género. Utiliza la API de Taddy para obtener las listas de podcasts más populares, descarga los episodios seleccionados, transcribe su contenido con Whisper y luego genera un resumen usando OpenAI. El resultado se envía mediante correo electrónico.
  - **Complejidad:** Alta (21 nodos)

- **[2960-video_analyzer_youtube.json](workflows/2960-video_analyzer_youtube.json)**
  - **Descripción:** Este flujo utiliza diferentes modelos de lenguaje para analizar un video de YouTube a través de su transcripción, estructurando el análisis en formato JSON y envía los resultados por correo electrónico.
  - **Complejidad:** Alta (21 nodos)

- **[3061-wordpress-ai-optimizer.json](workflows/3061-wordpress-ai-optimizer.json)**
  - **Descripción:** Este flujo automatiza la creación y optimización de entradas en WordPress usando AI para generar títulos, artículos y metaetiquetas SEO amigables, además de manejar imágenes y actualizar hojas de cálculo.
  - **Complejidad:** Alta (21 nodos)

- **[0796-n8n-reAct-scraper.json](workflows/0796-n8n-reAct-scraper.json)**
  - **Descripción:** Este flujo utiliza un agente de IA ReAct con la herramienta HTTP_Request_Tool para extraer y procesar contenido HTML mediante solicitudes HTTP, aplicando limitaciones en largo de página y simplificándolo según los parámetros.
  - **Complejidad:** Alta (20 nodos)

- **[1239-wordpress-multi-social-publisher.json](workflows/1239-wordpress-multi-social-publisher.json)**
  - **Descripción:** Este flujo automatizado permite publicar contenido de WordPress en múltiples redes sociales usando modelos de lenguaje y procesamiento estructurado.
  - **Complejidad:** Alta (20 nodos)

- **[2692-http-web-content-processor.json](workflows/2692-http-web-content-processor.json)**
  - **Descripción:** Este flujo procesa una solicitud HTTP para obtener contenido de una página web, lo convierte a Markdown y aplica limitaciones como la eliminación de enlaces e imágenes si el método es simplificado. Maneja errores y formatea la salida según los parámetros proporcionados.
  - **Complejidad:** Alta (20 nodos)

- **[2743-youtube-rss-generator.json](workflows/2743-youtube-rss-generator.json)**
  - **Descripción:** Este flujo genera URLs de RSS personalizadas para canales de YouTube y vídeos específicos en diferentes formatos (ATOM, JSON, MRSS, PLAINTEXT, SFEED y XML) utilizando fuentes externas.
  - **Complejidad:** Alta (20 nodos)

- **[2863-youtube-mcp-server.json](workflows/2863-youtube-mcp-server.json)**
  - **Descripción:** Este flujo configura un servidor MCP que utiliza herramientas externas para realizar búsquedas en YouTube, descargar transcripciones y monitorear métricas de uso con APIFY.com.
  - **Complejidad:** Alta (20 nodos)

- **[2738-gmail-label-assigner.json](workflows/2738-gmail-label-assigner.json)**
  - **Descripción:** Este flujo automatiza la asignación de etiquetas a mensajes de Gmail usando IA. Analiza los correos electrónicos y determina cuáles etiquetas aplicar basándose en su contenido.
  - **Complejidad:** Alta (19 nodos)

- **[3083-linkedin-profile-finder.json](workflows/3083-linkedin-profile-finder.json)**
  - **Descripción:** Este flujo automatiza la búsqueda de perfiles de LinkedIn a través de un formulario donde el usuario proporciona el nombre completo y la empresa. Utiliza Bright Data para realizar búsquedas en Google y GPT-4o-mini para analizar los resultados, extraer información relevante y generar un seguimiento personalizado por correo electrónico.
  - **Complejidad:** Alta (19 nodos)

- **[0026-linkedin-top-sourcer.json](workflows/0026-linkedin-top-sourcer.json)**
  - **Descripción:** Este flujo permite encontrar perfiles de LinkedIn utilizando técnicas de búsqueda booleana a partir de una descripción natural del candidato.
  - **Complejidad:** Alta (18 nodos)

- **[1134-youtube-moments-analyzer.json](workflows/1134-youtube-moments-analyzer.json)**
  - **Descripción:** Este flujo analiza videos de YouTube en busca de momentos 'engaging' donde la intensidad supera un umbral y que no son demasiado cercanos entre sí, generando una respuesta estructurada con las coordenadas temporales más relevantes.
  - **Complejidad:** Alta (18 nodos)

- **[0910-url-markdown-batch.json](workflows/0910-url-markdown-batch.json)**
  - **Descripción:** Este flujo procesa URLs en lotes de 10, utiliza la API de Firecrawl para convertir contenido HTML a markdown y extraer enlaces, gestionando las limitaciones del proveedor.
  - **Complejidad:** Alta (17 nodos)

- **[1144-firecrawl-markdown-scraper.json](workflows/1144-firecrawl-markdown-scraper.json)**
  - **Descripción:** Este flujo automatiza la extracción de contenido web en formato Markdown y sus enlaces usando la API Firecrawl
  - **Complejidad:** Alta (17 nodos)

- **[1146-digitalocean-snapshots-management.json](workflows/1146-digitalocean-snapshots-management.json)**
  - **Descripción:** Este flujo automático administra automáticamente los snapshots de las instancias DigitalOcean, manteniendo un máximo de 4 y eliminando los más antiguos.
  - **Complejidad:** Alta (17 nodos)

- **[1413-automate_blog_creation.json](workflows/1413-automate_blog_creation.json)**
  - **Descripción:** Automatiza la creación de entradas de blog.
  - **Complejidad:** Alta (17 nodos)

- **[2622-auto-content-wordpress.json](workflows/2622-auto-content-wordpress.json)**
  - **Descripción:** Este flujo automático permite generar contenido completo en HTML con títulos optimizados SEO y palabras clave específicas, además de incorporar una imagen de Pexels cada vez que se publica un artículo en WordPress.
  - **Complejidad:** Alta (17 nodos)

- **[3136-tavily-search-extract.json](workflows/3136-tavily-search-extract.json)**
  - **Descripción:** Este flujo automatiza la búsqueda y extracción de información utilizando la API de Tavily, filtrando resultados por relevancia y resumiendo contenido con OpenAI.
  - **Complejidad:** Alta (17 nodos)

- **[1497-speed-up-social-media-banners-with-bannerbearcom.json](workflows/1497-speed-up-social-media-banners-with-bannerbearcom.json)**
  - **Descripción:** Este flujo permite generación de contenido utilizando OpenAI/GPT, Webhook, Twitter/X con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (16 nodos)

- **[0776-youtube-seo-blog-generator.json](workflows/0776-youtube-seo-blog-generator.json)**
  - **Descripción:** Este flujo automático permite extraer la transcripción de videos de YouTube utilizando Dumpling AI, generar un artículo de blog SEO completo con OpenAI GPT-4o basado en esa transcripción y enviarlo como correo electrónico junto con una imagen generada.
  - **Complejidad:** Media (15 nodos)

- **[0884-auto-post-sociales-n8n.json](workflows/0884-auto-post-sociales-n8n.json)**
  - **Descripción:** Este flujo automático, desencadenado diariamente a las 22:00 mediante un trigger programado, recoge información de una hoja de cálculo Google (URL y descripción del video) e integra con la API de Blotato para publicar el contenido en múltiples plataformas sociales sin intervención manual.
  - **Complejidad:** Media (15 nodos)

- **[0852-strapi-testimonials-automation.json](workflows/0852-strapi-testimonials-automation.json)**
  - **Descripción:** Este flujo automatizado busca coleccionar y analizar testimonios positivos en un sistema Strapi mediante la integración con Twitter.
  - **Complejidad:** Media (14 nodos)

- **[2544-n8n-chatbot-car-offer.json](workflows/2544-n8n-chatbot-car-offer.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE interactuar con el sitio web sell.peddle.com para obtener una oferta por un coche usado. Inicia la sesión en Airtop, carga el sitio y simula interacciones como hacer clics o teclear texto cuando se le indica mediante análisis del contenido actual de pantalla.
  - **Complejidad:** Media (14 nodos)

- **[2837-linkedin-posts-generator.json](workflows/2837-linkedin-posts-generator.json)**
  - **Descripción:** Este flujo automatiza la generación de mensajes LinkedIn promocionales para cada publicación de blog extraída de Ghost. Utiliza un agente AI para crear contenido atractivo y lo registra en una hoja de cálculo de Google.
  - **Complejidad:** Media (14 nodos)

- **[2971-youtube-automatic-metadata-uploader.json](workflows/2971-youtube-automatic-metadata-uploader.json)**
  - **Descripción:** Flujo para subir videos a YouTube con metadata optimizada automaticamente usando transcripciones e IA.
  - **Complejidad:** Media (14 nodos)

- **[3022-youtube_transcriber.json](workflows/3022-youtube_transcriber.json)**
  - **Descripción:** Este flujo transcribe videos de YouTube validando la URL y estructurando el texto con OpenAI para una salida limpia en portugués.
  - **Complejidad:** Media (14 nodos)

- **[3142-social-media-publisher.json](workflows/3142-social-media-publisher.json)**
  - **Descripción:** Este flujo automático gestiona la publicación de contenido en redes sociales como Instagram, LinkedIn, Facebook, X y TikTok a través de un formulario que acepta fotos o videos. Detecta el tipo de archivo (imagen o video), envía la información necesaria a la API correspondiente y muestra mensajes de éxito o error.
  - **Complejidad:** Media (14 nodos)

- **[1221-youtube-chapters-generator.json](workflows/1221-youtube-chapters-generator.json)**
  - **Descripción:** Este flujo de trabajo permite generar capítulos estructurados para videos de YouTube basándose en las subtitulaciones. Analiza el contenido temporal y crea un formato organizado.
  - **Complejidad:** Media (13 nodos)

- **[0129-twitter-banner-creator.json](workflows/0129-twitter-banner-creator.json)**
  - **Descripción:** Este flujo automático permite descargar los perfiles de seguidores recientes de Twitter, procesar sus imágenes de avatar (redimensionando y recortando), combinarlas con una imagen de fondo mediante composición multiestadio, y finalmente subirlas como banner usando la API OAuth1.0.
  - **Complejidad:** Media (12 nodos)

- **[0146-baserow-release-feed.json](workflows/0146-baserow-release-feed.json)**
  - **Descripción:** Este flujo automático recopila artículos de blog sobre 'release' desde baserow.io y genera una respuesta XML que puede ser utilizada para alimentar feeds o webhooks.
  - **Complejidad:** Media (12 nodos)

- **[0423-spotify-youtube-sync.json](workflows/0423-spotify-youtube-sync.json)**
  - **Descripción:** Este flujo sincroniza canciones entre listas de reproducción de YouTube y Spotify añadiendo solo las nuevas sin duplicados.
  - **Complejidad:** Media (12 nodos)

- **[0916-twitter-profile-banner-generator.json](workflows/0916-twitter-profile-banner-generator.json)**
  - **Descripción:** Este flujo automático permite crear un banner dinámico para Twitter combinando las imágenes de avatar de los seguidores más recientes con una imagen de fondo, utilizando la API OAuth1.0.
  - **Complejidad:** Media (12 nodos)

- **[1222-wikipedia-summarization-fl.json](workflows/1222-wikipedia-summarization-fl.json)**
  - **Descripción:** Este flujo automático utiliza Bright Data para extraer información de Wikipedia y Google Gemini AI para formatearla en un contenido legible e generar una resumen conciso.
  - **Complejidad:** Media (12 nodos)

- **[1454-create-dynamic-twitter-profile-banner.json](workflows/1454-create-dynamic-twitter-profile-banner.json)**
  - **Descripción:** Este flujo automatiza procesos utilizando Twitter/X con inteligencia artificial y APIs.
  - **Complejidad:** Media (12 nodos)

- **[1504-twitter-virtual-ai-influencer.json](workflows/1504-twitter-virtual-ai-influencer.json)**
  - **Descripción:** Este flujo permite generación de contenido utilizando OpenAI/GPT, Twitter/X con inteligencia artificial y APIs de forma programada.
  - **Complejidad:** Media (12 nodos)

- **[2661-youtube-transcripciones-resumen.json](workflows/2661-youtube-transcripciones-resumen.json)**
  - **Descripción:** Este flujo automático permite a un usuario enviar una URL de YouTube mediante Webhook para obtener su video ID y luego extraer el título y descripción del video. Posteriormente, se utiliza la transcripción del video junto con gpt-4o-mini para generar resúmenes estructurados con definiciones, características, detalles de implementación y ventajas/desventajas, formateados en markdown.
  - **Complejidad:** Media (12 nodos)

- **[3023-ai-whatsapp-support-bot.json](workflows/3023-ai-whatsapp-support-bot.json)**
  - **Descripción:** Este flujo automatiza un asistente de soporte al cliente en WhatsApp que utiliza inteligencia artificial para responder preguntas basadas en el contenido web de la empresa. Utiliza herramientas de crawling y análisis de páginas para obtener información precisa.
  - **Complejidad:** Media (12 nodos)

- **[0625-facebook_comments_flow.json](workflows/0625-facebook_comments_flow.json)**
  - **Descripción:** Este flujo obtiene los mensajes y comentarios más recientes de posts en una página de Facebook según la configuración inicial.
  - **Complejidad:** Media (11 nodos)

- **[1087-insta-chatbot-gpt.json](workflows/1087-insta-chatbot-gpt.json)**
  - **Descripción:** Este flujo permite integrar ChatGPT en Instagram mediante ManyChat para generar respuestas automatizadas.
  - **Complejidad:** Media (11 nodos)

- **[2623-wordpress-xmlrpc-posting.json](workflows/2623-wordpress-xmlrpc-posting.json)**
  - **Descripción:** Este flujo automático utiliza n8n junto con el protocolo XML-RPC para publicar artículos en WordPress.com.
  - **Complejidad:** Media (11 nodos)

- **[3212-cv-screening.json](workflows/3212-cv-screening.json)**
  - **Descripción:** Este flujo automático descarga un CV desde una URL, extrae su contenido PDF y envía la información junto con una descripción de trabajo a OpenAI para obtener una evaluación estructurada que determina el perfil del candidato en base a los requisitos del puesto.
  - **Complejidad:** Media (11 nodos)

- **[0329-blog-medium-publisher.json](workflows/0329-blog-medium-publisher.json)**
  - **Descripción:** Este flujo automático extrae contenido de blogs WordPress para publicar en Medium utilizando HTML y HTTP requests.
  - **Complejidad:** Media (10 nodos)

- **[0441-youtube-video-summarizer.json](workflows/0441-youtube-video-summarizer.json)**
  - **Descripción:** Este flujo automático permite obtener la transcripción de un video de YouTube y generar su resumen utilizando modelos de lenguaje.
  - **Complejidad:** Media (10 nodos)

- **[0472-workflow-wordpress-tts.json](workflows/0472-workflow-wordpress-tts.json)**
  - **Descripción:** Este flujo automático permite obtener un artículo de WordPress, generar su resumen o transcripción con una IA y convertirlo a audio para ser insertado como contenido multimedia en el mismo post.
  - **Complejidad:** Media (10 nodos)

- **[0858-tiktok-downloader-json.json](workflows/0858-tiktok-downloader-json.json)**
  - **Descripción:** Automático para descargar videos de TikTok sin el esticker de agua
  - **Complejidad:** Media (10 nodos)

- **[1090-upload-instagram-tiktok.json](workflows/1090-upload-instagram-tiktok.json)**
  - **Descripción:** Este flujo permite subir imágenes de forma automática a Instagram y TikTok utilizando el mismo endpoint.
  - **Complejidad:** Media (10 nodos)

- **[3178-youtube-summarizer.json](workflows/3178-youtube-summarizer.json)**
  - **Descripción:** Este flujo automatiza la resumen de videos de YouTube mediante la extracción de transcripciones y el uso de un motor de lenguaje para generar resúmenes concisos.
  - **Complejidad:** Media (10 nodos)

- **[0284-n8n-chat-conversational.json](workflows/0284-n8n-chat-conversational.json)**
  - **Descripción:** Este flujo permite a la conversación mantener contexto con los últimos mensajes gracias al almacenamiento en memoria buffer. Utiliza herramientas de búsqueda (SerpAPI) y Wikipedia para mejorar las respuestas del agente.
  - **Complejidad:** Media (9 nodos)

- **[0369-youtube-description-automation.json](workflows/0369-youtube-description-automation.json)**
  - **Descripción:** Este flujo automático permite añadir un texto predefinido a la descripción de todos tus videos de YouTube manteniendo el contenido original existente y verificando si es necesario realizar actualizaciones.
  - **Complejidad:** Media (9 nodos)

- **[0474-update-youtube-descriptions.json](workflows/0474-update-youtube-descriptions.json)**
  - **Descripción:** Este flujo automático permite insertar un texto específico entre dos líneas determinadas en las descripciones de todos los videos de YouTube. Se recogen primero todos los videos, luego para cada uno se obtiene su ID y se busca el texto a insertar basado en variables definidas previamente.
  - **Complejidad:** Media (9 nodos)

- **[0847-wp-ai-categorizer.json](workflows/0847-wp-ai-categorizer.json)**
  - **Descripción:** Este flujo automatiza la categorización de posts en WordPress usando modelos de lenguaje de OpenAI.
  - **Complejidad:** Media (9 nodos)

- **[0883-n8n-ai-categorize-wordpress.json](workflows/0883-n8n-ai-categorize-wordpress.json)**
  - **Descripción:** Esta plantilla automática utiliza la IA para asignar una única categoría a múltiples posts de WordPress basándose en su título.
  - **Complejidad:** Media (9 nodos)

- **[1051-youtube-video-summarizer.json](workflows/1051-youtube-video-summarizer.json)**
  - **Descripción:** Este flujo utiliza Searchapi.io junto con modelos de OpenAI y técnicas avanzadas de división de texto para extraer, procesar y generar un resumen completo sobre los contenidos de videos de YouTube especificados.
  - **Complejidad:** Media (9 nodos)

- **[1223-line-gratitude-reminder.json](workflows/1223-line-gratitude-reminder.json)**
  - **Descripción:** Este flujo automatizado envía a las 9:00 PM un mensaje personalizado generado por Azure OpenAI para motivar la reflexión sobre lo positivo del día mediante LINE.
  - **Complejidad:** Media (9 nodos)

- **[1441-auto-categorize-blog-posts-in-wordpress-using-ai.json](workflows/1441-auto-categorize-blog-posts-in-wordpress-using-ai.json)**
  - **Descripción:** Este flujo permite chatbot, automatización utilizando OpenAI/GPT, YouTube con inteligencia artificial y APIs.
  - **Complejidad:** Media (9 nodos)

- **[2666-ft-news-resumen.json](workflows/2666-ft-news-resumen.json)**
  - **Descripción:** Este flujo automatizado recoge diariamente noticias financieras de FT.com, las organiza mediante la extracción específica de contenidos utilizando CSS Selectors, las resumena con un modelo de Google Gemini en formato HTML y envía el resumen estructurado a una bandeja de Outlook.
  - **Complejidad:** Media (8 nodos)

- **[0496-gmail-news-to-linkedin.json](workflows/0496-gmail-news-to-linkedin.json)**
  - **Descripción:** Este flujo automático permite a un usuario recibir newsletters de Gmail y utilizar OpenAI para identificar las noticias principales, resumirlas y generar publicaciones para LinkedIn con un estilo inteligente y humor sutil.
  - **Complejidad:** Media (7 nodos)

- **[1459-dynamically-generate-a-webpage-from-openai.json](workflows/1459-dynamically-generate-a-webpage-from-openai.json)**
  - **Descripción:** Este flujo permite chatbot, generación de contenido utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (7 nodos)

- **[0072-medium-rss-feed.json](workflows/0072-medium-rss-feed.json)**
  - **Descripción:** Este flujo automático procesa RSS feeds de N8N desde Medium en lotes.
  - **Complejidad:** Media (6 nodos)

- **[0305-certificate-email-batch.json](workflows/0305-certificate-email-batch.json)**
  - **Descripción:** Este flujo automático lee un archivo CSV, lo divide en lotes y utiliza su contenido para enviar correos electrónicos con certificados generados previamente.
  - **Complejidad:** Media (6 nodos)

- **[0309-twitter-mentions-rocketchat.json](workflows/0309-twitter-mentions-rocketchat.json)**
  - **Descripción:** Este flujo verifica cada minuto en Twitter las menciones de '@n8n_io' y, si son nuevas, envía a RocketChat un mensaje con el texto del tweet y su URL.
  - **Complejidad:** Media (6 nodos)

- **[0688-youtube-raindrop-sync.json](workflows/0688-youtube-raindrop-sync.json)**
  - **Descripción:** Este flujo automático verifica cada 30 minutos la lista de reproducción especificada en YouTube y agrega los videos nuevos a Raindrop como marcadores con título compuesto por el nombre del propietario y el título del video, y etiqueta 'youtube'.
  - **Complejidad:** Media (6 nodos)

- **[1062-x-post-ai.json](workflows/1062-x-post-ai.json)**
  - **Descripción:** Este flujo automático publica automáticamente los últimos videos de YouTube en X/Twitter con texto generado por ChatGPT.
  - **Complejidad:** Media (6 nodos)

- **[1076-youtube-promotion-x.json](workflows/1076-youtube-promotion-x.json)**
  - **Descripción:** Este flujo automático verifica cada 30 minutos si hay nuevos videos en un canal de YouTube específico y utiliza ChatGPT para generar mensajes en X (antes Twitter) que promocionen dichos videos, manteniéndose bajo el límite de caracteres.
  - **Complejidad:** Media (6 nodos)

- **[1101-strapi-create-update.json](workflows/1101-strapi-create-update.json)**
  - **Descripción:** Este flujo automatizado permite crear una entrada en Strapi (posts), guardar su ID y luego actualizarla con un slug específico.
  - **Complejidad:** Media (6 nodos)

- **[1485-post-new-youtube-videos-to-x.json](workflows/1485-post-new-youtube-videos-to-x.json)**
  - **Descripción:** Este flujo permite chatbot, generación de contenido utilizando OpenAI/GPT, Twitter/X, YouTube con inteligencia artificial y APIs de forma programada.
  - **Complejidad:** Media (6 nodos)

- **[2564-twitter-hilo-automatizacion.json](workflows/2564-twitter-hilo-automatizacion.json)**
  - **Descripción:** Este flujo automatizado utiliza herramientas de Twitter y un modelo de lenguaje OpenAI para generar hilos coherentes e interactivos, manteniendo el contexto conversacional.
  - **Complejidad:** Media (6 nodos)

- **[2659-content-creator-agent.json](workflows/2659-content-creator-agent.json)**
  - **Descripción:** Este flujo automático utiliza la herramienta Tavily para buscar información en internet sobre un tema específico proporcionado por el usuario, y luego emplea un modelo de lenguaje Anthropic Chat Model para generar contenido HTML bien estructurado para blogs. Las conexiones aseguran que se realice primero una búsqueda en la web antes de solicitar al asistente IA que escriba el artículo.
  - **Complejidad:** Media (6 nodos)

- **[2710-youtube-sum-resumen.json](workflows/2710-youtube-sum-resumen.json)**
  - **Descripción:** Este flujo extrae el texto de un video de YouTube utilizando searchapi.io y lo resume con LangChain y OpenAI para generar resúmenes detallados con ejemplos de preguntas.
  - **Complejidad:** Media (6 nodos)

- **[0280-line-chatbot-agent.json](workflows/0280-line-chatbot-agent.json)**
  - **Descripción:** Este flujo automático utiliza un chatbot de LINE para manejar mensajes, almacenar el contexto en memoria buffer y acceder al modelo GPT-4o-mini de OpenAI. También integra la herramienta SerpAPI para búsqueda web.
  - **Complejidad:** Media (5 nodos)

- **[0368-youtube-upload-create-playlist.json](workflows/0368-youtube-upload-create-playlist.json)**
  - **Descripción:** Este flujo automático permite subir un video a YouTube y crear una lista de reproducción, añadiendo el ID del video recién cargado.
  - **Complejidad:** Media (5 nodos)

- **[0479-ideas-para-post.json](workflows/0479-ideas-para-post.json)**
  - **Descripción:** Este flujo automatizado lee ideas de una hoja de Google, genera un post para la plataforma especificada usando OpenAI y, si es Twitter, lo publica. Después actualiza la hoja con el texto del post.
  - **Complejidad:** Media (5 nodos)

- **[0628-perplexity-research.json](workflows/0628-perplexity-research.json)**
  - **Descripción:** Este flujo automatizado busca y extrae información relacionada con una consulta específica utilizando la API de Perplexity AI, formateando el resultado para obtener contenido limpio.
  - **Complejidad:** Media (5 nodos)

- **[0792-line-chatbot-memory-search.json](workflows/0792-line-chatbot-memory-search.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada utilizando la memoria del buffer, integrando la capacidad de búsqueda en web con SerpAPI y el modelo de lenguaje GPT-4o-mini.
  - **Complejidad:** Media (5 nodos)

- **[0918-humantic-profile-management.json](workflows/0918-humantic-profile-management.json)**
  - **Descripción:** Este flujo automático permite crear, actualizar y obtener un perfil de Humantic AI utilizando una URL de LinkedIn como entrada inicial.
  - **Complejidad:** Media (5 nodos)

- **[1027-facebook-long-lived-token.json](workflows/1027-facebook-long-lived-token.json)**
  - **Descripción:** Este flujo automático obtiene un token de acceso prolongado de Facebook a partir de parámetros configurados y luego lo utiliza para obtener tokens de página con ámbito de aplicación.
  - **Complejidad:** Media (5 nodos)

- **[1043-linkedin-url-discovery.json](workflows/1043-linkedin-url-discovery.json)**
  - **Descripción:** Este flujo busca y extrae URLs de LinkedIn en una hoja de Google específica para cada fila
  - **Complejidad:** Media (5 nodos)

- **[1470-generate-audio-from-text-using-openai-webhook-workflow.json](workflows/1470-generate-audio-from-text-using-openai-webhook-workflow.json)**
  - **Descripción:** Este flujo permite generación de contenido utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (5 nodos)

- **[2534-news-twitter-post.json](workflows/2534-news-twitter-post.json)**
  - **Descripción:** Este flujo automático busca noticias de inteligencia artificial mediante una consulta a Perplexity AI, genera un resumen formateado para Twitter/X y lo publica directamente en la plataforma.
  - **Complejidad:** Media (5 nodos)

- **[0031-webflow-crear-y-actualizar.json](workflows/0031-webflow-crear-y-actualizar.json)**
  - **Descripción:** Este flujo permite crear e actualizar un elemento en la colección de Webflow mediante una activación manual.
  - **Complejidad:** Baja (4 nodos)

- **[0064-twitter-if-trigger.json](workflows/0064-twitter-if-trigger.json)**
  - **Descripción:** Este flujo automático ejecuta un mensaje fijo en Twitter cuando se activa mediante un clic manual o por la evaluación de una condición numérica que depende del índice de iteración ($runIndex), pasando luego a nodos NoOp y Twitter según los resultados.
  - **Complejidad:** Baja (4 nodos)

- **[0134-tweet-image-jokes.json](workflows/0134-tweet-image-jokes.json)**
  - **Descripción:** Este flujo automático ejecuta una tarea cada día a las 17:00 horas para obtener chistes gráficos desde la API de Blablagues y luego los publica en Twitter utilizando imágenes.
  - **Complejidad:** Baja (4 nodos)

- **[0195-ghost-post-automation.json](workflows/0195-ghost-post-automation.json)**
  - **Descripción:** Este flujo automático permite crear un post en Ghost, actualizar su estado a publicado y luego obtener información sobre el post creado.
  - **Complejidad:** Baja (4 nodos)

- **[0312-wordpress-csv-export.json](workflows/0312-wordpress-csv-export.json)**
  - **Descripción:** Este flujo automatizado extrae y exporta todos los artículos de WordPress a un archivo CSV.
  - **Complejidad:** Baja (4 nodos)

- **[0427-zoom-wordpress-schedule.json](workflows/0427-zoom-wordpress-schedule.json)**
  - **Descripción:** Este flujo automático programa una nueva reunión de Zoom cada 360 días y actualiza un post en WordPress con su URL.
  - **Complejidad:** Baja (4 nodos)

- **[1246-twitter-banner-update.json](workflows/1246-twitter-banner-update.json)**
  - **Descripción:** Este flujo permite descargar una imagen de Unsplash y actualizarla como banner en Twitter mediante peticiones HTTP.
  - **Complejidad:** Baja (4 nodos)

- **[1506-update-twitter-banner-using-http-request.json](workflows/1506-update-twitter-banner-using-http-request.json)**
  - **Descripción:** Este flujo automatiza procesos utilizando Twitter/X con inteligencia artificial y APIs.
  - **Complejidad:** Baja (4 nodos)

- **[2608-youtube-transcript-extractor.json](workflows/2608-youtube-transcript-extractor.json)**
  - **Descripción:** Este flujo permite extraer y limpiar el texto transcritto de un vídeo de YouTube usando la API de RapidAPI.
  - **Complejidad:** Baja (4 nodos)

- **[0052-release-content-publisher.json](workflows/0052-release-content-publisher.json)**
  - **Descripción:** Este flujo automático permite obtener y publicar todos los contenidos cuyo nombre comienza con 'release' utilizando Storyblok.
  - **Complejidad:** Baja (3 nodos)

- **[0530-workflow-bloqueo-medio-dev-to.json](workflows/0530-workflow-bloqueo-medio-dev-to.json)**
  - **Descripción:** Este flujo automatizado permite enviar artículos tanto a la plataforma Medium como al API de dev.to mediante una solicitud HTTP, utilizando credenciales configuradas para ambas acciones.
  - **Complejidad:** Baja (3 nodos)

- **[0636-wp-post-automation.json](workflows/0636-wp-post-automation.json)**
  - **Descripción:** Este flujo automático crea un nuevo post en WordPress y actualiza inmediatamente el contenido después.
  - **Complejidad:** Baja (3 nodos)

- **[0657-linkedin-automation.json](workflows/0657-linkedin-automation.json)**
  - **Descripción:** Este flujo automatizado descarga una imagen de la URL especificada y publica esa imagen en LinkedIn junto a un mensaje predefinido.
  - **Complejidad:** Baja (3 nodos)

- **[1170-html-to-pdf-conversor.json](workflows/1170-html-to-pdf-conversor.json)**
  - **Descripción:** Este flujo automático convierte contenido HTML recibido en una solicitud de webhook en un archivo PDF y responde con él.
  - **Complejidad:** Baja (3 nodos)

- **[0306-twake-message-trigger.json](workflows/0306-twake-message-trigger.json)**
  - **Descripción:** Este flujo automático se activa manualmente y envía un mensaje vacío a Twake sin especificar contenido ni canal.
  - **Complejidad:** Baja (2 nodos)

- **[0551-manual-aws-sns-trigger.json](workflows/0551-manual-aws-sns-trigger.json)**
  - **Descripción:** Este flujo manual permite enviar un mensaje predefinido a una topic específica de AWS SNS al hacer clic en el botón 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[0553-aws-ses-email.json](workflows/0553-aws-ses-email.json)**
  - **Descripción:** Este flujo automático permite enviar un correo electrónico predefinido a través de AWS SES cuando se ejecuta manualmente.
  - **Complejidad:** Baja (2 nodos)

- **[0555-manual-aws-lambda-test.json](workflows/0555-manual-aws-lambda-test.json)**
  - **Descripción:** Este flujo manual permite desencadenar un AWS Lambda específico mediante una acción clic.
  - **Complejidad:** Baja (2 nodos)

- **[0583-wordpress-get-all.json](workflows/0583-wordpress-get-all.json)**
  - **Descripción:** Este flujo permite ejecutar manualmente una acción que obtiene todos los artículos desde una instancia de WordPress mediante sus credenciales API.
  - **Complejidad:** Baja (2 nodos)

- **[0647-contentful-get-all.json](workflows/0647-contentful-get-all.json)**
  - **Descripción:** Este flujo automático permite obtener todos los elementos de contenido desde una instancia de Contentful mediante un desencadenador manual.
  - **Complejidad:** Baja (2 nodos)

- **[0687-medium-publication.json](workflows/0687-medium-publication.json)**
  - **Descripción:** Este flujo permite publicar artículos en una publicación de Medium.
  - **Complejidad:** Baja (2 nodos)

- **[0746-strava-twitter-tweet.json](workflows/0746-strava-twitter-tweet.json)**
  - **Descripción:** Este flujo automático monitorea nuevas actividades de ciclismo en Strava y publica un tweet en Twitter con detalles sobre la distancia recorrida y el nombre del ejercicio.
  - **Complejidad:** Baja (2 nodos)

- **[0533-digitalocean-create-droplet.json](workflows/0533-digitalocean-create-droplet.json)**
  - **Descripción:** Este flujo automático crea una instancia Droplet en DigitalOcean usando los parámetros especificados y autenticándose con un token de acceso personal.
  - **Complejidad:** Baja (1 nodos)


### E-commerce y Pagos

- **[0826-ai-woocommerce-support-agent.json](workflows/0826-ai-woocommerce-support-agent.json)**
  - **Descripción:** Este flujo automatizado implementa un asistente de IA con n8n y WooCommerce para gestionar consultas de clientes sobre sus pedidos, asegurando privacidad mediante encriptación del correo electrónico y integrando funciones como DHL.
  - **Complejidad:** Alta (40 nodos)

- **[3077-shopify-to-d365-sync.json](workflows/3077-shopify-to-d365-sync.json)**
  - **Descripción:** Este flujo sincroniza órdenes de Shopify con Dynamics 365 Business Central creando pedidos y facturas. Detecta si las órdenes son de POS o web para generar respectivamente facturas o pedidos, verifica existencia de clientes y crea nuevos si no están en BC. Maneja ubicaciones multi-tienda y adiciona impuestos y descuentos como líneas.
  - **Complejidad:** Alta (39 nodos)

- **[0487-shopify-fulfillment-auto.json](workflows/0487-shopify-fulfillment-auto.json)**
  - **Descripción:** Este flujo automático busca filtrar y obtener las ordenes pendientes de fulfillment en Shopify para digital downloads o gift cards.
  - **Complejidad:** Media (13 nodos)

- **[2640-shopify-orders-to-baserow.json](workflows/2640-shopify-orders-to-baserow.json)**
  - **Descripción:** Este flujo automático ejecuta un GraphQL query diaria para obtener órdenes de Shopify y las inserta en una tabla basada en Baserow, extrayendo los parámetros UTM del primer visit. Solo se procesan las órdenes donde el campo 'Campaign' está presente.
  - **Complejidad:** Media (12 nodos)

- **[2558-bee-hiiv-gumroad-subscribers.json](workflows/2558-bee-hiiv-gumroad-subscribers.json)**
  - **Descripción:** Este flujo automatiza la adición de suscriptores a una newsletter de Beehiiv cada vez que se realiza una venta en Gumroad.
  - **Complejidad:** Media (10 nodos)

- **[0002-Gumroad-MailerLite-trigger.json](workflows/0002-Gumroad-MailerLite-trigger.json)**
  - **Descripción:** Este flujo automático añade un suscriptor a MailerLite cuando se produce una venta en Gumroad y lo asigna inmediatamente a un grupo específico.
  - **Complejidad:** Media (8 nodos)

- **[0403-stripe-checkout-filters.json](workflows/0403-stripe-checkout-filters.json)**
  - **Descripción:** Este flujo automático recupera todas las sesiones de checkout de Stripe del último mes y permite filtrarlas basándose en campos personalizados como nickname o job_title.
  - **Complejidad:** Media (7 nodos)

- **[2650-shopify-odoo-customer-sync.json](workflows/2650-shopify-odoo-customer-sync.json)**
  - **Descripción:** Este flujo sincroniza automáticamente los nuevos clientes de Shopify con contactos en Odoo, verificando primero si ya existe un contacto coincidente y creándolo si no se encuentra.
  - **Complejidad:** Media (5 nodos)

- **[0260-woo-product-flow.json](workflows/0260-woo-product-flow.json)**
  - **Descripción:** Este flujo automático permite crear un producto en WooCommerce, actualizar su stock y luego obtener el producto creado.
  - **Complejidad:** Baja (4 nodos)

- **[0027-chargebee-nuevo-cliente.json](workflows/0027-chargebee-nuevo-cliente.json)**
  - **Descripción:** Este flujo automático permite crear un nuevo cliente en Chargebee al ejecutar la tarea manual.
  - **Complejidad:** Baja (2 nodos)

- **[0140-onfleet-shopify-task.json](workflows/0140-onfleet-shopify-task.json)**
  - **Descripción:** Este flujo automático sincroniza la creación de un nuevo cumplimiento en Shopify con la generación correspondiente de una tarea en Onfleet.
  - **Complejidad:** Baja (2 nodos)

- **[0167-shopify-onfleet-tags-sync.json](workflows/0167-shopify-onfleet-tags-sync.json)**
  - **Descripción:** Este flujo automático actualiza las etiquetas de un producto en Shopify cada vez que se detecta una demora en una tarea de Onfleet.
  - **Complejidad:** Baja (2 nodos)

- **[0535-pay-pal-batch-operation.json](workflows/0535-pay-pal-batch-operation.json)**
  - **Descripción:** Este flujo ejecuta una operación en la cuenta de PayPal utilizando el ID del lote proporcionado.
  - **Complejidad:** Baja (2 nodos)

- **[0585-shopify-get-all-records.json](workflows/0585-shopify-get-all-records.json)**
  - **Descripción:** Este flujo ejecuta manualmente el desencadenador 'execute' que luego obtiene todos los registros de una cuenta Shopify.
  - **Complejidad:** Baja (2 nodos)

- **[0587-paddle-coupon-creator.json](workflows/0587-paddle-coupon-creator.json)**
  - **Descripción:** Este flujo automático permite crear una oferta de cupón en Paddle utilizando parámetros específicos.
  - **Complejidad:** Baja (2 nodos)

- **[0049-chargebee-event-trigger.json](workflows/0049-chargebee-event-trigger.json)**
  - **Descripción:** Este flujo automático recibe actualizaciones para cualquier evento en Chargebee.
  - **Complejidad:** Baja (1 nodos)

- **[0495-gumroad-sale-trigger.json](workflows/0495-gumroad-sale-trigger.json)**
  - **Descripción:** Este flujo automático se activa cuando ocurre una venta en Gumroad.
  - **Complejidad:** Baja (1 nodos)

- **[0584-shopify-order-trigger.json](workflows/0584-shopify-order-trigger.json)**
  - **Descripción:** Este flujo activo se dispara cuando se crea un nuevo pedido en Shopify mediante webhook.
  - **Complejidad:** Baja (1 nodos)


### Inteligencia Artificial y Procesamiento de Lenguaje Natural (NLP)

- **[2667-auto-doc-gpt-docsify.json](workflows/2667-auto-doc-gpt-docsify.json)**
  - **Descripción:** Este flujo automático genera documentación en Markdown para workflows de n8n utilizando GPT y Docsify, permitiendo crear páginas interactivas con esquemas visuales (Mermaid) que describen cada nodo.
  - **Complejidad:** Alta (60 nodos)

- **[3063-animated_stories_generator.json](workflows/3063-animated_stories_generator.json)**
  - **Descripción:** Este flujo crea historias animadas utilizando GPT-4o-mini para generar prompts, Midjourney para crear imágenes y Kling para generar videos, posteriormente combine los videos en Creatomate.
  - **Complejidad:** Alta (51 nodos)

- **[2924-hacker_news_video_creator.json](workflows/2924-hacker_news_video_creator.json)**
  - **Descripción:** Este flujo automatiza la creación de videos a partir de noticias de Hacker News. Recoge los artículos, los analiza para determinar su relevancia, genera imágenes con Leonardo AI y RunwayML, y crea un video con Creatomate.
  - **Complejidad:** Alta (48 nodos)

- **[2996-perplexity_to_html.json](workflows/2996-perplexity_to_html.json)**
  - **Descripción:** Este flujo automatiza la creación de una página HTML a partir de investigación de Perplexity, estructurando y estilizando con Tailwind CSS.
  - **Complejidad:** Alta (47 nodos)

- **[2777-encuesta-analisis.json](workflows/2777-encuesta-analisis.json)**
  - **Descripción:** Este flujo automatiza la obtención de encuestas y análisis usando OpenAI y Qdrant para extraer见解s mediante clustering y embeddings.
  - **Complejidad:** Alta (42 nodos)

- **[2828-organizador-tags.json](workflows/2828-organizador-tags.json)**
  - **Descripción:** Este flujo automático organiza workflows en carpetas específicas basadas en tags. Primero, inicia sesión en n8n, extrae los tags de los proyectos personales, permite seleccionarlos mediante un formulario y luego mueve los workflows a las carpetas correspondientes o crea nuevas si son necesarias.
  - **Complejidad:** Alta (40 nodos)

- **[3108-subworkflow-dependency-graph.json](workflows/3108-subworkflow-dependency-graph.json)**
  - **Descripción:** Este flujo automatiza la creación de un grafo de dependencias entre workflows en n8n y asigna etiquetas automáticamente basadas en las relaciones detectadas. Analiza los flujos para identificar cuáles son llamados por otros, visualiza estas relaciones y crea nuevas etiquetas si detecta cambios.
  - **Complejidad:** Alta (40 nodos)

- **[0787-n8n-ai-demo-multifunction.json](workflows/0787-n8n-ai-demo-multifunction.json)**
  - **Descripción:** Este flujo automático utiliza la plataforma n8n para construir un sistema de IA multifuncional que incluye procesamiento de PDFs mediante embeddings y text splitting, así como chatbot con QA basado en documentos usando el modelo GPT-4o. También integra una funcionalidad para programar citas.
  - **Complejidad:** Alta (39 nodos)

- **[0912-adaptive-rag-strategy.json](workflows/0912-adaptive-rag-strategy.json)**
  - **Descripción:** Este flujo analiza y clasifica consultas en categorías específicas (Fáctica, Analítica, de Opinión o Contextual) para aplicar estrategias adaptativas de recuperación e inteligencia artificial que optimicen la obtención de información relevante.
  - **Complejidad:** Alta (39 nodos)

- **[2776-pdf-pinecone-reserva.json](workflows/2776-pdf-pinecone-reserva.json)**
  - **Descripción:** Flujo que incluye la descarga de un PDF, su embedding y almacenamiento en Pinecone, además de una capacidad de reserva de citas mediante Google Calendar usando agentes de lenguaje como GPT-4o y Anthropic.
  - **Complejidad:** Alta (39 nodos)

- **[2823-anthropic-batch-processing.json](workflows/2823-anthropic-batch-processing.json)**
  - **Descripción:** Este flujo automático envía múltiples prompts simultáneamente a la API de Anthropic Claude Batch, verifica su estado y procesa los resultados utilizando记忆节点 para mantener el contexto.
  - **Complejidad:** Alta (39 nodos)

- **[2755-social-media-crawler.json](workflows/2755-social-media-crawler.json)**
  - **Descripción:** Este flujo extrae información de medios sociales de sitios web usando herramientas de recuperación de texto y URLs. Navega por páginas, obtiene enlaces sociales y los organiza en formato JSON.
  - **Complejidad:** Alta (38 nodos)

- **[2771-tax-code-ai-assistant.json](workflows/2771-tax-code-ai-assistant.json)**
  - **Descripción:** Este flujo automatiza la creación de un asistente chatbot legal especializado en códigos fiscales texanos. Descarga, procesa y almacena documentos PDF en Qdrant usando embeddings de Mistral.ai para permitir búsquedas avanzadas.
  - **Complejidad:** Alta (38 nodos)

- **[1150-spotify-playlist-classifier.json](workflows/1150-spotify-playlist-classifier.json)**
  - **Descripción:** Este flujo automático permite clasificar y añadir tracks de Spotify en múltiples playlists basándose en sus características e historial de reproducción mediante la utilización del modelo Claude 3.5.
  - **Complejidad:** Alta (37 nodos)

- **[2807-automatiza-categorizacion-outlook.json](workflows/2807-automatiza-categorizacion-outlook.json)**
  - **Descripción:** Este flujo automatiza la categorización de correos electrónicos en Outlook utilizando un agente de inteligencia artificial. Extrae el cuerpo del correo, lo procesa para eliminar HTML y luego lo envía a un modelo de lenguaje Ollama para asignar categorías. Si falla, registra el error. Dependiendo de la categoría resultante, mueve los correos a diferentes carpetas como 'Junk', 'Receipt', 'SaaS', 'Community', 'Business' u 'Action'.
  - **Complejidad:** Alta (36 nodos)

- **[3150-whatsapp-ai-responder.json](workflows/3150-whatsapp-ai-responder.json)**
  - **Descripción:** Este flujo automático gestiona mensajes de WhatsApp usando IA para responder de manera profesional. Analiza diferentes tipos de mensajes (texto, audio, video e imagen), los procesa con herramientas como Google Gemini y Wikipedia, y genera respuestas oportunas.
  - **Complejidad:** Alta (35 nodos)

- **[3202-whatsapp-bot-process.json](workflows/3202-whatsapp-bot-process.json)**
  - **Descripción:** Este flujo automático procesa mensajes de WhatsApp, maneja diferentes tipos como audio, video e imagen utilizando Google Gemini para transcripción y análisis, y utiliza un agente de inteligencia artificial para responder.
  - **Complejidad:** Alta (35 nodos)

- **[2545-visual-regression-testing.json](workflows/2545-visual-regression-testing.json)**
  - **Descripción:** Este flujo automático permite realizar pruebas de regresión visual en páginas web utilizando Apify para capturar imágenes y modelos de lenguaje visuales como Gemini para detectar cambios entre versiones.
  - **Complejidad:** Alta (34 nodos)

- **[2794-visual-regression-test-flow.json](workflows/2794-visual-regression-test-flow.json)**
  - **Descripción:** Flujo automatizado para realizar pruebas de regresión visual en sitios web usando Google Gemini y Apify. Genera imágenes base, las compara con capturas recientes e informa cambios detectados a través de Linear.
  - **Complejidad:** Alta (34 nodos)

- **[3076-ai-seo-keyword-automation.json](workflows/3076-ai-seo-keyword-automation.json)**
  - **Descripción:** Este flujo automático utiliza inteligencia artificial para realizar una investigación de palabras clave SEO. Incluye la expansión de temas, análisis de competidores, métricas como volumen de búsqueda y CPC, y genera una estrategia final optimizada.
  - **Complejidad:** Alta (34 nodos)

- **[3237-ai_magic_position.json](workflows/3237-ai_magic_position.json)**
  - **Descripción:** Este flujo incluye un agente AI con capacidades de memoria y recuperación vectorial, conectado a OpenAI y herramientas HTTP para posicionar flujos.
  - **Complejidad:** Alta (34 nodos)

- **[0715-ai-calendar-mcp.json](workflows/0715-ai-calendar-mcp.json)**
  - **Descripción:** Este flujo de trabajo n8n utiliza un agente de IA con OpenAI para gestionar interacciones conversacionales relacionadas con el calendario Google Calendar. Permite crear, buscar, actualizar y eliminar eventos, así como modificar texto entre mayúsculas y minúsculas mediante herramientas que responden a comandos.
  - **Complejidad:** Alta (32 nodos)

- **[2894-onboarding-clientes.json](workflows/2894-onboarding-clientes.json)**
  - **Descripción:** Este flujo automatiza el onboarding de nuevos clientes enviando un correo de bienvenida y agendando una llamada con un asesor de cuenta asignado.
  - **Complejidad:** Alta (31 nodos)

- **[0718-crypto-news-sentiment-bot.json](workflows/0718-crypto-news-sentiment-bot.json)**
  - **Descripción:** Este flujo automático analiza la consulta del usuario para extraer una palabra clave, busca noticias relacionadas en múltiples fuentes RSS de criptomonedas y utiliza GPT-4o para sintetizar información y evaluar el sentimiento del mercado.
  - **Complejidad:** Alta (30 nodos)

- **[2954-financial-documents-assistant.json](workflows/2954-financial-documents-assistant.json)**
  - **Descripción:** Este flujo monitorea un directorio local para documentos financieros y sincroniza los cambios con Qdrant usando Mistral.ai para crear un asistente de preguntas y respuestas.
  - **Complejidad:** Alta (29 nodos)

- **[3282-analisis_medios_gemini.json](workflows/3282-analisis_medios_gemini.json)**
  - **Descripción:** Este flujo utiliza diferentes metodologías para analizar medios como imágenes y PDFs empleando agentes de inteligencia artificial. Incluye rutas específicas para análisis de imágenes individuales y en=batch, uso de prompts personalizados, transformación a formato base64 y llamadas directas a la API de Gemini.
  - **Complejidad:** Alta (28 nodos)

- **[0779-rag-movie-recom-qdrant-openai.json](workflows/0779-rag-movie-recom-qdrant-openai.json)**
  - **Descripción:** Este flujo automático implementa un chatbot de IA basado en RAG para recomendar películas utilizando Qdrant como almacenamiento vectorial y OpenAI para embeddings e interacción.
  - **Complejidad:** Alta (27 nodos)

- **[0877-rag-peliculas-recomendacion-qdrant.json](workflows/0877-rag-peliculas-recomendacion-qdrant.json)**
  - **Descripción:** Este flujo automático permite a un chatbot recomendar películas mediante el uso de almacenamiento vectorial Qdrant y embeddings generados con OpenAI para análisis de consulta del usuario.
  - **Complejidad:** Alta (27 nodos)

- **[1112-openai-n8n-examples.json](workflows/1112-openai-n8n-examples.json)**
  - **Descripción:** Este flujo n8n contiene ejemplos de cómo utilizar diferentes modelos y APIs de OpenAI para generar resúmenes (TLDR), traducir texto, crear prompts para imágenes y más.
  - **Complejidad:** Alta (27 nodos)

- **[1395-call-processor.json](workflows/1395-call-processor.json)**
  - **Descripción:** Procesa grabaciones de llamadas y extrae información.
  - **Complejidad:** Alta (27 nodos)

- **[3100-openai-examples.json](workflows/3100-openai-examples.json)**
  - **Descripción:** Este flujo utiliza diferentes modelos de OpenAI como ChatGPT para resumir y traducir texto, Whisper-1 para transcripción de audio y DALLE-2 para generar imágenes a partir de descripciones textuales.
  - **Complejidad:** Alta (27 nodos)

- **[0821-email-ai-auto-responder.json](workflows/0821-email-ai-auto-responder.json)**
  - **Descripción:** Este flujo automático analiza correos electrónicos entrantes utilizando DeepSeek y OpenAI para resumirlos e identificar el tema. Si la clasificación detecta que es una solicitud sobre la empresa, se genera una respuesta estructurada profesionalmente basándose en información de Qdrant.
  - **Complejidad:** Alta (26 nodos)

- **[1007-comprador-personalizado-IA-RAG.json](workflows/1007-comprador-personalizado-IA-RAG.json)**
  - **Descripción:** Este flujo utiliza OpenAI y RAG para crear un asistente personalizado que responde a consultas sobre productos o información general del negocio.
  - **Complejidad:** Alta (25 nodos)

- **[2993-paul_graham_essays_milvus.json](workflows/2993-paul_graham_essays_milvus.json)**
  - **Descripción:** Este flujo automatiza la extracción y almacenamiento de artículos de Paul Graham en Milvus, utilizando OpenAI para generar respuestas con citas contextuales.
  - **Complejidad:** Alta (25 nodos)

- **[3139-AppointmentQualifierAI.json](workflows/3139-AppointmentQualifierAI.json)**
  - **Descripción:** Flujo de formulario que utiliza inteligencia artificial para calificar solicitudes de citas y administra la aprobación de las mismas mediante formularios integrados en n8n.
  - **Complejidad:** Alta (25 nodos)

- **[0905-whatsapp-chatbot-rag.json](workflows/0905-whatsapp-chatbot-rag.json)**
  - **Descripción:** Este flujo automático configura un chatbot de WhatsApp impulsado por IA que utiliza RAG (Retrieval-Augmented Generation) con OpenAI para mantener conversaciones contextualesizadas.
  - **Complejidad:** Alta (24 nodos)

- **[0914-website-chatbot-n8n.json](workflows/0914-website-chatbot-n8n.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de n8n mantener conversaciones con clientes, verificar disponibilidad en agenda mediante Microsoft Outlook API y enviar respuestas estructuradas. El agente AI utiliza el modelo GPT-4o para procesar consultas y tomar decisiones sobre citas o envíos de mensajes.
  - **Complejidad:** Alta (24 nodos)

- **[0936-ai-grant-tracker.json](workflows/0936-ai-grant-tracker.json)**
  - **Descripción:** Este flujo automatizado permite filtrar y analizar oportunidades de subvenciones relacionadas con IA en grants.gov. Usa nodos para eliminar duplicados mediante un sistema de seguimiento, solicita información detallada sobre cada subvención a través del API de grants.gov e incorpora modelos generativos de OpenAI para determinar la elegibilidad y facilitar el proceso.
  - **Complejidad:** Alta (24 nodos)

- **[1452-complete-business-whatsapp-ai-powered-openai.json](workflows/1452-complete-business-whatsapp-ai-powered-openai.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Webhook, WhatsApp con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (24 nodos)

- **[0814-elevenlabs-voice-rag-chatbot.json](workflows/0814-elevenlabs-voice-rag-chatbot.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de ElevenLabs mantener conversaciones en voz con los clientes utilizando documentos vectorizados y una memoria contextualizada.
  - **Complejidad:** Alta (23 nodos)

- **[2749-spotify-downloads-manager.json](workflows/2749-spotify-downloads-manager.json)**
  - **Descripción:** Este flujo automático gestiona una playlist de Spotify llamada 'Downloads'. Busca las canciones más recientes que el usuario haya marcado como favoritas y las agrega a la playlist, manteniendo solo un número definido de canciones. Si la playlist no existe, la crea. Si ya existe, elimina las canciones más antiguas si el límite se supera.
  - **Complejidad:** Alta (23 nodos)

- **[2757-automatiza-rfp.json](workflows/2757-automatiza-rfp.json)**
  - **Descripción:** Flujo automático para generar respuestas a RFPs utilizando Webhooks, Google Docs y OpenAI. Recibe un documento RFP, extrae las preguntas, las procesa con AI e inserta las respuestas en un documento de Google Docs.
  - **Complejidad:** Alta (23 nodos)

- **[0895-chat-pdf-ai-citas.json](workflows/0895-chat-pdf-ai-citas.json)**
  - **Descripción:** Este flujo automático permite a un chatbot analizar documentos PDF utilizando embeddings de OpenAI y recuperar información relevante con citas exactas cuando se consulta.
  - **Complejidad:** Alta (22 nodos)

- **[0946-dynamically_switch_llms_customer_support.json](workflows/0946-dynamically_switch_llms_customer_support.json)**
  - **Descripción:** Este flujo de n8n selecciona y utiliza dinámicamente diferentes modelos de lenguaje (como OpenAI) basados en un índice para generar respuestas polivalentes e iterar hasta encontrar una que cumpla con los criterios especificados, como el tono cortés.
  - **Complejidad:** Alta (22 nodos)

- **[0780-milvus-paul-graham-essays.json](workflows/0780-milvus-paul-graham-essays.json)**
  - **Descripción:** Este flujo permite crear un conocimiento base con embeddings de OpenAI a partir de ensayos recientes de Paul Graham, almacenando los vectores en una colección de Milvus.
  - **Complejidad:** Alta (21 nodos)

- **[0932-podcast-summary-flow.json](workflows/0932-podcast-summary-flow.json)**
  - **Descripción:** Este flujo automático permite a los usuarios recibir un resumen diario de podcasts top según género específico mediante transcripción e inteligencia artificial.
  - **Complejidad:** Alta (21 nodos)

- **[1103-plex-qbittorrent-automation.json](workflows/1103-plex-qbittorrent-automation.json)**
  - **Descripción:** Este flujo automatiza el control de velocidad y gestión de descargas en QBittorrent basado en eventos webhooks de Plex, permitiendo configurar límites de velocidad o realizar acciones específicas como pausar/retomar torrents según la acción recibida.
  - **Complejidad:** Alta (21 nodos)

- **[2893-imagen-style-transfer.json](workflows/2893-imagen-style-transfer.json)**
  - **Descripción:** Este flujo genera imágenes basadas en un estilo de imagen fuente utilizando Google Imagen 3.0 y Gemini 2.0 para describir el estilo. Los usuarios proporcionan una URL de imagen fuente y un prompt de imagen objetivo a través de un formulario, luego se valida la entrada y se descarga la imagen fuente. La imagen se analiza con Gemini 2.0 para obtener una descripción detallada del estilo visual, que se combina con el prompt del usuario para generar nuevas imágenes con Imagen 3.0. Las imágenes generadas se suben a Cloudinary y se envían al correo electrónico si el usuario lo especifica.
  - **Complejidad:** Alta (21 nodos)

- **[3075-video-narration-ai.json](workflows/3075-video-narration-ai.json)**
  - **Descripción:** Este flujo automatiza la creación de un guion narrativo para videos utilizando inteligencia artificial multimodal. Descarga un video, extrae marcos均匀mente distribuidos, los procesa con un modelo de lenguaje grande (LLM) para generar textos descriptivos y luego convierte ese texto en audio.
  - **Complejidad:** Alta (21 nodos)

- **[3203-video-narration-generator.json](workflows/3203-video-narration-generator.json)**
  - **Descripción:** Este flujo automatiza la creación de un guion narrativo para videos usando OpenAI y luego genera un audio a partir de dicho guion.
  - **Complejidad:** Alta (21 nodos)

- **[3317-agendamiento-citas-ai.json](workflows/3317-agendamiento-citas-ai.json)**
  - **Descripción:** Este flujo automático utiliza Gmail y Google Calendar para analizar correos electrónicos que soliciten una cita, revisar la disponibilidad en el calendario y proponer horarios libres mediante un agente de inteligencia artificial.
  - **Complejidad:** Alta (21 nodos)

- **[2795-banco-estado-pdf-to-markdown.json](workflows/2795-banco-estado-pdf-to-markdown.json)**
  - **Descripción:** Este flujo automatiza la conversión de un estado bancario PDF en formato imágenes a texto estructurado en markdown usando Google Gemini y OCR avanzado.
  - **Complejidad:** Alta (20 nodos)

- **[3012-web-query-semantic-re-ranking.json](workflows/3012-web-query-semantic-re-ranking.json)**
  - **Descripción:** Este flujo automatiza la realización de consultas web y reordena los resultados semanticamente usando Brave y Google Gemini para mejorar la relevancia.
  - **Complejidad:** Alta (20 nodos)

- **[3159-trustpilot-sentiment.json](workflows/3159-trustpilot-sentiment.json)**
  - **Descripción:** Este flujo extrae y analiza opiniones de Trustpilot usando DeepSeek para obtener información detallada y luego OpenAI para evaluar el sentimiento.
  - **Complejidad:** Alta (20 nodos)

- **[0795-realtime-meeting-transcriber.json](workflows/0795-realtime-meeting-transcriber.json)**
  - **Descripción:** Este flujo automatiza la transcripción de reuniones en tiempo real utilizando Recall.ai e integra las notas generadas con un chatbot de OpenAI para insights.
  - **Complejidad:** Alta (19 nodos)

- **[2531-etsy-product-scraper.json](workflows/2531-etsy-product-scraper.json)**
  - **Descripción:** Este flujo automático utiliza Bright Data Web Unlocker para realizar scraping avanzado en Etsy y extrae información detallada de productos usando Google Gemini Flash con base en los resultados obtenidos.
  - **Complejidad:** Alta (19 nodos)

- **[2943-auto-label-gmail.json](workflows/2943-auto-label-gmail.json)**
  - **Descripción:** Este flujo automatiza la asignación de etiquetas a mensajes nuevos en Gmail utilizando inteligencia artificial. Recoge los correos, los procesa con un modelo de lenguaje para determinar las etiquetas adecuadas y luego las aplica.
  - **Complejidad:** Alta (19 nodos)

- **[3342-web_agent_airtop.json](workflows/3342-web_agent_airtop.json)**
  - **Descripción:** Este flujo configura un agente web que utiliza Airtop para interactuar con una ventana del navegador, incluyendo abrir URLs, hacer clics y consultar páginas web siguiendo instrucciones dadas por el usuario. El agente también utiliza Claude 3.5 de Anthropic para procesar las interacciones.
  - **Complejidad:** Alta (19 nodos)

- **[0333-bored-api-activity-tool.json](workflows/0333-bored-api-activity-tool.json)**
  - **Descripción:** Este flujo permite a un agente AI llamar a un subflujo para extraer información sobre tipo y número de participantes, luego usar esa información para filtrar actividades mediante la Bored API y devolver el resultado combinado en una respuesta del chatbot.
  - **Complejidad:** Alta (18 nodos)

- **[0713-bright-data-gemini-chat-enhancement.json](workflows/0713-bright-data-gemini-chat-enhancement.json)**
  - **Descripción:** Este flujo permite a la IA de Gemini incorporar resultados de búsqueda en tiempo real de Google, Bing o Yandex para mejorar las respuestas del chatbot.
  - **Complejidad:** Alta (18 nodos)

- **[0937-detect-hallucinations-ollama.json](workflows/0937-detect-hallucinations-ollama.json)**
  - **Descripción:** Este flujo analiza textos para identificar afirmaciones incorrectas utilizando un modelo especializado de Ollama llamado bespoke-minicheck. Procesa el texto dividiéndolo en frases manteniendo elementos estructurales como fechas y listas, luego extrae las 'afirmaciones' (facts) para su verificación mediante cadenas LLM.
  - **Complejidad:** Alta (18 nodos)

- **[2880-calendario_openai_report.json](workflows/2880-calendario_openai_report.json)**
  - **Descripción:** Este flujo automatiza la investigación de asistentes y empresas utilizando API de OpenAI, recolecta información de calendario Google y envía un informe detallado por correo electrónico.
  - **Complejidad:** Alta (18 nodos)

- **[3323-hr-automatizacion.json](workflows/3323-hr-automatizacion.json)**
  - **Descripción:** Este flujo automático gestiona la automatización del proceso de selección de personal mediante la extracción de información clave de los CVs, el análisis con inteligencia artificial y la consolidación de resultados en una hoja de cálculo.
  - **Complejidad:** Alta (18 nodos)

- **[0876-image-search-workflow.json](workflows/0876-image-search-workflow.json)**
  - **Descripción:** Este flujo automático permite buscar imágenes basadas en objetos detectados utilizando inteligencia artificial, CDN y ElasticSearch para almacenar y consultar eficientemente los resultados.
  - **Complejidad:** Alta (17 nodos)

- **[0950-dsp-ai-tutor.json](workflows/0950-dsp-ai-tutor.json)**
  - **Descripción:** Este flujo n8n actúa como un asistente de tutoría para estudiantes de procesamiento de señales, utilizando modelos de OpenAI y Google Gemini para guiarles interactivamente mediante explicaciones teóricas, soluciones numéricas o referencias a memoria.
  - **Complejidad:** Alta (17 nodos)

- **[0958-image-caption-overlay.json](workflows/0958-image-caption-overlay.json)**
  - **Descripción:** Este flujo automático descarga una imagen usando HTTP Request, la redimensiona para optimizarla en AI y le añade un caption punny (título ingenioso) generado por Gemini 1.5 Pro.
  - **Complejidad:** Alta (16 nodos)

- **[1439-ask-questions-about-a-pdf-using-ai.json](workflows/1439-ask-questions-about-a-pdf-using-ai.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Alta (16 nodos)

- **[2793-image-caption-generator.json](workflows/2793-image-caption-generator.json)**
  - **Descripción:** Este flujo automatiza la generación de subtítulos en imágenes usando el modelo Gemini y los aplica visualmente.
  - **Complejidad:** Alta (16 nodos)

- **[2830-outlook-calendar-agent.json](workflows/2830-outlook-calendar-agent.json)**
  - **Descripción:** Este flujo utiliza un agente de inteligencia artificial para manejar consultas relacionadas con el calendario de Outlook. El usuario puede hacer preguntas sobre eventos calendarísticos y el agente, equipado con herramientas de Outlook, responderá apropiadamente.
  - **Complejidad:** Alta (16 nodos)

- **[3072-ollama-llm-router.json](workflows/3072-ollama-llm-router.json)**
  - **Descripción:** Este flujo configura una ruta automática de LLM privada y local usando Ollama para seleccionar dinámicamente el modelo más apropiado basado en la entrada del usuario.
  - **Complejidad:** Alta (16 nodos)

- **[0546-thehive-email-iocs.json](workflows/0546-thehive-email-iocs.json)**
  - **Descripción:** Este flujo automático procesa correos electrónicos entrantes mediante IMAP, los analiza con Cortex para detectar indicaciones de compromiso (IoCs), y crea observables correspondientes en TheHive para cada tipo de IoC identificado.
  - **Complejidad:** Media (15 nodos)

- **[0662-brave-search-chatbot.json](workflows/0662-brave-search-chatbot.json)**
  - **Descripción:** Este flujo de trabajo implementa un chatbot que utiliza GPT-4o y herramientas MCP para realizar búsquedas web en Brave, manteniendo memoria contextualizada.
  - **Complejidad:** Media (15 nodos)

- **[0813-voice-ai-chat.json](workflows/0813-voice-ai-chat.json)**
  - **Descripción:** Este flujo automático integra Webhook para entradas de voz en tiempo real, gestión de memoria contextualizada con modelos como Google Gemini y ElevenLabs.
  - **Complejidad:** Media (15 nodos)

- **[1163-strava_ai_coaching_analysis.json](workflows/1163-strava_ai_coaching_analysis.json)**
  - **Descripción:** Este flujo automatizado analiza actividades deportivas desde Strava utilizando una IA conversacional basada en Google Gemini para ofrecer consejos personalizados como entrenador triatlón y envía un resumen formateado por correo electrónico.
  - **Complejidad:** Media (15 nodos)

- **[1219-paul_graham_essays_resumer.json](workflows/1219-paul_graham_essays_resumer.json)**
  - **Descripción:** Este flujo automatizado extrae las URLs de ensayos recientes de Paul Graham a partir de una lista de artículos, luego obtiene el texto completo de cada ensayo y lo resumirá usando GPT.
  - **Complejidad:** Media (15 nodos)

- **[2549-semanal-shodan-thehive.json](workflows/2549-semanal-shodan-thehive.json)**
  - **Descripción:** Este flujo automático programa un escaneo semanal de direcciones IP y sus puertos específicos usando Shodan. Si encuentra servicios o comportamientos no esperados, genera una alerta en TheHive para su gestión.
  - **Complejidad:** Media (15 nodos)

- **[2550-3d-character-generation.json](workflows/2550-3d-character-generation.json)**
  - **Descripción:** Este flujo automático crea videos de rotación en 3D y modelos figurines a partir de imágenes, utilizando las API de PiAPI para generar diseños de personajes mediante Midjourney e integrarlas con herramientas como GPT-4o.
  - **Complejidad:** Media (15 nodos)

- **[2677-reddit-n8n-monitor.json](workflows/2677-reddit-n8n-monitor.json)**
  - **Descripción:** Este flujo automatiza la monitorización de posts en Reddit relacionados con n8n, utilizando OpenAI para clasificar y resumir los que sean relevantes.
  - **Complejidad:** Media (15 nodos)

- **[2696-country_capitals_fiction.json](workflows/2696-country_capitals_fiction.json)**
  - **Descripción:** Este flujo utiliza ChatGPT para responder preguntas sobre capitales de países ficticios. El usuario puede pedir una lista de países o la capital de un país específico.
  - **Complejidad:** Media (15 nodos)

- **[2809-seo-ai-keywords-generator.json](workflows/2809-seo-ai-keywords-generator.json)**
  - **Descripción:** Flujo que genera keywords SEO utilizando un agente de inteligencia artificial basado en el perfil del cliente ideal (ICP).
  - **Complejidad:** Media (15 nodos)

- **[3147-reddit-n8n-analizador.json](workflows/3147-reddit-n8n-analizador.json)**
  - **Descripción:** Este flujo recolecta y analiza publicaciones recientes de Reddit relacionadas con n8n, usando OpenAI para clasificar y resumir los posts.
  - **Complejidad:** Media (15 nodos)

- **[3188-ai-voice-chat.json](workflows/3188-ai-voice-chat.json)**
  - **Descripción:** Este flujo implementa un chatbot de voz que utiliza Webhook, Memory Manager, OpenAI, Google Gemini y ElevenLabs para mantener una conversación contextualizada con el usuario. El proceso incluye transcribir audio, almacenar y recuperar contexto, generar respuestas con inteligencia artificial y convertirlas en audio.
  - **Complejidad:** Media (15 nodos)

- **[0461-milvus-rag-chatbot-flow.json](workflows/0461-milvus-rag-chatbot-flow.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada utilizando documentos PDF insertados en Milvus y consultas RAG con embeddings de Cohere.
  - **Complejidad:** Media (14 nodos)

- **[0893-chat-ai-contexto.json](workflows/0893-chat-ai-contexto.json)**
  - **Descripción:** Este flujo automatizado permite mantener una conversación contextualizada con el asistente de OpenAI mediante la gestión de mensajes anteriores.
  - **Complejidad:** Media (14 nodos)

- **[1450-chatgpt-automatic-code-review-in-gitlab-mr.json](workflows/1450-chatgpt-automatic-code-review-in-gitlab-mr.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (14 nodos)

- **[2632-line-chatbot-memory.json](workflows/2632-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener conversaciones contextualesizadas utilizando el modelo GPT-4o-mini y acceder a información mediante herramientas como Wikipedia, Google Calendar y Gmail.
  - **Complejidad:** Media (14 nodos)

- **[2669-ollama-chat-ai.json](workflows/2669-ollama-chat-ai.json)**
  - **Descripción:** Este flujo procesa mensajes de chat mediante modelos de lenguaje locales en Ollama y devuelve respuestas estructuradas en JSON.
  - **Complejidad:** Media (14 nodos)

- **[2969-chatbot_line.json](workflows/2969-chatbot_line.json)**
  - **Descripción:** Este flujo de trabajo configura un chatbot en LINE que muestra una animación de cargando al recibir un mensaje y utiliza un agente de IA con CBT para responder a los usuarios. Si el mensaje no es texto, envía un aviso.
  - **Complejidad:** Media (14 nodos)

- **[3066-generar_fondo_grafico.json](workflows/3066-generar_fondo_grafico.json)**
  - **Descripción:** Este flujo utiliza Midjourney, GPT-4o-mini y Canvas API para generar un fondo de pantalla gráfico con una copia emotiva. Primero, GPT-4o-mini genera un texto basado en el tema y escenario proporcionados, luego Midjourney crea una imagen según la descripción, y finalmente Canvas diseña la composición final con texto y elementos visuales.
  - **Complejidad:** Media (14 nodos)

- **[3183-ollama-chat-flow.json](workflows/3183-ollama-chat-flow.json)**
  - **Descripción:** Este flujo procesa mensajes de chat utilizando el modelo Llama 3.2 de Ollama a través de una cadena básica de LLM para generar respuestas estructuradas en formato JSON.
  - **Complejidad:** Media (14 nodos)

- **[3230-gemini-bounding-box.json](workflows/3230-gemini-bounding-box.json)**
  - **Descripción:** Este flujo utiliza la API de Gemini 2.0 para detectar objetos en imágenes y dibujar cajas envolventes personalizadas.
  - **Complejidad:** Media (14 nodos)

- **[0987-line-chatbot-llm-extraction.json](workflows/0987-line-chatbot-llm-extraction.json)**
  - **Descripción:** Este flujo automatizado utiliza un modelo LLM self-hosted (Mistral Nemo) para extraer información personal de los mensajes recibidos en LINE, analizando y estructurando la respuesta según un esquema JSON predefinido.
  - **Complejidad:** Media (13 nodos)

- **[2811-gmail-auto-label.json](workflows/2811-gmail-auto-label.json)**
  - **Descripción:** Automatiza la categorización de correo electrónico en Gmail usando OpenAI para etiquetar mensajes basándose en existentes o crear nuevas etiquetas si es necesario.
  - **Complejidad:** Media (13 nodos)

- **[2888-automatizacion-ticket.json](workflows/2888-automatizacion-ticket.json)**
  - **Descripción:** Este flujo automatiza la generación y triaje de tickets.watch para esto, utiliza Gmail para extraer mensajes de soporte, OpenAI para triajear y etiquetar cada ticket, y Linear.app para crear un.issue basado en los resultados.ai
  - **Complejidad:** Media (13 nodos)

- **[2989-motion-illustration.json](workflows/2989-motion-illustration.json)**
  - **Descripción:** Este flujo genera una ilustración animada usando Midjourney y Kling API. Primero crea una imagen con Midjourney, luego espera y procesa el estado para generar un video con Kling, finalmente devuelve la URL del video sin marca de agua.
  - **Complejidad:** Media (13 nodos)

- **[3007-travel-agent-couchbase-vector.json](workflows/3007-travel-agent-couchbase-vector.json)**
  - **Descripción:** Este flujo utiliza Google Gemini 2.0 Flash y OpenAI para crear un agente de planificación de viajes con capacidad de búsqueda vectorial en Couchbase, permitiendo buscar y almacenar puntos de interés.
  - **Complejidad:** Media (13 nodos)

- **[3043-three-view-to-video.json](workflows/3043-three-view-to-video.json)**
  - **Descripción:** Convierte proyecciones ortográficas tridimensionales en video animado dinámico utilizando GPT-4o e Kling para generar imágenes y vídeos.
  - **Complejidad:** Media (13 nodos)

- **[0544-n8n-daily-ai-news.json](workflows/0544-n8n-daily-ai-news.json)**
  - **Descripción:** Este flujo automático busca artículos relacionados con inteligencia artificial (IA) usando las APIs de NewsAPI y GNews, los fusiona y utiliza GPT-4 para resumirlos y traducirlos al chino tradicional manteniendo términos técnicos en inglés.
  - **Complejidad:** Media (12 nodos)

- **[0901-linear-bugs-classifier.json](workflows/0901-linear-bugs-classifier.json)**
  - **Descripción:** Este flujo automatizado clasifica nuevos bugs en Linear utilizando OpenAI GPT-4 para determinar el equipo correcto basado en una lista predefinida de responsabilidades y actualiza o notifica si no se encuentra un destino adecuado.
  - **Complejidad:** Media (12 nodos)

- **[1022-gmail-ai-auto-responder.json](workflows/1022-gmail-ai-auto-responder.json)**
  - **Descripción:** Este flujo automático analiza los correos entrantes y decide si es necesario responder mediante inteligencia artificial de OpenAI, creando bocetos en Gmail para conversaciones.
  - **Complejidad:** Media (12 nodos)

- **[1029-seo-onpage-audit.json](workflows/1029-seo-onpage-audit.json)**
  - **Descripción:** Este flujo analiza el SEO on-page de una landing page utilizando modelos GPT para generar informes detallados.
  - **Complejidad:** Media (12 nodos)

- **[1031-open-meteo-ai-chat.json](workflows/1031-open-meteo-ai-chat.json)**
  - **Descripción:** Este flujo automático utiliza funciones (Tools) de Open-Meteo API con ChatGPT para determinar la ubicación exacta de una ciudad solicitada por el usuario y, posteriormente, utilizar esas coordenadas para generar un pronóstico meteorológico detallado.
  - **Complejidad:** Media (12 nodos)

- **[1032-ai-agents-http-tool.json](workflows/1032-ai-agents-http-tool.json)**
  - **Descripción:** Este flujo permite a los usuarios solicitar actividades o información mediante una consulta a IA, utilizando herramientas HTTP integradas que simplifican las llamadas de API.
  - **Complejidad:** Media (12 nodos)

- **[1136-linear-ai-classification.json](workflows/1136-linear-ai-classification.json)**
  - **Descripción:** Este flujo automático clasifica tickets de bugs en Linear usando una IA (OpenAI) y asigna el equipo responsable según sus áreas de trabajo. El ticket se analiza, la IA determina el equipo adecuado y este se actualiza en Linear.
  - **Complejidad:** Media (12 nodos)

- **[1208-pdf-image-extractor.json](workflows/1208-pdf-image-extractor.json)**
  - **Descripción:** Este flujo automático extrae imágenes de PDFs, analiza cada imagen con el modelo GPT-4o y genera un documento de texto integrando los resultados.
  - **Complejidad:** Media (12 nodos)

- **[1234-twitter-ai-influencer-schedule.json](workflows/1234-twitter-ai-influencer-schedule.json)**
  - **Descripción:** Este flujo automatizado genera y publica tweets periódicamente utilizando inteligencia artificial para mantener un estilo de influencer específico.
  - **Complejidad:** Media (12 nodos)

- **[1431-ai-chat-with-any-data-workflow.json](workflows/1431-ai-chat-with-any-data-workflow.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT con inteligencia artificial y APIs.
  - **Complejidad:** Media (12 nodos)

- **[1476-integrating-ai-with-open-meteo-api.json](workflows/1476-integrating-ai-with-open-meteo-api.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (12 nodos)

- **[2613-airflow-dag-monitor.json](workflows/2613-airflow-dag-monitor.json)**
  - **Descripción:** Este flujo automático permite iniciar una ejecución de un DAG en Airflow mediante una API y verificar su estado para tomar acciones según sea necesario.
  - **Complejidad:** Media (12 nodos)

- **[0394-manejador-errores.json](workflows/0394-manejador-errores.json)**
  - **Descripción:** Este flujo verifica si un workflow está activo y no tiene configurado un manejador de errores. Si es así, actualiza sus ajustes asignando el ID del manejador de error predeterminado mediante una llamada a la API.
  - **Complejidad:** Media (11 nodos)

- **[0443-comparativo-llm-pdf.json](workflows/0443-comparativo-llm-pdf.json)**
  - **Descripción:** Este flujo automatizado permite probar y comparar la capacidad de los modelos Gemini 2.0 Flash y Claude 3.5 Sonnet para extraer información directamente desde PDFs utilizando credenciales predefinidas.
  - **Complejidad:** Media (11 nodos)

- **[0505-openai-image-generation-edit.json](workflows/0505-openai-image-generation-edit.json)**
  - **Descripción:** Este flujo de trabajo permite generar una imagen inicial usando la API de OpenAI, convertirla en formato binario y luego editarla añadiendo elementos como cuernos mediante la misma API.
  - **Complejidad:** Media (11 nodos)

- **[0917-email-drafting-fastmail-openai.json](workflows/0917-email-drafting-fastmail-openai.json)**
  - **Descripción:** Este flujo automático analiza correos electrónicos no leídos de un buzón IMAP mediante la API de Fastmail y genera respuestas utilizando modelos como GPT-4, guardando los borradores en una carpeta específica.
  - **Complejidad:** Media (11 nodos)

- **[0925-cv-screening-openai.json](workflows/0925-cv-screening-openai.json)**
  - **Descripción:** Este flujo automatizado analiza currículums en PDF utilizando la API de OpenAI, creando evaluaciones estructuradas con una puntuación porcentual y resúmenes detallados.
  - **Complejidad:** Media (11 nodos)

- **[1003-ia-output-parser.json](workflows/1003-ia-output-parser.json)**
  - **Descripción:** Este flujo fuerza a las IAs a utilizar un formato de salida específico mediante parsers estructurados o autofijantes, garantizando respuestas organizadas y validadas.
  - **Complejidad:** Media (11 nodos)

- **[2801-email-reply-draft.json](workflows/2801-email-reply-draft.json)**
  - **Descripción:** Este flujo automático utiliza OpenAI para generar respuestas a correos electrónicos y los guarda en la bandeja de borradores de Fastmail.
  - **Complejidad:** Media (11 nodos)

- **[2921-ai-agent-charts-generator.json](workflows/2921-ai-agent-charts-generator.json)**
  - **Descripción:** Este flujo permite a un agente de inteligencia artificial generar gráficos personalizados en conversaciones usando OpenAI Structured Output para definir configuraciones de gráficos Chart.js y Quickchart.io.
  - **Complejidad:** Media (11 nodos)

- **[0516-email-classification-ai.json](workflows/0516-email-classification-ai.json)**
  - **Descripción:** Este flujo procesa correos electrónicos, clasifica en categorías específicas usando modelos de OpenAI y extrae información relevante sobre las candidatas.
  - **Complejidad:** Media (10 nodos)

- **[0772-generador_3d_figurine.json](workflows/0772-generador_3d_figurine.json)**
  - **Descripción:** Este flujo utiliza Midjourney para generar imágenes base y GPT-4o para crear vistas ortográficas de personajes en 3D.
  - **Complejidad:** Media (10 nodos)

- **[1427-ai-agent-with-ollama-for-current-weather-and-wiki.json](workflows/1427-ai-agent-with-ollama-for-current-weather-and-wiki.json)**
  - **Descripción:** Este flujo permite chatbot con inteligencia artificial y APIs.
  - **Complejidad:** Media (10 nodos)

- **[1501-text-automations-using-apple-shortcuts-1.json](workflows/1501-text-automations-using-apple-shortcuts-1.json)**
  - **Descripción:** Este flujo permite automatización, resumen utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (10 nodos)

- **[2657-calendar-agent.json](workflows/2657-calendar-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con el calendario del usuario, creando eventos individuales o con asistentes, obteniendo los horarios y eliminándolos. El agente conversacional de Google Calendar utiliza modelos GPT para manejar las solicitudes.
  - **Complejidad:** Media (10 nodos)

- **[2994-gemini-video-analysis.json](workflows/2994-gemini-video-analysis.json)**
  - **Descripción:** Este flujo analiza videos utilizando la API de Gemini AI. Descarga un video, lo sube a los servidores de Google y genera una descripción detallada mediante el modelo Gemini-2.0-flash-exp.
  - **Complejidad:** Media (10 nodos)

- **[3199-text_automation.json](workflows/3199-text_automation.json)**
  - **Descripción:** Flujo para automatizar tareas de traducción y edición de texto usando Apple Shortcuts y OpenAI. Analiza el tipo de solicitud, realiza la acción correspondiente con GPT-4 Mini y responde al Shortcut.
  - **Complejidad:** Media (10 nodos)

- **[3332-text-automations-shortcuts.json](workflows/3332-text-automations-shortcuts.json)**
  - **Descripción:** Este flujo utiliza Apple Shortcuts para enviar textos a un webhook y usar OpenAI para realizar diferentes tareas como traducir, corregir gramática o ajustar el largo del texto.
  - **Complejidad:** Media (10 nodos)

- **[1458-discord-ai-powered-bot.json](workflows/1458-discord-ai-powered-bot.json)**
  - **Descripción:** Este flujo permite chatbot, resumen utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (9 nodos)

- **[2595-line-chatbot-ai.json](workflows/2595-line-chatbot-ai.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener conversaciones mediante el uso de Groq y Llama3, enviando mensajes entrantes como solicitudes a la IA para generar respuestas.
  - **Complejidad:** Media (9 nodos)

- **[0664-tts-openai.json](workflows/0664-tts-openai.json)**
  - **Descripción:** Este flujo permite la conversión de texto en voz mediante el servicio de síntesis hablada de OpenAI.
  - **Complejidad:** Media (8 nodos)

- **[0909-openai-tts-manual.json](workflows/0909-openai-tts-manual.json)**
  - **Descripción:** Este flujo permite convertir texto en voz mediante la API de OpenAI con un proceso manual.
  - **Complejidad:** Media (8 nodos)

- **[1508-use-openrouter-in-n8n-versions-_178.json](workflows/1508-use-openrouter-in-n8n-versions-_178.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (8 nodos)

- **[2959-centroid_calculator.json](workflows/2959-centroid_calculator.json)**
  - **Descripción:** Este flujo calcula el centroide de un conjunto de vectores. Recibe una solicitud GET con un array de vectores, valida que sean consistentes y calcula su centroid.
  - **Complejidad:** Media (8 nodos)

- **[0956-html-generator.json](workflows/0956-html-generator.json)**
  - **Descripción:** Este flujo utiliza OpenAI Structured Output junto con n8n para generar dinámicamente páginas HTML basadas en solicitudes de usuario, usando un esquema JSON predefinido y Tailwind CSS como framework.
  - **Complejidad:** Media (7 nodos)

- **[0981-html-generator.json](workflows/0981-html-generator.json)**
  - **Descripción:** Este flujo automático permite generar dinámicamente páginas HTML completas basadas en solicitudes de usuario utilizando la estructura definida por OpenAI. El proceso envía el texto del usuario a la API de GPT-4o-mini con un esquema JSON específico, luego convierte esa respuesta JSON en HTML completo.
  - **Complejidad:** Media (7 nodos)

- **[1055-line-chatbot-search.json](workflows/1055-line-chatbot-search.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE buscar información en la web cuando el usuario hace consultas, utilizando herramientas como SearchAPI.io y modelos LLM como OpenAI.
  - **Complejidad:** Media (7 nodos)

- **[3169-siri_ai_agent.json](workflows/3169-siri_ai_agent.json)**
  - **Descripción:** Flujo que utiliza Siri para activar un agente de OpenAI a través de Apple Shortcuts, procesando comandos de voz y generando respuestas.
  - **Complejidad:** Media (7 nodos)

- **[3177-email-to-line-summarizer.json](workflows/3177-email-to-line-summarizer.json)**
  - **Descripción:** Este flujo automatiza la lectura de correos electrónicos, los resume con inteligencia artificial y los envía al mensajero LINE.
  - **Complejidad:** Media (7 nodos)

- **[0157-line-syncro-timer-sync.json](workflows/0157-line-syncro-timer-sync.json)**
  - **Descripción:** Este flujo automático sincroniza entradas de tiempo en Syncro a partir de una webhook que recibe información sobre llamadas telefónicas desde un chatbot.
  - **Complejidad:** Media (6 nodos)

- **[0334-line-chatbot-memory.json](workflows/0334-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automatizado procesa mensajes de chat en LINE utilizando memoria contextualizada para mantener un historial significativo y llama al asistente especificado para generar respuestas.
  - **Complejidad:** Media (6 nodos)

- **[0367-tweets-publicador.json](workflows/0367-tweets-publicador.json)**
  - **Descripción:** Este flujo automático extrae y publica los últimos Tweets almacenados en una hoja de Google llamada 'Tweets' cada 6 horas.
  - **Complejidad:** Media (6 nodos)

- **[0378-elevenlabs-text-to-speech.json](workflows/0378-elevenlabs-text-to-speech.json)**
  - **Descripción:** Este flujo verifica parámetros de entrada y utiliza la API de ElevenLabs para generar respuestas de voz a partir del texto proporcionado.
  - **Complejidad:** Media (6 nodos)

- **[0447-perplexity-ai-chat.json](workflows/0447-perplexity-ai-chat.json)**
  - **Descripción:** Este flujo automatizado envía una solicitud al API de Perplexity AI usando la clave proporcionada, incluyendo parámetros como prompt y dominios para filtrado.
  - **Complejidad:** Media (6 nodos)

- **[0513-email-tracking-pixel.json](workflows/0513-email-tracking-pixel.json)**
  - **Descripción:** Este flujo automatizado permite detectar cuando se abre un correo electrónico mediante el envío de una imagen PNG transparente a través de webhook, capturando parámetros como userId para identificar al remitente.
  - **Complejidad:** Media (6 nodos)

- **[0691-openai-image-gen.json](workflows/0691-openai-image-gen.json)**
  - **Descripción:** Este flujo automático utiliza la API de OpenAI ImageGen v1 para editar imágenes y generar una nueva versión basada en el prompt proporcionado.
  - **Complejidad:** Media (6 nodos)

- **[1013-openai-image-generation.json](workflows/1013-openai-image-generation.json)**
  - **Descripción:** Este flujo automático permite generar múltiples imágenes utilizando el modelo GPT-4 para imágenes de OpenAI a través de su API.
  - **Complejidad:** Media (6 nodos)

- **[1018-elevenlabs-tts-api.json](workflows/1018-elevenlabs-tts-api.json)**
  - **Descripción:** Este flujo automático permite generar audio de texto utilizando la API de Elevenlabs mediante webhooks, verificando primero que se proporcionen correctamente los parámetros 'voice_id' y 'text'.
  - **Complejidad:** Media (6 nodos)

- **[1057-analisis-feedback-ia.json](workflows/1057-analisis-feedback-ia.json)**
  - **Descripción:** Este flujo procesa comentarios de clientes, analiza el feedback con inteligencia artificial para obtener un resumen, sugerencias de mejora e ideas para posteos sociales, y luego envía los resultados por correo a la dirección del equipo.
  - **Complejidad:** Media (6 nodos)

- **[1086-perplexity-api-query.json](workflows/1086-perplexity-api-query.json)**
  - **Descripción:** Este flujo automático consulta a la API de Perplexity AI utilizando el modelo Sonar con un prompt del sistema y una solicitud del usuario, y luego procesa limpiamente la respuesta.
  - **Complejidad:** Media (6 nodos)

- **[0012-typeform-feedback-route.json](workflows/0012-typeform-feedback-route.json)**
  - **Descripción:** Este flujo analiza respuestas de formularios Typeform y las clasifica en hojas de cálculo de Google según si el valor numérico 'usefulness' es mayor o igual a 3.
  - **Complejidad:** Media (5 nodos)

- **[0364-documentacion-n8n-automatica.json](workflows/0364-documentacion-n8n-automatica.json)**
  - **Descripción:** Este flujo automático permite a los usuarios generar documentación de sus workflows n8n utilizando la API de OpenAI.
  - **Complejidad:** Media (5 nodos)

- **[0442-transform-image-to-lego-line.json](workflows/0442-transform-image-to-lego-line.json)**
  - **Descripción:** Este flujo automático permite recibir una imagen por un webhook de LINE, analizarla con GPT-4O-MINI para crear el prompt adecuado en DALL-E 3, generar la imagen alegorada como si estuviera hecha de LEGO y finalmente enviar esta nueva imagen al usuario mediante Line.
  - **Complejidad:** Media (5 nodos)

- **[0489-line-n8n-assistant.json](workflows/0489-line-n8n-assistant.json)**
  - **Descripción:** Este flujo implementa un asistente de IA en n8n que responde a mensajes de LINE utilizando modelos GPT y herramientas MCP.
  - **Complejidad:** Media (5 nodos)

- **[0515-auto-iniciar-flujos-n8n.json](workflows/0515-auto-iniciar-flujos-n8n.json)**
  - **Descripción:** Este flujo permite iniciar manualmente dos instancias de ejecución en n8n mediante el trigger. La descripción explica que estos flujos no se inician automáticamente después de importar, a menos que tengan la etiqueta 'Auto start' y estén configurados para autodesplegar.
  - **Complejidad:** Media (5 nodos)

- **[0675-clockify-proyecto-entrada-tiempo.json](workflows/0675-clockify-proyecto-entrada-tiempo.json)**
  - **Descripción:** Este flujo automático crea un proyecto en Clockify con detalles específicos y luego agrega una entrada de tiempo usando ese proyecto, manteniendo la coherencia del contexto.
  - **Complejidad:** Media (5 nodos)

- **[0845-openai-image-generator.json](workflows/0845-openai-image-generator.json)**
  - **Descripción:** Este workflow permite generar imágenes utilizando la API de OpenAI basándose en inputs proporcionados mediante formularios.
  - **Complejidad:** Media (5 nodos)

- **[0892-ollama-n8n-chat.json](workflows/0892-ollama-n8n-chat.json)**
  - **Descripción:** Este flujo permite interactuar con modelos de lenguaje locales (administrados por Ollama) a través de una interfaz de chat.
  - **Complejidad:** Media (5 nodos)

- **[1068-openai-tts-audio-generation.json](workflows/1068-openai-tts-audio-generation.json)**
  - **Descripción:** Este flujo permite generar audio a partir de texto utilizando la API de Text-to-Speech (TTS) de OpenAI. Se configura un webhook para recibir solicitudes POST que incluyen el texto a convertir.
  - **Complejidad:** Media (5 nodos)

- **[1429-ai-agent-chat.json](workflows/1429-ai-agent-chat.json)**
  - **Descripción:** Este flujo permite chatbot utilizando OpenAI/GPT, Webhook con inteligencia artificial mediante webhooks y APIs.
  - **Complejidad:** Media (5 nodos)

- **[3185-transform-image-to-lego.json](workflows/3185-transform-image-to-lego.json)**
  - **Descripción:** Este flujo transforma una imagen recibida a través de LINE en un estilo LEGO utilizando la API de DALL-E.
  - **Complejidad:** Media (5 nodos)

- **[0045-google-books-automation.json](workflows/0045-google-books-automation.json)**
  - **Descripción:** Este flujo automático obtiene información de un volumen específico y lo añade a una estantería en la API de Google Books mediante secuencia de llamadas con autenticación OAuth2.
  - **Complejidad:** Baja (4 nodos)

- **[0178-thehive-case-management.json](workflows/0178-thehive-case-management.json)**
  - **Descripción:** Este flujo automático permite crear, actualizar y obtener un caso en TheHive mediante secuencia de pasos conectados.
  - **Complejidad:** Baja (4 nodos)

- **[0289-mistral-cadena-hf.json](workflows/0289-mistral-cadena-hf.json)**
  - **Descripción:** Este flujo utiliza una cadena LLM básica conectada al modelo Mistral-7B-Instruct-v0.1 de Hugging Face junto con opciones de generación como temperatura y penalización.
  - **Complejidad:** Baja (4 nodos)

- **[0181-cortex-abuse-detector.json](workflows/0181-cortex-abuse-detector.json)**
  - **Descripción:** Este flujo analiza una URL utilizando el nodo de Abuse Finder en Cortex, y luego obtiene los detalles del trabajo usando la ID devuelta.
  - **Complejidad:** Baja (3 nodos)

- **[0534-speech-recognition-wit-ai.json](workflows/0534-speech-recognition-wit-ai.json)**
  - **Descripción:** Este flujo automatizado utiliza el nodo Read Binary File para leer un archivo WAV en la ruta especificada y lo envía a la API de Wit.ai mediante una solicitud HTTP POST para procesamiento.
  - **Complejidad:** Baja (2 nodos)

- **[1192-json-array-splitter.json](workflows/1192-json-array-splitter.json)**
  - **Descripción:** Este flujo de trabajo toma una entrada inicial que contiene una lista JSON y la expande en múltiples flujos, cada uno con un elemento individual del array para su posterior procesamiento.
  - **Complejidad:** Baja (2 nodos)

- **[0184-thehive-event-monitor.json](workflows/0184-thehive-event-monitor.json)**
  - **Descripción:** Este flujo monitoriza todos los eventos en el sistema TheHive y desencadena una acción cuando ocurre alguno.
  - **Complejidad:** Baja (1 nodos)


### Web Scraping y Extracción de Datos

- **[0990-google-trends-automatizacion.json](workflows/0990-google-trends-automatizacion.json)**
  - **Descripción:** Este flujo automático analiza los resultados de Google Trends, filtra por tráfico mínimo y resultados máximos, luego extrae información de artículos relacionados mediante scraping con Jina.ai. Si las condiciones se cumplen (por ejemplo: tráfico adecuado y nuevos términos), guarda la información en una hoja de Google para su seguimiento.
  - **Complejidad:** Alta (26 nodos)

- **[2802-webhook-relay.json](workflows/2802-webhook-relay.json)**
  - **Descripción:** Este flujo automático utiliza webhook.site para recibir y almacenar requests, posteriormente los procesa y reenvía a una dirección local mediante n8n. Se usa un token de autenticación y una clave para sincronizar el estado entre ejecuciones.
  - **Complejidad:** Alta (18 nodos)

- **[2885-reddit-business-opportunities.json](workflows/2885-reddit-business-opportunities.json)**
  - **Descripción:** Este flujo automatiza la extracción y análisis de publicaciones de Reddit relevantes para oportunidades empresariales, aplicando filtros y generando resúmenes con LLM.
  - **Complejidad:** Alta (17 nodos)

- **[2591-chatbot-jina-scraper.json](workflows/2591-chatbot-jina-scraper.json)**
  - **Descripción:** Este flujo automático permite a un chatbot integrar web scraping en tiempo real mediante Jina.ai para responder consultas de manera inteligente.
  - **Complejidad:** Media (9 nodos)

- **[0490-mediamarkt-deals.json](workflows/0490-mediamarkt-deals.json)**
  - **Descripción:** Este flujo automático procesa y envía ofertas de productos clasificadas por categoría mediante scraping web.
  - **Complejidad:** Media (8 nodos)

- **[2627-whatsapp-webhook-echo.json](workflows/2627-whatsapp-webhook-echo.json)**
  - **Descripción:** Este flujo de trabajo verifica un webhook con una solicitud GET y responde a POST Requests que contienen mensajes del usuario, enviando estos mensajes como respuestas en WhatsApp.
  - **Complejidad:** Media (8 nodos)

- **[0680-firecrawl-markdown-extractor.json](workflows/0680-firecrawl-markdown-extractor.json)**
  - **Descripción:** Este flujo automático utiliza FireCrawl para realizar un scrapeo web a partir de una URL proporcionada, formateando el resultado como texto markdown para facilitar su uso en aplicaciones y agentes.
  - **Complejidad:** Baja (4 nodos)

- **[2529-firecrawl-tool.json](workflows/2529-firecrawl-tool.json)**
  - **Descripción:** Este flujo permite a cualquier usuario enviar URLs para obtener respuestas de la API de Firecrawl y mantenerlas como campos editables en el contexto del workflow.
  - **Complejidad:** Baja (4 nodos)

- **[2975-conversion-rate-optimizer.json](workflows/2975-conversion-rate-optimizer.json)**
  - **Descripción:** Este flujo automatiza la optimización de tasa de conversión analizando una página de aterrizaje mediante el scraping y utilizando un agente de IA para realizar un análisis crítico y proponer mejoras específicas.
  - **Complejidad:** Baja (4 nodos)


### Agentes Autónomos y Lógica Dinámica

- **[1392-deep_researcher.json](workflows/1392-deep_researcher.json)**
  - **Descripción:** Agente de investigación profunda con IA.
  - **Complejidad:** Alta (85 nodos)

- **[1423-bot_handoff.json](workflows/1423-bot_handoff.json)**
  - **Descripción:** Transfiere la conversación de un bot a un agente humano.
  - **Complejidad:** Alta (39 nodos)

- **[1393-ai_phone_agent_retell.json](workflows/1393-ai_phone_agent_retell.json)**
  - **Descripción:** Agente telefónico con IA que utiliza Retell.
  - **Complejidad:** Alta (36 nodos)

- **[1274-proxmox-ai-agent.json](workflows/1274-proxmox-ai-agent.json)**
  - **Descripción:** Agente que automatiza tareas en servidores Proxmox con IA.
  - **Complejidad:** Alta (35 nodos)

- **[3065-chat-voice-agent-RAG.json](workflows/3065-chat-voice-agent-RAG.json)**
  - **Descripción:** Este flujo integra un chatbot, agente de voz y telefonía con Voiceflow, Google Calendar y RAG para gestionar citas, realizar búsquedas y respaldarse en vectores Qdrant.
  - **Complejidad:** Alta (34 nodos)

- **[3201-whatsapp-ai-sales-agent.json](workflows/3201-whatsapp-ai-sales-agent.json)**
  - **Descripción:** Este flujo automático utiliza WhatsApp para recibir mensajes de usuarios y responderles mediante un agente de AI integrado con una base de conocimientos vectorizada. Incluye la descarga de un catálogo en PDF, su procesamiento y almacenamiento en un vector store, así como la gestión de tipos de mensajes no soportados.
  - **Complejidad:** Alta (28 nodos)

- **[1160-customer-lead-ai-processing.json](workflows/1160-customer-lead-ai-processing.json)**
  - **Descripción:** Este flujo automático procesa solicitudes de contacto utilizando un agente de IA, analizando notas para determinar si son válidas y generando correos electrónicos profesionales cuando así lo requiere.
  - **Complejidad:** Alta (27 nodos)

- **[2644-openai-form-dynamic.json](workflows/2644-openai-form-dynamic.json)**
  - **Descripción:** Este flujo automático permite a un chatbot dinámicamente generar formularios basados en las respuestas del usuario y el análisis de una pregunta abierta previa, evitando así preguntar información redundante.
  - **Complejidad:** Alta (19 nodos)

- **[0009-multi-agente-ia.json](workflows/0009-multi-agente-ia.json)**
  - **Descripción:** Este flujo permite mantener una conversación multirrútil con múltiples agentes de IA basados en los modelos y configuraciones definidos, combinando sus respuestas e incorporando memoria para seguimiento.
  - **Complejidad:** Alta (18 nodos)

- **[3074-erp-chatbot-odoo.json](workflows/3074-erp-chatbot-odoo.json)**
  - **Descripción:** Este flujo automático permite a un chatbot contextualizado con Memoria de ventana recuperar y resumir oportunidades comerciales de Odoo, utilizando herramientas de cálculo y agentes conversacionales para mejorar la asistencia al usuario.
  - **Complejidad:** Alta (16 nodos)

- **[2690-blockchain_dex_insights_agent.json](workflows/2690-blockchain_dex_insights_agent.json)**
  - **Descripción:** Este flujo automático actúa como un agente de insights para DEX blockchain, utilizando diferentes herramientas de análisis y la API de DexScreener para proporcionar información en tiempo real sobre tokens y pares comerciales.
  - **Complejidad:** Media (15 nodos)

- **[1162-typeform-klicktipp-quiz.json](workflows/1162-typeform-klicktipp-quiz.json)**
  - **Descripción:** Este flujo automatizado procesa respuestas de formulario Typeform para crear contactos en KlickTipp y asignar etiquetas dinámicas basadas en las respuestas.
  - **Complejidad:** Media (14 nodos)

- **[3315-coin_market_cap_crypto_agent.json](workflows/3315-coin_market_cap_crypto_agent.json)**
  - **Descripción:** Flujo de agente decriptivo que utiliza API de CoinMarketCap para analizar y proporcionar información sobre criptomonedas a través de un sistema integrado de análisis de lenguaje natural con memoria.
  - **Complejidad:** Media (13 nodos)

- **[0398-agente-ia-herramientas.json](workflows/0398-agente-ia-herramientas.json)**
  - **Descripción:** Este flujo demostrativo permite a un agente de IA interactuar con herramientas web y APIs para proporcionar actividades o información mediante mensajes.
  - **Complejidad:** Media (12 nodos)

- **[0281-llm-chain-ai-agent.json](workflows/0281-llm-chain-ai-agent.json)**
  - **Descripción:** Este flujo ejecuta una cadena LLM para generar respuestas y utiliza un agente de IA con herramientas como Wikipedia para mejorar las búsquedas en conversaciones.
  - **Complejidad:** Media (10 nodos)

- **[0921-n8n-flujo-langchain.json](workflows/0921-n8n-flujo-langchain.json)**
  - **Descripción:** Este flujo permite ejecutar dos tipos de interacciones: una para obtener respuestas con cadenas LLM personalizadas y otra que utiliza un agente de chat integrado con WikipediaQueryRun como herramienta.
  - **Complejidad:** Media (10 nodos)

- **[0203-n8n-fecha-dinamica.json](workflows/0203-n8n-fecha-dinamica.json)**
  - **Descripción:** Este flujo utiliza expresiones de Luxon para calcular y formatear fechas dinámicamente en n8n.
  - **Complejidad:** Media (9 nodos)

- **[1054-outlook-ai-response.json](workflows/1054-outlook-ai-response.json)**
  - **Descripción:** Este flujo automático conecta una cuenta de Microsoft Outlook para filtrar y procesar correos entrantes específicos (en este caso 'sales@yourcompany.com'), utilizando un agente de IA que responde con estilo profesional, conciso y moderno basado en ejemplos predefinidos.
  - **Complejidad:** Media (9 nodos)

- **[2614-custom-ai-agent-memory.json](workflows/2614-custom-ai-agent-memory.json)**
  - **Descripción:** Este flujo configura un agente de IA personalizado con características específicas como personalidad, temas de conversación y estilos de respuesta en chino. La interacción se realiza a través del chat integrado en n8n.
  - **Complejidad:** Media (9 nodos)

- **[0456-keywords-analysis.json](workflows/0456-keywords-analysis.json)**
  - **Descripción:** Este flujo automático procesa keywords de una hoja de Google, las analiza para determinar si contienen nombres de software IT mediante un agente AI y actualiza la hoja con los resultados.
  - **Complejidad:** Media (8 nodos)

- **[2543-openrouter-llm-agent.json](workflows/2543-openrouter-llm-agent.json)**
  - **Descripción:** Este flujo configura un agente AI que utiliza diferentes modelos de lenguaje a través de OpenRouter y mantiene memoria conversacional para chats.
  - **Complejidad:** Media (8 nodos)

- **[0373-nasa-api-credentials.json](workflows/0373-nasa-api-credentials.json)**
  - **Descripción:** Este flujo utiliza una forma para ingresar dinámicamente la clave API de NASA, que luego se usa en el nodo de conexión con NASA mediante expresiones.
  - **Complejidad:** Media (7 nodos)

- **[0471-line-chatbot-ssh.json](workflows/0471-line-chatbot-ssh.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE solicitar interactivamente ayuda sobre comandos SSH y ejecutarlos en una VPS, utilizando herramientas como ReAct Agent y la extensión n8n-nodes-base.
  - **Complejidad:** Media (6 nodos)

- **[0739-peekalink-verificacion.json](workflows/0739-peekalink-verificacion.json)**
  - **Descripción:** Este flujo verifica si un servicio está disponible consultando una URL específica y utilizando condiciones lógicas.
  - **Complejidad:** Media (5 nodos)


### Otros / Misceláneos

- **[1269-api-schema-extractor.json](workflows/1269-api-schema-extractor.json)**
  - **Descripción:** Extrae y documenta el esquema de una API.
  - **Complejidad:** Alta (88 nodos)

- **[2936-api_schema_extractor.json](workflows/2936-api_schema_extractor.json)**
  - **Descripción:** Extrae esquemas de API identificando y procesando documentación técnica en línea para generar un esquema personalizado.
  - **Complejidad:** Alta (88 nodos)

- **[1263-meeting-reminder-bot.json](workflows/1263-meeting-reminder-bot.json)**
  - **Descripción:** Bot que envía recordatorios de reunión por mensajería.
  - **Complejidad:** Alta (61 nodos)

- **[1399-startups-funding-monitor.json](workflows/1399-startups-funding-monitor.json)**
  - **Descripción:** Monitorea rondas de financiación de startups.
  - **Complejidad:** Alta (51 nodos)

- **[2540-agricultural-anomaly-detection.json](workflows/2540-agricultural-anomaly-detection.json)**
  - **Descripción:** Este flujo configura los centros de cada cluster agrícola y establece umbrales para la detección de anomalías en imágenes de cultivos.
  - **Complejidad:** Alta (48 nodos)

- **[2700-cloudflare_kv_management.json](workflows/2700-cloudflare_kv_management.json)**
  - **Descripción:** Este flujo gestiona operaciones de Cloudflare KV Storage como listar, crear, eliminar y renombrar namespaces, así como realizar acciones específicas con pares clave-valor.
  - **Complejidad:** Alta (47 nodos)

- **[1277-baserow-llm-updates.json](workflows/1277-baserow-llm-updates.json)**
  - **Descripción:** Realiza actualizaciones en Baserow usando un modelo de lenguaje.
  - **Complejidad:** Alta (45 nodos)

- **[0864-n8n_leaderboard_stats.json](workflows/0864-n8n_leaderboard_stats.json)**
  - **Descripción:** Este flujo automatizado analiza métricas de usuarios n8n para generar un informe detallado y formateado en Markdown, incluyendo ranking de workflows más populares y estadísticas del creador.
  - **Complejidad:** Alta (43 nodos)

- **[1415-survey_insights_qdrant.json](workflows/1415-survey_insights_qdrant.json)**
  - **Descripción:** Analiza respuestas de encuestas y guarda vectores en Qdrant.
  - **Complejidad:** Alta (42 nodos)

- **[1261-ai-interview-flow.json](workflows/1261-ai-interview-flow.json)**
  - **Descripción:** Automatiza entrevistas utilizando preguntas generadas por IA.
  - **Complejidad:** Alta (40 nodos)

- **[2963-spotify-sync-playlist.json](workflows/2963-spotify-sync-playlist.json)**
  - **Descripción:** Este flujo sincroniza las canciones marcadas como favoritas en Spotify con una lista de reproducción específica. Automáticamente agrega nuevas canciones que estén en tus gustados pero no en la playlist y elimina aquellas que hayan sido eliminadas de tus gustados.
  - **Complejidad:** Alta (40 nodos)

- **[1414-spot-discrimination-analysis.json](workflows/1414-spot-discrimination-analysis.json)**
  - **Descripción:** Detecta discriminación en textos mediante IA.
  - **Complejidad:** Alta (38 nodos)

- **[0922-trustpilot-customer-insights.json](workflows/0922-trustpilot-customer-insights.json)**
  - **Descripción:** Este flujo automático extrae información de las reseñas del cliente en TrustPilot utilizando Qdrant para almacenar vectores y LLMs para generar insights sobre sentimiento general e identificar temas recurrentes.
  - **Complejidad:** Alta (37 nodos)

- **[1420-graphic-design-flow.json](workflows/1420-graphic-design-flow.json)**
  - **Descripción:** Automatiza tareas básicas de diseño gráfico.
  - **Complejidad:** Alta (37 nodos)

- **[3070-spotify-archiver.json](workflows/3070-spotify-archiver.json)**
  - **Descripción:** Este flujo automático archiva mensualmente las canciones favoritas de Spotify en una hoja de cálculo de Google y clasifica Tracks en playlists utilizando un modelo AI.
  - **Complejidad:** Alta (37 nodos)

- **[0861-line-chatbot-memory.json](workflows/0861-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada con sus usuarios mediante el uso de memoria utilizando la API REST del servicio.
  - **Complejidad:** Alta (35 nodos)

- **[2905-analyze-email-headers.json](workflows/2905-analyze-email-headers.json)**
  - **Descripción:** Este flujo analiza cabeceras de correo electrónico para detectar direcciones IP y fraude. Extrae IPs de las cabeceras 'received' y consulta su reputación mediante la API IP Quality Score, también verifica autenticación SPF, DKIM y DMARC.
  - **Complejidad:** Alta (35 nodos)

- **[3122-Proxmox-AI-Agent.json](workflows/3122-Proxmox-AI-Agent.json)**
  - **Descripción:** Este flujo automático gestiona tareas en Proxmox usando n8n y generativa AI. Analiza comandos, valida entradas, genera comandos API y los ejecuta.
  - **Complejidad:** Alta (35 nodos)

- **[3135-docker-immich-deploy.json](workflows/3135-docker-immich-deploy.json)**
  - **Descripción:** Este flujo configura y gestiona entornos Docker para la aplicación Immich, incluyendo deploy, arranque, parada, suspensión, montaje de discos y gestión de usuarios y ACLs. Utiliza SSH y Webhooks para interactuar con el servidor.
  - **Complejidad:** Alta (35 nodos)

- **[0926-docker_n8n_api_workflow.json](workflows/0926-docker_n8n_api_workflow.json)**
  - **Descripción:** Este flujo automático maneja la creación y administración de contenedores Docker a través de una API con autenticación básica.
  - **Complejidad:** Alta (34 nodos)

- **[1417-bitrix-chatbot-rag.json](workflows/1417-bitrix-chatbot-rag.json)**
  - **Descripción:** Chatbot en Bitrix con búsqueda RAG.
  - **Complejidad:** Alta (34 nodos)

- **[0904-line-chatbot-memory.json](workflows/0904-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automatizado permite a un chatbot de LINE mantener una conversación contextualizada mediante el uso de memoria persistente.
  - **Complejidad:** Alta (33 nodos)

- **[0928-n8n_workflow_stats.json](workflows/0928-n8n_workflow_stats.json)**
  - **Descripción:** Este flujo automático permite a los usuarios obtener estadísticas detalladas sobre los workflows de n8n, incluyendo información por nodo, global, etiquetas, webhooks y más. Utiliza funciones JS avanzadas como JMESPath para procesamiento eficiente.
  - **Complejidad:** Alta (33 nodos)

- **[3008-minio-deploy.json](workflows/3008-minio-deploy.json)**
  - **Descripción:** Este flujo automatiza el despliegue y gestión de contenedores Docker para MinIO en un servidor con WHMCS/WISECP. Maneja operaciones como crear, arrancar, detener, suspender, montar/desmontar discos y configurar ACLs, además de integración con Nginx para el acceso.
  - **Complejidad:** Alta (33 nodos)

- **[1267-email_subscription_workflow.json](workflows/1267-email_subscription_workflow.json)**
  - **Descripción:** Gestiona suscripciones de correo electrónico de forma automatizada.
  - **Complejidad:** Alta (32 nodos)

- **[2532-pdf-digital-sign-service.json](workflows/2532-pdf-digital-sign-service.json)**
  - **Descripción:** Este flujo automático permite la generación de claves y certificados digitales para firmar documentos PDF.
  - **Complejidad:** Alta (32 nodos)

- **[2647-whatsapp-ai-chatbot.json](workflows/2647-whatsapp-ai-chatbot.json)**
  - **Descripción:** Este flujo automatizado permite a un chatbot en WhatsApp analizar y responder de manera inteligente a diferentes tipos de mensajes: texto, voz, imágenes y PDFs.
  - **Complejidad:** Alta (32 nodos)

- **[0823-ai-monitoring-slack.json](workflows/0823-ai-monitoring-slack.json)**
  - **Descripción:** Este flujo automatizado monitorea artículos de interés en tiempo real utilizando múltiples fuentes RSS, clasifica su relevancia con IA y genera resúmenes formateados para facilitar la gestión eficiente.
  - **Complejidad:** Alta (31 nodos)

- **[0962-email-ai-assistant.json](workflows/0962-email-ai-assistant.json)**
  - **Descripción:** Este flujo automático analiza correos entrantes utilizando IA para resumirlos y generar respuestas, permitiendo revisiones humanas cuando es necesario.
  - **Complejidad:** Alta (31 nodos)

- **[1394-yoga-line-bot.json](workflows/1394-yoga-line-bot.json)**
  - **Descripción:** Bot de LINE que envía rutinas de yoga.
  - **Complejidad:** Alta (31 nodos)

- **[1273-service_now_search_bot.json](workflows/1273-service_now_search_bot.json)**
  - **Descripción:** Bot que busca información en ServiceNow.
  - **Complejidad:** Alta (29 nodos)

- **[2787-contabo-backups.json](workflows/2787-contabo-backups.json)**
  - **Descripción:** Este flujo automático programa snapshots diarios de instancias en Contabo, verificando y eliminando si ya existe un.snapshot antes de crear uno nuevo.
  - **Complejidad:** Alta (29 nodos)

- **[2980-reddit-pr-report.json](workflows/2980-reddit-pr-report.json)**
  - **Descripción:** Este flujo automatiza la identificación de historias trending mediante el análisis de discusiones en Reddit y su posterior análisis con LLM para generar informes estratégicos de PR.
  - **Complejidad:** Alta (29 nodos)

- **[0784-ai-meeting-tool.json](workflows/0784-ai-meeting-tool.json)**
  - **Descripción:** Este flujo automático permite a un asistente AI gestionar transcripciones de reuniones y realizar acciones automatizadas como crear eventos en Google Calendar para seguimiento.
  - **Complejidad:** Alta (28 nodos)

- **[3054-business-canvas-generator.json](workflows/3054-business-canvas-generator.json)**
  - **Descripción:** Flujo que genera un Canvas de Modelo de Negocio a partir de inputs de chat, utilizando LLM para cada sección y transformando los resultados en HTML.
  - **Complejidad:** Alta (28 nodos)

- **[3283-sync-email-templates.json](workflows/3283-sync-email-templates.json)**
  - **Descripción:** Este flujo sincroniza plantillas de correo electrónico entre Dartagnan y Braze. Recupera plantillas de Dartagnan, compara con las existentes en Braze y actualiza o crea nuevas según corresponda.
  - **Complejidad:** Alta (28 nodos)

- **[3128-gmail-mcp-server.json](workflows/3128-gmail-mcp-server.json)**
  - **Descripción:** Este flujo configura un servidor MCP para interactuar con Gmail, permitiendo realizar operaciones como buscar, eliminar, marcar como leído, agregar o quitar etiquetas y más.
  - **Complejidad:** Alta (27 nodos)

- **[2781-spotify-mqtt-controller.json](workflows/2781-spotify-mqtt-controller.json)**
  - **Descripción:** Este flujo maneja comandos MQTT de un botón remoto para controlar Spotify, incluyendo volumen y reproducción, además de reproducir listas favoritas.
  - **Complejidad:** Alta (26 nodos)

- **[3127-email-ai-responder.json](workflows/3127-email-ai-responder.json)**
  - **Descripción:** Este flujo automatiza la respuesta a correos electrónicos mediante DeepSeek R1 para resumir y enviar contestaciones profesionales.
  - **Complejidad:** Alta (26 nodos)

- **[3210-google_maps_email_scraper.json](workflows/3210-google_maps_email_scraper.json)**
  - **Descripción:** Este flujo extrae y procesa correos electrónicos de negocios desde Google Maps utilizando una lista de consultas. Busca URLs relacionadas con las búsquedas iniciales, filtra las irrelevantes, scrapea las páginas resultantes para encontrar direcciones de correo electrónico, elimina duplicados e importa los resultados a una hoja de cálculo de Google.
  - **Complejidad:** Alta (26 nodos)

- **[0867-linea_inventario_agendador.json](workflows/0867-linea_inventario_agendador.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de n8n agendar reuniones verificando la disponibilidad en Google Calendar y generando slots horarios de 30 minutos entre las horas laborales del lunes al viernes.
  - **Complejidad:** Alta (25 nodos)

- **[3217-appointment-scheduling-flow.json](workflows/3217-appointment-scheduling-flow.json)**
  - **Descripción:** Este flujo automatiza la gestión de citas profesionales usando formularios interactivos y aprobación humana. Recibe solicitudes, clasifica enquires con IA, valida términos, agenda fechas/horas, notifica al usuario y gestiona citas aprobadas o rechazadas.
  - **Complejidad:** Alta (25 nodos)

- **[1268-automatizacion_becas_ai.json](workflows/1268-automatizacion_becas_ai.json)**
  - **Descripción:** Automatiza el proceso de solicitudes de becas usando IA.
  - **Complejidad:** Alta (24 nodos)

- **[1278-chatbot-citas.json](workflows/1278-chatbot-citas.json)**
  - **Descripción:** Chatbot para agendar citas automáticamente.
  - **Complejidad:** Alta (24 nodos)

- **[3094-flujo-get-scaleway-servers.json](workflows/3094-flujo-get-scaleway-servers.json)**
  - **Descripción:** Este flujo automatiza la obtención y filtración de información de servidores en Scaleway, incluyendo instancias y baremetal, permitiendo buscar por tags, nombre, IP pública o zona.
  - **Complejidad:** Alta (24 nodos)

- **[0711-phishing-analysis-n8n.json](workflows/0711-phishing-analysis-n8n.json)**
  - **Descripción:** Este flujo automático analiza indicadores de compromiso en correos electrónicos, extrae URLs y las escanea con VirusTotal y URLScan.io para detectar posibles amenazas de phishing.
  - **Complejidad:** Alta (23 nodos)

- **[2655-_Generate_AI-Ready_llms.txt_Files_from_Screaming_Frog.json](workflows/2655-_Generate_AI-Ready_llms.txt_Files_from_Screaming_Frog.json)**
  - **Descripción:** Transforma un CSV exportado de Screaming Frog en un archivo `llms.txt` optimizado con títulos, URLs e información de indexabilidad, facilitando el rastreo y la clasificación por modelos de lenguaje.
  - **Complejidad:** Alta (23 nodos)

- **[2846-news-email-digest.json](workflows/2846-news-email-digest.json)**
  - **Descripción:** Flujo que recolecta, procesa y selecciona artículos de RSS de Calcalist y Mako para enviar un resumen diario formatiado por correo electrónico con los más relevantes para ejecutivos.
  - **Complejidad:** Alta (23 nodos)

- **[2915-mcp-google-calendar.json](workflows/2915-mcp-google-calendar.json)**
  - **Descripción:** Este flujo configura un servidor MCP integrado con Google Calendar para realizar operaciones de calendario como crear, actualizar y eliminar eventos mediante herramientas específicas.
  - **Complejidad:** Alta (23 nodos)

- **[3255-flujo-independiente.json](workflows/3255-flujo-independiente.json)**
  - **Descripción:** Este flujo implementa un proceso independiente que inicia una ejecución secundaria a través de un webhook y la reanuda en el contexto principal.
  - **Complejidad:** Alta (23 nodos)

- **[1422-analyze_reddit_posts_business_opportunities.json](workflows/1422-analyze_reddit_posts_business_opportunities.json)**
  - **Descripción:** Analiza publicaciones de Reddit en busca de oportunidades de negocio.
  - **Complejidad:** Alta (22 nodos)

- **[3261-bbc_podcast_workflow.json](workflows/3261-bbc_podcast_workflow.json)**
  - **Descripción:** Este flujo extrae y clasifica noticias de BBC, genera un guion para podcast usando LLM y los envía a Hugging Face para conversión en audio.
  - **Complejidad:** Alta (22 nodos)

- **[3288-follow_up_meetings.json](workflows/3288-follow_up_meetings.json)**
  - **Descripción:** Este flujo automático monitorea citas de venta pasadas para detectar si se han enviado mensajes posteriores y sugiere nuevas citas disponibles al usuario para programar una nueva reunión si es necesario.
  - **Complejidad:** Alta (22 nodos)

- **[3336-credenciales-transfer-n8n.json](workflows/3336-credenciales-transfer-n8n.json)**
  - **Descripción:** Flujo para transferir credenciales entre instancias de n8n. Permite seleccionar una instancia destino y una credencial origen, luego exporta, procesa y envía la credencial al destino.
  - **Complejidad:** Alta (22 nodos)

- **[1421-automated-seo-audit-report.json](workflows/1421-automated-seo-audit-report.json)**
  - **Descripción:** Genera reportes de auditoría SEO automáticamente.
  - **Complejidad:** Alta (21 nodos)

- **[2580-multiple-local-llm-testing.json](workflows/2580-multiple-local-llm-testing.json)**
  - **Descripción:** Este flujo automático permite probar múltiples modelos de LLM locales en LM Studio mediante solicitudes HTTP y análisis detallado de respuestas.
  - **Complejidad:** Alta (21 nodos)

- **[2637-line-bitrix-task-integration.json](workflows/2637-line-bitrix-task-integration.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada y actualizar la información del usuario en Bitrix24 para gestionar tareas.
  - **Complejidad:** Alta (21 nodos)

- **[2654-comparador-multiples-modelos.json](workflows/2654-comparador-multiples-modelos.json)**
  - **Descripción:** Este flujo permite comparar múltiples respuestas de modelos de lenguaje manteniendo memoria separada por modelo.
  - **Complejidad:** Alta (21 nodos)

- **[2671-performance-testing-multi-llm.json](workflows/2671-performance-testing-multi-llm.json)**
  - **Descripción:** Este flujo automático permite pruebas múltiples de modelos locales de lenguaje (LLM) a través del servidor LM Studio, analizando métricas como puntaje de legibilidad y longitud promedio de palabras para cada respuesta.
  - **Complejidad:** Alta (21 nodos)

- **[2868-sustentabilidad-news.json](workflows/2868-sustentabilidad-news.json)**
  - **Descripción:** Este flujo automático extrae y clasifica las noticias de la UE, identificando si están relacionadas con la sostenibilidad, y envía un resumen por correo electrónico.
  - **Complejidad:** Alta (21 nodos)

- **[3005-chinese-translator-line.json](workflows/3005-chinese-translator-line.json)**
  - **Descripción:** Este flujo traduce mensajes de LINE utilizando OpenRouter.ai para obtener caracteres chinos, pinyin y traducción al inglés.
  - **Complejidad:** Alta (21 nodos)

- **[0006-airtable-hn-job-scraping.json](workflows/0006-airtable-hn-job-scraping.json)**
  - **Descripción:** Este flujo automático permite extraer y estructurar ofertas de trabajo publicadas en 'Ask HN: Who is hiring' en Hacker News utilizando la API de Algolia.
  - **Complejidad:** Alta (20 nodos)

- **[0960-gitea-backup-workflow.json](workflows/0960-gitea-backup-workflow.json)**
  - **Descripción:** Este flujo automático verifica y guarda los workflows de n8n en un repositorio Git alojado en Gitea mediante una comparación de cambios y actualizaciones.
  - **Complejidad:** Alta (20 nodos)

- **[2561-inteligente-busqueda-web.json](workflows/2561-inteligente-busqueda-web.json)**
  - **Descripción:** Este flujo utiliza múltiples cadenas de pensamiento y modelos LLM para generar consultas óptimas, realizar búsquedas en la web e implementar un sistema de re-ranking semántico que evalúa los resultados y proporciona información relevante estructurada.
  - **Complejidad:** Alta (20 nodos)

- **[2903-extraer_y_decodificar_noticias_google.json](workflows/2903-extraer_y_decodificar_noticias_google.json)**
  - **Descripción:** Este flujo extrae y decodifica URLs de noticias de Google News a partir de su feed RSS, limpiando los enlaces para obtener artículos claros y accesibles.
  - **Complejidad:** Alta (20 nodos)

- **[2932-bluesky-threads.json](workflows/2932-bluesky-threads.json)**
  - **Descripción:** Este flujo crea hilos en Bluesky usando autenticación y solicitudes HTTP para publicar posts iniciales y respuestas anidadas con un esquema de espera y bucle.
  - **Complejidad:** Alta (20 nodos)

- **[0828-podcast-consciencia-ai.json](workflows/0828-podcast-consciencia-ai.json)**
  - **Descripción:** Este flujo analiza podcasts sobre la filosofía de la mente, extrae información clave y realiza búsquedas en Wikipedia para elaborar resúmenes mejorados.
  - **Complejidad:** Alta (19 nodos)

- **[1081-retry-on-fail-known-error.json](workflows/1081-retry-on-fail-known-error.json)**
  - **Descripción:** Este flujo implementa un mecanismo de reintento para una acción, pero evita los reintentos en caso de errores específicos conocidos como 'could not be found'.
  - **Complejidad:** Alta (19 nodos)

- **[1143-seo-serp-analysis.json](workflows/1143-seo-serp-analysis.json)**
  - **Descripción:** Este flujo automático busca y procesa resultados de búsqueda en Google para análisis SEO.
  - **Complejidad:** Alta (19 nodos)

- **[1403-web-security-audit.json](workflows/1403-web-security-audit.json)**
  - **Descripción:** Realiza auditorías de seguridad web automatizadas.
  - **Complejidad:** Alta (19 nodos)

- **[2687-flujo-verificacion-voz-correo.json](workflows/2687-flujo-verificacion-voz-correo.json)**
  - **Descripción:** Este flujo automático envía mensajes de voz para verificación y luego verifica el código a través de correo electrónico.
  - **Complejidad:** Alta (19 nodos)

- **[2792-flujo-imagen-ai.json](workflows/2792-flujo-imagen-ai.json)**
  - **Descripción:** Flujo que genera imágenes AI basadas en prompts y estilos seleccionados por el usuario, usando la API de Hugging Face. El usuario puede elegir entre diferentes estilos visuales como cyberpunk o neon para crear composiciones visuales avanzadas.
  - **Complejidad:** Alta (19 nodos)

- **[1006-rag-stock-analysis.json](workflows/1006-rag-stock-analysis.json)**
  - **Descripción:** Este flujo analiza informes de rentabilidad utilizando RAG para generar un informe detallado en formato markdown sobre las tendencias y diferencias.
  - **Complejidad:** Alta (18 nodos)

- **[1149-google-docs-image-replace.json](workflows/1149-google-docs-image-replace.json)**
  - **Descripción:** Automatización de documentos Google con reemplazo dinámico de imágenes.
  - **Complejidad:** Alta (18 nodos)

- **[1157-n8n-multi-workflow.json](workflows/1157-n8n-multi-workflow.json)**
  - **Descripción:** Este flujo automático permite ejecutar múltiples trabajos secundarios en paralelo y realizar un seguimiento de su estado hasta que todos finalicen.
  - **Complejidad:** Alta (18 nodos)

- **[2539-lands-knn-classification.json](workflows/2539-lands-knn-classification.json)**
  - **Descripción:** Este flujo de trabajo utiliza KNN con imágenes satelitales para clasificar tipos de paisaje mediante embeddings del modelo Voyage AI y consultas a Qdrant. Cuando hay empates, incrementa el número de vecinos hasta encontrar una mayoría clara.
  - **Complejidad:** Alta (18 nodos)

- **[2663-n8n-image-editor-flux-fill.json](workflows/2663-n8n-image-editor-flux-fill.json)**
  - **Descripción:** Este flujo permite procesar imágenes mediante inpainting con la herramienta FLUX Fill, integrando interacciones de usuario en un editor visual basado en Konva.js.
  - **Complejidad:** Alta (18 nodos)

- **[2683-podcast_workflow.json](workflows/2683-podcast_workflow.json)**
  - **Descripción:** Este flujo automático procesa un episodio de podcast dividiendo su transcripción, resumiéndola y generando preguntas y temas relacionados para luego formatear la información en HTML y enviarla mediante Gmail.
  - **Complejidad:** Alta (18 nodos)

- **[3017-knn_land_classifier.json](workflows/3017-knn_land_classifier.json)**
  - **Descripción:** Este flujo utiliza un clasificador KNN para determinar la clase de una imagen basada en su embedding vectorial. Primero, obtiene el embedding de la imagen mediante la API de Voyage AI, luego consulta Qdrant con este embedding para encontrar los vecinos más cercanos y aplica votación mayoritaria para resolver conflictos.
  - **Complejidad:** Alta (18 nodos)

- **[3104-flux-image-edit.json](workflows/3104-flux-image-edit.json)**
  - **Descripción:** Este flujo maneja una solicitud de relleno de imagen utilizando la API de FLUX. Primero recibe una imagen y un máscara a través de un webhook, luego procesa la imagen con el modelo de IA para generar una versión editada basada en un prompt proporcionado por el usuario.
  - **Complejidad:** Alta (18 nodos)

- **[3260-fact-checking_workflow.json](workflows/3260-fact-checking_workflow.json)**
  - **Descripción:** Este flujo automatiza la verificación de hechos y análisis de textos. Separa un texto en oraciones, utiliza LLM para marcar declaraciones como correctas o incorrectas, y produce un informe con las inexactitudes identificadas.
  - **Complejidad:** Alta (18 nodos)

- **[0822-email-approval-ia.json](workflows/0822-email-approval-ia.json)**
  - **Descripción:** Este flujo automatiza el procesamiento de correos electrónicos entrantes, genera resúmenes y respuestas usando RAG e IA, requiere aprobación Sí/No antes de enviarlas.
  - **Complejidad:** Alta (17 nodos)

- **[0873-opensea-marketplace-agent.json](workflows/0873-opensea-marketplace-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con la API de OpenSea para obtener información sobre listados, ofertas y órdenes de NFTs en diferentes colecciones e identificadores.
  - **Complejidad:** Alta (17 nodos)

- **[1137-pdf-qa-vector-store.json](workflows/1137-pdf-qa-vector-store.json)**
  - **Descripción:** Este flujo procesa mensajes de chat para responder preguntas sobre un PDF utilizando el vector almacenado en Qdrant.
  - **Complejidad:** Alta (17 nodos)

- **[2573-workflow-ai-investigacion.json](workflows/2573-workflow-ai-investigacion.json)**
  - **Descripción:** Este flujo utiliza LLMs para generar consultas de búsqueda, procesar resultados y sintetizar un informe de investigación completo.
  - **Complejidad:** Alta (17 nodos)

- **[2620-n8n-workflow-clone.json](workflows/2620-n8n-workflow-clone.json)**
  - **Descripción:** Este flujo permite clonar workflows entre diferentes instancias de n8n mediante la API, procesando lotes para optimizar el rendimiento.
  - **Complejidad:** Alta (17 nodos)

- **[2765-image-object-extraction.json](workflows/2765-image-object-extraction.json)**
  - **Descripción:** Este flujo utiliza la API de Cloudflare para detectar objetos en una imagen y luego extrae y almacena esos objetos como imágenes separadas en Elasticsearch para permitir búsquedas basadas en ellos.
  - **Complejidad:** Alta (17 nodos)

- **[2907-automated_churn_management.json](workflows/2907-automated_churn_management.json)**
  - **Descripción:** Automatiza la detección y manejo de riesgo de churn diario, generando ofertas personalizadas para clientes con alto riesgo de abandono.
  - **Complejidad:** Alta (17 nodos)

- **[2961-anomaly-crops-detection.json](workflows/2961-anomaly-crops-detection.json)**
  - **Descripción:** Este flujo utiliza embeddings de imágenes y clustering para detectar anomalias en cultivos. Recibe una URL de imagen, la convierte en un vector con el modelo de Voyage.ai, consulta contra vectores almacenados en Qdrant y determina si es similar a algún cultivo conocido o detecta anomalías.
  - **Complejidad:** Alta (17 nodos)

- **[3098-ai-powered-research-flow.json](workflows/3098-ai-powered-research-flow.json)**
  - **Descripción:** Flujo automatizado que utiliza LLMs y APIs para realizar investigaciones en deep search, generar queries de búsqueda, analizar resultados y crear informes detallados.
  - **Complejidad:** Alta (17 nodos)

- **[0278-paul_graham_essays.json](workflows/0278-paul_graham_essays.json)**
  - **Descripción:** Este flujo automático permite extraer y resumir los textos de hasta tres ensayos recientes publicados en la web de Paul Graham.
  - **Complejidad:** Alta (16 nodos)

- **[0416-zotero-pagination-bibliography.json](workflows/0416-zotero-pagination-bibliography.json)**
  - **Descripción:** Este flujo automático permite descargar colecciones e items (artículos) de la API de Zotero mediante un bucle que maneja paginaciones.
  - **Complejidad:** Alta (16 nodos)

- **[0417-image-composite-overlay.json](workflows/0417-image-composite-overlay.json)**
  - **Descripción:** Este flujo automático permite componer dos imágenes, superponiendo una sobre la otra en el centro de la imagen base.
  - **Complejidad:** Alta (16 nodos)

- **[0775-Email-AI-HLT-System.json](workflows/0775-Email-AI-HLT-System.json)**
  - **Descripción:** Este flujo automático utiliza IMAP para recibir correos electrónicos y AI para generar respuestas, integrando human intervention en el bucle para validar.
  - **Complejidad:** Alta (16 nodos)

- **[2599-workflow-nodes-update-check-template.json](workflows/2599-workflow-nodes-update-check-template.json)**
  - **Descripción:** Este flujo verifica nodos desactualizados en workflows de n8n, añade nuevos nodos con versiones más recientes y renombra los existentes para mantener la consistencia.
  - **Complejidad:** Alta (16 nodos)

- **[2602-kling-try-on-video-generator.json](workflows/2602-kling-try-on-video-generator.json)**
  - **Descripción:** Este flujo automático permite generar videos con probadores virtuales de 360 grados utilizando la API Kling, procesando primero las imágenes y luego generando el video final cuando esté disponible.
  - **Complejidad:** Alta (16 nodos)

- **[2835-acuity-chatbot-search.json](workflows/2835-acuity-chatbot-search.json)**
  - **Descripción:** Flujo que utiliza un chatbot para buscar información en la API de soporte de AcuityScheduling y formatear los resultados.
  - **Complejidad:** Alta (16 nodos)

- **[2896-secure-webhook-validator.json](workflows/2896-secure-webhook-validator.json)**
  - **Descripción:** Este flujo implementa un webhook seguro con autenticación y validación de campos requeridos. Verifica el token de autorización y los campos obligatorios en la solicitud, respondiendo con códigos HTTP apropiados (401 si falla la autenticación o 400 si faltan campos) y devolviendo una respuesta JSON exitosa.
  - **Complejidad:** Alta (16 nodos)

- **[2938-auth0-login-flow.json](workflows/2938-auth0-login-flow.json)**
  - **Descripción:** Este flujo implementa un sistema de autenticación OAuth2 con Auth0, que inicia una sesión del usuario redirigiéndolo a una página de login, obtiene el código de autorización y luego solicita el token de acceso para verificar la identidad del usuario.
  - **Complejidad:** Alta (16 nodos)

- **[3252-docker-registry-cleaner.json](workflows/3252-docker-registry-cleaner.json)**
  - **Descripción:** Este flujo automático elimina las imágenes y etiquetas viejas de un registro de Docker manteniendo solo las últimas 10 versiones y notificando los cambios.
  - **Complejidad:** Alta (16 nodos)

- **[1035-deepseek-chat-r1.json](workflows/1035-deepseek-chat-r1.json)**
  - **Descripción:** Este flujo permite interactuar con los modelos de DeepSeek (conversacional y razonador) manteniendo memoria contextualizada.
  - **Complejidad:** Media (15 nodos)

- **[2664-deepseek-ia-flujo.json](workflows/2664-deepseek-ia-flujo.json)**
  - **Descripción:** Este flujo automático permite integrar el modelo de IA DeepSeek Reasoner y Chat V3 manteniendo contexto conversacional mediante memoria.
  - **Complejidad:** Media (15 nodos)

- **[2753-n8n-updates-checker.json](workflows/2753-n8n-updates-checker.json)**
  - **Descripción:** Este flujo recupera la información de los tipos de nodos y las versiones disponibles, luego verifica si hay nodos que requieren actualización comparando su versión actual con la última versión registrada. Si un nodo no está activo o su versión es obsoleta, lo identifica y genera una salida formateada con el nombre del flujo, su ID y la lista de nodos desactualizados.
  - **Complejidad:** Media (15 nodos)

- **[2966-generar-palabras-clave-seo.json](workflows/2966-generar-palabras-clave-seo.json)**
  - **Descripción:** Este flujo genera frases clave SEO iniciales usando IA basándose en el perfil de cliente ideal.
  - **Complejidad:** Media (15 nodos)

- **[3289-ko-fi-webhook-handler.json](workflows/3289-ko-fi-webhook-handler.json)**
  - **Descripción:** Flujo que procesa webhooks de Ko-fi, verifica el token y maneja donaciones, suscripciones y órdenes de compra.
  - **Complejidad:** Media (15 nodos)

- **[0834-code-review-ai.json](workflows/0834-code-review-ai.json)**
  - **Descripción:** Este flujo automatizado permite a la herramienta Code Review del repositorio interactuar con los sistemas integrados que manejan solicitudes de pull, generando comentarios inteligentes basados en diferencias detectadas.
  - **Complejidad:** Media (14 nodos)

- **[1000-ip-authentication-report.json](workflows/1000-ip-authentication-report.json)**
  - **Descripción:** Este flujo consulta y filtra eventos de autenticación exitosa para diferentes tipos de inicio de sesión y luego envía un informe en formato CSV por correo electrónico.
  - **Complejidad:** Media (14 nodos)

- **[1133-linear-tickets-sync.json](workflows/1133-linear-tickets-sync.json)**
  - **Descripción:** Este flujo automático extrae y procesa todas las incidencias de un equipo específico en Linear, paginando los resultados para manejar grandes volúmenes.
  - **Complejidad:** Media (14 nodos)

- **[1161-gravity-klicktipp-integration.json](workflows/1161-gravity-klicktipp-integration.json)**
  - **Descripción:** Este flujo automatizado procesa envíos de formularios Gravity Forms para suscribir contactos y aplicar etiquetas en KlickTipp.
  - **Complejidad:** Media (14 nodos)

- **[2741-zalando-price-monitor.json](workflows/2741-zalando-price-monitor.json)**
  - **Descripción:** Este flujo monitorea precios en Zalando, extrae información de productos, compara con precios guardados y notifica si hay reducciones.
  - **Complejidad:** Media (14 nodos)

- **[2824-csrd-audit-flow.json](workflows/2824-csrd-audit-flow.json)**
  - **Descripción:** Flujo automático para auditar reportes CSRD en formato xHTML. Analiza y genera un informe sumarizando hallazgos clave y recomendaciones.
  - **Complejidad:** Media (14 nodos)

- **[2865-image_alt_text_generator.json](workflows/2865-image_alt_text_generator.json)**
  - **Descripción:** Este flujo extrae las imágenes y su texto alternativo de una página web, genera texto alternativo si es necesario y actualiza una hoja de cálculo con los resultados.
  - **Complejidad:** Media (14 nodos)

- **[3049-line-chat-gcal-gmail.json](workflows/3049-line-chat-gcal-gmail.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE integrarse con Google Calendar y Gmail para gestionar eventos y correo electrónico, utilizando memoria contextual y capacidades de respuesta avanzadas.
  - **Complejidad:** Media (14 nodos)

- **[3069-email-routing-ai.json](workflows/3069-email-routing-ai.json)**
  - **Descripción:** Este flujo automático clasifica y enruta correos electrónicos comerciales utilizando IA para asignar mensajes a diferentes departamentos.
  - **Complejidad:** Media (14 nodos)

- **[3099-country-capitals-tool.json](workflows/3099-country-capitals-tool.json)**
  - **Descripción:** Este flujo configura un asistente de chat que puede listar capitales de países ficticios o devolver la capital de un país específico basándose en una herramienta personalizada.
  - **Complejidad:** Media (14 nodos)

- **[3171-utm-link-generator-with-analytics.json](workflows/3171-utm-link-generator-with-analytics.json)**
  - **Descripción:** Este flujo crea enlaces UTM personalizados, genera códigos QR y programa informes de Analytics para monitorear su rendimiento.
  - **Complejidad:** Media (14 nodos)

- **[0331-eleven-openai-audio-translation.json](workflows/0331-eleven-openai-audio-translation.json)**
  - **Descripción:** Este flujo ejecuta un proceso de conversión y transcripción de texto francés a voz y luego al inglés.
  - **Complejidad:** Media (13 nodos)

- **[0869-bitrix-chatbot-webhook.json](workflows/0869-bitrix-chatbot-webhook.json)**
  - **Descripción:** Este flujo automatizado permite a Bitrix24 procesar eventos de chatbots mediante webhooks, validar tokens y enviar respuestas adecuadas.
  - **Complejidad:** Media (13 nodos)

- **[0887-horario-tareas-n8n.json](workflows/0887-horario-tareas-n8n.json)**
  - **Descripción:** Este flujo automatiza el activo y desactivo de un workflow en n8n a las 08:00 y 20:00 cada día.
  - **Complejidad:** Media (13 nodos)

- **[0903-bitrix24-chatbot-workflow.json](workflows/0903-bitrix24-chatbot-workflow.json)**
  - **Descripción:** Este flujo automático permite a Bitrix24 procesar eventos relacionados con chatbots (como mensajes y instalaciones) mediante webhooks, realizar validaciones de token y responder adecuadamente.
  - **Complejidad:** Media (13 nodos)

- **[2548-cv-error-notification.json](workflows/2548-cv-error-notification.json)**
  - **Descripción:** Este workflow detecta errores en otras tareas (ya sean problemas durante la ejecución o fallos al iniciar) y envía un correo detallado a través de Gmail para notificar sobre el incidente.
  - **Complejidad:** Media (13 nodos)

- **[3027-retry-executions-hourly.json](workflows/3027-retry-executions-hourly.json)**
  - **Descripción:** Este flujo programa una ejecución automática hourly para buscar y retry de executions con estado 'error' en n8n, usando credenciales guardadas.
  - **Complejidad:** Media (13 nodos)

- **[0132-line-chatbot-memory.json](workflows/0132-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada recordando el nombre y correo del usuario que lo activa.
  - **Complejidad:** Media (12 nodos)

- **[0318-line-chatbot-memory.json](workflows/0318-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada mediante el uso de memoria y herramientas personalizadas.
  - **Complejidad:** Media (12 nodos)

- **[0345-google-indexing-sitemap.json](workflows/0345-google-indexing-sitemap.json)**
  - **Descripción:** Este flujo automático extrae URLs de un sitemap XML y las envía por lotes a la API de Google Indexing para notificar sobre actualizaciones.
  - **Complejidad:** Media (12 nodos)

- **[0349-stoic-twitter-bot.json](workflows/0349-stoic-twitter-bot.json)**
  - **Descripción:** Este flujo automático permite crear y publicar tweets virales con un estilo personal sobre estóicismo moderno, programados cada 6 horas de manera aleatoria.
  - **Complejidad:** Media (12 nodos)

- **[0404-systeme-io-contact-flow.json](workflows/0404-systeme-io-contact-flow.json)**
  - **Descripción:** Este flujo automático recopila todos los contactos y etiquetas de Systeme.io utilizando la paginación para manejar las limitaciones de API.
  - **Complejidad:** Media (12 nodos)

- **[0480-calendar-voice-reminder.json](workflows/0480-calendar-voice-reminder.json)**
  - **Descripción:** Este flujo automático busca citas próximas y genera recordatorios por voz sintetizada para enviar a los asistentes.
  - **Complejidad:** Media (12 nodos)

- **[0870-chatbot-salud-ia.json](workflows/0870-chatbot-salud-ia.json)**
  - **Descripción:** Este flujo automático permite a un chatbot mantener una conversación contextualizada sobre planes de saúde doação, utilizando memoria persistente e integração com APIs externas para buscar informações específicas.
  - **Complejidad:** Media (12 nodos)

- **[1209-n8n-ai-meteorologia.json](workflows/1209-n8n-ai-meteorologia.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con la API Open-Meteo mediante herramientas que convierten en funciones, facilitando respuestas sobre pronósticos meteorológicos basados en ubicaciones especificadas por el usuario.
  - **Complejidad:** Media (12 nodos)

- **[1235-automatizacion-subtitulos-json2video.json](workflows/1235-automatizacion-subtitulos-json2video.json)**
  - **Descripción:** Este flujo automático utiliza json2video para generar subtítulos en videos de manera programada.
  - **Complejidad:** Media (12 nodos)

- **[1244-workflow-dashboard-mermaid.json](workflows/1244-workflow-dashboard-mermaid.json)**
  - **Descripción:** Este flujo automático permite visualizar y mostrar gráficos de los trabajos (workflows) de n8n utilizando la biblioteca mermaid.js para representar las conexiones entre nodos en diagramas.
  - **Complejidad:** Media (12 nodos)

- **[2660-email-agent.json](workflows/2660-email-agent.json)**
  - **Descripción:** Este flujo automático permite a un chatbot interactuar con cuentas de correo electrónico para gestionar tareas como enviar, responder y etiquetar correos.
  - **Complejidad:** Media (12 nodos)

- **[2818-squarespace-fulfillment.json](workflows/2818-squarespace-fulfillment.json)**
  - **Descripción:** Este flujo automatiza la gestión de órdenes en Squarespace Commerce. Busca órdenes pendientes y las marca como cumplidas, utilizando el API Key para autenticación.
  - **Complejidad:** Media (12 nodos)

- **[2891-flujo_whatsapp_klicktipp.json](workflows/2891-flujo_whatsapp_klicktipp.json)**
  - **Descripción:** Este flujo automatiza la entrega de mensajes personalizados en WhatsApp a partir de KlickTipp y procesa respuestas de los usuarios para controlar campañas. Detecta si el mensaje comienza con 'STOP' para re direccionar hacia soporte o suscribir al contacto.
  - **Complejidad:** Media (12 nodos)

- **[2957-oaut-service-config.json](workflows/2957-oaut-service-config.json)**
  - **Descripción:** Este flujo utiliza un modelo de lenguaje para identificar configuraciones OAuth2 a partir de un nombre de servicio. El proceso incluye la generación de URIs de autorización y token con una puntuación de confianza.
  - **Complejidad:** Media (12 nodos)

- **[3002-n8n-check-models.json](workflows/3002-n8n-check-models.json)**
  - **Descripción:** Este flujo verifica y registra qué modelos están siendo utilizados en cada workflow de n8n, recolectando información detallada sobre los nodos y workflows relevantes.
  - **Complejidad:** Media (12 nodos)

- **[3131-ssl-expiry-monitor.json](workflows/3131-ssl-expiry-monitor.json)**
  - **Descripción:** Este flujo automático monitorea la fecha de expiración de certificados SSL de sitios web almacenados en una hoja de cálculo de Google. Cada semana, extrae las URLs, verifica el estado de los certificados SSL usando ssl-checker.io y envía un correo electrónico si algún certificado está por vencer en menos de 7 días.
  - **Complejidad:** Media (12 nodos)

- **[3151-dub-co-url-shortener.json](workflows/3151-dub-co-url-shortener.json)**
  - **Descripción:** Este flujo configura y automatiza la creación de enlaces cortos usando la API de Dub.co. Permite ingresar una URL larga, opcionalmente un slug personalizado y dominio, y crea o actualiza el enlace correspondiente.
  - **Complejidad:** Media (12 nodos)

- **[3341-audio-translation-flow.json](workflows/3341-audio-translation-flow.json)**
  - **Descripción:** Este flujo traduce texto al inglés, genera audio en francés, transcribe ese audio de vuelta al texto y luego lo convierte en un archivo de voz en inglés.
  - **Complejidad:** Media (12 nodos)

- **[0236-ard-podcast-scraper.json](workflows/0236-ard-podcast-scraper.json)**
  - **Descripción:** Este flujo automatizado extrae enlaces de episodios de una página web, luego obtiene y procesa la información de cada episode para generar un feed RSS completo.
  - **Complejidad:** Media (11 nodos)

- **[0282-llm-output-structured.json](workflows/0282-llm-output-structured.json)**
  - **Descripción:** Este flujo procesa solicitudes con modelos de lenguaje grandes (LLM) para generar respuestas estructuradas, utilizando un parser automático que intenta corregir salidas no válidas mediante otro modelo LLM.
  - **Complejidad:** Media (11 nodos)

- **[0326-spotify-discover-weekly-archiver.json](workflows/0326-spotify-discover-weekly-archiver.json)**
  - **Descripción:** Este flujo automático archiva los tracks de la playlist 'Discover Weekly' en Spotify comparando y añadiendo solo las canciones que no están ya presentes.
  - **Complejidad:** Media (11 nodos)

- **[0414-passport-photo-validator.json](workflows/0414-passport-photo-validator.json)**
  - **Descripción:** Este flujo automático verifica la validez de fotos de pasaporte siguiendo los criterios del gobierno británico mediante un modelo de IA.
  - **Complejidad:** Media (11 nodos)

- **[0420-xero-webhook-verifier.json](workflows/0420-xero-webhook-verifier.json)**
  - **Descripción:** Este flujo verifica la autenticidad de webhooks entrantes de Xero mediante el cálculo y comparación del hash HMAC utilizando SHA-256 para garantizar integridad y seguridad.
  - **Complejidad:** Media (11 nodos)

- **[0422-image-processing-flow.json](workflows/0422-image-processing-flow.json)**
  - **Descripción:** Este flujo procesa imágenes subidas a ImgBB, las optimiza con ReSmush.it y almacena la versión optimizada en ImgBB.
  - **Complejidad:** Media (11 nodos)

- **[0508-google-autocomplete-letter.json](workflows/0508-google-autocomplete-letter.json)**
  - **Descripción:** Este flujo combina un keyword inicial con todas las letras del alfabeto para obtener múltiples autocompletaciones de Google y devuelve la lista completa.
  - **Complejidad:** Media (11 nodos)

- **[0849-passport-photo-validation.json](workflows/0849-passport-photo-validation.json)**
  - **Descripción:** Este flujo automático verifica la validez de fotos para pasaportes siguiendo las directrices del gobierno británico mediante modelos de visión por computadora en n8n.
  - **Complejidad:** Media (11 nodos)

- **[2804-fastmail-masked-email-flow.json](workflows/2804-fastmail-masked-email-flow.json)**
  - **Descripción:** Este flujo gestiona los direcciones de correo electrónico anónimas de Fastmail mediante su API. Permite obtener una lista de correos electrónicos anonimizados, crear nuevos con estado inicial, actualizar el estado (habilitado/deshabilitado) y eliminarlos. La interfaz HTML generada muestra un listado con opciones para filtrar por estado, agregar nuevos y realizar acciones.
  - **Complejidad:** Media (11 nodos)

- **[3168-generar_palabras_clave_seo.json](workflows/3168-generar_palabras_clave_seo.json)**
  - **Descripción:** Este flujo genera nuevas palabras clave para SEO y obtiene sus volúmenes de búsqueda utilizando la API de Google Ads. Analiza las palabras clave enviadas, extrae métricas como competencia y volumen promedio mensual, y actualiza una hoja de cálculo.
  - **Complejidad:** Media (11 nodos)

- **[0090-GitHub-issue-autoassign.json](workflows/0090-GitHub-issue-autoassign.json)**
  - **Descripción:** Este flujo asigna automáticamente el autor del issue o a quién se le pide en una conversación.
  - **Complejidad:** Media (10 nodos)

- **[0192-reporte-tiempo-hilo.json](workflows/0192-reporte-tiempo-hilo.json)**
  - **Descripción:** Este flujo automático genera un informe HTML detallado a partir de registros de hoja de tiempo para usuarios y tareas.
  - **Complejidad:** Media (10 nodos)

- **[0279-gmail-appointment-autoresponder.json](workflows/0279-gmail-appointment-autoresponder.json)**
  - **Descripción:** Este flujo automatizado procesa correos electrónicos no leídos para determinar si son citas y responde apropiadamente.
  - **Complejidad:** Media (10 nodos)

- **[0348-mail-api-scraper.json](workflows/0348-mail-api-scraper.json)**
  - **Descripción:** Este flujo permite extraer direcciones de correo electrónico de cualquier sitio web mediante una solicitud HTTP a un webhook.
  - **Complejidad:** Media (10 nodos)

- **[0352-rss-monitor.json](workflows/0352-rss-monitor.json)**
  - **Descripción:** Este flujo revisa periódicamente (cada hora) múltiples fuentes RSS específicas, verifica si los artículos fueron publicados en el último ciclo horario y envía correos con las novedades.
  - **Complejidad:** Media (10 nodos)

- **[0353-gmail-archivar.json](workflows/0353-gmail-archivar.json)**
  - **Descripción:** Este flujo automático archiva los mensajes y hilos de correo en la bandeja de entrada que no están marcados como favoritos (estrellas) desde la última ejecución, dejando solo las estrelladas.
  - **Complejidad:** Media (10 nodos)

- **[0363-highlevel-address-verification.json](workflows/0363-highlevel-address-verification.json)**
  - **Descripción:** Este flujo automático verifica la dirección postal de nuevos contactos en HighLevel mediante una API de verificación y agrega un tag según si es válida o no.
  - **Complejidad:** Media (10 nodos)

- **[0431-blue-sky-rss.json](workflows/0431-blue-sky-rss.json)**
  - **Descripción:** Este flujo automatiza la publicación de artículos RSS convertidos en posts multimedia de BlueSky.
  - **Complejidad:** Media (10 nodos)

- **[0432-meal-plan-generator.json](workflows/0432-meal-plan-generator.json)**
  - **Descripción:** Este flujo automático genera un plan de comidas aleatorias basado en recetas específicas para días futuros y lo envía a la API de Mealie.
  - **Complejidad:** Media (10 nodos)

- **[0450-gitlab-merge-request-flow.json](workflows/0450-gitlab-merge-request-flow.json)**
  - **Descripción:** Este flujo automático verifica si existe una solicitud de fusión abierta con el mismo nombre de rama y, en caso afirmativo, cierra; si no existe, crea una nueva.
  - **Complejidad:** Media (10 nodos)

- **[0473-line-chatbot-memory.json](workflows/0473-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automático permite a un chatbot de LINE mantener una conversación contextualizada con los usuarios mediante el almacenamiento y recuperación de estados.
  - **Complejidad:** Media (10 nodos)

- **[0547-wallabag-ttrss-sync.json](workflows/0547-wallabag-ttrss-sync.json)**
  - **Descripción:** Este flujo automático se utiliza para guardar artículos marcados como favoritos (starred) en TT-RSS a la aplicación Wallabag.
  - **Complejidad:** Media (10 nodos)

- **[0669-event-registration.json](workflows/0669-event-registration.json)**
  - **Descripción:** Este flujo automático permite registrar asistentes y gestionar sus participaciones en n8nConf, la conferencia de no código.
  - **Complejidad:** Media (10 nodos)

- **[0682-sitemap-json-filter.json](workflows/0682-sitemap-json-filter.json)**
  - **Descripción:** Este flujo lee un archivo sitemap.xml y extrae todas sus URLs individualmente.
  - **Complejidad:** Media (10 nodos)

- **[1089-comunidad-topicos-n8n.json](workflows/1089-comunidad-topicos-n8n.json)**
  - **Descripción:** Este flujo automático monitorea temas específicos en la comunidad de n8n mediante un término de búsqueda y actualiza una hoja de cálculo con los resultados.
  - **Complejidad:** Media (10 nodos)

- **[1140-gmail-email-test.json](workflows/1140-gmail-email-test.json)**
  - **Descripción:** Este flujo automático permite enviar correos electrónicos de prueba con una imagen adjunta utilizando autenticación OAuth2 en Google Mail.
  - **Complejidad:** Media (10 nodos)

- **[0078-comida-diaria-recipe.json](workflows/0078-comida-diaria-recipe.json)**
  - **Descripción:** Este flujo automático busca recetas en Edamam según parámetros especificados, incluyendo dieta y condición de salud aleatorias si se configura así. Luego calcula el rango correcto de recetas para enviar por correo.
  - **Complejidad:** Media (9 nodos)

- **[0262-diagnostico-migracion-n8n.json](workflows/0262-diagnostico-migracion-n8n.json)**
  - **Descripción:** Este flujo identifica workflows afectados por la migración de n8n 0.214.3 en nodos con múltiple salida.
  - **Complejidad:** Media (9 nodos)

- **[0270-postgres-google-sheets-sync.json](workflows/0270-postgres-google-sheets-sync.json)**
  - **Descripción:** Este flujo automático escucha actualizaciones en la tabla de usuarios y las filtra para guardar solo aquellos que no tienen @n8n.io en el correo.
  - **Complejidad:** Media (9 nodos)

- **[0347-euro-exchange-rate-processor.json](workflows/0347-euro-exchange-rate-processor.json)**
  - **Descripción:** Este flujo automático obtiene y procesa tasas de cambio del euro en tiempo real mediante una solicitud HTTP a la API de la Reserva Europea Central.
  - **Complejidad:** Media (9 nodos)

- **[0357-auto-seo-keywords-generator.json](workflows/0357-auto-seo-keywords-generator.json)**
  - **Descripción:** Este flujo automático recibe una consulta por Webhook, genera keywords relacionadas usando el API de Google Suggest y las formatea para su uso en investigación SEO.
  - **Complejidad:** Media (9 nodos)

- **[0509-html-pdf-compress.json](workflows/0509-html-pdf-compress.json)**
  - **Descripción:** Este flujo automático permite convertir un bloque de HTML en un archivo PDF y comprimirlo, así como procesar una URL específica para generar otro PDF a partir de ella.
  - **Complejidad:** Media (9 nodos)

- **[0510-html-pdf-png-conversion.json](workflows/0510-html-pdf-png-conversion.json)**
  - **Descripción:** Este flujo n8n permite probar la conversión de HTML a PDF y su posterior conversión a PNG al hacer clic en el botón 'Test workflow'.
  - **Complejidad:** Media (9 nodos)

- **[0805-conversational-ai-search.json](workflows/0805-conversational-ai-search.json)**
  - **Descripción:** Este flujo automático permite a un chatbot mantener conversaciones contextualizadas utilizando memoria de ventana e integrando herramientas para búsqueda web.
  - **Complejidad:** Media (9 nodos)

- **[0966-email-summary-agent.json](workflows/0966-email-summary-agent.json)**
  - **Descripción:** Este flujo automatizado recopila correos electrónicos de la última jornada y los resume con IA para destacar detalles clave, problemas e instrucciones de acción, enviando un informe resumido en HTML.
  - **Complejidad:** Media (9 nodos)

- **[1050-techcrunch-scraping.json](workflows/1050-techcrunch-scraping.json)**
  - **Descripción:** Este flujo automático extrae información detallada sobre los últimos artículos de TechCrunch mediante el procesamiento secuencial del HTML y solicitudes HTTP.
  - **Complejidad:** Media (9 nodos)

- **[1075-x-publication-automation.json](workflows/1075-x-publication-automation.json)**
  - **Descripción:** Este flujo automatizado permite publicar en X utilizando el servicio Airtop, siguiendo pasos de crear sesión, abrir ventana, escribir texto y hacer clic en 'Publicar'.
  - **Complejidad:** Media (9 nodos)

- **[0136-torrent-search-transmission.json](workflows/0136-torrent-search-transmission.json)**
  - **Descripción:** Este flujo automático busca torrents en KickassTorrents y Rarbg a partir de un título proporcionado por una solicitud POST Webhook. Si se encuentra un torrent, intenta añadirlo al cliente Transmission para descargarlo. En caso de no encontrar resultados o recibir un error 409 (conflicto), notifica que la película no está disponible.
  - **Complejidad:** Media (8 nodos)

- **[0315-icypeas-email-verifier.json](workflows/0315-icypeas-email-verifier.json)**
  - **Descripción:** Este flujo automático procesa listas de correos electrónicos en lotes desde una hoja de Google, utilizando credenciales API para autenticación y realizando solicitudes HTTP POST a la plataforma Icypeas.
  - **Complejidad:** Media (8 nodos)

- **[0327-tron_wallet_monitor.json](workflows/0327-tron_wallet_monitor.json)**
  - **Descripción:** Este flujo automático consulta y procesa transacciones recientes en una billetera TRC20, mostrando información formateada sobre los tokens recibidos.
  - **Complejidad:** Media (8 nodos)

- **[0377-google_slides_image_replacer.json](workflows/0377-google_slides_image_replacer.json)**
  - **Descripción:** Este flujo automático permite reemplazar imágenes en presentaciones de Google Slides mediante una solicitud POST con parámetros como presentation_id, image_key y image_url.
  - **Complejidad:** Media (8 nodos)

- **[0629-chatbot-pizza-order.json](workflows/0629-chatbot-pizza-order.json)**
  - **Descripción:** Este flujo permite a un chatbot manejar órdenes de pizza manteniendo memoria conversacional y usando herramientas como calculadora, menú de productos e historial de pedidos.
  - **Complejidad:** Media (8 nodos)

- **[0698-matrix-room-invite.json](workflows/0698-matrix-room-invite.json)**
  - **Descripción:** Este flujo automático crea una sala de discusión en Matrix y la invita al usuario actual si no ya está invitado.
  - **Complejidad:** Media (8 nodos)

- **[0781-line-chatbot-automatic-reply.json](workflows/0781-line-chatbot-automatic-reply.json)**
  - **Descripción:** Este flujo automático permite a un bot de LINE responder automáticamente a mensajes recibidos mediante webhooks, confirmando su recepción. Además, soporta la envío manual programada de mensajes utilizando una identificación del usuario específica.
  - **Complejidad:** Media (8 nodos)

- **[1020-item-matching-example.json](workflows/1020-item-matching-example.json)**
  - **Descripción:** Este flujo utiliza la función itemMatching() en el nodo de código para modificar campos específicos de los elementos del workflow.
  - **Complejidad:** Media (8 nodos)

- **[1177-registro-betterstack.json](workflows/1177-registro-betterstack.json)**
  - **Descripción:** Este flujo permite enviar mensajes de registro a la plataforma BetterStack mediante una solicitud HTTP POST.
  - **Complejidad:** Media (8 nodos)

- **[0005-google-calendar-outlook-sync.json](workflows/0005-google-calendar-outlook-sync.json)**
  - **Descripción:** Este flujo sincroniza eventos entre Google Calendar y Microsoft Outlook, creando automáticamente eventos en Outlook cuando se añaden en Gmail y eliminándolos al cancelarse.
  - **Complejidad:** Media (7 nodos)

- **[0055-line-message-processing.json](workflows/0055-line-message-processing.json)**
  - **Descripción:** Este flujo analiza mensajes recibidos y procesa diferentes acciones según su tipo.
  - **Complejidad:** Media (7 nodos)

- **[0180-gitlab-backup.json](workflows/0180-gitlab-backup.json)**
  - **Descripción:** Este flujo automatizado permite realizar respaldos de workflows y credenciales de n8n mediante comandos de Git, que se ejecutan periódicamente o manualmente.
  - **Complejidad:** Media (7 nodos)

- **[0213-google-sheets-process-timer.json](workflows/0213-google-sheets-process-timer.json)**
  - **Descripción:** Este flujo automático verifica cada 5 minutos si hay filas no procesadas en una hoja de cálculo y las marca como tales al ejecutarse manualmente.
  - **Complejidad:** Media (7 nodos)

- **[0283-cadena-q-a.json](workflows/0283-cadena-q-a.json)**
  - **Descripción:** Este flujo configura un procesamiento de cadenas para realizar búsquedas basadas en preguntas y responderlas, utilizando asignaciones como entrada.
  - **Complejidad:** Media (7 nodos)

- **[0293-email-validation-flow.json](workflows/0293-email-validation-flow.json)**
  - **Descripción:** Este flujo verifica automáticamente la validez de una dirección de correo electrónico capturada mediante un formulario y añade el contacto a una lista si es válida.
  - **Complejidad:** Media (7 nodos)

- **[0319-fastmail-mailbox-email.json](workflows/0319-fastmail-mailbox-email.json)**
  - **Descripción:** Este flujo automático obtiene y procesa información de bandeja y correos electrónicos desde la API JMAP de Fastmail.
  - **Complejidad:** Media (7 nodos)

- **[0370-flujo-confirmacion-transferencia.json](workflows/0370-flujo-confirmacion-transferencia.json)**
  - **Descripción:** Este flujo automático verifica si un registro ya existe en Grist antes de crear uno nuevo basado en una entrada webhooks con un campo 'Confirmed' para asegurar que solo se realiza la operación cuando es necesario.
  - **Complejidad:** Media (7 nodos)

- **[0380-hacker-news-monitor.json](workflows/0380-hacker-news-monitor.json)**
  - **Descripción:** Este flujo verifica cada día a las 1:00 PM si hay artículos destacados de 'Show HN' en la página principal de Hacker News y envía un correo con los más recientes.
  - **Complejidad:** Media (7 nodos)

- **[0418-fastmail-masked-email-generator.json](workflows/0418-fastmail-masked-email-generator.json)**
  - **Descripción:** Este flujo automático permite crear direcciones de correo electrónico enmascaradas utilizando la API de Fastmail. Se inicia mediante una solicitud POST a un webhook, que procesa y genera las direcciones solicitadas con los parámetros necesarios.
  - **Complejidad:** Media (7 nodos)

- **[0424-prism-elastic-alert-email.json](workflows/0424-prism-elastic-alert-email.json)**
  - **Descripción:** Este flujo automático verifica periódicamente alerts de seguridad en un sistema Elastic y envía correos electrónicos notificando sobre incidentes detectados.
  - **Complejidad:** Media (7 nodos)

- **[0436-cleaner-old-executions.json](workflows/0436-cleaner-old-executions.json)**
  - **Descripción:** Este flujo n8n verifica ejecuciones antiguas y las elimina si tienen más de 10 días.
  - **Complejidad:** Media (7 nodos)

- **[0438-twitch-stream-checker.json](workflows/0438-twitch-stream-checker.json)**
  - **Descripción:** Este flujo verifica si un usuario de Twitch específico está realizando una transmisión en vivo consultando su API GraphQL.
  - **Complejidad:** Media (7 nodos)

- **[0454-vps-upgrade-email-checker.json](workflows/0454-vps-upgrade-email-checker.json)**
  - **Descripción:** Este flujo automático ejecuta diariamente el comando 'apt list --upgradable' vía SSH en una máquina remota y envía un correo electrónico formateado en HTML si hay paquetes actualizables.
  - **Complejidad:** Media (7 nodos)

- **[0484-merge-pdfs-from-urls.json](workflows/0484-merge-pdfs-from-urls.json)**
  - **Descripción:** Este flujo permite combinar múltiples PDFs provenientes de URLs en un solo archivo usando una función JavaScript personalizada.
  - **Complejidad:** Media (7 nodos)

- **[0485-library-install.json](workflows/0485-library-install.json)**
  - **Descripción:** Este flujo automatizado permite instalar bibliotecas de Node.js (especificadas como una lista separada por comas) mediante la ejecución de comandos npm.
  - **Complejidad:** Media (7 nodos)

- **[0522-namecheap-ddns-updater.json](workflows/0522-namecheap-ddns-updater.json)**
  - **Descripción:** Este flujo automático verifica cada 15 minutos si la IP pública ha cambiado y actualiza automáticamente en Namecheap los registros DNS de múltiples subdominios.
  - **Complejidad:** Media (7 nodos)

- **[0998-google-credentials-setup.json](workflows/0998-google-credentials-setup.json)**
  - **Descripción:** Este flujo automático permite crear múltiples credenciales OAuth2 de Google en la herramienta n8n, utilizando información proporcionada manualmente.
  - **Complejidad:** Media (7 nodos)

- **[1021-daily-digest.json](workflows/1021-daily-digest.json)**
  - **Descripción:** Este flujo automático compila un resumen diario con noticias, correos electrónicos y tareas pendientes en una sola visualización HTML.
  - **Complejidad:** Media (7 nodos)

- **[1038-kb-confluence-search-response.json](workflows/1038-kb-confluence-search-response.json)**
  - **Descripción:** Este flujo busca en Confluence información relevante basada en consultas recibidas para mejorar el soporte técnico.
  - **Complejidad:** Media (7 nodos)

- **[1070-server-monitor-n8n.json](workflows/1070-server-monitor-n8n.json)**
  - **Descripción:** Este flujo automático verifica la disponibilidad de servidores web cada minuto mediante peticiones HTTP y registra los resultados en hojas de cálculo de Google.
  - **Complejidad:** Media (7 nodos)

- **[1074-netflix-email-forwarding-gmail-mailjet.json](workflows/1074-netflix-email-forwarding-gmail-mailjet.json)**
  - **Descripción:** Este flujo automatizado envía los correos electrónicos de Netflix recibidos en la cuenta Gmail a múltiples destinatarios definidos, utilizando tanto el servicio de Gmail como Mailjet para la transmisión.
  - **Complejidad:** Media (7 nodos)

- **[1083-line-email-ai-resumen.json](workflows/1083-line-email-ai-resumen.json)**
  - **Descripción:** Este flujo automatizado utiliza un modelo de IA para leer y resumir correos electrónicos entrantes con base en IMAP a través del protocolo IMAP, destacando elementos importantes o urgentes como fechas límite mediante análisis inteligente.
  - **Complejidad:** Media (7 nodos)

- **[1256-n8n_executions_csv.json](workflows/1256-n8n_executions_csv.json)**
  - **Descripción:** Exporta un resumen de ejecuciones de n8n a un archivo CSV.
  - **Complejidad:** Media (7 nodos)

- **[2557-seatable-webhook-validate.json](workflows/2557-seatable-webhook-validate.json)**
  - **Descripción:** Este flujo verifica webhooks de Seatable mediante autenticación HMAC SHA256, respondiendo con 200 OK si el hash coincide y con 403 Forbidden en caso contrario.
  - **Complejidad:** Media (7 nodos)

- **[2566-image-generation-api.json](workflows/2566-image-generation-api.json)**
  - **Descripción:** Este flujo automático permite generar imágenes a partir de un texto (prompt) mediante una URL web.
  - **Complejidad:** Media (7 nodos)

- **[2619-line-chatbot-memory.json](workflows/2619-line-chatbot-memory.json)**
  - **Descripción:** Este flujo automatizado permite a un chatbot de LINE mantener una conversación contextualizada mediante el uso de memoria para cada usuario.
  - **Complejidad:** Media (7 nodos)

- **[2813-transform-text.json](workflows/2813-transform-text.json)**
  - **Descripción:** Este flujo transforma un texto en minúsculas, mayúsculas y reemplaza palabras específicas usando comandos echo.
  - **Complejidad:** Media (7 nodos)

- **[2881-hotel-reservation-confirmation.json](workflows/2881-hotel-reservation-confirmation.json)**
  - **Descripción:** Este flujo maneja una reserva hotelera mediante un webhook de Retell, confirma la reserva y envía una respuesta al usuario.
  - **Complejidad:** Media (7 nodos)

- **[2974-mcp_calendar_operations.json](workflows/2974-mcp_calendar_operations.json)**
  - **Descripción:** Este flujo maneja operaciones de calendario de Google como obtener eventos, verificar disponibilidad, actualizar y eliminar eventos.
  - **Complejidad:** Media (7 nodos)

- **[3067-format-phone-us.json](workflows/3067-format-phone-us.json)**
  - **Descripción:** Este flujo procesa y formatea números de teléfono estadounidenses. Extrae solo los dígitos, verifica el código de país inicial, agrega el código si falta y luego formatea el número en diferentes formatos como nacional e internacional.
  - **Complejidad:** Media (7 nodos)

- **[0033-ip-location-email.json](workflows/0033-ip-location-email.json)**
  - **Descripción:** Este flujo verifica si el usuario está en España mediante su IP y envía un correo de bienvenida en español o inglés según la ubicación detectada.
  - **Complejidad:** Media (6 nodos)

- **[0119-close-date-automation.json](workflows/0119-close-date-automation.json)**
  - **Descripción:** Este flujo automático verifica si existe una fecha de cierre y, en caso negativo, la establece a tres semanas después.
  - **Complejidad:** Media (6 nodos)

- **[0130-config-impresao.json](workflows/0130-config-impresao.json)**
  - **Descripción:** Este flujo automático consulta la configuración de impressão e informações dos rolos de tecido para emitir etiquetas.
  - **Complejidad:** Media (6 nodos)

- **[0159-strava-accountability-checker.json](workflows/0159-strava-accountability-checker.json)**
  - **Descripción:** Este flujo diario verifica que un usuario ha registrado suficiente tiempo activo en Strava (mínimo definido en las horas de responsabilidad) y envía correos motivacionales a su equipo si no lo hace.
  - **Complejidad:** Media (6 nodos)

- **[0288-line-ai-color-bot.json](workflows/0288-line-ai-color-bot.json)**
  - **Descripción:** Este flujo automatizado permite a un chatbot de línea generar respuestas con funciones específicas como seleccionar colores aleatorios.
  - **Complejidad:** Media (6 nodos)

- **[0295-brightdata-screenshot.json](workflows/0295-brightdata-screenshot.json)**
  - **Descripción:** Este flujo automático permite capturar una pantalla web usando Bright Data Web Unlocker y guardarla en un archivo local.
  - **Complejidad:** Media (6 nodos)

- **[0302-zoom-from-google-calendar.json](workflows/0302-zoom-from-google-calendar.json)**
  - **Descripción:** Este flujo automatizado crea reuniones en Zoom basándose en eventos filtrados de Google Calendar.
  - **Complejidad:** Media (6 nodos)

- **[0366-slack-to-clickup-tasks.json](workflows/0366-slack-to-clickup-tasks.json)**
  - **Descripción:** Este flujo analiza un archivo JSON
  - **Complejidad:** Media (6 nodos)

- **[0395-html-to-pdf-automation.json](workflows/0395-html-to-pdf-automation.json)**
  - **Descripción:** Este flujo automático convierte documentos HTML en PDF utilizando ConvertAPI.
  - **Complejidad:** Media (6 nodos)

- **[0408-confluence-template-automation.json](workflows/0408-confluence-template-automation.json)**
  - **Descripción:** Este flujo automatiza la creación de una página en Confluence a partir de un template predefinido. Los parámetros base URL y ID del template son fijos, mientras que el espacio objetivo y las relaciones parentales se configuran mediante un set node.
  - **Complejidad:** Media (6 nodos)

- **[0493-proyectos-coste-missing.json](workflows/0493-proyectos-coste-missing.json)**
  - **Descripción:** Este flujo automático ejecuta una consulta SQL semanal para obtener proyectos externos activos con coste presupuestado faltante y envía correos electrónicos personalizados a diferentes equipos de cost centers según sus nombres.
  - **Complejidad:** Media (6 nodos)

- **[0633-syncro-ticket-proyecto.json](workflows/0633-syncro-ticket-proyecto.json)**
  - **Descripción:** Este flujo sincroniza el estado de tickets no resueltos desde una fuente externa con sus proyectos correspondientes en Clockify.
  - **Complejidad:** Media (6 nodos)

- **[0945-convertapi-merge.json](workflows/0945-convertapi-merge.json)**
  - **Descripción:** Este flujo automático descarga dos documentos PDF desde CDN utilizando autenticación de la API de ConvertPDF y luego los fusiona en un solo archivo para guardarlo.
  - **Complejidad:** Media (6 nodos)

- **[1028-lark-message-sender.json](workflows/1028-lark-message-sender.json)**
  - **Descripción:** Este flujo automático permite obtener un token de autenticación para Larksuite y posteriormente enviar un mensaje de texto a una conversación específica.
  - **Complejidad:** Media (6 nodos)

- **[1033-icypeas-email-verification.json](workflows/1033-icypeas-email-verification.json)**
  - **Descripción:** Este flujo verifica un correo electrónico único en Icypeas mediante una solicitud HTTP seguida de autenticación.
  - **Complejidad:** Media (6 nodos)

- **[1034-icypeas-domain-search.json](workflows/1034-icypeas-domain-search.json)**
  - **Descripción:** Este flujo automatizado realiza búsquedas de dominio utilizando la API de Icypeas.
  - **Complejidad:** Media (6 nodos)

- **[1116-quickbase-registros-n8n.json](workflows/1116-quickbase-registros-n8n.json)**
  - **Descripción:** Este flujo permite crear, actualizar y obtener registros en Quick Base mediante nodos configurados.
  - **Complejidad:** Media (6 nodos)

- **[2682-compare-datasets-frutas.json](workflows/2682-compare-datasets-frutas.json)**
  - **Descripción:** Este flujo compara dos datasets de frutas y colores usando el nodo Compare Datasets para identificar diferencias.
  - **Complejidad:** Media (6 nodos)

- **[2976-ai-research-jina.json](workflows/2976-ai-research-jina.json)**
  - **Descripción:** Este flujo automático utiliza la API de DeepSearch de Jina AI para realizar búsquedas y análisis en profundidad, formatear y limpiar las respuestas generadas por el modelo de IA.
  - **Complejidad:** Media (6 nodos)

- **[0038-orbit-member-update.json](workflows/0038-orbit-member-update.json)**
  - **Descripción:** Este flujo automatiza la creación y actualización de un miembro en Orbit, añade sus etiquetas, crea una nota personalizada para él y publica un artículo existente en su perfil.
  - **Complejidad:** Media (5 nodos)

- **[0041-filemaker-multi-step.json](workflows/0041-filemaker-multi-step.json)**
  - **Descripción:** Este flujo automático ejecuta acciones secuenciales de FileMaker: primero crea un registro en 'My Form Layout', luego edita el país en la misma tabla y finalmente consulta un registro existente.
  - **Complejidad:** Media (5 nodos)

- **[0074-getresponse-contact-update-flow.json](workflows/0074-getresponse-contact-update-flow.json)**
  - **Descripción:** Este flujo automático permite obtener todos los contactos de GetResponse y actualizar su campo campaignId si la campaña no es igual a 'n8n'.
  - **Complejidad:** Media (5 nodos)

- **[0198-csv-conversion.json](workflows/0198-csv-conversion.json)**
  - **Descripción:** Este flujo le permite leer un archivo CSV, procesarlo como una hoja de cálculo y convertirlo a formato JSON para almacenamiento.
  - **Complejidad:** Media (5 nodos)

- **[0266-mssql-to-csv.json](workflows/0266-mssql-to-csv.json)**
  - **Descripción:** Este flujo permite ejecutar una consulta SQL en la tabla 'SalesLT.ProductCategory' y guardar el resultado como un archivo CSV con ese nombre.
  - **Complejidad:** Media (5 nodos)

- **[0273-outlook-automated-email.json](workflows/0273-outlook-automated-email.json)**
  - **Descripción:** Este flujo automático permite a un usuario crear automáticamente un borrador de correo electrónico en Outlook, adjuntar una imagen descargada y enviarlo.
  - **Complejidad:** Media (5 nodos)

- **[0375-email-validation-domain-extraction.json](workflows/0375-email-validation-domain-extraction.json)**
  - **Descripción:** Este flujo prueba la validación de direcciones de correo electrónico y extrae el dominio utilizando funciones nativas de n8n.
  - **Complejidad:** Media (5 nodos)

- **[0391-convertir-pptx-a-json.json](workflows/0391-convertir-pptx-a-json.json)**
  - **Descripción:** Este flujo automático descarga un archivo PPTX de demostración, lo convierte a PDF usando ConvertAPI autenticado y guarda el resultado como 'document.pdf' en el sistema local.
  - **Complejidad:** Media (5 nodos)

- **[0393-2310_webpage-to-pdf_test.json](workflows/0393-2310_webpage-to-pdf_test.json)**
  - **Descripción:** Este flujo de prueba convierte la página web https://n8n.io en un archivo PDF y lo guarda como document.pdf.
  - **Complejidad:** Media (5 nodos)

- **[0396-convertapi-jpg-to-pdf.json](workflows/0396-convertapi-jpg-to-pdf.json)**
  - **Descripción:** Este flujo automático descarga una imagen demo y convierte el archivo JPG al formato PDF utilizando la API de ConvertAPI.
  - **Complejidad:** Media (5 nodos)

- **[0397-convertapi-pdf-conversion.json](workflows/0397-convertapi-pdf-conversion.json)**
  - **Descripción:** Este flujo automatizado descarga un archivo demo, lo convierte a formato PDFA utilizando la API de ConvertAPI y escribe el resultado en un archivo PDFA.
  - **Complejidad:** Media (5 nodos)

- **[0407-n8n-totp-authentication.json](workflows/0407-n8n-totp-authentication.json)**
  - **Descripción:** Este flujo verifica la validez de un código TOTP introducido utilizando el secreto proporcionado.
  - **Complejidad:** Media (5 nodos)

- **[0661-weather-alert.json](workflows/0661-weather-alert.json)**
  - **Descripción:** Este flujo automático consulta cada cierto tiempo la temperatura en Berlín y envía un mensaje de texto notificando que es necesario abrigarse si el valor actual del 'sentimiento' está por debajo de los 18 grados Celsius.
  - **Complejidad:** Media (5 nodos)

- **[0719-n8n_rss_photo_filter.json](workflows/0719-n8n_rss_photo_filter.json)**
  - **Descripción:** Este flujo obtiene RSS feeds nuevos de The Verge que contienen imágenes.
  - **Complejidad:** Media (5 nodos)

- **[0766-demo-batch.json](workflows/0766-demo-batch.json)**
  - **Descripción:** Este flujo utiliza el nodo Function para generar una lista de items y luego aplica SplitInBatches con tamaño de lote 1 para procesarlos en lotes individuales, verificando si quedan elementos pendientes.
  - **Complejidad:** Media (5 nodos)

- **[0767-split-batch-test.json](workflows/0767-split-batch-test.json)**
  - **Descripción:** Este flujo utiliza un trigger manual para iniciar una ejecución que genera 10 elementos numéricos y los procesa de uno en uno mediante SplitInBatches, verificando si el índice actual es igual a 5.
  - **Complejidad:** Media (5 nodos)

- **[0986-extract-lp.json](workflows/0986-extract-lp.json)**
  - **Descripción:** Este flujo permite extraer automáticamente el número de matrícula de imágenes subidas mediante formulario.
  - **Complejidad:** Media (5 nodos)

- **[1023-get-bible-api-adapter.json](workflows/1023-get-bible-api-adapter.json)**
  - **Descripción:** Este flujo permite convertir una lista de referencias bíblicas estructuradas en un formato compatible para consulta vía la API de GetBible.
  - **Complejidad:** Media (5 nodos)

- **[1024-clicksend-tts.json](workflows/1024-clicksend-tts.json)**
  - **Descripción:** Este flujo utiliza n8n para enviar mensajes de voz sintetizada a través del servicio ClickSend mediante una API REST. Permite crear un formulario donde los usuarios pueden ingresar texto (body), número destino, elegir entre voz masculina o femenina y seleccionar el idioma.
  - **Complejidad:** Media (5 nodos)

- **[1026-factura-pdf-jsreport.json](workflows/1026-factura-pdf-jsreport.json)**
  - **Descripción:** Este flujo permite ingresar información de factura mediante un formulario y genera automáticamente un documento PDF utilizando JSReport, que luego se adjunta en un correo electrónico.
  - **Complejidad:** Media (5 nodos)

- **[1040-auto_resume_disabled_workflows.json](workflows/1040-auto_resume_disabled_workflows.json)**
  - **Descripción:** Este flujo automático busca workflows con auto-resume habilitado y que estén desactivados, luego los activa para mantener el estado correcto.
  - **Complejidad:** Media (5 nodos)

- **[1046-gmail-api-automation.json](workflows/1046-gmail-api-automation.json)**
  - **Descripción:** Este flujo automático permite enviar y recibir correos electrónicos mediante la API de Gmail, utilizando un único conjunto de credenciales OAuth2 para las distintas operaciones.
  - **Complejidad:** Media (5 nodos)

- **[1080-ai-stock-analysis.json](workflows/1080-ai-stock-analysis.json)**
  - **Descripción:** Este flujo analiza gráficos de acciones o criptomonedas a través de imágenes utilizando IA y devuelve un análisis técnico simplificado en términos infantiles.
  - **Complejidad:** Media (5 nodos)

- **[1172-pdf-generator.json](workflows/1172-pdf-generator.json)**
  - **Descripción:** Este flujo automático permite generar documentos PDF basados en plantillas HTML predefinidas. Recibe información estructurada como detalles de factura, calcula montos automáticamente y convierte la estructura completa en un archivo PDF utilizando bibliotecas externas.
  - **Complejidad:** Media (5 nodos)

- **[2589-csv_to_excel_conversion.json](workflows/2589-csv_to_excel_conversion.json)**
  - **Descripción:** Este flujo automatizado importa un archivo CSV de una URL específica y lo convierte a formato .xlsx.
  - **Complejidad:** Media (5 nodos)

- **[2630-dumpling-ai-maps-business-leads.json](workflows/2630-dumpling-ai-maps-business-leads.json)**
  - **Descripción:** Este flujo automático permite extraer información de lugares comerciales de Google Maps mediante la API de Dumpling AI y guardarla en una hoja de cálculo estructurada.
  - **Complejidad:** Media (5 nodos)

- **[0013-bitwarden-line-sync.json](workflows/0013-bitwarden-line-sync.json)**
  - **Descripción:** Este flujo automático crea un nuevo grupo en Bitwarden, obtiene la lista de miembros del chatbot de LINE para sincronizar suscripciones, actualiza los miembros dentro del grupo creado y finalmente verifica el resultado obtenido.
  - **Complejidad:** Baja (4 nodos)

- **[0028-verificacion-email-deliverable.json](workflows/0028-verificacion-email-deliverable.json)**
  - **Descripción:** Este flujo verifica si el correo electrónico 'mcolomer@gmail.com' es válido y entregable utilizando un servicio externo.
  - **Complejidad:** Baja (4 nodos)

- **[0061-flujo-buscar-empresa.json](workflows/0061-flujo-buscar-empresa.json)**
  - **Descripción:** Este flujo busca y verifica la existencia de una empresa por su nombre usando un servicio externo.
  - **Complejidad:** Baja (4 nodos)

- **[0187-165_create_update_get_user_iterable.json](workflows/0187-165_create_update_get_user_iterable.json)**
  - **Descripción:** Este flujo permite crear, actualizar y recuperar información de usuarios a través de la API de Iterable.
  - **Complejidad:** Baja (4 nodos)

- **[0202-twist-channel-automation.json](workflows/0202-twist-channel-automation.json)**
  - **Descripción:** Este flujo automático permite crear un nuevo canal en Twist y luego enviarle una notificación personalizada con un enlace de acción al usuario.
  - **Complejidad:** Baja (4 nodos)

- **[0217-gestionar-correos-eliminar-y-agregar.json](workflows/0217-gestionar-correos-eliminar-y-agregar.json)**
  - **Descripción:** Este flujo permite obtener mensajes de Gmail marcados con una etiqueta específica, eliminar dicha etiqueta y añadir otra nueva.
  - **Complejidad:** Baja (4 nodos)

- **[0255-iss-position-rabbitmq.json](workflows/0255-iss-position-rabbitmq.json)**
  - **Descripción:** Este flujo envía cada minuto la posición actualizada de la Estación Espacial Internacional (ISS) a una cola RabbitMQ.
  - **Complejidad:** Baja (4 nodos)

- **[0263-egoi-suscriptor-creacion_actualizacion_recuperacion.json](workflows/0263-egoi-suscriptor-creacion_actualizacion_recuperacion.json)**
  - **Descripción:** Este flujo permite crear un suscriptor en una lista específica de e-goi, modificar luego algunos campos (como el nombre) y finalmente obtener los detalles actualizados del contacto.
  - **Complejidad:** Baja (4 nodos)

- **[0335-sendgrid-contact-flow.json](workflows/0335-sendgrid-contact-flow.json)**
  - **Descripción:** Este flujo permite crear, actualizar y obtener información de contactos en SendGrid a través del nodo SendGrid.
  - **Complejidad:** Baja (4 nodos)

- **[0359-crea_actualiza_y_consulta_usuario_gsuite.json](workflows/0359-crea_actualiza_y_consulta_usuario_gsuite.json)**
  - **Descripción:** Este flujo crea un usuario en Google Workspace usando el nodo de administrador y luego lo actualiza y obtiene para confirmar los cambios.
  - **Complejidad:** Baja (4 nodos)

- **[0360-gmail-error-alert.json](workflows/0360-gmail-error-alert.json)**
  - **Descripción:** Este flujo automático detecta errores en ejecuciones de otros trabajos y envía un correo detallado al usuario a través de la cuenta Gmail configurada.
  - **Complejidad:** Baja (4 nodos)

- **[0434-convertkit-list-subscribe-tag.json](workflows/0434-convertkit-list-subscribe-tag.json)**
  - **Descripción:** Este flujo manual permite agregar un suscriptor a una lista de ConvertKit específicamente identificada mediante su ID, crear una etiqueta asociada y añadir al mismo suscriptor existente en esa lista a la nueva etiqueta.
  - **Complejidad:** Baja (4 nodos)

- **[0532-hackernoon-extractor.json](workflows/0532-hackernoon-extractor.json)**
  - **Descripción:** Este flujo manual extrae los títulos y enlaces de artículos desde la página principal de Hacker Noon (hackernoon.com) mediante análisis HTML.
  - **Complejidad:** Baja (4 nodos)

- **[0635-api-reqres-interactions.json](workflows/0635-api-reqres-interactions.json)**
  - **Descripción:** Este flujo realiza una solicitud GET a la API de usuarios de reqres.in, seguida de un POST para crear un usuario y finalmente un PATCH para actualizar su job.
  - **Complejidad:** Baja (4 nodos)

- **[0708-workflow-timer-unique.json](workflows/0708-workflow-timer-unique.json)**
  - **Descripción:** Este flujo revisa las conexiones de un workflow en n8n para detectar si hay nuevos elementos de entrada que no han sido procesados antes, basándose en la marca de tiempo.
  - **Complejidad:** Baja (4 nodos)

- **[0731-security-scorecard-context-management.json](workflows/0731-security-scorecard-context-management.json)**
  - **Descripción:** Este flujo automático inicia manualmente, genera un scorecard de seguridad para 'n8n.io', obtiene una sola instancia del informe y lo descarga desde la URL proporcionada.
  - **Complejidad:** Baja (4 nodos)

- **[0736-discourse-automated.json](workflows/0736-discourse-automated.json)**
  - **Descripción:** Este flujo automatizado permite crear, actualizar y recuperar mensajes en Discourse utilizando n8n.
  - **Complejidad:** Baja (4 nodos)

- **[0741-strava-activity-flow.json](workflows/0741-strava-activity-flow.json)**
  - **Descripción:** Este flujo automático permite crear actividades en Strava con parámetros específicos, actualizarlas usando el ID obtenido anteriormente y obtener información sobre ellas.
  - **Complejidad:** Baja (4 nodos)

- **[0744-raindrop-automations.json](workflows/0744-raindrop-automations.json)**
  - **Descripción:** Este flujo automatizado utiliza Raindrop para crear y actualizar notas de forma secuencial.
  - **Complejidad:** Baja (4 nodos)

- **[0753-mailerlite-suscriptor.json](workflows/0753-mailerlite-suscriptor.json)**
  - **Descripción:** Este flujo de trabajo utiliza nodos MailerLite para crear, actualizar y obtener detalles de suscriptores basado en el correo electrónico.
  - **Complejidad:** Baja (4 nodos)

- **[0762-line-chatbot-automations.json](workflows/0762-line-chatbot-automations.json)**
  - **Descripción:** Este flujo configura procesos automáticos para LINE Chatbots utilizando nodos Autopilot de n8n y pasando parámetros entre ellos.
  - **Complejidad:** Baja (4 nodos)

- **[0764-wise-eur-transfer-flow.json](workflows/0764-wise-eur-transfer-flow.json)**
  - **Descripción:** Este flujo automático utiliza la API de Wise para crear y ejecutar transferencias monetarias entre cuentas.
  - **Complejidad:** Baja (4 nodos)

- **[0992-monitor-urls-periodico.json](workflows/0992-monitor-urls-periodico.json)**
  - **Descripción:** Este flujo n8n verifica periódicamente tres URLs específicas mediante peticiones HTTP, útil para monitorear recursos o servicios web.
  - **Complejidad:** Baja (4 nodos)

- **[1095-travis-ci-trigger.json](workflows/1095-travis-ci-trigger.json)**
  - **Descripción:** Este flujo de trabajo activa builds en Travis CI cuando ocurre un evento 'push' o una acción 'opened' en el repositorio 'n8n-io/n8n'.
  - **Complejidad:** Baja (4 nodos)

- **[1098-eliminar-mensajes-gmail-batches.json](workflows/1098-eliminar-mensajes-gmail-batches.json)**
  - **Descripción:** Este flujo automático permite eliminar mensajes antiguos de Gmail mediante operaciones por lotes.
  - **Complejidad:** Baja (4 nodos)

- **[1120-gmail-email-csv.json](workflows/1120-gmail-email-csv.json)**
  - **Descripción:** Descarga un correo de Gmail con un archivo JSON y convierte su información en un CSV para hojas de cálculo.
  - **Complejidad:** Baja (4 nodos)

- **[1191-rss-feed-multi-source.json](workflows/1191-rss-feed-multi-source.json)**
  - **Descripción:** Este flujo lee dos flujos RSS de fuentes diferentes utilizando el nodo rssFeedRead.
  - **Complejidad:** Baja (4 nodos)

- **[1202-gmail-emails-monitor.json](workflows/1202-gmail-emails-monitor.json)**
  - **Descripción:** Este flujo monitoriza el correo electrónico de Gmail y añade automáticamente cada mensaje recibido como una nueva fila en una hoja de cálculo
  - **Complejidad:** Baja (4 nodos)

- **[1218-pdfmonkey-document-generation.json](workflows/1218-pdfmonkey-document-generation.json)**
  - **Descripción:** Este flujo automático detecta cuando PDFMonkey genera un documento y descarga el archivo PDF si la generación es exitosa.
  - **Complejidad:** Baja (4 nodos)

- **[2631-email-to-tasks.json](workflows/2631-email-to-tasks.json)**
  - **Descripción:** Este flujo crea tareas en Google Tasks automáticamente al recibir un nuevo correo con la etiqueta 'To-Do'.
  - **Complejidad:** Baja (4 nodos)

- **[2645-v1-param-audit.json](workflows/2645-v1-param-audit.json)**
  - **Descripción:** Este flujo analiza los parámetros de todos los nodos en flujos activos para identificar aquellos que contienen expresiones afectadas por cambios en n8n v1.
  - **Complejidad:** Baja (4 nodos)

- **[0025-google-slides-thumbnail.json](workflows/0025-google-slides-thumbnail.json)**
  - **Descripción:** Este flujo automático permite descargar una miniatura de página específica en Google Slides después de haber obtenido previamente todos los slides de la presentación.
  - **Complejidad:** Baja (3 nodos)

- **[0057-uptime-robot-monitor-management.json](workflows/0057-uptime-robot-monitor-management.json)**
  - **Descripción:** Este flujo automatizado utiliza UptimeRobot para gestionar monitoreos web: primero crea un monitor con los parámetros dados, luego lo actualiza inmediatamente y finalmente obtiene el estado del monitor existente.
  - **Complejidad:** Baja (3 nodos)

- **[0063-standup-bot-config.json](workflows/0063-standup-bot-config.json)**
  - **Descripción:** Este flujo automático permite al bot de standup cargar una configuración desde un archivo local.
  - **Complejidad:** Baja (3 nodos)

- **[0067-obtener-registros-dns.json](workflows/0067-obtener-registros-dns.json)**
  - **Descripción:** Este flujo automático obtiene los registros DNS de un dominio específico usando n8n.
  - **Complejidad:** Baja (3 nodos)

- **[0068-line-chatbot-config-override.json](workflows/0068-line-chatbot-config-override.json)**
  - **Descripción:** Este flujo permite actualizar la configuración del chatbot mediante un trigger manual y guardarla en formato binario.
  - **Complejidad:** Baja (3 nodos)

- **[0069-line-weather-kelvin.json](workflows/0069-line-weather-kelvin.json)**
  - **Descripción:** Este flujo automático envía un mensaje de actualización del clima cada día a las 9:00 AM con la temperatura actual en Kelvin (grados Celsius) para Berlin mediante LINE.
  - **Complejidad:** Baja (3 nodos)

- **[0135-dominio-email-extractor.json](workflows/0135-dominio-email-extractor.json)**
  - **Descripción:** Este flujo extrae el dominio de un correo electrónico proporcionado mediante una función.
  - **Complejidad:** Baja (3 nodos)

- **[0148-daily-weather-spontit.json](workflows/0148-daily-weather-spontit.json)**
  - **Descripción:** Este flujo automático verifica cada día a las 9 de la mañana las condiciones climáticas actuales en Berlin y envía una notificación push al usuario con la temperatura actual.
  - **Complejidad:** Baja (3 nodos)

- **[0151-line-chatbot-response-token.json](workflows/0151-line-chatbot-response-token.json)**
  - **Descripción:** Este flujo procesa solicitudes webhooks de LINE, utilizando HMAC SHA256 sobre un token recibido y almacenando el resultado como 'response_token' para mantener memoria contextualizada.
  - **Complejidad:** Baja (3 nodos)

- **[0153-145-traductor-cocinas.json](workflows/0153-145-traductor-cocinas.json)**
  - **Descripción:** Este flujo automatizado permite obtener instrucciones de cóctel desde una API y traducirlas automáticamente al italiano.
  - **Complejidad:** Baja (3 nodos)

- **[0160-sendy-subscribe-campaign.json](workflows/0160-sendy-subscribe-campaign.json)**
  - **Descripción:** Este flujo automático permite añadir un suscriptor a una lista y crear/enviar una campaña cuando se activa manualmente.
  - **Complejidad:** Baja (3 nodos)

- **[0171-if-condition-checker.json](workflows/0171-if-condition-checker.json)**
  - **Descripción:** Este flujo toma una salida JSON predefinida, la parsea y luego comprueba si el valor de 'value1' (que siempre es true en este ejemplo) cumple con la condición esperada.
  - **Complejidad:** Baja (3 nodos)

- **[0189-url-shortener-stats.json](workflows/0189-url-shortener-stats.json)**
  - **Descripción:** Este flujo n8n crea una URL corta de un enlace proporcionado y luego obtiene estadísticas sobre el rendimiento y alcance de esa misma URL acortada.
  - **Complejidad:** Baja (3 nodos)

- **[0212-mysql-gsheets-semanal.json](workflows/0212-mysql-gsheets-semanal.json)**
  - **Descripción:** Este flujo automatizado ejecuta una consulta SQL semanalmente en la tabla de libros y escribe el resultado en una hoja de Google.
  - **Complejidad:** Baja (3 nodos)

- **[0232-agregar-archivo-json-a-hoja-google.json](workflows/0232-agregar-archivo-json-a-hoja-google.json)**
  - **Descripción:** Este flujo lee un archivo JSON y lo agrega en las hojas de cálculo Google.
  - **Complejidad:** Baja (3 nodos)

- **[0269-download-pdf-robot.json](workflows/0269-download-pdf-robot.json)**
  - **Descripción:** Este flujo automático permite descargar un archivo PDF específico de Deutsche Bahn cuando se recibe una solicitud GET en el webhook.
  - **Complejidad:** Baja (3 nodos)

- **[0297-imagen-texto-automatico.json](workflows/0297-imagen-texto-automatico.json)**
  - **Descripción:** Este flujo automático permite descargar una imagen de la internet y agregar texto a ella.
  - **Complejidad:** Baja (3 nodos)

- **[0445-sentry-release-flow.json](workflows/0445-sentry-release-flow.json)**
  - **Descripción:** Este flujo automático permite crear una nueva versión de un proyecto en Sentry y luego obtener todas las versiones existentes.
  - **Complejidad:** Baja (3 nodos)

- **[0459-imagen-gen-config.json](workflows/0459-imagen-gen-config.json)**
  - **Descripción:** Este flujo n8n permite generar imágenes personalizadas a partir de parámetros definidos en los nodos Set Image Properties.
  - **Complejidad:** Baja (3 nodos)

- **[0464-telegram-affirmations-daily.json](workflows/0464-telegram-affirmations-daily.json)**
  - **Descripción:** Este flujo automático ejecuta un script todos los días a las 9 AM para obtener y enviar un mensaje de afirmación diario mediante la API de affirmations.dev.
  - **Complejidad:** Baja (3 nodos)

- **[0488-crear_cliente_segment.json](workflows/0488-crear_cliente_segment.json)**
  - **Descripción:** Este flujo automatizado crea un nuevo cliente en Customer.io con la propiedad personalizada 'Name' configurada y luego añade inmediatamente a ese cliente a un segmento especificado.
  - **Complejidad:** Baja (3 nodos)

- **[0608-analisis-imagen-http.json](workflows/0608-analisis-imagen-http.json)**
  - **Descripción:** Este flujo manual permite descargar una imagen de un URL específica y extraer información sobre ella.
  - **Complejidad:** Baja (3 nodos)

- **[0611-telegram-cocktails-daily.json](workflows/0611-telegram-cocktails-daily.json)**
  - **Descripción:** Este flujo automático envía cada día a las 20:00 un cóctel aleatorio de TheCocktailDB mediante una foto con su receta.
  - **Complejidad:** Baja (3 nodos)

- **[0613-manual-trigger-renamer.json](workflows/0613-manual-trigger-renamer.json)**
  - **Descripción:** Este flujo se activa manualmente y luego establece un valor para la clave 'somevalue', que posteriormente es renombrada a 'newkey'.
  - **Complejidad:** Baja (3 nodos)

- **[0616-pdf-binario-lector.json](workflows/0616-pdf-binario-lector.json)**
  - **Descripción:** Este flujo automático, al hacer clic en 'execute', lee un archivo PDF binario almacenado localmente y lo procesa.
  - **Complejidad:** Baja (3 nodos)

- **[0677-mindee-receipt-extractor.json](workflows/0677-mindee-receipt-extractor.json)**
  - **Descripción:** Este flujo automático procesa una imagen de recibo utilizando Mindee para extraer información estructurada y devuelve el resultado en formato JSON.
  - **Complejidad:** Baja (3 nodos)

- **[0710-hoja-calc-binaria-lector.json](workflows/0710-hoja-calc-binaria-lector.json)**
  - **Descripción:** Este flujo lee un archivo de hoja de cálculo binario y lo almacena en memoria.
  - **Complejidad:** Baja (3 nodos)

- **[0743-quickbooks-cliente-factura.json](workflows/0743-quickbooks-cliente-factura.json)**
  - **Descripción:** Este flujo automático permite crear un cliente en QuickBooks y luego enviar una factura existente relacionada con ese ID.
  - **Complejidad:** Baja (3 nodos)

- **[0748-webinar-creation-update.json](workflows/0748-webinar-creation-update.json)**
  - **Descripción:** Este flujo automático crea una sesión web para el webinar 'Getting started with n8n', luego actualiza su descripción y finalmente ejecuta la acción de webinar.
  - **Complejidad:** Baja (3 nodos)

- **[0749-emelia-campaign-contact.json](workflows/0749-emelia-campaign-contact.json)**
  - **Descripción:** Este flujo automatizado crea una campaña de marketing en Emelia y agrega un contacto a dicha campaña.
  - **Complejidad:** Baja (3 nodos)

- **[0997-netsuite-suiteql-query.json](workflows/0997-netsuite-suiteql-query.json)**
  - **Descripción:** Este flujo permite ejecutar consultas SuiteQL en NetSuite y recibir los resultados a través de un webhook.
  - **Complejidad:** Baja (3 nodos)

- **[1100-gotify-weather-update.json](workflows/1100-gotify-weather-update.json)**
  - **Descripción:** Este flujo automático se dispara cada día a las 9:00 mediante un nodo Cron y obtiene la temperatura actual de Berlin usando OpenWeatherMap. Luego, utiliza Gotify para enviar una notificación con esta información como parte del mensaje.
  - **Complejidad:** Baja (3 nodos)

- **[1178-email-body-parser.json](workflows/1178-email-body-parser.json)**
  - **Descripción:** Este flujo analiza el cuerpo de un correo electrónico para extraer campos específicos del mensaje y almacenarlos como variables individuales en la nube.
  - **Complejidad:** Baja (3 nodos)

- **[1214-pdf-extractor.json](workflows/1214-pdf-extractor.json)**
  - **Descripción:** Este flujo permite descargar un PDF mediante una solicitud HTTP y extraer específicamente las páginas 2-3 para su procesamiento.
  - **Complejidad:** Baja (3 nodos)

- **[2817-eleven-labs-transcript.json](workflows/2817-eleven-labs-transcript.json)**
  - **Descripción:** Este flujo automatiza la creación de transcripciones de audio usando Eleven Labs. Inicia con un clic en 'Test workflow', lee el archivo multimedia desde el disco (/files/tmp/tst1.mp4), y lo procesa para obtener una transcripción enviando una solicitud POST a la API de Eleven Labs.
  - **Complejidad:** Baja (3 nodos)

- **[0011-totp-generator.json](workflows/0011-totp-generator.json)**
  - **Descripción:** Este flujo de trabajo genera códigos TOTP automáticamente al ejecutar el botón 'Test workflow'.
  - **Complejidad:** Baja (2 nodos)

- **[0034-clearbit-persona-buscar.json](workflows/0034-clearbit-persona-buscar.json)**
  - **Descripción:** Este flujo permite buscar información detallada de una persona utilizando su correo electrónico mediante la API Clearbit.
  - **Complejidad:** Baja (2 nodos)

- **[0083-harvest-cliente-ciclo.json](workflows/0083-harvest-cliente-ciclo.json)**
  - **Descripción:** Este flujo n8n permite crear un cliente en Harvest mediante una ejecución manual.
  - **Complejidad:** Baja (2 nodos)

- **[0092-segment-track-event.json](workflows/0092-segment-track-event.json)**
  - **Descripción:** Este flujo permite enviar un evento manualmente a Segment cuando se activa mediante el botón 'execute'.
  - **Complejidad:** Baja (2 nodos)

- **[0104-vero-profile-creation.json](workflows/0104-vero-profile-creation.json)**
  - **Descripción:** Este flujo manual permite crear perfiles de usuario en Vero mediante una ejecución directa, utilizando los parámetros definidos en el nodo Vero.
  - **Complejidad:** Baja (2 nodos)

- **[0113-webhook-html-response.json](workflows/0113-webhook-html-response.json)**
  - **Descripción:** Este flujo básico configura un webhook que escucha la ruta 'my-form' y responde con un HTML que incluye Bootstrap.
  - **Complejidad:** Baja (2 nodos)

- **[0114-flujo-tareas.json](workflows/0114-flujo-tareas.json)**
  - **Descripción:** Este flujo permite obtener todas las tareas de un flujo específico mediante un trigger manual.
  - **Complejidad:** Baja (2 nodos)

- **[0144-funcion-hoy.json](workflows/0144-funcion-hoy.json)**
  - **Descripción:** Este flujo utiliza el nodo Function para obtener la fecha actual en formato ISO y el día de la semana.
  - **Complejidad:** Baja (2 nodos)

- **[0147-set-variables-flujo.json](workflows/0147-set-variables-flujo.json)**
  - **Descripción:** Este flujo utiliza un trigger manual para ejecutar un nodo Set, que permite definir valores predeterminados para distintas variables en base al tipo especificado.
  - **Complejidad:** Baja (2 nodos)

- **[0168-Onfleet-to-QuickBooks-Invoices.json](workflows/0168-Onfleet-to-QuickBooks-Invoices.json)**
  - **Descripción:** Este flujo automático crea una factura en QuickBooks Online cuando se genera un nuevo tareas en Onfleet.
  - **Complejidad:** Baja (2 nodos)

- **[0173-sinonimos_aleman_openthesaurus_api.json](workflows/0173-sinonimos_aleman_openthesaurus_api.json)**
  - **Descripción:** Este flujo permite obtener los sinónimos de un término en alemán utilizando la API de OpenThesaurus.
  - **Complejidad:** Baja (2 nodos)

- **[0296-calendario-eventos.json](workflows/0296-calendario-eventos.json)**
  - **Descripción:** Este flujo automático permite añadir eventos a la agenda de Gmail especificados manualmente al iniciar una ejecución.
  - **Complejidad:** Baja (2 nodos)

- **[0463-add-task-google.json](workflows/0463-add-task-google.json)**
  - **Descripción:** Este flujo manual permite añadir una tarea específica de Google Tasks mediante un clic ejecutando el nodo correspondiente.
  - **Complejidad:** Baja (2 nodos)

- **[0521-mailchimp-subscribe.json](workflows/0521-mailchimp-subscribe.json)**
  - **Descripción:** Este flujo manual permite suscribirse a la lista de Mailchimp con el correo electrónico especificado y añadir campos predefinidos como FNAME.
  - **Complejidad:** Baja (2 nodos)

- **[0529-active-campaign-contact.json](workflows/0529-active-campaign-contact.json)**
  - **Descripción:** Este flujo permite cargar manualmente información de los usuarios a ActiveCampaign desde n8n.
  - **Complejidad:** Baja (2 nodos)

- **[0561-flujo-verificacion-email-hunter.json](workflows/0561-flujo-verificacion-email-hunter.json)**
  - **Descripción:** Este flujo automático verifica el correo electrónico utilizando la API de Hunter cuando se activa manualmente.
  - **Complejidad:** Baja (2 nodos)

- **[0563-mailjet-correo-test.json](workflows/0563-mailjet-correo-test.json)**
  - **Descripción:** Este flujo manual permite enviar un correo electrónico utilizando Mailjet. Se incluye texto predefinido, asunto, dirección de envío y dirección del destinatario.
  - **Complejidad:** Baja (2 nodos)

- **[0570-travis-ci-trigger-build.json](workflows/0570-travis-ci-trigger-build.json)**
  - **Descripción:** Este flujo manual permite iniciar un build en Travis CI haciendo clic, integrando el servicio de manera automatizada.
  - **Complejidad:** Baja (2 nodos)

- **[0572-invoice-ninja-getall.json](workflows/0572-invoice-ninja-getall.json)**
  - **Descripción:** Este flujo manual permite obtener todos los facturas de la cuenta usando el servicio de API de Invoice Ninja.
  - **Complejidad:** Baja (2 nodos)

- **[0580-xero-get-all.json](workflows/0580-xero-get-all.json)**
  - **Descripción:** Este flujo manual permite iniciar la ejecución para obtener todos los ítems de Xero mediante autenticación OAuth2.
  - **Complejidad:** Baja (2 nodos)

- **[0582-bannerbear-imagen-manual.json](workflows/0582-bannerbear-imagen-manual.json)**
  - **Descripción:** Este flujo automático permite a un usuario iniciar manualmente la generación de una imagen utilizando el servicio Bannerbear con un identificador específico y parámetros predefinidos para texto, color y fondo.
  - **Complejidad:** Baja (2 nodos)

- **[0606-n8n-rocks-crypto-example.json](workflows/0606-n8n-rocks-crypto-example.json)**
  - **Descripción:** Este flujo manual permite ejecutar una operación de cifrado en la cadena 'n8n rocks!' simplemente haciendo clic.
  - **Complejidad:** Baja (2 nodos)

- **[0607-manual-execute-date.json](workflows/0607-manual-execute-date.json)**
  - **Descripción:** Este flujo automático permite al usuario iniciar un proceso manualmente con la fecha específica '14/02/2020' usando el formato DD/MM/YYYY.
  - **Complejidad:** Baja (2 nodos)

- **[0614-read-rss-feed.json](workflows/0614-read-rss-feed.json)**
  - **Descripción:** Este flujo automático permite ejecutar la lectura de un RSS feed específico mediante un botón manual.
  - **Complejidad:** Baja (2 nodos)

- **[0615-send-email-example.json](workflows/0615-send-email-example.json)**
  - **Descripción:** Este flujo manual permite enviar un correo electrónico predefinido al hacer clic en el botón de ejecución.
  - **Complejidad:** Baja (2 nodos)

- **[0619-trigger-workflow.json](workflows/0619-trigger-workflow.json)**
  - **Descripción:** Este flujo manual permite iniciar la ejecución de otro workflow al hacer clic en el botón.
  - **Complejidad:** Baja (2 nodos)

- **[0659-error-alert-email.json](workflows/0659-error-alert-email.json)**
  - **Descripción:** Este flujo detecta errores en cualquier nodo y envía un correo electrónico detallado al administrador con información sobre el error, workflow afectado y detalles técnicos.
  - **Complejidad:** Baja (2 nodos)

- **[0699-zoom-crear-reunion.json](workflows/0699-zoom-crear-reunion.json)**
  - **Descripción:** Este flujo automático crea una reunión en Zoom usando la API OAuth2 mediante el desencadenante manual.
  - **Complejidad:** Baja (2 nodos)

- **[0720-spotify-cancion-especifica-trigger.json](workflows/0720-spotify-cancion-especifica-trigger.json)**
  - **Descripción:** Este flujo manual inicia una acción en Spotify usando la URI específica de una canción para buscar o reproducir.
  - **Complejidad:** Baja (2 nodos)

- **[0724-rocket-message-sender.json](workflows/0724-rocket-message-sender.json)**
  - **Descripción:** Este flujo automático se activa manualmente y envía un mensaje predefinido a la sala general de RocketChat.
  - **Complejidad:** Baja (2 nodos)

- **[0735-manual-trigger-translation.json](workflows/0735-manual-trigger-translation.json)**
  - **Descripción:** Este flujo manual permite ejecutar una traducción fija de un texto en inglés a alemán utilizando Google Translate.
  - **Complejidad:** Baja (2 nodos)

- **[0752-line-chatbot-context.json](workflows/0752-line-chatbot-context.json)**
  - **Descripción:** Este flujo automatizado utiliza Webhook y el Integration node postHog para mantener una conversación contextualizada.
  - **Complejidad:** Baja (2 nodos)

- **[0759-typeform-api-invoice.json](workflows/0759-typeform-api-invoice.json)**
  - **Descripción:** Este flujo utiliza un desencadenador de Typeform para recibir respuestas y las usa como parámetros JSON en el generador de PDF de APITemplate.io.
  - **Complejidad:** Baja (2 nodos)

- **[0768-beber.json](workflows/0768-beber.json)**
  - **Descripción:** Este flujo obtiene instrucciones aleatorias para preparar bebidas desde TheCocktailDB API y las traduce al francés usando DeepL.
  - **Complejidad:** Baja (2 nodos)

- **[1102-disqus-forum-details.json](workflows/1102-disqus-forum-details.json)**
  - **Descripción:** Este flujo automático ejecuta una acción manual para obtener los detalles de un foro específico en Disqus.
  - **Complejidad:** Baja (2 nodos)

- **[1182-trigger-crear-ticket.json](workflows/1182-trigger-crear-ticket.json)**
  - **Descripción:** Este flujo permite iniciar manualmente la creación de un nuevo ticket en Freshdesk.
  - **Complejidad:** Baja (2 nodos)

- **[1187-hue-light-control.json](workflows/1187-hue-light-control.json)**
  - **Descripción:** Este flujo automático permite encender una luz Philips Hue específica y ajustar su brillo a un valor determinado.
  - **Complejidad:** Baja (2 nodos)

- **[1190-captura-tiempo-automatica.json](workflows/1190-captura-tiempo-automatica.json)**
  - **Descripción:** Este flujo automático captura la fecha y hora locales actuales en formato detallado.
  - **Complejidad:** Baja (2 nodos)

- **[1297-generador_totp.json](workflows/1297-generador_totp.json)**
  - **Descripción:** Genera códigos TOTP para autenticación en dos pasos.
  - **Complejidad:** Baja (2 nodos)

- **[0062-active-campaign-account-trigger.json](workflows/0062-active-campaign-account-trigger.json)**
  - **Descripción:** Este flujo de trabajo se activa cuando un administrador añade una nueva cuenta en ActiveCampaign.
  - **Complejidad:** Baja (1 nodos)

- **[0125-flow-trigger-task.json](workflows/0125-flow-trigger-task.json)**
  - **Descripción:** Este flujo automático se dispara cuando ocurre una actualización en cualquier tarea especificada.
  - **Complejidad:** Baja (1 nodos)

- **[0137-tareas-toggl-alertas.json](workflows/0137-tareas-toggl-alertas.json)**
  - **Descripción:** Este flujo automático monitoriza continuamente entradas de tiempo nuevas en Toggl.
  - **Complejidad:** Baja (1 nodos)

- **[0453-convertkit-form-subscribe.json](workflows/0453-convertkit-form-subscribe.json)**
  - **Descripción:** Este flujo de trabajo monitoriza cuando un nuevo suscriptor se añade a través del formulario específico número 165198 en ConvertKit.
  - **Complejidad:** Baja (1 nodos)

- **[0543-postmark-email-events-trigger.json](workflows/0543-postmark-email-events-trigger.json)**
  - **Descripción:** Este flujo recoge actualizaciones de eventos específicos de Postmark para correos electrónicos, como rebotes o aperturas.
  - **Complejidad:** Baja (1 nodos)

- **[0559-mailchimp-subscribe-alert.json](workflows/0559-mailchimp-subscribe-alert.json)**
  - **Descripción:** Este flujo activa una acción cuando alguien se suscribe a la lista de Mailchimp especificada.
  - **Complejidad:** Baja (1 nodos)

- **[0562-mqtt-trigger.json](workflows/0562-mqtt-trigger.json)**
  - **Descripción:** Este flujo automático recibe mensajes de una cola MQTT cuando se publica un mensaje en el tópico correspondiente.
  - **Complejidad:** Baja (1 nodos)

- **[0571-acuity-appointment-trigger.json](workflows/0571-acuity-appointment-trigger.json)**
  - **Descripción:** Este flujo se activa cuando un usuario programa una cita a través de Acuity Scheduling.
  - **Complejidad:** Baja (1 nodos)

- **[0573-invoice-creation-trigger.json](workflows/0573-invoice-creation-trigger.json)**
  - **Descripción:** Este flujo automático se activa cuando se crea una factura en la API de Invoice Ninja.
  - **Complejidad:** Baja (1 nodos)

- **[0574-clockify-event-poller.json](workflows/0574-clockify-event-poller.json)**
  - **Descripción:** Este flujo automático monitoriza periódicamente la workspace especificada de Clockify cada minuto, esperando que ocurra algún evento para desencadenar acciones posteriores.
  - **Complejidad:** Baja (1 nodos)

- **[0576-eventbrite-order-triggers.json](workflows/0576-eventbrite-order-triggers.json)**
  - **Descripción:** Este flujo activa una integración cuando ocurren eventos relacionados con órdenes de entradas en Eventbrite, como la creación, actualización o reembolso.
  - **Complejidad:** Baja (1 nodos)

- **[0579-jotform-trigger.json](workflows/0579-jotform-trigger.json)**
  - **Descripción:** Este flujo automático se activa cuando un formulario específico de JotForm (ID: 202012795501445) es completado, utilizando credenciales de autenticación con la API de JotForm.
  - **Complejidad:** Baja (1 nodos)

- **[0588-survey-monkey-trigger.json](workflows/0588-survey-monkey-trigger.json)**
  - **Descripción:** Este flujo automático se activa cuando una nueva respuesta se crea en la encuesta específica de SurveyMonkey.
  - **Complejidad:** Baja (1 nodos)

- **[0618-flujo-email-imap.json](workflows/0618-flujo-email-imap.json)**
  - **Descripción:** Este flujo automático permite leer correos electrónicos desde un servidor IMAP.
  - **Complejidad:** Baja (1 nodos)

- **[0645-sse-trigger-n8n.json](workflows/0645-sse-trigger-n8n.json)**
  - **Descripción:** Este flujo automático utiliza un nodo de activación SSE para iniciar procesos basados en eventos enviados desde el servidor n8n.io.
  - **Complejidad:** Baja (1 nodos)

- **[0678-wufoo-form-submission.json](workflows/0678-wufoo-form-submission.json)**
  - **Descripción:** Este flujo automático recibe actualizaciones cuando se envía un formulario específico en Wufoo.
  - **Complejidad:** Baja (1 nodos)

- **[1107-activeMQ-amqp-trigger.json](workflows/1107-activeMQ-amqp-trigger.json)**
  - **Descripción:** Este flujo utiliza el trigger AMQP para recibir mensajes desde una cola de ActiveMQ.
  - **Complejidad:** Baja (1 nodos)

- **[2814-subscriber-unsubscribes-customerio.json](workflows/2814-subscriber-unsubscribes-customerio.json)**
  - **Descripción:** Este flujo activa un nodo cuando un suscriptor se da de baja en Customer.io, permitiendo realizar acciones basadas en dicho evento.
  - **Complejidad:** Baja (1 nodos)

## 🤝 Contribuciones

Añadimos organización por categorías y complejidad basada en número de nodos, por sugerencia de [Ángel Aparicio](https://www.instagram.com/p/DL5Z-fONoNe/).
