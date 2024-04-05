# ElectromagnetismoI

# Tarea 3: Ecuación de Laplace - Método de Relajación

Este repositorio contiene el código fuente de un programa implementado en Python para resolver la ecuación de Laplace en un dominio rectangular utilizando el método de relajación. La tarea forma parte de un proyecto académico para el curso "Ecuaciones Diferenciales Parciales" impartido por el Profesor Gabriel Téllez.

## Descripción del Programa

El programa acepta como entrada el número de puntos de la red \( N \) y \( M \), el tamaño del paso \( dx = dy \), y los valores de las condiciones de frontera \( V0(x, y) \) en los bordes del dominio. Luego, devuelve la solución de la ecuación de Laplace \( V(x, y) \) utilizando el método de relajación.

## Contenido del Repositorio

- **`laplace_relaxation.py`**: Contiene el código fuente del programa implementado en Python.
- **`test_laplace_relaxation.py`**: Contiene el código de prueba para verificar el correcto funcionamiento del programa.
- **`README.md`**: Proporciona información sobre el repositorio y cómo ejecutar el programa y las pruebas.
- **`solucion_computacional.png`**: Imagen que muestra la solución computacional de la ecuación de Laplace en 2D y 3D.
- **`solucion_analitica.png`**: Imagen que muestra la solución analítica de la ecuación de Laplace en 2D y 3D.
- **`informe.pdf`**: Documento que contiene un informe detallado sobre el método de relajación, la implementación del programa, la solución analítica y computacional, y el análisis de los resultados.

## Instrucciones de Uso

Para ejecutar el programa y realizar las pruebas, sigue estos pasos:

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener Python instalado en tu sistema.
3. Abre una terminal y navega al directorio donde clonaste el repositorio.
4. Ejecuta el programa principal con el siguiente comando:

   ```
   python laplace_relaxation.py
   ```

5. Para ejecutar las pruebas, utiliza el siguiente comando:

   ```
   python test_laplace_relaxation.py
   ```

## Referencias

- Documentación de Python: [https://docs.python.org/3/](https://docs.python.org/3/)
- Matplotlib: [https://matplotlib.org/](https://matplotlib.org/)
- NumPy: [https://numpy.org/](https://numpy.org/)

---

