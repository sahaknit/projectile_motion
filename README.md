# Projectile Motion Simulator

An interactive web-based projectile motion simulation application built with HTML, CSS, and JavaScript.

## Features

- **Physics Simulation**: Realistic projectile motion with adjustable speed and angle
- **Interactive Controls**: Start, pause, restart, and clear screen functionality
- **Customization**: 
  - Adjust speed and angle with increment/decrement buttons
  - Change colors for ball, floor, background, and path
  - RGB color picker for custom colors
  - Upload custom background images or use URLs
- **Visual Feedback**: Real-time position tracking (X/Y coordinates)
- **Path Tracing**: Toggle to visualize the projectile trajectory

## Deploy to Vercel

This project is ready to deploy on Vercel:

1. **Install Vercel CLI** (optional):
   ```bash
   npm install -g vercel
   ```

2. **Deploy**:
   ```bash
   vercel
   ```
   
   Or simply push to your Git repository and connect it to Vercel at [vercel.com](https://vercel.com)

3. **Access**: Once deployed, users can access the simulator directly through the provided URL

## Local Development

Open `interface/index.html` in a web browser to run locally.

## Project Structure

```
├── interface/
│   └── index.html      # Main HTML file
├── methods/
│   └── fuction.js      # Physics engine and controls
├── styles/
│   └── style.css       # Styling
├── vercel.json         # Vercel configuration
└── README.md           # This file
```

## Usage

1. Click **Set Speed** and use +/- buttons to adjust launch speed
2. Click **Set Angle** and use +/- buttons to adjust launch angle
3. Click **Start** to launch the projectile
4. Use **Pause/Resume** to control the simulation
5. Toggle **Path** to visualize the trajectory
6. Use **Set Color** to customize appearance

## License

Free to use and modify.
