# 10 days intership at Jyothi Engineering college


# Day-2 
## Tinker cad program 1-LED blinking

![no photo](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshidtinkercad.png)


# Day-2 
## Tinker cad program 2-LED blinking with a switch

[thikercad](https://www.tinkercad.com/things/8V7fwjLeWW0-ledbling/editel)

![no photo](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshidtinkecade2.png)


# day-3
## tinker cad program 3-LED blinking use ic 7408

[thinkercade](https://www.tinkercad.com/things/ezCf7UJyaQp-led-blinking-use-ic-7408/editel)

[schematic viewof exp 3](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshidtinkecade3schematicview.png)

![no photo](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshidtinkecade3.png)


# day-3
## thinker cad program 4

[thinkercade](https://www.tinkercad.com/things/1q30jd88bha-led-blink-with-arduino/editel)

![photo is loading](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshidtinkcad4.png)
 
## Code for LED blink with arduino 
```
// C++ code
//
/*
  This program blinks pin 13 of the Arduino (the
  built-in LED)
*/

void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  // turn the LED on (HIGH is the voltage level)
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  // turn the LED off by making the voltage LOW
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```
# day-3
## thinker cad program 5

[thinkercade](https://www.tinkercad.com/things/lFIvhIu467Z-2-led-blinhing-useing-arduino/editel)

![photo is loading](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshidtinkercad5.png)


 code for led blink with arduino 
 ```
 // C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(8, OUTPUT);
}

void loop()
{
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
 ```
# day-3
## thinker cad program 6
[thinkercade](https://www.tinkercad.com/things/5qFEsArirTq-5-led-with-using-arduino/editel)

![photo is loading](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshid6.png)

## Code of this experiment
```
e(7, LOW);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(4, HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(4, LOW);
  delay(300); // Wait for 1000 millisecond(s)
}// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(8, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(4, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(12, LOW);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(8, HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(7, HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrit
}
```

# Day-3
## Thinker cad program 7
### 7 segment display

[thinkercade](https://www.tinkercad.com/things/aK3rFULNbeh-7-segment-display/editel)

![photo is loading](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshidthinkercad7.png)

# Day-4
## make a program using blockly google developers
![photo is loading](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshidday4blockly2.png)https://www.tinkercad.com/things/6y1J4Emvzuo-display-0-to-9-using-arduino/editel

# Day-5
## Thnker cad program 1
### interfacing potentiometer with arduino
[thinkercade](https://www.tinkercad.com/things/fVyJBzGFkDy-interfacing-potentiometer-with-arduino/editel)

![photo is loading](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshidday5program1.png)
### code of the program
```
const int potPin=A0;

void setup() {
  Serial.begin(9600);
}
void loop(){
  int potValue = analogRead(potPin);
  Serial.println(potValue);
  delay(100);
}
```
# Day-5
## TINKERCAD PROGRAM 2
### EXPERIMENT NAME:DISPLAY 0 to 9 USING ARDUINO
[The circuit design Link of Tinkercad experiment 2](https://www.tinkercad.com/things/6y1J4Emvzuo-display-0-to-9-using-arduino/editel)
![photo is loading](https://github.com/muhammedanshid/10-days-internship/blob/main/img/anshid%20DISPLAY%200%20to%209%20USING%20ARDUINO%20Tinkercad.png)
### code of this program is 
```
// C++ code
//
void setup(){
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
  pinMode(10, OUTPUT);
  pinMode(9, OUTPUT);
  pinMode(8, OUTPUT);
  pinMode(7, OUTPUT);
}
void loop()
{
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,HIGH);
  delay(2000);
  digitalWrite(13,HIGH);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(2000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,HIGH);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,HIGH);
  digitalWrite(7,LOW);
  delay(2000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,LOW);
  delay(2000);
  digitalWrite(13,HIGH);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(2000);
  digitalWrite(13,LOW);
  digitalWrite(12,HIGH);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(2000);
  digitalWrite(13,LOW);
  digitalWrite(12,HIGH);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(2000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(2000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(2000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(2000);
} 
```
