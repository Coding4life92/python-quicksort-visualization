# Visualizing QuickSort with Animation

This project provides a real-time visualization of the QuickSort algorithm using an animated bar chart. The array is represented by a series of vertical bars, where the height of each bar corresponds to the value in the array. During the sorting process, the bars dynamically adjust their heights as the algorithm sorts the elements, offering a clear and engaging way to understand how QuickSort works.

## Features:

- QuickSort Visualization: This project visualizes the QuickSort algorithm step by step, showing how the list is partitioned and sorted in real-time.
- Interactive Input: The user is prompted to input the size of the array for the sorting demonstration.
- Animation: The sorting process is animated using a bar chart that updates after each iteration, making it easy to follow the algorithm’s progress.
- Colorful and Interactive Plot: The bars are colored using a "viridis" colormap, which adds visual appeal to the chart.

## How It Works:

- Quicksort Function: The quicksort function implements the recursive QuickSort algorithm. During the sorting process, the function yields the array after each partition, allowing the animation to update step by step.
- Graph Visualization: The showGraph() function generates the animated bar chart. Each bar corresponds to an element in the array, and its height changes dynamically as the algorithm partitions and sorts the elements.
- Animation: The animation is powered by the FuncAnimation class from matplotlib.animation, which updates the graph at each step of the sorting process.

## Requirements:

To run this project, you need to have the following Python libraries installed:

1.  matplotlib: Used for plotting the animated bar chart.
2.  numpy: Used for numerical operations (e.g., array manipulation).
3.  random: Used for randomizing the array before sorting.

You can install the required libraries using pip:

```bash
    pip install matplotlib numpy
```

## Libraries Used:

- matplotlib.pyplot: For plotting the static and animated bar charts.
- matplotlib.animation.FuncAnimation: For creating the animation of the sorting process.
- mpl_toolkits.mplot3d.axes3d: Importing for general 3D plotting tools (not directly used in this specific implementation, but may be useful for further expansion).
- matplotlib: A general import for the matplotlib library, though it's not directly used in the script.
- numpy: For numerical operations (e.g., generating random arrays).
- random: For shuffling the array to simulate random input data.

## How to Use:

Input the Array Size: When the program starts, you will be prompted to enter the size of the array. For example, you could input 20 to sort an array of 20 random numbers.
-Watch the Animation: Once you input the array size, the program will randomly shuffle the array and begin sorting it using QuickSort. The sorting process will be visualized through an animated bar chart.

End of Animation: The animation will stop once the array is completely sorted.

Example Usage:

```bash
Enter array size:
40
```

This will start the visualization of the QuickSort algorithm on a randomly shuffled array of size 40.

## Sample Output: 
<img width="638" alt="Screenshot 2025-01-20 at 9 44 22 PM" src="https://github.com/user-attachments/assets/830e92eb-92b4-45ac-8feb-30685a173225" />


