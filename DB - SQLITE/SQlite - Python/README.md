# DB
>Creación de la base de datos con una tabla correspondiente una vez se haya configurado todo desde las variables de entorno y el CMD del sistema. 

![DB](https://user-images.githubusercontent.com/107562949/201203292-f5cdebf0-34ea-4271-9030-bf473ffed801.PNG)


# UPDATE
>Comando update para la actualización de un registro.
Creación de la tabla a modificar.

![update](https://user-images.githubusercontent.com/107562949/201203672-156ad544-9966-4efd-b94a-c08e6b542b89.PNG)


>Estructura de la actualización del dato efectiva. 

![verificacion_update1](https://user-images.githubusercontent.com/107562949/201203953-0474955b-bd6d-4586-9e9e-dd8017c42e00.PNG)

>verificación: 

![verificacion_update2](https://user-images.githubusercontent.com/107562949/201204250-629f4f1c-5c36-44d2-b349-50c164a1f97c.PNG)

# SCHEMA
>Verificación de la estructura de la base de datos. 

![schema](https://user-images.githubusercontent.com/107562949/201204308-af4fe2a9-665f-47a4-b971-a436727670e2.PNG)


# DATE - DATETIME
>Funciones para fecha y hora. 
fecha(actual):

![date](https://user-images.githubusercontent.com/107562949/201204676-c4aad935-f430-4b8e-bdef-5e3116edb9c6.PNG)


>fecha pasada: 

![past_date](https://user-images.githubusercontent.com/107562949/201204706-ded10807-93e2-4ca6-bf35-03660426536b.PNG)


>hora(actual):

![datetime](https://user-images.githubusercontent.com/107562949/201204732-ec2372a5-aed5-4037-8346-81d715f21118.PNG)


>horas pasadas: 

![datetime_past](https://user-images.githubusercontent.com/107562949/201204769-20ecab0c-2320-4278-85ce-266b559d5da3.PNG) 


# PRIMARY KEY
>Asignación de llave primaria. 

![primary_key](https://user-images.githubusercontent.com/107562949/201209419-a76cd6fb-176d-483a-aa89-c75113a36615.PNG)


>De esta forma asignamos al valor “userid” como llave primaria y de valor int. 


# NOT NULL
>Asignación de un valor de tipo null. 

![not_null](https://user-images.githubusercontent.com/107562949/201209441-3541690b-bac1-45d6-b220-899c8803a45e.PNG)


>Esta instrucción no deja que el campo se encuentre vacío una vez insertamos los datos, sino que siempre haya un valor albergando. 

>llamando a la tabla: 

![calling_table](https://user-images.githubusercontent.com/107562949/201209470-cae2efd1-b440-4b52-b836-ac44d73abecc.PNG)


>Claramente se pueden observar los datos registrados, no obstante, si se registra un dato sin información, esto es lo que retornará: 

![not_nulltest1](https://user-images.githubusercontent.com/107562949/201209527-6bfcb413-6d2a-4185-9f9e-6426146bdc1b.PNG)

# UNIQUE 
>Asignación de un valor tipo unique. 

![unique](https://user-images.githubusercontent.com/107562949/201209564-46ba914f-b7dc-4ad7-8ddd-7656bf5e650f.PNG)


>De esta forma asignamos a la llave primaria “userid” cómo única. 


# DEFAULT
>Asignación de un valor tipo default. 

![default](https://user-images.githubusercontent.com/107562949/201209589-c71297d2-9fb5-4dee-93b0-0c96dac8a315.PNG)


>Asignamos valores de forma predeterminada para que al momento de hacer un insert en la tabla no sea necesario ingresar los datos que anteriormente habíamos asignado.


# CHECK
>Asignación de un valor tipo check. 

![check](https://user-images.githubusercontent.com/107562949/201209616-7bd2a9a1-af48-44c6-a3ab-73385f5df663.PNG)


>Al ingresar un dato menor al requerido aparecerá este error. 

![verification_check1](https://user-images.githubusercontent.com/107562949/201209638-2e87302d-8516-47f7-a9d2-6a4f44b667aa.PNG)


>Esto se debe a que la cantidad de caracteres que ingresamos es menor al que se requiere, que en este caso es 9. 

>Sin embargo…
![verification_check2](https://user-images.githubusercontent.com/107562949/201209653-01019a30-32ff-4ad7-907b-5da014d65387.PNG)


>Al ingresar un valor mayor o igual al previamente requerido, que en este caso es 13, satisfactoriamente la restricción check guardará el registro en la tabla. 

# ALTER TABLE
>Esta restriccion funciona para cambiar la estructura de una tabla existente. 

>En este caso, renombramos la tabla “users” a “users_” con la instrucción rename to.

![alter_table](https://user-images.githubusercontent.com/107562949/201209706-11ffa666-1069-4bf3-bb12-0e7751929f7a.PNG)

>Como se puede ver, renombramos la tabla. 

# DROP - DELETE 
>Drop: 
>Esta instrucción funciona para eliminar una tabla en la base de datos existente. 

>Eliminaremos la tabla def. 
![drop](https://user-images.githubusercontent.com/107562949/201209749-b7045970-6a53-4661-b354-5cd369c14628.PNG)


>Se eliminó correctamente. 

>Delete: 
>Esta instrucción funciona para eliminar una fila de una tabla existente. 

>Eliminaremos la fila userid de la tabla users_.
![delete](https://user-images.githubusercontent.com/107562949/201209785-0e3d34c2-9964-4da8-b774-60e0a3781a2f.PNG)


>Como se puede ver, eliminamos el userid que se encontraba registrado satisfactoriamente. 

# BACKUP - RESTORE
>backup: 
>No pude encontrar un comando que se ejecute desde el cmd, ya que todos los disponibles están para interfaces gráficas. 

>restore: 
>No pude encontrar un comando que se ejecute desde el cmd, ya que todos los disponibles están para interfaces gráficas. 

