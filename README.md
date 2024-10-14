# Tension-Measurement-Device

A wearable device designed to measure muscle and tendon tension for injury prevention in athletes. It integrates advanced sensing technologies, including piezoelectric sensors and actuators, to monitor and provide real-time feedback on muscle performance.

## Introduction
The **Tension-Measurement-Device (Tensoid)** is a portable tensiometer developed for athletes, particularly those involved in high-performance sports. The device aims to help prevent injuries by monitoring muscle and tendon stress.

Key Features:
- **Real-time Monitoring**: Measure muscle and tendon tension.
- **Durable Design**: Made from carbon fiber reinforced polymer for high strength and low wear.
- **Wireless Data Transmission**: Supports 5G/Wi-Fi to connect with smartphones or smartwatches for instant feedback.
- **AMOLED Touchscreen Display**: View data directly on the device.

## Muscle-Tendon Dynamics
Tendons are collagen-based tissues that connect muscles to bones, absorbing impact during movement. The Tensoid uses **piezoelectric sensors** and **miniature accelerometers** to measure tendon stress and dynamics.

### Stress-Strain Relationship
<img src="https://github.com/user-attachments/assets/28c13f5f-e973-49d9-b1c5-88b1d821756b" width="40%">
<br>
<figcaption style="text-align: center;">Stress-Strain Diagram</figcaption>
<br><br>


- **Toe Region**: Maximum elongation of up to 2%.
- **Linear Region**: Elongation between 2-4%, indicating a linear relationship between tendon stress and load.
- **Failure Region**: Beyond the physiological limit, the tendon cannot return to its original state.

Equation for tendon tension:
- **Tendon Tension** = (wave speed² * tendon density) - (K * shear modulus)
  - In the linear region, the relationship simplifies to **Tendon Tension** = (wave speed² * tendon density).

## Device Structure
The device has three key components connected by **Y-couplings**:

## Device Structure
The device has three key components connected by Y-couplings:

### PILine Ultrasonic Piezomotor
The **PILine Ultrasonic Piezomotor** enables precise linear horizontal movement along the y-axis, with a range of 5 mm to the left or right. The coupling element is in direct contact with the Y-shaped plate, and any wear particles generated during operation are collected in a dedicated compartment.

- Linear horizontal movement (along the y-axis) 5 mm to the right or left
- Coupling element in contact with Y-shaped plate
- Wear particles collected in the corresponding space

<img src="https://github.com/user-attachments/assets/a94bdf60-f9f1-471d-b1eb-ec67e7bed3e4" width="40%">
<br>
<figcaption style="text-align: center;">The <strong>Y-coupling midsection</strong> allows interaction with corresponding actuators to achieve controlled movement with minimal energy loss.</figcaption>
<br><br>

<img src="https://github.com/user-attachments/assets/c382ec80-5b0d-4bfb-bc2c-5e6d1397e3b2" width="40%">
<br>
<figcaption style="text-align: center;">Corresponding actuators to achieve controlled movement with minimal energy loss.</figcaption>
<br><br>

[Watch PILine Ultrasonic Piezomotor in action](https://www.youtube.com/watch?v=6fXBp_KJyVw)

### PI NEXLINE PiezoWalk
The **PI NEXLINE PiezoWalk** actuator is designed for both lifting and holding applications, featuring minimal wear due to its frictionless operation.

<img src="https://github.com/user-attachments/assets/e3244293-ebea-44c4-ab00-059e67839962" width="40%">
<br>
<figcaption style="text-align: center;">The <strong>PI NEXLINE PiezoWalk</strong> actuator.</figcaption>
<br><br>

[Watch PI NEXLINE PiezoWalk in action](https://www.youtube.com/watch?v=PMmutw8N2K8)
<br><br>


### Actuators
![Actuators](https://github.com/user-attachments/assets/f780c933-5955-43b4-b6fe-77ce5cd7e230)
- Includes **PICMA stacked multilayer piezo actuators**, **PILine ultrasonic piezomotors**, and **PI NEXLINE PiezoWalk**.
- Designed to provide precise movement control with low wear.

### Polyurethane Strap
![Polyurethane Strap](https://github.com/user-attachments/assets/34f9671c-cfdc-4c6a-bb19-65ce8895410d)
- Strong, flexible, water-resistant, with magnetic coupling for safety in case of accidents.

### Casing Material
- Made from **carbon fiber reinforced polymer (CFRP)** for a lightweight yet strong build, suitable for biological applications like protheses.
- **High thermal conductivity** helps dissipate heat away from internal components.

## Sensors and Chip Technology
The **Tensoid** integrates different sensors to measure muscle and tendon activity:

### Miniature Accelerometer
![Accelerometer](https://github.com/user-attachments/assets/903d75d9-6370-446c-86e5-f995c508ff2f)
- **3225F series accelerometer**: Provides 1mV/g sensitivity and is housed in a titanium casing for durability.

### Chip Technology
- Equipped with **Qualcomm Snapdragon 888+** for on-device AI processing, supporting efficient 5G connectivity.

## Display and User Interface
The Tensoid features a **full-color AMOLED touchscreen** that allows users to interact with the device and view real-time data.

### Display
![AMOLED Display](https://github.com/user-attachments/assets/bf1beb0f-2864-4501-aba4-f7664edc1133)
- 18-inch touchscreen panel that is lightweight and cost-effective.

## Functionality
The Tensoid software provides detailed analysis of tendon activity and feedback to improve workout performance:

- **Real-Time Data Visualization**: Monitor **transverse tendon acceleration** and identify critical points.
- **Wireless Communication**: Uses 5G/Wi-Fi to connect with the **Tensoid app** on smartphones or smartwatches.
- **Tenselink Functionality**: Allows multiple Tensoids to be linked together for advanced data analysis.

## Market Positioning
The **Tensoid** is unique in the market with no direct competitors, offering advanced muscle and tendon monitoring that extends beyond traditional heart rate monitors.

### Strengths and Opportunities
- **Versatile**: Suitable for multiple muscle groups and sports.
- **Durable and User-Friendly**: Uses materials and design optimized for longevity and ease of use.
- **Potential Opportunities**: Integration with popular fitness trackers and further optimization of the design for cost reduction.

## Challenges and Solutions
- **Market Uncertainty**: Conducted market studies to gauge interest.
- **High Manufacturing Costs**: Simplified design to reduce costs while maintaining functionality.
- **Risk of Copycats**: Patented the design to prevent counterfeiting.

## Project Goals
1. **Injury Prevention**: Monitor muscle and tendon stress to prevent overstraining.
2. **Performance Optimization**: Provide athletes with real-time feedback on workout intensity.
3. **Advanced Sensing**: Utilize high-precision sensors for detailed analysis of muscle performance.
4. **Durable Build**: Lightweight and resistant to environmental wear and tear, perfect for sports use.

## Usage Instructions
1. **Attachment**: Secure the device to the muscle or tendon area to be monitored.
2. **Monitoring**: Use the AMOLED display or the Tensoid app to monitor real-time data.
3. **Workout Feedback**: Adjust workout intensity based on the feedback provided by the Tensoid.

## Future Improvements
- **Integration with Fitness Apps**: Compatibility with popular fitness tracking apps.
- **Enhanced Sensor Precision**: Further advancements in sensor accuracy and battery life.

## Initial Design Sketches
Below are hand-drawn sketches of the initial concept, further refined and processed for manufacturing.

<img src="https://github.com/user-attachments/assets/9eee6567-0f46-401b-8dd5-b0e22beab924" width="50%">
<img src="https://github.com/user-attachments/assets/bb917bcf-ec07-45bc-9860-e4fb50cf0de7" width="50%">
<img src="https://github.com/user-attachments/assets/838cf2e9-3b8a-4cb3-b52b-13665d03a26b" width="50%">

## Technology Stack
- **Hardware**: Piezoelectric sensors, miniature accelerometers, Qualcomm Snapdragon 888+ for AI processing.
- **Software**: Tensoid app for smartphones/smartwatches, powered by 5G/Wi-Fi communication.
- **Materials**: Carbon fiber reinforced polymer, Polyurethane bands with magnetic coupling for flexibility.

