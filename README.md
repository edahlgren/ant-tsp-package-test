# Data science: Using real-life ant colony behavior to efficiently search a dataset

This demo simulates a real ant colony's foraging behavior to search for the shortest tour of a connected data points in a dataset. [[1](http://www.aco-metaheuristic.org/aco-code/public-software.html)]

Ants are decentralized, and have limited memory and capabilities. Yet through simple communication mechanisms, a colony of ants can efficiently solve complex problems like predator evasion and shortest path finding. If we mimic the behavior of ant colonies in computer systems, we can create efficient, scalable, and distributed algorithms for searching, sorting, and classifying data. [[2](https://link.springer.com/content/pdf/10.1007%2Fs10994-010-5216-5.pdf)]

In this demo, you can experiment with a simulated ant colony to find solutions to the traveling salesman problem: to solve the problem you need to find the shortest route a salesman should take to tour a region so he visits every city.

The traveling salesman problem is an example of an important general problem: how to efficiently make a complete tour of a network. For example, the problem can be used to efficiently route internet data, schedule package deliveries, manage warehouse operations, and even to analyze genetically inherited DNA markers in plants. [[3](https://www.intechopen.com/books/traveling-salesman-problem-theory-and-applications/traveling-salesman-problem-an-overview-of-applications-formulations-and-solution-approaches)], [[4](https://support.sas.com/resources/papers/proceedings12/160-2012.pdf)]

To test the demo, three real-life datasets are included: the coordinates of cities in Djibouti (Africa), Qatar (Middle East), and Luxembourg (Europe). [[5](http://www.math.uwaterloo.ca/tsp/world/countries.html)] Featured is the "MAX-MIN" ant colony system created by Thomas Stützle and Holger H. Hoos. [[6](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=8D8BB000CCFB5296D609EA6EC9AB226B?doi=10.1.1.127.3897&rep=rep1&type=pdf)]

Vote for us to feature more demos of ant colony algorithms and applications.

```
$ ./build.sh && ./shell.sh
```
