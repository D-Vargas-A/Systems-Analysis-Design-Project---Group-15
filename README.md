# Workshop 1 - Systems Analysis of PAKDD Cup 2014 Competition

## Team Members
- *David Eduardo Muñoz Mariño* - 20232020281
- *Daniel Vargas Arias* - 20232020103
- *Juan Esteban Moreno Durán* - 20232020097
- *Julián Darío Romero Buitrago* - 20232020240

*Course*: Systems Analysis & Design  
*Semester*: 2025-III  
*Professor*: Eng. Carlos Andrés Sierra, M.Sc.  
*Program*: Computer Engineering  
*Institution*: Universidad Distrital Francisco José de Caldas

## Competition Overview

This analysis focuses on the *PAKDD Cup 2014* Kaggle competition: "ASUS Malfunctional Components Prediction". The competition challenges participants to predict future malfunctional components in ASUS notebooks based on historical data, directly impacting inventory management, customer satisfaction, and operational costs.

*Competition Link*: [https://www.kaggle.com/competitions/pakdd-cup-2014](https://www.kaggle.com/competitions/pakdd-cup-2014)

## Repository Structure


workshop-1/
├── README.md                           # This file
├── pakdd_systems_analysis.tex          # LaTeX source code
├── pakdd_systems_analysis.pdf          # Final report (PDF)
├── diagrams/                           # Visual representations
│   ├── system_architecture.png
│   ├── data_flow_diagram.png
│   └── component_interaction_map.png
└── references/                         # Supporting materials
    └── competition_data_overview.md


## Methodology

Our systems analysis approach followed a comprehensive framework incorporating multiple analytical perspectives:

### 1. *Systems Engineering Analysis*
- *Requirements Identification*: Defined functional and non-functional requirements for the prediction system
- *Architecture Design*: Developed a layered architecture approach (Data → Processing → Application layers)
- *Lifecycle Considerations*: Analyzed development, deployment, and maintenance phases

### 2. *Element Identification and Relationship Mapping*
- *Core Components*: Hardware elements, manufacturing processes, usage patterns, temporal factors
- *Data Elements*: Input features, target variables, contextual information
- *Process Elements*: Data collection, prediction models, decision support systems
- *Inter-relationships*: Causal relationships, feedback loops, and data flow architecture

### 3. *Complexity and Sensitivity Analysis*
- *Constraint Analysis*: Technical limitations (data quality, computational limits) and business constraints (budget, compliance)
- *Sensitivity Assessment*: Categorized parameters by sensitivity levels (high, medium, low impact)
- *Conflict Identification*: Trade-offs between accuracy vs. efficiency, false positives vs. negatives

### 4. *Chaos Theory Application*
- *Chaotic Behavior*: Non-linear dynamics, sensitive dependence on initial conditions
- *Feedback Loop Analysis*: Positive and negative feedback mechanisms
- *Stochastic Elements*: Random processes and uncertainty sources in the system

### 5. *Visual System Representation*
Created comprehensive diagrams using TikZ in LaTeX:
- System Architecture Diagram
- Data Flow Diagram  
- Component Interaction Map

## Tools and Technologies Used

- *LaTeX*: Document preparation and professional formatting
- *TikZ/PGF*: Technical diagram creation
- *Systems Thinking Frameworks*: For comprehensive analysis approach
- *Web Research*: Competition background and technical context
- *Git*: Version control for collaborative development

## Key Findings

### System Strengths
- Rich historical data providing solid foundation for predictive modeling
- Clear business value proposition with direct operational impact
- Well-defined problem scope with measurable success criteria
- Strong feedback mechanisms enabling continuous improvement

### System Weaknesses
- High sensitivity to external factors beyond system control
- Complex interdependencies making failure prediction challenging
- Potential for chaotic behavior reducing prediction reliability
- Significant computational requirements for real-time processing

### Critical Success Factors
- Data quality management as foundational requirement
- Robust model validation and testing procedures
- Effective integration with existing business processes
- Continuous monitoring and adaptive learning capabilities

## Analysis Approach

1. *Competition Research*: Comprehensive study of the PAKDD Cup 2014 problem statement, objectives, and business context
2. *Systems Decomposition*: Breaking down the competition into fundamental elements and analyzing their relationships
3. *Multi-perspective Analysis*: Applying systems engineering, complexity theory, and chaos theory lenses
4. *Visual Modeling*: Creating clear, technical diagrams to illustrate system structure and dynamics
5. *Critical Assessment*: Identifying strengths, weaknesses, opportunities, and threats within the system

## Future Work

This analysis serves as the foundation for subsequent workshops in the course. Future extensions may include:

- *Technical Implementation*: Developing actual prediction models using the analyzed framework
- *System Extensions*: Expanding analysis to other product categories and industries
- *Performance Optimization*: Addressing identified weaknesses and constraints
- *Real-world Validation*: Testing theoretical findings against practical implementations

## References and Sources

- PAKDD Cup 2014 Competition documentation and datasets
- Systems engineering principles and methodologies
- Chaos theory and complex systems literature
- Machine learning and predictive maintenance research
- Industry best practices for reliability engineering

## Report Access

📄 *Final Report*: [pakdd_systems_analysis.pdf](./pakdd_systems_analysis.pdf)

The complete analysis report is available in PDF format, containing detailed technical analysis, visual diagrams, and comprehensive conclusions based on our systems thinking approach.

## Contact Information

For questions or clarifications regarding this analysis, please contact any team member or refer to the course instructor:

*Instructor*: Eng. Carlos Andrés Sierra, M.Sc.  
*Email*: cavirguzs@udistrital.edu.co

---

This project was completed as part of the Systems Analysis & Design course requirements at Universidad Distrital Francisco José de Caldas, demonstrating application of systems thinking principles to real-world data science competitions.
