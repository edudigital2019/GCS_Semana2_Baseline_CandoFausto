# SDD v1 — Análisis Predictivo de Ventas (APV)

## Arquitectura (baseline)
- Capa de Dominio: entidades (ej. Sale)
- Capa de Datos: DbContext EF Core (SQL Server)
- Capa de Servicios: resumen y predicción demo
- Entrada/Salida: consola (v1 demo)

## Componentes mínimos
- Sale (Entidad)
- ApvDbContext (EF Core)
- SalesService (resumen)
- ForecastService (predicción demo)

## Decisiones técnicas
- .NET + EF Core por consistencia con el proyecto APV.
- SQL Server como motor de datos.
- Baseline v1.0 incluye documentación y un build mínimo reproducible.
