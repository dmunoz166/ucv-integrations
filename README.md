# POC - DEMO UCV
https://github.com/codeaprendiz/devops-essentials
Velocity se integra a Jenkins y/o  Jira

- [Velocity github](https://urbancode.github.io/velocity-info/)

https://www.ibm.com/docs/en/urbancode-velocity/1.5.x?topic=upgrading-installing-standard-edition

Jira: https://confluence.atlassian.com/adminjiraserver/getting-started-with-jira-data-center-on-aws-938846966.html

[DevOps Query Language](https://ibm.webex.com/ibm/url.php?frompanel=false&gourl=https%3A%2F%2Fwww.ibm.com%2Fdocs%2Fen%2Furbancode-velocity%2F1.4.x%3Ftopic%3Dmanagement-devops-query-language)

Como hacer consultas a traves de query para las integraciónes (Job en jenkins, etc)

## JKE-App-1
Se realizara la integración de este repositorio de github con UCV

## Personas
Roberto Chiabra Valera (Arquitecto de la cuenta IBM):



### Actividades Realizadas
1. Conexión de UCV con Jira ( Van de la mano del vsm.json,Falta revisar por que algunos WIs "En curso" no se ven en la interfaz de ucv)
2. Integración con Github (Se ven los PR y el estado de cada uno como cuadrados en ucv)
3. Integración con Pipeline de Jenkins (Almenos como invocar UCV desde el pipeline para que se vea como se avanza en el despliegue, hace falta corregir pues no logre que jenkins recibiera el numero de la versión a desplegar desde ucv si no que hay que especificar desde el pipeline, se ven como triangulos en la interfaz)
4. Integración con UCD (Se logro desplegar una snapshot de un proceso a partir de una app simple en UCD)
5. Se logro realizar el despliegue desde UCD y el mismo UCV
