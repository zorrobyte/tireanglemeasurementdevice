 # tireanglemeasurementdevice
A device to measure a vehicle's tire angle in relation to the steering angle for accurate steer ratio specification.

# Overview
This project was born out of a need to measure a factual steer ratio for use within Openpilot, an OSS vehicle autonomy platform. The OP planner uses tire angles, which is factored by steer ratio to determine a final steering angle. As you can imagine, factual steering ratios are important.

This device will also determine if a vehicle has Variable Ratio steering.

# Project Goal
To build two devices that can be placed under the front wheels, plugged into Comma Giraffe, and easily polt the angles, such as:
![](https://github.com/zorrobyte/tireanglemeasurementdevice/raw/master/images/angleexample.png)
