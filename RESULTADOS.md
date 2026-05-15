# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 6 correctas de 9 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+UPPER(nombre) | precio
 DISCO DURO SATA3 1TB | 86.99
 MEMORIA RAM DDR4 8GB | 120.00
 DISCO SSD 1 TB | 150.99
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 7: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+LOWER(nombre) | precio
 disco duro sata3 1tb | 86.99
 memoria ram ddr4 8gb | 120.00
 disco ssd 1 tb | 150.99
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 9: Error
- **Descripción**: 'NoneType' object is not iterable

