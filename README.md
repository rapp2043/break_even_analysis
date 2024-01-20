# Cost-Benefit Analysis of Transitioning from Traditional Instructor-Led Training to Computer-Based Training
This repository contains the R scripts and documentation for a comprehensive cost-benefit analysis for transitioning a training program to eLearning. 

## Overview
This repository contains the R scripts and documentation for a comprehensive cost-benefit analysis to support the decision-making process for transitioning a training program from Instructor-Led Training (ILT) to Computer-Based Training (CBT) modules. The analysis estimates redevelopment costs, operational savings, and the break-even point, focusing on maintaining or enhancing learning quality and experience.

## Repository Structure
- `README.md`: Detailed project overview, including the methodology and key findings.
- `cost_benefit_analysis.Rmd`: R Markdown document that contains the full analysis, from data preprocessing to final visualization.
- `data/`: Directory containing any data files used in the analysis (if applicable and shareable).
- `output/`: Generated reports and graphs in various formats (PDF, Word, HTML).
- `scripts/`: Individual R scripts for specific parts of the analysis, such as cost calculations and savings projections.

## Methodology
The project is structured around a series of R scripts and an R Markdown document, which together define the variables, perform calculations, and create visualizations to support the analysis. Key components include:

- Redevelopment cost calculations for CBT modules.
- Operational savings estimates from transitioning to CBTs.
- Break-even point analysis to determine when the transition costs will be offset by the savings.
- Predictive modeling for future savings.
- Survey analysis framework for post-transition assessments of learning quality and experience.

## Key Findings
- The break-even point for the transition from ILT to CBT is achieved after the delivery of just three CBT sessions.
- Cumulative savings increase exponentially with the delivery of additional CBT sessions.
- A predictive savings model indicates significant long-term cost reductions while maintaining or improving training quality.

## Visualization
The repository includes a break-even analysis plot generated using `ggplot2`, illustrating the cost savings over time as compared to the initial redevelopment investment.

## Usage
To replicate the analysis or adapt the methodology to a similar context:

1. Clone the repository.
2. Run the `cost_benefit_analysis.Rmd` in RStudio to generate the full report.
3. Utilize the scripts in the `scripts/` directory for specific analytical tasks.

## Contributing
Suggestions and contributions are welcome via pull requests or issues. Please ensure that any contributions are well-documented and include updated tests where necessary.

## License
This project is open-source and available for use in other personal projects.
