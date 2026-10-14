# SecurePlan Backend

API de **SecurePlan Mobile**, una aplicación móvil de agenda para organizar actividades y mejorar la productividad. Este repositorio es el servidor: guarda los datos de los usuarios y de sus eventos, y se los entrega de forma segura a la app móvil.

Proyecto integrador de la asignatura Desarrollo Móviles Integral.

## Qué hace

- Registra usuarios y permite iniciar sesión de forma segura.
- Guarda y administra los eventos de la agenda de cada usuario.
- Protege la información: cada usuario solo puede ver y modificar sus propios eventos.
- Permite exportar la agenda en distintos formatos.

## Tecnologías

- .NET
- PostgreSQL

La app móvil está en el repositorio [secureplan-mobile](https://github.com/DelmyCab27/secureplan-mobile).

## Cómo ejecutarlo

1. Instala .NET y PostgreSQL.
2. Crea una base de datos vacía.
3. Copia el archivo `.env.example` a `.env` y llena tus datos de conexión.
4. Corre el servidor con `dotnet run`.

## Equipo

| Integrante | Rol |
| --- | --- |
| _Josue_ | Lead Backend & Security Engineer |
| _Kairos_ | Lead Frontend Mobile Developer |
| _Yussif_ | UI/UX & Mobile Developer |
| _Delmy_ | DevSecOps & QA Engineer (Scrum Master) |
| _Adolfo_ | Fullstack Support & Sync Integrator |
