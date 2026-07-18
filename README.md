Potentiometers:

    Connect the first potentiometer's middle pin (output) to A0 (analog pin 0) on the Arduino.
    Connect the second potentiometer's middle pin (output) to A1 (analog pin 1) on the Arduino.
    Connect one side pin of both potentiometers to 5V on the Arduino.
    Connect the other side pin of both potentiometers to GND on the Arduino.

LED Matrix:

    Follow the wiring instructions for your specific LED matrix. For a common MAX7219-based 8x8 LED matrix, the wiring would typically be:
        VCC to 5V
        GND to GND
        DIN to D11
        CS to D10
        CLK to D13
Explanation

    Potentiometers:
        POT1_PIN controls the speed.
        POT2_PIN controls the horizontal scroll direction.

    Speed Adjustment:
        The speed is mapped from the potentiometer value and set using myDisplay.setSpeed(speed).

    Scroll Direction:
        The horizontal scroll direction is set based on the potentiometer value:
            If pot2Value is greater than 512, scroll left.
            If pot2Value is less than or equal to 512, scroll right.

Steps to Verify and Upload

    Install Libraries:
        Ensure MD_Parola and MD_MAX72XX libraries are installed through the Arduino Library Manager.

    Upload the Sketch:
        Connect your Arduino Nano to your computer.
        Select the correct board and port under Tools.
        Click on the Upload button to upload the sketch to your Arduino Nano.
