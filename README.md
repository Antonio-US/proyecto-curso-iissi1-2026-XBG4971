# Nox

## Miembros del grupo LX-XXX-X (sustituir)

1. Bolaños Sevillano, Alfredo
2. Jimenez de la Fuente, Alvaro
3. Padilla Copado, Antonio
4. Salazar Alonso, Antonio

## 1. Introducción al problema

- Nuestro equipo se pone a disposición de la clienta Nadia Coronel Correa, quien preside una asociación estudiantil centrada en ámbitos académicos, por
lo que nuestro proyecto consistirá en proveer de un servicio de acceso a material de
estudio, apuntes realizados por estudiantes etc… .
- En términos generales, la clienta solicita una aplicación que recoja apuntes y material de
estudio organizados en distintos repositorios para ponerlos al servicio de unos usuarios, que
a su vez son socios de la asociación a la que se presta este proyecto. La aplicación
distingue entre usuario corriente y usuario administrador. Un usuario corriente tiene que
tener la posibilidad tanto de donar sus documentos de cualquier ámbito estudiantil
pudiendo clasificarlo por sus características (grado universitario, curso… ) como de acceder
y descargar otros apuntes de la aplicación.
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
A continuación se redactan los requisitos funcionales que describen las principales funcionalidades que NOX debe proveer. Gestionar el repositorio académico de ASTRA, permitiendo a los estudiantes compartir, consultar y utilizar recursos académicos bajo un sistema de control de acceso y moderación. Así, los requisitos funcionales son los siguientes:


#### R.F.01. Título requisito funcional

Como [tipo de usuario]
quiero [servicio]
para [razón]

#### R.F.01. Título requisito funcional

Como [tipo de usuario]
quiero [servicio]
para [razón]


**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### 4.1.1. Requisitos de información

##### R.I.01. Título requisito de información

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- ...

#### 4.1.2. Reglas de negocio

##### R.N.01. Título regla negocio

Como presidenta de la asociación quiero que los archivos verificados solo reciban este criterio tras haber sido revisados por al menos dos administradores distintos para asegurar la diversidad de opinion en los archivos 
##### R.N.02. Título regla negocio
Como presidenta quiero que todos lo usuarios posean un perfil completo (Nombre, contraseña, etc) dentro de la aplicación para poder ser fácilmente reconocibles
##### R.N.03. Título regla negocio
Como técnico debo tener la exclusividad del acceso al código para garantizar un sistema de gestión de errores eficiente y maximizar el control del mantenimiento de la aplicación tras su lanzamiento
##### R.N.04. Título regla negocio
Como presidenta quiero que los usuarios deban iniciar sesión a la aplicación mediante la información de su perfil (nombre/número de socio y contraseña) para facilitar el acceso de los usuarios a la aplicación 
##### R.N.05. Título regla negocio
Como presidenta quiero que solo puedan subir archivos los miembros de la asociación universitaria ASTRA con duración superior a una semana para asegurar el completo conocimiento de la normativa de la asociación por parte de los usuarios
##### R.N.06. Título regla negocio
Como administrador quiero que los usuarios suspensos no puedan subir ni descargar archivos para mantener la calidad del contenido de la aplicación, sin impedir el estudio de los usuarios y como aliciente al uso correcto de la aplicación
##### R.N.01. Título regla negocio
Como presidenta quiero que las cuentas de los usuarios puedan ser eliminadas permanentamente sin afectar a los apuntes que hayan subido previamente para poder mantener un ambiente activo dentro de la aplicación sin eliminar contenido ya presente  
##### R.N.07. Título regla negocio
Como administrador quiero que todas las cuentas de los usuarios sean automáticamente suspensas en septiembre de cada año y los administradores tengamos que reactivarlas, para mantener la aplicación acorde a la renovación de miembros de la asociación ASTRA
##### R.N.08. Título regla negocio
Como presidenta quiero que los apuntes de cursos anteriores sean eliminados si no supera cierto numero de descargas o presentan más de cierta puntuación, para mantener solo los apuntes realmente útiles
##### R.N.09. Título regla negocio
Como presidenta debo asegurar que el trato de la información de los usuarios se de en correspondencia con la normativa de ASTRA de protección de datos para mantener la integridad de la asociación 

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


