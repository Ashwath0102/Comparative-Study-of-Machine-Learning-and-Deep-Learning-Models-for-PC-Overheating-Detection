# Comparative Study of Machine Learning and Deep Learning Models for PC Overheating Detection

This code focuses on a classification task to determine whether a personal computer (PC) is overheated or not. The study involves a comparative analysis of machine learning and deep learning models based on their accuracy in detecting CPU overheating. The primary goal is to identify the most effective model for accurate and reliable detection.

Basically, when the CPU is under heavy load or the temperature starts to rise, the system's thermal management mechanism will typically increase the fan speed to help cool down the CPU and maintain its temperature within a safe range. This is a common practice in laptops, desktops, and other computing devices to prevent overheating.

### Problem Statement

In the era of technology-driven advancements, ensuring the optimal performance and safety of computing devices is paramount. Overheating is a critical issue that can not only compromise the functionality of a computer but also pose potential hazards. Therefore, developing efficient methods for CPU overheating detection is of significant importance.

### Code Summary

In this study, we conducted a classification task to determine if a CPU is overheated or not based on various input features, including temperature, fan speed, CPU load, GPU load, RAM usage, and VRAM usage. 

##### Dataset Description
The dataset, consisting of over 7500 samples of 6 features, was generated synthetically to simulate real-world conditions.
The exact relationships between these factors can be complex and may depend on the specific hardware, system configuration, workload, and other variables. However, a simplified example of how these factors might interact:

Let's assume a simple rule of thumb for illustration purposes:
***CPU Overheating Threshold:***

Temperature > 89°C

OR

***The CPU is considered overheating if any of the following conditions are true:***

Temperature > 80°C
Either fan speed is greater than 3000 RPM or CPU load is greater than 0.8
Either CPU load is greater than 0.7, GPU load is greater than 0.7, RAM usage is greater than 0.7, or VRAM usage is greater than 0.7

Effect of Fan speed on Overheating:

![download (1)](https://github.com/Ashwath0102/Comparative-Study-of-Machine-Learning-and-Deep-Learning-Models-for-PC-Overheating-Detection/assets/59199696/fdb8242e-844f-4271-92ad-9f8b50de3f9b)

Pairplot on how the selected input features affect the output:

![download](https://github.com/Ashwath0102/Comparative-Study-of-Machine-Learning-and-Deep-Learning-Models-for-PC-Overheating-Detection/assets/59199696/35d8b611-61d7-442f-ad28-98472966ffab)


We explored several machine learning models, including **Logistic Regression, Decision Tree, Random Forest, Naive Bayes, and Support Vector Machine,** to predict CPU overheating. Additionally, a **deep learning model** with three layers was implemented for comparison.

### Result

The research findings indicate the following accuracies for CPU overheating detection:

Logistic Regression: 96.1%
Decision Tree: 99.8%
Random Forest: 99.8%
Naive Bayes: 94.0%
Support Vector Machine: 97.1%
Deep Learning: 97.6%

![newplot (2)](https://github.com/Ashwath0102/Comparative-Study-of-Machine-Learning-and-Deep-Learning-Models-for-PC-Overheating-Detection/assets/59199696/fd552e2d-90fe-4e7f-9119-b05eca76a905)

Based on accuracy, the Decision Tree model stands out as the best performer with an accuracy of 99.8%.

This comparative analysis serves as a valuable resource for selecting an appropriate model for CPU overheating detection, ensuring system health and user satisfaction.

*Side note: Keep in mind that this example is a simplified illustration and real-world scenarios can be more intricate due to the interplay of various factors.*

### Phyical Limitations

**Overheating** can occur due to factors such as inadequate cooling, insufficient thermal paste application, high CPU load, poor ventilation, blocked air vents, and more. Fans play a crucial role in cooling the components and preventing overheating by dissipating heat away from the CPU.

### Reasons For Overheating

Overheating in a computer system can be caused by a combination of several factors. Here are some of the key factors that contribute to overheating:

*Temperature:*
Higher ambient temperature or inadequate cooling can lead to overall temperature rise within the system.

*Fan Speed:*
Inadequate fan speed or faulty cooling fans can result in insufficient heat dissipation.

*Ventilation and Airflow:*
Poor case design or obstructions in the airflow path can hinder proper heat exchange.

*Dust and Debris:*
Accumulation of dust on components and fans can reduce cooling efficiency.

*CPU Load:*
Intensive processing tasks can cause the CPU to generate more heat.

*GPU Load:*
Graphics-intensive applications can lead to higher GPU temperatures.

*RAM Usage:*
High RAM usage can increase temperature due to higher power consumption.

*VRAM Usage:*
Intensive graphics tasks can lead to higher VRAM temperatures.

*Overclocking:*
Overclocking components beyond their intended specifications can result in higher temperatures.

*Insufficient Thermal Paste:*
Improper application of thermal paste between the CPU/GPU and heatsink can hinder heat transfer.

*Power Supply Unit (PSU):*
A low-quality or inefficient PSU can generate more heat.

*Laptop Usage on Soft Surfaces:*
Using a laptop on soft surfaces can block cooling vents and lead to higher temperatures.

*Background Processes:*
Background processes consuming CPU and memory resources can lead to increased heat generation.

*Software Optimizations:*
Poorly optimized software can cause components to work harder, increasing heat output.

*Malfunctioning Hardware:*
Faulty components like malfunctioning fans, heat sinks, or sensors can disrupt cooling.

*Thermal Design and Component Layout:*
Inadequate thermal design and improper placement of components can hinder heat dissipation.

*Old or Dried Thermal Paste:*
Over time, the thermal paste between components and heatsinks can dry up, reducing heat transfer efficiency.

*Closed or Obstructed Case:*
A closed or obstructed computer case can trap heat and affect airflow.

***Solution: To prevent overheating, it's important to maintain proper cooling, monitor component temperatures, clean dust regularly, optimize software usage, and ensure that your system's hardware components are working as intended.***

**Note:** It's essential to monitor your CPU's temperature, fan speed, and load while running intensive tasks or during prolonged usage. Many hardware monitoring tools are available that can provide real-time data on these parameters.

For accurate and reliable results, consider consulting your CPU's documentation or the manufacturer's recommendations for safe operating temperatures and optimal fan speed settings. It's always better to keep your CPU within its specified temperature range to ensure longevity and reliable performance.
