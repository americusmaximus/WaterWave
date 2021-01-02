# WaterWave
WaterWave is a  C# library to work with Wavefront .obj and .mtl files.

WaterWave is a library that runs on .Net Framework 4.0, 4.5, 4.7, 4.8, .Net Core 3.1, as well as .Net 5. Please see Build and Usage sections below for details.

## Build
### Windows
#### Visual Studio
Open one of the solutions and build it. Please see `<TargetFrameworks>` node in the `.csproj` files to add or remove target frameworks for the build.

#### CLI
To build the solution please use following command:

> dotnet build WaterWave.sln --configuration Release

To build the solution for only one of the target frameworks please use the following command that shows an example of building for .Net 5.

> dotnet build WaterWave.sln --framework net50 -- configuration Release

### Linux
Please see the CLI section of building the code under Windows.

## Use
[Triangulator](https://github.com/americusmaximus/Triangulator) uses the library to convert height map images to Waterfront .obj files.