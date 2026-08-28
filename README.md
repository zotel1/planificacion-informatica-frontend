# ⚡ PokeAPI - Frontend

Frontend de una aplicación Pokédex desarrollado con **HTML**, **CSS** y **JavaScript**.

Este proyecto forma parte de un trabajo práctico académico y tiene como objetivo aplicar conceptos fundamentales de desarrollo frontend, consumo de APIs, manipulación del DOM, diseño responsive, Git/GitHub y trabajo colaborativo.

El proyecto se desarrollará inicialmente tomando como referencia el tutorial de freeCodeCamp Español:

**“Crea una Pokédex con HTML, CSS y JavaScript (PokéAPI)”**

Durante la etapa de aprendizaje se utilizará directamente la **PokeAPI oficial**. En la integración final, el frontend deberá obtener los datos mediante el backend desarrollado por el otro equipo.

---

## 🎯 Objetivo del proyecto

El objetivo principal es construir una Pokédex utilizando exclusivamente:

- HTML;
- CSS;
- JavaScript.

La primera versión del proyecto grupal buscará reproducir las funcionalidades desarrolladas en el tutorial de referencia.

Durante el aprendizaje:

```text
Frontend
HTML + CSS + JavaScript
        │
        │ fetch()
        ▼
PokeAPI oficial
```

Durante la integración final:

```text
Frontend
HTML + CSS + JavaScript
        │
        │ HTTP / fetch()
        ▼
Backend propio
Node.js + Express
        │
        │ HTTP / fetch()
        ▼
PokeAPI oficial
```

El frontend será responsable de:

- construir la interfaz de la Pokédex;
- mostrar los Pokémon obtenidos;
- representar su información en tarjetas;
- mostrar sus tipos;
- mostrar peso y altura;
- permitir filtrar Pokémon por tipo;
- permitir volver a visualizar todos los Pokémon;
- adaptarse a distintos tamaños de pantalla según lo realizado en el tutorial;
- consumir inicialmente PokeAPI;
- reemplazar posteriormente esas solicitudes por llamadas al backend propio.

No se incorporarán funcionalidades adicionales solamente porque sean posibles. Cualquier mejora posterior deberá ser analizada y aprobada antes de desarrollarse.

---

# 📚 Objetivos académicos

El objetivo del trabajo no es solamente obtener una aplicación funcionando.

También se busca que cada integrante comprenda y pueda explicar el código que incorpora al proyecto.

Durante el desarrollo se busca aprender y aplicar:

- HTML semántico;
- etiquetas;
- atributos;
- IDs;
- clases;
- estructura de una página web;
- CSS;
- variables CSS;
- modelo de caja;
- Flexbox;
- CSS Grid;
- diseño responsive;
- Media Queries;
- JavaScript;
- variables y constantes;
- funciones;
- arreglos;
- métodos como `map()` e `includes()`;
- eventos;
- Event Listeners;
- manipulación del DOM;
- creación dinámica de elementos;
- consumo de APIs;
- `fetch`;
- asincronía;
- Promises;
- JSON;
- Git;
- GitHub;
- ramas;
- commits;
- Pull Requests;
- revisión de código;
- trabajo colaborativo.

---

# 🎓 Material de aprendizaje

El material principal será el tutorial de freeCodeCamp Español:

**“Crea una Pokédex con HTML, CSS y JavaScript (PokéAPI)”**

Todos los integrantes deberán reproducir el tutorial completo.

El tutorial construye progresivamente:

```text
HTML
↓
Estructura de la Pokédex
↓
CSS
↓
Diseño de la interfaz
↓
Responsive Design
↓
JavaScript
↓
Consumo de PokeAPI
↓
Manipulación del DOM
↓
Generación de tarjetas
↓
Filtrado por tipo
```

El tutorial tiene una duración aproximada de una hora.

---

# 🧪 Repositorios personales de aprendizaje

Cada integrante deberá reproducir el tutorial completo en un **repositorio personal y público de GitHub**.

Estos repositorios funcionarán como laboratorios individuales de aprendizaje.

Cada integrante podrá allí:

- seguir el tutorial paso a paso;
- escribir el código mostrado;
- realizar pruebas;
- equivocarse y corregir;
- practicar Git;
- realizar commits propios;
- hacer push a GitHub;
- registrar su progreso individual.

El objetivo es que cada desarrollador tenga contacto con la aplicación completa antes de comenzar a implementar tareas en el repositorio compartido.

El código completo del tutorial desarrollado en estos repositorios **no se integrará automáticamente al repositorio grupal**.

La separación será:

```text
Repositorio personal
        │
        ├── tutorial
        ├── práctica
        ├── experimentación
        └── aprendizaje
```

y:

```text
Repositorio grupal
        │
        ├── tareas reales
        ├── ramas feature
        ├── commits individuales
        ├── Pull Requests
        └── producto académico
```

Cada integrante deberá poder explicar durante la defensa oral tanto el proceso de aprendizaje como las funcionalidades que desarrolló en el repositorio grupal.

---

# 👥 Equipo frontend

El equipo está compuesto por cuatro integrantes:

- Avaca — Desarrollador frontend.
- Robledo — Desarrollador frontend.
- Pedrozo — Desarrollador frontend.
- Sigel — Product Owner y desarrollador frontend.

Los cuatro integrantes participarán del aprendizaje y del desarrollo.

Sigel tendrá inicialmente además responsabilidades de:

- coordinación;
- organización del trabajo;
- preparación administrativa del repositorio;
- revisión del avance;
- apoyo técnico al equipo;
- coordinación con backend;
- realización de merges aprobados hacia `dev`.

Todos los integrantes deberán utilizar sus propias cuentas de GitHub y realizar sus propios commits.

El profesor forma parte del repositorio como colaborador y podrá revisar el historial para observar el aporte de cada integrante.

---

# 🚀 Tecnologías

## Frontend

- HTML5.
- CSS3.
- JavaScript.

No se utilizarán frameworks frontend.

Por lo tanto, la versión inicial no incorporará:

- React;
- Angular;
- Vue;
- TypeScript.

## APIs

Durante el aprendizaje:

- PokeAPI oficial.

Durante la integración:

- Backend propio del proyecto.

## Herramientas

- Git.
- GitHub.
- Trello.
- Navegador web.
- DevTools del navegador.

## Despliegue

Antes de la entrega se prevé publicar:

```text
Frontend → Vercel
```

El backend será desplegado por su equipo mediante Render u otro servicio gratuito acordado.

---

# 🏗️ Arquitectura prevista

## Etapa de aprendizaje

Mientras se reproduce el tutorial:

```text
┌─────────────────────────┐
│        FRONTEND         │
│                         │
│ HTML + CSS + JavaScript │
└────────────┬────────────┘
             │
             │ fetch()
             ▼
┌─────────────────────────┐
│     PokeAPI oficial     │
└─────────────────────────┘
```

Esta comunicación directa se utilizará para aprender el funcionamiento del tutorial.

## Arquitectura final

La versión integrada seguirá:

```text
┌─────────────────────────┐
│        FRONTEND         │
│                         │
│ HTML + CSS + JavaScript │
└────────────┬────────────┘
             │
             │ HTTP / fetch()
             ▼
┌─────────────────────────┐
│         BACKEND         │
│                         │
│    Node.js + Express    │
└────────────┬────────────┘
             │
             │ fetch()
             ▼
┌─────────────────────────┐
│     PokeAPI oficial     │
└─────────────────────────┘
```

En la integración final, el frontend no deberá depender directamente de PokeAPI para el recorrido principal acordado.

---

# 🧩 Funcionalidades iniciales

El alcance inicial se basa exclusivamente en lo desarrollado en el tutorial.

La aplicación:

- mostrará los primeros **151 Pokémon**;
- mostrará una tarjeta por Pokémon;
- mostrará el ID;
- mostrará el nombre;
- mostrará la imagen oficial;
- mostrará uno o dos tipos;
- mostrará peso;
- mostrará altura;
- permitirá filtrar Pokémon por tipo;
- permitirá volver a mostrar todos los Pokémon;
- utilizará un diseño responsive basado en CSS Grid y Media Queries.

No forma parte del alcance inicial agregar por cuenta propia:

- búsqueda por nombre;
- favoritos;
- equipos;
- colecciones;
- autenticación;
- estadísticas adicionales;
- evoluciones;
- movimientos;
- habilidades;
- paginación;
- nuevas vistas;
- frameworks.

Estas posibilidades podrán evaluarse posteriormente solamente si el proyecto principal está estable y existe tiempo suficiente.

---

# 🎨 Interfaz del tutorial

La interfaz contará inicialmente con:

```text
Header
│
└── Navegación
    └── Botones de filtrado por tipo

Main
│
└── Lista de Pokémon
    │
    ├── Tarjeta Pokémon
    ├── Tarjeta Pokémon
    ├── Tarjeta Pokémon
    └── ...
```

Las tarjetas mostrarán visualmente:

```text
ID
Imagen
Nombre
Tipos
Peso
Altura
```

El número de ID también forma parte del diseño visual de la tarjeta.

El objetivo inicial es aproximarse al diseño construido durante el tutorial antes de considerar modificaciones visuales propias.

---

# 📱 Diseño responsive

El tutorial incorpora un diseño adaptable mediante CSS.

Se utilizan principalmente:

- CSS Grid;
- unidades `fr`;
- Flexbox;
- Media Queries.

La distribución de tarjetas podrá cambiar según el tamaño de pantalla, mostrando aproximadamente:

```text
Pantallas pequeñas
→ 1 columna

Pantallas mayores
→ 2 o más columnas
```

El comportamiento definitivo deberá reproducir lo desarrollado en el tutorial.

---

# 📁 Estructura inicial

El tutorial utiliza una estructura sencilla:

```text
frontend/
│
├── index.html
├── style.css
├── main.js
└── README.md
```

No se incorporará una arquitectura de carpetas compleja sin una necesidad real.

Al tratarse de un proyecto académico para desarrolladores principiantes, se priorizará que la estructura sea fácil de comprender.

La organización podrá evolucionar posteriormente únicamente si el proyecto realmente lo necesita.

---

# ⚙️ Funcionamiento JavaScript

JavaScript será responsable de:

- consultar los datos;
- transformar información necesaria para mostrarla;
- generar las tarjetas dinámicamente;
- insertar contenido en el DOM;
- detectar clics en los botones de filtrado;
- filtrar Pokémon según sus tipos;
- volver a mostrar la lista completa cuando corresponda.

Entre los elementos principales del tutorial se encuentran:

```javascript
listaPokemon
```

como referencia al contenedor donde se mostrarán las tarjetas, y:

```javascript
botonesHeader
```

como conjunto de botones utilizados para el filtrado.

La función principal identificada en el tutorial es:

```javascript
mostrarPokemon(data)
```

Su responsabilidad es construir y mostrar visualmente la información de cada Pokémon dentro de la interfaz.

---

# 🌐 Consumo inicial de PokeAPI

El tutorial realiza una solicitud por Pokémon.

Conceptualmente:

```javascript
fetch(`https://pokeapi.co/api/v2/pokemon/${id}`)
```

para IDs comprendidos entre:

```text
1
↓
151
```

Por lo tanto, durante el aprendizaje el flujo será:

```text
GET Pokémon 1
GET Pokémon 2
GET Pokémon 3
...
GET Pokémon 151
```

Cada respuesta se transforma desde JSON y se utiliza para generar la tarjeta correspondiente.

---

# 📦 Datos utilizados

La primera versión necesita únicamente:

```json
{
  "id": 25,
  "name": "pikachu",
  "image": "URL_DE_OFFICIAL_ARTWORK",
  "types": [
    "electric"
  ],
  "weight": 60,
  "height": 4
}
```

Los datos utilizados son:

- `id`;
- `name`;
- imagen oficial;
- `types`;
- `weight`;
- `height`.

No se necesitan inicialmente estadísticas de combate ni otras propiedades disponibles en PokeAPI.

---

# 🎛️ Filtrado por tipo

El filtrado se realizará inicialmente en el frontend.

Los botones del encabezado utilizan eventos para detectar qué tipo fue seleccionado.

La lógica utiliza los tipos ya disponibles en los datos de cada Pokémon.

Conceptualmente se trabajará con operaciones como:

```javascript
data.types.map(...)
```

e:

```javascript
includes(...)
```

El usuario podrá:

```text
Seleccionar tipo
        ↓
Mostrar Pokémon de ese tipo
```

y también:

```text
Seleccionar “Ver todos”
        ↓
Mostrar nuevamente los 151 Pokémon
```

El backend no necesita implementar inicialmente un endpoint específico de filtrado para que esta funcionalidad exista.

---

# 🔗 Integración con backend

Durante la primera etapa:

```text
Frontend → PokeAPI
```

Posteriormente se realizará una prueba temprana utilizando un solo Pokémon.

Por ejemplo:

```text
Frontend
        ↓
GET /api/pokemon/25
        ↓
Backend
        ↓
PokeAPI
```

La prueba servirá para comprobar:

- URL del backend;
- CORS;
- estructura JSON;
- comunicación entre ambos proyectos;
- renderizado de los datos;
- posibles errores de integración.

La URL local prevista inicialmente es:

```text
http://localhost:3000
```

Por lo tanto, una solicitud podrá utilizar conceptualmente:

```javascript
fetch(`http://localhost:3000/api/pokemon/${id}`)
```

La ruta definitiva deberá respetar el contrato acordado entre frontend y backend.

---

# 📡 Contrato inicial con backend

El endpoint mínimo propuesto para la primera integración es:

```http
GET /api/pokemon/:id
```

Ejemplo:

```http
GET /api/pokemon/25
```

La respuesta preliminar será:

```json
{
  "id": 25,
  "name": "pikachu",
  "image": "URL_DE_OFFICIAL_ARTWORK",
  "types": [
    "electric"
  ],
  "weight": 60,
  "height": 4
}
```

Inicialmente podrá conservarse el comportamiento educativo del tutorial:

```text
GET /api/pokemon/1
GET /api/pokemon/2
GET /api/pokemon/3
...
GET /api/pokemon/151
```

Un posible endpoint de colección:

```http
GET /api/pokemon?limit=151
```

o una posible paginación:

```http
GET /api/pokemon?limit=20&offset=0
```

son evoluciones posibles del backend.

No son requisitos iniciales del frontend y no se desarrollará código que dependa de ellos hasta que hayan sido acordados e implementados.

---

# ⚠️ Manejo de errores

El tutorial no incorpora un sistema complejo de manejo de errores.

Durante la integración con nuestro backend se evaluará el comportamiento necesario para respuestas como:

```text
400 Bad Request
404 Not Found
500 Internal Server Error
```

El backend propone inicialmente una estructura simple:

```json
{
  "error": "Pokemon no encontrado"
}
```

El frontend deberá adaptarse solamente al formato de error que quede finalmente aprobado en el contrato.

No se inventará un sistema de errores complejo antes de necesitarlo.

---

# 🌿 Estrategia de ramas

El repositorio grupal utilizará:

```text
main
 ↑
dev
 ↑
feature/*
```

## `main`

Contendrá únicamente versiones estables.

No se desarrollarán funcionalidades directamente sobre esta rama.

## `dev`

Será la rama de integración.

Las funcionalidades terminadas, revisadas y aprobadas llegarán primero a `dev`.

No se desarrollarán funcionalidades directamente sobre esta rama.

## `feature/*`

Cada tarea se desarrollará en una rama independiente.

Formato previsto:

```text
feature/FE-XX-descripcion-corta
```

Ejemplos ilustrativos:

```text
feature/FE-01-configurar-base-frontend
feature/FE-02-crear-estructura-html
feature/FE-03-maquetar-tarjetas-pokemon
feature/FE-04-consumir-pokeapi
feature/FE-05-filtrar-pokemon-por-tipo
```

Estos nombres son ejemplos de la convención.

Los nombres definitivos serán establecidos cuando se apruebe el backlog y cada tarjeta de Trello indicará exactamente qué rama debe crear el desarrollador.

---

# 🏁 Inicialización de `dev`

Al comienzo del trabajo grupal, Sigel realizará una única acción administrativa:

```text
main
↓
crear dev
```

La creación de `dev` no representa una funcionalidad del producto.

Una vez disponible `dev`, el código del proyecto deberá incorporarse mediante el flujo normal:

```text
dev
↓
feature/FE-XX-descripcion
↓
Pull Request
↓
dev
```

La estructura inicial HTML, CSS y JavaScript no deberá desarrollarse directamente sobre `dev`.

---

# 🔄 Flujo de trabajo con Git y GitHub

Cada integrante utilizará su propia cuenta de GitHub.

Antes de comenzar una tarea:

```bash
git checkout dev
```

Actualizar:

```bash
git pull origin dev
```

Crear la rama indicada:

```bash
git checkout -b feature/FE-XX-descripcion
```

Comprobar la rama:

```bash
git branch
```

Después de trabajar y probar:

```bash
git status
```

Revisar los cambios y agregar los correspondientes a la tarea:

```bash
git add .
```

Crear un commit:

```bash
git commit -m "feat: descripcion del cambio"
```

La primera vez que se suba una rama:

```bash
git push -u origin feature/FE-XX-descripcion
```

Después se creará un Pull Request:

```text
feature/FE-XX-descripcion
        ↓
       dev
```

Las correcciones solicitadas durante una revisión deberán realizarse dentro de la misma rama.

Después de la aprobación y el merge:

```bash
git checkout dev
git pull origin dev
```

La siguiente tarea siempre debe comenzar desde una `dev` actualizada.

---

# 📝 Conventional Commits

Los commits deberán ser descriptivos.

Se utilizarán inicialmente convenciones sencillas como:

```text
feat:
fix:
docs:
```

Ejemplos:

```text
feat: crear estructura principal de la pokedex
```

```text
feat: agregar tarjetas de pokemon
```

```text
feat: consumir datos desde pokeapi
```

```text
feat: filtrar pokemon por tipo
```

```text
fix: corregir filtrado de pokemon
```

```text
docs: actualizar instrucciones del proyecto
```

No deberán utilizarse mensajes ambiguos como:

```text
cambios
prueba
actualizacion
arreglo
codigo nuevo
final
```

El historial de Git debe permitir comprender qué realizó cada integrante.

Esto también será importante para la evaluación académica del trabajo colaborativo.

---

# 🔍 Pull Requests

Toda funcionalidad del proyecto grupal deberá seguir:

```text
Tarea
↓
Rama feature
↓
Desarrollo
↓
Pruebas
↓
Commit
↓
Push
↓
Pull Request
↓
Revisión
↓
Merge a dev
```

Inicialmente, Sigel será responsable de realizar los merges hacia `dev`.

La revisión por otro integrante podrá realizarse cuando sea útil, especialmente como parte del aprendizaje colaborativo, pero no será obligatorio que todos los Pull Requests tengan un reviewer distinto.

Ninguna feature deberá integrarse directamente a `main`.

Cuando `dev` represente una versión estable:

```text
dev
↓
Pull Request
↓
main
```

---

# ✅ Criterios generales para considerar una tarea terminada

Una tarea no estará terminada solamente porque el código haya sido escrito.

Como mínimo deberá comprobarse que:

- cumple el objetivo acordado;
- funciona en el navegador;
- no presenta errores visibles relacionados con la tarea;
- se realizaron las pruebas manuales correspondientes;
- solamente incluye cambios relacionados con la tarea;
- fue desarrollada en la rama indicada;
- el responsable realizó sus propios commits;
- los commits tienen mensajes descriptivos;
- la rama fue subida a GitHub;
- existe un Pull Request hacia `dev`;
- las observaciones fueron corregidas cuando correspondía;
- el cambio fue aprobado antes del merge;
- la documentación fue actualizada si la tarea lo requiere.

---

# 🧪 Testing

El profesor no exige pruebas automatizadas.

Inicialmente se utilizarán pruebas manuales.

Según la funcionalidad podrán comprobarse:

- estructura visual;
- estilos;
- responsive;
- carga de los 151 Pokémon;
- información mostrada;
- tarjetas;
- botones;
- filtros;
- opción de mostrar todos;
- consola del navegador;
- pestaña Network;
- comunicación con PokeAPI;
- comunicación futura con el backend.

No se incorporará un framework de testing únicamente para aumentar la complejidad del proyecto.

---

# 📋 Gestión de tareas

El trabajo será organizado posteriormente mediante Trello.

El tablero no se creará hasta que el backlog técnico haya sido revisado y aprobado.

Las futuras tareas utilizarán identificadores:

```text
FE-XX
```

Cada tarjeta podrá contener:

- identificador;
- título;
- responsable principal;
- objetivo;
- motivo pedagógico;
- dependencias;
- prioridad;
- tamaño;
- conceptos practicados;
- rama exacta;
- criterios de aceptación;
- pruebas manuales;
- checklist técnico;
- checklist Git/GitHub.

Ejemplo conceptual:

```text
FE-XX — Nombre de la tarea
```

asociada a:

```text
feature/FE-XX-descripcion
```

Cada tarea tendrá un responsable principal para facilitar la trazabilidad del trabajo y de los commits.

---

# 🤝 Trabajo colaborativo

El proyecto está especialmente orientado al aprendizaje del trabajo en equipo.

No se dividirá permanentemente el equipo de esta manera:

```text
Integrante 1 → HTML
Integrante 2 → CSS
Integrante 3 → JavaScript
```

La intención es que, después de reproducir individualmente el tutorial, los integrantes puedan trabajar progresivamente sobre tareas reales del producto.

Se buscará que las tareas:

- tengan un objetivo claro;
- sean suficientemente pequeñas;
- permitan identificar al responsable;
- reduzcan dependencias innecesarias;
- permitan practicar Git y Pull Requests;
- permitan explicar el aporte durante la defensa oral.

La forma exacta de dividir las funcionalidades será definida en el backlog técnico antes de crear las tarjetas de Trello.

---

# 🔄 Relación entre aprendizaje y proyecto grupal

El proceso esperado será:

```text
Tutorial individual
        ↓
Repositorio personal público
        ↓
Comprensión de HTML + CSS + JavaScript
        ↓
Práctica de Git
        ↓
Repositorio grupal
        ↓
Tarea FE-XX
        ↓
feature/FE-XX
        ↓
Commit
        ↓
Push
        ↓
Pull Request
        ↓
dev
```

El objetivo es evitar que una única persona complete toda la aplicación y que los demás solamente realicen modificaciones menores.

Cada integrante deberá tener oportunidades concretas de aportar al repositorio grupal.

---

# 🛣️ Evolución prevista

## Etapa 1 — Aprendizaje individual

```text
HTML
CSS
JavaScript
PokeAPI
Git
```

Cada integrante reproduce el tutorial en su repositorio personal.

## Etapa 2 — Base del proyecto grupal

```text
index.html
style.css
main.js
```

Se crea la estructura mínima mediante tareas versionadas.

## Etapa 3 — Construcción grupal

Se incorporan progresivamente las funcionalidades presentes en el tutorial mediante ramas feature y Pull Requests.

## Etapa 4 — Integración temprana

Se prueba un único Pokémon utilizando:

```text
Frontend
↓
Backend
↓
PokeAPI
```

## Etapa 5 — Integración completa

El frontend reemplaza progresivamente las consultas directas a PokeAPI por solicitudes al backend propio.

El objetivo temporal inicial para esta integración es:

**19 al 25 de octubre de 2026.**

## Etapa 6 — Mejoras opcionales

Solo después de tener el recorrido principal integrado y estable podrán analizarse mejoras de diseño o funcionalidades adicionales.

## Etapa 7 — Estabilización y entrega

Los últimos días se reservarán para:

- pruebas;
- correcciones;
- documentación;
- integración;
- preparación de la defensa;
- despliegue;
- entrega.

No se planificarán funcionalidades importantes nuevas durante los últimos días.

---

# 🎤 Defensa oral

El trabajo incluye una defensa oral.

Cada desarrollador deberá poder explicar:

- qué tareas realizó;
- qué ramas utilizó;
- qué commits realizó;
- qué problemas encontró;
- cómo resolvió esos problemas;
- qué partes del código incorporó;
- cómo funciona su funcionalidad;
- cómo utilizó Git y GitHub;
- cómo colaboró con el resto del equipo.

Por este motivo, cada integrante deberá comprender el código que incorpora al proyecto y no limitarse a copiarlo.

---

# 📌 Estado del proyecto

🚧 **En planificación / desarrollo**

Fecha de entrega final:

**12 de noviembre de 2026**

El alcance inicial se encuentra basado en el tutorial:

**“Crea una Pokédex con HTML, CSS y JavaScript (PokéAPI)”**

La primera versión priorizará:

```text
Aprendizaje
↓
Trabajo colaborativo
↓
Pokédex del tutorial
↓
Integración con backend
↓
Estabilización
↓
Entrega
```

Las funcionalidades adicionales solamente se evaluarán una vez que el recorrido principal esté integrado y estable.