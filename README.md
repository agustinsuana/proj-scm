# Proyecto Plan de Gestión de la Configuración
## Version 0.1

Historia de revisiones
| Fecha      | Version | Descripcion                          | Autor           |
|------------|---------|--------------------------------------|------------------
| 23/09/2023 | 0.1     | Elaboración de plan de configuracion | Fabiola Carrasco|
| 23/09/2023 | 0.1     | Elaboración de plan de configuracion | Eduardo Medina  |
| 23/09/2023 | 0.1     | Elaboración de plan de configuracion | Agustin Suaña   |


### 1. Introducción
El presente informe contiene el Plan de Gestión de Configuración de la Aplicación de Geolocalización para Empresa Distribuidora de GLP (AGED), un las actividades de SCM son:
- Planificar la configuración de SCM
- Definición de la línea base del proyecto.
- Seguimiento de la línea base del proyecto.
- Definición del ambiente controlado.
- Control de cambios.
- Descripción de la versión.
- Notas de la versión.
- Realizar informe final de SCM

#### 1.1 Propósito
Este documento describe las actividades de gestión de configuración de software que deben ser llevadas a cabo durante el proceso de desarrollo del proyecto. Aquí se definen tanto los productos que se pondrán bajo control de configuración como los procedimientos que deben ser seguidos por los integrantes del equipo de trabajo.

#### 1.2 Alcance
El Plan de configuración está basado en algunos supuestos que se detallarán:
- El tiempo de duración del proyecto está limitado a 14 semanas, por lo tanto se busca una rápida respuesta a los cambios, tratando que este procedimiento sea lo menos burocrático posible.
- El Modelo de Proceso se basa en un desarrollo incremental, dado por las distintas iteraciones. Resulta importante tener control sobre cada una de las iteraciones y fases, de los productos generados en estas y de los cambios surgidos, evaluados y aprobados.
- La elección de los elementos de configuración se realizará en base a los entregables, siendo ésta responsabilidad del Responsable de SCM, apoyado por los integrantes de cada disciplina.

#### 1.3 Terminología
CCB (Configuration Control Board) Comité de Control de Configuración.
CI (Configuration Item) elemento bajo gestión de Configuración.
SCA (Software Change Authorization) Autorización de Cambio en el Software.
SCM (Software Configuration Management) Gestión de Configuración del Software.
SCMR (SCM Responsible) Responsable de SCM.
SCR (System/Software Change Request) Petición de Cambio en el Sistema/Software.
SQA (Software Quality Assurance) Aseguramiento de la Calidad del Software.
SQAR (SQA Responsible) Responsable de SQA.
VR (Verification Responsible) Responsable de verificación.


Definimos como un elemento de configuración a una unidad física y/o lógica parte de un conjunto mayor de elementos, producida o adquirida, que por sus características es distinguible de las demás y cuya evolución interesa administrar. Son elementos de Configuración en un proyecto de software:

01. El plan de proyecto. 
02. El plan de Gestión de Configuración. 
03. El documento de definición de requerimientos. 
04. Estándares de análisis, diseño, codificación, pruebas y auditoría.
05. Documentos de análisis del sistema. 
06. Documentos de diseño del sistema. 
07. Prototipos. 
08. Documentos de diseño de alto nivel. 
09. Documentos de diseño de bajo nivel. 
10. Especificaciones de prueba del sistema. 
11. El plan de pruebas del sistema. 
12. El Código fuente del programa. 
13. Código objeto y ejecutable. 
14. Especificaciones de pruebas de unidad. 
15. Planes de pruebas de unidad. 
16. Documentos de diseño de base de datos. 
17. Datos de prueba. 
18. Datos del proyecto. 
19. Manuales de usuario.

Referencias
ISO 12207
IEEE 1012

Gestión de SCM
A continuación, se describen las responsabilidades y responsables para la realización de las actividades de gestión de configuración dentro del proyecto.

Organización

Según el tamaño del proyecto se empiezan a establecer los grupos de trabajo. Este proyecto de software cuenta con tres desarrolladores debido a su tamaño, por tanto son ellos mismos los encargados de establecer y ejecutar el plan de gestión de la configuración. En esta tabla se muestran los cargos de los desarrolladores del software dentro de esta actividad:




NOMBRE
CARGO
Eduardo Medina
SCMR
Fabiola Carrasco
Especialista Técnico, SQAR
Agustín Suaña
VR


El plan de gestión de la configuración está presente en las siguientes tareas:

Gestión del Proyecto.
Comunicación Gestión de Calidad.
Análisis de Requerimientos.
Diseño.
Implementación.
Verificación.
Implantación.
Gestión de configuración.
Control de cambios (SCM).
La siguiente tabla busca representar cómo se vinculan las actividades de SCM con los distintos roles en el proyecto.

Actividad
Rol Responsable
Otros roles involucrados
Planificar la configuración de SCM
SCMR


Definición de la línea base del proyecto
SCMR
SQAR, Especialista técnico.
Seguimiento de la línea base del proyecto
SCMR
Todos los integrantes.
Definición del ambiente controlado
SCMR*1
Especialista técnico.
Control de cambios
CCB*2, SCMR



Descripción de la versión

SCMR
Administrador, SQAR, Documentador de usuario, VR
Notas de la versión
SCMR
SQAR, VR
Realizar informe final de SCM
SCMR






Responsabilidades

El SCMR debe proveer la infraestructura y el entorno de configuración para el proyecto. Debe preocuparse porque todos los integrantes del grupo entiendan y puedan ejecutar las actividades de SCM que el Plan les asigna, así como asegurar que éstas sean llevadas a cabo. Seguir la línea base, controlando las versiones y cambios de ella, son tareas correspondientes a él. Debe definir y construir el Ambiente Controlado e informar al resto del equipo sobre la manera de usarlo.
 Otras actividades que conciernen al SCMR son:

Identificar los elementos de configuración, estableciendo así la línea base del proyecto.
Fijar una política de nomenclatura de los elementos de configuración para facilitar la identificación y ubicación de éstos en el proyecto.
Llevar a cabo el control de la configuración, estableciendo estándares y procedimientos a seguir con
respecto a los cambios para permitir un control de los mismos.
Proveer reportes de estado de la configuración mediante el seguimiento del historial de las revisiones y liberaciones.
Realizar auditorías de la línea base del software para verificar que el Sistema en desarrollo es consistente
y la línea base está bien definida.


Políticas, directivas y procedimientos aplicables
Respecto a los documentos en el repositorio de google docs, todos tienen derechos de administrador, osea, permiso de lectura, escritura y creación de nuevos documentos. Se tiene como política la total confianza en todos los integrantes del equipo.

Actividades de SCM
Identifica todas las actividades y tareas que se requieren para el manejo de la configuración del sistema. Estas deben ser tanto actividades técnicas como de gestión de SCM, así como las actividades generales del proyecto que tengan implicancia sobre el manejo de configuración.

Identificación de la configuración
Elementos de configuración
Para este proyecto se observa que los elementos de configuración no necesariamente se corresponden con los entregables definidos en el Modelo de Proceso y viceversa.
La decisión de cuáles de los entregables serán elementos de configuración será tomada por el SCMR, quién deberá tomar en cuenta qué elementos serán necesarios cuando se quiera recuperar una versión completa del sistema.
Se debe generar una línea base por iteración en cada Fase, de acuerdo a lo siguiente:
Los eventos que dan origen a la línea base.
Los elementos que serán controlados en la línea base.
Los procedimientos usados para establecer y cambiar la línea base.
La autorización requerida para aprobar cambios a los documentos de la línea base.

Nomenclatura de Elementos

En esta sección se especifican la identificación y descripción única de cada elemento de configuración.

Además se especifica cómo se distinguirá las diferentes versiones de cada elemento.
Para todos los elementos de configuración se les deberá agregar, después del nombre del mismo, información acerca del grupo al que corresponde el elemento y la versión del mismo.

 El formato para esta nomenclatura es: NomenclaturaGXvY.extensión, donde:

Nomenclatura es la especificada más abajo para cada elemento.
X es un número de 1 dígito que identifica al grupo.
Y indica la versión del elemento de configuración o entregable.
Extensión indica la extensión del elemento de configuración o entregable.

[Ejemplo: RQALSG1v2.doc, es como se deberá llamar el entregable "Alcance del Sistema" correspondiente al grupo 1 y cuya versión del documento es la 2.]

Para los entregables, se deberá identificar a qué fase e iteración corresponden en forma manual. Esto es: para los elementos bajo control de configuración se los almacenará de forma que se puedan recuperar dada la Fase e iteración a la que corresponden, y para los elementos que no se encuentran bajo control de configuración podrán ser almacenados por ejemplo en carpetas que identifiquen la Fase e iteración a la que pertenecen.
Se indica la siguiente nomenclatura para cada entregable en el modelo de proceso, según la disciplina (en caso que exista algún elemento de configuración que se agregue a los que se detallan abajo, se deberá incluir en las tablas siguientes de acuerdo a la disciplina a la que pertenece, indicando la nomenclatura usada):

Requerimientos:

Nomenclatura
Entregable
RQACT
Acta de Reunión de Requerimientos
RQDRQ
Especificación de Requerimientos
RQMOD
Modelo de Casos de Uso
RQRSU
Requerimientos Suplementarios
RQDVC
Documento de Validación con el Cliente
RQPIU
Pautas para Interfase de Usuario
RQRCA
Requerimientos Candidatos
RQALS
Alcance del Sistema
RQGLO
Glosario
RQOOMDO
Modelo de Dominio
RQOODRP
Documento de Requerimientos para el Prototipo
RQGXNOM
Nomenclatura


Diseño:

Nomenclatura
Entregable
DSMDI
Modelo de Diseño
DSARQ
Descripción de la Arquitectura
DSOOMDA
Modelo de Datos
DSOODDP
Documento de Diseño del Prototipo


Implementación:

Nomenclatura
Entregable
IMEDT
Estándar de Documentación Técnica
IMEI
Estándar de Implementación
IMPR
Prototipo
IMIIN
Informe de Integración
IMDT
Documentación técnica


IMIVU
Informe de Verificación Unitaria
IMOOPII
Plan de Integración de la Iteración
IMOOMIM
Modelo de Implementación
IMOOEJI
Ejecutable de la Iteración
IMOORRP
Reporte de Revisión por Pares
IMOOCVU
Clases de la Verificación Unitaria de Módulo
IMGXICO
Informe de Consolidación
IMGXEST
BC Con Estilos
IMGXCON
BC Consolidado
IMGXNUC
BC Núcleo
IMGXMOD
BC Módulo


Verificación:

Nomenclatura
Entregable
VRPVV
Plan de Verificación y Validación
VRDAP
Documento de Evaluación y Ajuste del Plan de V & V
VRPVI
Plan de Verificación de la Iteración
VRMCP
Modelo de Casos de Prueba
VRIVD
Informe de Verificación de Documento
VRIVI
Informe de Verificación de Integración
VRIVS
Informe de Verificación del Sistema
VRRPR
Reportes de Pruebas
VREV
Evaluación de la Verificación
VRIFV
Informe Final de Verificación


Implantación (IP):

Nomenclatura
Entregable
IPMSU
Materiales para Soporte al Usuario
(Se pueden usar sufijos para identificar cada ítem dentro del material Ej. IPMSUMU para Manual de Usuario)
IPMCA
Materiales para Capacitación
IPPS
Presentación del Sistema
IPPLA
Plan de Implantación
IPVPR
Versión del Producto
IPOOEDU
Estándar de Documentación de Usuario
IPOORFPA
Reporte Final de Pruebas de Aceptación



Gestión de Configuración y Control de Cambios (SCM):

Nomenclatura
Entregable
SCMPLA
Plan de Configuración
SCMMAC
Manejo del Ambiente Controlado
SCMGC
Gestión de Cambios
SCMRV
Registro de Versiones
SCMILB
Informe de la Línea Base del Proyecto
SCMIF
Informe Final de SCM


Gestión de Calidad (SQA)

Nomenclatura
Entregable
SQAPLA
Plan de Calidad
SQADAP
Documento de Evaluación y Ajuste del Plan de Calidad
SQARTF
Informe de RTF
SQAES
Entrega Semanal de SQA
SQAIR
Informe de Revisión de SQA
SQADV
Descripción de la Versión
SQANV
Notas de la Versión
SQAIF
Informe Final de SQA


Gestión de Proyecto (GP):

Nomenclatura
Entregable
GPPLA
Plan de Proyecto
GPISP
Informe de Situación del Proyecto
GPEM
Estimaciones y Mediciones
GPDRI
Documento de Riesgos
GPRAC
Registro de Actividades
GPIFP
Informe Final de Proyecto
GPARE
Acta de la Reunión de Equipo
GPPIT
Plan de la Iteración
GPPDE
Plan de Desarrollo
GPICF
Informe de Conclusiones de la Fase
GPPDIP
Presentación en Diapositivas del Proyecto
GPPDP
Presentación al Director del Proyecto
GPARD
Acta de la Reunión con el Director del Proyecto
GPOODAP
Documento de Evaluación y Ajuste al Plan de Proyecto
GPIARI
Acta de la Reunión de Integración


Comunicación (COM):

Nomenclatura
Entregable
COMDI
Documento Informativo
COMENS
Encuesta de Satisfacción del Cliente
COMEVS
Evaluación de Satisfacción del Cliente







Elementos de la Línea Base del Proyecto


FASE: [Fase]
ITERACIÓN: [Iteración]
Elemento
Descripción
Disciplina
[Nombre del elemento de la Línea Base]
[Descripción del elemento de la Línea Base]
[Disciplina a la que pertenece]















Recuperación de los Elementos de configuración

    CONFIGURACIÓN: Las características funcionales y físicas de una versión específica de hardware y elementos de software que combinados de acuerdo a procedimientos de construcción específicos cumplen un propósito particular.


Control de configuración

En esta sección se detallan las actividades de solicitud, evaluación, aprobación e implementación de cambios a los elementos de la línea base.
Los cambios apuntan tanto a la corrección como al mejoramiento.
El procedimiento que se describe a continuación es el que se utilizará cada vez que se precise introducir un cambio al sistema.
Se entiende por cambio al sistema, las modificaciones que afecten a la línea base del sistema, como pueden ser:

Cambios en los Requerimientos.
Cambios en el Diseño.
Cambios en la Arquitectura.
Cambios en las herramientas de desarrollo.
Cambios en la documentación del proyecto. (agregar nuevos documentos o modificar la estructura de los existentes)

Solicitud de cambios

Cuando se realiza la solicitud de un cambio, se actualiza el documento de “Solicitud de cambio” para registrar esta solicitud.
Se debe ingresar toda la información necesaria, detallada en el documento.


Evaluación de cambios o Análisis de Impacto

La evaluación del cambio involucra determinar qué es necesario hacer para implementar el cambio y la estimación de sus costos y plazos.



Se realiza en 2 pasos:

Planificación de la evaluación del cambio que involucra:
Revisar la solicitud de cambio para entender su alcance. (Si es necesario se discute con el originador para aclarar el alcance de lo propuesto y los motivos de la solicitud.
Determinar las personas del proyecto que deben realizar el análisis de evaluación del cambio e involucrarse.
Desarrollar un Plan para la evaluación del cambio.
Si el cambio involucra al Cliente, obtener el acuerdo de éste con el Plan.
Evaluar el cambio:
Dependiendo de las características del cambio, la evaluación del cambio puede ser realizada por el Administrador o ser delegado a otras personas del proyecto.
Se debe determinar el impacto en:
Los productos técnicos.
Los Planes de proyecto.
Los acuerdos con el cliente.
Los Riesgos del proyecto.


Se actualiza el documento "Gestión de cambios".

Aprobación o desaprobación de cambios

Se debe formar el "Comité de Control de Configuración".
La composición de este comité puede variar según el tipo de cambio y las líneas de trabajo involucradas en él.

Se sugieren como posibles integrantes:
Administrador (obligatorio)
Arquitecto (opcional)
Analista (opcional)
Implementador (opcional)
SCM (obligatorio)
Cliente (opcional)

Se define un comité de Control de Configuración de nivel superior, compuesto por el Gerente de proyecto, al cual se elevarán las solicitudes de cambios cuya aprobación o desaprobación no se pueda resolver por el primer comité.

Implementación de cambios

Una vez realizada la evaluación del cambio, se decide en qué momento implementarlo. Esta etapa involucra los procesos necesarios para implementar la solicitud y monitorear el progreso del trabajo.
Además se especificará el momento de liberación del cambio; así como también los responsables de las actividades que involucra el cambio.
Recordando que nos basamos en un proceso de desarrollo incremental e iterativo, donde en cada iteración se realizan tareas de Análisis de requerimientos, Diseño, Implementación y Verificación; se debe introducir el cambio en el área que lo originó y continuar con las actividades del ciclo (Requerimientos, Análisis, Diseño, Implementación, Verificación) que impactarán los elementos de la línea base correspondientes a cada actividad.

Estado de la configuración

Las actividades de control de estado son para reunir información y reportar el estado de los elementos de configuración.

Los reportes de estado se enviaran por correo a todos los integrantes. Además se guardará en el repositorio de google docs en el documento "Reporte de estado de configuración [fecha]" donde fecha tiene el formato ddmmaaaa.
La frecuencia no será fija por ahora. Se hará un reporte a pedido del administrador, o de algún otro integrante del equipo, o a criterio del SCMR.
Queda por definir:
1. Como la información será obtenida, guardada, procesada, y reportada.

En los reportes de estado de los elementos de configuración se debe incluir como mínimo la siguiente información:
Primera versión aprobada.
El estado de los cambios solicitados.
El estado de implementación de los cambios aprobados.

Auditorías y revisiones de configuración

Se realizarán auditorías de la línea base antes de una liberación de ésta o de una actualización de la versión de un componente prioritario de ésta.

Estas auditorías incluirán:
Objetivo: el objetivo de todas las auditorías es verificar que en un momento dado la línea base se compone de una colección consistente y bien definida de productos.
Elementos de configuración bajo auditoría: se elegirán uno o más elementos de configuración de mayor
prioridad en la línea base.
Agenda de auditorías: antes de la liberación o actualización.
Conducción: las auditorías serán dirigidas por el SCMR.
Participantes: SCMR y los autores de los elementos de configuración a auditar.
Documentos Requeridos: Documentos de SCR y reportes de estado de la configuración generados.
Reportes de Deficiencias y Acciones Correctivas: determinadas por los participantes.
Criterio de Aprobación: lo determina el SCMR.

Control de Interfases

Las actividades de Control de Interfases controlan los cambios a los elementos de configuración del proyecto, que modifican las interfaces con elementos fuera del alcance del Plan.
Este control será llevado por el SCMR como parte del control de la configuración.



Calendario

Actividad
Depende de:
Comienzo
Planificar el Plan de Configuración.
Nada
En curso.
Definir Línea Base del Proyecto
Plan de Configuración.
Semana 4 probablemente.

Realizar informe final de SCM
Gestión de cambios Inf. de Línea Base del proyecto.
Plan de Configuración.

Semana 14
Implementación del control de cambios.


Semana 5 probablemente.

Comienzo y fin de auditorías: Se realizará una auditoría todos los domingos, antes de cada entrega.

Recursos
A la fecha (23/09/2023) se utilizarán las herramientas provistas por google docs. Esto es, un repositorio que permite almacenar y editar documentos de texto. Para acceder solo se necesita un navegador web y conexión a internet.
Se asume que no se necesita capacitación para usar las herramientas, debido al perfil de los integrantes del equipo.

Se está viendo la posibilidad de usar Git/Github para la gestión del código fuente y versionamiento de entregables.

Para la documentación, se usará Sharepoint

Mantenimiento del Plan de SCM
El responsable de monitorear el Plan de Configuración es el SCMR.
Se hará una revisión del Plan de Configuración al comienzo de cada iteración. En caso de que haya modificaciones se comunicarán por correo a todos los integrantes.
