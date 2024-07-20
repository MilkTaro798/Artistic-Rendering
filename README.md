# Artistic Rendering

This project implements various artistic rendering techniques using GLSL shaders in WebGL. It was completed as part of the CSCI 4611 course at the University of Minnesota.

![Screenshot](https://github.com/MilkTaro798/Artistic-Rendering/blob/main/screenshot1.png)

## Features

- Toon shading using texture ramps for diffuse and specular lighting
- Silhouette outline rendering
- Normal mapping for enhanced surface detail
- Interactive model viewer with multiple shading options

## Implementation Details

The project uses TypeScript and WebGL to create a 3D model viewer with the following shader implementations:

1. Toon shader: Implements cartoon-style shading using texture ramps for diffuse and specular lighting.
2. Outline shader: Renders a black silhouette outline around the 3D model using vertex displacement and stencil buffer techniques.
3. Normal map shader: Applies normal mapping to enhance surface details without increasing geometry complexity.

## Technologies Used

- TypeScript
- WebGL
- GLSL (OpenGL Shading Language)

## Running the Project

To run this project locally:

1. Clone the repository
2. Install dependencies with `npm install`
3. Start the development server with `npm run start`
4. Open a web browser and navigate to `http://localhost:8080`

## Acknowledgments

This project was based on an assignment from the CSCI 4611 course at the University of Minnesota, taught by Evan Suma Rosenberg. The original assignment description and some of the starter code were provided by the course.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.