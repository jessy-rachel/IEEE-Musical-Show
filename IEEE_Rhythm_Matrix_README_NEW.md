# 🎹 IEEE Arduino Rhythm Matrix

### Beginner-Friendly Hardware Workshop | Interactive Music & Light Console

**Duration:** 90 minutes  
**Format:** Guided hands-on workshop in teams (target: four groups)  
**Level:** Beginners — no prior Arduino experience required  
**Facilitators:** Pranshu · Jeslyn · Shayna

## Workshop Overview

Build a simple **Arduino-powered musical keyboard** using push buttons, a passive piezo buzzer, and an RGB LED. Participants learn how microcontrollers detect inputs and control outputs, then combine sound and light into a creative mini-performance.

**Final outcome:** Each team demonstrates a working multi-key musical console with LED colors that respond to key presses.

## Learning Outcomes

- Understand Arduino Uno fundamentals, digital inputs and outputs, and basic sensor interfaces.
- Read push-button input using `digitalRead()` and `INPUT_PULLUP`.
- Generate musical notes at different frequencies using `tone()` and stop sound with `noTone()`.
- Synchronize RGB LED colors with button-triggered notes.
- Customize and present a short musical/light sequence as a team.

## Workshop Modules & Team Responsibilities

| Module | Facilitator | Focus | Deliverable |
| --- | --- | --- | --- |
| **1. Arduino Basics & Inputs** | **Pranshu** | Microcontroller basics, GPIO, push buttons, brief LDR/IR/DHT sensor showcase and LED/buzzer outputs | Buttons detected as digital inputs |
| **2. Tone Generation** | **Jeslyn** | Passive piezo buzzer, `tone(pin, frequency)`, pitch/frequency, mapping notes to buttons | Each key plays a distinct musical note |
| **3. RGB LED Light Show** | **Shayna** | RGB LED wiring, color selection, synchronized lighting | Different notes activate distinct colors |

> **Hardware note:** Use a **passive** piezo buzzer for varying musical pitches; an active buzzer usually produces a fixed pitch. Arduino's standard `tone()` supports **one note at a time**, so simultaneous polyphony is not part of the beginner build.

## 90-Minute Agenda

| Time | Session | Lead |
| --- | --- | --- |
| **00:00–00:15** | Quick demo, Arduino fundamentals, buttons & sensor overview | Pranshu |
| **00:15–00:35** | Connect buzzer; map buttons to musical notes | Jeslyn |
| **00:35–00:55** | Add synchronized RGB LED effects | Shayna |
| **00:55–01:15** | **Rhythm Matrix Challenge:** personalize your console | All facilitators |
| **01:15–01:30** | Team performances, voting & mini-awards | All facilitators |

## Optional Challenge: Rhythm Matrix 🏆

Teams get **20 minutes** to create a short, recognizable melody or original beat with synchronized LED colors. Each team then performs for **30–60 seconds**, followed by a quick audience vote.

**Suggested awards:** Best Melody · Best Light Show · Most Creative Team.

If time and components permit, teams can try advanced extras such as tempo changes, an octave-shift button, a potentiometer to adjust pitch, or a simple prerecorded sequence. These are **optional**, not required for a successful workshop.

## Materials & Setup

**Per group (ideal):**
- Arduino Uno and compatible USB cable
- Breadboard and jumper wires
- 3–4 momentary push buttons
- 1 passive piezo buzzer (electrically suitable for the intended drive circuit)
- 1 RGB LED and appropriate current-limiting resistors
- Laptop with Arduino IDE and USB access

**Shared:** Projector for demonstrations; optional LDR, IR, and DHT sensors for a short introductory demo; spare components and cables.

**Backup setup:** If four physical kits are not available, conduct the guided exercise in **Tinkercad Circuits**, after checking availability of the required simulated components. A single physical demo kit can accompany the simulation.

## Repository Structure

```text
IEEE-Arduino-Rhythm-Matrix/
├── README.md                         # Workshop overview and plan
├── 01-Pranshu-Arduino-Basics/        # Buttons, sensor demos, input reading
├── 02-Jeslyn-Tone-Generation/       # Buzzer and musical note mapping
├── 03-Shayna-RGB-Light-Show/        # RGB light synchronization
├── 04-Final-Integration/            # Full working keyboard sketch
└── Workshop-Resources/              # Slides, diagrams, simulation links
```

Each facilitator can upload their **own `.ino` sketches**, diagrams, notes and screenshots inside their folder. The final integrated Arduino sketch can be placed in `04-Final-Integration` once all three modules work together.

## Contribution Workflow

1. Test your module independently (physical circuit or verified simulation).
2. Add your code and any wiring diagram to your own folder.
3. Describe the pins used, wiring instructions, and how to run your `.ino` sketch in the folder's README.
4. Before integration, agree on the final **shared pin assignment** to avoid conflicts.
5. Test and document the combined sketch under `04-Final-Integration`.

**Project status:** Workshop proposal and repository structure prepared. Individual module code and wiring plans to be added by facilitators.

---

*Prepared for an IEEE student hardware workshop. The agenda and optional challenge are planning targets and can be adapted to available hardware and participant pace.*
