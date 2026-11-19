# Elección de empresa

**Empresa:** Nexova Solutions

## Justificación

Me atrae Nexova porque combina servicios B2B con problemas reales de talento y atención al cliente, donde la IA puede mejorar directamente la operación. Su equipo externalizado de soporte tiene 30 agentes, tarda una media de 48 horas en resolver incidencias y debe cumplir un SLA de 24 horas; además, trabaja sin una base de conocimiento centralizada. En el curso quiero construir un agente de soporte con RAG que ayude a resolver consultas frecuentes, reduzca la carga manual y derive a una persona los casos que requieran intervención.

## Departamentos que me interesan

- **Atención al Cliente (Roberto Díaz):** Los 30 agentes atienden por teléfono, email y chat sin una base de conocimiento compartida; la resolución media es de 48 horas frente al SLA comprometido de 24. Me interesa porque es el área donde un agente RAG puede responder preguntas frecuentes y escalar incidencias complejas.
- **Tecnología e Infraestructura (Sergio Molina):** El equipo de seis personas mantiene herramientas desconectadas, entre ellas un helpdesk legacy, y carece de telemetría y logging centralizado. Me interesa porque la integración con los tickets y la observabilidad son necesarias para que el agente de soporte sea útil y se pueda evaluar.

## Reto de automatización

Automatizar con RAG al menos el 40% de las consultas frecuentes sin intervención humana y reducir el tiempo medio de resolución desde las 48 horas actuales hasta menos de 24 horas, cumpliendo el SLA comprometido. Los casos con baja confianza, sentimiento negativo o necesidad de atención especializada se derivarán a un agente humano.

## My AI Agent Idea

**Nombre:** Nexova Support Copilot
**Qué hace:** Recibe la consulta del cliente y busca información relevante en la base de conocimiento mediante RAG. Redacta una respuesta basada en las fuentes disponibles y resuelve automáticamente solo los casos frecuentes con suficiente respaldo. Si no encuentra evidencia suficiente, detecta una incidencia sensible o identifica riesgo de insatisfacción, crea o actualiza el ticket y lo deriva a un agente con un resumen del caso. Registra el resultado para medir la tasa de resolución automática y los tiempos de atención.
**Información que necesita:** Mensajes de clientes recibidos por email y chat, transcripciones disponibles de llamadas, artículos de la base de conocimiento, tickets históricos y su resolución, y datos de prioridad y SLA por cliente. También necesita acceso controlado al helpdesk existente para consultar y actualizar tickets.
**Qué produce o activa:** Respuestas sugeridas o automáticas con referencias a la información consultada, tickets clasificados y priorizados, derivaciones a agentes con contexto, alertas a supervisores para casos urgentes o con sentimiento negativo, y métricas de automatización y tiempos de resolución.
