# evaluacionGit





\# evaluacionGit — Microservicios EPS



Repositorio del taller práctico de \*\*Control de versiones con Git y GitHub\*\*,

asignatura Ingeniería de Software III (FI303290), UNIAJC.



Simula la organización de un proyecto de microservicios para una \*\*EPS

(Entidad Promotora de Salud)\*\*, distribuido en tres ramas con contenido

diferenciado:



| Rama | Contenido |

|---|---|

| `main` | Estructura base de microservicios + documento de estructura |

| `desarrollo` | Estructura base + `Docs/` (arquitectura) + `Algoritmos\_pruebas/` |

| `pruebas` | Estructura base + `Algoritmos\_pruebas/` (sin `Docs/`) |



\## Estructura de microservicios (`eps-microservicios/`)



eps-microservicios/

├── api-gateway/

├── servicio-autenticacion/

├── servicio-afiliados/

├── servicio-citas/

├── servicio-historias-clinicas/

├── servicio-autorizaciones/

├── servicio-facturacion/

└── servicio-notificaciones/





Cada carpeta de servicio contiene únicamente un archivo `.gitkeep`

(o un `.txt` de una línea) porque Git no versiona carpetas vacías.



\## Arquitectura



Ver `Docs/Arquitectura\_EPS.docx` (solo en la rama `desarrollo`) para la

explicación completa y el diagrama de la arquitectura de microservicios.



\## Flujo de trabajo



```bash

git status

git add .

git commit -m "mensaje descriptivo"

git push origin <rama>

```



\## Autor



Estudiante: zharick Dayana Balanta Garcia

Usuario de GitHub: zharick-2026

Período académico: 2026-2



