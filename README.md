# Challenge Backend Junior - Informe

## Objetivo

Este proyecto tiene como objetivo realizar un CRUD (Create, Read, Update, Delete) para entidades en una API .NET Core. Se busca también configurar y conectar la API con una base de datos SQL Server.

## Pasos realizados

### Clonación de repositorio:
• Se clonó el repositorio del Challenge-Jr_Backend.

### Configuración de la Base de Datos:
• Se configuró el connectionString para establecer la conexión con una base de datos local en SQL Server.

• Se realizaron las migraciones necesarias para crear las tablas correspondientes en la base de datos.

### Correción de errores en entidades:
• Se realizaron ajustes en las clases de las entidades (Coberturas, Pólizas, PolizasCoberturas) para asegurar que los atributos se manejen correctamente y admitan los valores nulos según sea necesario.

### Pruebas con Swagger:
• Se utilizó Swagger para realizar pruebas de las solicitudes HTTP y comprobar el correcto funcionamiento de los controladores.

• Se solucionaron problemas y errores detectados durante las pruebas.

### Validación y corrección:
• Se validó que todas las solicitudes HTTP devolvieran códigos 200 y funcionaran correctamente.

• Se realizó una revisión exhaustiva para corregir cualquier problema encontrado durante el proceso.


## Conclusiones: 
A pesar de algunos desafíos en la configuración inicial y correcciones en las entidades, se logró completar con éxito el objetivo principal del Challenge Backend Junior. La API está conectada y funciona correctamente, permitiendo realizar operaciones CRUD en todas las entidades, incluyendo la clase accesoria PolizasCoberturas que nos permitiría en un futuro manejar el maestro detalle de pólizas.
