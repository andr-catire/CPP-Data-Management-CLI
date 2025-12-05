# CPP-Data-Management-CLI
Este es un **Sistema de Gestión de Inventario y Mantenimiento de Datos de Tiendas** implementado en **C++** utilizando **Estructuras de Datos Dinámicas (Listas Enlazadas)**.
Desarrollado durante el segundo semestre de Estructuras de Datos, el proyecto se enfoca en replicar las funciones de mantenimiento y consulta de datos (CRUD) típicas de los sistemas de gestión empresarial (ERP). Demuestra un sólido entendimiento de la asignación dinámica de memoria, la manipulación de punteros y la construcción de nodos (`struct`) para gestionar información persistente.

## 🛠️ Tecnologías Utilizadas (Tech Stack)

| Categoría | Tecnología | Concepto Principal |
| :--- | :--- | :--- |
| **Lenguaje Base** | **C++** | Programación estructurada y manejo de memoria (`new`/`delete`). |
| **Estructura de Datos**| **Listas Enlazadas Simples** | Manejo de nodos dinámicos para `productos` y `tiendas`. |
| **Almacenamiento** | Archivos (`.dat`) | Persistencia de datos mediante lectura y escritura de archivos. |
| **Interfaz** | Consola/CLI | Interacción con el usuario mediante `cin`, `cout` y menús de opciones. |

## 💡 Características Clave (Operaciones CRUD y Punteros)

Este proyecto muestra capacidad para construir un sistema de gestión con todas las operaciones **CRUD** (Crear, Leer, Actualizar, Eliminar) implementadas mediante punteros:

### 📂 Mantenimiento de Productos y Tiendas
* **Crear y Eliminar Nodos:** Implementación de lógica para insertar y remover nodos (productos/tiendas) de la lista enlazada, manejando la reorganización de los punteros.
* **Consultas:** Búsqueda eficiente por código único y por nombre en la lista.
* **Modificación:** Funciones para modificar los datos dentro de un nodo (`nombre`, `marca`, `dirección`).

### 💾 Persistencia de Datos
* **Carga/Guardado a Archivo:** El sistema lee y escribe los datos de las estructuras en archivos `.dat` para que la información se mantenga disponible entre ejecuciones del programa.

## ⚙️ Estructura del Código

El corazón del proyecto reside en dos **Listas Enlazadas Simples**, donde cada nodo (`struct producto` y `struct tienda`) contiene los datos y un puntero (`*prox`) al siguiente elemento de la lista.

## 💻 Instalación y Uso

Este es un proyecto de consola de C++. Necesitarás un compilador de C++ (como g++ o Visual Studio con el kit de C++).

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/andr-catire/CPP-Data-Management-CLI.git](https://github.com/andr-catire/CPP-Data-Management-CLI.git)
    cd CPP-Data-Management-CLI
    ```

2.  **Compila el código:**
    ```bash
    # Si usas g++ en Linux/Chromebook
    g++ tu_archivo_principal.cpp -o app
    ```

3.  **Ejecuta el programa:**
    ```bash
    ./app
    ```
    Sigue las instrucciones del menú principal.

## 🧑‍💻 Desarrolladores

* **Andres Gonzales** (`andr-catire`)

---
