# Interference Patterns on a Water Surface

## Motivation
Interference occurs when waves from different sources overlap, creating new patterns. On a water surface, this can be easily observed when ripples from different points meet, forming distinctive interference patterns. These patterns can show us how waves combine in different ways, either reinforcing each other or canceling out.

Studying these patterns helps us understand wave behavior in a simple, visual way. It also allows us to explore important concepts, like the relationship between wave phase and the effects of multiple sources. This task offers a hands-on approach to learning about wave interactions and their real-world applications, making it an interesting and engaging way to dive into wave physics.

## Task and Solution

### 1. Select a Regular Polygon
Let's choose an **equilateral triangle** for simplicity. We place three point wave sources at the vertices of this triangle.

### 2. Position the Sources
Let the wave sources be located at the vertices of the equilateral triangle in the 2D plane. Each source emits circular waves with the same frequency, amplitude, and wavelength. The displacement of the water surface at any point $ P $ on the surface, at time $ t $, will be influenced by the superposition of the waves from all the sources.

### 3. Wave Equations
The wave emitted from a point source at position $ \vec{r}_i $ (where $ i $ is the index for the source) is given by:

$$
\psi_i(\vec{r}, t) = A \cos(k |\vec{r} - \vec{r}_i| - \omega t + \phi_i)
$$

Where:
- $ A $ is the amplitude of the wave,
- $ k = \frac{2\pi}{\lambda} $ is the wave number (related to the wavelength $ \lambda $),
- $ \omega = 2\pi f $ is the angular frequency (related to the frequency $ f $),
- $ |\vec{r} - \vec{r}_i| $ is the distance between the observation point $ P $ and the source $ \vec{r}_i $,
- $ \phi_i $ is the phase of the wave from the source at time $ t = 0 $.

### 4. Superposition of Waves
The total displacement at point $ \vec{r} $ is the sum of the displacements from all $ N $ sources. For the equilateral triangle, where the sources are at $ \vec{r}_1, \vec{r}_2, \vec{r}_3 $, the total displacement $ \psi(\vec{r}, t) $ is:

$$
\psi(\vec{r}, t) = \sum_{i=1}^{N} \psi_i(\vec{r}, t)
$$

For three sources:

$$
\psi(\vec{r}, t) = A \sum_{i=1}^{3} \cos(k |\vec{r} - \vec{r}_i| - \omega t + \phi_i)
$$

### 5. Analyze Interference Patterns
To understand the interference patterns, we need to look at the resulting displacement $ \psi(\vec{r}, t) $ as a function of the position $ \vec{r} $ and time $ t $

- **Constructive Interference** occurs when the waves from the sources are in phase, leading to larger amplitudes at certain points. This happens when the distance to each source is such that the phases align.
  
- **Destructive Interference** occurs when the waves from the sources are out of phase, leading to cancelation. This happens when the distances to each source result in phase differences that cause the waves to cancel each other out.

### 6. Visualization
We can now visualize the interference pattern formed by the superposition of the waves from the three sources. A graphical representation of the surface displacement can help identify regions of constructive and destructive interference.

#### Example for an Equilateral Triangle:

Consider an equilateral triangle where the wave sources are positioned at the vertices. We can simulate and visualize the interference pattern as follows:

1. **Amplitude Plot**: A 2D plot showing the displacement at different points on the water surface.
2. **Interference Zones**: Areas where the waves reinforce each other (constructive interference) and where they cancel each other out (destructive interference).

#### Simulated Interference Pattern:

For simplicity, we could simulate the behavior using a basic numerical model where we calculate the displacement $ \psi(\vec{r}, t) $ at each point in space and color the points based on their amplitude.

### 7. Considerations
- **Coherent Sources**: All sources emit waves with the same frequency, wavelength, and amplitude, and they maintain a constant phase difference.
- **Wave Propagation**: The waves spread outward in all directions from the point sources, and their superposition can be studied by examining the resulting displacement at various points on the surface.

### 8. Real-World Applications
Interference patterns on water surfaces have real-world analogs in optics, acoustics, and other fields. The principle of superposition is used to analyze wave interactions in:

- **Optical Interference**: Diffraction patterns in double-slit experiments.
- **Acoustic Waves**: Sound interference in open spaces.
- **Water Wave Phenomena**: The interaction of ripples in oceans, lakes, and ponds.

---

## Deliverables
- **Markdown Document**: Explaining the task and solution, including wave equations and superposition principles.
- **Graphical Representations**: Visualizing the interference patterns for the equilateral triangle configuration.
- **Discussion**: Explaining the constructive and destructive interference regions observed in the simulation.

---