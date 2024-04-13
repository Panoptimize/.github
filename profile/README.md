# Panoptimize
## Objetivo
El proyecto se centra en el uso de AWS Connect para mejorar las operaciones de un contact center, aprovechando las capacidades de computación en la nube para optimizar la gestión de las interacciones con los clientes. AWS Connect es una solución basada en la nube que ofrece servicios de centro de contacto, facilitando la creación de experiencias de cliente personalizadas con tecnología de inteligencia artificial y análisis en tiempo real. 

El objetivo del proyecto es implementar una solución que permita a las agencias mejorar su eficiencia operativa y la calidad del servicio al cliente, utilizando las herramientas avanzadas que AWS Connect ofrece. Se trabajará en personalizar flujos de trabajo, análisis de voz y datos en tiempo real, y en integrar sistemas existentes para dar una visión 360 grados del cliente, en un marco que cumpla con los requisitos funcionales y no funcionales especificados en los documentos proporcionados. 

## Alcance
Definimos los siguientes requerimientos funcionales

| ID     	| Stakeholder                    	| Descripción                                                                                                       	| Prioridad  	|
|--------	|--------------------------------	|-------------------------------------------------------------------------------------------------------------------	|:----------:	|
| RF01   	| Directivo, Supervisor, Agente  	| Deberá autentificarse.                                                                                            	|    Alta    	|
| RF02   	| Directivo                      	| Deberá poder configurar y gestionar los accesos de usuario y permisos dentro de la plataforma.                    	|   Media    	|
|  RF03  	|           Supervisor           	| Deberá poder visualizar el rendimiento de los agentes en tiempo real a través de un dashboard.                    	|    Alta    	|
|  RF04  	|           Supervisor           	| Deberá tener acceso al histórico entre agente y cliente.                                                          	|    Baja    	|
|  RF05  	|           Supervisor           	| Podrá consultar una lista ordenada de las interacciones del día por cada agente.                                  	|    Alta    	|
|  RF06  	|           Directivo            	| Podrá acceder a un listado donde se visualice el desempeño de los supervisores.                                   	|    Baja    	|
|  RF07  	|           Supervisor           	| Podrá ver el desempeño general demostrado durante el día/semana.                                                  	|   Media    	|
|  RF08  	|           Supervisor           	| Deberá poder visualizar la distribución gráfica de los agentes en el área.                                        	|    Alta    	|
|  RF09  	|           Supervisor           	| Deberá poder realizar cambios a la distribución actual de los agentes en el piso digital.                         	|   Media    	|
|  RF10  	|           Supervisor           	| Deberá tener un área con acciones recomendadas según el rendimiento actual de los agentes.                        	|    Alta    	|
|  RF11  	|           Supervisor           	| Podrá visualizar el historial de check-in y check-out de los agentes.                                             	|   Media    	|
|  RF12  	|           Supervisor           	| Tendrá acceso a una lista de todos los agentes activos e inactivos.                                               	|    Alta    	|
|  RF13  	|           Supervisor           	| Podrá observar tiempo de trabajo que le resta a cada agente.                                                      	|    Alta    	|
|  RF14  	|           Supervisor           	| Deberá de poder visualizar los datos demográficos de cada agente.                                                 	|   Media    	|
|  RF15  	|           Directivo            	| Deberá de poder visualizar detalles sobre sus supervisores (detalles de contacto, nombre, etc.)                   	|    Baja    	|
|  RF16  	|           Supervisor           	| Podrá ver la lista priorizada de los agentes que han pedido ayuda.                                                	|    Alta    	|
|  RF17  	|           Supervisor           	| Deberá ser notificado sobre los agentes, que requieren de una transferencia.                                      	|   Media    	|
|  RF18  	|           Supervisor           	| Podrá evaluar la retroalimentación proporcionada por el modelo de inteligencia artificial.                        	|    Baja    	|
|  RF19  	|           Supervisor           	| Deberá poder filtrar la información desplegada en los dashboards para reconocer patrones de trabajo y eficiencia  	|    Alta    	|
|  RF20  	|           Supervisor           	| Podrá descargar un reporte del rendimiento de un agente en particular o todo el conjunto de agentes.              	|   Media    	|
| RF21   	|           Supervisor           	| Deberá ser notificado cuando el nivel de temperatura es inusual en una interacción.                               	|    Alta    	|
| RF22   	|           Supervisor           	| Deberá ser notificado cuando el tiempo que dura una interacción es inusual.                                       	|    Alta    	|
|  RF23  	|           Supervisor           	| Tendrá acceso a una clasificación ordenada de mayor a menor rendimiento entre los agentes.                        	|   Medio    	|
|  RF24  	|             Agente             	| Podrá mandar una solicitud de apoyo al supervisor, cuando se encuentre en una interacción                         	|    Baja    	|
|  RF25  	|             Agente             	| Deberá responder una encuesta de su servicio cuando termine una interacción                                       	|    Baja    	|
|  RF26  	|             Agente             	| Podrá ver la temperatura de su interacción.                                                                       	|    Baja    	|
|  RF27  	|             Agente             	| Podrá consultar la información general sobre la interacción actual.                                               	|    Baja    	|
|  RF28  	|           Directivo            	| Podrá personalizar la encuesta de cierre de las interacciones de los agentes                                      	|    Baja    	|
|  RF29  	|           Supervisor           	| Deberá ser notificado cuando el agente mande una solicitud de apoyo                                               	|   Media    	|

## Entregables
1. Código fuente 
3. Demostración de funcionamiento 
4. SQAP 
5. Documentación base (SRS) 
6. Plan de proyecto
