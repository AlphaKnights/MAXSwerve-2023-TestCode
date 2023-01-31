# MAXSwerve Java code for Alpha Knights #6695
Note that this is meant to be used with a drivetrain composed of four MAXSwerve Modules, each configured with one SPARKS MAX, a Falcon 500 as the driving motor with a Talon FX, and NEO 550 as the turning motor with the Spark Max, and a REV Through Bore Encoder as the absolute turning encoder.

To get started, make sure you have calibrated the zero offsets for the absolute encoders in the Hardware Client using the `Absolute Encoder` tab under the associated turning SPARK MAX devices.

## Prerequisites

* SPARK MAX Firmware v1.6.2 - Adds features that are required for swerve
* REVLib v2023.1.2 - Includes APIs for the new firmware features
* Phoenix Pro and 5 Vendor Dep

