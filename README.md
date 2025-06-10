# Python-assignment
Classwork
import matplotlib.pyplot as plt

# Temperature over a week
temperatures = [20, 22, 19, 23, 21, 24, 20]
days = ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday', 'Sunday']

plt.figure(figsize=(10, 5))
plt.plot(days, temperatures, marker='o', linestyle='-', color='blue')

plt.title('Temperature Readings Over a Week')
plt.xlabel('Day')
plt.ylabel('Temperature (°C)')

plt.grid(True)

plt.tight_layout()
plt.show()
