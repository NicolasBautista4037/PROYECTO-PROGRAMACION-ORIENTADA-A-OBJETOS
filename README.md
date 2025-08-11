# PROYECTO-PROGRAMACION-II
Este repositorio contiene todo lo relacionado con el desarrollo del proyecto para la asignatura de programación II.

# Aplicación Web Local para Gestión de Cultivos en Finca

## Breve Descripción del Problema que Resuelve

Muchos agricultores y pequeños propietarios tienen dificultades para llevar un control sencillo y organizado de sus cultivos y actividades en la finca, especialmente sin acceso a sistemas complejos o conexión a internet. Esta aplicación resuelve ese problema al ofrecer una herramienta web que funciona 100% local en el navegador, para gestionar cultivos de forma fácil, rápida y sin depender de servidores ni APIs externas.

## Integrantes del Equipo

- [Johán Nicolás Bautista Raba](https://github.com/NicolasBautista4037)
- [Juan Sebastian Morales]()

## Lista Inicial de Módulos del Sistema

1. **Gestión de Cultivos:**  
   - Registrar cultivos (nombre, tipo, fecha de siembra, área sembrada).  
   - Listar cultivos existentes.  
   - Editar y eliminar registros de cultivos.

2. **Persistencia Local:**  
   - Almacenamiento y recuperación de datos usando LocalStorage del navegador.  
   - Datos guardados automáticamente para que persistan tras cerrar el navegador.

3. **Interfaz de Usuario:**  
   - Página web sencilla, responsive y amigable.  
   - Formularios y tablas para manipular los datos.

4. **Opcionales (futuras mejoras):**  
   - Incorporar chatbot básico con respuestas predefinidas.  
   - Exportar información a CSV para respaldo manual.

## Tecnologías a Utilizar

- **HTML5** para estructura.  
- **CSS3** para diseño y estilos.  
- **JavaScript** para la lógica del CRUD y manipulación del DOM.  
- **LocalStorage** para almacenamiento local y persistente.

## Flujo del Sistema

1. El usuario abre la aplicación en su navegador.  
2. Puede registrar nuevos cultivos llenando un formulario.  
3. Los cultivos se listan dinámicamente en pantalla.  
4. Puede editar o eliminar cualquier cultivo.  
5. Todos los datos se guardan y cargan desde LocalStorage automáticamente.  
6. No se requiere conexión a internet para funcionar.

## Cronograma de actividades

| Actividad                     | Duración estimada |
|------------------------------|-------------------|
| Diseño de interfaz y prototipo| 2 días            |
| Desarrollo de funcionalidades | 5 días            |
| Pruebas y correcciones        | 2 días            |
| Documentación final           | 1 día             |

## Beneficios del enfoque local

- Total independencia de conexión o servidores externos.  
- Fácil instalación y uso inmediato en cualquier navegador moderno.  
- Control total del usuario sobre sus datos.  
- Ideal para usuarios con poco acceso a tecnologías avanzadas.

---

## Enlaces de interés

- [Documentación LocalStorage MDN](https://developer.mozilla.org/es/docs/Web/API/Window/localStorage)  
- [Ejemplo simple de CRUD en JavaScript](https://www.w3schools.com/howto/howto_js_todolist.asp)

---

## Posibles Mejoras Futuras

- Integrar chatbot básico con respuestas predefinidas embebidas en JS.  
- Añadir sistema de exportación/importación de datos.  
- Mejorar UI con frameworks ligeros como TailwindCSS o Bootstrap.  
- Incorporar módulos simples de estadísticas y reportes.

---


