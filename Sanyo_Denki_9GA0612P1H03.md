## Update: Fan Performance and Replacement

### Evaluation of Noctua NF-A6x25 Fan

After conducting a performance evaluation using a manometer, it was determined that the Noctua NF-A6x25 fan does not provide sufficient static pressure for effective fume extraction in the V-Flow system.

### New Recommended Fan: Sanyo Denki 9GA0612P1H03

To address this issue, we recommend replacing the Noctua fan with the Sanyo Denki 9GA0612P1H03. This fan offers a higher static pressure, ensuring better performance in the V-Flow system. This is a drop in replacement.

- **Product**: Sanyo Denki 9GA0612P1H03
- **Link**: [Digi-Key Product Page](https://www.digikey.com/en/products/detail/sanyo-denki-america-inc/9GA0612P1H03/6192282)

### Benefits of the Sanyo Denki 9GA0612P1H03 Fan

- **Improved Static Pressure**: The Sanyo Denki fan provides adequate static pressure, ensuring effective fume extraction even at 50% operational speed.
- **Stable Chamber Temperatures**: Operating at 50%, the fan does not significantly affect the chamber temperatures, maintaining an optimal environment for 3D printing.

### Installation Instructions

1. **Remove Existing Noctua Fan**:
   - Disconnect and remove the Noctua NF-A6x25 fan from the exhaust system.

2. **Install Sanyo Denki 9GA0612P1H03 Fan**:
   - Mount the Sanyo Denki fan in place of the Noctua fan using the same mounting points.
   - Connect the fan to the existing wiring. Ensure that the wiring is secure and that there are no loose connections.

3. **Configuration Adjustments**:
   - Update your Klipper configuration to reflect the new fan specifications. Adjust the fan speed settings to ensure optimal performance.

### Updated Klipper Configuration

```ini
[gcode_macro exhaustfanvars]
variable_speed_exhaust_fan: 0.5  # Adjusted speed for the Sanyo Denki fan
variable_exhaust_on: 0           # Tracks if the exhaust fan is on (1) or off (0)
gcode:
```
