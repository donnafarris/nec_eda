# nec_eda

An analysis of J2000 heliocentric ecliptic orbital elements for 170 NECs (Near-Earth Comets).

## Potential Avenues of Analysis

### Orbital Characteristics Analysis:

Distribution of orbital elements like eccentricity, inclination, and orbital period.
Identification of common ranges for these elements among near-Earth comets.

### Comet Population Statistics:

Number of comets with specific orbital characteristics.
Comparison of perihelion and aphelion distances to determine the average size of orbits.

### Non-Gravitational Forces:

Analysis of non-gravitational parameters (A1, A2, A3) to understand how these forces affect cometary orbits.

### Orbital Stability and Potential Hazards:

Examination of the Minimum Orbit Intersection Distance (MOID) to assess the potential risk of comet-Earth collisions.

### Temporal Analysis:

Trends in the epochs and perihelion passages to study the temporal distribution of comet observations.

### Comparative Analysis:

Comparison of known comets (like Halley's Comet) with others to identify unique or similar characteristics.

## Columns

### Categorical Columns:

- Object: Identifier of the comet.
- ref: Reference for the data.
- Object_name: Name of the comet.

### Quantitative Columns:

- Epoch (TDB): Time of the orbital elements.
- TP (TDB): Time of perihelion passage.
- e: Eccentricity of the orbit.
- i (deg): Inclination of the orbit in degrees.
- w (deg): Argument of perihelion in degrees.
- Node (deg): Longitude of the ascending node in degrees.
- q (AU): Perihelion distance in astronomical units (AU).
- Q (AU): Aphelion distance in AU.
- P (yr): Orbital period in years.
- MOID (AU): Minimum orbit intersection distance in AU.
- A1 (AU/d^2): Non-gravitational parameter A1.
- A2 (AU/d^2): Non-gravitational parameter A2.
- A3 (AU/d^2): Non-gravitational parameter A3.
- DT (d): Uncertainty in days.
