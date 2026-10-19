MODELO INICIAL DE DATOS — HealthApp



Entidad: Paciente

\- paciente\_id

\- nombre\_completo

\- fecha\_nacimiento

\- correo

\- telefono



Entidad: Usuario

\- usuario\_id

\- correo

\- hash\_contrasena

\- rol



Relacion:

Un usuario autorizado puede gestionar la informacion

de un paciente de acuerdo con sus permisos.



Consideraciones:

\- Validar los datos antes de almacenarlos.

\- Evitar almacenar contrasenas en texto plano.

\- Restringir el acceso a la informacion sensible.



Nota:

Este documento representa una propuesta inicial,

no una base de datos implementada.

