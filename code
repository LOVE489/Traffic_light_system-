import pandas as pd
import matplotlib.pyplot as plt

# Creating the structured data
data = {
    "Date": pd.date_range(start="2024-01-01", periods=20, freq="D"),
    "Value1": [828, 7065, 5861, 7163, 9432, 7330, 5434, 6858, 4418, 2689,
               9115, 7803, 2670, 7275, 3395, 1456, 7458, 1604, 6094, 6716],
    "Value2": [1261, 4225, 3286, 651, 548, 3922, 3681, 4139, 2495, 518,
               2029, 2281, 3542, 2438, 2627, 682, 1143, 1032, 4459, 3742],
    "Metric": [54.42, 31.58, 68.28, 60.20, 37.96, 51.87, 46.59, 63.94, 79.98, 51.52,
               29.40, 60.15, 74.21, 39.83, 41.59, 53.66, 36.54, 28.58, 42.91, 29.73]
}

# Creating a DataFrame
df = pd.DataFrame(data)

# Display the first few rows
print(df.head())

# Plot the data
plt.figure(figsize=(10, 5))
plt.plot(df["Date"], df["Metric"], marker='o', linestyle='-', color='b', label='Metric')
plt.xlabel("Date")
plt.ylabel("Metric Value")
plt.title("Metric Trend Over Time")
plt.legend()
plt.xticks(rotation=45)
plt.grid()
plt.show()
