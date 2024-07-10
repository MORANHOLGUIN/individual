# individual
<img width="582" alt="image" src="https://github.com/MORANHOLGUIN/individual/assets/168208095/a4d46be6-2ab2-41d8-8dd6-e722eb70eb16">
<img width="579" alt="image" src="https://github.com/MORANHOLGUIN/individual/assets/168208095/e0701019-f0c7-4276-bd0d-b8673cacb0d4">
<img width="575" alt="image" src="https://github.com/MORANHOLGUIN/individual/assets/168208095/548de3d5-04cb-4a04-912b-71959500ba7f">

Constructor InterfazGrafica:

Inicia la conexión a la base de datos y crea la interfaz gráfica.

Método connectDB:

Establece la conexión a la base de datos PostgreSQL con JDBC.

Método createGUI:

Configura la ventana principal, añade un combo box para seleccionar el año y una tabla para mostrar datos.

Método populateComboBox:

Llena el combo box con los años disponibles en la base de datos.

Método updateTableInBackground:

Ejecuta una consulta SQL en segundo plano para obtener y mostrar los datos de los constructores del año seleccionado.

Método main:

Inicia la aplicación y asegura que la creación de la interfaz gráfica se realice en el hilo de eventos de Swing.








