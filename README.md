# Motor-drive-design-and-implementation-for-two-wheel-robot-base

" I used tinkercad website online to design it "

This circuit design moving two motors using H brage l298.

The Circuit consists of :

1- Arduino.

2- one H brage l298.

3- one battery 9 volts.

4- two DC Motors.

![Screen Shot 2021-08-05 at 6 02 40 PM](https://user-images.githubusercontent.com/85816257/128373256-bcd4019f-2879-432a-b668-38bf5f1ca134.png)

# C Of The Circuit :

void setup() { pinMode(11, OUTPUT); pinMode(10, OUTPUT); pinMode(7, OUTPUT); pinMode(6, OUTPUT); }

void loop() { digitalWrite(11, HIGH); digitalWrite(7, HIGH);

delay(1000); // Wait for 1000 millisecond(s)

digitalWrite(11, LOW); digitalWrite(7, LOW);

delay(1000); // Wait for 1000 millisecond(s)

digitalWrite(10, HIGH);// Moving clockwise digitalWrite(6, HIGH);// Moving clockwise

delay(1000); // Wait for 1000 millisecond(s)

digitalWrite(10, LOW);// Moving counterclockwise digitalWrite(6, LOW);// Moving counterclockwise

delay(1000); // Wait for 1000 millisecond(s)

}
