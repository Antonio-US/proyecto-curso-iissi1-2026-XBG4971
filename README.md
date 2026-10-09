# Nox

## Miembros del grupo LX-XXX-X (sustituir)

1. Bolaños Sevillano, Alfredo
2. Jimenez de la Fuente, Alvaro
3. Padilla Copado, Antonio
4. Salazar Alonso, Antonio

## 1. Introducción al problema

- Nuestro equipo se pone a disposición de la clienta Nadia Coronel Correa, quien preside una asociación estudiantil centrada en ámbitos académicos, por
lo que nuestro proyecto consistirá en proveer de un servicio de acceso a material de
estudio, archivos realizados por estudiantes etc… .
- En términos generales, la clienta solicita una aplicación que recoja archivos y material de
estudio organizados en distintos repositorios para ponerlos al servicio de unos usuarios, que
a su vez son socios de la asociación a la que se presta este proyecto. La aplicación
distingue entre usuario corriente y usuario administrador. Un usuario corriente tiene que
tener la posibilidad tanto de donar sus documentos de cualquier ámbito estudiantil
pudiendo clasificarlo por sus características (grado universitario, curso… ) como de acceder
y descargar otros archivos de la aplicación.
- Por otro lado se distingue un usuario
administrador perteneciente a la junta directiva de la asociación, un perfil con la capacidad
de realizar todas las acciones de un usuario común y de aprobar o denegar documentos
subidos por los estudiantes con el fin de verificar la validez de los mismos.

Versión extendida de la introducción al problema: [Acta de primera entrevista](Acta%20de%20primera%20entrevista.md)

## 2. Glosario de términos

- Términos específicos del dominio del problema, ordenados alfabéticamente. Se valorará la presencia de información multimedia.

## 3. Visión general del sistema

### 3.1. Requisitos generales
- Registro de Material de Estudio: Como presidenta de la asociación de estudio Astra, quiero centralizar el material de estudio digital para proveer un buen servicio de aprendizaje a los socios de la asociación.
- Organización de Repositorios y contenidos: Como Equipo directivo de Astra, queremos una búsqueda eficiente e intuitiva de los repositorios para facilitar el uso y gestión de la aplicación.
- Control de Material: Como Encargados principales de la asociación queremos un sistema de  verificación del material privado para controlar los archivos puestos a disposición de nuestros miembros.
- Gestión de material_ Como Junta Directiva de la asociación queremos manejar con libertad los documentos publicados y archivados para poder ofrecer un servicio completo y actualizado.
- Inicio de Sesión en la aplicación: Como presidenta quiero un sistema de inicio de sesión para asegurar la integridad de la aplicación y sus beneficiarios.
- Calificación de Servicios: Como proveedores queremos una forma de saber el nivel de satisfacción con el material de aprendizaje que compartimos


### 3.2. Usuarios del sistema

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales
- A continuación se redactan los requisitos funcionales que describen las principales funcionalidades que NOX debe proveer. Gestionar el repositorio académico de ASTRA, permitiendo a los estudiantes compartir, consultar y utilizar recursos académicos bajo un sistema de control de acceso y moderación. Así, los requisitos funcionales son los siguientes:

#### R.F.01. Registro de usuarios: 
Como presidenta, quiero permitir a los estudiantes crear una cuenta de usuario entregando los datos personales que la aplicación les pida, para que Nox pueda identificar los usuarios que accedan al sistema. 

#### R.F.02. Autenticación de usuarios: 
Como presidenta, quiero que Nox permita realizar inicio y cierre de sesión aplicando un método de autenticación para que los usuarios puedan identificarse. 

#### R.F.03. Gestión de roles y permisos: 
Como presidenta, quiero diferenciar entre usuarios ordinarios y autorizados, permitiendo establecer roles y permisos distintos para gestionar y controlar las funciones que cada usuario pueda desempeñar. 

#### R.F.04. Control de acceso al repositorio: 
Como presidenta, quiero limitar el acceso al repositorio de recursos académicos según se sea usuario o no, para tener un control del acceso a Nox. 

#### R.F.05. Liberación de recursos académicos: 
Como presidenta, quiero permitir que los usuarios suban sus recursos y que, una vez revisados, para quedar al libre uso del resto de miembros. 

#### R.F.06. Gestión de información de los recursos: 
Como  administrador, quiero administrar y clasificar correctamente la información de cada recurso académico liberado, para mejorar la gestión de los archivos. Asimismo, también debe garantizar al usuario la posibilidad de eliminar dicho recurso antes de ser verificado por un administrador.  

#### R.F.07. Revisión de recursos: 
Como administrador, quiero asegurar que los recursos publicados cumplen la normativa vigente de ASTRA, posibilitando a los usuarios autorizados visualizar el material que esté pendiente de revisión y tomar la decisión de si cumplen los criterios correspondientes para ser lanzados, para evitar la existencia dentro de Nox de archivos que no sean válidos. 

#### R.F.08. Aprobación y rechazo de recursos: 
Como administrador, quiero redactar el porqué de la eliminación o rechazo de un recurso académico liberado, para dejar constancia de una justificación válida para dicha decisión. 

#### R.F.09. Retirada de recursos: 
Como administrador, quiero retirar recursos académicos que hayan sido subidos cuando se detecte el incumplimiento de la normativa o cualquier otra razón que justifique su retirada, para no tener archivos dentro de Nox que dañen la plataforma, en cualquier sentido. 

#### R.F.10. Búsqueda de recursos: 
Como usuario, quiero poder buscar los recursos académicos que desee mediante el medio correspondiente para poder encontrar mis archivos más rápidamente. 

#### R.F.11. Filtrado de recursos. 
Como presidenta, quiero permitir que a la hora de buscar dichos recursos pueda aplicarse un filtrado por parámetros como la asignatura, carrera o curso, para alcanzar más rápido al resultado deseado. 

#### R.F.12. Consulta de recursos: 
Como usuario, quiero visualizar los recursos que vayan a descargarse para saber qué archivos van a ser utilizados. 

#### R.F.13. Descarga de recursos: 
Como usuario, quiero descargar los recursos que desee para tenerlos en mi ordenador.

#### R.F.14. Registro de descargas: 
Como administrador, quiero registrar el número de descargas realizadas en cada recurso académico, para mantener la constancia de la tendencia dentro de la plataforma que crea dichos archivos. 

#### R.F.15. Reporte de recursos: 
Como usuario, quiero poder detectar materiales que infrinjan normas de ASTRA, teniendo la posibilidad de comunicar incidencias relacionadas con el recurso académico para poder calificar la utilidad de los archivos mediante un sistema de calificación. 

#### R.F.16. Gestión de incidencias y moderación: 
Como administrador, quiero gestionar las incidencias comunicadas por los usuarios para emprender las acciones correspondientes sobre los usuarios que hayan subido el recurso académico infractor. 

#### R.F.17. Gestión de usuarios: 
Como administrador, quiero gestionar las cuentas de los usuarios, para mantener el control de acceso a Nox mediante un panel de administrador donde se pueda añadir, editar y eliminar cuentas de ususario así como nivel de permisos, derechos de descargas de archivos... etc. 

#### R.F.18. Suspensión y restauración del acceso: 
Como administrador, quiero poder suspender las cuentas a los usuarios en caso de incumplir la normativa así como la posibilidad de restaurarlas posteriormente, para poder permitir de nuevo la visualización de archivos y recursos de Nox. 

#### R.F.19. Gestión del estado de los recursos: 
Como administrador, quiero actualizar el estado de cada recurso (pendiente de revisión, aprobado, rechazado, retirado) para determinar si el archivo puede ser descargado por los estudiantes. 

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### 4.1.1. Requisitos de información

##### R.I.01. Título requisito de información

- Como socio quiero poder acceder a la siguiente información de cada archivo:
	- Autor
	- Fecha de subida
	- Formato
	- Nº de descargas
	- Puntuación
	- Verificación
	- Asignatura, que debe poseer la información:
		- Nombre de la asignatura
		- Titulación
		- Año de la carrera
 
##### R.I.02. Título requisito de información

- Como socio quiero poder editar la siguiente información de cada archivo:
	- Puntuación

##### R.I.03. Título requisito de información

- Como socio quiero poder acceder y editar la siguiente información de mi cuenta:
	- Nombre de usuario
	- Contraseña
	- archivos, que debe de contar con:
		- Apunte individual
	- Información personal, que debe constar de:
		- Nombre
		- Apellido
		- Nº de socio
		- Teléfono
		- Dirección
		- Correo
  
##### R.I.04. Título requisito de información

- Como socio quiero poder acceder a la siguiente información de las cuentas de otros socios:
	- Nombre de usuario
	- archivos

##### R.I.05. Título requisito de información

- Como administrador quiero poder acceder y editar la siguiente información de las cuentas de otros socios:
	- archivos
	- Permisos que a su vez consta de:
		- Permiso de descarga
		- Permiso de subida
		- Permiso de verificación
		- Permiso de registro
		- Permiso de uso de cuenta

##### R.I.06. Título requisito de información

- Como administrador/presidente/técnico quiero poder acceder a la siguiente información de las cuentas de otros socios:
	- Nombre de usuario
	- Información personal

##### R.I.07. Título requisito de información

- Como presidente/técnico quiero poder acceder y editar la siguiente información de las cuentas de otros socios/administradores:
	- Nombre de usuario
	- archivos
	- Información personal
	- Permisos que a su vez consta de:
		- Permiso de descarga
		- Permiso de subida
		- Permiso eliminación
		- Permiso administrador
		- Permiso permiso verificación
		- Permiso de registro
		- Permiso de uso de cuenta

##### R.I.08. Título requisito de información

- Como administrador/presidente quiero poder acceder y editar la siguiente información de cada archivo:
	- Formato
	- Verificación
	- Asignatura

##### R.I.09. Título requisito de información

- Como técnico quiero poder editar a la siguiente información de otras socios/administradores/presidente:
	- Nombre de usuario
	- archivos
	- Información personal

#### 4.1.2. Reglas de negocio

##### R.N.01. Título regla negocio
- Como presidenta de la asociación quiero que los archivos verificados solo reciban este criterio tras haber sido revisados por al menos dos administradores distintos para asegurar la diversidad de opinion en los archivos 
##### R.N.02. Título regla negocio
- Como presidenta quiero que todos lo usuarios posean un perfil completo (Nombre, contraseña, etc) dentro de la aplicación para poder ser fácilmente reconocibles
##### R.N.03. Título regla negocio
- Como técnico debo tener la exclusividad del acceso al código para garantizar un sistema de gestión de errores eficiente y maximizar el control del mantenimiento de la aplicación tras su lanzamiento
##### R.N.04. Título regla negocio
- Como presidenta quiero que los usuarios deban iniciar sesión a la aplicación mediante la información de su perfil (nombre/número de socio y contraseña) para facilitar su acceso a la aplicación 
##### R.N.05. Título regla negocio
- Como presidenta quiero que solo puedan subir archivos los socios con duración superior a una semana para asegurar el completo conocimiento de la normativa de la asociación por parte de los socios
##### R.N.06. Título regla negocio
- Como administrador quiero que los usuarios suspensos no puedan subir ni descargar archivos para mantener la calidad del contenido de la aplicación, sin impedir el estudio de los usuarios y como aliciente al uso correcto de la aplicación
##### R.N.07. Título regla negocio
- Como presidenta quiero que las cuentas de los usuarios puedan ser eliminadas permanentamente sin afectar a los archivos que hayan subido previamente para poder mantener un ambiente activo dentro de la aplicación sin eliminar contenido ya presente  
##### R.N.08. Título regla negocio
- Como técnico quiero que los usuarios no tengan acceso o derecho de manipulación de ningunos de sus permisos propios, para mantener la estabilidad de la jerarquía de permisos
##### R.N.09. Título regla negocio
-  Como presidenta quiero tener la capacidad de poder eliminar los permisos de los socios en caso de mala conducta y rebajarlos al rol de socio, para poder mantener la correcta administración de la aplicació
##### R.N.10. Título regla negocio
- Como administrador quiero que todas las cuentas de los socios sean automáticamente suspensas en septiembre de cada año y los administradores tengamos que reactivarlas, para mantener la aplicación acorde a la renovación de miembros de la asociación ASTRA
##### R.N.11. Título regla negocio
- Como presidenta quiero que los archivos de cursos anteriores sean eliminados si no supera cierto numero de descargas o presentan más de cierta puntuación, para mantener solo los archivos realmente útiles
##### R.N.12. Título regla negocio
- Como presidenta debo asegurar que el trato de la información de los usuarios se de en correspondencia con la normativa de ASTRA de protección de datos para mantener la integridad de la asociación 

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

### 4.2. Mapa de historias de usuario (opcional)

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Título requisito no funcional**
Como [tipo de usuario]
quiero [servicio]
para [razón]

-- fin entregable 1 --

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

- con restricciones.

### 5.2. Escenarios de prueba

- con descripción textual y diagrama de objetos UML.

## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:------|:-----------|:-----------|:-----------|:-----------|
| RI-1  | X          | X          | X          | X          |
| RI-2  |            | X          |            | X          |
| RF-1  |            | X          |            | X          |
| RF-2  | X          |            | X          | X          |
| RN-1  |            | X          |            |            |
| RN-2  | X          | X          | X          |            |
| ...   |            |            |            |            |

-- fin entregable 2 --

## 7. Modelo relacional en 3FN

- Relaciones obtenidas al aplicar la transformación del modelo conceptual.

### 7.1.  Justificación de la estrategia de transformación de jerarquías

- si se identificaron jerarquías en el MC.


### 8. Matriz de trazabilidad MC/SQL (opcional):

- Restricciones sobre el MC / Elementos del modelo tecnológico (SQL) (Triggers, checks, etc.)
- Incluir Reglas de negocio — Constraints/Triggers en las matrices de trazabilidad para el entregable 3

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:-------|:-------|:-------|:-------|:-------|
| TABLA-1 |        |        |        |        |
| TABLA-2 |        |        |        |        |
| TABLA-3 |        |        |        |        |
| TABLA-4 |        |        |        |        |
| TRIG-1 |        |        |        |        |
| TRIG-2 | X      | X      |        | X      |
| TRIG-3 |        | X      |        | X      |
| TRIG-4 |        |        | X      |        |
| CONST-1 |        |        |        |        |
| CONST-2 | X      | X      |        | X      |
| CONST-3 |        | X      |        | X      |
| CONST-4 |        |        | X      |        |

Se consideran todo tipo de constraints declarativas (aquellas definidas durante el CREATE TABLE).
-- fin entregable 3 --

## Referencias


