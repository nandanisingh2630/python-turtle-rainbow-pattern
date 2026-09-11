#Python Turtle Rainbow Pattern

A colorful and mesmerizing **generative art project built with Python Turtle**. The program creates a beautiful rainbow flower/spiral pattern by combining circular movements, nested loops, rotations, and continuously changing HSV colors.

## ✨ Features

* 🐢 Built using Python Turtle
* 🌈 Dynamic rainbow color generation
* 🌀 Creates a flower-like spiral pattern
* ⚡ Uses Turtle's fastest drawing speed
* 🎨 Uses mathematical and geometric movements
* 💻 Requires no external libraries

## 🛠️ Technologies Used

* **Python 3**
* `turtle`
* `colorsys`

Both modules are available in Python's standard library.

## 📂 Project Structure

```text
python-turtle-rainbow-pattern/
│
├── rainbow_pattern.py
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/python-turtle-rainbow-pattern.git
```

### 2. Open the project directory

```bash
cd python-turtle-rainbow-pattern
```

### 3. Run the Python program

```bash
python rainbow_pattern.py
```

A Turtle graphics window will open and generate the colorful pattern.

## 🎨 How It Works

The program uses nested loops to repeatedly draw circular shapes while changing their direction and size.

The main steps are:

1. Set Turtle speed to maximum.
2. Set the background color to black.
3. Generate colors using HSV color conversion.
4. Gradually increase the hue value to create a rainbow effect.
5. Draw circular arcs using different radii.
6. Rotate the Turtle after each shape.
7. Repeat the process to create the final flower-like design.

## 🌈 Color Generation

The project uses:

```python
colorsys.hsv_to_rgb(h, 1, 1)
```

The `h` value changes gradually during the drawing process, producing a smooth sequence of colors across the artwork.

## 🧠 Concepts Practiced

This project demonstrates:

* Python loops
* Nested loops
* Functions and modules
* Turtle graphics
* RGB and HSV colors
* Mathematical patterns
* Circular geometry
* Iterative design
* Generative art

## 🎯 Learning Objective

The project was created to practice Python programming concepts while exploring **creative coding and generative art**.

It shows how simple loops, mathematical movements, and color transformations can be combined to create complex visual designs.

## 🔮 Future Improvements

Possible improvements include:

* Add animation effects
* Allow users to choose colors
* Create multiple pattern styles
* Add keyboard controls
* Allow users to customize the number of layers
* Save the generated artwork as an image
* Add a GUI for pattern customization

## 👩‍💻 Author

**Nandani Singh**

BCA – Artificial Intelligence

Interested in **Python, Data Analytics, AI/ML, and Software Development**.

⭐ If you like this project, consider giving the repository a star!
