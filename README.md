# BIOLAB

BIOLAB is a static, browser-based computational biology sandbox. It prioritizes transparent methods, reproducible simulations, and explicit limitations over clinical or structural claims that the local models cannot support.

## Modules

- **Genetic Algorithm**: seeded DNA sequence optimization with per-generation fitness and diversity.
- **CRISPR Guide Explorer**: strand-aware SpCas9 and Cas12a PAM discovery, basic sequence-quality ranking, and design warnings.
- **Protein Sequence Explorer**: molecular weight, estimated pI, GRAVY, net charge, hydrophobicity, and a conceptual 3D residue trace.
- **Cellular Automata**: seeded qualitative rule systems with single-generation stepping.
- **Research Hub**: curated primary sources and regulator pages with evidence and limitation labels, verified 7 June 2026.

## Run locally

No build step is required. Start a local server:

```powershell
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Test

```powershell
node tests/bio-utils.test.js
```

## Scientific scope

The CRISPR score is a transparent sequence heuristic, not an on-target model or genome-wide off-target prediction. The protein trace is not a predicted structure. Cellular automata are qualitative toy rules, not calibrated biological models. Use the exported JSON to record configurations and results.
