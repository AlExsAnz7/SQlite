# DB
>Creación de la base de datos con una tabla correspondiente una vez se haya configurado todo desde las variables de entorno y el CMD del sistema. 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/DB.PNG)


# UPDATE
>Comando update para la actualización de un registro.
Creación de la tabla a modificar.

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/update.PNG)

>Estructura de la actualización del dato efectiva. 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/verificacion_update1.PNG)

>verificación: 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/verificacion_update2.PNG)


# SCHEMA
>Verificación de la estructura de la base de datos. 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/schema.PNG)


# DATE - DATETIME
>Funciones para fecha y hora. 
fecha(actual):

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/date.PNG)

>fecha pasada: 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/past_date.PNG)

>hora(actual):

 ![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/datetime.PNG)

>horas pasadas: 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/datetime_past.PNG)


# PRIMARY KEY
>Asignación de llave primaria. 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/primary_key.PNG)

>De esta forma asignamos al valor “userid” como llave primaria y de valor int. 


# NOT NULL
>Asignación de un valor de tipo null. 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/not_null.PNG)

>Esta instrucción no deja que el campo se encuentre vacío una vez insertamos los datos, sino que siempre haya un valor albergando. 

>llamando a la tabla: 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/calling_table.PNG)

>Claramente se pueden observar los datos registrados, no obstante, si se registra un dato sin información, esto es lo que retornará: 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/not_nulltest1.PNG)


# UNIQUE 
>Asignación de un valor tipo unique. 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/unique.PNG)

>De esta forma asignamos a la llave primaria “userid” cómo única. 


# DEFAULT
>Asignación de un valor tipo default. 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/default.PNG)

>Asignamos valores de forma predeterminada para que al momento de hacer un insert en la tabla no sea necesario ingresar los datos que anteriormente habíamos asignado.


# CHECK
>Asignación de un valor tipo check. 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/check.PNG)

>Al ingresar un dato menor al requerido aparecerá este error. 

![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/verification_check1.PNG)

>Esto se debe a que la cantidad de caracteres que ingresamos es menor al que se requiere, que en este caso es 9. 

>Sin embargo…
![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/verification_check2.PNG)

>Al ingresar un valor mayor o igual al previamente requerido, que en este caso es 13, satisfactoriamente la restricción check guardará el registro en la tabla. 

# ALTER TABLE
>Esta restriccion funciona para cambiar la estructura de una tabla existente. 

>En este caso, renombramos la tabla “users” a “users_” con la instrucción rename to.
![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/alter_table.PNG)

>Como se puede ver, renombramos la tabla. 

# DROP - DELETE 
>Drop: 
>Esta instrucción funciona para eliminar una tabla en la base de datos existente. 

>Eliminaremos la tabla def. 
![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/drop.PNG)

>Se eliminó correctamente. 

>Delete: 
>Esta instrucción funciona para eliminar una fila de una tabla existente. 

>Eliminaremos la fila userid de la tabla users_.
![Alt text](../../../../../../../C:/Users/W/OneDrive/Escritorio/DB%20-%20SQLITE/img/delete.PNG)

>Como se puede ver, eliminamos el userid que se encontraba registrado satisfactoriamente. 

# BACKUP - RESTORE
>backup: 
>No pude encontrar un comando que se ejecute desde el cmd, ya que todos los disponibles están para interfaces gráficas. 

>restore: 
>No pude encontrar un comando que se ejecute desde el cmd, ya que todos los disponibles están para interfaces gráficas. 

