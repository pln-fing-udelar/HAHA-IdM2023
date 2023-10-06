# HAHA (Ingeniería de Muestra 2023)

En este repositorio se encuentran los datos de entrenamiento (``train.csv``) y desarrollo (``dev.csv``) para la competencia **HAHA**. 
Cada ``.csv`` contiene pares (text,es_humor).

Para la carga de datos se puede seguir el enfoque que resulte más práctico, pero una recomendación es usar la biblioteca ``urllib`` para Python:

```
import urllib.request

urllib.request.urlretrieve("https://raw.githubusercontent.com/pln-fing-udelar/HAHA-IdM2023/main/train.csv", "train.csv")
urllib.request.urlretrieve("https://raw.githubusercontent.com/pln-fing-udelar/HAHA-IdM2023/main/dev.csv", "dev.csv")

```

## Más detalles

Por más detalles dirigirse a la web de los desafíos: https://www.fing.edu.uy/inco/grupos/pln/desafiosPLN/

Correo de contacto: pln@fing.edu.uy
