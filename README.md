# SharpGL Learning Projects

A collection of educational 3D graphics projects built with C# and SharpGL, demonstrating core OpenGL concepts through interactive Windows Forms applications.

## 📋 Overview

This repository contains hands-on learning projects that explore 3D graphics fundamentals including transformations, rotations, projections, and real-time rendering using the SharpGL library (a .NET wrapper for OpenGL).

## 🎯 Projects Included

### 1. **Rotatable Cube**
An interactive 3D cube rendering application that demonstrates basic OpenGL rendering and user interaction.

**Features:**
- Mouse-controlled 3D rotation
- Real-time transformation matrices
- Perspective projection
- Colorful face rendering with depth testing
- Smooth rotation handling

**Learning Concepts:**
- OpenGL initialization and context management
- Vertex and fragment shader basics
- Model-View-Projection (MVP) matrices
- 3D coordinate transformations
- Mouse event handling for 3D interaction

### 2. **3D Camera Model**
A complex 3D model of a camera constructed using OpenGL primitives, fully interactive and rotatable.

**Features:**
- Multi-component 3D camera geometry
- Full 3D rotation capabilities
- Interactive mouse controls
- Real-time rendering loop
- Advanced transformation techniques

**Learning Concepts:**
- Composite 3D object modeling
- Complex geometric transformations
- Camera coordinate systems
- Hierarchical transformations
- Performance optimization for multiple objects

## 🛠️ Technology Stack

| Technology | Version |
|-----------|---------|
| **Language** | C# (.NET Framework) |
| **GUI Framework** | Windows Forms |
| **Graphics Library** | SharpGL (OpenGL Wrapper) |
| **Rendering API** | OpenGL 2.1+ |
| **IDE** | Visual Studio 2019+ |

## 📦 Project Structure

```
SharpGL-Learning-Projects/
├── Rotatable cube/
│   ├── Form1.cs
│   ├── Form1.Designer.cs
│   ├── Program.cs
│   └── *.csproj
├── 3DCamera/
│   ├── Form1.cs
│   ├── Form1.Designer.cs
│   ├── Program.cs
│   └── *.csproj
├── README.md
└── .gitignore
```

## 📚 Key Concepts Demonstrated

- **3D Coordinate Systems**: Understanding world, view, and projection coordinate spaces
- **Transformation Matrices**: Rotation, translation, and scaling operations
- **OpenGL Pipeline**: Vertex processing, rasterization, and fragment shading
- **Real-time Rendering**: 60 FPS animation loops
- **User Interaction**: Mouse event handling for 3D object manipulation
- **Depth Testing**: Proper z-buffer management for 3D depth perception
- **Perspective Projection**: Creating realistic 3D viewing frustum

## 🚀 Getting Started

### Prerequisites
- Visual Studio 2019 or later
- .NET Framework 4.7.2 or higher
- NuGet Package Manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/74hamed/SharpGL-Learning-Projects.git
   cd SharpGL-Learning-Projects
   ```

2. **Open in Visual Studio**
   - Open the solution file (`.sln`) in Visual Studio
   - The solution may contain multiple projects, one for each learning example

3. **Restore NuGet Packages**
   - Visual Studio should automatically restore packages
   - If not, use: `Package Manager Console` → `Update-Package -Reinstall`

4. **Build and Run**
   - Select a project in Solution Explorer
   - Press `F5` or click "Start Debugging"
   - The application window will launch with the 3D graphics rendering

### Controls

| Input | Action |
|-------|--------|
| **Mouse Drag** | Rotate the 3D object |
| **Mouse Move** | Real-time rotation feedback |
| **Window Resize** | Dynamic viewport adjustment |

## 🎓 Learning Path

1. Start with **Rotatable Cube** to understand basic OpenGL setup and rendering
2. Move to **3D Camera Model** to explore more complex geometric modeling
3. Experiment with modifying transformation matrices to deepen understanding
4. Try adding new features like zoom, pan, or lighting

## 🔧 Dependencies

The projects require the following NuGet package:
- **SharpGL** - Provides .NET bindings for OpenGL

To install manually:
```powershell
Install-Package SharpGL
```

## 💡 Tips for Learning

- Read OpenGL documentation alongside the code
- Experiment with modifying rotation speeds and angles
- Try adding new geometric shapes to the scenes
- Study the transformation matrix calculations
- Implement additional features like lighting or texturing

## 📝 Notes for Developers

- Each project is self-contained and can be run independently
- SharpGL handles platform-specific OpenGL initialization
- The rendering loop runs at approximately 60 FPS by default
- Mouse coordinates are normalized to 3D space for smooth interaction

## 🤝 Contributing

This repository is primarily for educational purposes. If you have improvements or new learning projects:
1. Fork the repository
2. Create a feature branch
3. Add your educational project or improvements
4. Submit a pull request

## 📄 License

This repository is intended for educational purposes. Feel free to use, modify, and share for learning.

## 👤 Author

**Hamed** - [GitHub Profile](https://github.com/74hamed)

## 🔗 Resources

- [SharpGL Documentation](https://github.com/dwmkerr/sharpgl)
- [OpenGL Tutorials](https://learnopengl.com/)
- [3D Graphics Fundamentals](https://www.khronos.org/opengl/)
- [C# WinForms Guide](https://docs.microsoft.com/en-us/dotnet/desktop/winforms/)

## 📞 Support

For issues or questions:
- Check existing GitHub issues
- Review the code comments for implementation details
- Consult OpenGL documentation for graphics concepts

---

**Last Updated**: June 2026  
**Repository Status**: Active Learning Project
