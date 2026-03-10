# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 2 correctas de 6 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.41 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 2: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | apellido1 | apellido2
-Pedro | Heller | Pagac
-Ismael | Strosin | Turcotte
+apellido1 | apellido2 | nombre
+Heller | Pagac | Pedro
+Strosin | Turcotte | Ismael
```

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | apellido1 | apellido2 | nif
-Antonio | Fahey | Considine | 10485008K
-Guillermo | Ruecker | Upton | 85869555K
+apellido1 | apellido2 | nombre
+Fahey | Considine | Antonio
+Ruecker | Upton | Guillermo
```

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,13 @@
 id | nombre | cuatrimestre | curso | id_grado
+21.00 | Desarrollo de interfaces de usuario | 1.00 | 3.00 | 4.00
+22.00 | Ingeniería de Requisitos | 1.00 | 3.00 | 4.00
+23.00 | Integración de las Tecnologías de la Información en las Organizaciones | 1.00 | 3.00 | 4.00
+24.00 | Modelado y Diseño del Software 1 | 1.00 | 3.00 | 4.00
+25.00 | Multiprocesadores | 1.00 | 3.00 | 4.00
+26.00 | Seguridad y cumplimiento normativo | 1.00 | 3.00 | 4.00
+27.00 | Sistema de Información para las Organizaciones | 1.00 | 3.00 | 4.00
+28.00 | Tecnologías web | 1.00 | 3.00 | 4.00
+29.00 | Teoría de códigos y criptografía | 1.00 | 3.00 | 4.00
 72.00 | Bases moleculares del desarrollo vegetal | 1.00 | 3.00 | 7.00
 73.00 | Fisiología animal | 1.00 | 3.00 | 7.00
 74.00 | Metabolismo y biosíntesis de biomoléculas | 1.00 | 3.00 | 7.00
```

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ❌ Query 6: Error
- **Descripción**: 'NoneType' object is not iterable

