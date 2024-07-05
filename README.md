**Búsqueda en Google por Fecha y Dominio**

**Un script sencillo** de Python que te permite buscar en Google resultados dentro de un rango de fechas específico y dominio. El script solicita la entrada del usuario para la palabra clave de búsqueda, fechas de inicio y fin, y tipo de dominio, y luego utiliza la biblioteca `googlesearch` para obtener los resultados de la búsqueda. Los resultados se guardan en un archivo de texto con las entradas de búsqueda y fechas de timestamp.

**Características:**

* Busca en Google resultados dentro de un rango de fechas específico
* Filtra resultados por tipo de dominio (por ejemplo, .com, .org, .edu)
* Guarda los resultados de la búsqueda en un archivo de texto con las entradas de búsqueda y fechas de timestamp

**Uso:**

1. Ejecuta el script y entra la palabra clave de búsqueda, fechas de inicio y fin, y tipo de dominio cuando se te solicite.
2. El script obtendrá los resultados de la búsqueda y los guardará en un archivo de texto con las entradas de búsqueda y fechas de timestamp.

**INSTALACIÓN Y NOTAS:**
* **DEBIAN:**
* Instala python (si aun no lo tienes): ```sudo apt update && sudo apt install python3```
* Crear un entorno virtual: ```python3 -m venv pysearch```
* Activa el entorno virtual: ```source pysearch/bin/activate```
* Instala la biblioteca de Google API Client Library para Python: ```pip install google```
* Arrancar el script: ```python3 pysearch.py```
