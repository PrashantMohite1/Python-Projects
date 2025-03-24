To create a virtual environment (venv) in Python, follow these steps:

1. **Open your terminal or command prompt**.

2. **Navigate to the directory** where you want to create the virtual environment. Use the `cd` command to change directories if needed.

   Example:
   ```bash
   cd path/to/your/project
   ```

3. **Create the virtual environment**. Run the following command:

   - On **Windows**:
     ```bash
     python -m venv myenv
     ```

   - On **macOS/Linux**:
     ```bash
     python3 -m venv myenv
     ```

   This will create a directory called `myenv` (or any name you choose) that contains the virtual environment.

4. **Activate the virtual environment**:

   - On **Windows**:
     ```bash
     .\myenv\Scripts\activate
     ```

   - On **macOS/Linux**:
     ```bash
     source myenv/bin/activate
     ```

   After activation, your terminal prompt should change to show the name of your virtual environment.

5. **Deactivate the virtual environment** when you're done by typing:
   ```bash
   deactivate
   ```

Once the virtual environment is activated, you can install packages in isolation using `pip` and they will only be available within that environment.

Let me know if you need more help!