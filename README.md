# APV — Baseline Repo (C# + EF Core + SQL Server)

APV es un sistema para cargar ventas, analizarlas y generar predicciones/indicadores para apoyar decisiones comerciales.
Este repositorio se usa como depósito de Elementos de Configuración (CI) y para crear una Línea Base (Baseline v1.0)
reproducible y auditable usando Git (tags y release).
Para esto se ha usado proyecto integrador semestre pasado Sexto.

## Stack (baseline)
- Backend: C# (.NET) + Entity Framework Core
- Base de datos: SQL Server
- Configuración: appsettings

## Estructura del repositorio
- /docs/SRS: requisitos
- /docs/SDD: diseño y arquitectura
- /src/APV.Minimal: código mínimo
- /tests/APV.Minimal.Tests: pruebas mínimas
- /config: appsettings.example.json 
- /scripts: scripts de ejemplo (SQL)


