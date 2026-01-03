# Arima_Series_De_Tiempo

Preparación de los datos: Se carga un archivo llamado MuertesAnuales.csv y se limpia eliminando la columna de años, convirtiéndola en un índice de tiempo que va desde 1960 hasta 2019.

Análisis de estacionariedad: Se grafican la media móvil y la desviación estándar. Como se ve que la línea roja (media) sube constantemente, se confirma que el proceso no es estacionario, lo cual se valida con la prueba adfuller que importaste antes.

Ajuste del modelo ARIMA: Se define el modelo para encontrar el patrón matemático detrás de esa curva ascendente de datos.

Predicción (Forecasting): Esta es la parte clave. El código genera valores predictivos para los años 2019 a 2023. En la última gráfica, se ve la línea azul (datos originales) y una pequeña línea naranja al final, que representa la predicción del modelo hacia el futuro.

<img width="822" height="786" alt="image" src="https://github.com/user-attachments/assets/e07e924c-8a0e-4266-ba05-d2fec6e98d64" />
