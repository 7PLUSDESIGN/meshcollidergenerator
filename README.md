# Mesh Collider Generator
A lightweight, web-based 3D utility designed to generate physics-optimized collision meshes (colliders) from complex 3D models, ensuring they comply with strict game engine performance constraints (hard-capped at a maximum of 256 triangles).

### Key Features
* **Multi-Format Support:** Import `.obj`, `.stl`, `.ply`, `.fbx`, `.dae`, `.gltf`, and `.glb` files easily via drag-and-drop.
* **3 Optimized Algorithms:** Choose between *Convex Hull*, *Simplified (Quadric Decimation)*, and *Voxel Hull* generation.
* **Performance Safe-Guard:** Automatically limits and clamps the output collider to a safe budget (Max 256 triangles) to ensure optimal physics performance.
* **Dynamic 3D Viewport:** Real-time visualization built with Three.js, featuring automatic ground-level grid snapping at the base of the model.
* **Clean Export:** Download the optimized collider instantly as `.obj` or `.dae` files.
