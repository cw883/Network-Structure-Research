# Network-Structure-Research
Visualizing network structure seen in autonomous systems and how their behavior behaves in accordance with human network structure
Inspired by https://www.science.org/doi/10.1126/science.aau9735, where they attempt to measure the relationship strength vs relationship degrees of connection, we see an interesting pattern.
As people are further separated by degrees of connection, which is measured by how many friends of friends does it take to reach the other person from your node, we see that their relationship actually strengthens.  

Information Science Professor Yian Yin and I are interested in whether this U-shaped pattern is unique to human networks or can it also be found in other networks. We investigate one instance of this non-human network in an autonomous system network collected from Stanford over the course of 700 days. This network: "the graph of routers comprising the Internet can be organized into sub-graphs called Autonomous Systems (AS). Each AS exchanges traffic flows with some neighbors (peers). We can construct a communication network of who-talks-to- whom from the BGP (Border Gateway Protocol) logs." We then aggregated these 700 networks into one big network and drew conclusions from there. 

In doing this, we had to aggregate and clean all data from each of the networks, calculate tie range or the 2nd shortest path with the edge between nodes removed, and graph the resulting errorbars and plot consistent with how the article above.

One of the 700+ networks is included as an example, but the full data can be obtained from the link below.
Data from https://snap.stanford.edu/data/as-733.html

<img width="820" alt="Screenshot 2024-03-21 at 4 07 48 PM" src="https://github.com/cw883/Network-Structure-Research/assets/139663188/58c93b46-ef75-4e1e-8b43-d46d8b8d4fc5">
