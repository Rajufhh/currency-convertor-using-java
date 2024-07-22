# currency-convertor-using-java

Currency Converter Project
Project Overview
The Currency Converter project is a Java-based application designed to convert amounts between different currencies. It supports multiple currencies and provides a simple graphical user interface (GUI) for ease of use. The application is built with scalability in mind, allowing for easy addition of new currencies.

Setup and Installation
Prerequisites
Java Development Kit (JDK) 8 or higher
Git (optional, for cloning the repository)
Installation
Clone the Repository (Optional)

bash
Copy code
git clone https://github.com/yourusername/currency-converter.git
cd currency-converter
Download the Project

Download the ZIP file of the project from the repository and extract it.

Compile the Project

Navigate to the project directory and compile the Java files using the following command:

bash
Copy code
javac -d bin src/*.java src/currencies/*.java
Run the Application

Execute the main class to start the application:

bash
Copy code
java -cp bin CurrencyConverterApp
Usage
Launch the application by running the CurrencyConverterApp class.
Select the source currency and the target currency.
Enter the amount to be converted.
Click the "Convert" button to get the converted amount.
Code Structure
The project structure is organized as follows:

scss
Copy code
currency-converter/
│
├── src/
│   ├── CurrencyConverterApp.java
│   ├── currencyConverter.java
│   └── currencies/
│       ├── EUR.java
│       ├── GBP.java
│       ├── INR.java
│       ├── JPY.java
│       ├── KWD.java
│       ├── KYD.java
│       └── USD.java
├── images/
│   ├── converter.png
│   └── please-wait.jpg
└── README.md
Detailed Description of Key Components
CurrencyConverterApp.java
This is the main class that initializes and runs the application. It sets up the GUI and handles user interactions.

currencyConverter.java
This class contains the logic for converting currencies. It includes methods for retrieving exchange rates and performing the conversion.

currencies/
This directory contains Java classes for each supported currency (e.g., EUR.java, GBP.java). Each class defines the currency code and the exchange rate.

Images
converter.png: An image used in the application's GUI.
please-wait.jpg: An image displayed while the conversion is being processed.
Contributing
We welcome contributions to the Currency Converter project! To contribute:

Fork the repository.
Create a new branch for your feature or bug fix.
Implement your changes and commit them with descriptive messages.
Push your branch to your forked repository.
Submit a pull request with a detailed description of your changes.
