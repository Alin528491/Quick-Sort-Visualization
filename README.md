**Quick Sort Visualization
**
This is a interactive, real-time visualization of the Quick Sort algorithm built with HTML, CSS, and JavaScript.

**Live Demo:
https://alin528491.github.io/Quick-Sort-Visualization/**

**Overview:
**This project is a visual tool designed to help users understand how the Quick Sort algorithm works step by step.

Instead of just showing the final sorted result, it breaks the process down into individual operations like:

comparisons
swaps
pivot selection

Each step is animated so you can actually see how the algorithm transforms the array over time.

**Features**
Real-time Quick Sort visualization
Step-by-step animation of:
comparisons
swaps
partitioning
Adjustable array size
Adjustable speed control
Start/Pause/Reset controls
Random array generation
Visual status indicators
Optional sound feedback

**How It Works
**
The visualization is driven by a precomputed list of steps generated from the Quick Sort algorithm.
Instead of sorting directly, the algorithm records actions such as:

compare(i, j)
swap(i, j)
pivot selection

These steps are then replayed using animation frames to create a smooth visual experience.

**Controls**
Start	Begins the sorting animation
Pause	Pauses/resumes the animation
Reset	Resets to the original array
Random	Generates a new random array
Size Slider	Adjusts number of elements
Speed Slider	Controls animation speed
Sound Toggle	Enables/disables sound effects
Tech Stack
HTML5 Canvas – rendering the visualization
Vanilla JavaScript – logic and animation loop
CSS3 – styling and UI
ResizeObserver – responsive canvas handling

No external frameworks or libraries are used.

**Project Structure
**Quick-Sort-Visualization/
index.html # Main application
README.md # Project documentation

**Purpose**
This project was built to:

make sorting algorithms more intuitive
turn abstract concepts into something visual
create an interactive learning tool rather than static code
Future Improvements
Add more sorting algorithms (Merge Sort, Heap Sort, etc.)
Step-by-step manual mode
Highlight recursion stack
Better mobile responsiveness
Performance metrics (time complexity visualization)

Author
Built by Alin K.
