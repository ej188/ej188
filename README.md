# Eunjae Yu

### Applied machine learning · Data science · Industrial data systems

I connect operational data, predictive models, and the decisions they support. My work spans industrial sensor integration, equipment-health analysis, demand forecasting, and applied LLM workflows. I focus on understanding the data, making validation explicit, and explaining findings to technical and business stakeholders.

I’m pursuing opportunities in data science, applied ML and AI engineering, and forward-deployed software engineering.

## Selected work

| Project | My work | What to explore |
| --- | --- | --- |
| [Predictive Maintenance of Rotating Equipments](https://github.com/ej188/Predictive-Maintenance-of-Rotating-Equipments) | Developed an internship proof of concept from sensor and maintenance-data integration through RUL modeling and evaluation; presented it to C-suite and global reliability and maintenance leaders. | Operating-cycle analysis, complementary Random Forest strategies, near-failure evaluation, and the limits of a constructed reference target. |
| [Demand Forecasting](https://github.com/ej188/Demand-Forecasting) | Implemented and iterated on multivariate shipment-demand forecasting with Temporal Fusion Transformers. | Temporal validation, hierarchical demand features, real-unit error analysis, and SARIMAX baseline context. |
| [Predictive Maintenance of CNC Machine](https://github.com/ej188/Predictive-Maintenance-of-CNC-Machine) | Contributed industrial telemetry integration and developed coolant-conductivity forecasting and validation workflows. | MTConnect and IO-Link integration, SQL ingestion, residual diagnostics, and prediction intervals. |
| [Anomaly Analysis](https://github.com/ej188/Anomaly-Analysis) | Documenting an independent study of anomaly-detection policies and LLM-based verification. | Evaluation design, calibration tradeoffs, and scenario-based verification plans. Work in progress. |

## Internship proof of concept

During my IT internship, I developed a predictive-maintenance proof of concept connecting industrial sensor history with maintenance events. I investigated equipment degradation, engineered temporal features, and developed regression strategies that combined historical operating cycles with current-cycle behavior.

An important finding emerged during evaluation: aggregate agreement with the reference target concealed weaker performance near failure. I presented the proof of concept, its limitations, and priorities for stronger data and broader validation to executive and global engineering stakeholders.

The [public case study](https://github.com/ej188/Predictive-Maintenance-of-Rotating-Equipments) explains my approach without company data, internal artifacts, or numerical results. It documents a proof of concept; production readiness and operational impact were not established.

## Technical focus

- **Machine learning and forecasting:** Random Forest regression, Temporal Fusion Transformers, Prophet, and SARIMAX baseline work.
- **Data engineering:** Python, SQL, sensor and event-data integration, cloud-warehouse analytics, MTConnect, and IO-Link.
- **Statistical reasoning:** temporal validation, residual and autocorrelation analysis, prediction intervals, error slicing, and target-validity checks.
- **Applied AI:** LLM classification prompt development and an ongoing study of anomaly verification.
- **Delivery and communication:** problem framing, engineering collaboration, readable documentation, and executive presentation of a technical proof of concept.

## How I approach a project

I start with the operational question and the available evidence. I examine missingness, event definitions, and what information would be available at prediction time. I compare model behavior across relevant conditions, then communicate the findings, limitations, and next decisions.

Each project distinguishes completed contributions from planned experiments. Public material emphasizes methods and reasoning while respecting the boundaries of private work.
