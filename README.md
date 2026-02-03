#  Stealth Women Safety Application

##  Problem Statement
In many critical domestic violence or harassment situations, women are unable to open safety apps, make calls, or access the internet due to fear, phone seizure, or locked-screen constraints.  
Most existing safety solutions fail because they require visible user interaction during emergencies.

## Proposed Solution
A stealth emergency safety application disguised as a calculator that enables silent activation through hardware-based triggers.  
The system operates in the background, captures evidence securely, and escalates alerts only when risk thresholds are crossed.

The design prioritizes:
- User safety over visibility
- Offline-first operation
- Zero screen interaction during emergencies

##  Key Features
- Calculator-style disguise (no visible SOS elements)
- Emergency trigger via volume button press (3 times)
- Silent background audio recording
- Offline evidence storage with timestamps
- Risk-level analysis to prevent false alerts
- Automatic alert sharing to authorities or NGOs when limits are crossed
- Secure, hidden access to evidence for later review

##  Emergency Workflow
1. User presses the volume button three times during a critical situation
2. Background service activates silently
3. Audio evidence is recorded and stored offline
4. Risk level increases with repeated triggers
5. Alerts are automatically sent to trusted authorities when thresholds are exceeded
6. User can later access evidence through a hidden internal interface

##  UI / UX Design (Figma)
🔗 Figma Prototype Link:  
https://www.figma.com/make/EznC2a2UTOrqrNjUKXxHXd/Women-Safety-App-Design?p=f&t=xEw4vp8qMeF9tonQ-0&fullscreen=1

The UI is intentionally minimal and non-alarming, ensuring the application appears harmless even under observation.

##  Technology Stack (Planned)
- Android (Kotlin)
- Background Services
- Local Encrypted Storage
- Offline Trigger Handling
- Secure Alert Transmission

##  Project Status
This repository represents a *prototype and design-focused implementation* developed for hackathon evaluation.  
The emphasis is on problem understanding, system logic, and feasibility rather than full production deployment.


## 👥 Team
- UI/UX Design & Product Logic
- Emergency Flow & Risk Modeling
- Prototype Demonstration
