# 📦 Análisis de Exportaciones de Frutas – Dashboard en Tableau

Este proyecto tiene como objetivo desarrollar un **dashboard interactivo en Tableau** para analizar datos históricos de exportaciones de frutas por parte de empresas internacionales a diversos países y clientes. El análisis busca identificar patrones de consumo, rendimiento empresarial y distribución geográfica tanto en volumen (toneladas) como en ganancias monetarias.

---

## 🧠 ¿Por qué este proyecto?

El comercio internacional de frutas es un sector clave para muchas economías agrícolas. Entender qué clientes compran más, qué frutas son más exportadas y qué países generan mayores ganancias es vital para optimizar la logística, definir estrategias comerciales y detectar nuevas oportunidades de mercado.

Este dashboard puede ser utilizado por **exportadoras, cámaras de comercio, analistas de mercado** o autoridades gubernamentales para:

- Evaluar el rendimiento por empresa
- Detectar tendencias de consumo por cliente o país
- Tomar decisiones basadas en datos para futuras campañas de exportación

---

## 🔍 Preguntas que responde el dashboard

1. ¿Qué clientes compraron más toneladas de fruta?
2. ¿Qué empresa fue la mayor exportadora en volumen?
3. ¿Qué fruta compra cada cliente con mayor frecuencia?
4. ¿Qué países generaron mayores ganancias?
5. ¿Cuál es el porcentaje de ganancias por país sobre el total exportado?
6. ¿Qué porcentaje de las toneladas exportadas corresponde a cada país?

---

## 📁 Archivos del Proyecto

| Archivo                        | Descripción                                                  |
|-------------------------------|--------------------------------------------------------------|
| `Data Exportaciones.xlsx`     | Detalle de cada operación: cliente, país, fruta, toneladas, ganancias |
| `Empresa.csv`                 | Identificador y nombre de cada empresa exportadora          |
| `Frutas.txt`                  | Catálogo de frutas con sus respectivos IDs                  |
| `Imágenes/`                   | Capturas del modelo de datos y dashboard final              |
| `Dashboard Exportación`       | Dashboard del proyecto                                      |
| `README.md`                   | Documentación del proyecto                                  |

---

## 🔗 Modelo de Datos

En Tableau, se diseñó un modelo relacional conectando:

- Las exportaciones (hechos) con:
  - el catálogo de empresas
  - el catálogo de frutas

Esto permite mantener integridad referencial y facilitar los análisis por dimensiones como fruta, empresa y cliente.

---

## 📊 Visualizaciones Incluidas

- 📌 **Ranking de Clientes por Toneladas**
- 🏭 **Ranking de Empresas Exportadoras**
- 🍊 **Exportaciones por Cliente y Fruta**
- 🌎 **Ganancias por País**
- 💰 **% de Ganancias por País**
- ⚖️ **Distribución de Toneladas Exportadas por País (donut chart)**

📷 **Captura del Dashboard Final:**

<img src="Imágenes/Dashboard.png" alt="Vista del dashboard" width="600"/>

---

## 📈 Insights Relevantes

- 🔝 **China** lidera el ranking de ganancias, con más de **92 millones de USD**, representando más del **30% del total**.
- 🇺🇸 **Estados Unidos y Canadá** también son destinos clave, con un volumen importante de toneladas exportadas, aunque con ganancias ligeramente menores.
- 🥑 **Palta, Mandarina y Naranja** son las frutas más exportadas en volumen, destacando su preferencia internacional.
- 👤 Algunos clientes presentan una alta concentración en frutas específicas, lo que puede indicar oportunidades de diversificación o estrategias de fidelización.
- 📦 La **empresa con mayor volumen exportado** difiere de la que más ganancias genera, lo cual invita a revisar estrategias de precios o márgenes por tipo de fruta y país.

---

## 📌 Conclusiones

- Existe una **concentración de ganancias en pocos países**, lo que puede representar un riesgo si alguno de esos mercados cae.
- La diversificación de frutas por cliente es clave: algunos clientes compran solo 1 o 2 frutas, lo que limita el potencial de venta cruzada.
- Es posible que algunas empresas estén **sacrificando rentabilidad por volumen**, mientras que otras logran mayor margen con menos toneladas.
- Este tipo de dashboards permite detectar **ineficiencias o oportunidades ocultas** en la cadena de exportación.

---

## 💻 Herramientas Utilizadas

- **Tableau Desktop / Public**: visualización y construcción del dashboard
- **Microsoft Excel**: limpieza y preparación de los datos
- **CSV / TXT / XLSX**: múltiples fuentes integradas en Tableau

---

## 🚀 Acceso al Dashboard

🔗 [**Ver en Tableau Public**](#) *(Reemplazar con el enlace cuando esté publicado)*

---

## 📂 Estructura del Repositorio



**Octavio Alvarez**  
[LinkedIn](https://linkedin.com/in/octavio-alvarez-6a229b223)

