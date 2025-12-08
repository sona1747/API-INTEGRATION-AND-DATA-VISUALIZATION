# API-INTEGRATION-AND-DATA-VISUALIZATION

COMPANY  : CODTECH IT SOLUTIONS PVT.LTD

NAME : SONA K

INTERN ID : CT04DR1948  

DOMAIN : PYTHON PROGRAMMING

DURATION : 4 WEEKS

MENTOR NAME : NEELA SANTHOSH



Weather Data Fetching and Visualization Using Python – Project Description 

This project focuses on building a complete data-fetching and visualization system using Python by integrating a public API and converting the real-time weather data into an easy-to-understand graphical format. The main objective of this task is to demonstrate the ability to interact with web-based APIs, extract structured JSON data, process it programmatically, and present the information visually using Python libraries. The project uses the OpenWeatherMap API to obtain forecast information for any city and visualizes temperature trends using Matplotlib, a powerful data visualization library.

The first stage of this project involves understanding what an API is and how it works. An API (Application Programming Interface) allows two applications to communicate. In this case, Python acts as a client that sends a request to the OpenWeatherMap server, asking for weather data of a particular city. The server then responds with structured information in JSON format, which Python can easily parse and use. Before fetching the data, a user must generate an API key by creating a free account on the OpenWeatherMap website. This key ensures secure and authorized access to the API.

Next, the project uses Python’s requests library to send HTTP GET requests to the API endpoint. The response received contains a detailed weather forecast for the next several hours or days, including temperature, humidity, wind speed, and atmospheric conditions. For this task, we mainly focus on extracting temperature data and the corresponding timestamp for the next eight forecast periods (approximately 24 hours). The JSON structure returned by the API contains nested dictionaries, so Python’s list and dictionary handling techniques are applied to extract the required values.

After successfully fetching and processing the data, the next step is visualization. For this, Matplotlib is used. A line graph is chosen to represent temperature variation over time because it clearly shows how the temperature increases or decreases throughout the day. The timestamps are placed on the X-axis, and the temperature values are plotted along the Y-axis. Additional features like marker points, axis labels, chart title, and rotation of X-axis labels make the visualization more readable and attractive.

The final plot is displayed in Google Colab and also saved as a jpeg file . Saving the output graph is important because it serves as the deliverable for the internship task and provides evidence that the script works correctly. This image can also be used in reports and GitHub repositories.

This project teaches several practical skills essential for modern Python development. It demonstrates how to connect Python programs to external data sources, handle JSON structures, perform data preprocessing, and generate visual insights using plots. It also strengthens understanding of libraries like requests for networking and matplotlib for visualization. In addition, performing this project in Google Colab helps beginners learn how to run Python code online without installing software on their computer.

Overall, this task successfully illustrates the full workflow of a real-world data analytics project: data retrieval → data processing → visualization → reporting. The student not only gains programming skills but also learns how APIs power modern applications like weather apps, stock tracking systems, and smart dashboards. Completing this project shows the ability to build data-driven tools using Python and prepares the student for more advanced tasks such as automation, machine learning, and dashboard development.
