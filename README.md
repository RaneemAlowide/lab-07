Lab 7 design pattern
Student name : Raneem Emad Alowide
Student ID: 2110171


#Q2: Change the number of created images to hundreds of thousands to experiment with the effects of the flyweight pattern? How many flyweights have been created?


#Q3: Explain how the flyweight design pattern reduces the number of objects stored in memory compared to storing all objects in memory?

Answer: The Flyweight design pattern reduces memory usage by sharing common data between multiple objects instead of storing duplicate data in each object. It achieves this by separating shared (intrinsic) data from unique (extrinsic) data, storing shared data centrally, and reusing it among objects. This minimizes the number of objects created and memory consumed, leading to better performance.
