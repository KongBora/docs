---
title: Timeline events
allowTitleToDifferFromFilename: true
shortTitle: Línea de tiempo
intro: The Timeline events API can return different types of events triggered by timeline activity in issues and pull requests.
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - API
miniTocMaxHeadingLevel: 3
---

## About the Timeline events API

The Timeline events API can return different types of events triggered by timeline activity in issues and pull requests. Para obtener más información sobre los tipos de eventos específicos que puedes recibir desde la API de eventos de propuestas, consulta la sección "[Tipos de eventos de propuestas](/developers/webhooks-and-events/issue-event-types)". Para obtener más información acerca de los eventos específicos que puedes recibir de la API de Eventos para Solicitudes de Extracción, consulta la sección "[Tipos de evento de las Solicitudes de Extracción](/developers/webhooks-and-events/issue-event-types)". Para obtener más información, consulta la "[API de Eventos de GitHub](/developers/webhooks-and-events/github-event-types)".

Puedes utilizar esta API para mostrar información sobre los informes de problemas y solicitudes de extracción o para determinar a quién debería notificársele sobre los comentarios en los informes de problemas.

{% data reusables.pull_requests.issues-pr-shared-api %}
