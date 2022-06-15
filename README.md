# Hola Mundo
-----> También usado como mis apuntes virtuales del curso de innovacciónvirtual<---------

Autor: Pablo Marroquín.
Fecha: 08 de junio de 2022.

Módulo 1
.
--- Apuntes ---
.
.....Unidad 1.....
.
.
Azure es un servicio para la presencia empresarial ofreciendo servicios basados en la nube:
-Almacenamiento remoto, hospedaje de bases de datos y administración centralizada de cuentas
-Tambien IA e IoT
.
{ ¿De qué va Aspectos básicos de Azure?
6 rutas de aprendizaje 
1       servicios centrales de proceso,
 2      red,
  3     almacenamiento y bases de datos de Azure,
   4    aprender sobre los procedimientos recomendados de seguridad en la nube
    5   explorar la vanguardia en IoT
      6 aprendizaje automático
.      
Contenidos de Examen 
.
Área de dominio AZ-900

Peso

Descripción de los conceptos de la nube

20-25 %

Descripción de los servicios básicos de Azure

15-20 %

Descripción de las principales soluciones y herramientas de administración de Azure

10-15 %

Descripción de las características de seguridad general y de seguridad de red

10-15 %

Descripción de las características de identidad, gobernanza, privacidad y cumplimiento

20-25 %

Descripción de Microsoft Cost Management y los acuerdos de nivel servicio

10-15 %
.
.....Unidad 2.....
.
¿Qué es la informática en la nube?

-  Es la entrega de servicios informáticos a través de Internet, lo que se conoce como la nube. Estos servicios incluyen servidores, almacenamiento, bases de datos, redes, software, análisis e inteligencia. La informática en la nube ofrece una innovación más rápida, recursos flexibles y economías de escala.
-  
¿Por qué suele ser más barato usar la informática en la nube?

Normalmente solo se paga por los servicios en la nube que se usan, lo que permite:
- Reducir los costos operativos.
-Ejecutar la infraestructura de forma más eficaz.
-Escalar a medida que cambien las necesidades empresariales.

¿Por qué debería migrar a la nube?

En este mundo digital cambiante, surgen dos tendencias:
- Los equipos proporcionan nuevas características a los usuarios a velocidades récord.
- Los usuarios esperan una experiencia cada vez más amplia y envolvente con sus dispositivos y con el software.
Para desarrollar los servicios y ofrecer experiencias de usuario innovadoras y novedosas más rápidamente, la nube proporciona acceso a petición para:
- Un grupo casi ilimitado de componentes de proceso, almacenamiento y redes sin procesar.
- Reconocimiento de voz y otros servicios cognitivos que ayudan a hacer que su aplicación destaque entre la multitud.
- Servicios de análisis que proporcionan datos de telemetría desde el software y los dispositivos.
.
.....Unidad 3.....
.
¿Qué es azure?
Azure es un conjunto de servicios en la nube en expansión constante que ayudan a la organización a cumplir los desafíos empresariales actuales y futuros. Azure le ofrece la libertad de compilar, administrar e implementar aplicaciones en una red global masiva mediante sus herramientas y plataformas favoritas.
.
.....Unidad 4.....
.
Paseo por los servicios de Azure
.
Modulo 2
.
Nube pública: Servicios disponibles para cualquiera, usando los servicios de nube de teceros
No hay gastos para escalar verticalmente
Solo se paga por lo que se usa
Nube privada: recursos informáticos de uso exclusivo de una organización o empresa, que puede tener su propio centro de datos o estar hospedad por un servicio de terceros
Las org, tienen control de los recursos y seguridad


Son responsables de las actualizaciones y mantenimiento
Nube hibrida: Permite compartir datos entre la pública y privada
Máx flexibilidad
Las organizaciones determinan dónde se van a ejecutar sus aplicaciones.
Las organizaciones controlan la seguridad, el cumplimiento o los requisitos legales.

Gastos de capital CapEx
Gastos operativos OpEx
Dicho de otra forma, si Tailwind Traders es dueño de su infraestructura, comprará equipos que se incluirán como recursos en su balance de cuentas. Dado que se ha realizado una inversión de capital, los contables clasifican esta transacción como CapEx. Con el tiempo, a fin de contabilizar la duración útil limitada de los activos, estos se deprecian o se amortizan.

Los servicios en la nube, por otro lado, se clasifican como OpEx debido a su modelo de consumo. No hay ningún recurso que Tailwind Traders pueda amortizar, y su proveedor de servicios en la nube (Azure) administra los costos asociados con la compra y la vida útil del equipo físico. En consecuencia, los gastos de explotación tienen un impacto directo en el beneficio neto, la base imponible y los gastos asociados en el balance contable.

Modelos de Servicios en la Nube
IaaS

Infraestructura como servicio

Este modelo de servicio en la nube es el más similar a la administración de servidores físicos; un proveedor de servicios en la nube mantendrá actualizado el hardware, pero el mantenimiento del sistema operativo y la configuración de red serán su responsabilidad como inquilino de nube.

PaaS

Plataforma como servicio

Este modelo de servicio en la nube es un entorno de hospedaje administrado. El proveedor de servicios en la nube administra las máquinas virtuales y los recursos de red, y el inquilino de nube implementa sus aplicaciones en el entorno de hospedaje administrado.}

SaaS

Software como servicio

En este modelo de servicio en la nube, el proveedor de servicios en la nube administra todos los aspectos del entorno de la aplicación, como las máquinas virtuales, los recursos de red, el almacenamiento de datos y las aplicaciones. El inquilino de nube solo necesita proporcionar sus datos a la aplicación administrada por el proveedor de servicios en la nube.


Módulo 3
.
.
U2.
 Recursos: Los recursos son instancias de servicios que puede crear, como máquinas virtuales, almacenamiento o bases de datos SQL.
 Grupos de recursos: Los recursos se combinan en grupos de recursos, que actúan como contenedor lógico en el que se implementan y administran recursos de Azure como aplicaciones web, bases de datos y cuentas de almacenamiento.
 Suscripciones: Una suscripción agrupa las cuentas de usuario y los recursos que han creado esas cuentas de usuario. Para cada suscripción, hay límites o cuotas en la cantidad de recursos que se pueden crear y usar. Las organizaciones pueden usar las suscripciones para administrar los costos y los recursos creados por los usuarios, equipos o proyectos.
 Grupos de administración: Estos grupos le ayudan a administrar el acceso, las directivas y el cumplimiento de varias suscripciones. Todas las suscripciones de un grupo de administración heredan automáticamente las condiciones que se aplican al grupo de administración.

Modulo 4

Azure Storage: para migrar aplicaciones a un servicio basado en la nube
Disk Storage: Maquina virtual de Azure que usa discos de almacenamiento y proceso de datos emulando a los de la realidad SSD, HDD y Ultra disk, requiere de la administración del desarrollador
Blob Storage: No hay restricción en cuanto al tipo de dato que contiene, cargas simultáneas, vidios etc, no requiere de administración, es GOD para streaming con 8TB de datos para VM
Azure Files: Es un recurso compartido de almacenamiento de archivos
Niveles de acceso de Blobs: Frecuente, Esporádico y archivo
.
Modulo 5
.
    Cosmos DB: es un servicio de base de datos de varios modelos distribuido globalmente. almacena los datos en formato de secuencia de registro de átomos (ARS). Sirve para manejar la API con la que se sientan mas comodos, en el proceso de migración de bases de datos.
    SQL Database:es una base de datos de alto rendimiento, confiable, totalmente administrada y segura. Puede usarla para compilar aplicaciones y sitios web controlados por datos en el lenguaje de programación que prefiera sin necesidad de administrar infraestructura. (PaaS). Realizar practica correspondiente a creación de base de datos SQL
   Azure Database for MySQL: es un servicio de bases de datos relacionales en la nube, y se basa en el motor de base de datos de MySQL Community Edition, alta disponibilidad, el servicio se encarga de muchos de los procedimientos
   Azure Database for PostgreSQL:Se destaca la opción de un solo servidor, ofrece tres planes de tarifa; básico, de uso general y optimizado para memoria.
   Hiperescala (Citus): escala horizontalmente las consultas entre varias máquinas mediante el particionamiento.admite aplicaciones multiinquilino, análisis operativos en tiempo real y cargas de trabajo transaccionales de alto rendimiento. 
   Azure SQL Managed Instance
   análisis y macrodatos
   Azure Synapse Analytics: Tiene una experiencia unificada para ingerir, preparar, administrar y servir datos para las necesidades inmediatas de inteligencia empresarial y aprendizaje automático.
   Azure HDInsight: admite una amplia gama de escenarios, como la extracción, la transformación y la carga de datos (ETL), el almacenamiento de datos, el aprendizaje automático e IoT.
   Azure Databricks: le ayuda a descubrir información de todos los datos y a crear soluciones de inteligencia artificial. 
    Análisis con Azure Data Lake: El servicio de análisis puede administrar trabajos de cualquier escala al instante, simplemente estableciendo el ajuste adecuado. 
