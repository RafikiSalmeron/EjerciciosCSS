# Orden de peso de selectores
```!important```  
Es el que más peso tiene. Si lo añadimos, indicamos que esto tiene priordiad sobre el resto de selectores.

```#titulo```  
El selector con más peso, es el más reestrictivo, que en este caso es el id.

```.container href```   
Tiene un pseudoelemento después de la clase, por lo tanto pesa más que el selector de clase.

```.container```  
Selecciona clases y no elementos, por lo tanto tiene más peso que los selectores de elementos.

```h1```  
Selecciona al elemento "h1", por lo tanto es más pesado que el selector * que selecciona a todos los elementos.

``` * ``` 
