# 🚦 Análisis de Siniestralidad Vial - Teusaquillo, Bogotá

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

> Dashboard geoespacial interactivo para análisis de accidentalidad vial en Teusaquillo, Bogotá (2015-2023)



<img width="1528" height="784" alt="image" src="https://github.com/user-attachments/assets/6482d8ff-5f07-43b3-9c63-7a637795b2b7" />


---

## 🎯 Resumen Ejecutivo

Análisis integral de **5,779 casos de siniestralidad vial** en la localidad de Teusaquillo durante 9 años, combinando análisis estadístico, visualización de datos y georreferenciación para identificar patrones críticos de accidentalidad y generar estrategias de seguridad vial basadas en evidencia.

### 🚨 Hallazgos Críticos
- **41% motociclistas** lesionados (grupo de mayor riesgo)
- **3,760 choques** registrados (tipo de accidente más frecuente)
- **Viernes + horas pico (7-9 AM)**: Combinación más peligrosa
- **60% víctimas son hombres** (21-28 años: grupo etario más vulnerable)
- **Mayo**: Mes con mayor siniestralidad

---

## 📊 Métricas de Impacto

| Métrica | Valor | Insight |
|---------|-------|---------|
| **Total Lesionados** | 5,779 personas | Análisis 2015-2023 |
| **Actor Vial Crítico** | Motociclistas (41%) | Requiere intervención urgente |
| **Tipo Accidente #1** | Choques (65%) | Infraestructura y señalización |
| **Día Crítico** | Viernes | Fin de jornada laboral |
| **Hora Pico** | 7-9 AM | Congestión vehicular |
| **Género Vulnerable** | Hombres (60%) | Enfoque educativo específico |
| **Año Récord** | 2022 | Pico de siniestralidad |

---

## 🗺️ Componentes del Proyecto

### 1. **Dashboard Power BI** - Análisis Temporal y Estadístico
- Filtros interactivos: Año, día semana, edad, hora
- Tendencias mensuales de lesionados (2015-2023)
- Distribución por rol en transporte (motociclista, pasajero, peatón, conductor, ciclista)
- Análisis de clases de accidentes
- Segmentación por tipo de servicio y género

### 2. **Análisis Descriptivo Excel** - Limpieza y Preparación
- ETL de datos abiertos (Secretaría Distrital de Movilidad)
- Estandarización de registros
- Validación de calidad de datos

---

## 🛠️ Stack Tecnológico

**Herramientas de Análisis:**
- **Power BI Desktop**: Visualización y storytelling de datos
- **Microsoft Excel**: ETL y limpieza de datos
- **Power Query**: Transformaciones y modelado

**Técnicas Aplicadas:**
- Análisis Exploratorio de Datos (EDA)
- Segmentación Multivariable
- Visualización de Datos Complejos
- Urban Analytics

**Fuentes de Datos:**
- Datos Abiertos - Secretaría Distrital de Movilidad
- Datos Abiertos Bogotá

---

## 🔍 Insights Accionables

### 🏍️ **1. Crisis en Motociclistas** (CRÍTICO)
**Hallazgo:** 41% de lesionados son motociclistas  
**Acción Recomendada:**
- Campañas educativas específicas para motociclistas
- Carriles exclusivos o protegidos en corredores críticos
- Programas de conducción defensiva obligatorios
- Mayor control policial en horarios pico

### 💥 **2. Choques: El Problema Principal**
**Hallazgo:** 3,760 choques (65% del total)  
**Acción Recomendada:**
- Auditoría de señalización vial en puntos críticos
- Mejora de diseño geométrico en intersecciones
- Semaforización inteligente basada en flujo vehicular
- Implementación de reductores de velocidad

### 📅 **3. Patrón Viernes + Horas Pico**
**Hallazgo:** Mayor concentración viernes 7-9 AM  
**Acción Recomendada:**
- Refuerzo de vigilancia policial viernes en AM
- Campañas "Viernes Seguro"
- Flexibilización de horarios laborales (trabajo remoto)
- Ajuste dinámico de tiempos semafóricos

### 👨 **4. Hombres Jóvenes en Riesgo**
**Hallazgo:** 60% son hombres, rango crítico 21-28 años  
**Acción Recomendada:**
- Educación vial en universidades y empresas
- Incentivos para conducción segura (seguros)
- Programas de concientización sobre consecuencias
- Restricciones graduales para conductores novatos

### 📆 **5. Mayo: Mes de Mayor Riesgo**
**Hallazgo:** Pico de accidentalidad en mayo  
**Acción Recomendada:**
- Operativos preventivos en abril-mayo
- Revisiones técnico-mecánicas previas
- Campañas preventivas desde abril
- Análisis de condiciones climáticas del periodo

---

## 📁 Estructura del Repositorio

```
Teusaquillo_Road_Safety_Analysis/
│
├── data/
│   ├── Data_Injured                           # Datos originales Sec. Movilidad
│   ├── Data_Injured_Cleaned/                       # Base de datos procesada
│
│
├── powerbi/
│   └── Dashboard_Accident_Rate.pbix  # Dashboard principal
│
├── docs/
│   ├── Report_Teusaquillo.pdf     # Informe académico completo
│               
│
├── images/
│   ├── dashboard_preview.png
│   └── teusaquillo.png
│
└── README.md
```

---

## 🎓 Metodología

### **Fase 1: Adquisición de Datos**
- Extracción desde portales open data distritales
- Periodo: 2015-2023 (9 años de registros)
- Variables: Fecha, hora, ubicación, tipo accidente, rol víctima, género, edad, servicio

### **Fase 2: Limpieza y Preparación (Excel)**
```
Registros originales: ~6,200
↓ Eliminación duplicados
↓ Corrección errores tipográficos
↓ Estandarización formatos
↓ Validación consistencia
Registros finales: 5,779
```

### **Fase 3: Análisis Estadístico (Power BI)**
- Creación de medidas DAX personalizadas
- Segmentación por múltiples variables
- Visualizaciones interactivas
- Análisis de tendencias temporales

---

## 📸 Visualizaciones Destacadas

### Dashboard Power BI incluye:

**📈 Panel Temporal:**
- Gráfico de líneas: Lesionados por mes (2015-2023)
- Filtros: Año, día semana, rango horario

**👥 Panel Demográfico:**
- Contadores por género (Hombres: 3,700 | Mujeres: 2,079)
- Distribución por edad
- Roles en transporte (dona chart)

**🚗 Panel de Accidentalidad:**
- Clases de accidentes (barras comparativas)
- Tipos de servicio (particular, público, oficial)
- Indicador de fuga del lugar

**🗺️ Panel Geoespacial:**
- Mapa interactivo de Teusaquillo
- Marcadores de siniestros por ubicación
- Integración con capas base de Bogotá

---

## 💡 Recomendaciones Estratégicas

### **Corto Plazo (0-6 meses)**
1. ✅ Desplegar campaña educativa en colegios y universidades
2. ✅ Aumentar presencia policial viernes 7-9 AM en puntos críticos
3. ✅ Auditoría de señalización en top 10 intersecciones peligrosas
4. ✅ Programa piloto "Motociclista Seguro" en Teusaquillo

### **Mediano Plazo (6-12 meses)**
1. 🔄 Rediseño geométrico de 5 intersecciones críticas
2. 🔄 Implementación de semaforización inteligente
3. 🔄 Creación de ciclorrutas protegidas
4. 🔄 Sistema de monitoreo con cámaras en tiempo real

### **Largo Plazo (1-3 años)**
1. 🎯 Plan integral de seguridad vial Teusaquillo 2025-2027
2. 🎯 Infraestructura completa para movilidad sostenible
3. 🎯 Integración con sistemas distritales de movilidad inteligente
4. 🎯 Reducción objetivo: 30% de siniestralidad para 2027

---

## 📖 Contexto del Proyecto

<img width="458" height="446" alt="image" src="https://github.com/user-attachments/assets/51ecd402-de38-4c5b-9f25-11b64501ae15" />


**Localización:** Teusaquillo, Bogotá D.C., Colombia  
**Área:** 1,421 hectáreas (Centro de Bogotá)  
**Periodo de Análisis:** 2015-2023  
**Alineación:** Plan Nacional y Distrital de Seguridad Vial

**Límites:**
- Norte: Fontibón, Engativá, Barrios Unidos (Calle 63, Av. 68)
- Sur: Mártires, Puente Aranda
- Oriente: Chapinero, Santa Fe (Carrera 14, Av. 26)
- Occidente: Av. 68, Calle 22

---

## 🎯 Habilidades Demostradas

- ✅ **Business Intelligence** (Power BI, DAX)
- ✅ **Data Cleaning** (Excel, Power Query)
- ✅ **Urban Analytics** (patrones de movilidad)
- ✅ **Statistical Analysis** (tendencias, segmentación)
- ✅ **Data Storytelling** (narrativa con datos)
- ✅ **Public Policy Analysis** (seguridad vial)
- ✅ **ETL Processes** (datos abiertos gubernamentales)

---

## 👤 Autor

**Aarón Mateo Tocora Jiménez**  
📍 Bogotá D.C., Colombia  

---

## 📚 Referencias

- [Secretaría Distrital de Movilidad - Datos Abiertos](https://datos.movilidadbogota.gov.co/)
- [Datos Abiertos Bogotá](https://datosabiertos.bogota.gov.co/)
- Plan Nacional de Seguridad Vial
- Plan Distrital de Seguridad Vial Bogotá

---

## 📄 Licencia

Este proyecto es de uso académico y demostrativo para portafolio profesional.

---

**⭐ Este análisis puede salvar vidas. Comparte para crear conciencia sobre seguridad vial.**
