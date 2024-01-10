import numpy as np
import matplotlib.pyplot as plt

# Define the time range from 0 to 2*pi seconds with small time intervals
t = np.linspace(0, 2 * np.pi, 1000)

# Define three different values for x
x_values = [np.pi/6, np.pi/4, np.pi/3]

# Create a figure and axis with grid lines
fig, ax = plt.subplots()
ax.grid(True)

# Plot the graph for each x value
for x in x_values:
    y = np.cos(x) * np.sin(t) + np.cos(2 * x) * np.sin(2 * t)
    ax.plot(t, y, label=f'x={x:.2f}')

# Add labels and a legend
ax.set_xlabel('Time (seconds)')
ax.set_ylabel('Displacement (y)')
ax.set_title('Superimposed Stationary Wave: $y = \cos(x)\sin(t) + \cos(2x)\sin(2t)$')
ax.legend()

# Show the plot
plt.show()

