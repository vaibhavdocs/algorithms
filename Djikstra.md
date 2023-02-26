Djikstra algorithms provides the shortest path between two points and shortest path refers to the 
cost to reach the endpoint from the source

There are 2 algorithms that provide the shortest path between vertices
i) Breadth first search -
                        Gives the shortest path betweeen verrtices based on no of vertices in betweeen them 
ii) Djikstra - 
                Shortest path based on the minimum cost to reach that the destination 



Implementation of Djikstra

Step 1 - Maintain the graph data structure with the help of hashtable
        Example - 
            graph["A"] = ["B", "C", "D"] // This gives us the neighbours of the A, not implemented exactly as shown here 
            graph["B"] = ["A", "E", "F"] // This gives us the neighbours of the B

            graph["A"] = [
                "B" : 6,  // 6 is the cost attached to AB edge
                "C" : 2   // 2 is the cost attached to BC edge
            ]

            graph["A"]["B"] = 6

