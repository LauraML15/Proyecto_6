# Análisis de Ventas de Videojuegos - Ice Store 🎮

## 📌 Descripción del Proyecto
Este proyecto se desarrolló como parte de un análisis de negocio para la tienda online **Ice**, que vende videojuegos en todo el mundo.  
El objetivo principal fue **identificar patrones que determinan si un juego tiene éxito o no**, con el fin de detectar proyectos prometedores y planificar campañas publicitarias más efectivas.  

Los datos incluyen información de 1980 a 2016, como reseñas de usuarios y críticos, géneros, plataformas (Xbox, PlayStation, etc.), ventas regionales y la clasificación ESRB.

> Imaginamos estar en diciembre de 2016, con el reto de pronosticar ventas y tendencias para el año 2017.  

---

## 🎯 Objetivos del Análisis
1. **Preparación de datos**  
   - Limpieza y estandarización de columnas.  
   - Tratamiento de valores ausentes.  
   - Creación de métricas como las *ventas globales*.  

2. **Análisis exploratorio (EDA)**  
   - Tendencias de lanzamientos por año.  
   - Comparación de ventas entre plataformas.  
   - Identificación de ciclos de vida de consolas.  
   - Efecto de reseñas (usuarios y críticos) sobre ventas.  
   - Distribución y rentabilidad de los géneros.  

3. **Perfil de usuario por región**  
   - NA (Norteamérica), UE (Europa), JP (Japón).  
   - Principales plataformas y géneros por región.  
   - Influencia de la clasificación ESRB en cada mercado.  

4. **Pruebas de hipótesis**  
   - Diferencias en calificaciones de usuarios entre Xbox One y PC.  
   - Diferencias en calificaciones de usuarios entre juegos de Acción y Deportes.  

---

## 🛠️ Herramientas Utilizadas
- **Python** 🐍  
- **Pandas** para manipulación de datos.  
- **Matplotlib / Seaborn** para visualización.  
- **NumPy** para operaciones estadísticas.  
- **SciPy** para pruebas de hipótesis.  
- **Jupyter Notebook** para documentación del flujo de trabajo.  

---

## 📊 Resultados Destacados
- Las plataformas muestran **ciclos de vida claros**, con picos de ventas seguidos de declive en un rango de 5-10 años.  
- Las **reseñas de críticos** tienen una correlación más fuerte con las ventas que las reseñas de usuarios.  
- Los géneros **Acción y Deportes** son los más rentables a nivel global, aunque difieren en popularidad según la región.  
- La clasificación **ESRB** influye más en Norteamérica y Europa que en Japón.  
- Se identificaron **plataformas con potencial para 2017** (ej. PS4, Xbox One, 3DS).  

---

## 📌 Conclusión General
El análisis permitió construir un marco de referencia sobre **tendencias históricas de la industria de videojuegos**, aportando información valiosa para planificar campañas publicitarias y apoyar la toma de decisiones estratégicas.  

En resumen: el éxito de un videojuego depende no solo de su plataforma y género, sino también de la aceptación de críticos, del ciclo de vida de la consola y de la región en la que se comercializa.  

---

## 🚀 Ejecución
Clona el repositorio y abre el Jupyter Notebook:  

```bash
git clone https://github.com/usuario/nombre-repo.git
cd nombre-repo
jupyter notebook

