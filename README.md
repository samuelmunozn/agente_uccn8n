Agente UCC - Automatización con n8n
Estudiante: Samuel Muñoz
Programa: Ingeniería de Software
Institución: Universidad Cooperativa de Colombia (Campus Pasto)
Descripción del Proyecto
Este repositorio contiene la arquitectura y los flujos de trabajo desarrollados en n8n para el funcionamiento del "Agente UCC". Este sistema implementa un asistente de inteligencia artificial capaz de gestionar interacciones, procesar información e integrarse con plataformas de mensajería como WhatsApp.
Estructura del Repositorio
El proyecto se compone de los siguientes archivos principales:
 ⁠docker-compose.yml⁠: Archivo de configuración para levantar el entorno de n8n de manera local mediante contenedores Docker.
 ⁠flujo_1_ingesta.json⁠: Flujo de trabajo diseñado para la ingesta, lectura y procesamiento inicial de datos y documentos.
 ⁠flujo_2_agente_chat.json⁠: Contiene la lógica principal del agente conversacional para interactuar y responder consultas.
 ⁠flujo_3_agente_wa.json⁠: Configuración específica para la integración y despliegue del agente automatizado a través de WhatsApp.
 Instrucciones de Ejecucion para evaluacion 
 1. Clonar el repositorio: Abra un terminal y ejecute:
    git clone https://github.com/samuelmunozn/agente_uccn8n.git
cd agente_uccn8n
2. Desplegar el entorno n8:Asegúrese de tener Docker Desktop (o Docker Engine) instalado y en ejecución en su equipo. Luego, levante el servicio con:
   docker-compose up -d
   3. Acceder a la plataforma:
Abra su navegador web e ingrese a ⁠http://localhost:5678⁠ (puerto por defecto de n8n).
   4. Importar los flujos de trabajo.
