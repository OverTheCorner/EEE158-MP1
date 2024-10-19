# EEE 158 MP 1: Guidance and Tips

## Coding Style

Make use of functionized and modular coding practices. don't just stuff all the code into your `main` function, make use of functions

For Example,

```c
int detect_button_1();
    //0: prototype your functions


int main() {
    //1: make your functions in main. Make it look like english
    detect_button_1();
    
    return 0;
}

int detect_button_1() {
    //2: this is where you can code
    // your function code
}
```

## Milestone Setting

### Part of SMART Goals

- (Specific, Measurable, Achievable, Relevant, Time Bound)
- Makes you keep track of progress
- Helps you understand where to debug
- Prevents you from feeling overwhelmed

Examples of Milestone for MP1:

#### Hardware Setup

- Milestone 1: “I have a circuit test bench that matches the specs”

#### Inputs (Buttons and ADC)

- Milestone 2: “I can detect the button presses on both buttons”
- Milestone 3:  “I can generate an interrupt on both buttons”
- Milestone 4: “I can read the value of the potentiometer”

#### Outputs (PWM and Timers)

- Milestone 5: “I can control PWM on one channel of the RGB LED”
- Milestone 6: “I can control PWM on all 3 channels of the RGB LED”
- Milestone 7: “I can control the brightness of the RGB LED”
- Milestone 8: “I can create an LED sequence with specific timing with changing color”
- Milestone 9: “I can create an LED Sequence with changing color and brightness”

#### Integration

- Milestone 10: “I can change the brightness of the RGB LED based on the Potentiometer Input”
- Milestone 11: “I can change the sequence speed of the RGB LED based on Potentiometer Input”
- Milestone 12: “I have achieved the specs of MP1”

## Minimum Parts list for MP1

- Two Tactile Switches
- One Potentiometer
  - Recommended Value: 10k Ohm
- One RGB LEd
  - Common Cathode / Common Ground / Common Negative
  - *note*: Use Current Limiting Resistors in series with each color 

### Notes for the Parts

You may need to use more parts than the ones above if you want stabilize parts of your circuit
such as the potentiometer input, button debouncing. etc.