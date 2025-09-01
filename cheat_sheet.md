# tirotir Electronics Calculator Suite Help

## Battery Specifications

- **AA Battery**:
  - Voltage: 1.5V
  - Typical Capacity: \~2000-3000 mAh (milliamp-hours), depending on quality (e.g., 2.4 Ah at 1.2V for rechargeable NiMH)
  - Current: Varies by load; typically provides 0.5-1A continuous, up to 2A in short bursts
- **9V Battery**:
  - Voltage: 9V
  - Typical Capacity: \~500-600 mAh
  - Current: Limited to \~0.5A continuous; short bursts up to 1A

*Note*: Capacities and currents depend on battery chemistry (alkaline, NiMH, etc.) and load. Always check manufacturer specs.

## Basic Circuit Examples

### 1. Simple LED Circuit

- **Components**: LED, Resistor (220-330Ω), AA Battery (1.5V)
- **Purpose**: Lights a single LED
- **Diagram**:

  ```
  + (Battery) ---- [Resistor] ---- (+) LED (-) ---- (Ground)
  ```
- **Calculation**: Use LED Resistor Calculator with 1.5V supply, LED forward voltage (e.g., 2V), and desired current (e.g., 20mA).
- **Notes**: Resistor limits current to protect the LED.

### 2. Blinking LED Circuit

- **Components**: LED, Resistor (220-330Ω), Capacitor (10µF), 555 Timer IC, AA Battery (1.5V-9V)
- **Purpose**: Creates a blinking effect
- **Diagram**:

  ```
  + (Battery) ---- [555 Timer] ---- [Resistor] ---- (+) LED (-) ---- (Ground)
                       |---- [Capacitor] ---- (Ground)
  ```
- **Calculation**: Use RC Filter Calculator to set frequency (e.g., 1Hz with R=10kΩ, C=10µF).
- **Notes**: 555 Timer in astable mode; adjust R and C for blink rate.

### 3. Photocell (LDR) Circuit

- **Components**: Photocell (LDR), Resistor (10kΩ), LED, AA Battery (1.5V)
- **Purpose**: LED brightness varies with light intensity
- **Diagram**:

  ```
  + (Battery) ---- [Photocell] ---- (+) LED (-) ---- (Ground)
                       |---- [10kΩ Resistor] ---- (Ground)
  ```
- **Calculation**: Use Voltage Divider Calculator; LDR resistance changes with light (e.g., 1kΩ in light, 10kΩ in dark).
- **Notes**: LED dims in dark as voltage drop across LDR increases.

### 4. Buzzer Circuit

- **Components**: Buzzer, Resistor (100Ω), Switch, AA Battery (1.5V)
- **Purpose**: Produces sound when activated
- **Diagram**:

  ```
  + (Battery) ---- [Switch] ---- [Resistor] ---- (Buzzer +) ---- (Ground)
  ```
- **Calculation**: Use Ohm's Law Calculator with buzzer impedance (e.g., 8Ω) and 1.5V supply.
- **Notes**: Resistor protects buzzer from overcurrent; check buzzer specs.

### 5. Transistor Switch Circuit

- **Components**: NPN Transistor (e.g., 2N3904), Resistor (1kΩ base, 220Ω collector), LED, AA Battery (1.5V)
- **Purpose**: Switches LED on/off with base current
- **Diagram**:

  ```
  + (Battery) ---- [220Ω] ---- (+) LED (-) ---- (Collector) [Transistor]
                       |---- (Emitter) ---- (Ground)
                       |---- [1kΩ] ---- (Base) ---- (Switch) ---- (Ground)
  ```
- **Calculation**: Use Transistor Switch Calculator; base current \~1/10th collector current (e.g., 2mA base for 20mA LED).
- **Notes**: Switch controls base to turn transistor on.

### 6. Capacitor Charge/Discharge Circuit

- **Components**: Capacitor (100µF), Resistor (10kΩ), Switch, LED, AA Battery (1.5V)
- **Purpose**: LED fades on/off with capacitor charge
- **Diagram**:

  ```
  + (Battery) ---- [Switch] ---- [Resistor] ---- (+) Cap (-) ---- (Ground)
                       |---- (+) LED (-) ---- (Ground)
  ```
- **Calculation**: Use Capacitor Charge/Discharge Calculator; time constant = R × C (e.g., 1s for 10kΩ × 100µF).
- **Notes**: LED brightness fades as capacitor charges/discharges.

## General Tips

- **Safety**: Use appropriate resistors to limit current; avoid exceeding battery or component ratings.
- **Tools**: Access calculators via `dashboard.html` for precise values.
- **Export**: Use "Export Image" to save circuit diagrams for reference.
- **Date Created**: September 01, 2025, 11:55 AM +04

*Powered by tirotir.by - Your Electronics Calculation Companion*