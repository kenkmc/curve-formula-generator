Interactive Plotting Tool
This is a simple, interactive web-based tool that allows users to plot points on a grid and visualize either a straight line or a polynomial curve fitted to those points. The corresponding mathematical formula for the plotted line or curve is displayed dynamically.

Features
Interactive Canvas: Click on the canvas to add points.

Grid System: Points are snapped to a discrete grid for easy alignment.

Straight Line Plotting: Plot a straight line given at least two points. The tool calculates and displays the equation in the form y = mx + c or x = constant for vertical lines.

Curve (Polynomial) Plotting: Plot a curve by adding multiple points. The tool performs polynomial regression (up to degree 3) to fit a curve and displays its equation.

Dynamic Formula Display: See the formula update in real-time as you add or clear points.

Clear Canvas Functionality: Reset the plot with a single click.

Responsive Design: Built with Tailwind CSS for a clean and adaptable user interface.

How to Use
Open index.html: Simply open the index.html file in your web browser.

Choose Plot Type: Select either "Straight Line" or "Curve (Polynomial)" using the radio buttons.

Add Points: Click anywhere on the grid within the canvas to add points.

For a straight line, you need a minimum of two points.

For a curve, add multiple points to define the desired shape. The more points you add, the better the polynomial fit will generally be.

View Formula: The mathematical formula for the plotted line or curve will appear below the canvas.

Clear Plot: Click the "Clear Canvas" button to remove all points and start fresh.

Technical Details
This tool is built using:

HTML5: For the basic page structure.

CSS (Tailwind CSS): For styling and layout. The Tailwind CSS CDN is used for simplicity.

JavaScript: For all interactive logic, including:

Canvas drawing (grid, axes, points, lines, curves).

Coordinate conversion between canvas pixels and plot units.

Mathematical calculations for straight line equations (slope-intercept form).

Polynomial Regression: An implementation of the least squares method using Gaussian elimination to find the coefficients of the best-fit polynomial.

Project Structure
.
└── index.html
The entire application is contained within a single index.html file, including the HTML structure, CSS styling, and JavaScript logic.

Local Development
To run this project locally:

Clone this repository (if applicable) or save the index.html file to your local machine.

Open the index.html file directly in your web browser (e.g., Chrome, Firefox, Edge).

No special server setup or build process is required.

Future Enhancements (Ideas)
Allow users to input custom formulas.

Add options for higher-degree polynomial regression.

Implement drag-and-drop for points to adjust their positions.

Enable zooming and panning on the canvas.

Export plot data or images.

Improve error handling and user feedback for invalid inputs or plot conditions.
