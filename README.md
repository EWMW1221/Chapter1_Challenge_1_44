Chapter1_Challenge_1_44)
📘 Description
Config File Loader is a Java console program that demonstrates file handling and exception management.
It reads a configuration file (config.txt), validates its contents, and checks whether a specified file path exists.

The program covers multiple types of exceptions including:

File not found
Invalid number format
Input/output errors
Custom exceptions for business logic
🧩 Features
Reads a configuration file line by line using BufferedReader.
Parses the version number and checks for compatibility.
Reads a file path from the config and verifies its existence.
Handles multiple exceptions gracefully:
FileNotFoundException
NumberFormatException
IOException
General Exception
Ensures cleanup and final message using finally block.
🛠️ Requirements
Java Development Kit (JDK) version 8 or later
A text editor or IDE (e.g., VS Code, IntelliJ IDEA, NetBeans, Eclipse)
A configuration file named config.txt in the project directory
🚀 How to Run
1️⃣ Prepare the Config File
Create a config.txt file in the project directory with the following structure:
