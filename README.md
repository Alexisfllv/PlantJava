# Plantillas Base: MySQL y PostgreSQL con Spring Boot

Este repositorio contiene **dos plantillas iniciales** para proyectos
con **Spring Boot**, listas para trabajar con: - **MySQL**
(`PlantMysql`) - **PostgreSQL** (`PlantPostgresql`)

## 🚀 Uso de las plantillas

1.  Clona este repositorio.
2.  Copia la carpeta del proyecto que necesites (`PlantMysql` o
    `PlantPostgresql`).
3.  Cambia el nombre del proyecto según el nuevo que vayas a crear.

### 🔧 Cambio de nombre del proyecto

Para evitar conflictos y seguir buenas prácticas: 1. Edita el archivo
`pom.xml`: - Cambia el valor de `<artifactId>` por el nuevo nombre del
proyecto. - Cambia el valor de `<groupId>` si deseas organizar tus
paquetes bajo otro dominio/empresa.

2.  Renombra el directorio principal de tu proyecto.

3.  Ajusta el nombre del paquete dentro de `src/main/java` si es
    necesario.

Ejemplo:

``` xml
<groupId>com.miempresa</groupId>
<artifactId>MiNuevoProyecto</artifactId>
<version>0.0.1-SNAPSHOT</version>
```

## 📂 Estructura

    /PlantMysql
    /PlantPostgresql

Cada carpeta es independiente y puede servir como **base** para nuevos
desarrollos.

------------------------------------------------------------------------

✍️ Autor: Alexis Souv
