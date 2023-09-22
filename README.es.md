<!-- hide -->
# Regresión lineal - Guía paso a paso
<!-- endhide -->

- Comprender un dataset nuevo.
- Procesarlo aplicando un análisis exploratorio (EDA).
- Modelar los datos utilizando la regresión logística.
- Analizar los resultados y optimizar el modelo si fuera posible.

## 🌱  Cómo iniciar este proyecto

Sigue las siguientes instrucciones:

1. Crea un nuevo repositorio basado en el [proyecto de Machine Learing](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Codespace usando la [extensión del botón de Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Una vez que el VSCode del Codespace haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de resolver el caso práctico, asegúrate de confirmar tus cambios, haz push a tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.

## 📝 Instrucciones

### Predecir el coste del seguro médico de una persona

La importante compañía de seguros 4Geeks Insurance S.L. quiere calcular, en función de datos fisológicos de sus clientes cuál va a ser la prima (coste) que debe asumir cada uno de ellos. Para ello, ha reunido a un equipo completo de médicos y en función de datos de otras compañías y un estudio particular han logrado reunir un conjunto de datos para entrenar un modelo predictivo.

#### Paso 1: Carga del conjunto de datos

El conjunto de datos se puede encontrar en esta carpeta de proyecto bajo el nombre `medical_insurance_cost.csv`. Puedes cargarlo en el código directamente desde el enlace (`https://raw.githubusercontent.com/4GeeksAcademy/linear-regression-project-tutorial/main/medical_insurance_cost.csv`) o descargarlo y añadirlo a mano en tu repositorio. En este conjunto de datos encontrarás las siguientes variables:

1. `age`. Edad del beneficiario principal (numérico)
2. `sex`. Género del beneficiario principal (categórico)
3. `bmi`. Indice de masa corporal (numérico)
4. `children`. Número de niños/dependientes cubiertos por el seguro de salud (numérico)
5. `smoker`. ¿Es fumador? (categórico)
6. `region`. Área residencial del beneficiario en USA: noreste, sureste, suroeste, noroeste (categórico)
7. `charges`. Prima del seguro médico (numerico)

#### Paso 2: Realiza un EDA completo

Este segundo paso es vital para asegurar que nos quedamos con las variables estrictamente necesarias y eliminamos las que no son relevantes o no aportan información. Utiliza el Notebook de ejemplo que trabajamos y adáptalo a este caso de uso.

Asegúrate de dividir convenientemente el conjunto de datos en `train` y `test` como hemos visto en lecciones anteriores.

#### Paso 3: Construye un modelo de regresión lineal

No es necesario que optimices los hiperparámetros. Comienza utilizando una definición por defecto y mejórala en el paso siguiente.

#### Paso 4: Optimiza el modelo anterior

Después de entrenar el modelo, si los resultados no son satisfactorios, optimízalo si fuera posible.

> NOTA: Solución: https://github.com/4GeeksAcademy/linear-regression-project-tutorial/blob/main/solution.ipynb