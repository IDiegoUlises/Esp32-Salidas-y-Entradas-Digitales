# Esp32 Puertos Digitales
<img src="https://github.com/IDiegoUlises/Esp32-Puertos-Digitales/blob/main/Images/ESP32-DOIT-DEVKIT.jpg" width="1000" height="400" />

* **Tiene 30 puertos**
* **Voltaje es de 0 a 3.3 Volt**


### Conexion Puerto Digital
<img src="https://github.com/IDiegoUlises/Esp32-Puertos-Digitales/blob/main/Images/Apagar-y-prender.jpg" width="500" height="500" />

### Usando Puerto Digital Para Parpadeo de Led
```c++
int led = 23;

void setup()
{
  pinMode(led, OUTPUT);
}

void loop()
{
  digitalWrite(led, HIGH);
  delay(1000);
  digitalWrite(led, LOW);
  delay(1000);
}
```
