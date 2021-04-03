
#include <FastLED.h>
#define LED_PIN     7
#define NUM_LEDS    20
CRGB leds[NUM_LEDS];
void setup() {
  FastLED.addLeds<WS2812, LED_PIN, GRB>(leds, NUM_LEDS);
}
void loop() {
  for (int i = 0; i <=19; i++) {
    leds[i] = CRGB ( 0, 0, 255);
    FastLED.show();
    delay(40);
  }
  for (int i = 0; i <=19; i++) {
    leds[i] = CRGB ( 255, 0, 0);
    FastLED.show();
    delay(40);
  }
  for (int i = 0; i <= 19; i++) {
    leds[i] = CRGB ( 0, 255, 0);
    FastLED.show();
    delay(40);
  }
  for (int i = 0; i <=19; i++) {
    leds[i] = CRGB ( 150, 0, 255);
    FastLED.show();
    delay(40);
  }
  for (int i = 0; i <= 19; i++) {
    leds[i] = CRGB ( 255, 200, 20
    );
    FastLED.show();
    delay(40);
  }
  for (int i = 0; i <=19; i++) {
    leds[i] = CRGB ( 85, 60, 180);
    FastLED.show();
    delay(40);
  }
  for (int i = 0; i <= 19; i++) {
    leds[i] = CRGB ( 50, 255, 20
    );
    FastLED.show();
    delay(40);
  }
}
