# 1-febrero
void setup() {
  pinMode(2, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(6, OUTPUT);
}

void loop() {
  digitalWrite(2, HIGH);
  delay(100);
  digitalWrite(2, LOW);
  delay(400);
  digitalWrite(4, HIGH);
  delay(100);
  digitalWrite(4, LOW);
  delay(400);
  digitalWrite(6, HIGH);
  delay(100);
  digitalWrite(6, LOW);
  delay(400);
}
