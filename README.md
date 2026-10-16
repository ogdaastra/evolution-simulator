# EVOLVER | Artificial Life Laboratory

A standalone, browser-based artificial-life and evolution simulator. It runs locally in your browser with no build step, account, external libraries, or network requests.

## Run it

Open [index.html](./index.html) in a modern browser, or enable GitHub Pages to host it as a website.

## Experiments and features

- Explore a spatial population of organisms with five heritable traits: camouflage, speed, cold tolerance, heat tolerance, and disease resistance.
- Adjust food availability, temperature, predator pressure, mutation rate, reproduction, migration, and climate regime.
- Trigger environmental events such as drought, sudden freeze, wildfire, disease, resource bloom, isolation, and catastrophic impact.
- Load presets for camouflage, ice-age selection, predator–prey pressure, bottlenecks, island habitats, and elevated mutation.
- Track population size, mean fitness, trait means, diversity, and generation history.
- Save session snapshots, compare a snapshot with the current population, and export CSV history or JSON state.

## Scientific limitations

EVOLVER is an educational agent-based model, not a validated prediction of any real species. Fitness and environmental effects are simplified heuristics; the model does not represent real loci/chromosomes, explicit sexes, dominance, full recombination, calibrated ecological rates, or genuine divergence among multiple populations. Results are illustrative and stochastic. Run replicated experiments before drawing conclusions about selection versus random drift.

## Reproducibility

Set the random seed before resetting the experiment. Reproduction of a run also depends on using the same sequence of controls and events in the same implementation.

## License

No license has been specified yet. Add a license file if you intend to define reuse permissions.
