# Challenge 1 
## Análisis de balance de tiendas

### Descripción
En este proyecto se busca analizar el balance de las cuatro tiendas utilizando las bibliotecas `Pandas` y `Matplotlib`, con el fin de generar gráficos que permitan identificar las fortalezas y debilidades de cada una. Además, se representa la ubicación de las tiendas mediante la biblioteca `Cartopy`.


#### Objetivo 
El objetivo es identificar la tienda con los balances más bajos para recomendar al señor Juan cuál debería vender e invertir así en un nuevo negocio.

---
## Uso del proyecto

### 1- Instalar las bibliotecas a implementar de forma local
- [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)
- [Numpy](https://numpy.org/install/)
- [Matplotlib](https://matplotlib.org/stable/install/index.html)
- cartopy

  **Nota:** si se van a implementar en colab solo se debe instalar `cartopy` de la sigiente forma:
  ```  
  !pip install cartopy
  ```

### 2- Importar base de datos:

-  Por medio de gitHub:
 ```
"https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv"
```
```
"https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv"
```
```
"https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv"
```
```
"https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv"
```

- Por medio local
  se debe remplazar en las variables url1, url2, url3 y url4
  referenciar la hubicacion de los archivos:
```
  ./base-de-datos-challenge1latam/tienda_1 .csv
```
```
  ./base-de-datos-challenge1latam/tienda_2.csv
```
```
  ./base-de-datos-challenge1latam/tienda_3.csv
```
```
  ./base-de-datos-challenge1latam/tienda_4.csv
```

- Por colab:
  > El código está implementado para su uso en Colab. Solo ejecuta el archivo si la carpeta se guarda directamente en el Drive; de lo contrario, deberás buscar la carpeta "Alura" y copiar la dirección.

