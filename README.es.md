<!-- hide -->
# Linear Regression Project Tutorial
<!-- endhide -->

- En este proyecto, construiremos un modelo de regresión lineal para predecir la prima de seguro para un individuo en función de diferentes factores.
- Comienza con tu análisis exploratorio de datos y transformación de datos si es necesario.
- Crea tu modelo de referencia, mide tus resultados y optimiza tu modelo.
- Finalmente, cree una canalización para su modelo final y colóquela en su archivo app.py.

## 🌱  Cómo iniciar este proyecto

Esta vez no se hará Fork, tómate un tiempo para leer estas instrucciones:

1. Crear un nuevo repositorio basado en el [proyecto de Machine Learing](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Gitpod usando la [extensión del botón de Gitpod](https://www.gitpod.io/docs/browser-extension/).
3. Una vez que Gitpod VSCode haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de resolver los ejercicios, asegúrate de confirmar tus cambios, hazle "push" a el fork de tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.

## 📝 Instructions

**Predecir el costo del seguro médico de una persona**

Este conjunto de datos tiene 7 columnas. Usaremos la columna 'charges' (cargos) como la variable objetivo porque queremos crear un modelo que prediga el costo del seguro en función de diferentes factores.

Columnas:

- age: edad del beneficiario principal.

- sex: contratista de seguros género, hombre o mujer.

- bmi: índice de masa corporal.

- children: número de niños cubiertos por el seguro de salud / Número de dependientes.

- smoker: fumador.

- region: el área residencial del beneficiario en los EE. UU., noreste, sureste, suroeste, noroeste.

- charges: costos médicos individuales facturados por el seguro de salud.

**Paso 1:**

El conjunto de datos se puede encontrar en esta carpeta de proyecto como archivo 'medical_insurance_cost.csv'. Te invitamos a cargarlo directamente desde el enlace (https://raw.githubusercontent.com/4GeeksAcademy/linear-regression-project-tutorial/main/medical_insurance_cost.csv), o para descargarlo y agregarlo a tu carpeta data/raw. En ese caso, no olvides agregar la carpeta de datos al archivo .gitignore.

> Si tiene dificultades con este proyecto, puede consultar la guía de solución: https://github.com/4GeeksAcademy/linear-regression-project-tutorial/blob/main/solution_guide.ipynb

¡Es hora de trabajar en ello!

**Paso 2:**

Utiliza el notebook explore.ipynb para buscar patrones e información valiosa sobre las relaciones entre las funciones o entre la función y el objetivo.

> Pista: no hay valores nulos

No olvides escribir tus observaciones.

**Paso 3:**

Ahora que tienes un mejor conocimiento de los datos, en tu notebook exploratorio crea un primer modelo de regresión lineal con tus datos, para poder predecir la prima del seguro.

Elije una métrica para medir tus resultados.

**Paso 4:**

Hypertune tu modelo para mejorar tus resultados.

Utiliza app.py para crear tu pipeline final de modelado de Machine Learning.

Guarda tu modelo final en la carpeta 'models'.

En tu archivo README escribe un breve resumen.
