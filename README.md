# BoletaTuya: Chatbot para Consultas sobre Eventos

*BoletaTuya* es un chatbot diseñado para responder preguntas sobre eventos a los que los usuarios planean asistir o ya han comprado boletos. Este chatbot no gestiona la venta de entradas, sino que se centra en proporcionar información detallada acerca de los eventos. Para garantizar respuestas precisas y actualizadas, el bot hace uso de *Modelos de Lenguaje Grandes (LLMs)* y extrae la información directamente desde un archivo PDF predefinido que contiene todos los detalles de los eventos.

## Características principales

- Respuesta a preguntas sobre compra de boletas: reclamos, devoluciones, seguros.
- Extracción de información directamente desde un archivo PDF.
- Soporte para lenguaje natural mediante *Modelos de Lenguaje Grandes (LLMs)*.
- Interacción fluida y amigable para el usuario.
- No gestiona la venta de boletos, solo responde a consultas.

## ¿Cómo funciona?

El chatbot utiliza *LLMs* para procesar las preguntas del usuario y buscar las respuestas dentro de un archivo PDF que contiene toda la información relevante a la compra de boletas. Al no manejar la venta de boletos, el objetivo es que los usuarios puedan resolver cualquier duda antes de asistir a su evento, como el horario, la lista de artistas o las restricciones de entrada.

## 📋 Requisitos previos

Antes de ejecutar el proyecto, asegúrate de tener instalados los siguientes programas:

- Python 3.8 o superior
- pip (Python Package Manager)
- Acceso a un modelo de lenguaje grande (por ejemplo, GPT-3 o similar)
- Paquete pdfplumber para la extracción de datos del PDF

## Funcionamiento

El sistema se inicia con la carga de un archivo PDF que contiene toda la información relevante sobre la compra de boletas para eventos. El chatbot procesa las preguntas del usuario y utiliza un *modelo de lenguaje grande (LLM)* para interpretar las consultas y buscar respuestas directamente en el PDF. El archivo PDF se analiza cada vez que se recibe una nueva pregunta, lo que garantiza que la información siempre esté actualizada según los contenidos del documento.

### Ejemplo de uso:

- Usuario: "¿Cómo puedo acceder a una devolución por no asistir?"
- BoletaTuya: "Debes cumplir con los requisitos establecidos: presentar por escrito la razón de la ausencia junto a los soportes, la factura de la compra y documento de identificación del comprador."
