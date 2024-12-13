# Examen 1ª Evaluación

---

Explica a continación cada apartado del examen

Con cada apartado realiza un commit diferente

![ex_diagrama.drawio.png](.idea/ex_diagrama.drawio.png)
- **Declaración del array**:
  ```java
    /**
  * Creado el tablero de damas.
  *
  * @version 1.0
  * @autor Daniel Figueroa Vidal
    */
  
  
  
  public class Damas {
    public static void main(String[] args) {
        String[][] tablero = {
            {null, "negras", null, "negras", null, "negras", null, "negras"},
            {"negras", null, "negras", null, "negras", null, "negras", null},
            {null, "negras", null, "negras", null, "negras", null, "negras"},
            {null, null, null, null, null, null, null, null},
            {null, null, null, null, null, null, null, null},
            {"blancas", null, "blancas", null, "blancas", null, "blancas", null},
            {null, "blancas", null, "blancas", null, "blancas", null, "blancas"},
            {"blancas", null, "blancas", null, "blancas", null, "blancas", null},
        };
    }
  }
  ```

- **Primera funcion**:
  ```java
  /**
   * Recorrer tablero.
   * Mostraremos por pantalla el tablero
   *
   * @param tablero[][].
   */

  ```
- **Segunda funcion**:
  ```java
  /**
   * Recorrer tablero para contar cuantas blancas y cuantas negras hay en el tablero.
   *
   * @param tablero[][].
   */

  ```
  
- **Tercera funcion**:
  ```java
  /**
   * Comprobar si las quien va ganando, o si van empates. Retornando un string con el que va ganando
   *
   * @param blancas, negras.
   * @return ganador
   */

  ```