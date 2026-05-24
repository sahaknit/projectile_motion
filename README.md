# Projectile Trajectory Simulator

A web-based projectile trajectory simulator that demonstrates projectile motion physics with interactive controls.

## 🌐 Live Demo

This project is ready to be deployed on Vercel. Once deployed, users can access it directly from their browser.

## 🚀 Deploy to Vercel

### Option 1: Deploy via Vercel Dashboard (Recommended)

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will automatically detect the `vercel.json` configuration
6. Click "Deploy"

### Option 2: Deploy via Vercel CLI

```bash
# Install Vercel CLI
npm install -g vercel

# Login to Vercel
vercel login

# Deploy
vercel --prod
```

## 🎮 Features

- **Interactive Controls**: Adjust velocity, angle, gravity, and launch height
- **Real-time Visualization**: See the projectile trajectory animated on canvas
- **Physics Statistics**: View max height, range, and flight time
- **Multiple Trajectories**: Fire multiple projectiles to compare different settings
- **Click to Aim**: Click anywhere on the canvas to automatically calculate and fire
- **Responsive Design**: Works on desktop and mobile devices

## 📊 Physics Parameters

- **Initial Velocity**: 10-100 m/s
- **Launch Angle**: 0-90 degrees
- **Gravity**: 1-20 m/s² (default: 9.8 m/s² for Earth)
- **Launch Height**: 0-100 meters

## 🛠️ Technology Stack

- HTML5 Canvas
- Vanilla JavaScript
- CSS3 with modern styling

## 📁 Project Structure

```
/workspace
├── web/
│   └── index.html          # Main application file
├── vercel.json             # Vercel deployment configuration
├── README.md               # This file
└── Assets/                 # Original Unity project assets
    └── Scripts/            # Original C# scripts
        ├── Trajectory.cs
        ├── Gun.cs
        └── ...
```

## 🎯 How It Works

The simulator uses the classic projectile motion equations:

- **Horizontal Position**: x = v₀ × cos(θ) × t
- **Vertical Position**: y = h₀ + v₀ × sin(θ) × t - ½ × g × t²

Where:
- v₀ = initial velocity
- θ = launch angle
- g = gravitational acceleration
- h₀ = initial height
- t = time

## 👥 Usage

1. Open the deployed URL in any modern browser
2. Adjust the sliders to set your desired parameters
3. Click "Fire Projectile" to launch
4. Click "Clear Trajectories" to reset
5. Or simply click on the canvas to aim and fire!

## 📄 License

MIT License

---

**Original Unity Project**: This web version is based on the original Unity projectile trajectory project, reimagined as a standalone web application for easy sharing and deployment.
