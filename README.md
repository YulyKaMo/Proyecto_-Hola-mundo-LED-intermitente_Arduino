# 💡 Proyecto Hola mundo. LED intermitente Arduino

Esta práctica introductoria permite aprender a programar y controlar dispositivos electrónicos. Consiste en hacer que un LED se encienda y apague repetidamente, simulando un parpadeo, generalmente con un intervalo de tiempo definido entre cada cambio de estado. Es el equivalente al "Hola Mundo" en otros lenguajes de programación, mostrando la capacidad básica de interactuar con el hardware.

## 🎯 Objetivo

Familiarizarse con el entorno de desarrollo, la placa de control (Arduino) y comprender los conceptos básicos de entrada/salida digital mediante el control de un LED.

## 🧠 Conceptos aprendidos- Temáticas

![Temáticas proyecto Hola mundo—LED intermitente_Arduino](img/Img01_Tematicas.jpg)

## 🛠️ Materiales

![Materiales proyecto Hola mundo—LED intermitente_Arduino](img/Img02_Materiales.jpg)

## 🔌 Esquema de conexión

![Plano proyecto Hola mundo—LED intermitente_Arduino](img/Img03_Plano.jpg)

## 📄 Codigo para Arduino
```
#define LedA 13;

void setup() 
{
 pinMode(LedA,OUTPUT); 
}

void loop() 
{ 
 digitalWrite(LedA,HIGH); 
 delay(1000); // Temporiza un segundo (1s = 1000ms)
 digitalWrite(LedA,LOW); 
 delay(1000); 
}
```

## 📌 Notas adicionales

* Se puede usar otro pin digital (por ejemplo, 8) cambiándolo también en el código.
* El valor en milisegundos de delay() controla la velocidad de parpadeo del LED.
