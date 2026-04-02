# Baxter VR — Virtual Reality Exposure Therapy Prototype

![Baxter Teaser](Docs/baxterTeaser.png)

[Watch Demo Video](https://drive.google.com/file/d/1kjgba_oeoHeW1pzkNYUYNdggs33GfRWd/view?usp=sharing)

## Overview

Baxter VR is a virtual reality exposure therapy (VRET) prototype designed to explore how virtual reality can be used to simulate human–dog interactions for individuals with dog-related fear or anxiety (cynophobia).

The project investigates how interaction design, scale manipulation, and controlled exposure scenarios in VR can be used to create flexible and gradable exposure experiences. The system was developed as part of research exploring accessible, affordable, and adaptable virtual reality exposure therapy systems.

Unlike traditional exposure therapy simulations that focus primarily on visual realism, Baxter VR explores how interaction mechanics and spatial relationships can be used to influence perceived threat and emotional response.

*This work was published and presented at the 2025 IEEE International Symposium on Mixed and Augmented Reality (ISMAR) in Daejeon, South Korea on 8 October 2025.*

---

## Research Motivation

Exposure therapy is one of the most effective treatments for specific phobias, but in vivo exposure can be difficult to arrange, expensive, and unpredictable. Virtual reality offers a controlled alternative, but many VR exposure systems lack flexible interaction design and gradation mechanisms. As well, VR is an underexplored medium for delivering dog phobia therapy, especially when compared to other animal phobias.

Baxter VR was developed to explore:

- How users respond to virtual dogs at different distances and scales
- How perceived threat changes when the user is larger or smaller than the dog
- How interaction design can support gradual exposure
- How VR exposure systems can be designed to be flexible and customizable for therapists

This project later contributed to research investigating design principles for virtual reality exposure therapy systems.

---

## Key Design Concepts

### 1. Scale Manipulation

A core feature of Baxter VR is the ability to change the scale relationship between the user and the dog.

Instead of only changing the distance between the user and the virtual dog, the system allows:

- The user to become very large relative to the dog
- The user to become very small relative to the dog
- The environment to scale dynamically

This allows therapists or researchers to explore how **relative size and perceived power** influence fear responses.

---

### 2. World-in-Miniature Interaction

The system includes a world-in-miniature interface that allows the user or facilitator to:

- Adjust the size of the environment
- Change distances between the user and the dog
- Reposition elements in the environment

This allows exposure scenarios to be adjusted dynamically without restarting the experience.

---

### 3. Behaviour Preview System

To reduce unpredictability, the system includes a **behaviour preview feature**:

- A simplified dog model demonstrates behaviours before they occur
- Users can preview actions such as walking, barking, or approaching
- This helps reduce uncertainty and supports gradual exposure

---

### 4. Multi-Sensory Exposure

The system includes multiple stimulus types:

- Visual presence of the dog
- Dog movement and approach behaviour
- Audio (barking, movement sounds)
- Spatial proximity
- Relative scale

These elements can be combined to create different exposure intensity levels.

---

## System Features

- Virtual dog with multiple behaviour states
- Scale manipulation (user scale and environment scale)
- World-in-miniature environment editing
- Behaviour preview system
- Adjustable exposure intensity
- Research-oriented exposure scenario design
- VR interaction using tracked controllers
- Designed for room-scale VR

---

## Technical Implementation

Baxter VR was developed in **Unity**.

Key technical systems included:

- VR interaction system
- World-in-miniature manipulation system
- Dynamic environment scaling
- AI behaviour system for virtual dog actions
- Audio system for spatialized dog sounds
- Scenario control system for exposure conditions
- Event system for triggering dog behaviours
- Data collection hooks for research purposes

The system was designed to allow researchers to modify exposure parameters without rebuilding the application.

---

## My Contributions

My work on this project included:

- Interaction system design
- Implementation of scale manipulation system
- Implementation of world-in-miniature interaction system
- Exposure scenario design
- Dog behaviour system implementation
- Unity development and system integration
- Research design and study preparation

---

## Research Context

This project contributed to research on virtual reality exposure therapy design and was later published as part of academic research investigating design principles for simulating human–animal interactions in VR exposure therapy.

The project formed part of a broader research agenda exploring how virtual reality exposure therapy systems can be designed to be accessible, affordable, and adaptable.

---

## Limitations and Future Work

This prototype was an early-stage research system and not a clinical tool.

Future work could include:

- Separated/asymmetrical therapist control interfaces
- More advanced dog behaviour AI
- Additional environments
- Clinical trials with participants
- Integration into clinician workflows
- Expanded exposure customization tools

---

## Disclaimer

This project is a research prototype and is not a clinically validated therapy tool.
