# 3D-Sorting-Algorithim-Visualizer

3D sorting algorithim visualizer made in C++ using OpenGL

Currently supports Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort, and Heap Sort

![](https://github.com/Your_Repository_Name/Your_GIF_Name.gif)

#### Movement Controls

- W A S D for movement
- Space and Left Shift for moving up and down
- Mouse move to look around
- M to play/resume BGM
- P to pause BGM
#### Sorting Controls

- R to shuffle the values
- 1 for Bubble Sort
- 2 for Insertion Sort
- 3 for Selection Sort
- 4 for Merge Sort
- 5 for Quick Sort
- 6 for Heap Sort

### To Compile

```sh
g++ -I include -L. -L lib -o main src/main.cpp src/shader.cpp src/stb_image.cpp src/glad.c -lglfw3 -lopengl32 -lgdi32 -lwinmm
```