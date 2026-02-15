# RPS Sim

An evolutionary Rock-Paper-Scissors population simulation with multiple strategy types and mutation support.

## Files
- `main.py`: simulation entry point and plotting
- `simulation.py`: simulation engine and day progression
- `individual.py`: individual strategy behavior
- `patch.py`: patch interactions and payoff ratios

## Run
From this folder:

```bash
python3 main.py
```

The simulation displays:
- population per strategy over time
- total population over time

## Configuration
Adjust `main()` arguments in `main.py`:
- `patches`, `days`
- `starting_counts`
- `true_mutation_chance`
- payoff settings (`winner_result`, `loser_result`, `tie_result`)
