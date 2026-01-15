# Research Page Setup Summary

## What Was Created

I've created a new research page at `_pages/research.md` that follows the same structure as your teaching page. The page is configured to appear in your navigation menu between "people" (nav_order: 3) and "teaching" (nav_order: 4).

## Research Themes Included

The page covers four main research themes:

### 1. Interpretability of LLMs Using Geometry and Topology

- Summarizes both papers you provided (Intrinsic Dimension and Persistent Topological Features)
- Highlights prompt-level intrinsic dimension analysis
- Discusses pre-output safety screening applications
- Mentions the four processing phases discovered via zigzag persistence
- Includes placeholders for 2 figures

### 2. Topological Data Analysis for Neural Population Dynamics

- Generic description of the neuroscience work (as requested, since it's unpublished)
- Focuses on zigzag persistence for visual cortex data
- Mentions the Sensorium 2023 dataset
- Includes placeholder for 1 figure

### 3. Information Maximizing Persistent Homology

- Generic description of Fisher information optimization for filtrations (unpublished)
- Discusses the TopoFisher framework
- Highlights results from noisy circle and GRF experiments
- Includes placeholders for 2 figures

### 4. Bayesian Feature Extraction for X-ray Absorption Spectroscopy

- Generic description of NEXAFS work (unpublished)
- Focuses on uncertainty quantification and model selection
- Mentions the Ti L₂,₃ system and operando experiments
- Includes placeholders for 2 figures

## Next Steps: Adding Figures

I've created placeholder README files in `assets/img/research/` that describe what each figure should contain:

1. **llm_intrinsic_dimension.png** - ID evolution curves across layers
2. **llm_zigzag_persistence.png** - Persistence diagrams/barcodes
3. **neuroscience_zigzag.png** - Neural activity topology visualization
4. **fisher_ph_pipeline.png** - Pipeline schematic diagram
5. **fisher_ph_results.png** - Fisher information comparison results
6. **xas_bayesian_fit.png** - Spectral fit decomposition
7. **xas_posterior_corner.png** - Posterior correlation plot

To add the actual images:

1. Extract appropriate figures from your papers/thesis/posters
2. Save them as PNG files with the names listed above
3. Place them in `assets/img/research/`
4. The page will automatically display them (no code changes needed)

## Page Features

- **Navigation**: The page will appear in your main navigation menu as "research"
- **Structure**: Similar to teaching page with clear sections and horizontal rules
- **Images**: Uses Jekyll's liquid syntax for responsive image display with captions
- **Software Section**: Includes links to your open-source tools (TopoFisher, ZigZagLLMs)
- **FAIR Principles**: Mentions reproducibility and open science

## Viewing the Page

Once you commit these changes and push to GitHub, the page will be accessible at:
`https://matteo.biagetti.github.io/research/`

The page will automatically appear in your navigation menu between "people" and "teaching".

## Customization Options

If you want to modify the page further:

- **Add more details**: Edit `_pages/research.md` directly
- **Change order**: Modify `nav_order: 3.5` to a different value
- **Update descriptions**: Since some work is unpublished, you can make the descriptions more or less detailed as needed
- **Add publication links**: When papers are published, update the placeholder arXiv links

## File Structure Created

```
_pages/
  └── research.md (main page content)

assets/img/research/
  ├── README_llm_intrinsic_dimension.txt
  ├── README_llm_zigzag_persistence.txt
  ├── README_neuroscience_zigzag.txt
  ├── README_fisher_ph_pipeline.txt
  ├── README_fisher_ph_results.txt
  ├── README_xas_bayesian_fit.txt
  └── README_xas_posterior_corner.txt
```

All content has been formatted with Prettier for consistency with your existing pages.
