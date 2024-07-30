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

### Solution:

#### Given:
- <code>Voltage source: 125V</code>
- <code>Resistor: 90Ω</code>
- <code>Capacitor: 55μF</code>

1. **Calculate the current \( I \):**

   The impedance of the capacitor \( X_C \):

   $$
   X_C = \frac{1}{\omega C} = \frac{1}{2\pi f C} = \frac{1}{2\pi \cdot 50 \cdot 55 \times 10^{-6}}
   $$

   Assuming a frequency \( f = 50Hz \):

   $$
   X_C \approx 57.87Ω
   $$

   Total impedance \( Z \):

   $$
   Z = \sqrt{R^2 + X_C^2} = \sqrt{90^2 + 57.87^2} \approx 106.26Ω
   $$

   Current \( I \):

   $$
   I = \frac{V}{Z} = \frac{125V}{106.26Ω} \approx 1.176A
   $$

2. **Voltage across resistor \( V_R \) and capacitor \( V_C \):**

   Voltage across the resistor \( V_R \):

   $$
   V_R = I \cdot R = 1.176A \cdot 90Ω \approx 105.84V
   $$

   Voltage across the capacitor \( V_C \):

   $$
   V_C = I \cdot X_C = 1.176A \cdot 57.87Ω \approx 68.12V
   $$

3. **The angle theta \( \theta \) and power factor (PF) for the circuit:**

   Angle \( \theta \):

   $$
   \theta = \tan^{-1}\left(\frac{X_C}{R}\right) = \tan^{-1}\left(\frac{57.87}{90}\right) \approx 32.15^\circ
   $$

   Power factor (PF):

   $$
   PF = \cos(\theta) = \cos(32.15^\circ) \approx 0.846
   $$

4. **True power (W), reactive power (VARs), apparent power (VA):**

   True power \( P \):

   $$
   P = V_R \cdot I = 105.84V \cdot 1.176A \approx 124.45W
   $$

   Reactive power \( Q \):

   $$
   Q = V_C \cdot I = 68.12V \cdot 1.176A \approx 80.11VAR
   $$

   Apparent power \( S \):

   $$
   S = V \cdot I = 125V \cdot 1.176A \approx 147VA
   $$

Thus, the solutions are as follows:
- Current \( I \approx 1.176A \)
- Voltage across resistor \( V_R \approx 105.84V \)
- Voltage across capacitor \( V_C \approx 68.12V \)
- Angle \( \theta \approx 32.15^\circ \)
- Power factor \( PF \approx 0.846 \)
- True power \( P \approx 124.45W \)
- Reactive power \( Q \approx 80.11VAR \)
- Apparent power \( S \approx 147VA \)
