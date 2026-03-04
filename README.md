# Análisis de Evasión de Clientes – TelecomX LATAM

## Descripción del proyecto
Este proyecto tiene como objetivo analizar la evasión de clientes (churn) en TelecomX LATAM mediante técnicas de análisis exploratorio de datos (EDA).

El propósito es identificar patrones y variables asociadas a la cancelación del servicio para generar insights estratégicos que ayuden a mejorar la retención de clientes.

## Objetivos

* Analizar la distribución general del churn.
* Identificar las variables categóricas vinculadas con una mayor evasión.
* Evaluar de que manera las variables numéricas afectan la cancelación.
* Extraer insights para orientar decisiones estratégicas.

## Dataset
El dataset contiene información de clientes, incluyendo:

* Datos demográficos (género, senior citizen, partner, dependents)
* Tipo de contrato
* Método de pago
* Servicios contratados
* Cargo mensual
* Cargo total acumulado
* Antigüedad (tenure)
* Variable objetivo: churn (0 = Permanece, 1 = Abandona)

## Limpieza y preparación de datos

Se realizaron los siguientes pasos:
* Conversión de variables categóricas numéricas de binarias a formato numérico.
* Tratamiento de valores nulos:
    - 224 registros vacíos de churn se imputaron como 0 porque representaban el 3% del total.
    - 11 valores nulos en charges_total fueron imputados como 0 ya que eran los clientes que no tenían tenure y por eso figuraban como nulos.
* Creación de la variable derivada cuentas_diarias.
* Estandarización del nombre de las columnas.
* Verificación de la consistencia y los tipos de datos.

## Tecnologías utilizadas
* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

## 
