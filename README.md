# Simple Energy Calculator

This Python script calculates the amount of energy required to move an object based on its weight and the distance between two points.

## How to Use

1. Clone this repository to your local machine.

```bash
github repo clone Statute8234/simple-Energy-calculation-program
```

4. Follow the prompts to input the weight of the object in pounds and the distance between point A and point B in meters.

5. The script will calculate and display the amount of energy required in joules to move the object the specified distance.

## Requirements

- Python 3.x

## Usage

```python
from object_energy_calculator import Object

weight = float(input("Enter the weight of the object in pounds: "))
distance = float(input("Enter the distance between point A and B in meters: "))

obj = Object(weight, distance)
print("You need", obj.J, "joules of energy to move the object", distance, "meters.")
```

## License

NONE
