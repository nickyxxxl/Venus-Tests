# Venus-Tests
Testing suite for the "5EID0 CBL Engineering Challenge for Venus" course.
PYNQ manual: [https://pynq.tue.nl/5EID0/getting-started/]

# Library Improvements
- [ ] `stepper_steps` command should halt until movement is done.

# Tests
- [ ] power-on and connectivity
  - Power on LEDs
  - SSH connection
  - VScode connection
- [ ] pins
    - Voltage sources (3V3, 5V)
    - ADC pins (A0-A5)
    - GPIO pins (AR4-AR13)
- [ ] ESP32
    - Communication
- [ ] stepper move accuracy
  - Speeds
    - Highest speed without staggering movement
    - Intermediate speed
    - Low speed
  - Movements
    - Forward
    - Backward
    - One wheel turn
    - Two wheel turn
