# Novaretail_proyect_analysis
Explorando drivers de comportamiento en NovaRetail+

## 🎯 Objetivo
Analizar los factores que influyen en el comportamiento de los clientes de NovaRetail+ para identificar patrones que ayuden a mejorar la retención y optimizar estrategias de marketing.

## 📊 Descripción del dataset
El conjunto de datos contiene información de clientes y su actividad mensual en la plataforma:

- **id_cliente:** Identificador único del cliente  
- **edad:** Edad del cliente  
- **nivel_ingreso:** Ingreso anual estimado  
- **visitas_mes:** Número de visitas mensuales al sitio o app  
- **compras_mes:** Número de compras realizadas en el mes  
- **gasto_publicidad_dirigida:** Gasto en anuncios asignado al usuario  
- **satisfaccion:** Calificación del cliente (1–5)  
- **miembro_premium:** 1 si tiene suscripción premium, 0 si no  
- **abandono:** 1 si abandonó la plataforma, 0 si no  
- **tipo_dispositivo:** Móvil, escritorio o tablet  

## 🧠 Metodología
1. **Carga y exploración del dataset:** Validación de tipos de datos, valores faltantes y rangos.  
2. **Análisis de correlaciones:** Identificación de relaciones entre variables numéricas.  
3. **Visualización:** Uso de `seaborn` y `matplotlib` para representar correlaciones y patrones.  
4. **Interpretación:** Detección de variables que influyen en la satisfacción y el abandono.  
5. **Recomendaciones:** Propuestas basadas en hallazgos estadísticos.

## 🧰 Tecnologías utilizadas
- Python 3  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Jupyter Notebook  

## 📈 Principales hallazgos
- Alta correlación entre **visitas_mes** y **compras_mes** → mayor actividad impulsa ventas.  
- Relación negativa entre **satisfaccion** y **abandono** → clientes satisfechos permanecen más tiempo.  
- Los **miembros premium** muestran mayor frecuencia de compra y menor tasa de abandono.

## 💡 Recomendaciones
- Implementar campañas de retención para usuarios con baja satisfacción.  
- Optimizar publicidad dirigida a clientes con alto nivel de ingreso.  
- Analizar comportamiento de miembros premium para potenciar su fidelización.

## 📂 Estructura del repositorio
Novaretail_proyect_analysis/
│
├── data/                     # Dataset original y procesad
├── novaretail_analysis.ipynb # Notebook principal del análisis
├── requirements.txt           # Librerías necesarias
└── README.md                  # Descripción del proyecto
