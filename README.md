# 📚 Curso de PHP y Laravel – De Cero a CRUD

Este repositorio contiene el plan de estudio para retomar **PHP** y llegar a desarrollar un **CRUD completo con Laravel**.  
La idea es avanzar desde lo más básico (variables, ciclos, métodos) hasta implementar un proyecto final en Laravel.  

---

## 📌 Contenido del Curso

### 🟢 Módulo 1: Fundamentos de PHP
**Objetivo:** Recordar y dominar la sintaxis base de PHP.  

**Temas:**
- ¿Qué es PHP? Historia y usos actuales.  
- Instalación y configuración (XAMPP, Laragon o Docker + PHP CLI).  
- Estructura de un archivo `.php`.  
- Variables, tipos de datos y constantes.  
- Operadores aritméticos, lógicos y de comparación.  
- Condicionales (`if`, `else`, `elseif`, `switch`).  
- Ciclos (`for`, `while`, `do...while`, `foreach`).  
- Funciones: definición, parámetros, valores de retorno.  
- Manejo de arreglos (`array`, asociativos, multidimensionales).  

**Ejercicio práctico:**  
Programa que calcule el promedio de calificaciones de un estudiante e indique si aprobó o reprobó.  

---

### 🟡 Módulo 2: PHP Intermedio
**Objetivo:** Aprender a estructurar mejor el código y trabajar con datos.  

**Temas:**
- Superglobales (`$_GET`, `$_POST`, `$_REQUEST`, `$_SERVER`).  
- Formularios HTML + PHP (enviar y recibir datos).  
- Manejo de sesiones y cookies.  
- Programación orientada a objetos (POO):  
  - Clases y objetos  
  - Propiedades y métodos  
  - Constructores y destructores  
  - Herencia y polimorfismo  
- Manejo de errores y excepciones.  

**Ejercicio práctico:**  
Formulario de inicio de sesión simple (sin base de datos).  

---

### 🟠 Módulo 3: PHP con Base de Datos (MySQL)
**Objetivo:** Conectar PHP con MySQL y realizar operaciones básicas.  

**Temas:**
- Introducción a MySQL y phpMyAdmin.  
- Conexión a la base de datos con `mysqli` y PDO.  
- Sentencias CRUD:  
  - Crear registros (INSERT).  
  - Leer registros (SELECT).  
  - Actualizar registros (UPDATE).  
  - Eliminar registros (DELETE).  
- Prevención de inyecciones SQL (sentencias preparadas).  

**Proyecto pequeño:**  
Agenda de contactos (CRUD básico en PHP + MySQL).  

---

### 🔵 Módulo 4: Introducción a Laravel
**Objetivo:** Conocer Laravel y sentar bases sólidas para usarlo.  

**Temas:**
- ¿Qué es un framework y por qué Laravel?  
- Instalación de Laravel con Composer.  
- Estructura de un proyecto Laravel.  
- Rutas (`routes/web.php`).  
- Controladores y vistas.  
- Blade templates (sistema de plantillas).  
- Migraciones y modelos (Eloquent ORM).  

**Ejercicio práctico:**  
Página web con un formulario de contacto que guarda datos en BD.  

---

### 🟣 Módulo 5: CRUD en Laravel
**Objetivo:** Construir un CRUD completo en Laravel.  

**Temas:**
- Crear un modelo y migración (ej. `Producto`).  
- Rutas y controladores RESTful.  
- Formularios y validación de datos.  
- Listado de registros con paginación.  
- Editar y eliminar registros.  
- Mensajes flash y redirecciones.  
- Relacionar modelos (ej. Categorías y Productos).  

**Proyecto final:**  
Un **CRUD de productos y categorías** en Laravel con interfaz en Blade.  

---

### 🔴 Módulo 6: Extras (Opcional)
- Autenticación en Laravel (login y registro con `php artisan make:auth` o Jetstream/Fortify).  
- Middleware y roles de usuario.  
- Deploy en hosting compartido o en servicios como Railway/Heroku.  

---

## ⏳ Duración sugerida
- 6 a 8 semanas, dedicando entre 6 y 8 horas semanales.  

---

## 🚀 Recomendación
- Crea una carpeta para cada módulo en este repo.  
- Documenta tus avances en un archivo `README.md` dentro de cada carpeta.  
- Sube los ejercicios y proyectos pequeños para tener tu progreso organizado.  
---
