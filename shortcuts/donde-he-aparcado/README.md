# 🚗 Dónde he aparcado

Guarda automáticamente la ubicación donde has aparcado el coche al desconectar CarPlay.

---

## 🧠 Cómo funciona

Este sistema se compone de dos partes:

1. ⚙️ **Automatización (la crea el usuario)**
2. 🔗 **Atajo (se proporciona en este repositorio)**

Cuando se desconecta CarPlay, el iPhone ejecuta el atajo automáticamente.

---

## 📲 Instalar atajo

🔗 [Dónde he aparcado]https://www.icloud.com/shortcuts/3099be7701d8499cb034e1cd9902ec14

---

## ⚙️ Configurar automatización

1. Abre la app **Atajos**
2. Ve a **Automatización**
3. Pulsa **Crear automatización personal**
4. Selecciona **CarPlay**
5. Configura:
   - 👉 **Se desconecta**
   - Desmarca 👉 **Se conecta**
6. Pulsa **Siguiente**
7. Añade acción:
   - 👉 **Ejecutar atajo**
   - Selecciona: `Dónde he aparcado`
8. Pulsa **Siguiente**
9. Desactiva:
   - ❌ "Solicitar confirmación"
10. Guardar

---

## ⚙️ ¿Qué hace el atajo?

El atajo realiza:

1. 📍 Obtener ubicación actual  
2. 🚗 Guardar ubicación como coche aparcado  
3. 🗺️ Generar enlace a Mapas  
4. 📝 Crear nota con:
   - Fecha actual  
   - URL de Mapas  
   - Ubicación  

---

## 📂 Resultado

Se crea una nota en la carpeta:

```bash
Parking
