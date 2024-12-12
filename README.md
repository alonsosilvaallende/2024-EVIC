# Presentación Mejorando la generación aumentada con recuperación (RAG) con la búsqueda híbrida en la conferencia EVIC 2024

La **presentación** se encuentra [aquí](https://alonsosilvaallende.github.io/2024-EVIC/).

El **notebook presentado** puede encontrarse [aquí](https://github.com/alonsosilvaallende/2024-EVIC/blob/main/EVIC.ipynb).

Para correr el notebook, se instalan los `requeriments.txt`:
```
pip install -r requirements.txt
```
Se debe instalar también `llama-cpp-python` y la instalación dependerá de la utilización o no de GPUs. En el caso más simple (sin GPUs):
```
pip install llama-cpp-python
```
Sino, seguir estas [instrucciones](https://github.com/abetlen/llama-cpp-python?tab=readme-ov-file#installation).

Esta presentación se llevó a cabo el 12 de diciembre de 2024.

El **abstract** de la presentación es:

> Los gráficos de conocimiento son excelentes para representar y almacenar información heterogénea e interconectada de manera estructurada, capturando de manera eficaz relaciones y atributos complejos en diferentes tipos de datos. La generación de texto estructurado permite crear gráficos de conocimiento al proporcionar resultados perfectamente estructurados, lo que lo convierte en un método ideal para extraer información estructurada. De manera similar, la generación de texto estructurado permite la creación de agentes al definir qué herramientas están permitidas y qué entradas de acción están permitidas. En esta charla, primero construimos una base de datos de gráficos a partir de datos no estructurados y luego creamos un agente para consultar la base de datos de gráficos.
