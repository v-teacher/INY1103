# INY1103 - FUNDAMENTOS CLOUD II

<p align="left" style="text-align:left;">
  <a href="https://www.duoc.cl/">
    <img alt="Github Universe" src="img/logo.png" width="1040"/>
  </a>
</p>


## ANTECEDENTES GENERALES

<p align="justify"> Fundamentos Cloud II es una asignatura de especialidad ubicada en el segundo semestre del itinerario formativo de la carrera de Ingeniería en Infraestructura Tecnológica/Técnico en Infraestructura Tecnológica, dentro de la línea formativa Fundamentos Cloud Computing. </p>

<p align="justify"> Su propósito es que los/las estudiantes apliquen los principios del Cloud Computing, orientados a la administración eficiente, segura y escalable de recursos digitales.</p>

#### Objetivo del repositorio

<p align="justify"> Este es un repositorio de recursos de scritps u otros archivos útiles o necesarios para desarrollo la clase.

## URLs de de referencia o utilidad

##### Reference for sql script

- [Create Table SQL](https://www.geeksforgeeks.org/sql-create-table/)
- [Select SQL](https://www.geeksforgeeks.org/sql-select-query/)


## ACTIVIDADES

## User data
#### ANTECEDENTES GENERALES

El [user data](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/user-data.html) de ![AWS](https://img.shields.io/badge/-AWS-FF9900?style=flat-square&logo=aws&logoColor=white) es un conjunto de instrucciones que se puede proporcionar al iniciar una instancia de Amazon EC2 para automatizar tareas de configuración. Estas instrucciones pueden ser scripts en shell, comandos de configuración, o scripts en otros lenguajes que se ejecutan al inicio de la instancia. El User Data se usa comúnmente para:

1. **Instalación de software**: Automáticamente instalar paquetes y aplicaciones necesarios.
2. **Configuración del sistema**: Realizar ajustes de configuración en el sistema operativo o en aplicaciones.
3. **Descarga de archivos**: Obtener archivos necesarios desde S3 u otros lugares.
4. **Configuración de servicios**: Iniciar y configurar servicios que deben ejecutarse en la instancia.

El User Data se ejecuta una vez al iniciar la instancia por primera vez. Sin embargo, se puede configurar para que se ejecute en cada arranque reiniciando la instancia. Esta funcionalidad es útil para la gestión de infraestructura como código, asegurando que las instancias se configuren automáticamente de manera consistente.

#### REQUERIMIENTOS PARA ESTA ACTIVIDAD

Usar los scripts indicados por su docente para las [actividades de la clase.](
https://github.com/Fundacion-Instituto-Profesional-Duoc-UC/INY1103/blob/main/user_data_ea_3.2.sh
)

Ejemplos de scripts de [user data](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/user-data.html) que se pueden utilizar son los ofrecidos por la [documentación de AWS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/user-data.html#user-data-shell-scripts).


#### DESARROLLO DE ACTIVIDAD

Para más detalles visite el laboratorio de ejecución indicado por su docente.

## AWS Lambda
#### ANTECEDENTES GENERALES

En esta práctica, crearás una función AWS Lambda que se activará cada minuto mediante un evento de Amazon EventBridge. La función, con un rol de AWS IAM, detendrá una instancia de Amazon EC2 en tu cuenta de AWS.

#### REQUERIMIENTOS PARA ESTA ACTIVIDAD

Para el desarrollo de esta actividad se requiere el script lambda_function.py alojada en la raíz de este repositorio.

#### DESARROLLO DE ACTIVIDAD

Esta actividad consiste en:
1. Crear una función de Lambda
2. Configurar el desencadenador
3. Configurar la función de Lambda
4. Verificar que la correcta llamada de función de Lambda

Para más detalles visite el laboratorio de ejecución indicado por su docente. 

## CONTRIBUCIONES

Contribuciones son bienvenidas! Revisa nuestra [Guía de Contribuciones](./docs/CONTRIBUTING.md)

##### Reference for Gitflow

- [Flujo de trabajo de Gitflow](https://www.atlassian.com/es/git/tutorials/comparing-workflows/gitflow-workflow)

<!-- Todos/das son bienvenidos/das a colaborar aquí usando las prácticas del Gitflow. Los cambios a la rama main deben ser siempre a través de la aprobación de Pull Request. </p> -->

## CÓDIGO DE CONDUCTA

👋 Por favor, contribuye con amabilidad. Revisa nuestro [Código de Conducta](./docs/CODE_OF_CONDUCT.md)
