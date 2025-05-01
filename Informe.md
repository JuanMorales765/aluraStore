# Balance de tiendas señor Juan

### Descripción
En este proyecto se busca analizar el balance de las cuatro tiendas utilizando las bibliotecas `Pandas` y `Matplotlib`, con el fin de generar gráficos que permitan identificar las fortalezas y debilidades de cada una. Además, se representa la ubicación de las tiendas mediante la biblioteca `Cartopy`.


#### Objetivo 
El objetivo es identificar la tienda con los balances más bajos para recomendar al señor Juan cuál debería vender e invertir así en un nuevo negocio.

---

![Imagen1](AluraStore/challenge1-data-science-latam-main/graficas/ingresosTotales.png)
##### Fig.1.Propia (La imagen muestra el total de los ingresos de las diversas tiendas con un porcentaje basado en el 100%)

Como se puede observar en la imagen, la tienda con menores ingresos es la número cuatro, con un total de `$1,038,375.70`. Para este análisis, sería la tienda opcional para que el señor Juan realice sus ventas. Para obtener estos resultados, se sumaron los valores de la columna "Precios" con el fin de calcular los ingresos de todas las tiendas.

---

![Imagen2](https://github.com/JuanMorales765/aluraStore/tree/main/AluraStore/challenge1-data-science-latam-main/graficas/Top3.png)
##### Fig. 2. Propia (La imagen muestra un top 3 de los productos más vendidos en cada tienda).


En la imagen se puede observar que los productos más vendidos son los muebles, los electrónicos y los juguetes. Este análisis muestra que la tienda dos es la que menos productos vende, con `442` unidades de muebles, `422` de electrónicos y `313` de juguetes, en comparación con el top del mercado establecido por las demás tiendas.
Se optó por mostrar un top de productos para lograr una mejor visualización de los datos, ya que presentar únicamente el artículo más vendido no brindaría un resultado representativo. De esta manera, se puede tener una mejor idea de qué tipos de artículos son los más comercializados por las tiendas.

---

![Imagen3](https://github.com/JuanMorales765/aluraStore/tree/main/AluraStore/challenge1-data-science-latam-main/graficas/calificaciónClientesTiendas.png)
##### Fig.3.Propia ( La imagen muestra la satisfacción de los clientes en cuanto a las tiendas donde adquirieron sus productos.

Como se puede ver en la imagen, la tienda con menor nivel de satisfacción por parte de los clientes es la tienda uno con un puntaje promedio de `3.98` de nivel de satisfacción de los clientes, segunda es la tienda cuatro con un valor de satisfacción de `4.00` de los clientes . Los datos no varían mucho entre las tiendas. También se tiene en cuenta que muchos usuarios están conformes, si se compara en una escala del uno al cinco, donde cinco representa el nivel máximo de satisfacción.

---

![Imagen4](https://github.com/JuanMorales765/aluraStore/tree/main/AluraStore/challenge1-data-science-latam-main/graficas/Productos-menos-y-mas-vendidos.png)
##### Fig.4.Propia (La imagen muestra los artículos más y menos vendidos en todas las tiendas)

En este análisis se puede observar que los muebles son los artículos más vendidos  en todas las tiendas, mientras que los menos vendidos son los artículos para el hogar y los instrumentos musicales. También se puede concluir que la tienda dos es la que menos productos del top de ventas ofrece a los clientes con `442` productos más vendidos que pretenece a la categoria de muebles y la tienda cuatro con `170` unidades.

---

![Imagen5](https://github.com/JuanMorales765/aluraStore/tree/main/AluraStore/challenge1-data-science-latam-main/graficas/gastosEnvios.png)
##### Fig.5.Propia (La imagen muestra los gastos de los envios de los diversos productos).

En esta grafica demuestra que la tienda cuatro es la que menos envios realiza con `$23,459.46` lo cual concuerda con ser la tienda con menores ingresos.


### Análisis de húbicación de las tiendas:

![Imagen6](https://github.com/JuanMorales765/aluraStore/tree/main/AluraStore/challenge1-data-science-latam-main/graficas/Map1.png)
##### Fig. 6. Propia (La imagen muestra la ubicación de la tienda 1)
A partir de esta imagen, se puede observar la distribución de las tiendas según los datos de ventas de la tienda 1.

![Imagen7](https://github.com/JuanMorales765/aluraStore/tree/main/AluraStore/challenge1-data-science-latam-main/graficas/Map2.png)
##### Fig.7.Propia (La imagen muestra la ubicación de la tienda 2)
En base a esta imagen se puede observar la distribución de las tiendas según los datos de las ventas de la tienda 2.

![Imagen8](https://github.com/JuanMorales765/aluraStore/tree/main/AluraStore/challenge1-data-science-latam-main/graficas/Map3.png)
##### Fig.8.Propia (La imagen muestra la ubicación de la tienda 3)
En base a esta imagen se puede observar la distribución de las tiendas según los datos de las ventas de la tienda 3.


![Imagen9](https://github.com/JuanMorales765/aluraStore/tree/main/AluraStore/challenge1-data-science-latam-main/graficas/Map4.png)
##### Fig.9.Propia (La imagen muestra la ubicación de la tienda 4)
En base a esta imagen se puede observar la distribución de las tiendas según los datos de las ventas de la tienda 4.

## Conclución

Se recomienda al señor Juan considerar la venta de la tienda cuatro, ya que presenta los ingresos más bajos, a pesar de tener buenas ventas de productos del top 3. Sin embargo, estas ventas se ven amortiguadas por el hecho de que la ubicación de las tiendas es muy similar, y geográficamente pueden cubrir la demanda de la tienda que se venda sin afectar significativamente el rendimiento general.


También se puede concluir que el análisis del top 3 de productos solo brinda una visión general de lo más comercializado. Por ello, se mantiene la decisión de que el señor Juan debería vender la tienda cuatro, ya que los productos más vendidos no se verán afectados a largo plazo, dado que las demás tiendas también ofrecen estos artículos y cuentan con una alta valoración por parte de los clientes.


En cuanto a la satisfacción de los clientes, es necesario capacitar al personal y analizar qué factores están impidiendo que los clientes otorguen mejores calificaciones. Esto permitirá aumentar el flujo de ventas, ya que el cliente es indispensable para el buen funcionamiento de las tiendas.

## Referencias

### Código implementdo
[Código implementado](https://github.com/JuanMorales765/aluraStore/blob/main/AluraStore/challenge1-data-science-latam-main/AluraStoreLatam.ipynb)
##### [Python para Data Science: primeros pasos](https://app.aluracursos.com/course/python-data-science-primeros-pasos)
##### [Python para Data Science: trabajar con funciones, estructuras de datos y excepciones](https://app.aluracursos.com/course/python-data-science-trabajar-funciones-estructuras-datos-excepciones)
##### [Principiante en Programación G8 - ONE](https://app.aluracursos.com/formacion-programacion-primeros-pasos-grupo8-one)
##### [Desarrollo Personal G8 - ONE](https://app.aluracursos.com/formacion-desarrollo-personal-grupo8-one)


> Informe creado por:
> Juan David Morales Fonnegra
> Medellín, Antioquia, Colombia



