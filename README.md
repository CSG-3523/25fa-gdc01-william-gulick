# 2025 CSG - Unity 6 Template Repository
Official 2025 Spring CSG Unity 6 project template repository! 

Read the guide below for essential information about the setup, structure, and best practices for working with this repository.

## **1. Setup Instructions**
- **Unity Editor Installation**: 
  - Download and install Unity 3D Editor (Version: `6000.0.34f1` or later) from [**Unity's official website**](https://unity.com/releases/editor/archive).
  
- **Clone the Repository**
   - Open **GitHub Desktop**, go to the 'Repositories' tab, and click on 'Add > Clone Repository'.
   - Paste the repository URL (`https://github.com/[your-repo-url]`) into the input field.
   - Click "Clone" to create the repository on your machine.

## **2. Repository Structure**
The project repository is organized as follows:
- **README.md**: This file you're reading.
- **resources**: A folder for any external content (e.g., notes, raw asset files).
- **ProjectName-Unity**: The Unity 6 project folder containing:
  - **`.gitignore`** and **`.gitattributes`** configured for Unity

## **3. Unity Project**    
- **Project Template**: The Unity project uses the **3D core URP** template. Learn more about [**URP for Unity 6**](https://unity.com/resources/introduction-to-urp-advanced-creators-unity-6)
- **Project Organization**: The project has been pre-sturctured using the standard Asset folder sturcture. Read more on project [**Project Organization**](https://getcreativetoday.com/GCT-Unity/unity-project-setup/project-organization)
    - All asset files should adhear to the following [**Asset Naming Conventions**](https://getcreativetoday.com/GCT-Unity/project-management/asset-naming)
- **Included Packages**: This project includes the [**Unity Hierarchy Folders**](ttps://github.com/xsduan/unity-hierarchy-folders) package, which as the name suggests allows for the visual use of folders for organziation in the Unity Hierarchy. 

## **4. Git Workflow Guidelines**
- **Gitignore Check**: Before pushing large (>1000 files), ensure `.gitignore` is present in the `ProjectName-Unity` folder and properly configured.
- **Large File Storage**: To allow for large file storage (LFS), ensure that the `.gitattributes` is properly setup.
   - Example `.gitattributes` for unity can be found here: []()
- **Commit Message**: Follow [**standard commit conventions**]().   
- **Branching Strategy**: Branches should typically be named by feature and/or release using the the keywords to idenitfy the type of branch. (e.g. `feature/inventory` or `release/v1.0` )

## **5. General Information**
This repository was developed for student use in the Computer Simulation & Gaming (CSG) program at the University of tulsa. 

For more  infomration contact program cordinator: [**Akram Taghavi-Burris**](akram-burris@utulsa.edu)


