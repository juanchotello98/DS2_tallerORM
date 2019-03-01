# DS2_tallerORM
Guía para realizar las pruebas con Postman
Nota: se utiliza Postam para escritorio para Windows

1. Ejecutar Postman
![Screenshot](https://github.com/juanchotello98/DS2_tallerORM/blob/master/images/Captura-1.JPG)

2. Seleccionar el tipo de request
Nota: el tipo de request será  GET
![Screenshot](https://github.com/juanchotello98/DS2_tallerORM/blob/master/images/Captura-2.JPG)

3. Introducir la url a la que haremos la request
Nota: la url es https://boiling-lake-96659.herokuapp.com/contacts
![Screenshot](https://github.com/juanchotello98/DS2_tallerORM/blob/master/images/Captura-3.JPG)

4. Enviar la consulta dando clic en el boton "Send" 
Nota: veremos como resultado lo siguiente en la previsualización de Postman
Nota2: si colocamos la misma dirección en el navegador obtendremos el mismo resultao pero visualizado de manera plano, no en formato JSON como nos lo brinda Postaman
![Screenshot](https://github.com/juanchotello98/DS2_tallerORM/blob/master/images/Captura-4.JPG)

5. Para realizar una nueva request repetimos los pasos 2 y 3.
Nota: el tipo de request será POST
Nota2: para esta consulta POST debemos ubicarnos en la opción "Body" y seleccionar la opción "x-www-form-urlencoded"
Nota:3: debemos registrar en formato "clave : valor" los campos de un nuevo registro. 
![Screenshot](https://github.com/juanchotello98/DS2_tallerORM/blob/master/images/Captura-5.JPG)

6. Para realizar una nueva request repetimos los pasos 2 y 3.
Nota: el tipo de request será PUT
Nota2: en la url esta vez debemos agregar (/id) del registro que queremos modificar:
https://boiling-lake-96659.herokuapp.com/contacts/4
Nota3: para esta consulta PUT debemos ubicarnos en la opción "Body" y seleccionar la opción "x-www-form-urlencoded"
Nota:4: debemos registrar en formato "clave : valor" los campos de un nuevo registro excpeto el campo "id"
![Screenshot](https://github.com/juanchotello98/DS2_tallerORM/blob/master/images/Captura-6.JPG)

6. Para realizar una nueva request repetimos los pasos 2 y 3.
Nota: el tipo de request será DELETE
Nota2: en la url esta vez debemos agregar (/id) del registro que queremos eliminar:
https://boiling-lake-96659.herokuapp.com/contacts/4
![Screenshot](https://github.com/juanchotello98/DS2_tallerORM/blob/master/images/Captura-7.JPG)

