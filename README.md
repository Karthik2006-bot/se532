
# Weather Modeling using Quadratic Equation

This project models temperature changes over a given number of days using a quadratic equation of the form:

$$
T(day) = a \cdot day^2 + b \cdot day + c
$$

It takes user input for coefficients and plots the resulting temperature trend.

## Features

* Accepts quadratic equation coefficients from the user or uses fixed values.
* Models temperature variation for a given number of days.
* Generates a plot using `matplotlib`.

## Requirements

* Python 3.x
* `matplotlib`

Install dependencies:

```bash
pip install matplotlib
```

## Usage

### Run in Local Environment

1. Clone or download the repository.
2. Open the notebook `task3_(532)_pynb.ipynb` in Jupyter or run as a `.py` script.
3. Provide the following inputs when prompted:

   * Quadratic coefficient (**a**)
   * Linear coefficient (**b**)
   * Constant term (**c**)
   * Number of days to model
4. A graph of temperature vs. day will be displayed.

### Run in Google Colab

Click the badge below to open in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Karthik2006-bot/se532/blob/main/task3_%28532%29_pynb.ipynb)

## Example

**Input:**

```
a = 2
b = -5
c = 20
Days = 10
```

**Output:**
A plotted curve showing temperature changes from day 0 to day 10.
