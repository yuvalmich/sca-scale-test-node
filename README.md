# sca-scale-test

## Package Data

| Project | Total Packages | Installation Time |
|---------|----------------|-------------------|
| Small | 71 packages | 8 seconds |
| Medium | 102 packages | 6 seconds |
| Large | 395 packages | 20 seconds |
| XL | 1,633 packages | 2 minutes 23 seconds |
| XXL | 3,470 packages | 3 minutes 20 seconds |

## Repository Size Classification

The following table explains how we determined the package counts for different repository sizes:

| Repository/Project Size | Direct Packages (Estimate) | Total Packages (Direct + Transitive) | Rationale |
|-------------------------|----------------------------|--------------------------------------|-----------|
| Small (e.g., Microservice, Toy Project) | 5 - 15 | 20 - 75 | Uses a few core libraries (e.g., web framework, logging). The transitive dependencies are manageable. |
| Medium (e.g., Standard Web App, Mid-Sized Library) | 15 - 30 | 75 - 300 | Needs more specialized tools (database connectors, authentication, a testing suite, utility libraries). The transitive fan-out grows rapidly. |
| Large (e.g., Monolith, Complex Enterprise Application) | 30 - 80+ | 300 - 1,000+ | Requires a broad range of capabilities, often integrates with many external services, and likely has a history of adding—but rarely removing—dependencies. |
