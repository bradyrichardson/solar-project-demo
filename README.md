# Solar Energy Calculator Demo 🌞

A cutting-edge solar energy assessment tool that combines advanced 3D visualization, machine learning, and geospatial analysis to provide comprehensive solar potential evaluations for any location.

![Solar Energy Calculator Demo](solar-demo.gif)

## 🚀 Overview

This demo showcases a solar energy algorithm I wrote that leverages a variety of ML technologies to analyze and visualize solar potential. The system processes 3D point cloud data, integrates with Google Maps for real-world context, and employs machine learning models to deliver accurate solar assessments using the PV library.

The result of running this algorithm is a Wh estimate per qualifying surface detected by the algorithm, along with data about the dimensions and angle of each plane in the point cloud.

## ✨ Key Features

- **3D Point Cloud Processing**: Advanced LiDAR data aggregation and processing using Open3D and laspy
- **Geospatial Integration**: Google Maps integration for location-based analysis
- **Machine Learning Pipeline**: PointCLIP v2 integration for  feature extraction
- **Data Science Workflow**: Analysis using pandas, numpy, and scipy
- **Interactive Visualizations**: 3D plots and charts with matplotlib

## 🛠️ Technology Stack

### Core Libraries
- **Open3D**: 3D point cloud processing and visualization
- **Google Maps API**: Geospatial data and location services
- **PyTorch**: Deep learning framework for solar prediction models
- **PointCLIP v2**: Vision-language model for 3D point cloud understanding

### Data Science & Analysis
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing and array operations
- **scipy**: Scientific computing and optimization algorithms
- **matplotlib**: Data visualization and plotting

### 3D & Geospatial
- **laspy**: LiDAR data processing and manipulation
- **Additional GIS tools**: Geospatial analysis and mapping
