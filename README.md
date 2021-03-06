# HDRP Graphics Stress Test
![HDRP Stress test](https://i.imgur.com/JLpMwqL.png)  
## How to use  
- Before building the player: execute **Edit->Visual Effects->Rebuild All Visual Effect Graphs**  
- To run from the editor: Open **Base** scene and click play  
- Scene switching: **Space Bar** or click on **Prev/Next**  
- Wait till it stops **sampling the frames** and start calculating the average value  
## Legend
- **AllocatedMemoryForGraphicsDriver**: The amount of allocated memory for the graphics driver, in bytes  
- **TotalAllocatedMemory**: The total memory allocated by the internal allocators in Unity. Unity reserves large pools of memory from the system  
- **TempAllocatorSize**: The size of the temp allocator  
- **TotalReservedMemoryg**: The total memory Unity has reserved  
- **TotalUnusedReservedMemory**: The amount of unused memory in pools where Unity allocates memory for usage when it needs to allocate memory  
## Scenes
- CPUParticles
- CPUPhysics
- GPUParticles
- Lights
- Particles_Collision
- Rendering_OpaqueLit
- Rendering_TransparentLit


