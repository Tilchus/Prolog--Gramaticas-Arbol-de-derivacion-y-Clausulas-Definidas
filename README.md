# Gramáticas de Cláusulas Definidas (DCG) en Prolog
## Procesamiento del Lenguaje Natural — Análisis Sintáctico Estructural

Este repositorio contiene el desarrollo completo del Trabajo Práctico para la cátedra **Técnicas de Procesamiento del Habla**, correspondiente al 2º año de la **Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial** del **Instituto Tecnológico Beltrán**.

---

## 📋 Información del Proyecto

* **Institución:** Instituto Tecnológico Beltrán (ISFT 197)
* **Carrera:** Tecnicatura Superior en Ciencia de Datos e IA (2º Año)
* **Cátedra:** Técnicas de Procesamiento del Habla
* **Profesora:** Yanina Escudero
* **Alumna:** Silvana Alejandra Gerez

---

## 🎯 Objetivo del Trabajo Práctico

El proyecto consiste en el **análisis sintáctico estructural de una lista de diez oraciones seleccionadas** con el fin de estudiar y modelar cómo se organiza el lenguaje natural mediante reglas formales. 

Cada oración cuenta con una descomposición jerárquica presentada en dos formatos complementarios:
1. **Árbol Sintáctico:** Representación gráfica que ilustra cómo las palabras se agrupan en constituyentes o sintagmas (Nominales, Verbales, Adjetivales y Preposicionales).
2. **Estructura Sintáctica Formal:** Desglose detallado de las reglas de producción formales, diseñadas y estructuradas específicamente para su posterior implementación lógica en el lenguaje **Prolog** mediante Gramáticas de Cláusulas Definidas (DCG).

---

## 📝 Oraciones Analizadas

El corpus del trabajo abarca el análisis de las siguientes estructuras lingüísticas:

1. *Los aztecas hablaban náhuatl.*
2. *La dominación islámica disminuyó progresivamente.*
3. *Los reyes católicos conquistaron Granada.*
4. *El catalán es una lengua romance.*
5. *Los mayas resistieron la colonización española.*
6. *Los sacerdotes evangelizaban a los indígenas.*
7. *Las lenguas minoritarias de España han entrado en una nueva etapa.*
8. *El español es lengua oficial en diecinueve países de Latinoamérica.*
9. *El terreno de Paraguay representaba desafíos de envergadura para los españoles.*
10. *Los niños monolingües de desarrollo normal pasan por varias etapas.*

---

## 📂 Contenido del Repositorio

* **`Prolog Gramaticas PDF 11.pdf`**: Documento principal que contiene el desarrollo metodológico, los árboles sintácticos vectoriales y las correspondientes reglas de producción sintáctica para cada uno de los enunciados.

---

## ⚙️ Conceptos Lingüísticos Aplicados (DCG)

Las estructuras se modelaron bajo la lógica computacional de reglas de producción, mapeando componentes esenciales del lenguaje:
* **Sintagmas:** `SN` (Sintagma Nominal), `SV` (Sintagma Verbal), `SAdj` (Sintagma Adjetival), `SP` (Sintagma Preposicional), `SAdv` (Sintagma Adverbial).
* **Categorías Léxicas:** `Det` (Determinante), `N` (Nombre/Sustantivo), `V` (Verbo), `Adj` (Adjetivo), `P` (Preposición), `Adv` (Adverbio).
