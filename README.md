# Aplicación Móvil Para el Agua Potable Rural
=============================================================================== 

# APR-01

 - Descripción:
 
Este App se creó para lograr que una Aplicación móvil
nos permita ingresar datos en dicha aplicación y que los almacene en
una Base de Datos externa SQL.

# APR-02

 - Descripción:
 
En esta App se probo que la aplicación logre guardar los datos en su Base de Datos SQLite 
y una vez guardado los datos logremos exportarlo a la BD externa y la vez poder revisar en
su panel de administración del phpMyAdmin 


# APR_BD_Externa SQLitebrowser-03

 - Descripción:

Acá se probo un software que permite crear base de datos para SQLite, en la cual se 
creo una base dato para verificar funcionalidad con el dispositivo móvil.

 - Link Software para BD-SQLite [www.sqlitebrowser.org](https://sqlitebrowser.org/)

# APR-Login-con-DB-externa-04
  Sprint 04

 - En esta App se creo un login para un operador.
 - Se logro crear una Base de Dato Externa, en la cual se crearon unas tablas con algunos 
   campos para realizar algunas pruebas.
 - Como conclusión, podemos validar un operador con el login y consultar datos en la App,
   sobre si el medidor corresponde a la casa que se esta tomando la lectura.
   
# APR-Login-Registro-05
  Sprint 05
  
  - Acá tenemos una APP que permite el Regsitro de Usuario valido 
  - Se integra el modulo de Registro Lectura.
  - Se integra el modulo de Verificar Lectura.
  - Como conclusión se unifican todos los modulos anteriores para optener una sola App.
  
 # APR-Login-BD-Hosting-06
   Sprint 06
   - App con su login valido
   - Registrando los datos de lectura en la App y enviandolos a una base de datos ubicada en un hosting
   (https://www.000webhost.com/cpanel-login?from=panel)
   - Como resultado final tenemos un login valido, una toma de lectura y su envio de datos desde la App a una BD externa.
   
 # APR_Importación_Exportación-07
   Sprint 06
   - App con login valido
   - App Registar lecturas
   - La App Importa datos hacia la base datos SQLite de la Appp
   - La App exporta los datos registrados en la App hacia la Base de Datos externa.
   - Link del hosting : https://apragua.000webhostapp.com/login.html
 
 # APR_validación_de_datos_exportados-08
   Sprint 07
   - En esta App se configuro que la aplicación solo perimita subir una vez las lecturas a la BD, esto correspondera cuando el    operador termine de registrar todas las lecturas de los medidores.
   - De esta forma evitar subir medidores de usuario sin lecturas
   
 # APR_Importación_Exportación_BBDD-09
   Sprint 07
   - Login válidado
   - Verificar medidor que corresponda a la casa correcta
   - Registrar Lecturas
   - Verificar lectura ingresada
   - Podemo subir solamente los mediores que tienen registro de lecturas en la Apps
   _ Ignora los medidores que no tienen registrado una lectura
   - Importa la base de datos de servidor.
   
 # APR_Importacio_Exportacio_BD_BotonVolver-10
   Sprint 08 
   - En esta versión es de solo tiene una variante, que es un botón en las Activity
   - Motivo, realizar pruebas con android studio y el framework de Espresso.
   _ Se crea un realase para estsa versión.
   - Link Release Apk : https://github.com/haka2087/App_APR/releases/tag/V1.5-beta.6
   
   
   
   

