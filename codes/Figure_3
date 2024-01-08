import numpy as np
import matplotlib.pyplot as plt

# Define the time range from 0 to 10 seconds with small time intervals
t = np.linspace(0, 10, 1000)

# Define three different values for x
x_values = [1, 2, 3]

# Create a figure and axis with grid lines
fig, ax = plt.subplots()
ax.grid(True)

# Plot the graph for each x value
for x in x_values:
    y = 3 * np.sin(5 * x - 0.5 * t) + 4 * np.cos(5 * x - 0.5 * t)
    ax.plot(t, y, label=f'x={x}')

# Add labels and a legend
ax.set_xlabel('Time (seconds)')
ax.set_ylabel('Displacement (y)')
ax.set_title('Travelling Harmonic Wave: $y = 3\sin(5x - 0.5t) + 4\cos(5x - 0.5t)$')
ax.legend()

# Show the plot
plt.show()
