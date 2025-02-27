# Mean-Variance-Standard-Deviation-Calculator
# Mean-Variance-Standard Deviation Calculator

## Description
This project is a Python-based **Mean-Variance-Standard Deviation Calculator** that computes statistical values (mean, variance, standard deviation, max, min, and sum) for a given 3x3 matrix. The program uses **NumPy** for efficient numerical computations.

## Features
- Takes a list of 9 numbers as input
- Converts the list into a 3x3 NumPy array
- Computes the following statistical values along rows, columns, and the entire matrix:
  - Mean
  - Variance
  - Standard Deviation
  - Maximum
  - Minimum
  - Sum
- Raises an error if the input list contains fewer than 9 elements

## Installation
### Prerequisites
Ensure you have **Python 3.x** installed. You can check your Python version using:
```sh
python --version
```

### Install Dependencies
The project requires **NumPy**. Install it using:
```sh
pip install numpy
```

## Usage
### Running the Script
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/mean-var-std-calculator.git
   cd mean-var-std-calculator
   ```
2. Run the script:
   ```sh
   python main.py
   ```

### Example Input & Output
#### **Input:**
```python
from mean_var_std import calculate
print(calculate([0,1,2,3,4,5,6,7,8]))
```

#### **Output:**
```json
{
  "mean": [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  "variance": [[6.0, 6.0, 6.0], [0.6666666666666666, 0.6666666666666666, 0.6666666666666666], 6.666666666666667],
  "standard deviation": [[2.449489742783178, 2.449489742783178, 2.449489742783178], [0.816496580927726, 0.816496580927726, 0.816496580927726], 2.581988897471611],
  "max": [[6, 7, 8], [2, 5, 8], 8],
  "min": [[0, 1, 2], [0, 3, 6], 0],
  "sum": [[9, 12, 15], [3, 12, 21], 36]
}
```

## Error Handling
If the input list does not contain exactly 9 numbers, the program raises an error:
```python
ValueError: List must contain nine numbers.
```

## Contributing
Feel free to fork this repository and submit pull requests with improvements or bug fixes!

## License
This project is licensed under the MIT License.

## Contact
For any questions or support, reach out via [your-email@example.com](mailto:your-email@example.com).

