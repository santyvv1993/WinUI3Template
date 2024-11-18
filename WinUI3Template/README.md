# WinUI 3 Template (.NET 9)

A minimal, pre-configured template for Windows desktop applications using WinUI 3 and .NET 9.

## Features
- Pre-configured WinUI 3 project structure
- Debug and build configurations
- VS Code workspace settings
- Git integration ready

## Prerequisites

- Windows 10/11
- Visual Studio Code
- .NET 9 SDK
- Windows App SDK
- Git

## Project Structure

- WinUI3Template/ 
- ├── .vscode/ VS Code configuration 
- │ ├── launch.json Debug configuration 
- │ └── tasks.json Build tasks 
- ├── Assets/ Application resources 
- ├── Views/ XAML pages 
- │ └── MainPage.xaml Main application page 
- ├── app.manifest Application manifest 
- ├── WinUI3Template.csproj Project configuration 
- └── README.md 
Project documentation


## Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd <project-name>
```

2. Install dependencies:
```bash
dotnet restore
```

3. Build the project:
```bash
dotnet build
```


4. Run the application:

```bash
dotnet run
```

Development
Branch Strategy
- main: Template base configuration
- develop: Development integration
- feature/*: Feature branches
Creating New Project from Template

Creating New Project from Template
1. Clone template:

git clone <template-url> new-project
cd new-project

2. Reset Git:
```bash
git remote rename origin template
git remote add origin <new-repo-url>
```
3. Create development branch:
```bash
git checkout -b develop
```
Configuration
- Target Framework: net9.0-windows10.0.19041.0
- Windows App SDK: 1.4.231219000
- Platform: x64
- Output Type: WinExe

VS Code Configuration
Includes preconfigured:

- Debug settings
- Build tasks
- Launch configurations

License
MIT License

```bash
Key changes:
- Fixed code block formatting
- Added proper tree structure
- Improved headings hierarchy
- Added proper spacing
- Suggested MIT LicenseKey changes:
- Fixed code block formatting
- Added proper tree structure
- Improved headings hierarchy
- Added proper spacing
- Suggested MIT License
```
