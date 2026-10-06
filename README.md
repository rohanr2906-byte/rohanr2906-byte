# Hi, I'm Rohan Rosario Ravikanth

Master’s student in **Electrical and Microsystems Engineering at OTH Regensburg**, focused on **Applied AI, embedded systems, test and validation, automation, machine vision, and Python-based engineering tools**. I build practical projects that combine **software, electronics, data analysis, and real-world engineering applications**.

## Technical Focus

- Applied AI for Engineering
- Embedded Systems and Electronics
- Test and Validation
- Software Testing and QA Automation
- Python-Based Engineering Tools
- Machine Vision and Industrial Inspection
- Industrial Automation
- IoT and Energy Management
- Measurement Data Analysis
- PCB Design and Hardware Integration

## Technical Skills

| **Area** | **Skills and Tools** |
| --- | --- |
| **Programming and Data** | Python, C, C++, NumPy, pandas |
| **Applied AI** | LLMs, Ollama, AI-assisted engineering workflows, engineering data analysis |
| **Software and Web** | FastAPI (Basic), SQL (Basic), TypeScript (Basic), HTML |
| **Testing and Validation** | pytest, Playwright, manual testing, functional testing, system-level testing, test-case development, debugging, root-cause analysis |
| **AI and Speech** | Ollama, local large language models, Whisper speech recognition |
| **Computer Vision** | OpenCV, Cognex VisionPro, Cognex DataMan, machine vision, image processing, defect detection, industrial inspection, 3D vision systems |
| **Embedded Systems** | Arduino, STM32, Raspberry Pi, UART, I²C, PWM, sensor and actuator integration |
| **Automation** | Industrial automation, PLC and HMI fundamentals, hardware-software integration, commissioning |
| **Electronics** | KiCad, schematic design, PCB layout, PCB assembly, soldering, circuit wiring, sensor integration |
| **Measurement** | Oscilloscope, multimeter, power-supply measurements, signal measurements, hardware troubleshooting |
| **Engineering Tools** | Git, GitHub, GitHub Actions, MATLAB, Simulink, Microsoft Excel, PowerPoint, Word |

## Master's Thesis — Ongoing

### Evaluation of AI Tools for Engineering Analysis of Substation Measurement Data in Low-Voltage Distribution Networks

- Analysing low-voltage substation measurement data including phase currents, voltage, power, phase imbalance, missing values, and data plausibility.
- Evaluating AI tools for engineering reasoning, data analysis, assumption handling, and missing-information detection.
- Comparing tools including ChatGPT, Claude, Gemini, Genspark, and Manus.
- Documenting engineering results using Excel analysis, data visualisations, presentations, and technical reports.
- Investigating the practical use of Applied AI in electrical-engineering data analysis.

**Technologies:** ChatGPT, Claude, Gemini, Genspark, Manus, Excel, Data Analysis, Data Visualization, Technical Reporting

## Public GitHub Projects

### Data Analysis, Applied AI and Automation

#### [AI Agent for Missing-Data Analysis](https://github.com/rohanr2906-byte/ai-agent-missing-data-analysis)

- Developed an explainable Python workflow for detecting, analysing, visualising, and handling missing values in CSV and Excel measurement datasets.
- Implemented rule-based strategy recommendations, phase-current and neutral-current plausibility checks, automated reports, data visualisations, pytest tests, and GitHub Actions.
- **Technologies:** Python, pandas, openpyxl, Matplotlib, pytest, GitHub Actions

#### [AI Workflow Automation System](https://github.com/rohanr2906-byte/ai-workflow-automation)

- Developed a Python workflow that reads task information from CSV files, processes the data, and generates an automated summary report.
- **Technologies:** Python, pandas, CSV

#### [OpenCV Quality Inspection Demo](https://github.com/rohanr2906-byte/opencv-quality-inspection-demo)

- Developed an image-processing demonstration for detecting defects in sample industrial-part images.
- Applied grayscale conversion, thresholding, contour detection, defect-classification logic, and automated validation.
- **Technologies:** Python, OpenCV, NumPy, pytest

### Embedded Systems, Electronics and IoT

#### [Automotive Indicator Control ECU Demo](https://github.com/rohanr2906-byte/gray-indicator-control-ecu)

- Developed an Arduino-based automotive indicator control module supporting left, right, hazard, and indicator-off functions.
- Implemented GPIO input handling, LED control, non-blocking timing using `millis()`, UART logging, wiring documentation, and validation test cases.
- **Technologies:** Arduino Uno, Embedded C/C++, GPIO, UART, Arduino IDE

#### [Smart Heating IoT Demo](https://github.com/rohanr2906-byte/smart-heating-iot-demo)

- Developed a simulated multi-zone heating-control system using CSV-based temperature measurements and automatic day and night profiles.
- Implemented hysteresis control, energy-consumption estimation, CSV logging, automated tests, GitHub Actions, and an HTML dashboard.
- **Technologies:** Python, Matplotlib, pytest, HTML, CSV, GitHub Actions

#### [LED Indicator PCB](https://github.com/rohanr2906-byte/LED_Indicator_Board)

- Designed a functional LED indicator PCB while following the complete PCB-development workflow.
- Created the schematic, assigned footprints, routed the board, completed ERC and DRC checks, generated a 3D model, and exported Gerber and drill files.
- **Technologies:** KiCad 10, Schematic Editor, PCB Editor, 3D Viewer

### Software Development, Testing and QA

#### [Playwright TypeScript UI Test Automation](https://github.com/rohanr2906-byte/ui-test-automation-playwright)

- Developed automated UI tests for valid and invalid login scenarios on the SauceDemo web application.
- Applied the Page Object Model to separate selectors, user actions, and test logic while validating URLs, page titles, inventory items, and error messages.
- **Technologies:** Playwright, TypeScript, Node.js, Page Object Model, HTML Reporting

#### [DemoShop Mobile QA Testing Project](https://github.com/rohanr2906-byte/mobile-app-qa-test-plan-demo)

- Developed and tested a responsive mock shopping application with login, product search, cart, checkout, order confirmation, and logout functionality.
- Prepared manual test cases, bug reports, screenshot evidence, test-summary documentation, responsive viewport tests, and automated UI tests.
- **Technologies:** Python, Playwright, pytest, HTML, CSS, JavaScript, Manual Testing

#### [Backend API Demo Using FastAPI](https://github.com/rohanr2906-byte/backend-api-demo-fastapi)

- Developed a backend API demonstration with database integration and automated testing.
- Organised the project into API and testing components with SQLAlchemy database handling and a local SQLite task database.
- **Technologies:** Python, FastAPI, SQLAlchemy, SQLite, pytest

## Academic Projects

### Development and Evaluation of an Intelligent Voice Assistant

- Developed and completed a local AI voice assistant using Python, Ollama, and offline Whisper.
- Implemented voice and keyboard interaction, multilingual conversations, memory, response streaming, weather information, lecture transcription, structured notes, summaries, action items, and revision questions.
- Evaluated response time, speech-recognition accuracy, and system performance, with results exported to CSV and Excel.
- Refactored the application into modular Python components and deployed it successfully on a Raspberry Pi 5.
- Integrated USB microphone input and bi-colour LED status indication and verified successful assistant interaction on the Raspberry Pi.

**Technologies:** Python, Ollama, Whisper, Raspberry Pi 5, USB Microphone, Local LLMs

### Anti-Theft Smart Billing System

- Developed an automated smart billing system using RFID, a load cell, and a microcontroller-controlled robotic trolley.
- Implemented real-time product identification, item tracking, weight verification, and billing validation to detect unauthorised item additions or removals.
- Designed, integrated, and tested the hardware using RFID and weight sensors, an LM7805 voltage-regulation circuit, and embedded control logic.

**Technologies:** RFID, Load Cell, Microcontroller, LM7805, Embedded C

### Anti-lock Braking System Study

- Studied anti-lock braking system behaviour using wheel-speed sensing and braking-control principles.
- Analysed the relationship between wheel-speed variation, wheel locking, and real-time braking response.
- Developed an understanding of automotive electronic control and system integration.

## Career Interests

I am building practical skills for opportunities in:

- Applied AI for Engineering
- Embedded Systems Engineering
- Test and Validation Engineering
- Software Testing and QA Automation
- Industrial Automation
- Machine Vision and Industrial Inspection
- IoT and Energy Management
- Automotive and Electronics Testing
- Python-Based Engineering Tool Development

## Languages

- **English:** C1
- **German:** B1, actively improving toward B2

## Contact

- **Email:** rohan.r2906@gmail.com
- **GitHub:** https://github.com/rohanr2906-byte
