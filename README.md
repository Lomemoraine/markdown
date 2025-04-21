| Feature | Description                  | Attack Relevance                                                                 | Attack Example                                  |
|---------|------------------------------|---------------------------------------------------------------------------------|------------------------------------------------|
| LIT101  | Water tank level (mm)        | **Overflow/Underflow**: Sudden spikes/drops may indicate tank manipulation.     | Attacker falsifies level readings to cause flooding. |
| FIT101  | Inflow water rate (L/s)      | **Flow Tampering**: Abnormal rates suggest pipe leaks or valve interference.    | Unauthorized valve closure disrupting supply.      |
| AIT202  | Chlorine concentration (mg/L)| **Chemical Sabotage**: Deviations risk unsafe water quality.                    | Injecting excess chlorine to poison water.         |
| DPIT301 | UF pressure (kPa)            | **Membrane Damage**: Pressure spikes indicate physical/cyber damage to filters. | Forcing overpressure to rupture membranes.         |
| P101    | Pump status (On/Off)         | **Unauthorized Control**: Unexpected shutdowns disrupt water flow.              | Stopping pumps via malicious Modbus commands.      |# markdown
