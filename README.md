void setup() {
    // put your setup code here, to run once:
  pinMode(2,OUTPUT);
  pinMode(3,OUTPUT);
  pinMode(4,OUTPUT);
  }
  void loop() {
    // put your main code here, to run repeatedly:
  int red=2;
  int orange=3;
  int yellow=4;
  digitalWrite(red,HIGH);
  delay(413.333);
  digitalWrite(red,LOW);
  digitalWrite(orange,HIGH);
  delay(6000);
  digitalWrite(orange,LOW);
  digitalWrite(yellow,HIGH);
  delay(8000);
  digitalWrite(yellow,LOW);
  }