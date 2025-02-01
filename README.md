# Benford's Law Fraud Detection Application

A Java-based client-server application that analyzes numeric data in text files using Benford's Law to detect potential fraud. Features a GUI for client interaction and leverages multithreading to handle multiple clients simultaneously.


## Features

- **Client-Server Architecture**: Separates analysis (server) and user interaction (client).
- **Multithreaded Server**: Handles up to 100+ simultaneous client connections.
- **Interactive GUI**: Built with Swing/AWT for file upload and result visualization.
- **Benford's Law Analysis**: 
  - Calculates leading digit distribution (1-9).
  - Compares results with expected frequencies using chi-squared tests.
- **Network Communication**: Uses Java Sockets for client-server data transfer.

## Prerequisites

- Java Development Kit (JDK) 8 or later.
- Basic understanding of Benford's Law (optional).

## Installation & Usage

### 1. Compile the Project
```bash
javac -d . BenfordsLaw.java BenfordClient.java BenfordServer.java AppliedBenfordsLaw.java



## Demo

### Client GUI
![Client Interface](Benford-s-Law-Fraud-Detection-Analysis/misc/images/Screenshot1.png)

### Analysis Results
![Benford's Law Chart](Benford-s-Law-Fraud-Detection-Analysis/misc/images/Screenshot2.png)
