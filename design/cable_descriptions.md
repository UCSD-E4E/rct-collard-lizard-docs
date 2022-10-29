# Battery Distribution Spider
| Parameter      | Value                  |
|----------------|------------------------|
| Termination 1  | Lead Acid Battery Lugs |
| Termination 2a | XT30-F                 |
| Termination 2b | XT30-F                 |
| Cable Type     | 16 AWG                 |
| Cable Length   | 18.0 in                |

# Sleep Timer Power Cable
| Parameter     | Value              |
|---------------|--------------------|
| Termination 1 | XT30-M             |
| Termination 2 | 2x 0.1 in Header F |
| Cable Type    | 22 AWG             |
| Cable Length  | 3.0 in             |

# Power Switch Control Cable
| Parameter     | Value              |
|---------------|--------------------|
| Termination 1 | 2z 0.1 in Header F |
| Termination 2 | 2x 0.1 in Header F |
| Cable Type    | 22 AWG             |
| Cable Length  | 3.0 in             |

# Sleep Timer to OBC Comms Cable
| Parameter     | Value              |
|---------------|--------------------|
| Termination 1 | 4z 0.1 in Header F |
| Termination 2 | 4x 0.1 in Header F |
| Cable Type    | 22 AWG             |
| Cable Length  | 6.0 in             |

Use 2x, PC817 Optocouplers, 4x 1k resistors

```
P1.1 = Tx
P1.2 = GND
P1.3 = Rx
P1.4 = 3v3

P2.1 = Tx
P2.2 = GND
P2.3 = Rx
P2.4 = 3v3

U1.1 = Anode
U1.2 = Cathod
U1.3 = Emitter
U1.4 = Collector

U2.1 = Anode
U2.2 = Cathod
U2.3 = Emitter
U2.4 = Collector

R1 = 330
R2 = 1k
R3 = 330
R4 = 1k

P1.1 <-> R1.1
R1.2 <-> U1.1
P1.2 <-> U1.2, R2.1
P1.3 <-> R2.2, U2.3
P1.4 <-> U2.4
P2.1 <-> R3.1
R3.2 <-> U2.1
P2.2 <-> U2.2, R4.1
P2.3 <-> R4.2, U1.3
P2.4 <-> U1.4
```

# Data Drive Cable
| Parameter     | Value     |
|---------------|-----------|
| Termination 1 | USB 3.0 A |
| Termination 2 | USB 3.0 C |
| Cable Length  | 6.0 in    |

# GPS Cable
| Parameter     | Value      |
|---------------|------------|
| Termination 1 | USB 3.0 A  |
| Termination 2 | USB Device |
| Cable Length  | 6.0 in     |

# Wifi Antenna
| Parameter     | Value    |
|---------------|----------|
| Termination 1 | u.fl     |
| Termination 2 | RP-SMA M |
| Cable Type    | RG316    |
| Cable Length  | 6.0 in   |

# OBC to SDR Cable
| Parameter     | Value           |
|---------------|-----------------|
| Termination 1 | USB 2.0 A       |
| Termination 2 | USB 2.0 micro B |
| Cable Length  | 6.0 in          |

# SDR to DC Block Cable
| Parameter     | Value  |
|---------------|--------|
| Termination 1 | SMA-M  |
| Termination 2 | SMA M  |
| Cable Type    | RG316  |
| Cable Length  | 3.0 in |

# DC Block to LNA Cable
| Parameter     | Value  |
|---------------|--------|
| Termination 1 | SMA-M  |
| Termination 2 | SMA M  |
| Cable Type    | RG316  |
| Cable Length  | 3.0 in |

# LNA to Antenna Cable
| Parameter     | Value    |
|---------------|----------|
| Termination 1 | SMA-M    |
| Termination 2 | SMA M    |
| Cable Type    | RG316    |
| Cable Length  | 120.0 in |

# Switched 12V Cable
| Parameter      | Value  |
|----------------|--------|
| Termination 1  | XT30-M |
| Termination 2a | XT30-F |
| Termination 2b | XT30-F |
| Cable Type     | 16 AWG |
| Cable Length   | 3.0 in |

# Switched 5V Splitter
| Parameter      | Value             |
|----------------|-------------------|
| Termination 1  | XT30-M            |
| Termination 2a | 5.5mm Barrel Plug |
| Termination 2b | USB 2.0 micro B   |
| Cable Type     | 22 AWG            |
| Cable Length   | 6.0 in            |
