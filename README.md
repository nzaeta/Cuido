# Cuido

Sitio web para una empresa que presta servicios de cuidado de adultos mayores. Desarrollado en equipo de 4 personas.

<strong>Por acuerdo con el cliente no podemos compartir el código en GitHub.</strong>

Rol: Desarrollo Back-End. API Rest <br>
Tecnologías utilizadas: Java, Spring Framework (Spring Boot y Spring Security), MySQL, JPA, Lombok, Git <br>
Herramientas: Eclipse, Insomnia, Workbench <br>

https://cuido.ar/

El proyecto fue dividido en 4 etapas:
- Módulo Administración (COMPLETADO)
- Módulo Liquidación 
- Módulo Profesional
- Módulo Cliente<br><br>


<strong>Módulo Administración (COMPLETADO)</strong><br>
- Login implementando JWT
- CRUD de Profesionales, Días y Horarios de disponibilidad, Pacientes, Contactos, Servicios, Turnos, Ausencias.
- Listar servicios sin cubrir, activos y finalizados.
- Asignar profesional, o reemplazar el ya asignado.
- Matcheo del turno cargado con los profesionales que puedan tomarlo, teniendo en cuenta: su especialidad, horario de trabajo, otros turnos ya tomados y ausencias informadas.
- Generar automáticamente nuevos turnos ante conflictos que se presenten al realizar algún cambio (modificación del horario, baja del profesional, vacaciones, etc.)

<br>


![image](https://github.com/nzaeta/Cuido/assets/106348660/bacc84e6-3f28-4553-806d-ae52ff793298)

![image](https://github.com/nzaeta/Cuido/assets/106348660/cdd1ab41-192a-4d48-81e9-77e9cc30238e)

![image](https://github.com/nzaeta/Cuido/assets/106348660/f26a0dec-02dc-46e8-b8c4-866bf77c651d)

<br>
<strong>Módulo Liquidación</strong>

Generar resumen de ingresos y egresos. Liquidar los pagos a profesionales y proveedores. Generar los recibos y facturas para enviar a los clientes.<br><br>

<strong>Módulo Profesional</strong>

Para ser accedido por un usuario con rol de profesional, donde podrá ver sus servicios activos y finalizados y la cantidad de hs que se le tienen que liquidar.<br>
Ver servicios sin cubrir y tomarlos según su disponibilidad. <br>
Agregar y modificar sus datos personales.<br><br>

<strong>Módulo Cliente</strong>

Para ser accedido por un usuario con rol de cliente. Podrá ver sus servicios activos y finalizados y la cantidad de hs que se le tienen que liquidar. 
Agregar y modificar sus datos personales.<br>
Acceder a una cámara que monitoree el servicio prestado (si lo contrata).<br>



