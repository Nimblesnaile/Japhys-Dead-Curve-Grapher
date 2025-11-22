# Japhys-Dead-Curve-Grapher
This program analyzes lifespan data for a group of flies and generates a survival curve. The result is a clear visual representation of the lifespan distribution for the specified genotype or group.

There is no currently only support for data gathered in a fashion exactly like the template. Having no gender/genotype is supported, and as long as fly counts are underneath the labels, the program will produce a graph.

1. Create a cleaned google sheet with names above each column of death counts.
2. Download it as a csv.
3. Mount it to the google notebook by changing the file location within the ipynb script, labelled <# CHANGE THIS TO YOUR CSV>.
4. Connect to a runtime and click Run All in the top left.
5. Your graph(s) will be produced in the output.
