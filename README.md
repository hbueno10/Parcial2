# Parcial2

Descripción
- Proyecto sencillo para gestionar un carrito de compra con productos.
- Implementa clases: `modelo.Producto`, `modelo.CarritoCompra`, `modelo.Main`, `modelo.TestRunner`.

Autor y versión
- Autor: Hugo Bueno Olmos
- Versión: 1.0

Funcionamiento del código
- Producto: encapsula nombre, categoría (enum), precio y unidades. Valida parámetros en constructor y setters.
- CarritoCompra: lista encapsulada; operaciones de añadir, eliminar, calcular total, listar y vaciar.
- Main: ejemplo de uso que muestra productos y total.
- TestRunner: suite de pruebas autoejecutables (sin JUnit) que valida comportamiento válido e inválido.

Generar JavaDoc
- Ejecuta desde la raíz del proyecto:
  ```
  javadoc -d doc modelo\*.java
  ```
  La documentación HTML quedará en la carpeta `doc`.

Compilar y ejecutar
1. Compilar:
   ```
   javac -d out modelo\*.java
   ```
2. Ejecutar ejemplo:
   ```
   java -cp out modelo.Main
   ```
3. Ejecutar tests (TestRunner):
   ```
   java -cp out modelo.TestRunner
   ```
