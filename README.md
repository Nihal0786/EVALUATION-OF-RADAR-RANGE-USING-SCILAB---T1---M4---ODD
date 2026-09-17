# EVALUATION-OF-RADAR-RANGE-USING-SCILAB---T1---M4---ODD
## Aim
To calculate the maximum range of a radar system using the Radar Range Equation and verify the results through Scilab programming.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
The Radar Range Equation is a fundamental formula used in radar system design to determine the maximum range at which a radar can detect a target. 

### Mathematical Representation
The maximum radar range $R_{\max}$ is given by:

$$R_{\max} = \left( \frac{P_t G_t G_r \lambda^2 \sigma}{(4\pi)^3 P_{\min}} \right)^{\frac{1}{4}}$$

Where:
* $R_{\max}$ : Maximum detectable range of the radar (m)
* $P_t$ : Transmitted power (W)
* $G_t$ : Gain of the transmitting antenna
* $G_r$ : Gain of the receiving antenna
* $\lambda$ : Wavelength of the radar signal (m), calculated as $\lambda = \frac{c}{f}$ (where $c = 3 \times 10^8 \text{ m/s}$)
* $\sigma$ : Radar cross-section of the target ($\text{m}^2$)
* $P_{\min}$ : Minimum detectable signal power of the receiver (W)

---

## Procedure / Algorithm
1. **Set Up the Scilab Environment:** Launch the Scilab workspace/console.
2. **Define Parameters:** Set values for transmitted power ($P_t$), antenna gains ($G_t, G_r$), frequency ($f$), radar cross section ($\sigma$), and minimum power ($P_{\min}$).
3. **Calculate Wavelength:** Convert signal frequency to wavelength using $\lambda = \frac{c}{f}$, where $c = 3 \times 10^8 \text{ m/s}$.
4. **Define Radar Range Equation:** Compute the numerator and denominator using Scilab's built-in math functions and `%pi`.
5. **Calculate Maximum Range:** Evaluate $R_{\max}$ by raising the ratio to the power of $0.25$ (1/4th power).
6. **Execute and Display Results:** Run the Scilab script (`.sce`) to display the maximum radar range in meters and kilometers.
<img width="960" height="1280" alt="80dfead5-2d4f-4878-9cd4-1b0af758a16e" src="https://github.com/user-attachments/assets/6165704a-5fed-4981-b886-d31e033858af" />
<img width="960" height="1280" alt="62e2b2c8-6f44-41a2-9ad8-b68b39711462" src="https://github.com/user-attachments/assets/6b0b34dc-8676-4926-a1e1-ef64fa4c1fff" />
<img width="960" height="1280" alt="1daec115-4b4b-49f2-80ff-0c32f799df5b" src="https://github.com/user-attachments/assets/2fbd663e-eeca-471a-ae7c-30f70f1d1b23" />
<img width="960" height="1280" alt="e1b8f929-3480-478c-b176-d0f1e70bc14d" src="https://github.com/user-attachments/assets/1776d834-d024-4872-b2b8-d2e808e738a8" />

---

## MODEL GRAPH
<img width="960" height="1280" alt="9f512c5d-f3ac-492c-8ae2-c5a78760c41d" src="https://github.com/user-attachments/assets/c03b5cd1-2c8f-47e7-b8f5-04463c899e24" />
