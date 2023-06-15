## OPTIMIZACIÓN DE UN PORTAFOLIO DE INVERSION
Este proyecto tiene como objetivo realizar una optimización de un portafolio de inversión que consta de 25 acciones de diferentes empresas. Utilizando técnicas de optimización y análisis de datos, buscamos encontrar la combinación óptima de acciones que maximice el rendimiento y minimice el riesgo. Dichas acciones son  'JCI','BMW','TYO','DIS','BBVA','AAPL','TSLA','NKE 'C','NU','NFLX','UBER','GM','SPOT','MCD','META', 'MMC','MSFT','GOOG','NVDA','AMZN','ADBE','F','T','GBOOY'], y estaran divididas por clases a lo largo del codigo en entretenimiento, transporte y Paqueteria, servicio de telecomunicaciones, moda e industria automotriz.

Descripción del codigo 

El proyecto se centra en la construcción de un modelo de optimización de cartera utilizando herramientas matemáticas para encontrar la asignación de activos más eficiente posible. El algoritmo tiene en cuenta el rendimiento histórico de los activos, así como su nivel de riesgo, y proporciona una distribución de activos óptima que maximiza la rentabilidad esperada mientras se minimiza la volatilidad.

Intrucciones de instalación

Para la realización de el codigo es necesario obtener las librerias 
import numpy as np
import pandas as pd
import yfinance as yf
import riskfolio as rp
import matplotlib.pyplot as plt
import warnings

Características

Utiliza datos históricos de los activos para calcular las tasas de rendimiento y riesgo.
Proporciona una interfaz gráfica intuitiva para ingresar los datos y visualizar los resultados.
Genera informes detallados sobre la distribución óptima de la cartera y el rendimiento esperado.


Estructura de archivos y directorio 

data: Los datos obtenidos para el proyecto se adquirieron con la herramienta Yfinance en un periodo del 01/01/2019 al 30/12/2022

Proyecto BIVA.py : El archivo principal del proyecto que realiza la optimización del portafolio.

Dependencias

Python 3.10

Contacto

Si tienes alguna pregunta o sugerencia sobre este proyecto, puedes contactarme a través de mi correo vivianabeltran373@gmail.com.
