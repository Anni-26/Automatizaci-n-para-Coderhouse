# Proyecto Final — Sistema de Registro y Confirmación (Taller DETONA / LATENTE)
Curso: IA Automation

## Descripción
Sistema automatizado de registro y confirmación para el taller DETONA de LATENTE. El flujo captura los
datos de un participante mediante Google Forms, los guarda en Airtable, genera un mensaje de confirmación
personalizado con Gemini API, espera la aprobación humana (HITL) por Gmail, y envía la confirmación final
al participante. Incluye manejo de errores ante datos incompletos y fallos de API.

# Automatización-para-Coderhouse
Sistema automatizado de registro y confirmación para un taller. Stack: n8n · Google Forms · Airtable · Gemini API · Gmail

## Stack tecnológico
- Orquestador: n8n
- Formulario de entrada: Google Forms + Google Sheets
- Base de datos: Airtable
- IA: Google Gemini (Flash-Lite)
- Canal de salida: Gmail

## Archivos incluidos
- `Diagrama Automatización.drawio.pdf` — Mapa de arquitectura del flujo completo
- `Manual_Operativo_Automatizacion_Taller.pdf` — Estructura de la base de datos y esquemas de información
- `Optimizacion_Costos_Automatizacion.pdf` — Justificación de herramientas y modelo de IA elegido
- `Taller Vicencial- REGISTROS.json` — Blueprint exportado del flujo de n8n
- `Airtable_Estados_Diferentes.png` — Evidencia de los distintos estados del flujo en Airtable
- `Correo_Participante.png` — Evidencia del correo de confirmación recibido
- `Ejecuciones_Exitosas.png` — Evidencia de ejecuciones exitosas en n8n
- `Email_Registro_Incompleto.png` — Evidencia de la prueba de error (datos incompletos)
- `Screen1 Nodo completo.png` — Vista general del flujo completo en n8n

## Enlaces
- Base de datos (Airtable, modo lectura): https://airtable.com/appfs11VLulAGbECV/shrJVmgGOJXRwmTvN
- Video demo (3 min): https://drive.google.com/file/d/1-oepuC7hF-F0d3gi7Rf9FUelvz2qjiCI/view?usp=sharing

