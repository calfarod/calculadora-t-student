# 📊 Calculadora Interactiva de la Distribución t de Student

Una aplicación web interactiva, liviana y responsive diseñada para estudiantes, docentes e investigadores en estadística. Permite visualizar la Función de Densidad de Probabilidad (PDF) de la **distribución $t$ de Student**, calcular valores críticos ($t_{\alpha/2}$) y áreas de colas, así como comparar gráficamente la distribución $t$ con la **distribución Normal Estándar ($Z$)**.

---

## 🚀 Características Principales

* **Visualización Dinámica:** Gráfico en tiempo real mediante HTML5 Canvas que ajusta la curva y las áreas sombreadas según los parámetros seleccionados.
* **Cálculos Estadísticos Precisos:**
  * Aproximación de Lanczos para la función Gamma ($\Gamma$).
  * Cálculo de valores críticos mediante búsqueda numérica de raíces (Bisección).
* **Parámetros Ajustables:**
  * Grados de libertad ($\nu$ o $df$) desde $1$ hasta $120$.
  * Niveles de confianza habituales ($80\%$, $90\%$, $95\%$, $98\%$, $99\%$).
  * Enfoque de **dos colas** ($t_{\alpha/2}$) o **una cola** ($t_\alpha$).
* **Superposición Comparativa:** Opción para activar la curva de la Distribución Normal Estándar ($Z$) y observar la convergencia a medida que aumentan los grados de libertad.
* **Copia Rápida:** Botón para copiar el resumen de resultados en un solo clic para tareas, informes o guías de estudio.
* **Sin Dependencias Externas:** Desarrollado en **HTML5, CSS3 y JavaScript vanilla** puro. Funciona en cualquier navegador sin necesidad de servidor backend ni instalación de librerías.

---

## 🛠️ Estructura del Repositorio

El proyecto mantiene una estructura simple de archivo único para facilitar su alojamiento y distribución:

```text
calculadora-t-student/
├── index.html         # Aplicación web completa (HTML, CSS y JS integrados)
├── img                # Activos visuales
|    └── formula1.jpg  # Documentación de
└── README.md          # Documentación del proyecto
```

Thank you Lord ❤️