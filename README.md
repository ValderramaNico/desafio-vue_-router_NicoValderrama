# Desafío Vue Router

1. Modificar el código del menú de navegación en sus ítems e integrar `<router-link>`.

![alt text](<src/assets/utils/code 1.png>)

2. Generar las rutas que se requieran según los ítems ya establecidos en el menú de navegación. Estas rutas van a cargar los componentes a través de carga controlada o lazy load.

*(Ejemplo de 'products')*
![alt text](<src/assets/utils/code 2.png>)

3. Generar las vistas en su respectivo directorio para que las rutas definidas tengan funcionalidad y muestren información.

![alt text](<src/assets/utils/Captura de pantalla 2024-07-19 213319.png>)

4. En la vista Productos y Contacto deberá haber un enlace de redirección al inicio del sitio.

*Se creó un botón que devuelve al inicio*
![alt text](<src/assets/utils/Captura de pantalla 2024-07-19 214514.png>)

![alt text](<src/assets/utils/code 3.png>)

5. En la vista de Productos.vue se recibirán props enviados desde la definición de la ruta logrando la siguiente visualización:

*Props en raiz (index.js)*
![alt text](<src/assets/utils/code 4.png>)

*Props recibidas en 'ProductsView'*
![alt text](<src/assets/utils/code 4.1.png>)

`Por Nicolás Valderrama`