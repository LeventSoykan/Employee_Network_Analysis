Employee Network Analysis
=========================

This project was created for DataCamp competition on network analysis. The aim of this study is to create an employee network using message data and use this network to gain insight on relationships among employess and departments. Below are a few important points.

Data
------------

Data is provided in 2 separate files: "employees.csv" and "messages.csv"

* Messages has information on the sender, receiver, time and message length
* Employees has information on each employee including id, department, location and age. 

Analysis
------------

The project includes several features to analyze the employee network:

*   **Network visualization**: A non directional weighted graph  is produced using the NetworkX library. The graph nodes contain information on different aspects of the network, such as the departments or ages of the employees.

*   **Data Analysis**: Relationships between messages and age, department and date are explored using graph data.  
    
*   **Centrality metrics**: Several centrality metrics are calculated including degree centrality, betweenness centrality. These metrics are to identify the most important employees in the network.
    
Installation
------------

To install the required libraries, you can use pip:

Copy code

`pip install networkx pandas matplotlib`

You will also need to download the data files from the `data` folder in this repository.

Usage
-----

The main entry point for the project is the `employee_network_analysis.py` script. You can run it from the command line:

Copy code

`python employee_network_analysis.py`

This will load the data, analyze the network, and produce several graphs and metrics. 
    

License
-------

This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
------------

Contributions are welcome! If you want to contribute to this project, please fork the repository and submit a pull request with your changes.
