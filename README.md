# ChatGPT-Clone
Project Setup Instructions
1. Install Node.js
 To run the Node.js files in this project, you need to have Node.js installed on your laptop. Follow these steps:

• Visit the official Node.js website: https://nodejs.org/.
• Download and install the LTS version (Long-Term Support).
• Once installed, verify the installation by opening your terminal/command prompt and running the following command:
node -v
This should display the installed version of Node.js. If it works, Node.js is installed successfully.
• If there’s an issue with running it, delete the node_modules folder and package-lock.json file, and then run:
npm install
in the VS Code terminal to download the dependencies mentioned in the package.json file.

2. Install Tailwind CSS Extension in VS Code
Follow these steps to install the Tailwind CSS IntelliSense extension for better support in VS Code:

• Open VS Code.
• Go to the Extensions Panel:
• On the left sidebar, click on the Extensions icon (or press Ctrl+Shift+X).
• Search for "Tailwind CSS IntelliSense":
• In the search bar, type Tailwind CSS IntelliSense and press Enter.
• Install the Extension:Click on the Install button next to the extension.

3. Install Flask and PyMongo Globally
You can install Flask and PyMongo without using a virtual environment by following these steps:

•Open the terminal in VS Code by clicking on Terminal > New Terminal.
•Run the following commands to install Flask and PyMongo globally:
pip install flask
pip install pymongo

4. Verify Installations
To verify that Flask and PyMongo were successfully installed, run:
pip list
You should see both Flask and PyMongo in the list of installed packages.

5. Configure VS Code to Use the Python Interpreter
VS Code should automatically detect the global Python interpreter, but if you encounter issues, follow these steps:

• Press Ctrl+Shift+P (or Cmd+Shift+P on macOS) to open the Command Palette.
• Type Python: Select Interpreter and select it.
• Choose the system-wide Python interpreter.

6. Install MongoDB Compass
Download and install MongoDB Compass from the official website: MongoDB Compass Download.
Follow the installation instructions for your operating system.
• Connect to MongoDB Database Using the Connection String
• Open MongoDB Compass.
• When prompted, paste the connection string found in line 13 of the main.py file in the project into the connection field and click Connect.
    The connection string in your project will look like this:
    mongodb+srv://<username>:<password>@cluster0.mongodb.net/<database_name>?retryWrites=true&w=majority
•After connecting, you will be able to view the collections and data stored in the MongoDB database.You can use the MongoDB Compass GUI to explore, add, or modify data as needed.

8. Set Up API Key for OpenAI
• Create a Fresh OpenAI Account(new is necessary for free key access):
• Go to the Playground section on OpenAI and create a Secret Key under the API Keys section.
• Replace my API key with your new API key in line 7 of the main.py file.

10. Run the Project
Once the setup is complete:

Run the main.py file.
In the Python terminal, a link will be provided, which will open a browser to run the HTML file.
