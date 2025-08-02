# Instrucciones del proyecto

1. Descarga y prepara los datos.  Explica el procedimiento.

2. Examina el equilibrio de clases. Entrena el modelo sin tener en cuenta el desequilibrio. Describe brevemente tus hallazgos.

3. Mejora la calidad del modelo. Asegúrate de utilizar al menos dos enfoques para corregir el desequilibrio de clases. Utiliza conjuntos de entrenamiento y validación para encontrar el mejor modelo y el mejor conjunto de parámetros. Entrena diferentes modelos en los conjuntos de entrenamiento y validación. Encuentra el mejor. Describe brevemente tus hallazgos.

4. Realiza la prueba final.

### Descripción de los datos

Puedes encontrar los datos en el archivo `datasets/Churn.csv` file. [Descarga el conjunto de datos](datasets/Churn.csv).

**Características**

- **RowNumber:** índice de cadena de datos
- **CustomerId:** identificador de cliente único
- **Surname:** apellido
- **CreditScore:** valor de crédito
- **Geography:** país de residencia
- **Gender:** sexo
- **Age:** edad
- **Tenure:** período durante el cual ha madurado el depósito a plazo fijo de un cliente (años)
- **Balance:** saldo de la cuenta
- **NumOfProducts:** número de productos bancarios utilizados por el cliente
- **HasCrCard:** el cliente tiene una tarjeta de crédito (1 - sí; 0 - no)
- **IsActiveMember:** actividad del cliente (1 - sí; 0 - no)
- **EstimatedSalary:** salario estimado

*Objetivo*

- **Exited:** El cliente se ha ido (1 - sí; 0 - no)