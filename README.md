# Proyecto_ Hola mundo—LED intermitente_Arduino


#define LedA 13

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
