### ChatGPT-Clone Project Setup Instructions

**1. Install Node.js**  
Download and install the LTS version from [Node.js](https://nodejs.org/). Verify installation by running `node -v` in the terminal. If issues occur, delete the `node_modules` folder and `package-lock.json`, then run `npm install` to reinstall dependencies.

**2. Install Tailwind CSS Extension in VS Code**  
Open VS Code, go to the Extensions panel (`Ctrl+Shift+X`), search for "Tailwind CSS IntelliSense," and click Install.

**3. Install Flask and PyMongo Globally**  
Open the terminal in VS Code and run `pip install flask pymongo`. Verify installation with `pip list` to ensure both packages are installed.

**4. Configure VS Code for Python**  
Open the Command Palette (`Ctrl+Shift+P`), type "Python: Select Interpreter," and choose the system-wide Python interpreter.

**5. Install MongoDB Compass**  
Download MongoDB Compass from [here](https://www.mongodb.com/products/compass). Open it and use the connection string from line 13 of `main.py` to connect to the database. You can view and modify data directly in MongoDB Compass.

**6. Set Up OpenAI API Key**  
Create a new OpenAI account and generate an API key under the API Keys section. Replace the placeholder key in line 7 of `main.py` with your new key.

**7. Run the Project**  
Run `main.py` in the terminal and use the provided link to open the project in a browser.
