# Conveyor Belt Health Monitoring System

An integrated conveyor belt monitoring solution designed to detect potential belt damage, monitor wear, and support predictive maintenance in iron ore mines.

## Overview

Conveyor belts are essential for material transportation in mining operations. Unexpected belt damage can cause downtime, expensive repairs, and safety risks.

This project proposes a centralized monitoring system that combines multiple sensors, data processing, and a software dashboard to provide better visibility into conveyor belt health.

## Key Features

- **Surface Damage Detection:** Identify visible cuts, cracks, tears, and surface abnormalities using an industrial camera.
- **Internal Damage Detection:** Use Magnetic Flux Leakage (MFL) technology to assess potential steel-cord damage.
- **Thickness and Wear Monitoring:** Monitor belt thickness and potential wear.
- **Belt Rip Detection:** Detect potential longitudinal belt tears.
- **Defect Position Mapping:** Use rotary encoder data to associate defects with belt position.
- **Centralized Dashboard:** Display processed sensor data, defect information, and monitoring status.
- **Maintenance Support:** Help prioritize inspections and maintenance using defect severity and monitoring results.

## System Architecture

```text
Industrial Sensors
  |
  |-- Surface Inspection Camera
  |-- MFL Sensor System
  |-- Thickness Sensor
  |-- Belt Rip Detection Sensor
  |-- Rotary Encoder
  |
  v
Data Acquisition
  |
  v
Edge Processing Unit
  |
  v
Data Analysis and Fusion
  |
  v
Data Storage
  |
  v
Monitoring Dashboard
  |
  v
Alerts and Reports
```

## Current Progress

- **Dashboard Development:** Monitoring dashboard software is under development to process and display conveyor belt health information.
- **Test Data Evaluation:** Data-processing workflows are being tested using datasets available through Hugging Face.
- **3D Mechanical Design:** A 3D conveyor belt model is being designed to determine suitable sensor mounting positions.
- **Hardware Integration:** Physical sensor integration and real-time testing are planned for future development stages.

## Proposed Technology and Components

| Component | Purpose |
|---|---|
| Industrial Camera | Surface damage inspection |
| MFL Sensor System | Internal steel-cord damage assessment |
| Thickness Sensor | Belt wear monitoring |
| Rip Detection Sensor | Longitudinal tear detection |
| Rotary Encoder | Belt speed and defect position mapping |
| Industrial Edge Computer | Data acquisition and processing |
| Monitoring Dashboard | Visualization, alerts, and reports |

*Final hardware models, interfaces, and compatibility will be confirmed during detailed design.*

## Expected Benefits

- Earlier identification of potential belt defects.
- Improved visibility into conveyor belt condition.
- Better defect localization and maintenance planning.
- Reduced dependence on manual inspection alone.
- Potential reduction in unplanned downtime, subject to validation.

## Future Scope

- Integration with real-time industrial sensors.
- Automated defect classification and severity assessment.
- Historical trend analysis and defect progression tracking.
- Dashboard notifications and maintenance reports.
- Pilot testing under actual conveyor operating conditions.
- Integration with plant monitoring systems where supported.

## Research and Resources

- [Hugging Face](https://huggingface.co/) — Platform for datasets and machine learning resources.
- [RONDS Intelligent Camera](https://www.ronds.com/products/ronds-intelligent-camera/)
- [CONTI CordProtect](https://www.continental-industry.com/gb/en/products-solutions/digital/conveying-digital-solutions/belt-monitoring-systems/conti-cordprotect)
- [CONTI WearInspect](https://www.continental-industry.com/in/en/products-solutions/digital/conveying-digital-solutions/conveyor-inspections-services/conti-wearinspect)
- [CONTI SurfaceInspect](https://www.continental-industry.com/global/en/products-solutions/digital/conveying-digital-solutions/conveyor-inspections-services/conti-surfaceinspect)
- [Almex BeltGard](https://www.almex.com/india/en/beltgard1/)
- [Beltscan Products](https://www.beltscan.com/products)
- [GreCon BELTVIEW](https://www.fagus-grecon.com/en-us/measurement-technology/products/beltview)
- [Research Paper on Conveyor Belt Monitoring](https://pmc.ncbi.nlm.nih.gov/articles/PMC11561352/)

*These references inform the proposed design. The specific Hugging Face dataset used for testing should be linked separately.*

## Project Status

**Currently in Development**

Dashboard preparation, test-data evaluation, and 3D mechanical design are in progress. Hardware integration, real-time sensor testing, and field validation remain future steps.

## Disclaimer

This project is under development and is not a certified industrial safety system. The proposed architecture and components require engineering verification, compatibility testing, and field validation before operational deployment.
