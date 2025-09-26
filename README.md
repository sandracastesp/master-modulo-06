# MÓDULO 6: Introducción a React
---

## 📌 Proyecto 1: Tarjeta de presentación con información estática
**Objetivo:**  
Aprender a crear un proyecto de React con Vite, definir y usar componentes funcionales, entender la sintaxis básica de JSX, renderizar información estática y ejecutar una aplicación en el navegador.  

**Resultado:**  
Se obtuvo una tarjeta de presentación simple en React con información estática.  

**Pasos realizados:**
1. Creación del proyecto con Vite e inicio del servidor.  
2. Creación del componente `Tarjeta.jsx` dentro de `src/` (extensión de JS que permite escribir código similar a HTML).  
3. Integración del componente en `App.jsx` y se reemplazó el código existente.  
4. Verificación de ejecución correcta de la aplicación.  

---

## 🛒 Proyecto 2: Lista de compras
**Objetivo:**  
Crear una aplicación web interactiva para generar una lista de compras usando `useState`, permitiendo al usuario **agregar** y **eliminar** productos en tiempo real. 

**Resultado:**  
Aplicación intuitiva con lista dinámica y manejo de estado con arreglos.  

**Pasos realizados:**
1. Creación del componente `ListaCompras`.  
2. Uso de `useState` para manejar el estado de la lista de compras.  
3. Input + botón para añadir productos.  
4. botón a lado de cada producto para eliminarlo (usando setProductos con el método .filter()) cuando el usuario desee quitarlo.  

---

## ⏱ Proyecto 3: Contador de tiempo
**Objetivo:**  
Simular una aplicación de seguimiento de tareas y calcular el tiempo total dedicado.  

**Hooks utilizados:**
- `useEffect`: gestionar efectos secundarios (como el manejo de la hora en la interfaz), se utiliza para actualizar el título de la página cada vez que las tareas cambian, cada vez que se agrega una tarea, el efecto se ejecuta y se actualiza el título con el total acumulad
- `useMemo`: optimizar cálculos de horas totales (evita cálculos innecesarios de las horas totales cuando no cambian las tareas).  
- `useState`: manejar tareas y duraciones.  

**Resultado:**  
Aplicación eficiente que calcula y actualiza el tiempo de manera dinámica solo cuando cambian las tareas.  

**Pasos realizados:**
1. Creación del proyecto con Vite e inicio del servidor. 
2. En App.jsx se implementó la lógica de la aplicación con un formularios que permita agregar tareas con su duración, lista de tareas con sus tiempos y total acumulado de tiempo que se calcule solo cuando se agregue una nueva tarea.
---

## 🚀 Proyecto 4: Ciclo de vida de componentes
**Objetivo:**  
Comprender el ciclo de vida de los componentes funcionales (montaje, actualización y desmontaje).  

**Conceptos aplicados:**  
- `useState`, `useEffect`, `useMemo` para gestionar el estado, ejecutar efectos secundarios, optimizar cálculos y comprender el ciclo de vida.
- Simulación de un **panel de control de una nave espacial**, mostrando distancia, combustible, estado y planetas visitados.  

---

## 🎮 Proyecto 5: Juego "Adivina el Número"
**Objetivo:**  
Practicar la **renderización condicional** como la capacidad de mostrar o esconder componente en la interfaz de usuario según ciertas condiciones,  permitiendo  modificar la interfaz dinámicamente en respuesta a eventos o estados y practicar la **composición de componentes**.  

**Resultado:**  
Juego interactivo en el que el usuario intenta adivinar un número aleatorio entre 1 y 100, con retroalimentación dinámica y contador de intentos.  

**Componentes creados dentro de src/ :**
- `Game`: lógica principal.  
- `useState`: Guarda número ingresado y respuesta.
- `InputNumber`: entrada de datos.  
- `Message`: mensajes de pista o éxito.  
- `RestartButton`: reiniciar el juego.  

Se probó el juego, se ajusta el diseño con CSS y se agrega contador de intentos.

---

## 🎛 Proyecto 6: Hooks avanzados
# Proyecto: Conditional Rendering y Components Composition en React

**Objetivo**
Este proyecto es un taller práctico para aprender **renderización condicional** y **composición de componentes** en React mediante un juego interactivo llamado **"Adivina el Número"**.  
El usuario debe adivinar un número generado aleatoriamente y recibirá retroalimentación dinámica hasta acertar.

Practicar:
- Renderización condicional para mostrar mensajes según el estado del juego.
- Composición de componentes para crear una interfaz modular y reutilizable.

**Estructura de Componentes**
- **Game**: Componente principal con la lógica del juego.  
- **InputNumber**: Campo de entrada para el número del usuario.  
- **Message**: Muestra pistas o mensajes de éxito.  
- **RestartButton**: Reinicia el juego.  

---

## 🌐 Proyecto 7: Rutas con `react-router-dom`
**Objetivo:**  
Aplicar rutas estáticas y dinámicas con `react-router-dom`.  

**Resultado:**  
Plataforma web para gestionar citas médicas con navegación entre páginas

**Enrutador básico con las siguientes rutas:**
- `/` → Inicio  
- `/citas` → Lista de citas médicas.
- `/citas/:id` → Detalles de cita (usando `useParams`)  
- `/*` → Página de error  

---

## 🔐 Proyecto final: Clon de Twitter (con autenticación)
**Objetivo:**  
Añadir un sistema de autenticación simulado para controlar el acceso a páginas y funcionalidades. Generar un clon simplificado de Twitter que permite registrarse o iniciar sesión e interactuar con la línea del tiempo y publicar tweets.

**Componentes creados:**
- `Login.js`: formulario de inicio de sesión.  
- `Home.js`: línea de tiempo.  
- `Profile.js`: perfil del usuario.  

**Características:**
- Estado de autenticación con `useState`.  
- Persistencia de la información con `localStorage`.  
- Rutas protegidas con React Router.  
- Redirecciones según autenticación.  

---

✨ **Conclusión:**  
Este módulo permitió comprender desde lo más básico de React hasta conceptos avanzados como hooks, renderización condicional, rutas y autenticación, desarrollando aplicaciones prácticas y escalables.
