import numpy as np
import matplotlib.pyplot as plt

# Define the time range from 0 to 3 seconds with small time intervals
t = np.linspace(0, 3, 1000)

# Define three different values for x
x_values = [1, 2, 3]

# Create a figure and axis with grid lines
fig, ax = plt.subplots()
ax.grid(True)

# Plot the graph for each x value
for x in x_values:
    y = 2 * np.cos(3 * x) * np.sin(10 * t)
    ax.plot(t, y, label=f'x={x}')

# Add labels and a legend
ax.set_xlabel('Time (seconds)')
ax.set_ylabel('Displacement (y)')
ax.set_title('Stationary Wave: y = 2*cos(3x)*sin(10t)')
ax.legend()

# Show the plot
plt.show()

