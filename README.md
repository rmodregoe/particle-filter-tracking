
# Particle Filter Tracking with Adaptive Template Updating

## Project Description
This project implements particle filter tracking for object detection and tracking in videos. It leverages Gaussian noise for particle generation, Mean Squared Error (MSE) for similarity evaluation, and an Infinite Impulse Response (IIR) filter for adaptive template updating. The implementation is applied to video sequences for tracking objects like faces and hands.

## Features
- **Particle Filter Tracking**:
  - Generates particles using Gaussian noise.
  - Evaluates similarity using MSE and converts it to weights via a Gaussian function.
  - Resamples particles based on their weights.
- **Template Updating**:
  - Uses IIR filters to dynamically update the tracking template.
- **Adaptive Filtering**:
  - Adjusts particle size and incorporates window size as a parameter for enhanced tracking.
- **Visualization**:
  - Displays tracked objects with bounding boxes and particle distributions.

## Included Files
- `tracking.ipynb`: Jupyter Notebook containing the implementation of particle filter tracking and adaptive template updating.

## Requirements
- **Python**: Version 3.8 or higher
- Required Libraries:
  - `numpy`
  - `opencv-python`
  - `matplotlib`

Install dependencies using:
```bash
pip install numpy opencv-python matplotlib
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/rmodregoe/particle-filter-tracking.git
   ```
2. Open `tracking.ipynb` in Jupyter Notebook.
3. Follow the instructions to execute the particle filter tracking for the provided video files.

## Results
- Tracks objects in video sequences.
- Visualizes the tracking process with bounding boxes and particle distributions.
- Demonstrates the effect of varying parameters like window size and number of particles.

## License
This project is licensed under the MIT License.

## Contact
For any questions or feedback, contact Ricardo Modrego at [r.modrego.e@gmail.com](mailto:r.modrego.e@gmail.com).
