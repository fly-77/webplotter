# Serial Data Plotter WebApp

A **graphical user interface** for plotting serial data received over USB, designed as a more flexible and powerful alternative to Arduino IDE's Serial Plotter.

---

## ✨ Features

- **Flexible Data Parsing**  
  Accepts serial data as a sequence of numbers separated by commas and terminated by a newline.  
  Example input: `12.3,45.6,78.9\n`

- **Customizable Plot Layout**  
  - Define how to split incoming data into multiple graphs using index positions.  
  - Example: Entering `0,2,6` with **2 plot windows** will:
    - Plot the first 2 values in Graph 1
    - Plot the next 4 values in Graph 2

- **CSV Export**  
  - Export received data to Excel-compatible `.csv` files
  - Supports locale-specific settings for:
    - Decimal separator
    - Thousand separator
    - Value separator

- **Graph Controls**  
  - Autoscale Y-axis
  - Rolling X-axis with adjustable range
  - Manual Y-axis scaling
  - Moving average overlay
  - Axis labeling
  - Export all plotted data (including moving averages) to CSV

---

## 🚀 How to Use

- **Online**  
  No installation required — simply open the webapp via the link provided on this page.

- **Offline / Localhost**  
  If your PC doesn't have internet access:
  - Clone or download the project
  - Run it locally using a development environment like **Visual Studio Code**

---

## 📦 Requirements

- A microcontroller sending comma-separated numeric data over USB
- A Chrome browser or other browser that supports the Webserial API to run the webapp


