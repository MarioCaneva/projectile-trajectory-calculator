# Projectile Trajectory Calculator

This Python application calculates the trajectory of a projectile launched with a specified speed, height, and angle. The program leverages object-oriented programming principles, such as encapsulation, to ensure that the internal data is managed safely. The app calculates the displacement, coordinates, and visualizes the trajectory of the projectile using a graph.

---

## 📦 Features

- **Encapsulation**: The speed, height, and angle of the projectile are encapsulated using private attributes and managed via getter and setter methods.
- **Trajectory Calculation**: The projectile’s displacement, coordinates, and trajectory are calculated based on physics formulas.
- **Graphical Representation**: A graph is generated showing the projectile’s path using ASCII characters.
- **Data Table**: A table of coordinates is displayed to visualize the projectile's path at each point.

---

## 🧠 Concepts Practiced

- **Encapsulation**: Using private attributes (`__speed`, `__height`, `__angle`) and getter/setter methods to control access to data.
- **Projectile Physics**: Calculating displacement, velocity components, and vertical and horizontal motions.
- **Graphical Representation**: Visualizing the projectile’s trajectory using a simple graph in ASCII format.
- **OOP**: Defining classes, inheritance, and encapsulation to structure the code in an object-oriented manner.

---

## 📚 Usage Example

```python
projectile_helper(20, 230, 45)
Output:
yaml
Copy
Edit
Projectile details:
speed: 20 m/s
height: 230 m
angle: 45°
displacement: 108.2 m

  x      y
  0   230.00
  1   229.94
  2   229.76
  ...
 108   0.00

⊣                                           
⊣                                           
⊣                                           
. . . [Graph representation of trajectory]
⚙️ Functions
Projectile Class
The Projectile class contains:

Attributes: Speed, height, and angle.

Methods:

calculate_all_coordinates(): Calculates all coordinates of the projectile’s path.

__calculate_displacement(): Computes the horizontal displacement of the projectile.

__calculate_y_coordinate(): Calculates the y-coordinate at a given x-coordinate.

Graph Class
The Graph class:

Generates a coordinate table.

Visualizes the projectile's trajectory in an ASCII graph.

projectile_helper()
This helper function creates a Projectile instance, calculates coordinates, and prints the results in both table and graphical format.

🛠️ How to Run
Clone this repository to your local machine.

Run the projectile_helper() function with desired parameters:

Speed in m/s

Height in meters

Launch angle in degrees
