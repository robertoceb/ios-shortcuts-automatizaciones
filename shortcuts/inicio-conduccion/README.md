# 🚗 Inicio de conducción

Automatización inteligente que detecta cuándo te conectas al coche y configura automáticamente el iPhone antes de iniciar la marcha, incluyendo asistencia por voz y navegación.

---

## 🧠 Cómo funciona

Este sistema combina:

1. ⚙️ Automatización (CarPlay o Bluetooth)
2. 🔗 Atajo principal (`Inicio de conducción`)
3. 🏠 Configuración previa (`Configurar casa`)

---

## ⚠️ Requisitos

Antes de usar este atajo debes ejecutar:

👉 🏠 [Configurar casa](../configurar-casa/README.md)

Esto guarda tu dirección para poder usarla al decir “casa”.

---

## 📲 Instalación

Instala el siguiente atajo:

- 🔗 [Inicio de conducción]https://www.icloud.com/shortcuts/490eab408844452aa0d8a0cc1d05c27b

---

## ⚙️ Configurar automatización

1. Abre **Atajos → Automatización**
2. Pulsa **Crear automatización personal**
3. Selecciona:
   - 🚗 **CarPlay → Se conecta**
   *(o Bluetooth del coche)*
4. Añade acción:
   - 👉 **Ejecutar atajo**
   - Selecciona: `Inicio de conducción`
5. Desactiva:
   - ❌ Solicitar confirmación
6. Guardar

---

## ⚙️ ¿Qué hace el atajo?

1. 🔋 Comprueba el nivel de batería  
2. 🤖 Genera un mensaje por voz tipo asistente (ChatGPT)  
3. 🔊 Reproduce el mensaje  
4. 🎤 Solicita destino por voz  
5. 🧠 Interpreta la respuesta:
   - Si dices **“no”** → cancela  
   - Si dices **“casa”** → usa tu dirección guardada  
   - Si dices otro destino → lo procesa automáticamente  
6. 🗺️ Abre Google Maps con la ruta  

---

## 🏠 Uso de “casa”

Cuando dices “llévame a casa”:

- El atajo lee el archivo:
