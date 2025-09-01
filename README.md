# tirotir Electronics Calculator Suite

Welcome to the **tirotir Electronics Calculator Suite**, a collection of web-based tools designed to assist with various electronics calculations. This suite includes calculators for resistor combinations, Ohm's Law, capacitor charge/discharge, voltage dividers, RC filters, LED circuits, transistor switches, op-amps, inductor combinations, and Wheatstone bridges. All tools feature interactive circuit diagrams and an export image function.

## Overview

- **Branding**: Powered by tirotir
- **Date Created**: September 01, 2025
- **Tools Included**:
  - Resistor Combination Calculator
  - Ohm's Law Calculator
  - Capacitor Charge/Discharge Calculator
  - Capacitor Combination Calculator
  - Voltage Divider Calculator
  - RC Filter Calculator
  - LED Resistor Calculator
  - Transistor Switch Calculator
  - Op-Amp Calculator
  - Inductor Combination Calculator
  - Wheatstone Bridge Calculator

## Features
- Interactive circuit diagrams updated in real-time based on input values.
- Export diagrams as PNG images with the "Export Image" button.
- Responsive design for desktop and mobile use.
- Centralized dashboard (`dashboard.html`) to access all calculators.

## Setup Instructions

### Local Usage
1. **Download or Clone the Repository**:
   - Clone this repository: `git clone <repository-url>` (replace with your repository URL if hosted on GitHub).
   - Alternatively, download the ZIP file and extract it.

2. **Directory Structure**:
   - Ensure all `.html` files (e.g., `resistor_calculator.html`, `dashboard.html`, etc.) are in the same directory.

3. **Open in Browser**:
   - Navigate to `dashboard.html` in your web browser (e.g., Chrome, Firefox) by double-clicking the file or using `file://` protocol (e.g., `file:///path/to/dashboard.html`).

### Hosting Online
- **GitHub Pages**:
  1. Upload the `electronics-calculator-suite` directory to a GitHub repository.
  2. Enable GitHub Pages in the repository settings, selecting the root directory or `/electronics-calculator-suite` as the source.
  3. Access the live site at `https://<username>.github.io/<repository-name>/electronics-calculator-suite/dashboard.html`.

- **Other Hosting**: Use any static site hosting service (e.g., Netlify, Vercel) by uploading the directory.

## Usage
1. Open `dashboard.html` to view the list of calculators.
2. Click on any calculator name to access its tool.
3. Enter the required input values and click "Calculate" to see results and updated diagrams.
4. Use the "Export Image" button to download the current diagram as a PNG file.
5. Some tools include a "Reset" button to clear inputs and diagrams.

## Tools Details
- **Resistor Combination Calculator**: Find the best series, parallel, or hybrid combination of identical resistors.
- **Ohm's Law Calculator**: Compute voltage, current, or resistance.
- **Capacitor Charge/Discharge Calculator**: Calculate capacitor voltage over time.
- **Capacitor Combination Calculator**: Determine equivalent capacitance.
- **Voltage Divider Calculator**: Calculate output voltage and resistor values.
- **RC Filter Calculator**: Compute cutoff frequency for low-pass or high-pass filters.
- **LED Resistor Calculator**: Calculate the limiting resistor for an LED circuit.
- **Transistor Switch Calculator**: Determine base resistor for an NPN transistor switch.
- **Op-Amp Calculator**: Calculate gain and resistor values for op-amp circuits.
- **Inductor Combination Calculator**: Find equivalent inductance for series or parallel combinations.
- **Wheatstone Bridge Calculator**: Calculate unknown resistance or balance voltage.

## Known Issues
- The "Export Image" button may occasionally fail if the canvas is not fully rendered. A 100ms delay is implemented as a workaround; report persistent issues for further optimization.
- No internet connection is required for local use, but hosting online requires a static file server.

## Contributing
This is a static HTML/CSS/JavaScript project. Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make changes and commit: `git commit -m "Description of changes"`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.

## Contact
- **Website**: [tirotir](https://tirotir) (if applicable, update with your actual domain)
- **Support**: For issues or suggestions, contact support@tirotir (replace with your email).
- **Date Updated**: September 01, 2025, 11:32 AM +04

## License
This project is open-source under the MIT License. See `LICENSE` file for details (create a `LICENSE` file if needed).

---

*Powered by tirotir & AI- Your Electronics Calculation Companion*