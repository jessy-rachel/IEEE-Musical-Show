# IEEE Arduino Rhythm Matrix
### Beginner-Friendly Hardware Workshop: Interactive Music and Light Console

**Duration:** 90 minutes  
**Format:** Hands-on workshop in teams (approximately four groups)  
**Level:** Beginner  
**Facilitators:** Pranshu, Jeslyn, Shayna

## Workshop Overview

This workshop introduces participants to Arduino programming and basic electronics through the development of an interactive musical keyboard. Using push buttons, a passive piezo buzzer, and RGB LEDs, participants will learn how a microcontroller processes inputs and controls outputs to generate musical notes and corresponding light effects.

By the end of the workshop, each team will have developed a functional Arduino-based musical console capable of playing different notes with synchronized LED colors.

## Learning Objectives

Participants will learn to:

- Understand basic Arduino concepts, digital inputs and outputs, and sensor interfacing.
- Detect button presses using `digitalRead()` and `INPUT_PULLUP`.
- Generate musical notes at different frequencies using the `tone()` function.
- Control RGB LEDs and synchronize lighting effects with musical notes.
- Combine individual components into a functional electronic system.

## Workshop Modules

### Module 1: Arduino Basics and Inputs
**Facilitator: Pranshu**

Introduction to Arduino Uno, microcontrollers, digital and analog pins, and basic electronic components. Participants will explore common sensors such as LDR, IR, and DHT, along with outputs such as LEDs and buzzers.

The hands-on activity will focus on connecting push buttons to Arduino and detecting user input.

**Outcome:** Participants can successfully read button inputs using Arduino.

### Module 2: Tone Generation
**Facilitator: Jeslyn**

Introduction to sound generation using a passive piezo buzzer. Participants will understand how different frequencies produce musical pitches and use the Arduino `tone()` function to assign musical notes to individual push buttons.

**Outcome:** Each button produces a distinct musical note when pressed.

### Module 3: RGB LED Light Show
**Facilitator: Shayna**

Introduction to RGB LEDs, basic color control, and synchronization of outputs. Participants will program the RGB LED to display different colors corresponding to different musical notes.

**Outcome:** The musical keyboard produces synchronized sound and lighting effects.

## Workshop Schedule

| Duration  | Session                   | Activities                                                             | Facilitator      |
| --------- | ------------------------- | ---------------------------------------------------------------------- | ---------------- |
| 0–15 min  | Arduino Basics and Inputs | Introduction to Arduino, sensors, outputs, and push-button interfacing | Pranshu          |
| 15–35 min | Tone Generation           | Buzzer connections, musical frequencies, and mapping notes to buttons  | Jeslyn           |
| 35–55 min | RGB LED Integration       | RGB LED connections and synchronization of colors with musical notes   | Shayna           |
| 55–75 min | Team Challenge            | Customizing melodies, rhythms, and lighting effects                    | All Facilitators |
| 75–90 min | Demonstration and Voting  | Team performances, audience voting, and awards                         | All Facilitators |

## Optional Team Challenge: Rhythm Matrix

After completing the basic circuit, teams will have approximately 20 minutes to develop a short musical performance using their Arduino console.

Each team will demonstrate a recognizable melody or original beat accompanied by synchronized LED effects.

Performances will last approximately 30–60 seconds per team.

Suggested award categories include Best Melody, Best Light Show, and Most Creative Team.

Depending on available time and resources, participants may also explore additional features such as tempo adjustments, octave switching, pitch control using a potentiometer, or programmed melody playback.

## Hardware and Software Requirements

Each group will ideally require:

- Arduino Uno with USB cable
- Breadboard and jumper wires
- 3–4 push buttons
- Passive piezo buzzer
- RGB LED with current-limiting resistors
- Laptop with Arduino IDE installed

Additional shared resources include a projector, optional LDR, IR, and DHT sensors for demonstration, and spare electronic components.

If sufficient Arduino kits are unavailable, the workshop may be conducted using Tinkercad Circuits for circuit simulation and programming, subject to verification of component availability. A physical Arduino setup can also be used for live demonstrations.

**Technical consideration:** A passive piezo buzzer is preferred for generating different musical frequencies. The standard Arduino `tone()` function produces one note at a time, which is sufficient for the intended beginner-level project.

## Repository Structure

The GitHub repository will organize the workshop materials and source code according to each facilitator's responsibilities.

```text
IEEE-Musical-Show/
│
├── README.md
│
├── 01-Pranshu-Arduino-Basics/
│
├── 02-Jeslyn-Tone-Generation/
│
├── 03-Shayna-RGB-Light-Show/
│
└── Workshop-Resources/
```

Each facilitator will maintain their respective folder with Arduino code, circuit diagrams, implementation instructions, and relevant documentation.

The `04-Final-Integration` folder will contain the complete Arduino program combining button inputs, musical note generation, and RGB LED synchronization.

The `Workshop-Resources` folder will contain supporting materials such as presentation slides, circuit diagrams, and simulation references.

## Development and Collaboration

Each facilitator will independently prepare and test their assigned module before integration.

Arduino programs will be uploaded as `.ino` files alongside any required wiring instructions and circuit diagrams.

Before combining the modules, the team will finalize a common Arduino pin configuration to prevent hardware conflicts.

The integrated circuit and program will then be tested to ensure proper operation before the workshop.

## Project Status

The workshop structure, module responsibilities, and proposed schedule have been finalized for preparation.

Individual Arduino programs, circuit diagrams, and final integration will be added as development progresses.

The workshop activities and schedule may be adjusted based on component availability, preparation progress, and participant requirements.
