# 🚗 Inicio de conducción

Automatización inteligente que detecta cuándo te conectas al coche y configura el iPhone automáticamente antes de iniciar la marcha.

Incluye asistencia por voz y navegación automática.

---

## 🧠 ¿Para qué sirve?

Este atajo te permite:

- Preparar el iPhone automáticamente al entrar en el coche  
- Recibir asistencia por voz tipo asistente  
- Iniciar navegación sin tocar el móvil  
- Integrar tu dirección de casa para uso rápido  

Ideal para uso diario en desplazamientos.

---

## ⚙️ Requisitos

- 📱 iOS actualizado  
- 📲 App Atajos  
- 🔗 Dependencias (OBLIGATORIO):
  - 🏠 Configurar casa  

👉 Debes haber configurado previamente tu ubicación de casa.

---

## 📲 Instalación

1. Descarga el atajo:  
   🔗 https://www.icloud.com/shortcuts/490eab408844452aa0d8a0cc1d05c27b  

2. Ábrelo en la app **Atajos**

---

## ▶️ Uso

Este sistema no se ejecuta manualmente.

Funciona automáticamente al conectarte al coche.

---

## 🤖 Automatización

Configura una automatización en iOS:

1. Abre **Atajos → Automatización**  
2. Pulsa **Crear automatización personal**  
3. Selecciona:
   - 🚗 **CarPlay → Se conecta**  
   *(o Bluetooth del coche)*  
4. Añade acción:
   - Ejecutar atajo  
   - Selecciona: **Inicio de conducción**  
5. Desactiva:
   - ❌ "Solicitar confirmación"  
6. Guardar  

---

## 📂 ¿Qué hace internamente?

El atajo:

1. Detecta que te conectas al coche  
2. Comprueba el nivel de batería  
3. Genera un mensaje por voz tipo asistente  
4. Reproduce el mensaje  
5. Solicita un destino por voz  
6. Interpreta la respuesta:
   - “no” → cancela  
   - “casa” → usa tu ubicación guardada  
   - otro destino → lo procesa automáticamente  
7. Abre Google Maps con la ruta  

---

## 🏠 Uso de “casa”

Cuando dices “llévame a casa”:

- El atajo lee el archivo configurado previamente  
- Utiliza esa ubicación como destino  
- Inicia la navegación automáticamente  

👉 Esto depende directamente del atajo **Configurar casa**

---

## ⚠️ Problemas comunes

- ❌ No reconoce la voz → revisa permisos de micrófono  
- ❌ No abre navegación → revisa Google Maps instalado  
- ❌ “Casa” no funciona → ejecuta de nuevo Configurar casa  
- ❌ No se ejecuta → revisa la automatización  

---

## 💡 Notas

- Funciona mejor con CarPlay  
- Compatible con Bluetooth del coche  
- Puedes adaptar el mensaje de voz a tu gusto  
- Puedes cambiar la app de navegación si lo deseas  
