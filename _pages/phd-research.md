---
permalink: /phd-research/
title: "Masterplan to PhD"
author_profile: true
---

## Research Focus

My PhD research focuses on **Human-Robot Interaction (HRI)**, specifically on improving **Human-Robot Conversations (HRC)** through visual models. The goal is to enhance **Visual Voice Activity Detection (VVAD)** and **Speaker Identification** to make them robust and applicable in HRI scenarios. This involves addressing several dimensions:

- Transitioning from **single-person** to **multi-person** interactions.
- Exploring input sizes, ranging from:
  - **Lip Features** -> **Face Features** -> **Lip Images** -> **Face Images**  -> **Full Images**.
- Producing outputs such as:
  - **Speaking/Not Speaking Labels** and
  - **Bounding Boxes** for active speakers.

## Motivation

I believe it is crucial for humans to interact with robots in a natural way in the future. Currently, Human-Robot Conversations are highly one-dimensional, often resembling simple chatbots. However, the physical form, sensors, and actuators of robots allow for the integration of additional modalities, which can significantly enhance the interaction experience.

## Goals

The primary goal of my PhD is to make **VVAD** and **Speaker Identification** not only robust but also practical for robotics applications. This includes:

1. Developing models that are efficient and scalable:
   - Creating smaller versions of the models that can run on less powerful hardware, beyond high-performance GPUs.
2. Providing accessible implementations:
   - Publishing the final implementation as a **Python library**.
   - Offering a **ROS2 Node** to make the results easily available for robotic systems.
   - Packaging the solution as a **Docker container** for out-of-the-box usability.

By achieving these goals, I aim to bridge the gap between cutting-edge research and practical applications in robotics, enabling more natural and multimodal human-robot interactions.