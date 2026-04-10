# 🚗 Salida coche

Automatización inteligente que detecta cuándo sales del coche y guarda automáticamente la ubicación de aparcamiento, solo si estás lejos de casa.

---

## 🧠 Cómo funciona

Este sistema combina:

1. ⚙️ Automatización (CarPlay o Bluetooth)
2. 🔗 Atajo principal (`Salida coche`)
3. 🔗 Atajo auxiliar (`Dónde he aparcado`)
4. 🏠 Configuración previa (`Configurar casa`)

---

## ⚠️ Requisitos

Antes de usar este atajo debes ejecutar:

👉 🏠 [Configurar casa](../configurar-casa/README.md)

Esto guarda tu ubicación para poder calcular distancias.

---

## 📲 Instalación

Instala los siguientes atajos:

- 🔗 [Salida coche]https://www.icloud.com/shortcuts/f891d200ea1645fcb1d631d1a5df6f27
- 🔗 [Dónde he aparcado]https://www.icloud.com/shortcuts/3099be7701d8499cb034e1cd9902ec14

---

## ⚙️ Configurar automatización

1. Abre **Atajos → Automatización**
2. Pulsa **Crear automatización personal**
3. Selecciona:
   - 🚗 **CarPlay → Se desconecta**
   *(o Bluetooth del coche)*
4. Añade acción:
   - 👉 **Ejecutar atajo**
   - Selecciona: `Salida coche`
5. Desactiva:
   - ❌ Solicitar confirmación
6. Guardar

---

## ⚙️ ¿Qué hace el atajo?

1. 📍 Obtiene tu ubicación actual  
2. 🏠 Obtiene la ubicación de casa (archivo `casa`)  
3. 📏 Calcula la distancia entre ambas  
4. 🔎 Si la distancia es mayor que un umbral (ej: 0.3 km):
   - Ejecuta `Dónde he aparcado`  

---

## 📏 Lógica de distancia

El atajo solo se ejecuta si estás lo suficientemente lejos de casa:

- Valor recomendado: `0.3 km` (300 metros)
- Puedes ajustarlo según tus necesidades

Esto evita guardar ubicaciones cuando estás en casa.

---

## 🚀 Ventajas

- Totalmente automático  
- Evita registros innecesarios  
- Funciona sin intervención  
- Reutiliza lógica de otros atajos  

---

## 🔐 Privacidad

- No incluye direcciones personales  
- Usa un archivo local (`casa`)  
- No comparte datos fuera del dispositivo  

---

## ⚠️ Errores comunes

- ❌ No haber ejecutado `Configurar casa`
- ❌ Archivo `casa` inexistente o mal ubicado
- ❌ Automatización sin configurar
- ❌ Permisos de ubicación desactivados

---

## 💡 Personalización

Puedes ampliar este atajo:

- Cambiar distancia mínima  
- Añadir notificaciones  
- Ejecutar otros atajos  
- Integrarlo con modos de concentración  

---

## 🔗 Relacionado

- 🏠 Configurar casa  
- 📍 Dónde he aparcado  
