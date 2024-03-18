# Antes de ejecutar: 

Como usted podra ver en el docuemnto [DBConnection.java](https://github.com/paulacastano/pdd-sakila/blob/main/DBConnection.java) en la linea
13 existe una variable llamada `dbPath` con el valor `"jdbc:sqlite:C:/Users/cardo/Documents/pdd-sakila/db/sqlite-sakila.db"` usted debe sustituir
`C:/Users/cardo/Documents` por la localizacion de la carpeta donde descargo el repositorio


# Instrucciones de ejecucion

1. Compile el codigo usando el comando

```bash
javac Main.java
```

2. Ejecute el codigo usando el comando

```bash
java -classpath ".;sqlite-jdbc-3.7.2.jar" Main
```
