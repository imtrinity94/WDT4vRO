# Workflow Documentation Tool for Aria Automation Orchestrator (WDT4vRO) v2.0.0

[![Open in Browser](https://img.shields.io/badge/Open%20in-Browser-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://wdt4vro.vercel.app/)
[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg?style=for-the-badge)](https://github.com/imtrinity94/WDT4vRO/releases/tag/v2.0.0)

A comprehensive visualization and documentation tool that converts XML-based workflow definitions from VMware VCF Operations Orchestrator (aka Aria Automation Orchestrator or vRealize Orchestrator) into intuitive, interactive diagrams. This tool helps teams understand, document, and maintain complex workflows with ease.

🌐 **Try Online**: [https://wdt4vro.onrender.com/](https://wdt4vro.onrender.com/) or [https://wdt4vro.vercel.app/](https://wdt4vro.vercel.app/)

## 🚀 What's New in v2.0.0

- **Enhanced Script Display**
  - Improved script viewing with syntax highlighting
  - Better handling of script content in custom conditions
  - More reliable script extraction from workflow items

- **Improved Workflow Item Handling**
  - Better support for custom conditions
  - More accurate display of workflow item properties
  - Fixed issues with Windows OS condition display

- **UI/UX Improvements**
  - Updated welcome screen with version information
  - Better error handling and user feedback
  - Improved layout for workflow details

## Homescreen
<img width="816" alt="image" src="https://github.com/user-attachments/assets/8041e1e3-3286-4caa-9a84-c87e3e19d801" />

## Generated Workflow Schema
![Workflow Visualization Example](assets/wofklow_sample_diagram.png)

## Generated Metadata Tables and Scripts Tables
<img width="851" alt="image" src="https://github.com/user-attachments/assets/286e7cc5-570c-4f63-8510-a4ab7975f772" />


## 🌟 Key Features

- **📝 XML Workflow Import**
  - Directly upload XML workflow files
  - Supports all standard vRO workflow elements
  - Automatic detection of workflow types and relationships

- **🎨 Intelligent Visualization**
  - Automatic layout of workflow elements
  - Color-coded nodes for different element types
  - Custom icons for different workflow actions
  - Support for async workflows and scheduled tasks

- **🔍 Interactive Interface**
  - Zoom and pan functionality
  - Detailed tooltips on hover
  - Responsive design for all devices
  - Full-screen mode for better visibility

- **📄 Comprehensive Documentation**
  - Automatic metadata extraction
  - Input/output parameter documentation
  - Workflow element details panel
  - Export functionality for sharing

## 🚀 Getting Started

### Quick Start

#### Option 1: Use Online Version (Recommended)
1. Go to [https://wdt4vro.onrender.com/](https://wdt4vro.onrender.com/)
2. Click "Upload Workflow" and select your XML file

#### Option 2: Run Locally
1. **Clone the repository**
   ```bash
   git clone https://github.com/imtrinity94/WDT4vRO.git
   cd WDT4vRO
   ```

2. **Run a local server**
   - Python 3:
     ```bash
     python -m http.server 8000
     ```
   - Or use any other local web server

3. **Open in browser**
   - Navigate to `http://localhost:8000`
   - Click "Upload Workflow" and select your XML file

## 🛠️ Usage Guide

### Uploading Workflows
1. Click the "Upload Workflow" button
2. Select your XML workflow file
3. The tool will automatically process and display the workflow

### Navigation
- **Zoom**: Use the +/- buttons or mouse wheel
- **Pan**: Click and drag the canvas
- **Reset View**: Click the home button

### Export Options
- **PNG**: Download as high-resolution image
- **HTML**: Self-contained HTML export

## 🏗️ Project Structure

```
WDT4vRO/
├── assets/               # Static assets and images
│   ├── wdt4vro_icon.svg   # Application icon
│   └── wdt4vro-screenshot.png # Screenshot
├── icons/                 # Workflow element icons
│   ├── action.svg         # Action icon
│   ├── workflow-async.svg # Async workflow icon
│   ├── workflow-schedule.svg # Schedule workflow icon
│   └── ...
├── Sample Workflow XMLs/  # Example workflow files
│   └── all-workflow-element-polyglot.xml
├── index.html            # Main application file
├── full.render.js        # Graphviz renderer
├── README.md             # This file
└── LICENSE               # License information
```

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Report Issues**
   - Found a bug? Open an issue with steps to reproduce
   - Have a feature request? Let us know!

2. **Submit Pull Requests**
   - Fork the repository
   - Create a feature branch
   - Commit your changes
   - Push to your fork
   - Submit a pull request

3. **Improve Documentation**
   - Update README
   - Add code comments
   - Write tutorials or guides

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support, please:
1. Check the [Issues](https://github.com/imtrinity94/WDT4vRO/issues) page
2. If your issue isn't listed, create a new one
3. For direct contact, email support@example.com

## 📚 Resources

- [vRO Documentation](https://docs.vmware.com/en/vRealize-Orchestrator/)
- [Graphviz Documentation](https://graphviz.org/documentation/)
- [SVG Reference](https://developer.mozilla.org/en-US/docs/Web/SVG)

## 🌟 Special Thanks

- VMware for vRealize Orchestrator
- The Graphviz team
- All contributors and users

---

<div align="center">
  Made with ❤️ by the WDT4vRO Team
  
  ---
  
  <sub>VMware Aria Automation Orchestrator™ is a trademark of Broadcom Inc. This project is not affiliated with or endorsed by Broadcom Inc. or its subsidiaries.</sub>
</div>
