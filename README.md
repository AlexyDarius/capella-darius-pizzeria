# Pizzeria System Model with Capella (MBSE)

Welcome to the **Pizzeria System Model**, a detailed Model-Based Systems Engineering (MBSE) project built using [Capella](https://www.eclipse.org/capella/). This repository contains a comprehensive model of a pizzeria’s operations—covering ordering, payment, kitchen, delivery, and management subsystems—designed to optimize efficiency and serve as a training ground for MBSE and Capella. The project was developed solo by Alexy Roman as of April 10, 2025, with plans to derive educational courses, business-owner summary and start to implement digital tools in pilot pizzerias.

## Project Overview

This project models a single-location pizzeria with a various charge range (1-10 staff, 20-200 orders/day) using the Arcadia methodology in Capella. It spans all four Arcadia layers—Operational Analysis (OA), System Analysis (SA), Logical Architecture (LA), and Physical Architecture (PA)—to create a traceable, end-to-end system representation. Key goals include reducing order-to-delivery time, minimizing inventory waste, and balancing staff quantity and workload during peak hours.

### Objectives
- **Technical**: Build a rigorous MBSE model to master Capella and explore pizzeria optimization.
- **Educational**: Provide a foundation for future MBSE/Capella courses.
- **Practical**: 
	- Offer insights adaptable for pizzeria owners (via a future summary).
	- Derive digitalisation projects.

## Model Details

### Scope
- **Subsystems**:
  1. **Ordering**: On-site (staff, kiosk) and web (app, website).
  2. **Payment**: Cash, card, online gateways.
  3. **Kitchen**: Order preparation, inventory management, workflow.
  4. **Delivery**: Driver assignment, routing, tracking.
  5. **Management**: Sales analytics, inventory forecasting.
- **Optimizations**:
  - Queue management for peak-hour order balancing.
  - Web and self-ordering.
  - Automated inventory restocking triggers.
  - Delivery route optimization.

### Tools Used
- **Capella**: Version 6.1.0 for modeling.
- **Draw.io**: Pre-model sketches.
- **Excel/Google Sheets**: Requirements and data tracking.
- **Markdown**: Documentation.

## Getting Started

### Prerequisites
- Capella installed (download from [eclipse.org/capella](https://www.eclipse.org/capella/)).
- Basic understanding of MBSE and the Arcadia methodology.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/[your-username]/pizzeria-system-model.git
 2.  Open the Capella model:
    -   Launch Capella.
    -   Import models/Pizzeria_System/*.aird into your workspace.
3.  Explore the diagrams and documentation in docs/.

### Usage

-   Navigate the model in Capella to explore each layer (OA → PA).
-   Refer to docs/Technical_Report.md for a detailed walkthrough.
-   Use research_notes.md for context on pizzeria assumptions.
- 
## Future Work

-   Derive MBSE/Capella courses from this model.
-   Create a simplified deliverable for pizzeria owners (e.g., 5-10 page PDF).
-   Create digitial tool to optimise oredring and payment.
-   Expand to multi-location pizzeria chains or additional subsystems (e.g., staff scheduling).

## Contributing

This is a solo project for now, but feedback is welcome! Open an issue or submit a PR if you spot improvements or want to collaborate on future iterations.

## License


Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)

Copyright (c) 2025 Alexy Roman

This work is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License. 
To view a copy of this license, visit http://creativecommons.org/licenses/by-nc/4.0/ or send a letter to 
Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

Summary: You are free to share (copy and redistribute) and adapt (remix, transform, build upon) the material  for non-commercial purposes, as long as you give appropriate credit to Alexy Roman. 
Commercial use requires  explicit permission from the author.

## Contact

-   GitHub: AlexyDarius
-   Email: dev@alexyroman.com
