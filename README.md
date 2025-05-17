# Genetic Algorithm String Evolution

This project demonstrates a simple genetic algorithm in Python that evolves a population of random strings to match a target string:  
**"computational cognitive science"**

## How it works

- Initializes a random population of strings (chromosomes).
- Calculates fitness based on matching characters with the target.
- Selects the best chromosomes.
- Performs crossover to produce offspring.
- Mutates offspring with a small mutation rate.
- Replaces the old population with the best chromosomes.
- Repeats until the target string is evolved.

## Usage

Run the script with:

```bash
python genetic_algorithm.ipynb
