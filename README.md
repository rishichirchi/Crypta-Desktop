# Crypta Desktop Application



Crypta Desktop is an advanced digital forensics and incident response (DFIR) application.This is the cross-platform desktop application for the Crypta project, built with the Flutter framework. Designed for anomaly detection and pattern recognition across system data and network activity, Crypta leverages AI/ML models to classify system risks, identify indicators of compromise (IoCs), and provide actionable insights. With support for real-time forensic analysis and a user-friendly interface built using Flutter, it ensures secure and efficient investigations.

---

## Why Crypta?

- **Automated Forensic Data Collection**: Automates tools like FTK Imager, Volatility, RegRipper, and Sysinternals Suite using Python libraries (PyEWF, MemProcFS, Regipy, and PSUtil) to analyze forensic images, memory dumps, registry hives, and background processes.
- **Network Traffic Analysis**: Uses Wireshark and Scapy for packet capture analysis and identification of suspicious network activities.
- **IoC Identification**: Detects anomalies with custom YARA rules and correlates known IoCs using MISP databases.
- **AI/ML Integration**: Employs TensorFlow models for anomaly detection and risk classification, prioritizing critical artifacts for investigators.
- **Cross-Platform Dashboards**: Real-time data visualization, interactive timelines, and exportable reports in PDF, JSON, and CSV formats.
- **Scalable Architecture**: Built with FastAPI, Next.js, and Flutter for high performance and easy deployment.
- **Live Drive Detection**: Enables investigators to connect drives and perform real-time forensic analysis.
- **Chatbot Insights**: Provides detailed explanations of detected anomalies through an integrated chatbot.

---

## Features

- **File Encryption and Decryption**: Protect sensitive data with secure encryption methods.
- **Real-Time Analysis**: Perform live drive detection and forensic analysis.
- **AI/ML-Powered Insights**: Classify system risks and detect anomalies.
- **Comprehensive Reporting**: Generate detailed forensic reports with export options.
- **Cross-Platform Compatibility**: Works seamlessly on Windows, macOS, and Linux.
- **User-Friendly Interface**: Simple and intuitive UI built with Flutter.

---


## Getting Started

Follow these instructions to set up and run the application on your local machine.

### Prerequisites

- Flutter SDK installed. ([Installation Guide](https://docs.flutter.dev/get-started/install))
- Dart SDK installed.
- Git installed.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rishichirchi/Crypta-Desktop.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Crypta-Desktop
   ```

3. Fetch the dependencies:

   ```bash
   flutter pub get
   ```

4. Run the application:

   ```bash
   flutter run
   ```

---

## Usage

1. Select a file to encrypt or decrypt.
2. Provide necessary keys or passwords for encryption/decryption.
3. Save the processed file securely.
4. Perform live forensic analysis by connecting drives.
5. Analyze network traffic for suspicious activities.

---

## Contributing

Contributions are welcome! If you’d like to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:

   ```bash
   git checkout -b feature-name
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add feature-name"
   ```

4. Push to the branch:

   ```bash
   git push origin feature-name
   ```

5. Open a pull request.

---

## License

Specify your license here (e.g., MIT License). Replace the placeholder below if applicable.

```text
This project is licensed under the MIT License - see the LICENSE file for details.
```

---

## **Maintained By**: [Rishi Chirchi](https://github.com/rishichirchi)

- **Author**: Rishi Chirchi
- **Email**: rishiraj.chirchi@gmail.com

Feel free to reach out for collaboration or questions about the project!



