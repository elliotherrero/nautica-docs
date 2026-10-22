# Cómo contribuir a nautica-docs

## Ramas

- La rama `main` debe tener siempre código que funcione.
- No se suben cambios directamente a `main`.
- Cada tarea se realiza en una rama `feature/nombre-de-la-tarea`.
- Los arreglos urgentes utilizan `hotfix/descripcion`.

## Mensajes de commit

- Cada commit debe contener un cambio concreto.
- Utilizamos el formato Conventional Commits:
  - `feat: añade la página de servicios`
  - `fix: corrige el enlace del menú`
  - `docs: actualiza el README`
- Los mensajes se escriben en imperativo, en una línea y sin punto final.

## Pull requests

- Indica la incidencia que resuelve con `closes #5`, cambiando el número por el de la incidencia correspondiente.
- Otro miembro del equipo debe revisar y aprobar antes de fusionar.
- Después de fusionar, se borra la rama.

## Lo que nunca se sube

- Contraseñas, tokens ni claves privadas.
- Archivos de configuración personal como `.env`, `.vscode/` o `.idea/`.