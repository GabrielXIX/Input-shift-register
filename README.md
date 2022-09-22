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
