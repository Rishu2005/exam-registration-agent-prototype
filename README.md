# Exam Registration Agent (Prototype)

This repository contains a **prototype-level implementation** of an
agentic Android automation built for **Droidrun DevSprint 2026**.

## Problem
Students face difficulty while filling long and time-sensitive
exam registration forms on Android devices. Manual form filling is
repetitive, error-prone, and stressful.

## Solution
We propose a **Droidrun-style agent** that assists students during
exam registration by:
- Observing Android UI elements via the Accessibility layer
- Mapping student data to relevant form fields
- Guiding form filling actions
- Stopping before final submission for security

## Agentic Workflow
Goal → Observe → Decide → Act → Verify

## Technology Stack
- Droidrun (agent framework – conceptual)
- Android Accessibility
- ADB (interaction simulation)
- Gemini LLM (used for field–value mapping, optional)
- Chrome (target app)

## Note
This project represents a **prototype and design validation**.
Due to Android security restrictions on live government portals,
the demo focuses on agent behavior and feasibility rather than
full production automation.
