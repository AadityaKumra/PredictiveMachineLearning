<a href="#" class="button"> <h1>**Predictive Maintenance**</h1> ([Deployed Project Link](https://aadityakumra-predictivemaintenance.streamlit.app/))</a>
> Analyzing historic data, this project aims to leverage ML and Data Visualization skills to visualize and analyze trends and relationship between various factors that affect the performance of a machine. With large and diverse data samples, Microsoft Azure Predictive Maintenance dataset allows for robust model training and evaluation.

```diff 
What is the issue that industries are facing and how our project aims to provide solutions for them?
```


The maintenance of machines poses significant challenges, leading to frequent breakdowns, decreased productivity, increased downtime, and higher costs.
The industry still focuses on REACTIVE, Periodic and PROACTIVE maintenance instead of predictive maintenance. 

![image](https://github.com/AadityaKumra/PredictiveMachineLearning/assets/72290209/12210b2e-2bf3-4443-8637-c83566160c73)

What is the objective of this project?
>
>Our objective is to focus on Predictive maintenance which Leverages historic and real time data to:
>> - Anticipate and detect potential failure <br>
>> - Provide early warnings and actionable insights to maintenance teams. <br>
>> - Reduce the number of unexpected failures <br>
>

![image](https://github.com/AadityaKumra/PredictiveMachineLearning/assets/72290209/5543e955-1757-4417-b8af-9e6346fe3131)

![image](https://github.com/AadityaKumra/PredictiveMachineLearning/assets/72290209/99ca0337-6fc3-42d1-9163-4d47ee51543a)

<h1> Dataset Description </h1>

- <u>**Telemetry Time Series Data:**</u> It consists of hourly average of voltage, rotation, pressure, vibration collected from 100 machines for the year 2015 and has 8,76,099 rows.
Metadata of Machines: it contains  Model type & age of the Machines.
Failures: Each record represents replacement of a component due to failure. This data is a subset of Maintenance data. This data is rounded to the closest hour since the telemetry data is collected at an hourly rate. 

- <u>**Errors:**</u> These are errors encountered by the machines while in operating condition. Since, these errors don't shut down the machines, these are not considered as failures. The error date and times are rounded to the closest hour since the telemetry data is collected at an hourly rate. 

- <u>**Maintenance:**</u> If a component of a machine is replaced.  Components are replaced under two situations:

	1. During the regular scheduled visit, the technician replaced it (Proactive Maintenance). 

	2. A component breaks down and then the technician does an unscheduled maintenance to replace the component (Reactive Maintenance). This is considered as a failure and corresponding data is captured under Failures.

    Maintenance data has both 2014 and 2015 records. This data is rounded to the closest hour since the telemetry data is collected at an hourly rate. 
- <U>**Metadata of Machines:**</U> Model type & age of the Machines.

1. Pressure: The highest recorded pressure is 185.95 units and The lowest recorded pressure is 51.24 units this indicates a significant range in pressure values over the given time period. It suggests that the machine experienced both high and low pressure conditions during its operation.

2.	Vibration: The highest recorded vibration is 76.79 unitsand. The lowest recorded vibration is 14.88 units This reveals a considerable variation in vibration levels. Higher vibration values may indicate potential mechanical issues or imbalances, while lower values may represent periods of smoother operation.
3.	Voltage: The highest recorded voltage is 255.12 units and  The lowest recorded voltage is 97.33 units. This demonstrates a significant disparity in voltage levels. Higher voltage values can potentially pose risks to electrical components, while lower values may indicate fluctuations in the power supply.

4.	Rotation: The highest recorded rotation is 695.02 units and The lowest recorded rotation is 138.43 units. This indicates a substantial range in rotation speed. Higher rotation values may indicate faster operational speeds, while lower values may represent periods of slower rotation or idleness.

