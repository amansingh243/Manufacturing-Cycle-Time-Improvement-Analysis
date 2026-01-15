# Manufacturing-Cycle-Time-Improvement-Analysis
Manufacturing Cycle Time Improvement Analysis using Excel and Python. The project analyzes production batch cycle times, visualizes distributions using histograms, identifies outliers with IQR method, and provides data-driven recommendations to improve manufacturing efficiency.

Tools & Technologies
MS Excel – Data calculation and histogram visualization
Python
pandas – data processing
matplotlib – visualization
Jupyter Notebook – analysis and documentation
📊 Dataset Description

The dataset contains batch-level manufacturing data with the following columns:

Batch_ID – Unique identifier for each production batch

Start_Timestamp – Production start time

End_Timestamp – Production end time

Cycle_Time_Hours – Total production time in hours

Note: Negative cycle times caused by overnight production were corrected before analysis.

📈 Analysis Performed
1️⃣ Cycle Time Calculation

Calculated cycle time in hours using start and end timestamps.

Performed validation and data correction for timestamp-related issues.

2️⃣ Excel Analysis

Created a separate worksheet to visualize cycle time distribution.

Built a histogram to analyze variability and frequency of cycle times.

Observed that most batches fall within a lower cycle time range, with a few long-running batches.

3️⃣ Python Analysis

Loaded the cleaned dataset using pandas.

Generated summary statistics for cycle times.

Identified outliers using the Interquartile Range (IQR) method.

Visualized the cycle time distribution using matplotlib histogram.

🚨 Key Insights

Majority of batches have consistent and stable cycle times.

A small number of batches show significantly higher cycle times, indicating potential bottlenecks.

Zero-frequency bins in the histogram highlight gaps in cycle time ranges.

Outlier batches are likely impacted by machine downtime, rework, or scheduling delays.

💡 Business Recommendations

Investigate high cycle-time batches to identify root causes such as equipment failures or rework.

Improve production scheduling to reduce delays in long-running batches.

Standardize manufacturing processes to minimize variability.

Track cycle time as a key performance indicator (KPI) for continuous improvement.
