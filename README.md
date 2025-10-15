# 👣 Carbon-Footprint-App

## 🇪🇺 Project Context

This application was developed as a core project for the **Object-Oriented Programming (OOP)** class, forming a thematic component of the wider European initiative: **"Gender, Digitalization, Green: Ensuring a Sustainable Future for all in Europe."**

The goal is to provide users with an accessible tool to calculate their personal carbon footprint and promote sustainable lifestyle choices.

## ✨ Core Functionality

The application calculates the user's total carbon footprint by collecting information about their lifestyle across several categories.

### Factors Considered:

The calculation integrates multiple sources of emissions, primarily influenced by user-provided data on:

* **Household:** Energy consumption (electricity, heating, etc.).
* **Travel:** Emissions from various modes of transport, including:
    * Flights
    * Car usage
    * Motorbike usage
    * Public transport (Bus & Rail)
* **Other Emissions:** General lifestyle factors (e.g., hotels, clothing consumption, food and drink, pharmaceuticals).

## 📐 Architecture and Technology

The application employs a robust, two-tiered architecture to ensure separation of concerns between the user interface and the calculation logic:

* **Front-End (Qt):** Responsible for the graphical user interface (GUI) and user interaction.
* **Back-End (C++):** Manages the core data models, business logic, and interaction with external calculation modules.

### **API Integration via Python Scripts**
Crucially, the application calculates the carbon footprint by leveraging **external APIs** (Application Programming Interfaces) designed specifically for emission factor calculations. These API calls are orchestrated and executed through dedicated **Python scripts** integrated into the C++ backend.

## ⚙️ Dependencies and Setup

Due to the complex nature of integrating C++ with the Qt Framework, specific steps and dependencies are required for compilation and execution.
To build and run this project, you must install the following components:

1.  **Qt Installation:** Install the Qt framework using the official installer. A custom download must be performed to include all necessary components:
    * **Qt Design Studio 4.6.1**
    * **Qt WebEngine**
    * **Qt 6.8.0**
    * **Developer and Designer Tools**
    * **Qt Creator 14.0.2**
2.  **C/C++ Compiler:** A standard C++ compiler (like GCC or MSVC) compatible with your OS and Qt installation.
3.  **Python Environment:** A Python environment must be set up to execute the API calling scripts.

## 🙋 My Specific Contribution

As a member of the development team, my primary responsibilities focused on the critical data collection and calculation layers:

* **Python Scripting:** I was responsible for developing and testing the dedicated **Python scripts** that handle the data processing and make calls to the external carbon factor calculation APIs.
* **C++ Integration:** I managed the **integration of these Python scripts** into the overarching C++ backend architecture, ensuring seamless data exchange and robust error handling between the two programming environments.
* **Front-End Assistance:** I contributed to the **initial implementation of the Front-End** (Qt), focusing on specific user input forms related to lifestyle factors.
