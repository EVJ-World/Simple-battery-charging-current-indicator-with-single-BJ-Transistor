# Simple Battery Charging Current Indicator (with Single BJT)

This simple circuit shows the charging current level using just one bipolar transistor.
![Simple current inficator's circuit)](https://github.com/EVJ-World/Simple-battery-charging-current-indicator-with-single-BJ-Transistor/blob/main/simple_charging_indicator.jpg)
*Fig. 1 – Simple current inficator's schematic (by Vytautas Janusonis / EVJ)*

A simple way to detect battery charge with reasonable accuracy.  
Here the end of charging is detected when the battery voltage  
reaches **13.6 V** (≈ −200 mV from the supply voltage) and the current  
at that time is **~133 mA**, then the **red LED turns off**.

The uniqueness of the idea is the reduction of the **base opening voltage threshold**  
by adding a dropout voltage on the **R2 resistor** from the **R2 + R3** voltage divider.  
The voltage supposedly reduces the typical base opening threshold of the transistor  
from ~600 mV to ~200 mV.  
This is achieved by adding a ~400 mV offset to the transistor base.  
A 0.4 V voltage is created with the resistor divider **R2 + R3**.

---

## License

This project is licensed under **CC BY-NC-SA 4.0**.  
See `LICENSE.md` for full details.

### Attribution Required

If you use, adapt, or redistribute the schematics, please credit the author with one of the following links:

- https://linkedin.com/in/vytautasjanusonis  
- https://github.com/EVJ-World  

**Example attribution:**  
> Original schematic by EVJ — https://linkedin.com/in/vytautasjanusonis

---

## Support

If you found this project useful, you can support me via PayPal:  
**https://www.paypal.com/paypalme/EVJ**
