# VR Project

A Unity-based project featuring bucket physics and paint simulation with SPH (Smoothed Particle Hydrodynamics) fluid dynamics.

## Project Structure

- **Assets/Scripts/Bucket physics/** - Bucket physics simulation and mesh building
- **Assets/Scripts/SPH/** - SPH fluid simulation and ray marching visualization
- **Assets/Scripts/Paint Droplet System/** - Paint droplet physics and splat effects
- **Assets/Scripts/Connectors/** - Adapter and connector components
- **Assets/Shader/** - Compute shaders and visualization shaders
- **ProjectSettings/** - Unity project configuration

## Requirements

- Unity (see ProjectSettings/ProjectVersion.txt for required version)
- Compatible with C# 9.0+

## Getting Started

1. Open the project in Unity
2. Load the SampleScene from Assets/Scenes/
3. Explore the bucket physics and fluid simulation systems

## Key Features

- Realistic bucket physics with mass and material properties
- SPH-based fluid simulation
- Paint droplet system with splat generation
- GPU-accelerated visualization with compute shaders

## License

See LICENSE file for details.
