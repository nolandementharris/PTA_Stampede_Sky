### Passenger Transport Aircraft - Project Overview
The primary goal of this project was to improve passenger transport aircraft efficiency by 50% compared to the 737 using a retractable canard design. Retracting the canard in cruise was intended to reduce drag-generating surface area and lower fuel consumption. While final efficiency results remained beyond the scope of this phase, the core challenge lay in the stability trade-offs of variable-geometry airframes—specifically balancing static stability across both retracted and extended modes to maintain a reasonable static margin in each. To address this, the team built two prototypes: the first validated performance and flight-test procedures for a retractable canard configuration, while the second established dynamic similarity by matching static margins to enable a more accurate analysis of transient behavior during retraction.

### My Role
- **Flight Mechanics:** Early in the project, I focused on full-scale flight mechanics, primarily control surface sizing and airframe stability analysis. I identified the flight regimes used for control surface sizing, which helped guide the team toward the final configuration.
- **Prototype:**
  - **Initial Prototype:** As full-scale optimization continued, I shifted heavily into avionics. The team flew the first prototype on INAV using a streamlined ExpressLRS (ELRS) flight controller setup to simplify operations and streamline pre-flight checks.
  - **Second Prototype:**The second prototype ran ArduPilot to support in-flight gain scheduling between retracted and extended modes, trading added complexity for easier handling and smoother testing. I wrote onboard Lua scripts that read transmitter PWM changes and swapped in pre-determined gain sets per configuration. 
    
### Student Conference Presentation
Alongside two teammates, I attended the AIAA Region V Student Conference as a presenter and as a general officer representative for CU AIAA. Working with a six-person team, I co-authored a technical paper synthesizing our findings and methodology on retractable canards. You can view our abstract [here](AIAA_Stampede_Sky_Abstract.pdf).

### Full Scale Current Configuration

<img width="1245" height="774" alt="image" src="https://github.com/user-attachments/assets/eb432ec0-2ef6-4aeb-9226-fc817d72f421" />

