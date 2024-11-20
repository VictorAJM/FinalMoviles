# Proyecto Final: Dispositivos Inteligentes

## Milestones Detallados

### **1. Configuración Inicial** (1-2 días)

- [X] **Configurar el entorno:**
  - Instalar Node.js, Expo CLI, y configurar un proyecto de React Native.
  - Crear un proyecto en Firebase y configurar Firestore como base de datos.
  - Configurar Firebase en el proyecto React Native.
  - Instalar dependencias principales:
    - `firebase`
    - `react-navigation`
    - Librerías de diseño (`react-native-paper`, `styled-components`, etc.).
- [ ] **Definir la estructura del proyecto:**
  - Crear carpetas base:
    - `screens`, `components`, `services`, y `assets`.
  - Crear colecciones iniciales en Firebase:
    - **categorías**
    - **productos**

---

### **2. Desarrollo de Pantalla Principal** (3-4 días)

- [ ] **Diseño del UI:**
  - Crear la pantalla inicial para mostrar categorías como cuadros o tarjetas.
  - Añadir un campo de entrada y un botón para agregar nuevas categorías.
- [ ] **Funcionalidad:**
  - Conectar la pantalla inicial a Firebase Firestore:
    - Consultar y mostrar las categorías disponibles.
    - Permitir agregar nuevas categorías (validar entradas para evitar duplicados).
  - Implementar navegación a la pantalla de productos al seleccionar una categoría.
- [ ] **Pruebas:**
  - Verificar que las categorías se guardan y se muestran correctamente.

---

### **3. Desarrollo de la Pantalla de Productos** (4-5 días)

- [ ] **Diseño del UI:**
  - Crear una lista estilizada para mostrar productos de la categoría seleccionada.
  - Añadir un campo de entrada y un botón para agregar nuevos productos.
- [ ] **Funcionalidad:**
  - Consultar productos relacionados a la categoría seleccionada desde Firebase.
  - Permitir agregar nuevos productos con:
    - Nombre
    - Descripción
    - Imagen (subida a Firebase Storage).
  - Guardar la URL de la imagen en Firestore.
- [ ] **Estilización:**
  - Diseñar la lista de productos mostrando:
    - Nombre
    - Descripción
    - Imagen en miniatura.
- [ ] **Pruebas:**
  - Verificar que los productos se muestran y actualizan correctamente.

---

### **4. Mejora de la Presentación** (2-3 días)

- [ ] **Optimización de la Interfaz:**
  - Ajustar el diseño para dispositivos móviles.
  - Implementar un tema de colores y estilos consistentes.
- [ ] **Animaciones:**
  - Añadir transiciones al abrir pantallas o actualizar listas.

---

### **5. Pruebas y Documentación** (2-3 días)

- [ ] **Pruebas Completas:**
  - Revisar todas las funciones principales:
    - Agregar categorías/productos.
    - Consultar listas.
    - Manejar errores o entradas inválidas.
  - Probar la aplicación en distintos dispositivos/emuladores.
- [ ] **Documentación del Código:**
  - Agregar comentarios claros para explicar la lógica y las integraciones clave.

---

### **6. Preparación para la Presentación** (1-2 días)

- [ ] **División de Roles:**
  - Asignar secciones del proyecto para que cada integrante pueda explicarlas.
- [ ] **Simulación de Preguntas:**
  - Preparar preguntas comunes sobre:
    - Lógica del código.
    - Integración con Firebase.

---

## Productos Incluidos

Cada producto debe incluir:

- **Nombre:** Título claro del producto.
- **Descripción:** Breve detalle del producto.
- **Imagen:** Subida a Firebase Storage.

**Ejemplo visual:**

- **Categoría:** Tecnología
  - **Producto:** Laptop X
    - **Descripción:** Procesador Intel i7, 16GB RAM.
    - **Imagen:** Mostrada desde Firebase.

---

## Rúbrica de Evaluación

- **Uso de una fuente de datos como Firebase Firestore o una REST API:** 60%
- **Funcionamiento completo de la aplicación con React Native:** 30%
- **Buena presentación de la aplicación (estilo, diseño, etc.):** 10%
