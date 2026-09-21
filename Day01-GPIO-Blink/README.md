# Day 1: LED Blink (GPIO Basics)

## What I Built
Simple Arduino program that blinks built-in LED every 500ms.

## Code
```cpp
void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(500);
  digitalWrite(LED_BUILTIN, LOW);
  delay(500);
}
```

## What I Learned
- GPIO = General Purpose Input Output (pins you can control)
- digitalWrite(HIGH) = turn ON (5 volts)
- digitalWrite(LOW) = turn OFF (0 volts)  
- delay(500) = wait 500 milliseconds

## Why This Matters
- Foundation of embedded systems: control hardware with code
- Every embedded device starts here
- Proof: code → real-world effect

## Recruiter Explanation
"Built first embedded project using GPIO. Controlled LED via microcontroller output pin. Understand digital I/O, timing, and firmware basics."

## Next
Day 2: Add button (digital input)
