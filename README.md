### Passenger Transport Aircraft - Project Overview
The primary goal of this project is to improve the efficiency of a passenger transport aircraft by 50% as compared to the 737. The path we chose to accomplish this goal is a retractable canard design. The intention is to reduce the total surface area generating drag while in cruise, ultimately leading to less fuel usage. While we are not yet in a position to provide results on whether our design will achieve this target, the true difficulty of this project has been found in the stability considerations of variable geometry airframes. It has required compromising the static stability behavior in both retracted and extended modes to have a "reasonable" static margin in both modes. Due to this consideration, two prototypes are being made, the first to test the performance and flight test procedures of a retractable canard aircraft. The second will build upon the knowledge of the first and develop dynamic similarity by matching the static margins and ultimately providing far more accurate analysis on the **transient** condition during retraction.

### My Role
- **Flight Mechanics:** Throughout the beginning of this project, I worked on the flight mechanics of the full-size aircraft, primarily in the control surface sizing and stability analysis of the airframe. These early designs guided us to our current configuration, as I determined flight regimes in which control surface sizing should be performed.
- **Prototype:**
  - **Initial Prototype:** When I began working on the first prototype, the full-scale was continuously optimized. I began working on **avionics**, where I have now worked extensively. We plan to fly our first prototype using INAV with a stripped-down ELRS-based flight controller for ease of use and to make the flight checks go a little smoother.
  - **Second Prototype:** Our second, however, will use ArduPilot to enable in-flight gain scheduling for the retracted and extended flight modes to make the aircraft easier to fly and to enable smoother testing, at the cost of increased complexity. I have been developing LUA scripts to write on board the flight controller that will read PWM signal changes from the transmitter and rewrite the gains from a pre-determined set for each configuration. In the meantime, we have finished a dry avionics setup and are now fully outfitting the first prototype with avionics, and we will be performing component checks with the university shortly.
 
### Student Conference Presentation
I will be attending the AIAA Region V Student Conference as both a general officer representative of CU AIAA and as a presenter, alongside two of my teammates. We will be writing a paper with a group of six teammates to synthesize what we have learned and draw a conclusion on retractable canards and the methodology we used to do so. Our abstract may be found [here]().

### Full Scale Current Configuration

<img width="1245" height="774" alt="image" src="https://github.com/user-attachments/assets/eb432ec0-2ef6-4aeb-9226-fc817d72f421" />

