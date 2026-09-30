1. Create the project directory
mkdir WebCraft
cd WebCraft
2. Open the project in VS Code
code .
3. Create the HTML file

Create:

index.html

Paste the complete WebCraft HTML code into index.html and save it.

The file already contains the HTML, CSS, and JavaScript, so no additional dependencies are required.

4. Run the website

For a simple local preview:

start index.html

For a proper local development server, use:

python -m http.server 5500

Then open:

http://localhost:5500

If python is not recognized:

py -m http.server 5500
5. Stop the server

Press:

Ctrl + C
Project structure
WebCraft/
└── index.html
Important

For this particular HTML file, you do not need:

npm install
npm run dev
npm start
