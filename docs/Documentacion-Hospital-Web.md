# Documentación – Hospital Web
**Proyecto:** interfaz-construyete
**Fecha:** Octubre 2026
**Estado:** Completado con capturas de pantalla

## Índice
1. Introducción
2. Objetivos
3. Alcance
4. Descripción General
5. Tecnologías Utilizadas
6. Estructura de Archivos
7. Diseño de Interfaz
8. Roles del Sistema
9. Arquitectura del Sistema
10. Flujo Cliente-Servidor
11. Formulario de Solicitud de Cita
12. Funcionalidad JavaScript
13. Guía de Uso
14. Capturas de Pantalla (PENDIENTE)
15. Conclusión
16. Recomendaciones

## 1. Introducción
Hospital Web es un sistema web para consultar y solicitar servicios médicos. Es una página estática con portal de bienvenida, navegación por secciones y formulario de citas.

## 2. Objetivos
- Facilitar el acceso a información médica.
- Mostrar roles y arquitectura Cliente-Servidor de forma didáctica.
- Permitir solicitar citas mediante formulario.

## 3. Alcance
Proyecto front-end sin backend ni base de datos real. La lógica de servidor/base de datos se representa de forma conceptual.

## 4. Descripción General
- Portal de bienvenida a pantalla completa con gradiente.
- Solicitud de nombre, correo y edad antes de ingresar.
- Barra de carga animada 0-100%.
- Secciones: Inicio, Roles, Arquitectura, Solicitar cita.

## 5. Tecnologías Utilizadas
- HTML5, CSS3 (flex, grid, responsive), JavaScript Vanilla.

## 6. Estructura de Archivos
```text
interfaz-construyete/
├── index.html
├── README.md
└── docs/
    ├── Documentacion-Hospital-Web.md
    └── Documentacion-Hospital-Web.pdf
```

## 7. Diseño de Interfaz
- Colores principales: #0066ff, #6a35ff, #d633ff, fondo #f1f7ff.
- Tarjetas de roles con gradientes.
- Apartados con <details>/<summary> de colores.
- Responsive @media(max-width:750px).

## 8. Roles del Sistema
- **Administrador:** Gestiona usuarios, citas, médicos y expedientes.
- **Cliente:** Consulta información y solicita citas.
- **Servidor:** Procesa solicitudes y administra información.

## 9. Arquitectura del Sistema
- Usuario/Cliente, Solicitud, Servidor, Respuesta, Base de datos, Flujo del sistema.

## 10. Flujo Cliente-Servidor
Cliente → Solicitud → Servidor → Base de datos → Respuesta → Cliente.

## 11. Formulario de Solicitud de Cita
Campos: Nombre completo, Número de expediente, Especialidad (Medicina general, Pediatría, Cardiología, Dermatología, Ginecología), Fecha, Hora, Teléfono, Motivo. Valida con `required` y muestra alerta de confirmación.

## 12. Funcionalidad JavaScript
- `mostrarDatos()`: muestra formulario de datos.
- `iniciarCarga()`: valida nombre/correo/edad (1-120) y anima barra.
- `mostrarPagina(pagina)`: cambia sección activa y scroll top.
- `enviarSolicitud(event)`: preventDefault + alert confirmación.

## 13. Guía de Uso
1. Abrir `index.html` en navegador.
2. Clic Ingresar → completar nombre, correo, edad → Continuar.
3. Esperar carga 100%.
4. Navegar con botones Inicio/Roles/Arquitectura/Solicitar cita.

## 14. Capturas de Pantalla

### 14.1 Creación del repositorio en GitHub
Se verifica que el nombre `interfaz-construyete` está disponible.

![Crear repositorio](../imgs/Captura%20de%20pantalla%202026-10-03%20223843.png)

### 14.2 Repositorio creado - Quick setup
GitHub muestra las instrucciones para subir con `git init`, `add`, `commit` y `push`.

![Quick setup](../imgs/Captura%20de%20pantalla%202026-10-03%20223940.png)

### 14.3 Portal de bienvenida Hospital Web
Pantalla inicial con botón Ingresar.

![Bienvenida](../imgs/Captura%20de%20pantalla%202026-10-03%20224820.png)

### 14.4 Formulario Antes de ingresar
Solicitud de Nombre, Correo electrónico y Edad con botón Continuar.

![Antes de ingresar](../imgs/Captura%20de%20pantalla%202026-10-03%20230304.png)

## 15. Conclusión
Interfaz completa, funcional y responsive, lista y subida a GitHub, con evidencia visual incluida.

## 16. Recomendaciones
- Agregar capturas cuando estén disponibles.
- A futuro: backend, base de datos, validación servidor, autenticación.
