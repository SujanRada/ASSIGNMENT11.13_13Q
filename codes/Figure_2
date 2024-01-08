import numpy as np
import matplotlib.pyplot as plt

# Define the wave velocity
v = 1.0  # You can adjust the velocity as needed

# Define the time range from 0 to 5 seconds with small time intervals
t = np.linspace(0, 5, 1000)

# Define three different values for x
x_values = [1, 3, 5]

# Create a figure and axis with grid lines
fig, ax = plt.subplots()
ax.grid(True)

# Plot the graph for each x value
for x in x_values:
    y = np.sqrt(x - v * t)
    ax.plot(t, y, label=f'x={x}')

# Add labels and a legend
ax.set_xlabel('Time (seconds)')
ax.set_ylabel('Displacement (y)')
ax.set_title('Wave: $y = \sqrt{x - vt}$')
ax.legend()

# Show the plot
plt.show()
