<div align="center">
  <img src="https://aplicativos.udi.edu.co/proacudi/img/logo-udi.png" alt="Logo UDI" width="300">
  <br><br>

  # Calculadora de Investigación de Operaciones
  **Álgebra Lineal | Universitaria de Investigación y Desarrollo (UDI)**

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JS"/>
    <img src="https://img.shields.io/badge/Plotly.js-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly"/>
  </p>
</div>

---

## 📋 Descripción

Este proyecto es una aplicación web diseñada para resolver problemas de **Programación Lineal** de forma interactiva y didáctica. Fue desarrollada como parte del curso de Investigación de Operaciones/Álgebra Lineal de la **UDI**.

La herramienta permite a los estudiantes verificar sus ejercicios manuales y comprender la lógica detrás de los algoritmos de optimización mediante dos módulos principales:

1.  **Método Gráfico:** Visualización geométrica para problemas de 2 variables.
2.  **Método Simplex:** Solución tabular paso a paso para problemas de *n* variables.

## 🚀 Funcionalidades Principales

### 📈 Módulo 1: Método Gráfico
* **Interfaz Intuitiva:** Diseño limpio para ingresar coeficientes de la función objetivo y restricciones.
* **Dinámico:** Permite agregar ($+$) o eliminar ($-$) restricciones según sea necesario.
* **Visualización Avanzada:**
    * Graficación de las líneas de restricción.
    * **Sombreado automático** de la Región Factible.
    * Identificación visual de los vértices.
    * Trazo de la línea de la función objetivo (Isocuanta) sobre el punto óptimo.
* **Tabla de Resultados:** Lista todos los vértices factibles y su valor en $Z$, resaltando la solución óptima.

### 🔢 Módulo 2: Método Simplex (Paso a Paso)
* **Algoritmo Completo:** Implementación de la lógica matricial de Gauss-Jordan utilizando JavaScript puro (sin librerías de "caja negra" para el cálculo).
* **Iteraciones Detalladas:** Muestra cada tabla simplex generada durante el proceso.
* **Ayudas Visuales:**
    * Identificación automática del **Elemento Pivote** (Círculo azul).
    * Explicación textual de qué variable entra y cuál sale de la base en cada iteración (Cuadro amarillo).
    * Detección automática de condiciones de parada.
* **Resultado Final:** Resumen claro de la solución óptima en un recuadro verde destacado.

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+).
* **Librerías:**
    * `Plotly.js` (vía CDN) para la generación de gráficos vectoriales interactivos.
* **Fuentes:** Google Fonts (Roboto) para una apariencia moderna y legible.

## 📂 Estructura del Proyecto

```text
📁 Trabajo_Algebra/
│
├── 📄 index.html      # Menú principal con navegación y Logo UDI
├── 📄 grafico.html    # Calculadora del Método Gráfico
├── 📄 simplex.html    # Calculadora del Método Simplex tabular
└── 📄 README.md       # Documentación del proyecto
