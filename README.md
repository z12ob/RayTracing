Ray Tracing in One Weekend
This project implements a ray tracer based on the book "Ray Tracing in One Weekend" by Peter Shirley, Trevor David Black, and Steve Hollasch (Version 4.0.2, 2025-04-25).
Project Overview
The goal is to create a ray tracer that produces a final render with spheres, diffuse, metal, and dielectric materials, antialiasing, and defocus blur. The project follows the tutorial's step-by-step approach using C++.
Build Instructions

Ensure you have CMake and a C++ compiler (e.g., MinGW or MSVC) installed.
Create a build directory and run CMake:cmake -B build
cmake --build build


Run the program to generate an image:build/inOneWeekend.exe > image.ppm

Open image.ppm with an image viewer that supports PPM format (e.g., GIMP or a text editor to verify).

Features

Outputs a 400x225 image with 100 samples per pixel.
Includes a scene with a ground plane, center sphere (diffuse), left sphere (dielectric), and right sphere (metal).
Implements antialiasing, gamma correction, and ray bouncing up to 50 depths.

Future Steps

Explore Book 2: "Ray Tracing: The Next Week" for additional features.
Optimize performance or add more complex scenes.

Acknowledgments
Thanks to the authors and contributors of the Ray Tracing project on GitHub.