# 3D Mathematical Animations

This collection contains 7 comprehensive 3D mathematical animation examples using HTML, CSS, and JavaScript.

## Files Overview

### 1. 3d-rotating-cube-math.html
**Mathematical Concept:** 3D Rotation Transformations
- Displays a rotating cube with different mathematical constants on each face
- Uses CSS 3D transforms: `rotateX(θ)` and `rotateY(φ)`
- Shows: π, e, φ (golden ratio), √2, i², ∞

### 2. 3d-spiral-helix.html
**Mathematical Concept:** Parametric Equations for Helix
- Visualizes a 3D helix using parametric equations
- Equations:
  - x = r·cos(t)
  - y = r·sin(t)
  - z = h·t
- Rainbow gradient coloring based on position

### 3. 3d-wave-function.html
**Mathematical Concept:** Wave Functions in 3D
- Interactive 3D wave visualization
- Equations: z = A·sin(kx - ωt + φ₁)·cos(ky - ωt + φ₂)
- Three modes: Sine Wave, Cosine Wave, Combined
- Real-time animation with controls

### 4. 3d-fibonacci-spiral.html
**Mathematical Concept:** Fibonacci Sequence & Golden Ratio
- Visualizes the Fibonacci spiral in 3D space
- Shows Fibonacci numbers: 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233
- Demonstrates golden ratio: φ = (1 + √5) / 2 ≈ 1.618
- Each box size corresponds to Fibonacci numbers

### 5. 3d-rotating-torus.html
**Mathematical Concept:** Torus Parametric Equations
- Interactive 3D torus (donut shape)
- Parametric equations:
  - x = (R + r·cos(v))·cos(u)
  - y = (R + r·cos(v))·sin(u)
  - z = r·sin(v)
- Adjustable major radius, minor radius, and resolution

### 6. 3d-sphere-coordinates.html
**Mathematical Concept:** Spherical to Cartesian Coordinates
- 3D sphere with latitude and longitude grid
- Conversion formulas:
  - x = R·sin(θ)·cos(φ)
  - y = R·sin(θ)·sin(φ)
  - z = R·cos(θ)
- Highlights equator and poles

### 7. 3d-lorenz-attractor.html
**Mathematical Concept:** Chaos Theory - Lorenz System
- Visualizes the Lorenz attractor (butterfly effect)
- Differential equations:
  - dx/dt = σ(y - x)
  - dy/dt = x(ρ - z) - y
  - dz/dt = xy - βz
- Parameters: σ = 10, ρ = 28, β = 8/3
- Multiple trajectories showing chaotic behavior

## How to Use

1. Open any HTML file in a modern web browser
2. All animations are self-contained (no external dependencies)
3. Watch the 3D animations rotate automatically
4. For interactive examples (wave function, torus), use the provided controls

## Technical Details

- **No external libraries required** - Pure HTML, CSS, and JavaScript
- **CSS 3D Transforms** - Using `perspective`, `transform-style: preserve-3d`, `rotateX/Y/Z`, `translate3d`
- **JavaScript Animations** - Using `requestAnimationFrame` for smooth 60fps animations
- **Parametric Equations** - Mathematical formulas converted to 3D coordinates
- **Responsive Design** - Works on various screen sizes

## Educational Value

Each animation includes:
- Clear title and description
- Mathematical formulas displayed prominently
- Visual representation of abstract mathematical concepts
- Smooth, eye-catching animations to aid understanding

## Browser Compatibility

Works best in modern browsers that support:
- CSS 3D Transforms
- ES6 JavaScript
- requestAnimationFrame API

Tested on: Chrome, Firefox, Safari, Edge (latest versions)

---

Created for the htmlcss repository to demonstrate 3D mathematical visualizations using web technologies.
