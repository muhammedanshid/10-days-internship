# Day-10
## last day we make and Design the Light Controlled Street light as project in thinker cad
### [project link in thinker cad](https://www.tinkercad.com/things/9A8lrZIFfTY-light-controlled-street-light-project/editel)
#### code of this project
```
int sensorValue = 0;
void setup()
{
  pinMode(A0, INPUT);
  pinMode(9, OUTPUT);
  Serial.begin(9600);
}
void loop()
{
  // read the value from the sensor
  sensorValue = analogRead(A0);
  // print the sensor reading so you know its range
  Serial.println(sensorValue);
// map the sensor reading to a range for the LED
  analogWrite(9, map(sensorValue, 0, 1023, 0, 255));
  delay(100); // Wait for 100 millisecond(s)
}
```

