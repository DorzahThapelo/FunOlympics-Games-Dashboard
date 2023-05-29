# FunOlympics-Games-Dashboard
To streamline the installation and deployment process of the prototype dashboard system in a production environment, we have provided a comprehensive set of procedures. By following the steps outlined below, you can successfully install and deploy the system.

## 1. Logical Packaging and Distribution
The Python Jupyter-based Power BI dashboard can be logically packaged as a Python project. The project can be organized into modules and sub-modules based on functionality. It is recommended to use a version control system like Git to manage the source code. The packaged project can be distributed as a zip file or uploaded to a code repository for deployment.

For distribution, the software can be made available through a website or a code repository 
such as GitHub. Users can download the source code or installation package from the website 
or repository to deploy it in their environment.

## 2. Licensing or Registration
The licensing requirements depend on the specific dependencies 
and libraries used in the project. You should review the licenses of the third-party libraries 
included in your project to ensure compliance. If you plan to distribute the dashboard 
commercially, you may need to obtain appropriate licenses or permissions. Otherwise, if it is 
an internal project, you might not require any specific licensing.

## 3. Technical Requirements

### a. Data Platform:
• The Power BI dashboard relies on data sources. It can connect to various data 
platforms such as SQL databases, Excel files, SharePoint lists, REST APIs, etc. The 
specific data platform requirements will depend on the data sources you intend to 
connect to.

### b. Hardware:
• The hardware requirements are typically dependent on the size and complexity of the 
dataset being processed and the number of users accessing the dashboard 
simultaneously. It is recommended to have sufficient processing power and memory 
to handle the data and user load effectively.

✓ Laptop-HP ProBook 440 G7 Notebook PC

✓ Processor - Intel Core i5 - 10210U processor. 1.6 GHz

✓ Installed RAM - 16.0 GB @2400 MHz

✓ Hard drive – 500 GB HDD

### c. Software:
• Python: The Power BI dashboard development will require Python as the programming 
language. Ensure that the appropriate version of Python is installed (e.g., Python 3.7+).

• Jupyter Notebook/JupyterLab: The dashboard development can be done within 
Jupyter Notebook or JupyterLab. Install the desired version of Jupyter to create and 
edit notebook files.

• Power BI: Power BI Desktop is required for creating and publishing the dashboard. 
Install the latest version of Power BI Desktop from the official Microsoft website.

### d. Programming Languages and Tools:
• Python: The primary programming language for the development of the Power BI 
dashboard.

• Jupyter Notebook/JupyterLab: Provides an interactive development environment for 
coding, visualizations, and documentation.

• Power BI: The Power BI Python SDK can be used for programmatically interacting 
with Power BI, such as creating datasets, reports, and dashboards.

• Libraries: Depending on the project requirements, you might utilize libraries like Pandas, 
NumPy, Matplotlib, Plotly, or other Python libraries for data processing, analysis, and 
visualization.

### e. Network/Operating System:
• The Power BI dashboard development is not tightly coupled with any specific operating 
system. It can be developed on Windows, macOS, or Linux. Ensure that the necessary 
network access and firewall rules are in place to connect to the required data sources

### f. Set Up The Environment
To ensure a smooth installation and deployment of the prototype dashboard system in a production environment, it is crucial to follow these steps to install and manage Python and its necessary libraries:

#### Python Installation:
Ensure that Python is installed in the production environment, preferably using the same version that was used during the development of the dashboard. You can download the Python installer from the official Python website (https://www.python.org) and follow the provided installation instructions for your specific operating system.

#### Python Environment:
It is recommended to set up a dedicated Python environment for the dashboard system. This helps in isolating the dependencies and prevents conflicts with other Python projects in the production environment. Virtual environments, such as virtualenv or conda environments, are commonly used for this purpose.
