\# Plan de pruebas — HealthApp



\## CP-01. Campos vacios

Entrada: correo y contrasena vacios.

Resultado esperado: solicitar los datos obligatorios.



\## CP-02. Datos incompletos

Entrada: solo se proporciona el correo.

Resultado esperado: impedir el intento de acceso.



\## CP-03. Credenciales incorrectas

Entrada: credenciales no validas.

Resultado esperado: rechazar el acceso y mostrar un mensaje.



\## CP-04. Credenciales validas

Entrada: credenciales correctas.

Resultado esperado: permitir el acceso autorizado.



\## Alcance

Estos casos documentan el comportamiento esperado.

Su ejecucion requiere implementar el modulo de autenticacion.

