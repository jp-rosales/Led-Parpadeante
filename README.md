# Led-Parpadeante
## Juan Pablo Rosales - 2025
### Descripción
Proyecto simple de Arduino para encender y apagar un LED con Arduino
### Objetivo
Aprender funcionamiento básico de Arduino y del LED
### Materiales
-Arduino Uno  
-LED  
-Resistencia 220Ω  
-Cables  
-Protoboard  
### Código
**Archivo Principal:** led_parpadeante.ino  
int led = 13;

void setup() {
  pinMode(led, OUTPUT);
}

void loop() {
  digitalWrite(led, HIGH);
  delay(1000);
  digitalWrite(led, LOW);
  delay(1000);
}


