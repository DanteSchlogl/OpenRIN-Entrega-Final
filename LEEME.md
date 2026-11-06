# OpenRIN 1.0 — Entrega final

Plataforma integral de alertas y monitoreo para pacientes anticoagulados.
Autor: Muñiz Cortés, Carlos Santiago · Legajo B00000955-VCO
Prácticas Profesionalizantes III · Docente: Weingand, Gastón Matías · Universidad Abierta Interamericana

## Contenido

| Carpeta | Qué hay |
|---|---|
| `1 - Documentacion` | Carpeta de Proyecto (PDF, 150 páginas). En `Revision` están las observaciones y las correcciones de texto aplicadas. |
| `2 - Manual del Programador` | Manual del programador en ayuda `.chm` y en documento PDF (manual de programación). |
| `3 - Modelo de diagramas (draw.io)` | Diagramas de clases, secuencia, casos de uso, actividad y DER, en `.drawio` (editables) y `.png`, con el generador. |
| `4 - Base de Datos` | Scripts SQL de las dos bases y un respaldo de las bases con los datos de demostración. |
| `5 - Manual de Usuario` | Manual de usuario (PDF) y la ayuda en línea `OpenRIN-Ayuda.chm` (la misma que abre el botón Ayuda y la tecla F1). |
| `6 - Manual de Instalacion` | Manual de instalación (PDF). |
| `7 - Software (Instalador)` | `OpenRIN-Setup.exe`: instala la aplicación, SQL Server Express si falta, las bases y los datos de demostración. |
| `8 - Codigo Fuente` | Solución .NET 8 (`PlataformaACO.sln`), herramientas y pruebas automáticas. |
| `Prueba SQL` | Consultas para probar a mano la protección de integridad (alterar y deshacer un dato) y los respaldos. Empiece por `LEEME.txt`. |

## Para probarlo

1. Ejecute `7 - Software (Instalador)\OpenRIN-Setup.exe` y acepte el aviso de Windows.
2. Abra OpenRIN desde el escritorio. Los usuarios de demostración y su contraseña inicial figuran en el Manual de instalación (cámbielas después de probar).

## Notas

- El modelo está hecho con draw.io; no se incluye un archivo de Enterprise Architect.
- La capa de datos del negocio usa Entity Framework Core. La carpeta modelo indica no usar frameworks de persistencia de terceros: conviene consultarlo con el docente.
