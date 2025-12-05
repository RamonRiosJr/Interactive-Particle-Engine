**Interactive Particle Engine**

**📖 Introduction**

A high-performance, web-based particle physics simulation built with **Vanilla JavaScript** and the **HTML5 Canvas API**. This project demonstrates complex state management, object-oriented programming, and real-time rendering logic.

**🚀 Live Demo**

&lt;!-- Replace this link with your Github Pages URL or deployment link --&gt;

[View Live Demo](https://www.google.com/search?q=%23)

**📋 Overview**

The **Interactive Particle Engine** is a configuration tool designed for developers and designers to experiment with particle effects. It allows users to simulate different elemental materials (Water, Lava, Acid) and tweak physical properties like gravity, wind, and velocity in real-time.

It includes a visual editor where users can place emitters directly on a canvas and export the configuration as JSON, making it a viable tool for game level design or visual effects testing.

**✨ Key Features**

**🌋 Multi-Element Simulation**

Switch between distinct element types, each with unique physical behaviors and visual styles:

- **Water:** Standard gravity, blue palette, varying opacity.
- **Lava:** Low gravity (floaty), turbulence, additive glow effects.
- **Acid:** Fizzing motion, high gravity, neon green palette.

**🎛️ Real-Time Physics Configurator**

Dynamic control over the simulation engine:

- **Gravity & Wind:** Apply directional forces to all particles globally.
- **Velocity:** Control the initial emission force.
- **Spread:** Adjust the angular variance of particle emission.

**🛠️ Developer Tools**

- **Visual Debugging:** Emitters are visualized with crosshairs for precise placement.
- **JSON Export:** Instantly export the current state (physics settings + emitter locations) to the console for use in external applications.
- **Responsive Canvas:** The engine automatically handles window resizing and asset loading states.

**💻 Technical Highlights**

This project relies on **no external framework dependencies** for the core logic, demonstrating raw proficiency in JavaScript.

- **Object-Oriented Architecture:** Uses ES6 Classes (Particle, Emitter) to encapsulate logic, making the system modular and extensible.
- **Canvas Optimization:** Utilizes requestAnimationFrame for a smooth 60fps rendering loop.
- **Composite Operations:** Implements globalAlpha and shadowBlur for advanced visual effects like glowing lava.
- **State Management:** A central config object drives the simulation, allowing for immediate reactivity to UI inputs.

**📦 Installation & Usage**

- **Clone the repository:**
- git clone \[<https://github.com/yourusername/particle-engine.git\>](<https://github.com/yourusername/particle-engine.git>)
- **Open the project:** Simply open index.html in any modern web browser. No build step or server is required.

**🔧 Code Structure**

// Core configuration object driving the physics engine

const config = {

element: 'water',

gravity: 0.5,

velocity: 5,

// ...

};

// The Particle class handles individual physics calculations per frame

class Particle {

update() {

// Applies gravity, wind, and element-specific turbulence

}

draw(context) {

// Renders the particle based on lifecycle and opacity

}

}

**📄 License**

This project is open source and available under the [MIT License](https://www.google.com/search?q=LICENSE).
