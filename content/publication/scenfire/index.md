---
title: "SCENFIRE: A flexible scenario-based algorithm for burn probability-based estimates of exposure to wildfires"
authors:
  - "M. Rodrigues"
# Si estás tú en la lista de autores, puedes usar "admin" para que se enlace a tu perfil:
- "admin"

date: "2026-01-01" # Ajusta el día y mes si los conoces
doi: "10.1016/j.jocs.2026.102937"

# Tipo de publicación (1 = Conference paper, 2 = Journal article, 3 = Preprint, etc.)
publication_types: ["2"]

# Nombre de la revista
publication: "Journal of Computational Science"
publication_short: ""

abstract: >
  Stochastic wildfire spread simulations estimate burn probability (BP) and exposure, yet traditional calibration requires iterative tuning, and repeated model runs whenever ignition patterns or scenario assumptions change. This increases computational costs and limits flexibility for risk assessments. We present SCENFIRE, a scenario-oriented algorithm deriving BP-based exposure from a precomputed library of simulated fire perimeters. The method reconstructs target fire-size distributions by probabilistically selecting and weighting simulated events while minimizing a histogram-based discrepancy metric. This post-simulation selection framework enables efficient reproduction of historical or theoretical (e.g., power-law) fire regimes without rerunning spread simulations. Benchmarked in Spain and Chile, results support that theoretical distributions achieve lower discrepancy in regions dominated by large fires, though computational demands scale with complexity. Additionally, SCENFIRE supports uncertainty estimation in annual BP and conditional BP analyses based on flame length thresholds. The framework increases flexibility in exposure modeling, providing a reproducible tool for scenario exploration.
featured: true

# Enlaces y botones personalizados
url_pdf: "https://doi.org/10.1016/j.jocs.2026.102937"
url_code: ""
url_dataset: ""

# Etiquetas (opcional, ayuda a filtrar en tu web)
tags:
  - "Wildfires"
  - "Burn Probability"
  - "Algorithms"

featured: false
---