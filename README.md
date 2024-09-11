# Trabajo Práctico JPA + ENVERS - Desarrollo de Software 2024 <br/> Tomás Camacho | 3K09

Esta vez, al proyecto que realizamos implementando JPA, le agregamos auditoría con Envers a todas nuestras entidades. Además, probamos en el main (clase PersistenceApp) las instrucciones MERGE y REMOVE. <br/>

El trabajo fue individual, tuvimos a disposición videos del canal ColmenaTec, y un proyecto base que realizó el profesor Alberto Cortez. Además, se nos dio a disposición el archivo persistence.xml y las dependencias necesarias para llevar adelante el proyecto.

## Utilizamos:

✅ IntelliJ Idea <br/>
✅ H2 para la base de datos <br/>
✅ Librería LOMBOK <br/>
✅ Java Persistence <br/>
✅ Java Entity Manager Factory <br/>
✅ Hibernate Envers <br/>

## Instrucciones de uso

1️⃣  Ejecutar el main (se ejecutará la persistencia de las tablas, teniendo en el archivo 'persistence.xml' la acción CREATE). <br/>

2️⃣  Una vez creadas las tablas, comentar todo el código identificado como 'PERSIST' y descomentar el código identificado como 'MERGE'. Luego se debe cambiar la acción 'create' del archivo 'persistence.xml' por la acción 'update'. Ejecutarlo. Aquí actualizaremos el número de la factura1 y lo registraremos en la tabla Factura_AUD y en Revision_Info. <br/>

3️⃣  Comentar de nuevo el código MERGE, descomentar el código identificado como 'REMOVE' y ejecutarlo. Para este paso mantenemos la acción 'update' en el archivo persistence. Se eliminará la factura1 y veremos el registro de esta acción en las tablas Factura_AUD y Revision_Info.
