# SRS v1 — Análisis Predictivo de Ventas (APV)

## Requisitos funcionales (RF)

REQ-001 (RF): El sistema debe permitir registrar ventas (fecha, producto, cantidad, total) en una base SQL Server.  
REQ-002 (RF): El sistema debe permitir consultar un resumen de ventas (total, registros, rango de fechas).  
REQ-003 (RF): El sistema debe permitir importar ventas desde CSV (validando formato mínimo).  
REQ-004 (RF): El sistema debe ejecutar una predicción básica (modo demo) y devolver un resultado estimado.

## Requisitos no funcionales (RNF)

REQ-005 (RNF - Persistencia): El acceso a datos debe implementarse usando Entity Framework Core.  
REQ-006 (RNF - Seguridad/Trazabilidad): El repositorio no debe incluir credenciales reales;

REQ-007 (RNF - Auditoría): El sistema debe registrar en un archivo de log la fecha y usuario que ejecuta el proceso de predicción (modo demo), para permitir auditoría.

