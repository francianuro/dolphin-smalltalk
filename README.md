# dolphin-smalltalk
Inciso 3 - Sistema de Gestión de Consultas Médicas
Un consultorio médico necesita un sistema de gestión para organizar a los pacientes que
atiende diariamente. El software a desarrollar debe permitir:
El sistema debe permitir cargar los datos del consultorio, como el nombre del consultorio, la
cantidad de pacientes diarios, el número de médicos disponibles y las especialidades que
ofrece.
El consultorio atiende a una distinta cantidad de pacientes cada día. De cada consulta, se
debe registrar número de consulta, DNI del paciente, nombre completo, edad, síntomas,
médico asignado, fecha y hora de consulta (Se estima que las consultas se dan cada media
hora). Además, se debe especificar si la consulta es de tipo regular o de urgencia.
Para las consultas regulares, se debe almacenar también el diagnóstico y la receta si
corresponde. En el caso de las consultas de urgencia, se debe registrar la prioridad (Alta,
Media o Baja) y el tiempo de atención estimado.
El sistema debe permitir buscar a una consulta específica mediante número de consulta para
modificar su información o eliminar su registro. Tener en cuenta que las consultas regulares
no pueden superponerse. Si se diera el caso en que entra una consulta de urgencia en el
horario de una regular, se debe retrasar la consulta regular (y sus consultas posteriores, si
las hubiese) media hora.
Se debe poder generar un listado con todas las consultas realizadas o por realizar en un día
determinado, mostrando tanto las regulares como las de urgencia.
Se debe poder mostrar una lista solo con las consultas urgentes, ordenadas por prioridad
(de Alta a Baja).
Muchas veces es necesario realizar un informe de la edad promedio de los pacientes que
frecuentan distintas franjas horarias. Se debe poder elegir la franja a mostrar, ya sea mañana
(de 8 a 13), tarde (13 a 18) y noche (18 a 23).
Al irse de vacaciones, los médicos (usuarios del sistema), podrían querer ver las consultas
que hayan reservadas para ir acomodando sus agendas, por lo que se debe permitir generar
un listado de consultas, excluyendo el plazo de vacación del doctor.
Generar un diccionario que guarde la cantidad de consultas por paciente.
