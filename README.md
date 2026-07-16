# Sysmon Config Generator

An interactive, browser-based tool for creating, editing, validating, and exporting **Sysmon XML configurations** without manually writing XML.

Built for SOC Analysts, Detection Engineers, Threat Hunters, DFIR professionals, and Blue Teamers.

---

## Features

* Interactive Sysmon rule builder
* Import existing `sysmonconfig.xml`
* Live XML preview
* Export ready-to-use Sysmon configuration
* Rule Groups with Include/Exclude support
* Support for all major Sysmon Event IDs
* Built-in configuration linting and validation
* MITRE ATT&CK technique tagging
* ATT&CK coverage dashboard
* Detection presets (Baseline, Minimal, OT/ICS)
* Community configuration imports
* Deployment helper for Windows and Linux
* Fully client-side (no backend required)
* Works completely offline

---

## Why This Project?

Creating Sysmon configurations manually is tedious and error-prone.

This project provides an intuitive interface that allows security professionals to:

* Build detection rules visually
* Reduce XML syntax errors
* Organize RuleGroups efficiently
* Import and modify existing configurations
* Validate configurations before deployment
* Export production-ready Sysmon XML

---

## Supported Features

* Process Create
* Network Connections
* Registry Events
* Driver Load
* Image Load
* Process Access
* Process Tampering
* WMI Events
* DNS Queries
* File Events
* Named Pipes
* Remote Thread Creation
* File Blocking
* Clipboard Monitoring
* Raw Disk Access
* And more...

---

## Technology Stack

* HTML5
* CSS3
* Vanilla JavaScript
* DOMParser API
* FileReader API
* XML Generation

No frameworks.

No dependencies.

No installation required.

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/squzu/sysmon-config-generator.git
```

Open:

```text
index.html
```

in any modern browser.

That's it.

---

## Project Structure

```text
sysmon-config-generator/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
└── Examples/
```

---

## Roadmap

* Save/Load projects as JSON
* Drag-and-drop RuleGroups
* Search and filter fields
* Rule templates
* Sigma rule export
* ATT&CK Navigator export
* XML schema validation
* AI-assisted rule generation
* Dark/Light theme switch

---

## Contributing

Contributions are welcome.

If you'd like to improve the project, feel free to fork the repository, create a feature branch, and submit a pull request.

---

## License

This project is licensed under the MIT License.

See the LICENSE file for details.

---

## Author

**Shridhar Kamath**

Cybersecurity | Detection Engineering | Threat Hunting | Red Teaming

If you found this project useful, consider giving it a ⭐ on GitHub.
