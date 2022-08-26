# bookmedik-pro
Sistema de Gestion de Citas Medicas PRO
"# bookmedicpro" 

Este software se diseno para un instituto de neurorehabilitacion, de igual manera, es un software con capacidades de adaptacion para cualquier tipo de consultorio clinico pequeno que solo requiera de registro de clientes, pacientes, enfermeros y gestion de turnos a nivel interno.

La metodologia de trabajo del software es sobre la base de datos MYSQL con implmentacion del Backend en PHP para poderse usar sin necesidad de conexion a internet mediante el localhost que permite el servidor apache tomcat

# Autor: henrygarcia


Instalacion de BookMedik Pro en XAMPP en Windows


# 1.- Copiar la carpeta del sistema a la direccion c:\xampp\htdocs\ de manera que el sistema quede c:\xampp\htdocs\bookmedik-pro

# 2.- Instalar la base de datos contenida en el archivo c:\xampp\htdocs\bookmedik-pro\schema.sql, 
   puede ser desde PHPMyAdmin o desde la terminal

# 2.1 Desde la terminal

  cd \xampp\mysql\bin
  mysql -u
  root
  source \xampp\htdocs\bookmedik-pro\schema.sql
  /* 
  tambien puedes copiar el contenido del archivo schema.sql y pegarlo en la terminal */

# 3.- Modificar el archivo de conexion a la base de datos en caso de ser necesario 
  c:\xampp\htdocs\bookmedik-pro\core\controller\Database.php

4.- Acceder al sistema desde el navedador usando la direccion 
  http://localhost/bookmedik-pro/


# - Datos de acceso -

  Usuario: admin

  Password: admin
