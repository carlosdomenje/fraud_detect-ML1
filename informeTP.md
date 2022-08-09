#  TP1 - Análisis de Plataforma de Ventas Online

## Aprendizaje de máquinas I

### Domenje, Carlos R.


**Una plataforma de ventas online nos contrata para que realicemos un modelo que nos permita detectar un posible fraude dada cierta operación para ello contamos con un dataset**

https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset

**Utilizando los modelos de clasificación vistos hasta el momento generar un notebook que permita de ser posible resolver el problema que nos está planteando el cliente.**

## Descripción de las columnas.

A continuación se describen brevemente las columnas que intervienen en el dataset. 

- **step:** representa una unidad de tiempo donde 1 step equivale a 1 hora
- **type:** tipo de transacción en línea
- **amount:** el importe de la transacción
- **nameOrig:** cliente que inicia la transacción
- **oldbalanceOrg:** saldo antes de la transacción
- **newbalanceOrig:** saldo después de la transacción
- **nameDest:** destinatario de la transacción
- **oldbalanceDest:** saldo inicial del destinatario antes de la transacción
- **newbalanceDest:** el nuevo saldo del destinatario después de la transacción
- **isFraud:** transacción fraudulenta

Para este trabajo se tomará la columna **isFraud** como nuestra variable a predecir. Es decir, ante un nuevo dato de entrada queremos clasificar si la transacción que se esta realizando es fraudulenta o no. 

## Análisis de datos

