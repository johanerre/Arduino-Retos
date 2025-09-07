# PASO A PASO EJERCICIO I
Se requiere de el encendido de un led mediante el uso de un pulsador, en este caso, debe encender y apagar cuando se presione y si se vuelve a presionar debe apagarse.

## Definición de variables:

Se definen dos variables de tipo entero, una para el led y otra para el pulsador. Luego dos de tipo Booleano para los estados del pulsador.

const int Pul = 2;   
const int Led = 13;     
bool estadoLED = LOW;     
bool Uestado = HIGH; 