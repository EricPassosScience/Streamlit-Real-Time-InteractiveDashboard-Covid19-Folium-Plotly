# Dashboard Interactivo para Monitoreo de Casos de Covid-19 en Tiempo Real con Streamlit, Plotly y Folium
Vamos a construir un tablero interactivo en tiempo real, utilizando Python y las bibliotecas Streamlit (para construir el tablero), Folium (para construir mapas) y Plotly (para gráficos interactivos). 

## Documentación 
- Folium -> https://python-visualization.github.io/folium/
- Streamlit -> https://docs.streamlit.io
- Plotly -> https://plotly.com/python-api-reference/

## Fuente de Datos

Los datos están disponibles públicamente en la Universidad Johns Hopkins, considerada uno de los repositorios de datos más consistentes sobre COVID-19 en todo el mundo.
Estos son datos en tiempo real, actualizados cada 24 horas. Por tanto, si actualizamos la gráfica cada 24 horas, los resultados serán diferentes.

Con base en estos datos, un grupo de empresas creó una API pública y gratuita para acceder a estos datos. 

Datos -> https://coronavirus.jhu.edu/map.html

Datos de coordenadas del país -> adjunto

API -> https://covid19api.com/

También se puede encontrar más información sobre la fuente de datos en este repositorio de GitHub -> https://github.com/CSSEGISandData/COVID-19

## Veamos cómo resultó el Tablero
![Tabela](https://user-images.githubusercontent.com/97414922/224514100-e57578f0-87b2-45e9-8aa0-77b9027863df.png)

### Mapa con la distribución de casos en todo el mundo:
![Mapa](https://user-images.githubusercontent.com/97414922/224514166-9ad7cb32-10fa-4f32-b60f-911c8047e56c.png)

### Comparación de casos totales entre los 10 países más afectados:
![Gráfica de Barras](https://user-images.githubusercontent.com/97414922/224514259-9639965b-5681-46b0-8cd0-fbc2b6e1e348.png)

### Gráfico 3D del total de casos, total de muertes y total recuperado de los 20 países más afectados:
![Gráfico 3D](https://user-images.githubusercontent.com/97414922/224514345-53e50779-39fe-4106-bd82-50e0efe28be6.png)
