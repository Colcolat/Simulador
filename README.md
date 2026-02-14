# Simulador de Asignación de Memoria: Best Fit & Worst Fit

## a. Introducción
Este proyecto es un **Simulador HTML Interactivo** desarrollado para la unidad de "Memoria y Procesos de Entrada-Salida". Su objetivo es visualizar y comparar cómo funcionan los algoritmos de asignación de memoria en un entorno controlado, permitiendo gestionar bloques de memoria y procesos de manera dinámica.

## b. Instrucciones
Para utilizar el simulador, sigue estos pasos:
1.  **Ingreso de Datos**: En los campos de texto, introduce los tamaños de los bloques de memoria y de los procesos separados por comas.
2.  **Ejecución**: Haz clic en el botón **"Simular Best Fit"** o **"Simular Worst Fit"** según el algoritmo que desees probar.
3.  **Interpretación de Resultados**:
    * **Visualización de Bloques**: Se mostrarán cuadros que indican cuánto espacio de cada bloque está "usado" y cuánto permanece "libre".
    * **Fragmentación**: El sistema calculará la fragmentación total resultante después de las asignaciones.
    * **Tabla de Asignación**: Se generará una tabla que detalla qué proceso fue asignado a cada bloque o si algún proceso no pudo ser asignado por falta de espacio.

## c. Explicación de los Algoritmos
* **Best Fit (Mejor Ajuste)**: Este algoritmo recorre la memoria para encontrar el bloque libre más pequeño que sea suficiente para el proceso. Busca minimizar el desperdicio de memoria en cada bloque individual.
* **Worst Fit (Peor Ajuste)**: Este algoritmo selecciona siempre el bloque más grande disponible para colocar un proceso. La idea teórica es dejar un fragmento restante lo suficientemente grande como para que pueda ser útil para otros procesos.

## d. Reflexión
La gestión de memoria es un equilibrio entre velocidad de búsqueda y eficiencia de aprovechamiento. Mientras que **Best Fit** intenta ser óptimo en el uso del espacio, puede generar muchos fragmentos pequeños inutilizables (fragmentación externa). **Worst Fit** intenta combatir esto dejando huecos grandes, pero puede agotar rápidamente los bloques de gran tamaño necesarios para procesos pesados. La simulación permite observar estas diferencias de manera inmediata según los datos de entrada.

## e. Referencias
* Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). *Operating System Concepts*. Wiley.
* Tanenbaum, A. S., & Bos, H. (2014). *Modern Operating Systems*. Pearson.

