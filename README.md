# Java Setup and First Programs

This guide covers the essential steps to set up Java on Windows, write your first Java programs, and install Eclipse IDE.

---

## 1. Install Java JDK on Windows (from Oracle)

- Go to the [Oracle JDK download page](https://www.oracle.com/java/technologies/downloads/) and download the latest Java JDK installer for Windows.
- Run the installer and follow the prompts to install Java JDK on your system.

---

## 2. Set the Environment Path in Windows

- After installing JDK, you need to set the `JAVA_HOME` and update your `Path` variable:
  1. Search for "Environment Variables" in Windows search.
  2. Click "Edit the system environment variables".
  3. In the System Properties window, click "Environment Variables".
  4. Under "System variables", click "New" and set:
     - Variable name: `JAVA_HOME`
     - Variable value: Path to your JDK folder (e.g., `C:\Program Files\Java\jdk-XX`)
  5. Find the `Path` variable, click "Edit", and add: `%JAVA_HOME%\bin`
  6. Click OK to save changes.

---

## 3. Write Your First Java Code: Hello World

Create a file named `q.java` with the following code:

```java
public class q {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
