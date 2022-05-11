# CALCULADORA BASICA CON MENU 

Una calculadora basica se puede con condiciones . Se desea realizar alguna de las operaciones basica con dos numeros `x,y` . Ademas se desea calcular  la potencia  y el logaritmo. Se deben de considerar los casos donde `y=0` donde la division `x/y` . NO se puede calcular el `log(x)` . Se desea generar un menu donde el usuario pueda seleccionar la operacion a realizar . Una manera de hacerlo es la siguiente :

1. se reciben los dos numeros `x,y` para realizar la operacion. 
2. se recibe la operacion a realizar mediante la variable `opcion` la que selecciona en el menu que operacion ejecuta el algoritmo.
3. se indica la variable logica `bandera = False` , si la division o el logaritmo no se pueden calcular , se hace `bandera = False` .
4. Mediante condiciones se realiza la operacion deseada .
* En el caso de la division ,  si `y = 0`, No se puede realizar la division. Se muestra un mensaje y se hace `bandera=True`.
* En el caso del  logaritmo, si `x <= 0` , No se puede calcular el logaritmo , se muestra un mensaje y se hace `bandera=True`.
5. Se muestra el resultado en el caso en que `bandera = False`. 
*Tomado de: Python con aplicaciones a las matematicas, ingenieria y finanzas. Cervantes 0, Baez 0. *