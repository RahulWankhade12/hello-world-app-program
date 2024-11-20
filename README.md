Here’s how you can create a simple "Hello World" app in **Java**:

### Step 1: Write the Code

1. Open any text editor (e.g., Notepad, VSCode, IntelliJ IDEA).
2. Create a new file and name it `HelloWorld.java`.

Paste the following code into the file:

```java
// HelloWorld.java
public class HelloWorld {
    public static void main(String[] args) {
        // Print "Hello, World!" to the console
        System.out.println("Hello, World!");
    }
}
```

### Step 2: Save the File
Make sure the file is saved as `HelloWorld.java`. Java filenames must match the public class name, which in this case is `HelloWorld`.

### Step 3: Compile the Java Program
1. Open your terminal (Command Prompt on Windows or Terminal on macOS/Linux).
2. Navigate to the folder where `HelloWorld.java` is saved.
3. Compile the Java program using the `javac` command:

```bash
javac HelloWorld.java
```

This will create a `HelloWorld.class` file in the same directory.

### Step 4: Run the Java Program
Now, run the compiled Java program using the `java` command:

```bash
java HelloWorld
```

### Expected Output:
```
Hello, World!
```

---

### Summary:
- **Java file**: `HelloWorld.java`
- **Code**: Prints "Hello, World!" to the console.
- **Commands**: `javac` to compile and `java` to run.
