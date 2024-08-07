Dentro de este repositorio se encuentran ejercicio comprobar sus conocimientos de Git.
Deben realizar los ejercicios en orden

# Ejercicios

Primero cree una rama con su nombre, luego proceda a realizar los ejercicios

## Ejercicio 1. Realizar cambio

Cambiar el contenido del archivo `ejercicio-1.md` y poner su nombre.

Luego realizar un commit con los cambios y subirlo al repositorio.

## Ejercicio 2. Resolucion de conflictos

Realizar un merge de los cambios que se encuentran en la rama `ejercicio2` a su rama.
Resolver los conflictos de manera que el nombre que quede sea el suyo.
Luego subir los cambios al repositorio.

## Ejercicio 3. Revertir un cambio

El ejercicio 3 consiste en realizar una reversion de los cambios realizados en otro commit
(investigar `git revert`), para poder recuperar el estado original del repositorio con el
commit `initial commit`.

_NOTA_:
En este paso se deberia de eliminar el archivo de `Instrucciones.md`.
Es normal, pero REVISE EL HISTORIAL DE COMMITS (`git log` y `git reflog`).

## Ejercicio 4. Revertir el historial de commits

Vea que ocurre con el historial de commits despues de `git revert`.

Investigue si existe una forma de **resetear** el historial de commits hasta el commit con el
mensaje `initial commit`.

## Ejercicio 5. Rebase

Investigue el comando `rebase`.
Primero realice los cambios pedidos en el ejercicio 1 y haga rebase de los cambios de la rama
`ejercicio2`.
Luego resuelva los conflictos de haberlos.

Al final haga un push con sus cambios (forzados de ser necesario).

## Ejercicio 6. Pull request

Cree un nuevo commit con un nuevo archivo (ponga lo que quiera adentro).
El mensaje del commit debe decir "ejercicios completados".
Realice un pull request en Github con sus cambios
