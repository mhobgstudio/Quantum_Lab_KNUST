# Quantum_Lab_KNUST
Quantum Physics Lab from KNUST CoS



To run `.jar` files (Java archives) on Windows, macOS, and Linux, you need to have the Java Runtime Environment (JRE) or Java Development Kit (JDK) installed on your system. Here are the installation steps and basic instructions for each operating system:

## Windows

- **Install Java:**  
  Download the Java installer from the official Java website. Make sure to choose the version appropriate for your system (32-bit or 64-bit). Run the installer and follow the prompts to complete the installation[1][5].
- **Run the JAR file:**  
  - You can double-click the `.jar` file if Java is properly associated with `.jar` files.
  - Alternatively, open Command Prompt, navigate to the folder containing the `.jar` file, and run:
    ```
    java -jar yourfile.jar
    ```
  - If double-clicking opens the file in another program (like WinRAR), right-click the file, select "Open with," and choose "Java(TM) Platform SE Binary"[1][6].

## macOS

- **Install Java:**  
  Download the Java installer for macOS from the Java website. For Apple Silicon (M1/M2), select the ARM64 architecture. Run the `.pkg` installer and complete the setup[2].
- **Run the JAR file:**  
  - Open Terminal.
  - Navigate to the directory containing your `.jar` file using `cd`.
  - Run:
    ```
    java -jar yourfile.jar
    ```
  This will execute the JAR file. If you want to check your Java version, use `java -version`[2].

## Linux

- **Install Java:**  
  Use your distribution's package manager to install the JRE:
  - Ubuntu/Debian:
    ```
    sudo apt update
    sudo apt install default-jre
    ```
  - Fedora/CentOS:
    ```
    sudo dnf install java-latest-openjdk
    ```
  - Arch/Manjaro:
    ```
    sudo pacman -S jre-openjdk
    ```
  - Confirm installation with `java -version`[3].
- **Run the JAR file:**  
  - In Terminal, navigate to the folder containing the `.jar` file.
  - Run:
    ```
    java -jar yourfile.jar
    ```
  - Some desktop environments allow you to right-click the file and select "Open with" → Java Runtime[3].

## Additional Notes

- The Java version must be compatible with the version used to create the JAR file. If you get errors like `UnsupportedClassVersionError`, install a newer Java version[6].
- For all platforms, after installing Java, you may need to restart your terminal or file explorer for changes to take effect[5].
- If you want to develop Java applications, install the JDK (which includes the JRE), not just the JRE[6].

## Summary Table

| OS      | Installation Command/Method                  | Run JAR Command               |
|---------|----------------------------------------------|-------------------------------|
| Windows | Download installer from java.com, run setup  | `java -jar yourfile.jar`      |
| macOS   | Download installer for macOS, run .pkg file  | `java -jar yourfile.jar`      |
| Linux   | Use package manager (see above)              | `java -jar yourfile.jar`      |

