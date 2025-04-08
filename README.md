# 📈 Calculadora de Rendimientos Compuestos (Python)

Un pequeño script en Python para calcular el **rendimiento acumulado** y su **equivalente anualizado** a partir de rendimientos mensuales expresados como tasas anualizadas.

---

## 🧠 ¿Cómo funciona?

Este script toma una lista de rendimientos **mensuales anualizados** (por ejemplo, de un fondo de inversión) y calcula:

- ✅ El **rendimiento real acumulado** en el período (compuesto mes a mes).
- 📅 El **rendimiento anualizado acumulado**, útil para comparar con otros productos financieros.

---

## 🧪 Ejemplo de uso

```python
rendimientos_anual = [10.38, 10.01, 9.69]  # en porcentaje anual

# El script hace la magia:
# 1. Convierte a rendimiento mensual real
# 2. Aplica interés compuesto
# 3. Calcula el acumulado y lo anualiza
