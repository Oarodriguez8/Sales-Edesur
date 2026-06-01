# Resumen Ejecutivo: Reporte de Desempeño Comercial y Operativo (Edesur Dominicana)
**Período:** 1 de enero al 30 de noviembre de 2025

---

## 1. Resumen de Indicadores Clave (KPIs)

El desempeño general durante el periodo analizado muestra un crecimiento moderado en la facturación y la recaudación de ingresos en comparación con el mismo periodo del año anterior (Año Anterior). Sin embargo, coexiste con una reducción en el volumen de energía facturada y un deterioro en el control de pérdidas operativas.

* **Facturación Total:** **RD$ 46,056 MM** (Millones de Pesos), lo que representa un incremento del **+1.49%** vs. el año anterior.
* **Cobros (Recaudación):** **RD$ 44.8K MM** (donde K representa miles, equivalente a RD$ 44,800 MM). Registra un incremento del **+2.66%** en comparación con el año anterior.
* **Eficiencia de Cobros:** **97.2%**, logrando una mejora del **+1.15%** respecto al año pasado, lo que consolida una excelente gestión de recaudo sobre los compromisos facturados.
* **Energía Facturada:** **4,462.7 GWh**, lo que representa una **caída del -2.71%** en volumen de energía entregada en relación con el año anterior.
* **Disponibilidad del Servicio (ASAI):** Se mantiene estable y robusta en **95.4%** (0% de variación).

![Dashboard_performance](Reporte-Edesur.png)
---

## 2. Diagnóstico del Problema Crítico

A pesar de que los ingresos monetarios aumentaron (impulsados potencialmente por ajustes tarifarios o incrementos en el valor por contrato), el tablero expone una **desviación operativa severa**:

### **Incremento Desproporcionado en las Pérdidas de Energía (32.1%)**
Este indicador clave sufrió un deterioro del **-4.63%**, subiendo del 30.6% (año anterior) al **32.1%** actual.

* **Impacto de la brecha:** Mientras el volumen de energía facturada **disminuyó un -2.71%** (pasando de 4.6K GWh a 4,462.7 GWh), el porcentaje de pérdidas se elevó considerablemente. Esto implica que una porción significativa de la energía comprada o distribuida se desvía mediante pérdidas técnicas (deficiencias en redes) o no técnicas (fraudes, conexiones ilegales, fallas de medición).
* **Brecha de infraestructura (Telemedición):** El desglose provincial revela una fuerte correlación entre las bajas tasas de telemedición y el rendimiento operativo. Provincias como **San Juan (34.0% de telemedición)** y **Barahona (40.5% de telemedición)** evidencian un rezago crítico en comparación con el Distrito Nacional, que lidera con un **96.6%**.

---

## 3. Recomendaciones y Próximos Pasos

Con el objetivo de contener el impacto financiero derivado de las pérdidas y maximizar la alta eficiencia de cobros, se proponen las siguientes acciones estratégicas:

1.  **Plan de Fiscalización Focalizado en Zonas de Alta Pérdida:**
    * Desplegar operativos de auditoría de redes e inspección de fraudes comerciales prioritariamente en **San Juan, Barahona y Baní**, debido a sus bajos niveles de blindaje en medición.
    * Ejecutar balances de energía mediante macro-medición en los circuitos de la **Zona 1 (Distrito)**. Aunque cuenta con un 96.6% de telemedición, esta zona concentra el **59.7% de la facturación total** (RD$ 27,516 MM), por lo que cualquier reducción marginal en sus pérdidas impactará significativamente el flujo de caja.

2.  **Aceleración de Inversiones en Telemedición (CAPEX):**
    * Establecer una meta mandatoria para elevar el indicador general de telemedición (actualmente en **81.2%**), priorizando el financiamiento técnico en la Zona 4 y Zona 5 hasta alcanzar un mínimo del 75% de cobertura en los próximos dos trimestres.

3.  **Gestión de Estacionalidad y Mantenimiento de Redes:**
    * El gráfico de facturación mensual identifica una estacionalidad clara con picos máximos entre **Agosto y Octubre** (superando los RD$ 4,500 MM mensuales). Se recomienda adelantar los mantenimientos preventivos de redes a los meses de abril-mayo para minimizar el incremento de pérdidas técnicas causadas por la saturación térmica de las líneas durante la época de alta demanda.

4.  **Optimización del Gobierno de Datos en el Dashboard (Nota de TI):**
    * Estandarizar las etiquetas de escala: La nomenclatura de Cobros utiliza **"K"** para referirse a miles de millones (unidades de mil en la escala visual del KPI), lo cual genera confusión con la Facturación denotada explícitamente en **"MM"**. Se sugiere homogeneizar ambas métricas a "MM" (ej. RD$ 44,800 MM).
    * Revisar la lógica del KPI **Contratos Facturados** (10,462,136), el cual presenta una alerta de caída del **-88.54%** vs. el año anterior (91.3M). Es necesario confirmar si el histórico contenía duplicidades o si existe un error de cálculo en la fórmula DAX de comparación temporal.
