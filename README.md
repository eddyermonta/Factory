# Fabrica de Conexiones - Ejemplo de Patrón Factory

¡Bienvenido al proyecto de Fabrica de Conexiones!

## Descripción

Este proyecto es un ejemplo de implementación del patrón de diseño Factory en Java. La fábrica de conexiones permite obtener instancias de diferentes tipos de conexiones de bases de datos de manera uniforme y centralizada.

## Estructura del Proyecto

El proyecto está organizado en los siguientes paquetes y clases:

- **Paquete `com.mitocode`**:
  - `App.java`: Clase principal que contiene el método `main` para ejecutar la aplicación.
  - `ConexionFabrica.java`: Clase que implementa la lógica de la fábrica de conexiones.
- **Paquete `com.mitocode.inter`**:
  - `IConexion.java`: Interfaz que define los métodos `conectar` y `desconectar` para las conexiones.
- **Paquete `com.mitocode.inter.impl`**:
  - `ConexionOracle.java`: Clase que implementa la interfaz `IConexion` para una conexión a Oracle.

## Uso

1. Ejecuta la clase `App.java`.
2. La fábrica de conexiones creará instancias de conexiones a Oracle, MySQL y H2.
3. Cada conexión se conectará y desconectará, mostrando mensajes en la consola.

## Contribuciones

Este ejemplo fue tomado del canal de YouTube [MitoCode](https://www.youtube.com/user/codigofacilito) como parte de su curso de Java.

