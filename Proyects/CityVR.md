# City VR

**City VR** is an innovative project that transforms the process of code analysis into an immersive experience using a 3D virtual city. The project is designed to visualize and explore the performance and complexity of software systems through a VR environment, making abstract concepts more tangible and interactive.

This project is part of my work in **Virtual Reality** development, where I focus on creating interactive, immersive experiences that help visualize complex data, in this case, related to software metrics.

![City VR Overview](path_to_image_of_city_vr_overview.png) <!-- Image of the project overview -->

---

## Concept

The central idea behind **City VR** is to represent software as a virtual city, where the structure and elements of the city symbolize various aspects of the codebase. This visualization helps users better understand the relationships between different parts of the code, making it easier to spot inefficiencies and opportunities for optimization.

The city is constructed in a way that buildings represent code files or modules, and various city elements like neighborhoods, roads, and districts represent folders, classes, and other logical divisions of code. Key metrics, such as performance, complexity, or test coverage, are mapped to visual properties such as the size, color, and height of the buildings.

---

## Key Features

- **Immersive VR City**: Experience the code as a city you can walk through. The city’s layout and its buildings represent the software’s architecture, making it easier to understand how different parts of the code interact with one another.

- **Miniature Lobby Overview**: Upon entering the experience, users start in a lobby where the entire city is displayed as a miniature model. This small-scale view allows users to see the general structure of the software before entering the full-scale city. The lobby acts as a way to quickly understand the layout of the codebase and get a sense of its complexity.

- **Real-Scale City Exploration**: After getting an overview from the lobby, users are transported to the city in full scale. This allows for an immersive, up-close exploration of the code, where users can interact with individual buildings (representing code files or modules) to gain deeper insights into performance metrics, coverage, and more.

- **Dynamic Interactions**: The city reacts to changes in the code. For example, if you optimize a part of the code or improve its performance, the city will reflect these changes in real-time by adjusting the height, color, or appearance of the buildings.

- **Code Metrics Representation**: The appearance of each building in the city varies according to metrics like:
  - **Size**: Represents the file or module’s size (lines of code, number of functions, etc.).
  - **Color**: Maps to performance metrics, with cooler colors representing more efficient code and warmer colors indicating potential issues.
  - **Height**: The height of a building represents the complexity of the code within that file or module, making it easy to spot the most complex areas at a glance.

- **Interactive Tools**: Users can click on buildings to get detailed information about the code behind them, including performance reports, test coverage, and suggestions for optimization.

![City VR Interaction](path_to_image_of_city_interaction.png) <!-- Image showing interaction in the VR environment -->

---

## How It Works

1. **Start in the Miniature Lobby**: The experience begins in a small lobby that presents an overview of the entire city. From here, you can get a bird's-eye view of the codebase, represented as a cityscape with buildings of varying sizes, colors, and shapes.

   ![Miniature City View](path_to_image_of_miniature_city_view.png) <!-- Image of the miniature city view from the lobby -->

2. **Travel to the Full-Scale City**: Once you're ready, you can teleport from the miniature view to the full-scale city, where you can explore the code up close. As you walk through the city, you’ll notice that buildings representing different parts of the code are arranged logically according to their relationships (e.g., related files might be grouped together).

3. **Explore Code Metrics**: As you approach each building, you can interact with it to see more detailed metrics such as:
   - Performance data (response time, resource usage).
   - Code complexity (cyclomatic complexity, number of functions/methods).
   - Test coverage and code health.

   These insights are displayed in an intuitive, visual format, making it easy to understand at a glance where optimizations are needed.

4. **Real-Time Feedback**: As you interact with the city, making changes to the code, you’ll notice the city adjusting in real-time. For example, simplifying a complex function might cause a building to shrink, change color, or become more aligned with the city’s overall aesthetic.
