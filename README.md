# Calculadora Basica ANTLR
- Catedratico: Ing. Roman Pineda</br>
- Alumno: Oscar Luis Sanchez</br>

## Contenido
- Carpeta con la asignacion.

## Para Ejecutar (Linux)
Se debe ubicar en la carpeta raiz del proyecto y posteriormente hacer uso de los siguientes comandos:
```bash
export CLASSPATH=".:/usr/local/lib/antlr-4.9.3-complete.jar:$CLASSPATH"
```

```bash
javac Calc.java LabeledExpr*.java
```

```bash
java Calc expresionesTest.expr
```

```bash
grun LabeledExpr prog -gui expresionesTest.expr
```
