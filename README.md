<h1 align="center">
  <marquee behavior="alternate" scrollamount="4" width="80%">
    <span style="color: #3B82F6;">Guía APE 4: Integración de Clases y Objetos</span>
  </marquee>
</h1>

<p align="center">
  <b>Algoritmos y Lógica de Programación</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Universidad-T%C3%A9cnica%20de%20Ambato-red?style=for-the-badge" alt="UTA">
  <img src="https://img.shields.io/badge/Carrera-Ingenier%C3%ADa%20en%20Software-blue?style=for-the-badge" alt="Software">
  <img src="https://img.shields.io/badge/Lenguaje-Java-orange?style=for-the-badge" alt="Java">
  <img src="https://img.shields.io/badge/Modalidad-Individual-green?style=for-the-badge" alt="Individual">
</p>

---

## Información General

* **Universidad:** Universidad Técnica de Ambato[span_0](start_span)[span_0](end_span)
* **Asignatura:** Algoritmos y Lógica de Programación[span_1](start_span)[span_1](end_span)
* **Nivel / Paralelo:** Primer Semestre - Paralelo B[span_2](start_span)[span_2](end_span)
* **Actividad:** APE 4 - Integración de clases, objetos y métodos[span_3](start_span)[span_3](end_span)
* **Modalidad:** Presencial / Individual[span_4](start_span)[span_4](end_span)

---

## Contenido del Repositorio

Este repositorio contiene la implementación en Java de los ejercicios prácticos correspondientes a la integración de clases, objetos y métodos:

| Archivo | Enfoque |
| :--- | :--- |
| `Ejercicio1-1.java` | Objeto como atributo[span_5](start_span)[span_5](end_span) |
| `Ejercicio2-1.java` | Firmas y retornos[span_6](start_span)[span_6](end_span) |
| `Ejercicio3-1.java` | Objeto como parámetro[span_7](start_span)[span_7](end_span) |
| `Ejercicio4-1.java` | Cuentas y validaciones[span_8](start_span)[span_8](end_span) |
| `Ejercicio5-1.java` | Colaboración de clases[span_9](start_span)[span_9](end_span) |

---

## Detalle de los Ejercicios

### Ejercicio 1: Libro y Autor
* **Enfoque:** Objeto como atributo[span_10](start_span)[span_10](end_span).
* **Enunciado:** Crea la clase Autor (nombre, nacionalidad) y la clase Libro (titulo, anio, autor). Libro debe tener un atributo de tipo Autor y un metodo mostrarInformacion() que imprima el titulo, el año y el nombre del autor. En el método main, crea 2 libros[span_11](start_span)[span_11](end_span).

### Ejercicio 2: Rectángulo
* **Enfoque:** Firmas de métodos[span_12](start_span)[span_12](end_span).
* **Enunciado:** Crea la clase Rectangulo (base, altura) con los siguientes métodos, usando el tipo de retorno correcto en cada firma: calcularArea(), calcularPerimetro(), esCuadrado(), obtenerDescripcion() (devuelve una cadena como "Rectangulo de 4.0 x 6.0") y mostrar() para imprimir todos los resultados[span_13](start_span)[span_13](end_span).

### Ejercicio 3: Producto y Venta
* **Enfoque:** Objeto como parámetro[span_14](start_span)[span_14](end_span).
* **Enunciado:** Crea la clase Producto (nombre, precio, stock) con el método reducirStock(int cantidad) (que solo actúa si hay stock suficiente; si no, imprime "Stock insuficiente.") y mostrarProducto(). Crea la clase Venta (cantidad) con el método aplicar(Producto producto) que reduzca el stock y muestre el total a pagar[span_15](start_span)[span_15](end_span).

### Ejercicio 4: Transferencias
* **Enfoque:** Objeto como parámetro y validación de estados[span_16](start_span)[span_16](end_span).
* **Enunciado:** Usa la clase Cuenta y agrega el método transferir(Cuenta destino, double monto), que retire el monto de la cuenta actual y lo deposite en la cuenta destino solo si hay fondos suficientes. En el main, crea 2 cuentas, realiza una transferencia válida y otra que falle[span_17](start_span)[span_17](end_span).

### Ejercicio 5: Biblioteca
* **Enfoque:** Colaboración entre clases[span_18](start_span)[span_18](end_span).
* **Enunciado:** Crea tres clases que colaboren entre sí: Usuario, Libro y Prestamo. Prestamo tiene atributos de tipo Usuario y Libro, y su método registrar() intenta prestar el libro y muestra un mensaje según el resultado. En el main, haz que dos usuarios intenten pedir el mismo libro[span_19](start_span)[span_19](end_span).

---

<p align="center">
  <b>Universidad Técnica de Ambato</b>
</p>
