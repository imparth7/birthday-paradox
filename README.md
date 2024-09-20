# Birthday Paradox Simulation

This Python program simulates the Birthday Paradox, which demonstrates the surprising probability that in a group of people, at least two individuals will share the same birthday.

## Table of Contents

- [Introduction](#introduction)
- [How It Works](#how-it-works)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Example Output](#example-output)
- [License](#license)

## Introduction

The Birthday Paradox shows that in a group of just 23 people, there's a surprisingly high chance (over 50%) that two of them share the same birthday. This program uses a Monte Carlo simulation to explore this phenomenon and calculate the probability of shared birthdays in a specified group size.

## How It Works

1. The program generates a specified number of random birthdays.
2. It checks for any matching birthdays among the generated list.
3. It runs multiple simulations (100,000 by default) to calculate the probability of matching birthdays.

## Getting Started

To run this program, you'll need Python installed on your machine. You can download Python from [python.org](https://www.python.org/downloads/).

### Prerequisites

- Python 3.x

## Usage

1. Clone this repository or download the `birthday_paradox.py` file.
2. Open your terminal or command prompt.
3. Navigate to the directory containing the `birthday_paradox.py` file.
4. Run the program using the command:

   ```bash
   python birthday_paradox.py
   ```

5. Follow the prompts to input how many birthdays to generate (maximum 100).

## Example Output

```
How many birthdays shall I generate? (Max 100)
> 23

Here are 23 birthdays:
Jan 1, Feb 2, Mar 3, Apr 4, May 5, Jun 6, Jul 7, Aug 8, Sep 9, Oct 10, Nov 11, Dec 12, Jan 2, ...

In this simulation, multiple people have a birthday on Jan 2.

Generating 23 random birthdays 100,000 times...
100,000 simulations run.
Out of 100,000 simulations of 23 people, there was a matching birthday in that group 50712 times. This means that 23 people have a 50.71% chance of having a matching birthday in their group.
That's probably more than you would think!
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
