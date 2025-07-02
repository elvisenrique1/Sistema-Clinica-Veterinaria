## 🐾 Sistema de Gestión Clínica Veterinaria

#### ¡Bienvenido al repositorio del backend de la aplicación para la Gestión de una Clínica Veterinaria!
<p>
Este proyecto está diseñado para manejar la información de dueños, mascotas, citas y tratamientos, desarrollado en Java con Spring Boot, utilizando Maven como gestor de dependencias (Spring Boot DevTools, Lombok, Spring Web, JDBC API, MySQL Driver, HikariCP). Implementa conexión a la Base de Datos en la nube utilizando FreeDB.
</p>

Su objetivo principal es ofrecer una API para la gestión de datos relacionados con:

- **Dueños (Duenio):** Información de contacto de los propietarios de las mascotas.
- **Mascotas (Mascota):** Detalles sobre los animales, incluyendo su dueño asociado.
- **Citas (Cita):** Programación de turnos con información de fecha, hora, motivo y estado.
- **Tratamientos (Tratamiento):** Registro de diagnósticos, descripciones y costos asociados a una cita específica.

> Utiliza una base de datos MySQL.

> El proyecto cuenta con:

- Creación de paquete **entities** para la creacion y configuracion de las clases a implementar. (Duenio, Mascota, Cita y Tratamiento).
- Creación de paquete **enums** para la creacion y configuracion de la clase o enum a implementar. (Estado).
- Creación de paquete **repositories**, que incluye un subpaquete **interfaces** para la creación y configuración de las interfaces a implementar (**I_DuenioRepository, I_MascotaRepository, I_CitaRepository, I_TratamientoRepository**). Y las clases **DuenioRepository, MascotaRepository, CitaRepository, TratamientoRepository** pertenecientes al paquete en principio **repositories**.
- Creación de paquete **tests** incluye una clase **TestRepositories.java** que contiene una serie de pruebas para verificar la funcionalidad de los repositorios (CRUD y búsquedas específicas).

> Dentro del paquete resources.
- Creacion de carpeta "docs" que almacena los archivos DER (Diagrama de Entidad de Relación) en formato .png y en formato .mwb .
- Creacion de carpeta "sql" que contiene los archivos schema_DDL, Data_DML y queries.
- Pruebas o Test realizados de manera exitosa.

<p>
Este backend de Clínica Veterinaria representa una base sólida, su diseño modular y el uso de tecnologías estándar facilitan tanto el desarrollo como el mantenimiento. Las pruebas de repositorio aseguran la fiabilidad de las operaciones CRUD con una configuración adecuada, listo para la aplicación de gestión veterinaria. 
  
¡Esperando que este proyecto sea de gran utilidad! 
</p>

🧑‍💻 Desarrollado © 2025 **{<∫geedev>_}** by Elvis Guaiquire.
