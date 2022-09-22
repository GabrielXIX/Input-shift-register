# 74HC165 Input Shift Register (PISO)
## Componente de registro de desplazamiento

![image](https://user-images.githubusercontent.com/65438145/190032889-b1f6ec5d-6258-45e0-b733-44f278f6d087.png)

### Definición y función
Los registros de desplazamiento son circuitos integrados secuenciales que tienen la capacidad de almacenar y transferir información para obtener una salida de datos. Estos funcionan mediante un conjunto de flip-flops y compuertas que realizan una transición con una señal de reloj. Estos componentes se usan de almacenamiento temporal en un grupo de bits sobre los que se realizará un procesamiento y para aumentar las entradas digitales de cualquier microcontrolador.

### Tipos de registros de desplazamiento
- Serial-paralelo: Los datos entran uno por uno y salen de forma paralela

![image](https://user-images.githubusercontent.com/65438145/191808896-2686de2a-9465-493f-808b-d88502abf474.png)

- Paralelo-serial: Los datos entran de forma paralela y salen uno por uno

![image](https://user-images.githubusercontent.com/65438145/191808741-0e35710b-80f9-48d2-9048-c9e1a85384cd.png)

### Registro de desplazamiento *74HC165*
Este registro de desplazamiento capaz de transferir datos de forma Paralelo-serial y serial-serial de 8 bits. Dependiendo de qué pines tengan un alto o bajo voltaje se realizan diferentes operaciones como la carga asíncrona o la inhibición del reloj.

#### Ejemplo de carga de datos

![image](https://user-images.githubusercontent.com/65438145/191815895-b140d741-06b3-47db-b799-2a77ef3b7953.png)

#### Asignación de pines

![image](https://user-images.githubusercontent.com/65438145/190033149-8e9e0418-f9fd-4633-a2ec-519b9e5b69f3.png)

### Aplicaciones de los registros de desplazamiento

- Multiplicador serie
- Conversión de formato paralelo a serie para transferencia de datos entre dispositivos
- Utilizarlo como línea de retardo para entregar una señal que se retrasa con respecto a cuando se genera

### Referencias
- REGISTROS DE DESPLAZAMIENTO. Fundamentos de Sistemas Digitales. Recuperado de http://solano.orgfree.com/DISE%D1O%20DIGITAL%20CON%20VHDL/Registros.pdf
- Unit Electronics. 74LS165 Registro de Desplazamiento SN74LS165N. Recuperado de https://uelectronics.com/producto/74ls165-registro-de-desplazamiento-sn74ls165n/#:~:text=El%2074LS165%20se%20puede%20conectar,de%20desplazamiento%20puedes%20verlos%20Aquí.
- Registros de desplazamiento. Recuperado de https://personales.unican.es/manzanom/planantiguo/edigitali/REGG4.pdf
- EcuRed. Registro de desplazamiento. Recuperado de https://www.ecured.cu/Registro_de_desplazamiento
- SISO vs SIPO vs PISO vs PIPO-difference between SISO,SIPO,PISO,PIPO shift registers. (2012). Recuperado de https://www.rfwireless-world.com/Terminology/SISO-vs-SIPO-vs-PISO-vs-PIPO-shift-register-types.html
- Sergio Noriega. (2009). Registros de Desplazamiento. Introducción a los Sistemas Lógicos y Digitales. Recuperado de https://catedra.ing.unlp.edu.ar/electrotecnia/islyd/apuntes/Tema%206%20Registros%20de%20Desplazamiento%202009.pdf
- Kripkit. Registro de desplazamiento. Recuperado de https://kripkit.com/registro-de-desplazamiento/
- Registro de desplazamiento. Recuperado de https://es.wikipedia.org/wiki/Registro_de_desplazamiento

