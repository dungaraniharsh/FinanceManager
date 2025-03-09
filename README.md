# Personal Finance Manager

A Java-based application to manage personal finances, track transactions, and view financial history.

## Prerequisites

- **Java Development Kit (JDK 8 or above)**
  - Check installation:  
    ```bash
    java -version
    ```
  - If not installed, download from:
    - [Oracle JDK](https://www.oracle.com/java/technologies/downloads/)
    - [OpenJDK](https://openjdk.org/)

## Installation & Usage

### Command Line

1. **Navigate to the Project Folder**  
   Open Terminal/Command Prompt and go to the project directory:
   ```bash
   cd path/to/Personal-Finance-Manager-main
2. **Compile the Java Files**
Run:

```bash
    javac *.java
```
 - This generates .class files.

3. **Run the Application**
 - Execute the main class:
```bash
    java FinanceManager
```

4. **Running in an IDE (Optional)**
 - Open the project in IntelliJ IDEA, Eclipse, or VS Code.
 - Ensure FinanceManager.java contains the main() method.
 - Click the IDE's Run button to execute.

5. **Managing Transactions**
 - Follow on-screen prompts to:
    -- Add income/expenses
    -- View transaction history
    -- Analyze financial trends

**All transactions are auto-saved in transactions.txt.**

 
### Features to Highlight:
- Clear CLI instructions for beginners
- Compatibility with both Oracle JDK and OpenJDK
- Persistent data storage via `transactions.txt`
- IDE-friendly setup
