# 🔋 Modo batería baja automático

Automatización que ejecuta acciones cuando la batería del iPhone baja de un porcentaje definido.

---

## ⚠️ Importante

Este sistema **no es un atajo independiente**, sino una **automatización dentro de la app Atajos**.

---

## ⚙️ ¿Qué hace?

Cuando la batería baja (por ejemplo al 20%), el iPhone puede:

- 🔅 Reducir el brillo
- 📶 Desactivar WiFi o datos móviles
- 🔕 Activar modo No molestar
- ⚡ Activar modo de bajo consumo
- 📲 Ejecutar otros atajos

---

## 🧠 Cómo funciona

Se basa en una automatización personal:

- Evento: **Nivel de batería**
- Condición: baja de X%
- Acción: ejecutar una o varias acciones

---

## 🛠️ Configuración paso a paso

1. Abre la app **Atajos**
2. Ve a la pestaña **Automatización**
3. Pulsa **Crear automatización personal**
4. Selecciona **Nivel de batería**
5. Configura:
   - Baja de: `20%` (o el valor que quieras)
6. Pulsa **Siguiente**
7. Añade las acciones que quieras, por ejemplo:

   - Activar modo de bajo consumo
   - Ajustar brillo al 30%
   - Mostrar notificación

8. Pulsa **Siguiente**
9. Desactiva:
   - ❌ "Solicitar confirmación"
10. Guarda

---

## 🚀 Ejemplo de configuración recomendada

Cuando batería < 20%:

- ⚡ Activar modo de bajo consumo
- 🔅 Brillo al 30%
- 🔕 Activar modo No molestar

---

## 🔗 Opcional: usar un atajo

Puedes hacer que esta automatización ejecute un atajo más complejo:

- Crear un atajo llamado: `Modo ahorro`
- Añadir todas las acciones dentro
- Desde la automatización → ejecutar ese atajo

---

## ⚠️ Limitaciones

- Algunas acciones pueden pedir confirmación según iOS
- No todas las configuraciones se pueden automatizar al 100%
