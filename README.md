# MultidimensionalProject5

This project is a Microsoft Analysis Services (SSAS) multidimensional model using the Adventure Works sample data. It includes cube definitions, dimensions, and fact tables for multidimensional analysis.

## Setup
- **Prerequisites**: Microsoft SQL Server Analysis Services (SSAS) 2017 or later, Adventure Works database installed.
- **Setup Steps**:
  1. Open the `MultidimensionalProject5.sln` file in Visual Studio 2017.
  2. Build the solution to generate the SSAS cube.
  3. Configure the data source to connect to the Adventure Works database.

## Usage
- The project contains a cube named `MultidimensionalProject5` for OLAP analysis.
- Dimensions include Customer, Product, Sales Territory, etc.
- Fact tables like `Fact Internet Sales` provide aggregated data for analysis.

## Files
- `.sln`: Visual Studio solution file.
- `.dwproj`: Project file for the SSAS cube.
- `.dwproj.user`: User-specific project settings.
- `.database`: Database file for the SSAS cube.
- `.dim` files: Dimension definitions (e.g., Dim Customer, Dim Product).
- `.cube`, `.ds`, `.dsv`: Cube and data source files.

## Contributing
- Fork the repository and submit pull requests for improvements.