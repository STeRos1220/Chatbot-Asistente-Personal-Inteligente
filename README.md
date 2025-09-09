# Chatbot-Asistente-Personal-Inteligente
Este documento presenta la propuesta de desarrollo de un chatbot asistente personal inteligente que utiliza el modelo de lenguaje Microsoft Phi3 para gestionar citas, recordatorios, horarios y reglas personalizadas mediante procesamiento de lenguaje natural.

Objetivo General
• Desarrollar un chatbot asistente personal inteligente utilizando el modelo de lenguaje Microsoft Phi3 que gestione citas, recordatorios, horarios y reglas personalizadas a traves de interacciones conversacionales natu- ´
rales, mejorando la productividad y organizacion personal ´
del usuario.
Objetivos Específicos
• Implementar gestion inteligente de citas : Desarrollar funcionalidades para programar, modificar, consultar y
cancelar citas utilizando procesamiento de lenguaje natural con comprension de referencias temporales complejas. ´
• Crear sistema de recordatorios contextuales: Diseñar un sistema que genere recordatorios inteligentes basados
en tiempo, ubicacion, eventos específicos y patrones de comportamiento del usuario.
• Desarrollar administracion de horarios personalizados: Implementar capacidades para mantener, consultar y
optimizar horarios personales, familiares y profesionales
con deteccion automática de conflictos. 
• Integrar sistema de reglas personalizadas: Crear un
motor de reglas que permita al usuario definir restricciones y preferencias espec´ıficas (ej. disponibilidad, prioridades, restricciones temporales).
• Establecer integracion con calendarios externos: Desarrollar conectores para sincronizacion bidireccional con ´
Google Calendar, Outlook y otros sistemas de calendario
populares.

Modelo LLM Seleccionado
- **Modelo:** Microsoft Phi-3 Mini (3.8B parámetros).  
- **Ventajas:**
  - Ligero y eficiente (corre en CPU y GPUs medianas).  
  - Soporte multilingüe (español e inglés).  
  - Buen rendimiento para chatbots de asistencia personal.  

## 🏗️ Arquitectura
**Usuario → Interfaz (Web/CLI) → Backend (Flask/FastAPI) → Ollama API → Modelo Phi-3 → Respuesta al usuario**
