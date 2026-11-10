# Project Description — QV3 Electric Powertrain Conversion

## Project context

Mechanical development of the electric conversion of a three-wheel vehicle platform originally designed around an internal-combustion powertrain. The target architecture uses a brushless electric traction motor, lithium-ion battery and belt-driven single rear wheel.

## Personal engineering contribution

I personally designed the mechanical motor mounting arrangements and interfaces required to integrate the electric motor and belt transmission into the existing vehicle architecture.

I also designed the revised aluminium rear swing-arm configuration, taking responsibility for its mechanical interfaces with the chassis, suspension, rear wheel and brake-caliper support.

My involvement extended to the structural verification process: I contributed to defining the FEM load cases, reviewing and interpreting the ANSYS results, identifying critical stress concentrations and driving design modifications based on the simulation findings.

## Vehicle configuration from the supplied brochure

- Brushless motor: 34 kW peak, 18 kW continuous.
- Peak torque: 106 Nm.
- Battery capacity: 7.2 kWh.
- Declared range: 110 km.
- Reinforced secondary belt and toothed-belt final drive.
- Single rear-wheel drive.
- Published curb weight: 227 kg.

## FEM case study

The separate report evaluates the aluminium rear swing arm under:
- 2.5 g vertical acceleration with 3,386 N belt traction.
- 1.0 g braking and 1.0 g vertical acceleration with 3,386 N belt traction.
- 100 Nm torsional stiffness load case.

Reported torsional stiffness is 690 Nm/° for the steel reference and 826 Nm/° for the aluminium configuration. The stress plots show critical local peaks, and the report calls for modification of the brake-caliper-support/swing-arm connection.

## Technical note

The report's local stress maxima exceed the assumed 140 MPa yield strength. They are presented as critical findings that drove engineering review and design iteration, not as evidence that the original configuration passed strength verification.
