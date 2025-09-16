# netflix_sql_proyecto
analisis de titulos de netflix usando sql 


 🎬 Análisis de títulos de Netflix con SQL avanzado

Este proyecto aplica técnicas de SQL avanzado para analizar el catálogo de títulos de Netflix. Utilizando SQLite como motor de base de datos, se exploran patrones de distribución geográfica, tipos de contenido y estrategias de oferta mediante consultas complejas como CTE, funciones de ventana y simulación de OLAP.

---

 📁 Archivos incluidos

- `netflix_titles.csv`: Dataset original con información de títulos.
- `netflix_titles.db`: Base de datos SQLite con la tabla cargada.
- `consultas.sql`: Archivo con las tres consultas principales del análisis.
- `README.md`: Documentación del proyecto y hallazgos clave.

---

 🧠 Consultas aplicadas

1. CTE (Common Table Expression)
   Para calcular el ranking de países según la cantidad de títulos disponibles.

2. Window Function
   Para obtener el top 5 de países con más títulos, sin eliminar los datos restantes.

3. OLAP simulado con UNION ALL  
   Para mostrar subtotales por tipo de contenido y un total general, dado que SQLite no soporta `ROLLUP`.

---

🔍 Insights principales

1. Concentración geográfica del catálogo  
   Estados Unidos lidera ampliamente en cantidad de títulos disponibles en Netflix, lo que refleja su rol dominante en la producción audiovisual global.

2. Preferencia por contenido seriado 
   El análisis por tipo revela que los **TV Shows** superan en número a las películas en varios países, lo que sugiere una estrategia de contenido seriado para fomentar la retención de usuarios.

3. Distribución desigual y focalizada 
   El análisis OLAP simulado muestra que la mayoría del contenido está concentrado en pocos países y tipos, lo que podría estar vinculado a decisiones estratégicas de licencias o preferencias culturales.


 ✅ Conclusión

Este análisis permitió explorar el catálogo de Netflix desde una perspectiva estructurada y técnica, utilizando SQL avanzado en un entorno SQLite. Las consultas aplicadas ofrecieron una visión clara sobre la distribución geográfica, el tipo de contenido y la estrategia de oferta de la plataforma. El enfoque modular y escalable del proyecto lo convierte en una base sólida para futuros análisis más profundos.

🙌 Créditos
~ Nieva Ebe 
~ Pista Marcos 

