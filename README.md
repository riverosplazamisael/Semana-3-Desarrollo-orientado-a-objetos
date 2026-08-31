# SpeedFast

Proyecto desarrollado en Java para simular un sistema de entregas de pedidos con distintos tipos de servicio: comida, encomienda y express.

## Descripción

SpeedFast es una práctica de programación orientada a objetos que modela pedidos y operaciones relacionadas con la entrega. Cada pedido tiene información como el identificador, la dirección de entrega, el tipo de pedido y la distancia estimada. Además, se simulan acciones como asignar repartidor, calcular tiempo de entrega, despachar, cancelar y consultar historial.

## Funcionalidades

- Registro de pedidos por tipo.
- Asignación de repartidores.
- Cálculo del tiempo estimado de entrega.
- Despacho y cancelación del pedido.
- Visualización de resumen y historial de operaciones.
- Uso de abstracción, herencia e interfaces en Java.

## Estructura del proyecto

- `src/app/Main.java`: punto de entrada de la aplicación.
- `src/com/SpeedFast/model`: clases del dominio (`Pedido`, `PedidoComida`, `PedidoEncomienda`, `PedidoExpress`).
- `src/interfaces`: interfaces (`Despachable`, `Cancelable`, `Rastreable`).

## Requisitos

- Java JDK 17 o superior.
- IDE compatible con Java (IntelliJ IDEA, Eclipse o VS Code con extensión de Java).

## Cómo ejecutar

Desde la terminal en Windows PowerShell:

```powershell
cd ".\Respartos SpeedFast"
javac -d .\out (Get-ChildItem -Recurse -Filter *.java | ForEach-Object { $_.FullName })
java -cp .\out app.Main
```

También puedes ejecutar la clase `Main` directamente desde tu IDE.

## Ejemplo de salida

La aplicación imprime un flujo de ejemplo con pedidos de comida, encomienda y express, mostrando:

- asignación del repartidor,
- resumen del pedido,
- tiempo estimado de entrega,
- despacho,
- historial,
- cancelación.

## Autor

Proyecto académico de Programación Orientada a Objetos.
