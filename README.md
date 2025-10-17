# Ponderada: Blink com Arduino

Realizei a atividade de Blink utilizando o Arduino UNO, começando pelo LED interno no pino 13 e depois simulando um LED externo no Tinkercad. O objetivo foi compreender o funcionamento básico das funções `setup()` e `loop()` e o uso dos pinos digitais como saída, criando um efeito de luz piscando.

link para o tinkercad: https://www.tinkercad.com/things/4Yx4MwZrYBY-magnificent-elzing

O código utilizado para o LED interno foi:

```cpp
void setup() {
  pinMode(led, OUTPUT);
}

void loop() {
  digitalWrite(led, HIGH);
  delay(1000);
  digitalWrite(led, LOW);
  delay(1000);
}
```
