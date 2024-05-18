# Ciencia de Redes - Semestre 2021-2

Este repositorio contiene el material del curso Ciencia de Redes correspondiente al semestre 2021-2. 
Aquí encontrarás notebooks, tareas y proyectos relacionados con el estudio de redes complejas, incluyendo redes reales, modelos teóricos y sus propiedades.

## Contenido

- **Sesiones del Curso:**
  - [Sesión 1, 29-sep-2020: Introducción a numpy y networkx 1](Sesión%201,%2029-sep-2020,%20Introducción%20a%20numpy%20y%20networkx%201.ipynb)
  - [Sesión 2, 06-oct-2020: Introducción a numpy y networkx 2](Sesión%202,%2006-oct-2020,%20Introducción%20a%20numpy%20y%20networkx%202.ipynb)
  - [Sesión 3, 13-oct-2020: Matriz de adyacencia, redes reales y medidas de centralidad](Sesión%203,%2013-oct-2020.%20Matriz%20de%20adyacencia,%20redes%20reales%20y%20medidas%20de%20centralidad.ipynb)
  - [Sesión 4, 20-oct-2020: Coeficiente de acumulación y distribución de grado](Sesión%204,%2020-oct-2020,%20Coeficiente%20de%20acumulación%20y%20distribución%20de%20grado.ipynb)
  - [Sesión 5, 27-oct-2020: Componentes y comunidades](Sesión%205,%2027-oct-2020,%20Componentes%20y%20comunidades.ipynb)
  - [Sesión 6, 03-nov-2020: Redes aleatorias](Sesión%206,%2003-nov-2020,%20Redes%20aleatorias.ipynb)
  - [Sesión 7, 10-nov-2020: Redes aleatorias 2](Sesión%207,%2010-nov-2020,%20Redes%20aleatorias%202.ipynb)
  - [Sesión 8, 05-enero-2021](Sesión%208,%2005-enero-2021.ipynb)

- **Proyectos:**
  - [Proyecto final](Proyecto%20final%20.ipynb)

- **Tareas:**
  - [Tarea: Visualización medidas de centralidad](Tarea_%20Visualización_medidas_de%20_centralidad.ipynb)

- **Modelos y Simulaciones:**
  - [Redes con independencia de escala (scale-free)](Redes%20con%20independencia%20de%20escala%20(scale-free).ipynb)
  - [Redes grandes](Redes%20grandes%20.ipynb)
  - [Barabasi Albert solución](Barabasi_Albert_solucion.ipynb)
  - [Watts Strogatz (mundo pequeño)](Watts_Strogatz_(mundo_pequeño).ipynb)
  - [Watts Strogatz (mundo pequeño 2)](Watts_Strogatz_(mundo_pequeño_2).ipynb)

- **Datos de Ejemplo:**
  - [bio-celegans-dir.edges](bio-celegans-dir.edges)
  - [bn-mouse_visual-cortex_2.edges](bn-mouse_visual-cortex_2.edges)
  - [ENZYMES_g297.edges](ENZYMES_g297.edges)

- **Importa los datos en los notebooks de manera adecuada:**
  -Asegúrate de que los archivos de datos están en el mismo directorio que los notebooks o proporciona la ruta correcta al cargar los datos. Por ejemplo, para cargar un archivo .edges en un notebook, usa:
    import networkx as nx
    G = nx.read_edgelist('ruta_al_archivo.edges', create_using=nx.DiGraph())
    Ajusta 'ruta_al_archivo.edges' según la ubicación del archivo de datos en tu sistema.

