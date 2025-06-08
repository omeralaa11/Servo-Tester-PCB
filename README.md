# Servo Tester PCB

A simple and compact servo tester based on the NE556 timer IC. This project includes a custom-designed PCB layout suitable for testing standard hobby servos.

![PCB Render](https://github.com/omeralaa11/Servo-Tester-PCB/blob/main/images/pcb_render.png)

## 🧰 Features

- Manual PWM signal generation using NE556 timer
- Adjustable pulse width via potentiometer
- Compatible with most RC servos
- Compact and easy-to-fabricate PCB design
- Powered via standard 5V input

## 📝 Project Files

This repository contains:

- `Servo_Tester.kicad_pcb` – PCB layout file (KiCad)
- `Servo_Tester.sch` – Schematic file (KiCad)
- `images/` – Rendered images of the PCB and schematic

## ⚙️ How It Works

The NE556 timer is configured in astable mode to generate a PWM signal. By adjusting the potentiometer, the pulse width of the PWM signal changes, thereby controlling the servo angle.

Typical PWM specs:
- Frequency: ~2.5KHz or 25KHz

## 🔧 Hardware Requirements

- NE556 timer IC
- 2*50k potentiometer
- Resistors and capacitors (see schematic)
- Standard 3-pin servo header
- 5V to 15V power source

## 📸 Gallery

<img src="images/schematic.png" width="500"/>
<img src="images/3d_view.png" width="500"/>

## 🛠️ Usage

1. Connect a 5V power source to the input.
2. Plug in your servo to the output header (GND, VCC, Signal).
3. Rotate the potentiometer to test the servo movement.

## 🧑‍💻 Author

**Omer Alaa**  
🔗 [@omeralaa11](https://github.com/omeralaa11)



