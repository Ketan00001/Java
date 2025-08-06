# Java Setup and First Programs

This guide covers the essential steps to set up Java on Windows, write your first Java programs, and install Eclipse IDE.

---

## 1. Install Java JDK on Windows (from Oracle)

- Go to the [Oracle JDK download page](https://www.oracle.com/java/technologies/downloads/) and download the latest Java JDK installer for Windows.
- Run the installer and follow the instructions to install Java JDK on your system.

---

## 2. Set the Environment Path in Windows

- After installing JDK, set up your environment variables:
  1. Open the Start menu and search for "Environment Variables".
  2. Click on "Edit the system environment variables".
  3. In the System Properties window, click "Environment Variables".
  4. Under "System variables", click "New" to add:
     - Variable name: `JAVA_HOME`
     - Variable value: Path to your JDK directory (e.g., `C:\Program Files\Java\jdk-XX`)
  5. Find the `Path` variable, click "Edit", and add: `%JAVA_HOME%\bin`
  6. Save changes by clicking OK.

---

## 3. Write Your First Java Code: Hello World

Create a file named `q.java`:

```java
public class q {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

**How to run:**
1. Open Command Prompt.
2. Navigate to the folder containing `q.java`.
3. Compile: `javac q.java`
4. Run: `java q`

---

## 4. Program for Sum of Two Numbers

Create a file named `Main.java`:

```java
class Main {
  public static void main(String[] args) {
    int num1 = 2;
    int num2 = 1;
    int sum = num1 + num2;
    System.out.println(sum);
  }
}
```

**How to run:**  
Repeat the steps above:  
- Compile: `javac Main.java`
- Run: `java Main`

---

## 5. Download Eclipse IDE for Windows

- Go to the [Eclipse Downloads page](https://www.eclipse.org/downloads/) and download "Eclipse IDE for Java Developers".
- Run the installer and follow the setup instructions.
- Once installed, open Eclipse and set up your workspace to start writing Java code with an IDE.

---
