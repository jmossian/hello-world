# Ejercicios de DIP, ISP, SRP
## Ejercicio 1 

**DIP:** se cumple o no y por que
no se cumple porque hay una dependencia entre las clases BaseDeDatos y AnlizadorDatos. Si cambiamos algun aspecto de BaseDeDatos podríamos afectar el funcionamiento de AnlizadorDatos.

**ISP:** se cumple o no y por que

**SRP:** se cumple o no y por que
DataBaseObject cumple con el patron porque su unica responsabilidad es la de representar el objeto, pero BaseDeDatos y AnlizadorDatos no ya que BaseDeDatos se encarga de varias funcionalidades y el AnlizadorDatos tiene que validar una condicion y conocer una lista de datos.

## Ejercicio 2

```cs
//Insertar el código corregido

```
## Ejercicio 3 

```cs
////Insertar el código corregido. El ejercicio 2 y 3 pueden ser resueltos de forma conjunta

```