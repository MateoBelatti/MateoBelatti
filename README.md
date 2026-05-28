# Hola, soy Mateo Belatti 👋

Desarrollador full-stack enfocado en construir aplicaciones limpias y escalables — desde APIs REST hasta interfaces responsivas. Me importa escribir código que no solo funcione, sino que sea mantenible y esté bien estructurado.

---

## 🚀 Proyecto destacado: AppShowroom

AppShowroom es una aplicación web full-stack construida para mostrar y gestionar productos en un catálogo estilo showroom. El proyecto refleja mi capacidad de diseñar e implementar un sistema completo — desde la capa de base de datos hasta la interfaz de usuario — con una separación clara de responsabilidades entre el frontend y el backend.

El proyecto está dividido en dos repositorios independientes, cada uno con su propia responsabilidad:

---

### 🖥️ [AppShowroom — Frontend](https://github.com/MateoBelatti/AppShowroom-Frontend)

> React · Vite · JavaScript

Un frontend moderno basado en componentes, construido con **React** e impulsado por **Vite** para un desarrollo ágil y builds optimizados. La decisión de usar Vite por sobre bundlers tradicionales refleja un enfoque en la experiencia de desarrollo y el rendimiento desde el inicio.

**Puntos clave:**
- Arquitectura orientada a componentes para reutilización y escalabilidad
- Pipeline de build rápido con Vite — HMR casi instantáneo y bundles de producción livianos
- Se comunica con el backend a través de una API RESTful, manteniendo la capa de UI completamente desacoplada de la lógica de negocio

---

### ⚙️ [AppShowroom — Backend](https://github.com/MateoBelatti/AppShowroom-Backend)

> C# · ASP.NET Core · SQL Server · Arquitectura en capas

Una API REST robusta construida con **C# y ASP.NET Core**, siguiendo un patrón de arquitectura en capas que separa responsabilidades en proyectos bien definidos:

| Capa | Responsabilidad |
|---|---|
| `Api` | Controladores HTTP, ruteo, manejo de requests/responses |
| `Biblioteca` | Entity Framework (EF), dtos, mappers  |
| `Services` | Lógica de negocio, validaciones, orquestación |
| `Repository` | Abstraccion de capa de datos |

La persistencia de datos es manejada por **SQL Server**, por su confiabilidad y su integración nativa con .NET.

**Puntos clave:**
- Separación clara entre la superficie de la API, la lógica de servicios y los modelos de dominio
- Endpoints RESTful siguiendo convenciones estándar
- Solución de Visual Studio estructurada (`.slnx`) para una organización profesional del proyecto
- Diseño de API sin estado, preparado para escalar horizontalmente o integrarse con clientes externos en el futuro

---

## 🔄 Del monolito a una arquitectura moderna

Antes de la versión actual, este mismo proyecto existía como un único repositorio:

> **[appShowroom](https://github.com/MateoBelatti/appShowroom)** *(discontinuado)*

Esa versión — llamada internamente *CanelaApp* — fue la exploración inicial del concepto, pero fue construida con una stack diferente y sin la separación estructural que el proyecto necesitaba para crecer.

En lugar de parchearlo, tomé la decisión deliberada de **empezar de cero con las herramientas correctas**: adoptando ASP.NET Core y SQL Server en el backend para mayor solidez y escalabilidad, y React + Vite en el frontend para una capa de UI moderna y performante — cada uno viviendo en su propio repositorio con un contrato claro entre ellos.

Este cambio refleja algo que valoro en el desarrollo de software: **saber cuándo refactorizar y cuándo reconstruir**, y tener el criterio técnico para elegir la stack que se adapta al problema.

---

## 🛠️ Stack tecnológico

**Frontend**
`React` `Vite` `JavaScript` `Consumo de APIs REST`

**Backend**
`C#` `ASP.NET Core` `SQL Server` `API REST` `Arquitectura en capas`

**Herramientas**
`Visual Studio` `Git` `GitHub`

---
