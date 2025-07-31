# Stack Tecnológico
- ![Angular](https://img.shields.io/badge/-Angular-DD0031?logo=angular&logoColor=white)
- ![ExpressJS](https://img.shields.io/badge/expressjs-blue?style=plastic&logoColor=white)
- ![SQLite](https://img.shields.io/badge/sqllite-blue?style=plastic&logoColor=white)

# Ramas
- `main`: Rama productiva. En esta rama esta el código que se despliega a producción (usuarios finales).
- `develop`: Rama principal de desarrollo. De esta rama surgen las ramas de trabajo del equipo y aqui llegan los cambios que están listos para producción.

# Nombrado de ramas
- `feat/`: rama donde se trabajará una nueva funcionalidad. Surge de la rama `develop`.
- `fix/`: rama donde se trabajará la solución a un bug que no es urgente arreglar. Surge de la rama `develop`.
- `hotfix/`: rama donde se trabajará la solución a un bug que afecta a los usuarios y debe ser solucionado de inmediato. Surge de la rama `main`.

Ejemplo de nombrado de rama
Se debe desarrollar el componente de upload de ficheros
`feat/upload-files`
se ocupa el prefix `feat/` ya que es una nueva funcionalidad y la descripción `upload-files` describe lo que se realizará (en inglés).

# Versionado

Basaremos el versionado en `MAJOR.MINOR.PATCH`
donde:

- `MAJOR`: corresponde a una versión completamente diferente de la actual.
- `MINOR`: incrementa con cada nuevo despliegue a producción desde `develop` o al ser un `hotfix`, esto reinicia `PATCH` a `0`.
- `PATCH`: incrementa en relación a las ramas `feat/` o `fix` que surjan de `develop`, es decir, cada nueva rama de trabajo incrementa el versionado solo en `PATCH`.  
