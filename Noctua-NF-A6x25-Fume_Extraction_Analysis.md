# Determining Noctua NF-A6x25 Fan Suitability for Fume Extraction
  - This document provides a technical analysis demonstrating why the Noctua NF-A6x25 fan is adequate for ventilating a specified 3D printing enclosure. The analysis takes into account the volume of the enclosure, the air change rate (ACR) required for safe operation and compares these requirements against the capabilities of the Noctua NF-A6x25 fan.

## Enclosure Volume Calculation
  - Given the initial dimensions of the enclosure as 350mm x 350mm x 350mm, and accounting for an additional 50% increase in volume, the total volume is calculated as follows:
    - **Initial Volume:** `350mm x 350mm x 350mm = 42,875,000 mm³`
    - **50% Additional Volume:** `0.5 x 42,875,000 mm³ = 21,437,500 mm³`
    - **Total Volume:** `42,875,000 mm³ + 21,437,500 mm³ = 64,312,500 mm³`
    - **Converted to cubic meters (m³):** `64,312,500 mm³ / 1,000,000 = 0.0643125 m³`

## Air Change Rate (ACR) Consideration
  - For safe ventilation of ABS fumes, an ACR of 5 to 10 air changes per hour is recommended. Opting for the higher safety margin of 10 ACH:
    - **Required Airflow:** `0.0643125 m³ x 10 ACH = 0.643125 m³/h`

## Noctua NF-A6x25 Fan Specifications
  - The Noctua NF-A6x25 fan, with its specifications provided as follows, exceeds the required airflow for the calculated enclosure volume:
    - **Airflow:** `29.2 m³/h`
      - **This airflow significantly surpasses the minimum required airflow calculated for the enclosure, ensuring adequate ventilation.**

## Conclusion
  - Given the calculated required airflow of `0.643125 m³/h` for the increased volume of the 3D printing enclosure and comparing it to the Noctua NF-A6x25 fan's airflow capability of `29.2 m³/h`, it's evident that the fan provides more than sufficient airflow to meet the recommended ACR for safely venting ABS fumes. 
  - This analysis confirms the adequacy of the Noctua NF-A6x25 for this specific application, ensuring a safe environment for 3D printing activities involving ABS material.
