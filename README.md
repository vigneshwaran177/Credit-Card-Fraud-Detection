# Credit-Card-Fraud-Detection
Java-based project for detecting fraudulent credit card transactions using pattern recognition and basic machine learning models. Focused on real-time monitoring, minimizing false positives, and ensuring secure transaction analysis.
# Advanced Fraud Detection System

This is a simple **Fraud Detection System** built with Java using **AWT** for the graphical user interface (GUI). The system checks whether a financial transaction is fraudulent based on three rules:
- **High Transaction Amount**: If the transaction amount exceeds a threshold, it is flagged as fraudulent.
- **Suspicious Location**: Transactions from certain blocked locations are flagged as fraudulent.
- **Time-based Fraud**: Transactions during high-risk hours (midnight to 4 AM) are flagged as fraudulent.

## Features
- **Fraud Detection**: Checks whether a transaction is fraudulent based on the amount, location, and time.
- **Transaction History**: Displays all past transaction results.
- **User Interface**: Built using Java AWT with a grid layout.

## Technologies Used
- **Java**: AWT for GUI.
- **SimpleDateFormat**: For handling time input.

## How to Run
1. **Install Java**: Make sure you have the [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) installed.
2. **Download the Code**: Clone or download the project from GitHub.
3. **Compile**: 
    ```bash
    javac AdvancedFraudDetectionAWT.java
    ```
4. **Run**:
    ```bash
    java AdvancedFraudDetectionAWT
    ```

## Contributing
Feel free to fork the repository and submit pull requests. If you have suggestions for new features or improvements, open an issue or a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
