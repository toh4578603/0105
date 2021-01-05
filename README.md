# 0105
~~~c++
void setup() {
  // put your setup code here, to run once:
Serial.begin(9600);
}

void loop() {
  // put your main code here, to run repeatedly:
  int x =analogRead(A1);
  int y =analogRead(A2);
  int z =analogRead(A3);
  Serial.println("X      Y      Z");
  Serial.print(x);
  Serial.print("  ");
  Serial.print(y);
  Serial.print("  ");
  Serial.println(z);
 delay(1500);
}
~~~
