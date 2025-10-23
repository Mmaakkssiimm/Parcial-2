# SabanaEats 🍔
**Parcial Supletorio – Programación y Decisiones**

Proyecto que simula el backend de una aplicación de pedidos on-campus para estudiantes de la Universidad de La Sabana.  
Permite a los usuarios ver el menú, crear pedidos y almacenar toda la información en una base de datos SQLite.

---

##  Descripción general

SabanaEats es un prototipo en consola que representa el flujo básico de una app de pedidos:
1. El usuario puede consultar el menú disponible (comidas, bebidas y postres).
2. Puede crear un nuevo pedido seleccionando productos por su ID y cantidad.
3. El sistema calcula el total con impuestos específicos por tipo de producto.
4. Los datos se guardan en la base de datos `sabana_eats.db`.

El programa combina tres pilares:
- **POO (Herencia y Polimorfismo)**
- **SQLite (persistencia de datos)**
- **Lógica de negocio y control de flujo en consola**

---

## Cómo ejecutar el programa

### 1. Requisitos previos
Asegúrate de tener instalado:
- Python 3.9 o superior  
- Jupyter Notebook  
- SQLite (ya viene incluido en Python)

### 2. Abrir el proyecto
1. Abre Visual Studio Code o Jupyter Notebook.
2. Carga el archivo `Parcial2Supletorio_Maksim_Nagi.ipynb`.
3. Ejecuta **todas las celdas en orden** (desde arriba hacia abajo).

### 3. Interacción con el menú
Al final del notebook, se ejecuta automáticamente la función principal:
menu_interactivo()

---

El programa mostrará un menú de opciones como este:

=== SabanaEats ===
1. Ver menú de productos
2. Crear nuevo pedido
3. Salir

---

Opciones disponibles:

1 → Muestra todos los productos disponibles en la base de datos.

2 → Permite crear un nuevo pedido paso a paso.

Pide el nombre del cliente.

Muestra el menú con los IDs.

Solicita el ID y la cantidad de cada producto (escribe fin para terminar).

Calcula el total con impuestos incluidos y guarda el pedido en la base de datos.

3 → Cierra el programa.

---

## Estructura del repositorio

SabanaEats/
├── Parcial2Supletorio_Maksim_Nagi.ipynb # Notebook principal con el código
├── sabana_eats.db # Base de datos generada y poblada
└── README.md # Este archivo

