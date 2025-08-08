# Proyecto_ Hola mundo—LED intermitente_Arduino

void setup() 
{
 pinMode(13,OUTPUT); 
}

void loop() 
{ 
 digitalWrite(13,HIGH); // Enciende el LED
 delay(1000); // Temporiza un segundo (1s = 1000ms)
 digitalWrite(13,LOW); // Apaga el LED
 delay(1000); // Temporiza un segundo (1s = 1000ms)
}
