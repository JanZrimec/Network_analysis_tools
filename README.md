# Network_analysis_tools
Some Jupyter notebook scripts and functions based on DataCamp course: Network analysis in Python (Part 1).

The course data available on datacamp cannot be opened with NetworkX ver. 2.x, since pickled in nx ver. 1.11. Scripts save graph data to Pandas dataframe edgelist and nodelists (including node and edge attributes) and import to nx ver. 2.x. 

Original course data is also stored in folder datacamp_part1/.

# Export graph to dataframe and import from dataframe
Save graph data to to Pandas dataframe edgelist and nodelists with function in 'Networks_pytohn-datasets-19_7_18.ipynb':

`G_node_list_pd, G_edge_list_pd = graph_to_frames(G)`

Import graph from Pandas dataframe edgelist and nodelist with function in 'Networks_pytohn-datasets-20_7_18-import.ipynb':

`T = frames_to_graph(T_node_list, T_edge_list, create=nx.DiGraph())`
