Employee Network Analysis
=========================

This project provides a set of tools to analyze the network of relationships between employees in a company. It is built using Python and several libraries for data analysis and visualization, including NetworkX, Pandas, and Matplotlib.

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

This will load the data, analyze the network, and produce several graphs and metrics. You can customize the behavior of the script by modifying the parameters in the `config.json` file.

Features
--------

The project includes several features to analyze the employee network:

*   **Network visualization**: The script can produce a graph of the network using the NetworkX library. The graph can be customized to highlight different aspects of the network, such as the departments or the job titles of the employees.
    
*   **Centrality metrics**: The script calculates several centrality metrics for each employee, including degree centrality, betweenness centrality, and eigenvector centrality. These metrics can be used to identify the most important employees in the network.
    
*   **Community detection**: The script can perform community detection using the Louvain algorithm. This algorithm groups the employees into clusters based on their network connections. The clusters can be visualized and analyzed to identify patterns and relationships between employees.
    

License
-------

This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
------------

Contributions are welcome! If you want to contribute to this project, please fork the repository and submit a pull request with your changes.
