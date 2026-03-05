# Swift Doorbell W/ Arduino
**Collaborators:** Ibrahim Al-Howaid &amp; Aidan Drakes 

**Project Start:** February 5, 2026 

**Status:** In Progress (Design Cycle 2)

# The Problem
The shop features a security door that locks automatically and can only be opened from the inside. This requires a person to be physically present near the door to grant entry. However, when the shop is busy or staff are in the main classroom area, visitors often go unnoticed. A reliable alert system is needed to bridge this gap.

# Solution & Criteria
Our goal is to build a rugged, high-volume doorbell system tailored for a shop environment. The design must meet the following technical requirements:

- Audio Output: Minimum 80-90 dB (loud enough to be heard over shop machinery).
- Durability: Built to withstand the physical strain of daily heavy use.
- Maintenance: Securely wall-mounted but features an accessible opening for battery replacement and/or upgrades.

# Components:

 (Design cycle 1) 🛠️ Hardware Stack
 
- Microcontrollers: 2x Micro:Bit

- Power: 2x Battery cases 

- Input: [1x LED Button](https://www.amazon.ca/Nilight-Stainless-Latching-Switches-Waterproof/dp/B0BMVR2RRM/ref=sr_1_8?crid=3DV3F8GTZKL0R&dib=eyJ2IjoiMSJ9.97goyb5WPq66coA7I0-qGGkc5qGwcRxVoJKl1xU28IjYykzkQNahYAXcRwZTmlVES3VoNbFmwZmDoBAbxSqtlbhDXuIbAw5QVDgR0aZ2Ie-xfd5OuiJyO2GmL9eO22_1iPOTQBalzfOo5TQJE91X7btb4CFVfOXBCWGJGw59nURIjXEbiTSKT4x1ewGS9_vGJyfRQH1krc2IU4mF_woiDGFFvpyxNaxMBdQQ5fBcr4tzAzwjXNwKerOarS1jqylmm4Xa4xb8qPsjQ-4Q7q6oaNh7gxDILPuPfzBIUymTj_4.mRPwragvJzCY2GkOvKQD-k9MTDU-2wn6HpS9VTMSgkU&dib_tag=se&keywords=Gravity%3A+LED+Button&qid=1771351114&sprefix=micro+bit+large+button%2Caps%2C502&sr=8-8)

- Output: 1x Speaker

- Housing: 2x Custom 3D-printed cases (Designed by Aidan)

![IMG_4123 (1)](https://github.com/user-attachments/assets/0077188b-1b6c-4fb7-9bf6-87c2bc424323)


# Design Cycle 1: Micro:bit Prototype

- **Setup:** One "Emitter" (Button) and one "Receiver (Speaker)
- **Conclusion** We discovered that the Micro:bit did not adequately support the voltage required for the external button and speaker simultaneously.
