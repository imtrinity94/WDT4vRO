# Workflow Documentation Tool for Aria Automation Orchestrator (WDT4vRO)

A comprehensive visualization and documentation tool that converts XML-based workflow definitions from VMware Aria Automation Orchestrator into intuitive, interactive diagrams. This tool helps teams understand, document, and maintain complex workflows with ease.

![Workflow Visualization Example](assets/wdt4vro-screenshot.png)

## 🌟 Features

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

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/WDT4vRO.git
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
</div>
