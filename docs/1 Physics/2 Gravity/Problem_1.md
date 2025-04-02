# Orbital Period and Orbital Radius

## Motivation
The relationship between the square of the orbital period and the cube of the orbital radius, known as **Kepler's Third Law**, is a cornerstone of celestial mechanics. This simple yet profound relationship allows for the determination of planetary motions and has implications for understanding gravitational interactions on both local and cosmic scales. By analyzing this relationship, one can connect fundamental principles of gravity with real-world phenomena such as satellite orbits and planetary systems.

## Task and Solution

### 1. Derivation of the Relationship
For a small body of mass \( m \) orbiting a much larger mass \( M \) in a nearly circular orbit, Newton’s Second Law and the gravitational force equation give:

\[
F = m a
\]

where the centripetal acceleration is given by:

\[
a = \frac{v^2}{r}
\]

The gravitational force between the two bodies is:

\[
F = \frac{G M m}{r^2}
\]

Equating the gravitational force to the centripetal force:

\[
\frac{G M m}{r^2} = m \frac{v^2}{r}
\]

Canceling \( m \) and expressing velocity in terms of the orbital period \( T \) (since \( v = \frac{2 \pi r}{T} \)):

\[
\frac{G M}{r^2} = \frac{(2\pi r)^2}{T^2 r}
\]

Rearranging, we get:

\[
T^2 = \frac{4\pi^2}{G M} r^3
\]

which confirms **Kepler's Third Law**: the square of the orbital period is proportional to the cube of the orbital radius.

### 2. Implications for Astronomy
- This relationship allows astronomers to determine planetary masses and distances in exoplanetary systems.
- It is used in calculating satellite orbits around Earth and other planets.
- The formula generalizes to elliptical orbits when replacing \( r \) with the **semi-major axis**.

### 3. Real-World Examples
- **The Moon’s Orbit Around Earth**:
  - Using Earth's mass \( M \approx 5.972 \times 10^{24} \) kg and the Moon’s orbital radius \( r \approx 3.84 \times 10^8 \) m, we can predict the Moon’s orbital period.
- **Planets in the Solar System**:
  - Kepler’s Law is used to estimate planetary years based on their distance from the Sun.

### 4. Extension to Elliptical Orbits
For elliptical orbits, the same relationship holds when \( r \) is replaced by the semi-major axis \( a \), allowing the same methodology to be applied to comets, asteroids, and exoplanets.
