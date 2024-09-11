// Pin where the LED is connected (onboard LED is usually GPIO 2)
const int ledPin = 2;

void setup() {
  // Initialize the digital pin as an output
  pinMode(ledPin, OUTPUT);
}

void loop() {
  // Turn the LED on (HIGH is the voltage level)
  digitalWrite(ledPin, HIGH);
  // Wait for a second
  delay(1000);
  // Turn the LED off (LOW is the voltage level)
  digitalWrite(ledPin, LOW);
  // Wait for a second
  delay(1000);
}
