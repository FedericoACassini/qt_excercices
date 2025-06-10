# 🧠 Ejercicios Qt - Práctica de GUI en C++
Ejercicios prácticos utilizando Qt5 y C++, desarrollados como parte de la cursada de Programación.

Cada proyecto es una aplicación Qt individual enfocada en distintos temas clave: componentes gráficos, layouts, señales y slots, manejo de archivos, memoria, networking, integración con APIs y más.

---

## 📁 Proyectos

🔢 **01 - Ordenamiento de Postes (Clase personalizada)**
Define una clase `Poste` con atributos de altura y diámetro. Se almacenan en un arreglo propio y se ordenan por altura sin usar `std::vector` ni algoritmos de STL.

🔤 **02 - Ordenar Frases Hechas (Sin espacios)**
Almacena 5 expresiones idiomáticas en un `std::vector<std::string>`, las ordena alfabéticamente ignorando los espacios y muestra el resultado.

🧪 **03 - Inundación de Memoria (Límite de asignación)**
Define una clase personalizada y crea instancias hasta consumir aproximadamente 200 MB de RAM. Muestra la cantidad total de objetos creados.

🎚️ **04 - Control de Volumen (Título dinámico)**
Sincroniza un `QSlider` con un `QSpinBox` y actualiza el título de la ventana en tiempo real con el valor del volumen actual.

🖼️ **05 - Mostrar Imagen (Visor con autocierre)**
Muestra una imagen de alta resolución desde disco en un `QLabel` maximizado. La imagen no se deforma y la aplicación se cierra automáticamente luego de 3 segundos.

🔐 **06 & 07 - Login + Captcha (Cambio de formulario & validación)**
Implementa una pantalla de login con usuario y contraseña. Si son correctos (`admin` / `1111`), se abre un segundo formulario con campos de legajo, nombre, apellido y captcha.  
Incluye:
- Contraseña enmascarada con asteriscos  
- Presionar Enter activa el login  
- Validación del captcha  
- Restricciones y feedback de errores  

---

## 🛰️ Ejercicios de Red e Integración con API

🌐 **09 - Primera app con `network` 2025**  
- Crear canal de YouTube (modo **no listado**).  
- Replicar el ejemplo de clase para que **la imagen se descargue correctamente**.  
- Subir un video demostrando el funcionamiento.

🔑 **10 - Login en `empty project` 2025**  
- Replicar el ejemplo de login en un proyecto vacío.  
- Grabar video explicativo y subirlo como **no listado**.

🎨 **11 - Login con QtDesigner 2025**  
- Replicar el login usando **QtDesigner**.  
- Subir video con explicación.

🌡️ **12 - Login con temperatura de Córdoba**  
- Diseñar formulario con QtDesigner.  
- Mostrar temperatura actual usando API (`QLabel`).  
- Validar `admin` / `1234`, si es correcto abre otra ventana vacía.

🖼️ **13 - Login con imagen de fondo desde internet**  
- Añadir una imagen de fondo descargada automáticamente.  
- Al validar el login, abre una segunda ventana vacía.

📸 **14 - App para mostrar imagen y texto desde API**  
- Consumir una API que devuelva nombre, edad, país, imagen de avatar.  
- Mostrar esos datos en la segunda ventana.

🔁 **15 - Dos formularios (inicio y registro)**  
- Ventana de inicio con botones "Ingresar" y "Registrarse".  
- Cada uno abre su respectivo formulario.

🧾 **16 - Registro con validaciones**  
- Agregar campos: usuario, email, contraseña.  
- Verificar que todos estén completos antes de continuar.

🧮 **17 - Validaciones y señalización de errores**  
- Mostrar errores si los campos están vacíos.  
- Aplicar estilo de borde rojo para los inputs con error.

🔌 **18 - Comunicación con API externa**  
- Usar `QNetworkAccessManager` para enviar login y recibir respuesta.  
- Separar la lógica en una clase.

📡 **19 - Centralizar DataManager**  
- Eliminar managers de `Widget` y `Register`.  
- Usar una única clase `DataManager` para manejar las solicitudes HTTP.  
- Emitir señales como `loginExitoso()`, `loginFallido(QString)`.

🧠 **20 - Herencia y polimorfismo en Qt**  
- Crear jerarquía de clases que hereden de una clase base.  
- Usar punteros base para manejar objetos derivados en la interfaz.

🗃️ **21 - Guardar y leer desde SQLite**  
- Conectar con base de datos SQLite.  
- Guardar datos de registro y mostrarlos desde una tabla.

🧵 **22 - Uso de hilos en Qt (QThread)**  
- Realizar una tarea pesada (como descarga) en segundo plano.  
- Mostrar barra de progreso en la interfaz.

🎮 **23 - Simulador T-Rex (Juego estilo Google Dino)**  
- Juego simple con detección de colisiones, salto y obstáculos.  
- Usar `QTimer` y `QKeyEvent`.

⚙️ **24 - Benchmarking de funciones `inline`**  
- Comparar funciones normales vs funciones `inline` en tiempo de ejecución.  
- Mostrar resultados en consola.

---

## 🛠️ Requisitos
- Qt 5.x o superior  
- C++11 o superior  
- Compatible con Qt Creator (proyectos `qmake`)

---

## 👨‍💻 Autor
**Federico Cassini**  
Estudiante de Ingeniería en Informática

---

## 📄 Licencia
Este repositorio es público y de uso educativo. Podés hacer fork, adaptarlo o compartirlo libremente.
