# Problem 3: Series RC Circuit

**Question:** 

For the series RC circuit in the figure with \( R = 90Ω \) and \( C = 55μF \), calculate:
(a) Current \( I \)
(b) Voltage across resistor \( V_R \) and capacitor \( V_C \)
(c) The angle theta \( \theta \) and power factor (PF) for the circuit
(d) True power (W), reactive power (VARs), apparent power (VA)

**Given:**
- <code>Voltage source: 125V</code>
- <code>Resistor: 90Ω</code>
- <code>Capacitor: 55μF</code>

---

## Solution:

#### Given:
- <code>Voltage source: 125V</code>
- <code>Resistor: 90Ω</code>
- <code>Capacitor: 55μF</code>


1. **Calculate the current \( I \):**

   The impedance of the capacitor \( X_C \):

   $$X_C = \frac{1}{\omega C} = \frac{1}{2\pi f C} = \frac{1}{2\pi \cdot 50 \cdot 55 \times 10^{-6}}$$

   Assuming a frequency \( f = 50Hz \):

   $$X_C \approx 57.87 \, \Omega$$

   Total impedance \( Z \):

   $$Z = \sqrt{R^2 + X_C^2} = \sqrt{90^2 + 57.87^2} \approx 106.26 \, \Omega$$

   Current \( I \):

   $$I = \frac{V}{Z} = \frac{125 \, V}{106.26 \, \Omega} \approx 1.176 \, A$$

2. **Voltage across resistor \( V_R \) and capacitor \( V_C \):**

   Voltage across the resistor \( V_R \):

   $$V_R = I \cdot R = 1.176 \, A \cdot 90 \, \Omega \approx 105.84 \, V$$

   Voltage across the capacitor \( V_C \):

   $$V_C = I \cdot X_C = 1.176 \, A \cdot 57.87 \, \Omega \approx 68.12 \, V$$

3. **The angle theta \( \theta \) and power factor (PF) for the circuit:**

   Angle \( \theta \):

   $$\theta = \tan^{-1}\left(\frac{X_C}{R}\right) = \tan^{-1}\left(\frac{57.87}{90}\right) \approx 32.15^\circ$$

   Power factor (PF):

   $$PF = \cos(\theta) = \cos(32.15^\circ) \approx 0.846$$

4. **True power (W), reactive power (VARs), apparent power (VA):**

   True power \( P \):

   $$P = V_R \cdot I = 105.84 \, V \cdot 1.176 \, A \approx 124.45 \, W$$

   Reactive power \( Q \):

   $$Q = V_C \cdot I = 68.12 \, V \cdot 1.176 \, A \approx 80.11 \, VAR$$

   Apparent power \( S \):

   $$S = V \cdot I = 125 \, V \cdot 1.176 \, A \approx 147 \, VA$$

Thus, the solutions are as follows:

- **Current:** <code>I ≈ 1.176 A</code>
- **Voltage across resistor:** <code>V<sub>R</sub>≈ 105.84 V</code>
- **Voltage across capacitor:** <code>V<sub>С</sub> ≈ 68.12 V</code>
- **Angle:** <code>θ ≈ 32.15°</code>
- **Power factor:** <code>PF ≈ 0.846</code>
- **True power:** <code>P ≈ 124.45 W</code>
- **Reactive power:** <code>Q ≈ 80.11 VAR</code>
- **Apparent power:** <code>S ≈ 147 VA</code>
