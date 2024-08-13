# Curvetopia: Incremental Beautification using Algorithms and Neural Networks
## Welcome to Curvetopia! 🎨✨

Curvetopia is a cutting-edge framework designed to transform hand-drawn doodles into polished, visually harmonious designs. Combining traditional algorithms with neural networks, Curvetopia offers a modular system to progressively enhance and beautify sketches.

## Key Features
### Modular Filters: Apply custom filters like LineFilter and ConvexFilter to refine curves and reshape them into geometric forms such as circles, ellipses, and polygons.
### PixelDetector: A neural network-based filter that detects regular patterns within the doodles, enhancing complex shapes with precision.
### Incremental Process: Start with initial regularization, move through shape identification, and end with symmetry exploration to create a visually balanced output.
## How It Works
### Initial Regularization: Smoothen curves with B-spline interpolation and straighten nearly linear curves using linear regression.
### Shape Identification: Apply ConvexFilter to regularize basic geometric shapes and use PixelDetector to handle more complex patterns.
### Symmetry Exploration: Enhance the visual appeal by identifying and refining lines of symmetry in the final design.


