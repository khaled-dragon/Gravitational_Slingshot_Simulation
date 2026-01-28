# 🚀 Gravitational Slingshot Simulator

An interactive 2D orbital mechanics simulation that demonstrates **Newton's Law of Universal Gravitation**. Launch spacecraft, perform gravity assists (slingshots), and explore the delicate balance of orbital physics.

## 📖 About the Project

This project started as a challenge to translate complex astrophysical equations into a functional desktop application. It simulates the gravitational pull between a massive celestial body (Jupiter) and a lightweight spacecraft.

### Key Features:
* **Real-time Physics:** Accurate calculation of gravitational force, acceleration, and velocity vectors.
* **Intuitive Controls:** Click-and-drag launch system (mimicking a slingshot) to set initial trajectory and speed.
* **Collision Detection:** Realistic handling of spacecraft crashing into the planet or escaping the system.
* **Modern Aesthetics:** A sleek "Navy Blue" space theme with high-quality assets.

---

## 🧠 The Physics Behind It

The simulation is powered by the **Newtonian Gravity** formula:

## **F** = **G** * (**m1m2** / **r^2**)

Every frame, the engine calculates the distance between the ship and the planet, determines the gravitational vector using `math.atan2`, and updates the ship's velocity using trigonometric components (`cos` and `sin`).



## 🛠️ Tech Stack

* **Language:** Python 3.10+
* **Library:** Pygame (Graphics & Event handling)
* **Math:** Native Python `math` module for vector calculations.


## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed, then install Pygame:
```bash
pip install pygame
```

## Installation & Running

1. **Clone the repository:**
```bash
git clone [https://github.com/your-username/gravitational-slingshot.git](https://github.com/your-username/gravitational-slingshot.git)
```

2. **Place your assets (background.jpg and jupiter.png) in the root folder.**

3. **Run the simulation in Terminal:**
```bash
python main.py
```

### 🕹️ How to Use:

1. **First Click:** Sets the starting position of your spacecraft.
2. **Drag:** Pull back in the opposite direction of where you want to shoot (like a bow and arrow).
3. **Release:** Launch! Watch as the planet's gravity bends your path.