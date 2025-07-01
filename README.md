# 🐾 Gestión de Mascotas en una Clínica Veterinaria

## 📌 ¿Para qué sirve este programa?

Este programa simula un sistema básico de gestión de mascotas (perros y gatos) para una clínica veterinaria. Permite al usuario ingresar los datos de su mascota, registrar vacunas, mostrar su información, escuchar su sonido y describirla brevemente.

Es una aplicación hecha en **Python** usando el paradigma de **Programación Orientada a Objetos (POO)**. Está diseñada para aprender y demostrar conceptos como **herencia**, **encapsulación** y **polimorfismo** de forma práctica y sencilla.

---

## 🧠 ¿Qué conceptos de POO se aplican y dónde?

| Concepto                 | Dónde se usa en el programa                                   |
|--------------------------|---------------------------------------------------------------|
| **Clase base**           | La clase `Mascota` contiene atributos y métodos comunes.      |
| **Herencia**             | Las clases `Perro` y `Gato` heredan de `Mascota`.             |
| **Encapsulación**        | Atributos `_nombre`, `_edad` y `_historial_vacunas` protegidos (con guion bajo). |
| **Polimorfismo (1)**     | Método `hacer_sonido()` sobrescrito en `Perro` y `Gato`.      |
| **Polimorfismo (2)**     | Método `describir()` con o sin argumento para comportamiento variable. |
| **Definición de atributos y métodos** | Se definen claramente en la clase `Mascota` y en las clases derivadas (`Perro`, `Gato`), con métodos para mostrar información, agregar vacunas, hacer sonidos y describir. |
| **Instanciación de clases** | En la función `crear_mascota()`, donde se crean objetos de tipo `Perro`, `Gato` o `Mascota` según la entrada del usuario. |

---

## ▶️ ¿Cómo funciona el programa?

1. El usuario ejecuta el programa y se le pide ingresar:
   - Especie: perro o gato
   - Nombre
   - Edad
2. Se crea un objeto `Perro`, `Gato` o `Mascota` según lo que el usuario ingresó, usando la herencia para definir clases derivadas.
3. Luego, el usuario puede:
   - Ver la información de la mascota
   - Agregar vacunas
   - Escuchar el sonido del animal (según su especie)
   - Escribir una breve descripción

Todo esto se hace desde un menú interactivo en la terminal.
