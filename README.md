# Cascaded H-Bridge Converters
* Multicarrier PWMs
* Demand for high-voltage, high power converters capable of producing high-quality waveforms while utilizing low voltage devices and reduced switching frequencies has led to the multilevel inverter development with regard to semiconductor power switch voltage limits.
* Multilevel inverters (MLIs) are improved alternative devices to regular two-level inverters, to decrease dv/dt and di/dt ratios while providing an increased number of output levels in current and voltage waveforms.
* They are used in many application areas, including industrial drives, utility applications such as static compensators (STATCOMs), uninterruptible power supplies (UPSs), and integration of renewable energy sources to the utility grid.
* Suitable in various high voltage and high power applications due to their ability to synthesize waveforms with better harmonic spectrum.
* The most attractive features of multilevel inverters are as follows:-
  * They can generate output voltages with extremely low distortion and lower dv/dt.
  * They draw input current with very low distortion.
  * They generate smaller common mode (CM) voltage, thus reducing the stress in the motor bearings. In addition, using sophisticated modulation methods, CM voltages can be eliminated.
  * They can operate with a lower switching frequency.
* The different multilevel inverter structures are **cascaded H-bridge**, diode clamped and flying capacitor multilevel inverter.
* The cascaded multilevel inverter has the potential to be the most reliable and achieve the best fault tolerance owing to its **modularity**, a feature that enables the inverter to continue operating at lower power levels after cell failure. **Modularity** also permits the cascaded multilevel inverter to be stacked easily for high power and high-voltage applications.
* The cascaded multilevel inverter typically comprises several identical single phase H-bridge cells cascaded in series at its output side. This configuration is commonly referred to as a cascaded H-bridge, which can be classified as **symmetrical** if the dc bus voltages are equal in all the series power cells, or as **asymmetrical** if otherwise. In an asymmetrical CHB, dc voltages are varied to produce more output levels.
* Two series connected H-bridge cells which are fed by independent voltage sources. The outputs of the H-bridge cells are connected in series such that the synthesized voltage waveform is the sum of all of the individual cell outputs. The output voltage is given by **V=V1 +V2** Where the output voltage of the first cell is labeled V1 and the output voltage of the second cell is denoted by V2. There are five levels of output voltage ie **{2V, V, 0, -V, -2V}**.
* The main advantages of cascaded H-bridge inverter is that it requires the least number of components, modularized circuit and soft switching can be employed. But the main disadvantage is that when the voltage level increases, the number of switches increases and also the source, this in effect increases the cost and weight.
