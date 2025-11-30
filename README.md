# Evidencia 3 – Listado de Proyectos (Actividades 9, 10, 11 y 12)

Este repositorio contiene los proyectos desarrollados durante las Actividades 9, 10, 11 y 12.  
Cada actividad fue construida como un módulo independiente y se encuentra vinculada como submódulo dentro de este repositorio.

---

## ✅ Actividad 9 – Aplicación Base con Sidebar Personalizado

**Descripción del proyecto:**  
Se desarrolló una aplicación base en Android con un sidebar totalmente personalizado.  
La tarea incluía modificar:
- El ícono del usuario  
- El nombre del usuario  
- El correo  
- El nombre de la aplicación  
- El ícono de la app instalada  
- La pantalla de carga  
Esta aplicación funcionó como la base para las actividades posteriores.

**Experiencia personal:**  
Fue la primera vez que personalicé una aplicación Android desde cero con un sidebar real. Aunque al inicio fue confuso modificar íconos y la pantalla de carga, la estructura base terminó siendo útil para las actividades siguientes. Sentí que esta actividad me dio el “esqueleto” que iba a reutilizar muchas veces.

---

## ✅ Actividad 10 – Consumo de API (Rick & Morty / Simpsons u otra API)

**Descripción del proyecto:**  
Utilizando como base la aplicación creada en la actividad 9, se integró una API externa.  
La aplicación debía:
- Mostrar un listado de personajes  
- Al seleccionar uno, cargar sus detalles  
- Mostrar también información relacionada (como episodios)  
La lógica debía aplicar igual si se usaba otra API externa.

**Experiencia personal:**  
Fue interesante conectar una API con la interfaz de Android. El reto más grande fue manejar las peticiones y el detalle de cada personaje sin que la app se sintiera pesada. Al final logré que cargara bien la información, y fue la actividad donde empecé a sentir realmente cómo “respiraba” la app con datos reales.

---

## ✅ Actividad 11 – Uso de Base de Datos (CRUD + Relación de Datos)

**Descripción del proyecto:**  
Basado nuevamente en la app de la actividad 9, se creó una plataforma con:
- CRUD de catálogos  
- Una tabla con relación de datos  
- Una vista donde se revisan los datos cruzados  
Yo implementé la base de datos usando **Supabase**, de manera que todos los cambios se reflejaran en la nube.

**Comentarios del profesor:**  
La funcionalidad era correcta, pero el cambio no se reflejaba dinámicamente en la app al guardar.  
Se recomendó agregar:
- Un ícono personalizado  
- Una pantalla de loading

**Experiencia personal:**  
Fue la primera vez que usé Supabase en un proyecto Android. Me gustó que la información se mostrara en la base real, pero tuve problemas con el refresco dinámico de los datos. Intenté varias estrategias, pero aún así la app funcionó con la lógica CRUD principal. Esta actividad me obligó a pensar en sincronización de estados y en cómo se debe refrescar una UI en tiempo real.

---

## ✅ Actividad 12 – Proyecto Final

**Descripción del proyecto:**  
Entrega final del curso.  
Se entregó un archivo `.zip` que contenía:
- La aplicación final en formato `.apk`  
- Un PDF explicando el planteamiento del proyecto, las soluciones que ofrece y las ventajas de usarlo  

Este proyecto integró todo lo aprendido en las actividades anteriores:  
sidebar, consumo de API, base de datos, pantallas personalizadas y estructura de Android.

**Experiencia personal:**  
Fue la actividad más completa y donde conecté todo el aprendizaje del curso. El PDF me ayudó a estructurar el por qué de la aplicación y qué problema intentaba resolver. Fue satisfactorio ver que todo lo aprendido podía combinarse en un solo proyecto final funcional.

---

## 📌 Conclusión General

Las actividades formaron una secuencia lógica:  
primero la base visual, luego consumo de datos, después la base de datos y finalmente el proyecto completo.  
Trabajar con Android, APIs y Supabase me permitió desarrollar una aplicación más sólida y entender mejor el flujo de datos en aplicaciones móviles.

---
